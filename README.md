# Diccionario Clínico de Psicopatología 1
MSc. Erick Ríos · Universidad Americana (UAM) · 2026

Web interactiva en la que los estudiantes de Psicopatología 1 redactan las fichas de 33 términos de uso clínico. Las fichas se publican tras la revisión docente.

## Funciones
- **Diccionario:** índice por función psíquica, buscador, fichas con definición técnica, uso coloquial frente a uso clínico, error frecuente, términos relacionados y fuente APA 7.
- **Redactar una ficha:** formulario con vista previa en vivo; al enviar, el estudiante recibe un código de seguimiento.
- **Ejercicios:** se generan solos a partir de las fichas publicadas.
- **Acceso docente:** revisión, edición, publicación o devolución de fichas con observaciones.

## Configuración
Abre `index.html`, busca `const CONFIG` y pega la Project URL y la anon key de Supabase. Si quedan vacías, la web funciona en modo demostración (los datos se guardan solo en el navegador).

La base de datos se crea con el archivo `supabase.sql` en el SQL Editor de Supabase. Después, en Authentication, crea el usuario docente y desactiva el registro de nuevos usuarios.
