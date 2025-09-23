# .gitignore del proyecto

## Objetivo
Evitar subir archivos inútiles o sensibles que ensucian el historial.

## Qué ignora y por qué
- `.DS_Store` → basura de macOS.
- `node_modules/` → dependencias instalables, pesan y se regeneran.
- `dist/` y `build/` → artefactos de compilación.
- `.env` y `.env.*` → variables sensibles (tokens, claves).

## Nota de uso
Cuando se añadan herramientas (bundlers, test, etc.), se ajustará este archivo.