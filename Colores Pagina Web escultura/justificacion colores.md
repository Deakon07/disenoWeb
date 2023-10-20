> # Entregable colores Diseño de Interfaces Web

## Autor: Francisco Javier Guillén Puente

### He elegido los colores de la página web de escultura, del mismo color de los materiales que trabaja el cliente (Gabriel Casado) como son por ejemplo: madera, barro, arcilla, policromía de imágenes y como color de fondo gris,ayudando a transmitir la esencia de su arte escultórico. Estos colores crean un ambiente visual que resalta la belleza y lo unicidad de su trabajo artístico.

### Entrando en más detalle

#### Color de fondo: #E5E5E3 (gris claro)

El gris claro se ha elegido como color de fondo para la página web siendo un color neutral que proporciona un telón de fondo tranquilo y equilibrado, lo que permite que los colores de las obras de arte de Gabriel Casado destaquen. Además, el gris a menudo se asocia con la sofisticación y la serenidad, lo que puede reflejar la naturaleza artística y contemplativa de la escultura.

### Muestra 1 Policromía #E6C7C2 (un tono rosa pálido)

El rosa pálido se ha elegido para representar la policromía, la aplicación de diversos colores otorgando realismo a la figura. Este color puede simbolizar la creatividad y la delicadeza.

### Muestra 2 Barro: #974E3F (un tono marrón)

El marrón se asemeja a la madera, un material común en la escultura. Este color evoca la sensación cálida y natural de la madera, lo que puede crear una conexión inmediata con el visitante a la página o el cliente.

### Muestra 3 Arcilla: #826E6F (un tono gris verdoso)

El gris verdoso se relaciona con la arcilla, un material versátil en la escultura.

### Muestra 4: Terracota #550000 (un tono rojo oscuro)

El rojo oscuro, se representa como el barro, la arcilla modelada y posterioemente endurecida al horno. Se usará para acentuar elementos clave en la página. Además es un color llamativo y emocional que puede utilizarse para destacar información importante, como botones de llamada a la acción o títulos, atrayendo la atención del visitante hacia ciertos aspectos del sitio.

![](./Justificación%20colores.png)

**Fichero HTML**

```
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>Colores Gabriel Casado Ponce</title>
    <link rel="stylesheet" href="ColoresWeb.css" />
  </head>
  <body>
    <h1>Colores de la página web de escultura</h1>

    <table class="color-table">
      <tr>
        <th>Colores primarios:</th>
        <td class="sample sample-0 primary-0">
          <div>GRIS CLARO #E5E5E3</div>
        </td>
        <td class="sample sample-1 primary-1">
          <div class="blanco">POLICROMÍA #E6C7C2</div>
        </td>
        <td class="sample sample-2 primary-2">
          <div class="blanco">BARRO #974E3F</div>
        </td>
        <td class="sample sample-3 primary-3">
          <div class="blanco">ARCILLA #826E6F</div>
        </td>
        <td class="sample sample-4 primary-4">
          <div class="blanco">TERRACOTA #550000</div>
        </td>
      </tr>
    </table>

    <hr />
  </body>
</html>

```

**FICHERO CSS**

```
.primary-0 {
  background-color: #e5e5e3;
}
.primary-1 {
  background-color: #e6c7c2;
}
.primary-2 {
  background-color: #974e3f;
}
.primary-3 {
  background-color: #826e6f;
}
.primary-4 {
  background-color: #550000;
}

body {
  margin: 0;
  padding: 2em;
  background: #fff;
  color: #000;
  font: 12px/1.33 "Segoe UI", "Helvetica Neue", Helvetica, sans-serif;
  text-align: left;
}
h1 {
  margin: 0.5em 0;
  font-size: 200%;
}
p {
  margin: 0.5em 0;
}

.color-table {
  margin: 2em 2em 5em;
  border-collapse: collapse;
  border: none;
  border-spacing: 0;
  font-size: 100%;
}
.color-table th {
  padding: 0 1em 0 0;
  text-align: right;
  vertical-align: middle;
  font-size: 100%;
  font-weight: normal;
  border: none;
}
.color-table td.sample {
  width: 6em;
  height: 6em;
  padding: 10px;
  text-align: center;
  vertical-align: middle;
  font-size: 90%;
  border: 1px solid white;
  white-space: nowrap;
}
.color-table td.sample-0 {
  width: 18em;
}
.color-table.small td.sample {
  width: 3em;
  height: 3em;
  padding: 0;
  border: none;
}
.color-table.small td.sample-0 {
  width: 9em;
}

.color-table .blanco {
  margin-bottom: 0.2em;
  color: white;
}
.color-table .black {
  margin-top: 0.2em;
  color: black;
}

hr {
  margin: 2em 0 1em 0;
  border: none;
  border-bottom: 1px solid silver;
}


```

### Descargas

- [coloresWeb.html](./ColoresWeb.html)
- [ColoresWeb.css](./ColoresWeb.css)

### Subida a la Moodle

- [Justificación colores](./Fguillen[1749]Justificacion_colores.zip)
