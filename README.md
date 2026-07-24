# Tableros AB Agro · AB Energía

Portal único de los tableros de gestión. Una sola clave para todo.

**Link:** https://ludmilameiners.github.io/ABtableros/

| Página | Qué muestra |
|---|---|
| `index.html` | Portada con las tarjetas de los módulos |
| `financiera.html` | Proyección financiera semanal ABA + ABE |
| `hacienda.html` | Feedlot: stock, GDP, conversión, ventas |
| `planta.html` | Planta de biogás: generación por sustrato, costos USD/MWh, ociosidad, simulador |
| `tesoreria.html` | Tesorería diaria (uso interno — sin tarjeta en la portada) |

## Cómo actualizar

Los archivos de este repo son el resultado cifrado; no se editan a mano. Se regeneran con
`C:\CLAUDE\portal\build_portal.py`, que toma el contenido de cada módulo desde su origen
y lo vuelve a cifrar con la clave del portal. Después: Commit + Push desde GitHub Desktop.

La clave se define en la variable `PORTAL_KEY` de ese script.
