# 🌒 Atlas Viviente del Rostro: Códice de lo Invisible

🕯️ *Donde la carne, la forma y el alma médica convergen — un oráculo quirúrgico de visiones profundas, nacido del metal y la luz resonante, para trazar los caminos de la curación con el arte sutil de los antiguos sabios.*

---

# Asistente Quirúrgico Maxilofacial con IA

Este sistema integra segmentación médica, inteligencia artificial, historia clínica y recomendaciones quirúrgicas para apoyar decisiones en cirugía maxilofacial.

## Módulos

- **Frontend React**: Interfaz para ingresar datos, visualizar resultados y descargar informes.
- **Backend FastAPI**: Procesamiento clínico, autenticación, base de datos, auditoría.
- **Base de datos**: SQLite local.
- **Autenticación**: HTTP Basic con roles (`admin`, `medico`, `consulta`).

## Requisitos

- Node.js 18+
- Python 3.9+

## Instalación

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
```

```bash
cd frontend
npm install
npm run dev
```

## Seguridad

- Acceso por usuario y contraseña.
- Auditoría de accesos.
- Roles diferenciados por permisos.
