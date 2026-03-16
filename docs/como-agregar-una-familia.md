# Como agregar una familia

Una familia nueva solo puede entrar a `Familias de Mini` si ya esta
certificada.

## Requisitos minimos

- inventario activo certificado
- `README.md` de la familia
- `family.yaml`
- `family_blueprint.yaml`
- `skills_catalog.json`
- `base_flows.json`
- `compatibility_graph.json`
- carpeta `skills/`
- carpeta `schemas/`
- resumen de certificacion publico

## Flujo recomendado

1. Elegir una familia ya certificada.
2. Preparar una carpeta publica limpia en `familias/<nombre>/`.
3. Publicar solo minis y flows aprobados.
4. Excluir inventario exiliado o experimental.
5. Actualizar `familias/index.json`.
6. Hacer commit y push.

## Regla editorial

La narrativa publica del repo debe hablar de:

- familias
- minis
- flows
- capacidades
- certificacion

Debe evitar nombres internos o rutas privadas.
