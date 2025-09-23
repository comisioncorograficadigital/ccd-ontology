# CCD Ontology — v1.0 (GitHub Pages)

**Canonical base (GitHub Pages):** `https://comisioncorograficadigital.github.io/ccd-ontology/ontology/`

Este repositorio publica la Ontología CCD y materiales asociados (SKOS starter, SHACL, contexto JSON-LD).

## Publicación (GitHub Pages)
1. Crea el repo **comisioncorograficadigital/ccd-ontology**.
2. Sube estos archivos tal cual.
3. Activa **Settings → Pages**: "Deploy from a branch" (main) y carpeta `/docs` (o root, ambas opciones están preparadas).
4. Verifica que https://comisioncorograficadigital.github.io/ccd-ontology/ carga la página y que el TTL está en `https://comisioncorograficadigital.github.io/ccd-ontology/ontology/ccd-ontology-v1.ttl`.

## Importar en Omeka S
- **SKOS**: importa por URL RDF/XML `http://www.w3.org/2004/02/skos/core.rdf` o sube archivo local si falla.
- **PROV-O**: `https://www.w3.org/ns/prov-o.ttl` (o `.rdf`).
- **Ontología CCD**: importa **archivo local** `ontology/ccd-ontology-v1.ttl`.
- Luego importa tus **Resource Templates** (JSON) desde el pack de Omeka.

## Estructura
- `docs/` — Documentación pública (GitHub Pages).
- `ontology/ccd-ontology-v1.ttl` — Ontología CCD v1.0.
- `vocabularies/cctop-skos-starter.ttl` — SKOS starter (esquemas/Conceptos base).
- `validation/ccd-shapes.ttl` — SHACL mínimo.
- `export/ccd-context.jsonld` — Contexto JSON-LD.
- `w3id/.htaccess` — Ejemplo de redirección si deseas un alias estable `https://w3id.org/ccd/ontology/` más adelante.

## Licencia
- Ontología y documentos: CC-BY 4.0
