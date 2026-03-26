# Bmanager Updates

Este repositorio se utiliza exclusivamente para la distribución de versiones compiladas de Bmanager.

## 📦 Contenido

* Archivos .zip de cada versión en "Releases"
* Archivo `update.json` con la última versión disponible

## 🔄 Sistema de actualizaciones

La aplicación Bmanager consulta el archivo `update.json` para:

1. Verificar la versión más reciente
2. Descargar la actualización desde Releases
3. Ejecutar el actualizador (updater.exe)

## 🚀 Proceso para subir una nueva versión

1. Compilar la nueva versión de Bmanager
2. Comprimir todos los archivos en `Bmanager.zip`
3. Crear un nuevo Release (ej: v1.1.0)
4. Subir el archivo `.zip`
5. Actualizar `update.json` con la nueva versión y URL

## ⚠️ Notas importantes

* No subir código fuente en este repositorio
* No modificar archivos manualmente fuera del flujo de releases
* Mantener consistencia en las versiones

## 🧠 Autor

Proyecto desarrollado por [William Muñoz](https://www.linkedin.com/in/william62185/)
