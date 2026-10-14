# Refuerzo pedagógico — Contadores del Bar Salesiano

Entrega de **William Ariel Ortiz Terán**, curso **3E2**, desarrollada con Expo, React Native y TypeScript.

La aplicación contiene tres contadores independientes para sanduches, empanadas y jugos. Cada uno respeta sus límites, permite incrementar o disminuir su valor y puede reiniciarse.

## Retos completados

- Reto 01: dominio del contador con tipos, límites y estados de interfaz.
- Reto 02: componente presentacional `ContadorDisplay` con props tipadas.
- Reto 03: botón reutilizable con variantes, estado deshabilitado y respuesta táctil.
- Reto 04: integración de los tres contadores mediante `useState`.

## Verificación

```bash
pnpm install
pnpm run test:all
pnpm run check
pnpm run lint
```

Resultado esperado: los cuatro retos aprobados y cero errores de TypeScript o ESLint.

## Ejecutar la aplicación

```bash
pnpm start
```

Después se puede escanear el código QR con Expo Go. Para conocer la estructura, las reglas de entrega y el guion solicitado, consulta [GUIA_MONTAJE.md](GUIA_MONTAJE.md) y [PLANTILLA_SCREENCAST.md](PLANTILLA_SCREENCAST.md).
