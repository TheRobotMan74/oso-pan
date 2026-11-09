# Oso Pan

App instalable (PWA) de Panaderoso: ingresos y egresos, pedidos, producción, inventario, meta del mes,
productos y recetas. Es una página estática que habla con el Apps Script de la hoja
"Panaderoso Control V2" por su URL `/exec`:

- `POST /exec` con `{ accion, args, clave }` → `{ ok, datos }` o `{ ok: false, error }`

La URL `/exec` y la clave se ponen en la app (botón ⚙) y solo se guardan en ese aparato; no están en este repo.
