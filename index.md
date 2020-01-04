<head>
<script
  src="https://code.jquery.com/jquery-3.4.1.min.js"
  integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
  crossorigin="anonymous"></script>
<link rel="stylesheet" type="text/css" href="//cdn.datatables.net/1.10.13/css/jquery.dataTables.css">
<script type="text/javascript" charset="utf8" src="//cdn.datatables.net/1.10.20/js/jquery.dataTables.min.js"></script>
<script>
      $(document).ready(function(){
          $('div.datatable-begin').nextUntil('div.datatable-end', 'table').addClass('display');
          $('table.display').DataTable( {
              paging: true,
              stateSave: true,
              searching: true
          });
       });
</script>
</head>



<div class="datatable-begin"></div>
<table>
<thead>
<tr>
<th>Food</th>
<th>Description</th>
<th>Category</th>
<th>Sample type</th>
</tr>
</thead>
<tbody>
<tr>
<td>Apples</td>
<td>A small, somewhat round and often red-colored, crispy fruit grown on trees.</td>
<td>Fruit</td>
<td>Fuji</td>
</tr>
<tr>
<td>Bananas</td>
<td>A long and curved, often-yellow, sweet and soft fruit that grows in bunches in tropical climates.</td>
<td>Fruit</td>
<td>Snow</td>
</tr>
<tr>
<td>Kiwis</td>
<td>A small, hairy-skinned sweet fruit with green-colored insides and seeds.</td>
<td>Fruit</td>
<td>Golden</td>
</tr>
<tr>
<td>Oranges</td>
<td>A spherical, orange-colored sweet fruit commonly grown in Florida and California.</td>
<td>Fruit</td>
<td>Navel</td>
</tr>
</tbody>
</table>
<div class="datatable-end"></div>

