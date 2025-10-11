# 🔐 GateKeeper  
## Sistema Integral de Gestión de Accesos

![Estado](https://img.shields.io/badge/🚀_En_Producción-green) ![Licencia](https://img.shields.io/badge/Licencia-🔒_Privada-red) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-Auth_%26_DB-3ECF8E?logo=supabase&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![n8n](https://img.shields.io/badge/n8n-Automation-orange?logo=n8n&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Render](https://img.shields.io/badge/Render-0099FF?logo=render&logoColor=white)

## 📋 Descripción del Sistema
Control centralizado de accesos corporativos con administración de usuarios/roles, auditoría en tiempo real y políticas de seguridad.

## 🛠 Stack Tecnológico
**Backend:** Node.js + Express, JWT/RBAC  
**Base de Datos:** PostgreSQL **Supabase** (Auth + RLS + Audit)  
**Frontend:** HTML5/CSS3/JS  
**Automatizaciones:** **n8n** (altas/bajas/avisos)

## 🖥️ Infraestructura
**Render (Producción):**
- `backend`, `web`, `n8n` en **Docker**
- HTTPS + env seguros

**Supabase:**
- Auth (roles), RLS por recurso, storage  
- Backups + métricas

**Monitoreo:**
- Logs + alertas + métricas

## 🖥️ Estructura del Proyecto
📁 GateKeeper  
├── 📂 api/ (microservicios)  
│   ├── auth/      # Autenticación  
│   ├── access/    # Control de accesos  
│   └── admin/     # Administración  
├── 📂 core/  
│   ├── models/    # Entidades  
│   └── services/  # Reglas  
├── 📂 web/  
│   ├── dashboard/  
│   └── admin/  
└── 📂 docs/

## 🔍 Características Clave
- Gestión de usuarios/roles/permisos  
- Auditoría y trazabilidad  
- Integración con n8n para onboarding/offboarding  
- Reportes ejecutivos

## 🛡️ Seguridad Avanzada
- JWT + rotación de tokens  
- RLS granular  
- Registros de auditoría  
- Política de contraseñas estricta

## 📊 Métricas de Rendimiento
- 15k req/s (objetivo)  
- Latencia <200ms  
- 99.99% uptime

## 📝 Gestión de Versiones
- GitFlow + CI/CD en Render  
- Versionado semántico

💡 **Notas Técnicas:**  
✅ Enfoque Zero-Trust (por módulos)  
✅ Integración con n8n (eventos security)  
✅ Supabase Auth/RLS/Audit  
✅ Endpoints listos para SSO

"Donde la seguridad se encuentra con la innovación."

## 📬 Contacto Corporativo
**Julián Alberto Ramírez** – WoMo Soluciónˢ  
<img width="222" height="29" alt="Logo WSˢ" src="https://github.com/user-attachments/assets/24519130-f605-4762-a4f2-374c450f2b64" />

📅 **Control de Versiones**  
![Versión](https://img.shields.io/badge/Versión-1.1.0-blue) ![Actualizado](https://img.shields.io/badge/Actualizado-Jul_2025-green)

