# Observability Tools

Este proyecto contiene herramientas y configuraciones para la observabilidad de sistemas.

## Estructura del proyecto
- `compose.yaml`: Archivo de configuración para levantar los servicios necesarios mediante Docker Compose.

## Uso
1. Clona este repositorio.
2. Asegúrate de tener Docker y Docker Compose instalados.
3. Ejecuta:
   ```zsh
   docker compose up -d
   ```
   Esto levantará todos los servicios definidos en `compose.yaml`.

## Requisitos
- Docker
- Docker Compose

## Personalización
Modifica el archivo `compose.yaml` para agregar, quitar o configurar servicios según tus necesidades de observabilidad.

## Licencia
Este proyecto se distribuye bajo la licencia MIT.
