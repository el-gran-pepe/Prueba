<table>
  <tr>
    <th rowspan="7">FACTURA</th>
    <th>Campo</th>
    <th>Tipo de Campo</th>
    <th>Tipo de Clave</th>
  </tr>
  <tr>
    <td>ID_Factura</td>
    <td>INT / NOT NULL / AUTO_INCREMENT</td>
    <td>PK</td>
  </tr>
  <tr>
    <td>Fecha</td>
    <td>DATE</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Hora</td>
    <td>TIME</td>
    <td>-</td>
  </tr>
  <tr>
    <td>ID_Tipo</td>
    <td>INT / NOT NULL</td>
    <td>FK</td>
  </tr>
  <tr>
    <td>ID_Producto</td>
    <td>INT / NOT NULL</td>
    <td>FK</td>
  </tr>
  <tr>
    <td>ID_Dis</td>
    <td>INT / NOT NULL</td>
    <td>FK</td>
  </tr>
</table>


