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

### [2025-01-27] - Configuración y Subida a GitHub
- **Acción:** Configurado repositorio Git y subido todo el proyecto a GitHub
- **Motivo:** Usuario solicitó subir el proyecto completo a GitHub
- **Detalles:**
  - Inicializado repositorio Git local (`git init`)
  - Creado archivo `.gitignore` con exclusiones apropiadas
  - Commit inicial con todos los archivos del proyecto
  - Configurado repositorio remoto: `https://github.com/ovanesoft/Ovanesoft.git`
  - Resuelto merge conflict con README.md remoto
  - Subido exitosamente a GitHub (12 objetos, 47.93 KiB)
  - Repositorio disponible en: [https://github.com/ovanesoft/Ovanesoft](https://github.com/ovanesoft/Ovanesoft)

### [2025-01-27] - Configuración de Dominio Personalizado y GitHub Pages
- **Acción:** Configurado GitHub Pages con dominio personalizado ovanesoft.com
- **Motivo:** Usuario solicitó enlazar su dominio ovanesoft.com al repositorio para tener la página online
- **Detalles:**
  - Creado archivo `CNAME` con el dominio ovanesoft.com
  - Configurado GitHub Pages desde la rama main
  - Configurado DNS en GoDaddy con 4 registros A apuntando a GitHub Pages:
    - 185.199.108.153
    - 185.199.109.153
    - 185.199.110.153
    - 185.199.111.153
  - Configurado CNAME para www apuntando a ovanesoft.com
  - Sitio web completamente funcional y accesible en: **https://ovanesoft.com**
  - HTTPS habilitado automáticamente por GitHub Pages

## Reglas de Trabajo
1. **Siempre leer este archivo** antes de realizar cualquier trabajo
2. **Actualizar este archivo** inmediatamente después de cada cambio
3. **Registrar todos los cambios** con fecha, acción, motivo y detalles
4. **Mantener información verídica** y actualizada
5. **Este archivo es la absoluta verdad del proyecto**

## Contacto
- **Email:** info@ovanesoft.com
- **Web:** ovanesoft.com
