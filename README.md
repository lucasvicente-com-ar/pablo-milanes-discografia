# Pablo Milanés — Discografía Completa

> *"Esto no puede ser no más que una canción, quisiera fuera una declaración de amor..."*

## ¿Qué es esto?

Este proyecto es un **compilado histórico** de toda la obra musical de Pablo Milanés, creado con el propósito de **preservar su legado** para que nunca se pierda.

Pablo Milanés Arias (Bayamo, Cuba, 1943 – Madrid, España, 2022) fue uno de los grandes cantautores de América Latina y, junto a Silvio Rodríguez y Noel Nicola, padre fundador de la **Nueva Trova Cubana**. Su música —poesía hecha canción— recorrió más de cinco décadas y dejó una huella imborrable en la cultura latinoamericana.

Este repositorio reúne **toda su discografía oficial** en un solo lugar: cada álbum, cada canción, cada letra. Un archivo vivo para que las nuevas generaciones puedan descubrir, estudiar y disfrutar su obra completa.

## Datos del archivo

| Métrica | Valor |
|---|---|
| Álbumes | 48 |
| Canciones | 586 |
| Con letras completas | 558 (95.2%) |
| Portadas originales | 48 |
| Período cubierto | 1973 – 2021 |
| Fuente de datos | Múltiples fuentes: [milanespablo.com](https://www.milanespablo.com/discografia/), Genius, Cancioneros, CMTV, Musixmatch, letras.com |

## Discografía cronológica

| Año | Álbum | Tipo | Temas |
|---|---|---|---|
| 1973 | Versos de José Martí | Estudio | 12 |
| 1976 | La Vida No Vale Nada | Estudio | 10 |
| 1978 | No Me Pidas | Estudio | 11 |
| 1979 | Aniversario | Estudio | 9 |
| 1980 | Años | Estudio | 9 |
| 1980 | Canta a la Resistencia Popular Chilena | Estudio | 10 |
| 1981 | El Pregón de las Flores | Estudio | 12 |
| 1981 | Filin | Estudio | 11 |
| 1982 | Canta a Nicolás Guillén | Estudio | 11 |
| 1982 | Yo Me Quedo | Estudio | 9 |
| 1983 | El Guerrero | Estudio | 10 |
| 1984 | Ao Vivo No Brasil | En vivo | 12 |
| 1984 | Comienzo y Final de una Verde Mañana | Estudio | 10 |
| 1986 | Años 2 | Estudio | 11 |
| 1986 | Querido Pablo | Estudio | 20 |
| 1987 | Buenos Días América | Estudio | 8 |
| 1987 | Trovadores | Estudio | 10 |
| 1988 | Proposiciones | Estudio | 10 |
| 1989 | Con Ciertos Amigos | Estudio | 10 |
| 1989 | Filin 3 | Estudio | 10 |
| 1990 | Años 3 | Estudio | 10 |
| 1990 | Filin 2 | Estudio | 11 |
| 1990 | Identidad | Estudio | 8 |
| 1991 | Canto de la Abuela | Estudio | 8 |
| 1991 | Filin 4 | Estudio | 12 |
| 1991 | Filin 5 | Estudio | 12 |
| 1994 | Canta Boleros en Tropicana | Estudio | 14 |
| 1994 | Orígenes | Estudio | 11 |
| 1995 | En Blanco y Negro | Estudio | 17 |
| 1995 | Plegaria | Estudio | 9 |
| 1997 | Despertar | Estudio | 10 |
| 1998 | Vengo Naciendo | Estudio | 14 |
| 2000 | Días de Gloria | Estudio | 11 |
| 2002 | Pablo Querido | Estudio | 20 |
| 2005 | Como un Campo de Maíz | Estudio | 12 |
| 2005 | Líneas Paralelas | Estudio | 10 |
| 2007 | Regalo | Estudio | 10 |
| 2008 | Filin 6 | Estudio | 10 |
| 2008 | Más Allá de Todo | Estudio | 10 |
| 2008 | Raúl y Pablo | Estudio | 16 |
| 2013 | Renacimiento | Estudio | 10 |
| 2014 | Canción de Otoño | Estudio | 14 |
| 2016 | Flores del Futuro | Estudio | 10 |
| 2017 | Amor | Estudio | 11 |
| 2018 | Flor Oculta de la Vieja Trova | Estudio | 17 |
| 2019 | Mi Habana | Estudio | 21 |
| 2019 | Standards de Jazz | Estudio | 9 |
| 2021 | Antología Personal | Compilatorio | 42 |

## Estructura del repositorio

```
├── data.json              # Base de datos completa (álbumes, canciones, letras, portadas)
├── index.html             # Versión web (requiere servidor local)
├── index_standalone.html  # Versión autónoma (abrir directamente en navegador)
├── covers/                # Portadas originales de cada álbum (imágenes locales)
└── carpeta de trabajo/    # Scripts de scraping y procesamiento de datos
```

## Cómo usarlo

### Opción 1: Abrir directamente (recomendada)

Haz doble clic en **`index_standalone.html`** y se abrirá en tu navegador. No necesita internet ni servidor. Todo funciona offline: datos, letras y portadas están incluidas.

### Opción 2: Servidor local

```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx serve .
```

Luego abre `http://localhost:8000`

## Características del sitio

- **Línea de tiempo cronológica** — desde 1973 hasta 2021
- **Búsqueda** — por canción, álbum o texto de letra
- **Filtros** — por tipo de álbum (Estudio, En Vivo, Compilatorio)
- **Letras completas** — clic en cualquier canción para ver la letra
- **Portadas originales** — arte de cada álbum descargado del sitio oficial
- **Diseño responsivo** — funciona en escritorio y móvil
- **100% offline** — la versión standalone no necesita conexión

## Fuente de datos

Los datos fueron recopilados de múltiples fuentes:

- **[milanespablo.com](https://www.milanespablo.com/discografia/)** — sitio oficial (tracklists, portadas, descripciones, álbumes)
- **Genius** — letras de canciones
- **Cancioneros.com** — letras de canciones
- **CMTV.com.ar** — letras de canciones
- **Musixmatch** — letras de canciones
- **Letras.com** — letras de canciones

Este proyecto es un archivo de preservación, no una fuente original de contenido.

## Nota sobre derechos

Las letras y portadas pertenecen a sus respectivos autores y titulares de derechos. Este repositorio se crea con fines de **preservación cultural y educativa**, como un homenaje al legado de Pablo Milanés. Si eres titular de derechos y deseas solicitar la remoción de algún contenido, por favor abre un issue.

---

*"Yo pisaré las calles nuevamente..."* — Pablo Milanés

---

**by: Lucas M. Vicente & iAs**
