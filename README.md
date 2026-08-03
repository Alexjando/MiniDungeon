# 🗡️ Mini Dungeon Crawler

**Un motor de juego y Shooter Top-Down táctico construido desde CERO usando C++ nativo y Win32 API.**

![Windows](https://img.shields.io/badge/OS-Windows-blue?style=for-the-badge&logo=windows)
![C++](https://img.shields.io/badge/C++-Native_Win32-00599C?style=for-the-badge&logo=c%2B%2B)
![Python](https://img.shields.io/badge/Backend-Python_Flask-FFD43B?style=for-the-badge&logo=python)

[![Descargar Instalador](https://img.shields.io/badge/📥_Descargar_Juego_(Instalador_Oficial)-28a745?style=for-the-badge)](https://github.com/Alexjando/MiniDungeon/releases/latest/download/MiniDungeonCrawler_Setup.exe)

---

## En lugar de usar un motor comercial fácil como Unity o Godot que te resuelve todo, me propuse el reto de:
1. Crear mi propio motor de físicas, renderizado (GDI) y colisiones en **C++ puro**.
2. Crear un servidor backend en **Python (Flask)** alojado en la nube.
3. Crear un cliente HTTP asíncrono en C++ que se comunique con el servidor en tiempo real.
4. Implementar un **actualizador automático** que descarga los parches desde GitHub de forma invisible.

## 🎮 Controles
* **W, A, S, D** - Moverse.
* **Ratón** - Apuntar.
* **Clic Izquierdo** - Disparar (Físicas de partículas y daño de área incluidas).
* **SHIFT** - Dash / Corte letal (Daño cuerpo a cuerpo).
* **O** - Menú de Configuración Visual (Volumen analógico e Idioma en tiempo real).
* **T / W** - Tienda de Mejoras y Armería (en el menú principal).
