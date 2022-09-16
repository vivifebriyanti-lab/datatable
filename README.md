# datatable
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>latihan 1</title>
    <link rel="stylesheet" href="DataTables/datatables.min.css">
</head>
<body>
    <table id="contoh" class="display">
        <thead>
            <tr>
                <th width="5%">No</th>
                <th width="12%">Nama</th>
                <th width="15%">Kelas</th>
                <th width="15%">Alamat</th>
                <th width="5%">No HP</th>
            </tr>
            <tr>
                <td>3</td>
                <td>vivi/td>
                <td>XII k1</td>
                <td>jalan kiputih</td>
                <td>085607831212</td>
             </tr>  
            <tr>
                <td>3</td>
                <td>vivi</td>
                <td>XII k1</td>
                <td>jalan kiputih</td>
                <td>085607831212</td>
            </tr>
        </thead>
    </table>
<script src="DataTables/jQuery-3.6.0/jquery-3.6.0.min.js"></script>
<script src="DataTables/datatables.min.js"></script>
<script>
    $(function(){
        //  var data = [
        // ["1", "vivi ", "XII RPL 1","jalan kiputih", "085607831212"]
        // ["1", "febri", "XII RPL 1","jalan kiputih", "085607831212"]
        // ];
        var data = [];

        for (let i = 0; i <5;j++){
            data.push([i]);
                data[i].push[j];
        }
        $("#contoh").DataTable({
            responsive : true
        });
    });
</script>
</body>
</html>
