# Changelog

Todos los cambios notables de este proyecto serán documentados en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/),
y este proyecto adhiere al [Versionado Semántico](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Planificado
- Análisis de productos geográficos
- Análisis de órdenes judiciales  
- Versión móvil nativa del dashboard
- Sistema de analíticas integrado

---

## [1.0.0-beta] - 2024-12-XX

### 🎉 Lanzamiento Inicial

Primera versión beta del Portal de Datos AARIMO con funcionalidades core implementadas.

### ➕ Agregado

#### **Identidad Visual Corporativa**
- Implementación de paleta de colores oficial AARIMO
  - Verde claro: `#96b19c`
  - Verde oscuro: `#354634` 
  - Naranja corporativo: `#d4743e`
- Tipografía unificada con Rubik Light (peso 300)
- Logo oficial integrado desde repositorio GitHub
- Favicon personalizado con opciones de diseño (iniciales "AA" y hoja amazónica)

#### **Componentes del Portal**

**Header Personalizado**
- Fondo verde corporativo (#96b19c)
- Logo de 80px de altura con enlace a GitHub
- Título "Portal de Datos de la AARIMO" 
- Fuente Rubik Light aplicada
- Diseño responsive con flexbox

**Footer Profesional**
- Información de contacto: `tecnicosigaarimo@gmail.com`
- Ícono LinkedIn funcional: https://www.linkedin.com/company/aarimo/
- Copyright 2024 AARIMO
- Consistencia visual con header
- Efectos hover implementados

**Dashboard/Catálogo**
- Tema personalizado aplicado con colores corporativos
- Fuente alternativa: Noto Sans (más similar a Rubik disponible)
- Colores optimizados para legibilidad y accesibilidad
- URL de acceso: `/#dashboard-section`

#### **Sistema de Formularios**

**Formulario de Ingreso de Datos**
- 6 secciones estructuradas:
  1. Datos del Responsable
  2. Identificación del Dato
  3. Tipo de Dato  
  4. Metadatos Asociados
  5. Seguridad y Compartición
  6. Carga de Datos
- Manual completo integrado con ejemplos prácticos
- Configuración visual consistente con colores corporativos

**Formulario de Solicitud de Datos Restringidos**
- Proceso estructurado para acceso controlado
- 4 secciones principales:
  1. Información del Solicitante
  2. Detalles de la Solicitud
  3. Propósito de Uso
  4. Acuerdo de Confidencialidad
- Tiempo de respuesta: 2-3 días hábiles
- Sistema de trazabilidad implementado

#### **Recursos y Documentación**
- Tarjetas interactivas con efectos hover
- Enlaces directos a recursos:
  - Manual de Ingreso de Datos
  - Guía de Solicitud de Datos Restringidos
  - Soporte Técnico
- Diseño con bordes verdes corporativos
- Estructura responsive

#### **Banner Principal y Gestión de Imágenes**
- Sistema de gestión de imágenes colaborativo
- Invitación para banco de imágenes con botón funcional
- CSS personalizado para eliminar espacios no deseados
- Integración con correo electrónico para envío de fotos

#### **Sistema de Comunicación por Email**
- Correo HTML de presentación con estructura basada en tablas
- Diseño responsive para móviles y desktop  
- Estilos inline para máxima compatibilidad
- Logo optimizado con múltiples fallbacks
- Botones de acción funcionales:
  - Acceso al portal
  - Envío de retroalimentación
  - Contribución al banco de imágenes
- Código condicional para Outlook (MSO)
- Enlaces mailto pre-configurados

#### **Solución para Dispositivos Móviles**
- Página de notificación HTML independiente
- Mensaje informativo sobre desarrollo en curso
- Redirección clara a versión de escritorio
- Diseño limpio y profesional
- Implementación de identidad visual corporativa

### 🎨 Mejorado

#### **Responsividad y Accesibilidad**
- Media queries implementadas para múltiples dispositivos
- Adaptación automática de layouts con flexbox
- Contraste adecuado (WCAG 2.0) en todos los elementos
- Estructura semántica HTML implementada
- Alt text descriptivo en todas las imágenes
- Navegación por teclado optimizada

#### **Compatibilidad Cross-Browser**
- Optimización específica para Chrome, Firefox, Safari, Edge
- Soporte robusto para Outlook en correos HTML
- Fallbacks implementados para fuentes no disponibles
- Testing en múltiples plataformas de correo electrónico

#### **Botones y Elementos Interactivos**
- Estandarización de todos los botones:
  - Color: `#d4743e` (naranja corporativo)
  - Border-radius: 4px
  - Padding: 12px 25px
  - Fuente: Rubik Light
- Efectos hover implementados en todos los elementos interactivos
- Transiciones suaves (0.3s ease)

### 🔧 Configurado

#### **ArcGIS Hub Theme Settings**
```css
Global Nav Background: #ffffff
Global Nav Text: #353535
Header Background: #96b19c  
Header Text: #354634
Body Background: #ffffff
Body Text: #3f573e
Body Links: #d4743e
Base Font: Rubik Light
Heading Font: Rubik Light
```

#### **Custom CSS Implementado**
- `.banner-row-aarimo` para eliminación de espacios
- `.footer-background` para estilizado del pie de página
- Estilos responsive con media queries
- Código condicional para compatibilidad MSO

### 📝 Documentado

#### **Manuales de Usuario Creados**
- Manual de Ingreso de Datos (6 secciones detalladas)
- Manual de Solicitud de Datos Restringidos (proceso completo)
- Manual de Soporte Técnico (procedimientos y contacto)

#### **Documentación Técnica**
- Guía de colores corporativos con códigos hexadecimales
- Especificaciones de fuentes y pesos
- Código CSS personalizado documentado
- Configuraciones de ArcGIS Hub paso a paso

### 🚀 URLs de Producción

- **Portal Principal**: https://alianza-amazonica-aarimo-szf.hub.arcgis.com/
- **Dashboard**: https://alianza-amazonica-aarimo-szf.hub.arcgis.com/#dashboard-section
- **Manuales**:
  - Ingreso de Datos: `/pages/manual-de-ingreso-de-datos`
  - Datos Restringidos: `/pages/solicitud-de-datos-restringidos`  
  - Soporte Técnico: `/pages/soporte-técnico`

### 📞 Información de Contacto

- **Email Técnico**: tecnicosigaarimo@gmail.com
- **LinkedIn**: https://www.linkedin.com/company/aarimo/
- **Tiempo de Respuesta**: 24 horas hábiles
- **Technical Lead**: bryan.ramirez@fzs.org

---

## [0.1.0] - 2024-11-XX

### ➕ Agregado
- Configuración inicial del repositorio
- Estructura básica de ArcGIS Hub
- Configuración de dominio y accesos básicos

### 📝 Documentado  
- Definición de requerimientos iniciales
- Establecimiento de objetivos del proyecto

---

## Tipos de Cambios

- `➕ Agregado` para nuevas funcionalidades
- `🔄 Cambiado` para cambios en funcionalidades existentes  
- `❌ Obsoleto` para funcionalidades que se eliminarán próximamente
- `🗑️ Eliminado` para funcionalidades eliminadas
- `🔧 Arreglado` para corrección de errores
- `🔒 Seguridad` en caso de vulnerabilidades
- `🎨 Mejorado` para mejoras en diseño o UX
- `📝 Documentado` para cambios en documentación
- `🚀 Implementado` para despliegues y configuraciones de producción

---

## Información de Versiones

### Versionado Semántico
Este proyecto sigue el [Versionado Semántico](https://semver.org/). En resumen:
- **MAJOR.MINOR.PATCH** (ej: 1.0.0)
- **MAJOR**: Cambios incompatibles en la API
- **MINOR**: Funcionalidades agregadas de manera compatible  
- **PATCH**: Correcciones de errores compatibles

### Estados de Versión
- **alpha**: Versión muy temprana, funcionalidades básicas
- **beta**: Versión de prueba, funcionalidades principales completas
- **rc** (release candidate): Versión candidata para producción
- **stable**: Versión estable para producción

---

## Enlaces Útiles

- [Portal de Datos AARIMO](https://alianza-amazonica-aarimo-szf.hub.arcgis.com/)
- [Repositorio GitHub](https://github.com/AARIMO/portal-datos)
- [Issues y Feature Requests](https://github.com/AARIMO/portal-datos/issues)
- [Documentación Completa](https://github.com/AARIMO/portal-datos/wiki)
- [Guías de Contribución](CONTRIBUTING.md)