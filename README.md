# 🛡️ Confidata 🛡️

[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js->=18-brightgreen)](https://nodejs.org/)
[![Docker](https://img.shields.io/badge/Docker-ready-blue)](https://www.docker.com/)

**Confidata** es una plataforma avanzada para la **gestión de protección de datos personales en Ecuador**. Permite a las organizaciones administrar consentimientos, permisos y datos de manera segura, mantener a los usuarios informados sobre cambios y garantizar el cumplimiento de la normativa vigente. Incluye auditoría completa, control de accesos basado en roles, notificaciones automáticas y APIs para integrar con sistemas existentes, ofreciendo un entorno confiable y transparente para la privacidad de la información.

> 💡 *Gestiona consentimientos, administra información personal, envía notificaciones automáticas y asegura trazabilidad completa de manera sencilla y confiable.*

---

## ✨ Características Principales

- ✅ **Gestión de Consentimientos:** Registro y seguimiento de permisos de usuarios.  
- ✅ **Administración de Datos Personales:** Control centralizado y seguro.  
- ✅ **Sistema de Notificaciones:** Alertas automáticas ante cambios de consentimientos o situaciones críticas.  
- ✅ **Auditoría y Trazabilidad:** Historial completo de accesos y operaciones.  
- ✅ **API RESTful:** Integración sencilla con sistemas corporativos.  

---

## 🔒 Seguridad y Cumplimiento

- 🔐 Cifrado de datos en tránsito y en reposo.  
- 🛡️ Autenticación multifactor (2FA).  
- 🗝️ Control de acceso basado en roles (RBAC).  
- 📈 Monitoreo de seguridad en tiempo real y alertas.  
- ⚖️ Cumplimiento legal y mejores prácticas internacionales (referencia GDPR).  

---

## 🛠️ Stack Tecnológico

**Frontend:**  
- React  
- TypeScript  
- React Query  

**Backend:**  
- NestJS  
- MongoDB  
- Redis  
- Docker  
- JWT  

---

## 🚀 Instalación Rápida

### Prerrequisitos
- Node.js >= 18  
- Docker y Docker Compose  
- PostgreSQL >= 14  
- Redis >= 6  

### Pasos

```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/Confidata.git
cd Confidata

# Configurar variables de entorno
cp .env.example .env
# Editar .env según tus configuraciones

# Instalar dependencias Backend
npm install

# Instalar dependencias Frontend
cd frontend
npm install
cd ..

# Levantar servicios con Docker
docker-compose up -d

# Ejecutar migraciones y seed
npm run db:migrate
npm run db:seed

# Iniciar Backend
npm run start:dev

# Iniciar Frontend
cd frontend
npm run dev
