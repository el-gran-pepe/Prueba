<table>
  <tr>
    <th rowspan="9">PRODUCTO</th>
    <th>Campo</th>
    <th>Tipo de Campo</th>
    <th>Tipo de Clave</th>
  </tr>
  <tr>
    <td>ID_Producto</td>
    <td>INT / NOT NULL / AUTO_INCREMENT </td>
    <td>PK</td>
  </tr>
  <tr>
    <td>Producto</td>
    <td>VARCHAR (255)</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Producto_Completo</td>
    <td>VARCHAR (255)</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Etiqueta</td>
    <td>VARCHAR (100)</td>
    <td>-</td>
  </tr>
  <tr>
    <td>ID_Categoría</td>
    <td>VARCHAR (20)</td>
    <td>FK</td>
  </tr>
  <tr>
    <td>ID_Marca</td>
    <td>INT / NOT NULL</td>
    <td>FK</td>
  </tr>
  <tr>
    <td>Precio</td>
    <td>DECIMAL (10,2)</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Costo</td>
    <td>DECIMAL (10,2)</td>
    <td>-</td>
  </tr>
</table>

