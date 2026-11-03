# VTK Medical Visualization Web App

A browser-based 3D viewer for medical volumes built with **vtk.js**. It supports surface rendering with an adjustable iso value and volume ray casting with adjustable transfer functions, and you can switch between the two modes at runtime.

Team project: Omar Essam, Mohamed Bahaa, Youssef El Gazzar, Mohamed Ahmed Hamed.

## Demo

**Surface rendering: changing the iso value**

<img src="Output Screenshots/Chest.gif" alt="Iso value demo" width="600">

**Ray casting: changing the rendering properties**

<img src="Output Screenshots/Skull.gif" alt="Ray casting demo" width="600">

**Toggling between modes**

<img src="Output Screenshots/Toggle.gif" alt="Mode toggle demo" width="600">

## Run

```bash
npm install
npm start
```

## A problem we solved

After picking a mode, users couldn't switch again. We were binding the toggle with `querySelector()`, which returns only the first matching element. Switching to `querySelectorAll()` bound every mode control, so users can toggle freely.

## Tech stack

JavaScript · vtk.js · Webpack · npm
