### Preguntas Semana 4

Video YouTube: https://youtu.be/CsShvn_7jfc 

1. ¿Cuál es el comando utilizado para generar y aplicar migraciones en un entorno de desarrollo con Prisma Migrate?
   - a) npx prisma migrate create
   - b) npx prisma migrate up
   - c) npx prisma migrate dev
   
   **Respuesta correcta: c) `npx prisma migrate dev`**
   Explicación: El comando utilizado para generar y aplicar migraciones en un entorno de desarrollo es `npx prisma migrate dev`. Los otros comandos mencionados (`create` y `up`) son para crear migraciones nuevas y aplicar migraciones existentes, respectivamente, pero no para unificar ambas acciones como lo hace `dev`.

2. ¿Qué comando se debe evitar usar en un entorno de producción según la documentación?
   - a) npx prisma migrate reset
   - b) npx prisma migrate up
   - c) npx prisma migrate dev
   
   **Respuesta correcta: a) `npx prisma migrate reset`**
   Explicación: El comando `reset` es exclusivo para entornos de desarrollo y nunca debe ser utilizado en un entorno de producción. Los otros comandos (`up` y `dev`) también están diseñados para entornos de desarrollo, pero no llevan la misma advertencia explícita.

3. ¿Cuál es el propósito del comando `--create-only` en Prisma Migrate?
   - a) Aplicar migraciones de forma inmediata.
   - b) Crear una migración sin aplicarla.
   - c) Generar un esquema de base de datos desde cero.
   
   **Respuesta correcta: b) Crear una migración sin aplicarla.**
   Explicación: El comando `--create-only` se utiliza para crear una migración sin aplicarla. Esto es útil cuando necesitas personalizar una migración antes de aplicarla, como realizar cambios específicos en el esquema que Prisma Migrate no admite directamente. 