# Bitácora del Proyecto Ovanesoft

## Descripción del Proyecto
**Ovanesoft** es una empresa de desarrollo de software especializada en crear aplicaciones utilizando Inteligencia Artificial.

## Stack Tecnológico
- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Backend/Cloud:** Firebase, Firestore, Node.js
- **IA:** Claude.ai, ChatGPT
- **Herramientas:** Cursor (IDE), PWA
- **Funcionalidades:** QR Scanner, sistemas QR

## Servicios Ofrecidos
1. **Aplicaciones Web** - React, TypeScript, PWA
2. **Apps Móviles** - iOS y Android (nativas y multiplataforma)
3. **Integración con IA** - Claude.ai, ChatGPT
4. **Sistemas Complejos** - Firebase, Firestore, arquitecturas escalables
5. **Sistemas QR** - Logística, inventario, tracking
6. **Cloud & Hosting** - Firebase, GitHub Pages

## Estructura Actual del Proyecto
```
Ovanesoft/
├── .cursor/
│   └── rules/
│       └── bitacora.mdc
├── images/
│   └── ovanesoft-logo.png
├── index.html
└── bitacora.md (este archivo)
```

## Registro de Cambios

### [2025-01-27] - Creación de la Bitácora
- **Acción:** Creado el archivo `bitacora.md` en la raíz del proyecto
- **Motivo:** Siguiendo las reglas establecidas en `.cursor/rules/bitacora.mdc`
- **Detalles:** Este archivo servirá como la fuente de verdad del proyecto y se actualizará con todos los cambios realizados

### [2025-01-27] - Mejoras Responsive del Logo Ovanesoft
- **Acción:** Modificado el CSS del logo en la barra de navegación para hacerlo completamente responsive
- **Motivo:** Usuario solicitó que el logo sea responsive y conforme a la barra de menú
- **Detalles:** 
  - Cambiado de texto con gradiente a imagen (`object-fit: contain`)
  - Establecido tamaño base: `height: 40px, max-width: 200px`
  - Agregado efecto hover con `brightness`, `contrast` y `transform: scale(1.02)`
  - Responsive breakpoints:
    - Pantallas grandes (≥1200px): `height: 45px, max-width: 220px`
    - Tablets (≤768px): `height: 32px, max-width: 150px`
    - Móviles (≤480px): `height: 28px, max-width: 120px`
  - Transiciones suaves para todos los cambios de estado

## Reglas de Trabajo
1. **Siempre leer este archivo** antes de realizar cualquier trabajo
2. **Actualizar este archivo** inmediatamente después de cada cambio
3. **Registrar todos los cambios** con fecha, acción, motivo y detalles
4. **Mantener información verídica** y actualizada
5. **Este archivo es la absoluta verdad del proyecto**

## Contacto
- **Email:** info@ovanesoft.com
- **Web:** ovanesoft.com
