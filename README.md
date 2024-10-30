<table>
  <tr>
    <th rowspan="6">VENTAS</th>
    <th>Campo</th>
    <th>Tipo de Campo</th>
    <th>Tipo de Clave</th>
  </tr>
  <tr>
    <td>ID_Ventas</td>
    <td>INT / NOT NULL / AUTO_INCREMENT</td>
    <td>PK</td>
  </tr>
  <tr>
    <td>ID_Producto</td>
    <td>INT / NOT NULL</td>
    <td>FK</td>
  </tr>
  <tr>
    <td>ID_Factura</td>
    <td>INT / NOT NULL</td>
    <td>FK</td>
  </tr>
  <tr>
    <td>ID_Metodo</td>
    <td>INT / NOT NULL</td>
    <td>FK</td>
  </tr>
  <tr>
    <td>Cantidad</td>
    <td>INT</td>
    <td>-</td>
  </tr>
</table>


