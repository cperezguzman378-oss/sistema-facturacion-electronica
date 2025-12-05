# Sistema de Facturacion Electronica

Sistema completo de facturacion electronica con modulos JavaScript integrados

## Caracteristicas Principales

- 6 Paginas HTML completamente funcionales
- 43 Funciones JavaScript organizadas en 5 modulos
- Calculos automaticos (IVA, retenciones, totales)
- Validaciones en tiempo real (email, NIT, moneda)
- Gestion de DTEs (Documentos Tributarios Electronicos)
- Control de contingencias y modo diferido
- Almacenamiento local de datos
- Exportacion de reportes

## Estructura de Archivos

```
sistema-facturacion-electronica/
├── pages/                    # Paginas HTML
│   ├── dashboard.html
│   ├── crear-dte.html
│   ├── gestion-dte.html
│   ├── invalidacion-dte.html
│   ├── contingencias.html
│   └── configuracion.html
├── js/                       # Modulos JavaScript
│   ├── modulo-calculadora.js
│   ├── modulo-validador.js
│   ├── modulo-tabla.js
│   ├── modulo-almacenamiento.js
│   └── modulo-notificaciones.js
├── css/                      # Estilos
├── docs/                     # Documentacion
├── .gitignore
├── README.md
└── SETUP.md                  # Guia de instalacion
```

## Rapido Inicio

### 1. Clonar el repositorio

```bash
git clone https://github.com/cperezguzman378-oss/sistema-facturacion-electronica.git
cd sistema-facturacion-electronica
```

### 2. Agregar tus archivos

Copia tus archivos a las carpetas apropiadas:

```bash
cp tus-archivos-html pages/
cp tus-archivos-css css/
cp tus-archivos-js js/
```

### 3. Confirmar cambios

```bash
git add .
git commit -m "Agregar archivos del sistema"
git push origin main
```

## Modulos JavaScript

### Modulo Calculadora (8 funciones)
- calcularIVA() - Calcula IVA al 13%
- calcularRetencion() - Calcula retencion al 1%
- calcularSubtotal() - Suma de items
- calcularTotal() - Total final
- formatearMoneda() - Formato de moneda

### Modulo Validador (10 funciones)
- validarEmail() - Valida formato de email
- validarNIT() - Valida NIT salvadoreno
- validarMoneda() - Valida cantidad
- validarFecha() - Valida fechas

### Modulo Tabla (10 funciones)
- buscarEnTabla() - Busqueda rapida
- filtrarPor() - Filtrado de datos
- ordenarColumna() - Ordenamiento
- paginar() - Paginacion
- exportarCSV() - Exportacion

### Modulo Almacenamiento (10 funciones)
- guardarDTE() - Guarda DTEs
- obtenerDTE() - Recupera DTEs
- guardarCliente() - Gestiona clientes
- guardarConfiguracion() - Guarda datos empresa

### Modulo Notificaciones (5 funciones)
- mostrarExito() - Notificacion de exito
- mostrarError() - Notificacion de error
- mostrarAdvertencia() - Advertencia
- mostrarInfo() - Informacion

## Paginas HTML Incluidas

### 1. Dashboard
Panel de control con KPIs, graficos y actividad reciente

### 2. Crear DTE
Formulario para crear nuevos documentos tributarios electronicos

### 3. Gestion de DTE
Busqueda, filtros, ordenamiento y exportacion de DTEs

### 4. Invalidacion de DTE
Proceso para anular o invalidar DTEs

### 5. Contingencias
Registro de contingencias y modo diferido

### 6. Configuracion
Datos de la empresa y parametros del sistema

## Instalacion Detallada

Para instrucciones mas detalladas, consulta el archivo SETUP.md

## Licencia

Este proyecto esta disponible bajo licencia MIT.

## Autor

cperezguzman378-oss

## Soporte

Para reportar problemas o sugerencias, abre un issue en GitHub.
