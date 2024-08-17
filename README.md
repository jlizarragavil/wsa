# Web Security Audit (WSA)

![Web Security Audit](https://img.shields.io/badge/version-1.0.0-blue.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg)

## Descripción

**Web Security Audit (WSA)** es un script de auditoría de seguridad web que automatiza la recopilación de información y análisis de vulnerabilidades en sitios web. Utiliza herramientas populares como **Katana**, **Nuclei**, **Subfinder**, y **SecretFinder** para realizar un escaneo completo, identificando vulnerabilidades y configuraciones inseguras.

## Características

- Enumeración de subdominios.
- Escaneo de URLs con **Katana** para recolectar endpoints.
- Análisis de URLs usando **Nuclei** con múltiples tags de vulnerabilidad.
- Extracción de URLs con parámetros sospechosos.
- Integración con **SecretFinder** para descubrir secretos expuestos en archivos `.js`.

## Requisitos

- **Bash**: Asegúrate de estar usando **Bash** como tu shell.
- **Katana**: Herramienta de escaneo web.
- **Nuclei**: Herramienta para encontrar vulnerabilidades.
- **Subfinder**: Herramienta para enumerar subdominios.
- **SecretFinder**: Herramienta para encontrar secretos expuestos en archivos JS.
- **httpx-toolkit**: Herramienta para validar subdominios.

## Instalación

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
   ```
Asegúrate de que el script tenga permisos de ejecución:

   ```bash
   chmod +x WebSecurityAudit.s
   ```
   
