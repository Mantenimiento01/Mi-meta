# Mi Meta 💧🍽️🏊‍♀️⏳

App personal (web instalable, funciona sin internet) para acompañar un proceso de pérdida de peso saludable: de **64 kg a 56 kg**.

## Qué hace

- **Agua**: botones de +250 / +500 ml, vasos que se llenan y meta diaria editable (por defecto 2,25 L). En días de dos entrenamientos te recuerda tomar más.
- **Comida y calorías**: buscador con ~70 alimentos comunes en Colombia (arepa, pandebono, fríjoles, sancocho, corrientazo…), porciones ajustables, momentos del día y alimentos personalizados que quedan guardados. Muestra calorías y proteína contra tu objetivo.
- **Entrenamiento**: natación, salto de cuerda, baile, caminata u otro. Puedes registrar **varias sesiones el mismo día**. Plan semanal editable (6 días + descanso, con la opción de poner 2 actividades en un día), cronómetro, estimación de calorías quemadas y guías de rutina de 30–40 min.
- **Ayuno intermitente**: protocolos 12:12, 13:11, 14:10 y 16:8, temporizador en vivo, hora a la que abre tu ventana de comida, aviso al terminar, historial y racha. Si registras una comida estando en ayuno, te pregunta si quieres terminarlo.
- **Progreso**: registro de peso, gráfica con la línea de meta, kilos perdidos/faltantes y fecha estimada de llegada.
- **Respaldo**: descargar y restaurar tus datos en un archivo `.json`.

## Cómo se calcula el objetivo de calorías

1. Gasto basal (Mifflin-St Jeor, si pones estatura y edad; si no, una estimación por peso).
2. × factor de actividad (por defecto *moderada*, porque ya incluye entrenar 6 días).
3. − déficit según el ritmo elegido (0,5 kg/semana ≈ 550 kcal/día).
4. Nunca baja de 1.200 kcal.

Las calorías del ejercicio se muestran como información; **no** se suman al objetivo porque el factor de actividad ya las incluye.

> Los valores son aproximados y sirven para seguimiento. No reemplazan la orientación de un médico o nutricionista.

## Publicarla en GitHub (sin usar terminal)

1. Crea una cuenta en [github.com](https://github.com) si no tienes.
2. Botón **New repository** → nombre: `mi-meta` → *Public* → **Create repository**.
3. Clic en **uploading an existing file** y arrastra **todo el contenido** de esta carpeta (`index.html`, `sw.js`, `manifest.webmanifest`, `README.md` y la carpeta `icons`). → **Commit changes**.
4. Ve a **Settings → Pages** → en *Branch* elige `main` y `/ (root)` → **Save**.
5. En 1–2 minutos tu app queda en: `https://TU-USUARIO.github.io/mi-meta/`

## Instalarla en el celular

- **Android (Chrome)**: abre el enlace → menú ⋮ → **Instalar app** (o *Agregar a pantalla principal*).
- **iPhone (Safari)**: abre el enlace → botón Compartir → **Agregar a inicio**.

Queda con su ícono, se abre a pantalla completa y funciona sin internet.

## Tus datos

Todo se guarda **solo en tu teléfono** (nada se sube a internet). Si borras los datos del navegador o cambias de celular, se pierden; usa **Progreso → Descargar copia** cada cierto tiempo y **Restaurar** en el nuevo dispositivo.

## Archivos

| Archivo | Para qué |
|---|---|
| `index.html` | Toda la app |
| `sw.js` | Permite usarla sin conexión |
| `manifest.webmanifest` | Nombre, colores e ícono al instalarla |
| `icons/` | Íconos de la app |
