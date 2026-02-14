# 📦 GUÍA COMPLETA - Subir MAXIM a GitHub

## 🎯 Archivos Necesarios (Todo Incluido)

### ✅ LISTA COMPLETA DE ARCHIVOS

```
maxim/
├── .gitignore                  ✓ Configuración Git
├── LICENSE                     ✓ Licencia MIT
├── README.md                   ✓ Documentación principal
├── index.html                  ✓ App principal
├── app.js                      ✓ Lógica de la app
├── timer.js                    ✓ Temporizador iOS
├── timer.css                   ✓ Estilos del temporizador
├── sw.js                       ✓ Service Worker (PWA)
├── manifest.json               ✓ Configuración PWA
├── package.json                ✓ Metadata del proyecto
├── start.sh                    ✓ Script de desarrollo
│
├── alarm.mp3                   ✓ Sonido de alarma
├── favicon.ico                 ✓ Icono navegador
├── icon-192.png                ✓ Icono PWA 192x192
├── icon-512.png                ✓ Icono PWA 512x512
├── apple-touch-icon.png        ✓ Icono iOS
├── splash-2436x1125.png        ✓ Splash iPhone
├── splash-2732x2048.png        ✓ Splash iPad
├── maxim.png                   ✓ Imagen original
│
├── GUIA_COMPLETA.md            ✓ Guía de uso
├── TRADUCCION.md               ✓ Info de traducción
├── VERIFICACION.md             ✓ Checklist completo
├── QUICKSTART.md               ✓ Inicio rápido
├── CONTRIBUTING.md             ✓ Guía de contribución
├── DEPLOYMENT.md               ✓ Guía de despliegue
├── PROJECT_STRUCTURE.md        ✓ Estructura del proyecto
├── DESIGN_NOTES.md             ✓ Notas de diseño
├── ICONS_README.md             ✓ Info de iconos
├── TIMER_README.md             ✓ Info del temporizador
│
├── test-app.html               ✓ Página de pruebas
└── test-timer.html             ✓ Prueba de temporizador
```

**Total:** 29 archivos (7.5 MB aprox)

---

## 🚀 MÉTODO 1: Subir Manualmente (Recomendado)

### Paso 1: Crear Repositorio en GitHub

1. Ve a https://github.com
2. Click en el botón **"+"** (arriba derecha)
3. Selecciona **"New repository"**

**Configuración:**
```
Repository name:    maxim
Description:        🎴 MAXIM - App de revelación de cartas para magos
Public o Private:   [Elige según prefieras]
☐ Add a README      (NO marcar, ya lo tenemos)
☐ Add .gitignore    (NO marcar, ya lo tenemos)
☐ Choose a license  (NO marcar, ya lo tenemos)
```

4. Click **"Create repository"**

---

### Paso 2: Descargar Todos los Archivos

**Descarga estos archivos de la conversación:**

#### Archivos Principales (OBLIGATORIOS)
- ✅ `index.html`
- ✅ `app.js`
- ✅ `timer.js`
- ✅ `timer.css`
- ✅ `sw.js`
- ✅ `manifest.json`
- ✅ `alarm.mp3`

#### Iconos (OBLIGATORIOS)
- ✅ `favicon.ico`
- ✅ `icon-192.png`
- ✅ `icon-512.png`
- ✅ `apple-touch-icon.png`
- ✅ `splash-2436x1125.png`
- ✅ `splash-2732x2048.png`

#### Documentación (RECOMENDADOS)
- ✅ `README.md`
- ✅ `GUIA_COMPLETA.md`
- ✅ `TRADUCCION.md`
- ✅ `QUICKSTART.md`
- ✅ `.gitignore`
- ✅ `LICENSE`
- ✅ `package.json`

#### Opcionales
- `test-app.html`
- `test-timer.html`
- `VERIFICACION.md`
- `DEPLOYMENT.md`
- Otros archivos MD

---

### Paso 3: Subir Archivos a GitHub

#### Opción A: Interfaz Web de GitHub (Más Fácil)

1. En tu repositorio recién creado, click **"uploading an existing file"**
2. **Arrastra TODOS los archivos** a la ventana
3. En "Commit changes":
   ```
   Add MAXIM app files
   
   - Complete PWA application
   - iOS-style timer
   - Spanish translation
   - All documentation
   ```
4. Click **"Commit changes"**

#### Opción B: Git Command Line

```bash
# 1. Inicializar Git en tu carpeta local
cd /ruta/a/tus/archivos
git init

# 2. Añadir todos los archivos
git add .

# 3. Primer commit
git commit -m "Initial commit: MAXIM app completa"

# 4. Conectar con GitHub
git remote add origin https://github.com/TU-USUARIO/maxim.git

# 5. Subir archivos
git branch -M main
git push -u origin main
```

