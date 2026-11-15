# SIAAC UNL

Sistema Inteligente de Alerta de Animales en Cultivos.

## Estructura

- `backend/`: API Django, autenticación, cultivos, zonas y detección YOLO/OpenCV.
- `frontend/`: aplicación React/Vite.
- `hardware/`: firmware ESP32 y servicios Raspberry Pi.
- `database/`: esquema y datos iniciales.
- `deploy/`: configuración de despliegue.

## Puesta en marcha

1. Copiar `backend/.env.example` a `backend/.env` y completar la configuración.
2. Instalar dependencias del backend con `backend/requirements.txt`.
3. Instalar dependencias del frontend con `npm install` dentro de `frontend/`.
4. Ejecutar `docker compose up` o iniciar backend y frontend por separado.

Las carpetas de dependencias, compilaciones y datos locales no forman parte de esta copia.
