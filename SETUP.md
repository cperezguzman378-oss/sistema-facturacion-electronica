# 🚀 GUÍA DE CONFIGURACIÓN - TERMINAL

## Paso 1: Verificar Git instalado

Abre tu terminal (CMD, PowerShell o Git Bash) y ejecuta:

```bash
git --version
```

Si ves una versión, significa que Git está instalado. Si no, descárgalo desde: https://git-scm.com

---

## Paso 2: Configurar Git (si es primera vez)

Ejecutar estos comandos:

```bash
git config --global user.name "cperezguzman378-oss"
git config --global user.email "tu-email@gmail.com"
```

---

## Paso 3: Clonar el Repositorio

Navega a donde quieras guardar el proyecto y ejecuta:

```bash
git clone https://github.com/cperezguzman378-oss/sistema-facturacion-electronica.git
cd sistema-facturacion-electronica
```

---

## Paso 4: Agregar tus Archivos

Copia tus archivos HTML, CSS y JS a las carpetas correctas:

- **HTML** → `pages/`
- **CSS** → `css/`
- **JS** → `js/`

Luego ejecuta:

```bash
git add .
```

---

## Paso 5: Crear Commit

```bash
git commit -m "Agregar archivos del sistema de facturación electrónica"
```

---

## Paso 6: Subir a GitHub

```bash
git push origin main
```

Si te pide autenticación, sigue las instrucciones.

---

## ¿Listo? ✅

Verifica en: https://github.com/cperezguzman378-oss/sistema-facturacion-electronica
