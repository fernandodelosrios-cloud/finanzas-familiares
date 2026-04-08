# Gestor de Finanzas Familiares

Una web app para registrar y controlar gastos compartidos entre parejas.

## Características

- 📝 Registro de gastos con categorización
- 💾 Almacenamiento local (localStorage)
- 📊 Dashboard con presupuestos vs gastos real
- 📥 Exportar datos a CSV
- 📊 Sincronización manual con Google Sheets
- 📱 Mobile-friendly

## Desplegar en Vercel

### Opción 1: Desde GitHub (Recomendado)

1. **Crea un repositorio en GitHub**
   - Ve a https://github.com/new
   - Crea un nuevo repositorio llamado `finanzas-familiares`
   - No inicialices con README

2. **Sube los archivos**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/finanzas-familiares.git
   git push -u origin main
   ```

3. **Conecta Vercel a GitHub**
   - Ve a https://vercel.com/import
   - Selecciona tu repositorio `finanzas-familiares`
   - Vercel automáticamente detectará y desplegará
   - ¡Listo! Tu app estará en vivo en pocos segundos

### Opción 2: Drag & Drop en Vercel (Más simple)

1. Ve a https://vercel.com/new
2. Arrastra y suelta esta carpeta
3. ¡Listo! Vercel creará el despliegue automáticamente

## Uso

1. Abre la URL de tu app en Vercel
2. Registra gastos en "Registrar Gasto"
3. Visualiza en el "Dashboard"
4. Exporta a Google Sheets cuando quieras sincronizar

## Estructura de archivos

```
finanzas-app/
├── index.html          # App principal
├── vercel.json         # Configuración para Vercel
└── README.md          # Este archivo
```

## Compartir con tu esposa

Una vez desplegada en Vercel, comparte el link con antonellaag@gmail.com:
- Ambos pueden abrir el mismo link
- Los datos se guardan localmente en cada navegador
- Exporta a Google Sheets para sincronizar entre dispositivos

## Notas

- Los datos se guardan en localStorage del navegador
- Para sincronizar entre dispositivos, usa el botón "Exportar a Google Sheets"
- Cada navegador/dispositivo tiene sus propios datos hasta que sincronices manualmente

## Soporte

Para cambios o mejoras, contacta al desarrollador.
