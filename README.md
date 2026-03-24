# Universo 27

Repositorio de world building y escritura creativa para un universo
de ficción compartido. Tono general: grimdark. Un mismo universo
donde se cuentan múltiples historias independientes.

---

## Cómo usar este repositorio

Este repo está diseñado para trabajarse en conversación con IA
(actualmente Claude). El flujo es:

1. Abres una conversación nueva con Claude
2. Le pasas el contenido relevante del repo (archivos de `mundo/`,
   personajes, lo que aplique a la sesión)
3. Le cuentas tus ideas en bruto — por voz, por texto, como salgan
4. Claude las ordena, las aterriza y te devuelve el texto listo
   para copiar y pegar en el archivo correspondiente
5. Haces commit con el formato: `tipo: descripción breve`
   (`add:`, `update:`, `fix:`, `refactor:`)

**El repo es la memoria permanente. Las conversaciones son el taller.**

---

## Estructura

``` cmd
universo-27/
│
├── README.md                        ← este archivo
│
├── mundo/                           ← canon compartido por todas las historias
│   ├── cosmologia.md
│   ├── facciones.md
│   ├── geografia.md
│   ├── linea-de-tiempo.md
│   └── magia/
│       ├── README.md                ← fundamentos del sistema mágico
│       ├── espiritus.md             ← sistema de tratos, rangos, rey espiritual
│       └── circulos.md              ← magia programada (pendiente)
│
├── historias/
│   ├── precuela-antiharem/          ← historia 1, tono de cuento de hadas relativo
│   │   ├── README.md
│   │   ├── personajes/
│   │   │   ├── bruno.md
│   │   │   ├── lilith.md
│   │   │   ├── iris.md
│   │   │   ├── maribel.md
│   │   │   └── princesa.md          ← nombre pendiente
│   │   ├── capitulos/
│   │   └── notas.md
│   │
│   ├── historia-principal/          ← historia 2, grimdark real, post-precuela
│   │   ├── README.md
│   │   ├── personajes/
│   │   └── notas.md
│   │
│   └── ideas-sueltas/
│       └── conceptos.md
│
└── sesiones/                        ← resúmenes de conversaciones
    └── 2025-02-24-kickoff.md
```

---

## Tono y concepto

- **Grimdark:** el mundo es pesado, las organizaciones son turbias,
  los personajes tienen agendas reales. No hay fuerzas del bien puras.
- **Psicología como eje:** la magia refleja el mundo interno de cada
  personaje. Los conflictos son tan externos como internos.
- **Universo compartido:** las historias son independientes pero
  ocurren en el mismo mundo y línea de tiempo. Los eventos de una
  pueden tener eco en otras.
- **La precuela es el cuento de hadas:** transcurre bajo la paz
  artificial que mantiene el archimago director de la academia.
  La historia principal muestra lo que hay debajo de esa paz,
  y lo que queda cuando se rompe.

---

## Estado actual

|Archivo|Estado|
|---|---|
|`mundo/magia/README.md`|completado v1|
|`mundo/magia/espiritus.md`|completado v1|
|`mundo/magia/circulos.md`|pendiente|
|`mundo/cosmologia.md`|pendiente|
|`mundo/facciones.md`|pendiente|
|`mundo/geografia.md`|pendiente|
|`mundo/linea-de-tiempo.md`|pendiente|
|`historias/precuela-antiharem/personajes/bruno.md`|pendiente|
|`historias/precuela-antiharem/personajes/lilith.md`|pendiente|
|`historias/precuela-antiharem/personajes/iris.md`|pendiente|
|`historias/precuela-antiharem/personajes/maribel.md`|pendiente|
|`historias/precuela-antiharem/personajes/princesa.md`|pendiente|
|`historias/historia-principal/README.md`|pendiente|
