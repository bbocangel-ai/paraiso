# Propiedad Paraíso — landing

## Dos versiones, para dos usos

**`paraiso-un-archivo.html`** — todo adentro, imágenes incluidas. Lo abrís con doble
clic desde donde sea y se ve completo. Sirve para revisarlo, mostrarlo en el celular
o mandarlo por correo. No lo subas a GitHub: pesa 1,7 MB y es más lento.

**`index.html` + carpeta `img/`** — es la versión para publicar. Las imágenes van
por separado, así carga más rápido. Los dos archivos tienen que estar juntos:
si abrís `index.html` solo, sin la carpeta `img/` al lado, no vas a ver ninguna foto.

## Antes de publicar (obligatorio)

Abrí `index.html` y buscá `591XXXXXXXX`. Aparece **tres veces** (botón principal,
botón flotante y el link precargado). Reemplazá las tres.
Reemplazalo por el número real en formato internacional, sin `+`, sin espacios, sin guiones.

Ejemplo: para el 7XX-XXXXX de Bolivia → `5917XXXXXXX`

El mensaje precargado ya viene escrito: *"Hola, vi la página de la Propiedad Paraíso en Ipías y quiero más información."*
Si querés cambiarlo, editá el texto después de `?text=` (los espacios van como `%20`).

## Publicar en GitHub Pages

1. Creá un repositorio nuevo, público. Nombre sugerido: `paraiso`
2. Subí `index.html` y la carpeta `img/` completa a la raíz del repo
   (botón **Add file → Upload files**, arrastrás todo, **Commit changes**)
3. Andá a **Settings → Pages**
4. En *Source* elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guardá.
5. En 1–2 minutos la página queda en:
   `https://TUUSUARIO.github.io/paraiso/`

Ese es el link que mandás por WhatsApp.

## Estructura

```
index.html                    ← todo el sitio, un solo archivo
img/
  aerea-monte.jpg             ← foto principal (hero)
  aerea-potreros.jpg          ← sección Agua
  aerea-corral.jpg            ← sección Infraestructura
  casco.jpg                   ← vivienda
  potreros-delanteros.jpg     ← mapa 250 ha
  potreros-fondo.jpg          ← mapa 300 ha
  mapa-general.jpg            ← perímetro titulado
  acceso.jpg                  ← mapa Ipías → Paraíso
```

Para cambiar una foto: reemplazá el archivo en `img/` conservando el mismo nombre.

## Vocabulario usado

Santa Cruz, no rioplatense: **campamento** (no "casco"), **pastura sembrada**
(no "implantada"), **carretera** (no "ruta"), **ganado** (no "hacienda").
Se eliminó "zafra", que en Bolivia es de caña.

## Qué NO dice la página, a propósito

- Carga animal actual ni receptividad estimada
- Superficie desmontable ni promesas de permisos
- Precio
- Adjetivos de venta: la ficha declara datos, no los interpreta

## Dos líneas para que revises con tu papá

En la nota al pie de la ficha dice que la propiedad **está arrendada**.
Es información material que el comprador va a preguntar igual, pero si preferís
manejarla recién en la conversación, borrá esa frase del `index.html`.

Y dice **"título y plano en regla"**. Es la versión prudente. Si tienen la
Función Económico Social aprobada y quieren declararlo, se puede ser más
específico — pero sólo si está documentado.
