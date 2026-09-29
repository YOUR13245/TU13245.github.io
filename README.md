# nexura1
plataforma numero 1
# NEXURA

<div align="center">

![NEXURA Logo](public/brand/nexura-icon.svg)

**Tu contenido. Tu comunidad. En vivo.**

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](CHANGELOG.md)
[![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)](#instalación)
[![License](https://img.shields.io/badge/license-Proprietary-red.svg)](#licencia)

[Documentación](#documentación) • [Instalación](#instalación) • [Desarrollo](#desarrollo)

</div>

---

## 🎯 Descripción

NEXURA es una plataforma de streaming en vivo profesional, gratuita para usuarios y preparada para escalar. Permite a los creadores transmitir contenido en vivo, interactuar con su audiencia mediante chat en tiempo real, y construir comunidades alrededor de su contenido.

## ✨ Características

### 🎥 Streaming en Vivo
- Transmisión en vivo con OBS/RTMP
- Reproductor HLS profesional con baja latencia
- Detección automática de estado LIVE/OFFLINE
- Viewer count en tiempo real
- Stream keys con hash seguro

### 💬 Chat en Tiempo Real
- Chat en vivo con moderación completa
- Sistema de moderadores y VIPs
- Slow mode y followers-only mode
- Filtro de palabras y anti-spam
- Emotes y badges personalizados

### 📹 Video On Demand
- Grabación automática de streams
- Procesamiento de videos
- Generación de thumbnails
- Clips de 5-60 segundos
- Biblioteca de contenido

### 🔍 Descubrimiento
- Búsqueda global con sugerencias
- Sistema de categorías
- Recomendaciones personalizadas
- Tendencias y contenido destacado

### 👥 Comunidad
- Perfiles profesionales
- Sistema de seguidores
- Notificaciones en tiempo real
- Analytics y estadísticas

### 🛡️ Seguridad
- Autenticación segura
- Sistema de roles (OWNER, ADMIN, MODERATOR, USER)
- Moderación de contenido
- Rate limiting y anti-abuso

## 🛠️ Stack Tecnológico

### Frontend
- **Framework**: React 18
- **Lenguaje**: TypeScript
- **Estilos**: Tailwind CSS
- **Routing**: React Router v6
- **Icons**: Lucide React
- **Video**: hls.js (preparado)
- **Build**: Vite

### Backend (Preparado)
- **Runtime**: Node.js
- **Framework**: Express/Next.js
- **ORM**: Prisma
- **Base de datos**: PostgreSQL
- **Cache**: Redis
- **Streaming**: MediaMTX
- **Storage**: S3-compatible

## 📦 Instalación

### Requisitos
- Node.js 18+
- npm 9+

### Desarrollo Local

```bash
# Clonar repositorio
git clone https://github.com/tu-organizacion/nexura.git
cd nexura

# Instalar dependencias
npm install

# Ejecutar en desarrollo
npm run dev

# Abrir en navegador
# http://localhost:5173
```

### Producción

```bash
# Build para producción
npm run build

# Preview de producción
npm run preview
```

## 👥 Usuarios de Prueba

| Rol | Email | Contraseña |
|-----|-------|------------|
| OWNER | owner@nexura.live | Owner@12345 |
| USER | user@nexura.live | User@12345 |

**⚠️ IMPORTANTE**: Cambiar estas credenciales antes de usar en producción.

## 📚 Documentación

- [Informe de Auditoría](AUDIT_REPORT.md) - Estado actual del proyecto
- [Guía de Despliegue](docs/DEPLOYMENT.md) - Instrucciones de producción
- [Runbook](docs/RUNBOOK.md) - Procedimientos operativos

## 🚀 Estado del Proyecto

### Implementado ✅
- ✅ Sistema de autenticación completo
- ✅ Gestión de usuarios y roles
- ✅ Branding NEXURA (logo, favicon, colores)
- ✅ Landing page profesional
- ✅ Navegación responsive
- ✅ Sistema de notificaciones toast
- ✅ Base de datos con localStorage
- ✅ Build optimizado

### Pendiente ⚠️
- ⚠️ Dashboard del creador
- ⚠️ Perfiles de usuario
- ⚠️ Sistema de streaming completo
- ⚠️ Chat en tiempo real
- ⚠️ VOD y clips
- ⚠️ Búsqueda global
- ⚠️ Sistema de categorías
- ⚠️ Notificaciones push
- ⚠️ Analytics
- ⚠️ Monetización

## 🔒 Seguridad

NEXURA implementa múltiples capas de seguridad:

- ✅ Hash de contraseñas
- ✅ Tokens de sesión con expiración
- ✅ Validación de inputs
- ✅ Roles y permisos
- ✅ Auditoría de acciones
- ✅ Prevención de duplicados

### Pendiente
- ⚠️ 2FA para cuentas críticas
- ⚠️ Rate limiting avanzado
- ⚠️ CSRF tokens
- ⚠️ Validación de URLs
- ⚠️ Sanitización de contenido

## 📊 Métricas

- **Módulos**: 1381
- **Tamaño JS**: 206.60 KB (63.51 KB gzipped)
- **Tamaño CSS**: 28.17 KB (5.65 KB gzipped)
- **Tiempo de build**: ~3.5 segundos
- **Errores**: 0

## 🤝 Contribuir

Este es un proyecto privado. Para contribuciones:

1. Contactar a dev@nexura.live
2. Firmar acuerdo de confidencialidad
3. Seguir guías de estilo de código
4. Escribir tests para nuevas funcionalidades
5. Actualizar documentación

## 📄 Licencia

Copyright © 2024 NEXURA. Todos los derechos reservados.

Este software es propietario y confidencial. No se permite su uso, copia, modificación o distribución sin autorización explícita.

## 📞 Soporte

- **Email**: soporte@nexura.live
- **Documentación**: [AUDIT_REPORT.md](AUDIT_REPORT.md)

---

<div align="center">

**Hecho con ❤️ por el equipo NEXURA**

[Website](https://nexura.live) • [Documentation](#documentación) • [Support](#soporte)

</div>
