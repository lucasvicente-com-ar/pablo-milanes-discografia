# Pablo Milanés — Discografía Completa

Sitio web interactivo con la discografía completa de Pablo Milanés, incluyendo letras de canciones y portadas de álbumes.

## Datos

| Métrica | Valor |
|---|---|
| Álbumes | 48 |
| Canciones | 586 |
| Con letras | 489 (83%) |
| Período | 1973 – 2021 |

## Estructura

```
├── data.json              # Base de datos (álbumes, canciones, letras, portadas)
├── index.html             # Versión web (requiere servidor local)
├── index_standalone.html  # Versión autónoma (abrir directamente en navegador)
├── covers/                # Portadas de álbumes (imágenes locales)
└── carpeta de trabajo/    # Scripts de scraping y procesamiento
```

## Uso

### Versión autónoma (recomendada)
Abre `index_standalone.html` directamente en tu navegador. No requiere servidor.

### Versión con servidor
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```
Luego abre `http://localhost:8000`

## Fuente de datos

Todos los datos (tracklists, letras y portadas) fueron obtenidos del sitio oficial [milanespablo.com](https://www.milanespablo.com/discografia/).

## Licencia

Las letras y portadas pertenecen a sus respectivos autores y titulares de derechos. Este proyecto es con fines educativos y de preservación cultural.