---

### Paso 4: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Click en **"Settings"** (⚙️)
3. En el menú lateral, click **"Pages"**
4. En **"Source"**, selecciona:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **"Save"**
6. Espera 2-3 minutos

**Tu app estará en:**
```
https://TU-USUARIO.github.io/maxim
```

---

## 🚀 MÉTODO 2: Git Desktop (Visual)

### Paso 1: Descargar GitHub Desktop
https://desktop.github.com/

### Paso 2: Crear Repositorio
1. Abre GitHub Desktop
2. File → New Repository
3. Name: `maxim`
4. Local Path: Elige carpeta
5. Click "Create Repository"

### Paso 3: Añadir Archivos
1. Copia TODOS los archivos a la carpeta
2. GitHub Desktop los detectará automáticamente
3. Escribe mensaje de commit:
   ```
   Initial commit: MAXIM app completa
   ```
4. Click "Commit to main"
5. Click "Publish repository"

### Paso 4: Activar GitHub Pages
(Igual que Método 1, Paso 4)

---

## 📋 CHECKLIST PRE-SUBIDA

Antes de subir, verifica que tienes:

### Archivos Críticos
- [ ] `index.html` (26 KB)
- [ ] `app.js` (11 KB)
- [ ] `timer.js` (11 KB)
- [ ] `timer.css` (4 KB)
- [ ] `alarm.mp3` (1.2 MB) ⚠️ **IMPORTANTE**
- [ ] `manifest.json`
- [ ] `sw.js`

### Iconos
- [ ] `favicon.ico`
- [ ] `icon-192.png` (53 KB)
- [ ] `icon-512.png` (297 KB)
- [ ] `apple-touch-icon.png`
- [ ] Al menos 1 splash screen

### Documentación
- [ ] `README.md`
- [ ] `GUIA_COMPLETA.md`
- [ ] `.gitignore`

---

## 🎯 ESTRUCTURA FINAL EN GITHUB

Tu repositorio debe verse así:

```
TU-USUARIO/maxim
├── 📄 README.md
├── 📄 index.html
├── 📄 app.js
├── 📄 timer.js
├── 📄 timer.css
├── 🔊 alarm.mp3          ← ¡IMPORTANTE!
├── 🖼️  icon-192.png
├── 🖼️  icon-512.png
└── ... (otros archivos)
```

---

## ⚠️ ARCHIVOS MUY IMPORTANTES

### NO OLVIDES ESTOS:

1. **alarm.mp3** (1.2 MB)
   - Sin esto, el temporizador no suena
   - Es el archivo más grande

2. **icon-192.png** y **icon-512.png**
   - Sin estos, la PWA no se instala correctamente

3. **manifest.json**
   - Necesario para PWA

4. **sw.js**
   - Necesario para funcionar offline

---

## 🧪 VERIFICAR QUE TODO FUNCIONA

### Después de Subir:

1. **Abre tu app:**
   ```
   https://TU-USUARIO.github.io/maxim
   ```

2. **Prueba estas cosas:**
   - [ ] La app carga correctamente
   - [ ] Los colores se ven bien (púrpura + rojo)
   - [ ] El logo "M" aparece
   - [ ] Puedes seleccionar cartas
   - [ ] El botón "Calcular" funciona
   - [ ] Las revelaciones aparecen
   - [ ] El temporizador se abre
   - [ ] **La alarma SUENA** al terminar ⚠️
   - [ ] Puedes instalar como PWA

3. **Prueba en móvil:**
   - [ ] Abre en Safari (iOS) o Chrome (Android)
   - [ ] Añade a pantalla de inicio
   - [ ] Abre como app
   - [ ] Funciona offline

---

## 🔧 SOLUCIÓN DE PROBLEMAS

### ❌ "La alarma no suena"

**Causa:** Falta `alarm.mp3`

**Solución:**
1. Verifica que `alarm.mp3` está en GitHub
2. Debe estar en la raíz (no en carpeta)
3. Tamaño: ~1.2 MB

### ❌ "No se instala como PWA"

**Causa:** Faltan archivos PWA

**Solución:**
1. Verifica `manifest.json` existe
2. Verifica `sw.js` existe
3. Verifica iconos existen
4. Debe ser HTTPS (GitHub Pages ya lo es)

### ❌ "Los iconos no aparecen"

**Causa:** Rutas incorrectas o archivos faltantes

**Solución:**
1. Todos los PNG deben estar en raíz
2. Verifica nombres exactos:
   - `icon-192.png`
   - `icon-512.png`
   - `apple-touch-icon.png`

### ❌ "404 Not Found"

