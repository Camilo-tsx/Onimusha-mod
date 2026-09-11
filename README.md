<p align="right">
  <strong>Español</strong>
  &nbsp;•&nbsp;
  <a href="README.md">English</a>
</p>

# Onimusha: Way of the Sword — AI Difficulty Mod

Un mod de dificultad para **Onimusha: Way of the Sword** que hace que los combates sean más agresivos y dinámicos.

El mod permite que múltiples enemigos ataquen simultáneamente en lugar de esperar su turno, haciendo que los enfrentamientos sean más intensos y desafiantes.

## Características

* ⚔️ Múltiples enemigos pueden atacar simultáneamente.
* 🚫 Elimina el límite de atacantes del comportamiento vanilla.
* ⚡ Reduce los tiempos de espera del sistema de presión de los enemigos.
* 🔥 Reduce los intervalos del ritmo de combate.
* 🎮 No requiere configuración.
* 📦 Solo requiere **REFramework** para funcionar.

---

# Instalación

## 1. Instalar REFramework

Este mod requiere **REFramework** para funcionar.

Descarga la última versión desde el repositorio oficial:

<p align="center">
  <a href="https://github.com/praydog/REFramework-nightly/releases">
    <strong>⬇️ Descargar REFramework</strong>
  </a>
</p>

Descarga el archivo `REFramework.zip` correspondiente a la última versión disponible.

Extrae `dinput8.dll` en la carpeta principal donde está instalado **Onimusha: Way of the Sword**.

La estructura debería quedar aproximadamente así:

```text
Onimusha Way of the Sword/
├── dinput8.dll
├── reframework/
└── ...
```

Inicia el juego una vez para comprobar que REFramework se haya instalado correctamente.

---

## 2. Instalar el mod

Descarga el archivo `.lua` del mod:

<p align="center">
  <a href="Onimusha_AI_Tweaks.lua">
    <strong>⬇️ Descargar Onimusha AI Tweaks</strong>
  </a>
</p>

Después, ve a la carpeta donde está instalado **Onimusha: Way of the Sword** y abre:

```text
reframework/
```

Luego abre:

```text
reframework/autorun/
```

Coloca el archivo `Onimusha_AI_Tweaks.lua` dentro de esa carpeta.

La estructura final debería quedar así:

```text
Onimusha Way of the Sword/
├── dinput8.dll
└── reframework/
    └── autorun/
        └── Onimusha_AI_Tweaks.lua
```

### ¡Eso es todo!

El mod **no requiere ninguna configuración adicional**.

Simplemente inicia el juego y REFramework cargará automáticamente el mod.

---

# ¿Cómo comprobar que funciona?

Abre el menú de **REFramework** dentro del juego.

Deberías ver:

```text
Mod activado
```

Si aparece ese mensaje, el mod está cargado correctamente.

---

# Código fuente

¿No quieres descargar el archivo?

Puedes revisar el código fuente completo directamente desde GitHub.

<p align="center">
  <a href="Onimusha_AI_Tweaks.lua">
    <strong>📄 Ver código fuente completo</strong>
  </a>
</p>

El mod está escrito completamente en **Lua de texto plano**.

No contiene ejecutables ni archivos compilados.

Puedes abrir el archivo, revisar todo el código y copiarlo directamente desde GitHub si prefieres instalarlo manualmente.

---

# Instalación manual

Si prefieres no utilizar el archivo descargable, puedes crear el archivo manualmente.

Crea un archivo llamado:

```text
Onimusha_AI_Tweaks.lua
```

Copia dentro el código fuente del mod y colócalo en:

```text
reframework/autorun/
```

La estructura final debe ser:

```text
reframework/
└── autorun/
    └── Onimusha_AI_Tweaks.lua
```

No es necesario modificar ningún valor del código.

---

# Desinstalación

Para desinstalar el mod, simplemente elimina:

```text
reframework/autorun/Onimusha_AI_Tweaks.lua
```

No es necesario desinstalar REFramework.

---

# Compatibilidad

Este mod está diseñado para:

**Onimusha: Way of the Sword**

Requiere:

**REFramework**

---

# Créditos

Si te sirvió el mod, considera dejar una ⭐ en el repositorio.



<p align="center">
  <a href="README.md">🇬🇧 Read this page in English</a>
</p>
