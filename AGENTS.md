# Contexto del proyecto

Esta carpeta contiene juegos educativos para un niño de 4 años.

## Público y experiencia de uso

- Diseñar para un niño que todavía no sabe leer con fluidez.
- Priorizar instrucciones visuales y de audio, interacciones sencillas y objetivos evidentes.
- Usar botones grandes, separados y cómodos para interacción táctil.
- Evitar pantallas recargadas, textos largos, penalizaciones frustrantes y límites de tiempo exigentes.
- Dar feedback positivo, inmediato y fácil de entender.
- No incluir anuncios, compras, enlaces externos, recopilación de datos ni contenido inapropiado.

## Dispositivos compatibles

Los juegos deben funcionar en dispositivos Apple:

- iPhone
- iPad
- Mac

La compatibilidad principal es Safari, incluyendo interacción táctil y mediante ratón o trackpad. El diseño debe adaptarse a pantallas pequeñas y grandes, respetar las áreas seguras del dispositivo y evitar desbordamientos.

## Requisitos técnicos

- Cada juego debe ser una aplicación autónoma en un único archivo `.html`.
- Usar únicamente HTML, CSS y JavaScript estándar incluidos dentro del propio archivo.
- No introducir frameworks, gestores de paquetes, pasos de compilación ni dependencias externas.
- No depender de un servidor: el archivo debe poder abrirse directamente y funcionar sin conexión.
- Integrar localmente los recursos necesarios; preferir CSS, SVG embebido y emojis cuando sean adecuados.
- Mantener el código claro y organizado por secciones, aunque permanezca en un solo archivo.
- Si se usa audio o síntesis de voz, contemplar las restricciones de reproducción automática de Safari y ofrecer siempre un control visible para repetirlo.
- Degradar de forma segura si una API del navegador, una voz o `localStorage` no están disponibles.

## Accesibilidad y seguridad infantil

- Incluir nombres accesibles en botones que solo contienen iconos o imágenes.
- Mantener buen contraste y no comunicar aciertos o errores únicamente mediante color.
- Respetar `prefers-reduced-motion` y evitar animaciones intensas o parpadeos.
- Evitar bloquear innecesariamente el zoom y otras funciones de accesibilidad del dispositivo.
- No reproducir sonidos inesperados fuera de una interacción o sesión de juego activa.

## Validación antes de terminar

- Comprobar que el juego se abre como archivo HTML independiente.
- Verificar el flujo completo con interacción táctil y con ratón.
- Revisar tamaños pequeños de iPhone, orientación vertical de iPad y pantalla de Mac.
- Confirmar que no se realizan solicitudes de red y que no aparecen errores en la consola.
