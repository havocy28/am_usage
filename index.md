<head>
<script
  src="https://code.jquery.com/jquery-3.4.1.min.js"
  integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
  crossorigin="anonymous"></script>
  <link rel="stylesheet" type="text/css" href="//cdn.datatables.net/1.10.13/css/jquery.dataTables.css">
  <script type="text/javascript" charset="utf8" src="//cdn.datatables.net/1.10.20/js/jquery.dataTables.min.js"></script>
  <script>
  $(document).ready(function() {
      $('#example').DataTable( {
          "ajax": "Export.json"
      } );
  } );
  </script>
</head>


		


<table id="example" class="display" style="width:100%">
        <thead>
            <tr>
                <th>Ingredient</th>
                <th>ASTAG Rating</th>
                <th>WHO Rating</th>
                <th>System Antimicrobial Consults (%)</th>
                <th>Topical Antimicrobial Consults (%)</th>
            </tr>
        </thead>
        <tfoot>
            <tr>
                <th>Ingredient</th>
                <th>ASTAG Rating</th>
                <th>WHO Rating</th>
                <th>System Antimicrobial Consults (%)</th>
                <th>Topical Antimicrobial Consults (%)</th>
            </tr>
        </tfoot>
 </table>