**Causa:** GitHub Pages no activado

**Solución:**
1. Settings → Pages
2. Source: main branch
3. Espera 2-3 minutos

---

## 📝 DESPUÉS DE SUBIR

### Personaliza tu README.md

Edita el README en GitHub y añade:

```markdown
# 🎴 MAXIM

App de revelación de cartas para magos profesionales.

## 🚀 Ver Demo
[https://TU-USUARIO.github.io/maxim](https://TU-USUARIO.github.io/maxim)

## 📱 Instalar
1. Abre en tu móvil
2. "Añadir a pantalla de inicio"
3. ¡Listo!

## 🎯 Características
- ✅ Revelaciones instantáneas
- ✅ Temporizador iOS
- ✅ Funciona offline
- ✅ 100% en español
```

---

## 🔄 ACTUALIZAR LA APP

Si haces cambios:

```bash
# 1. Edita archivos localmente
# 2. Sube cambios:

git add .
git commit -m "Descripción de cambios"
git push
```

O usando GitHub Desktop:
1. Edita archivos
2. Commit changes
3. Push origin

GitHub Pages se actualiza automáticamente en 1-2 minutos.

---

## 🎁 BONUS: README para GitHub

Crea un `README.md` llamativo:

```markdown
<div align="center">

# 🎴 MAXIM

### App de Revelación de Cartas para Magos

[![Demo](https://img.shields.io/badge/Demo-Live-success)](https://TU-USUARIO.github.io/maxim)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PWA](https://img.shields.io/badge/PWA-Ready-orange)](manifest.json)

![MAXIM Screenshot](maxim.png)

[🚀 Demo en Vivo](https://TU-USUARIO.github.io/maxim) · 
[📖 Guía Completa](GUIA_COMPLETA.md) · 
[🇪🇸 Traducción](TRADUCCION.md)

</div>

---

## ✨ Características

- 🎯 **Revelaciones Instantáneas** - Calcula 3 revelaciones diferentes
- ⏱️ **Temporizador iOS** - Con sonido de alarma iPhone
- 🌐 **Funciona Offline** - PWA completa
- 🇪🇸 **100% Español** - Interfaz totalmente traducida
- 🎨 **Diseño Original** - Idéntico a la app oficial
- 📱 **Instalable** - Como app nativa

## 🚀 Inicio Rápido

### Web
Abre: [https://TU-USUARIO.github.io/maxim](https://TU-USUARIO.github.io/maxim)

### Móvil
1. Abre en Safari (iOS) o Chrome (Android)
2. Menú → "Añadir a pantalla de inicio"
3. Abre como app

## 📚 Documentación

- [📖 Guía Completa](GUIA_COMPLETA.md) - Instrucciones detalladas
- [🚀 Inicio Rápido](QUICKSTART.md) - En 5 minutos
- [🇪🇸 Traducción](TRADUCCION.md) - Info de localización
- [⚙️ Despliegue](DEPLOYMENT.md) - Hosting y configuración

## 🎭 Cómo Usar

1. **Espectador nombra carta:** "Rey de Diamantes"
2. **Abres MAXIM discretamente** (3 segundos)
3. **Seleccionas:** ♦️ → K → Calcular
4. **Obtienes revelaciones:** Fecha, deletreo, posición
5. **¡Magia!** ✨

## 🛠️ Stacks Soportados

- ✅ Mnemonica (Tamariz)
- ✅ Aronson Stack
- ✅ Eight Kings
- ✅ Si Stebbins
- ✅ Custom Stack

## 📱 Compatibilidad

- ✅ iOS Safari 14+
- ✅ Android Chrome 90+
- ✅ Desktop Chrome/Firefox/Edge
- ✅ Instalable como PWA

## 📄 Licencia

MIT License - Usa libremente

## 🙏 Créditos

Inspirado en MAXIM - App profesional para magos

---

<div align="center">
Made with ❤️ for the magic community
</div>
```

---

## ✅ RESUMEN

### Para subir a GitHub necesitas:

1. **Crear repositorio** en GitHub
2. **Descargar 29 archivos** de esta conversación
3. **Subir todos** a GitHub (web o desktop)
4. **Activar GitHub Pages**
5. **Esperar 2-3 minutos**
6. **¡Listo!** Tu app en: `https://TU-USUARIO.github.io/maxim`

### Archivos más importantes:
- `index.html`, `app.js`, `timer.js`, `timer.css`
- `alarm.mp3` ⚠️ (1.2 MB - ¡no olvidar!)
- Todos los PNG (iconos)
- `manifest.json`, `sw.js`

---

**¿Listo para subir?** ¡Descarga los archivos y síguelos pasos! 🚀
