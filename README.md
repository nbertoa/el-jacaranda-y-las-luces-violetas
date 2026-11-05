# El jacarandá y las luces violetas

*Cuando Dios habla a través de la naturaleza*

Libro narrativo-contemplativo de Nicolás Bertoa. Reúne catorce testimonios reales de cómo Dios le habló a través de la creación: árboles, animales, el viento, un sendero. El recorrido va de pedir señales a contemplar sin pedir nada, y termina frente a un naranjo que no se esfuerza por dar fruto: «Me alcanza con saber que Jesús está conmigo».

## ¿En qué estado está?

**Aprobado por Nico el 5 de noviembre de 2026.** Prólogo, 14 capítulos y epílogo, unas 6.200 palabras.

- Libro completo en un solo archivo, listo para ElevenReader: [`edicion/el-jacaranda-y-las-luces-violetas.md`](edicion/el-jacaranda-y-las-luces-violetas.md).
- Capítulos sueltos: [`manuscrito/`](manuscrito/).
- Lo que queda antes de publicar está en [`manuscrito/README.md`](manuscrito/README.md).

## ¿Qué hay acá?

| Archivo o carpeta | Qué tiene |
|---|---|
| [`edicion/`](edicion/) | El libro aprobado en un solo `.md`, sin marcas de formato que se lean en voz alta |
| [`manuscrito/`](manuscrito/) | Prólogo, 14 capítulos y epílogo, un archivo por sección |
| [`IDEA.md`](IDEA.md) | El eje central del libro y el arco |
| [`ESTRUCTURA.md`](ESTRUCTURA.md) | Cómo se ordenan los testimonios |
| [`DECISIONES.md`](DECISIONES.md) | Todo lo que se decidió y por qué |
| [`INVESTIGACION.md`](INVESTIGACION.md) | Fuentes verificadas y lo que queda por verificar |
| [`testimonios/`](testimonios/) | Los testimonios tal como Nico los contó, incluidos los dos que quedaron fuera |
| [`fuentes/`](fuentes/) | La reflexión del árbol y el relato del hermano Lorenzo |
| [`revision/`](revision/) | Las dos auditorías externas de ChatGPT |

## ¿Cómo se trabaja?

- Claude escribe en este repo. Nico lo escucha en ElevenReader, lo revisa y decide.
- Todo va en markdown plano, apto para escuchar en voz alta.
- Voz y estilo: [`nbertoa/escritura-voz-propia`](https://github.com/nbertoa/escritura-voz-propia). Filtro: [`nbertoa/jesus-como-filtro`](https://github.com/nbertoa/jesus-como-filtro). Lo propio de este libro queda en `DECISIONES.md`.
- Si se cambia un capítulo en `manuscrito/`, se regenera el archivo de `edicion/` uniendo todos los capítulos en orden.
