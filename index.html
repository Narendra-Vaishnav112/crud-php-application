<?php
$insert=false;
$update=false;
$delete=false;
//connecting to the sql database
$s_name="localhost";
$u_name="root";
$password="";
$db_name="notes";

$conn=mysqli_connect($s_name,$u_name,$password,$db_name);

// error handling 
if(!$conn){
    echo "database is not connected because of errr" . mysqli_connect_error();
}
if(isset($_GET['delete'])){
    $sno=$_GET['delete'];
    $delete=true;
    $sql="DELETE FROM `notes` WHERE `sno`=$sno";
    $result=mysqli_query($conn,$sql);
   
}
// update notes in database
if ($_SERVER['REQUEST_METHOD']=='POST'){
    if (isset($_POST['snoEdit'])){
        $sno=$_POST['snoEdit'];
        $title=$_POST['titleEdit'];
        $description=$_POST['descriptionEdit'];

        $sql="UPDATE `notes` SET `title` = '$title' , `description` = '$description' WHERE `notes`.`sno` = $sno";
        $result=mysqli_query($conn,$sql);
        if($result){
            $update=true;
        }
        else{
            echo "record is not updated yet";
        }

        
    }
    else{
        $title=$_POST['title'];
        $description=$_POST['description'];

        $sql="INSERT INTO `notes` (`title`,`description`) VALUES ('$title','$description' )";
        $result=mysqli_query($conn,$sql);

        if($result){
            // echo "your records have been submited successfully";
            $insert=true;
        }

        else{
            echo "your records have not recorder successsfully because of ",mysqli_error();
        }}}
?>
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <link rel="stylesheet" href="//cdn.datatables.net/1.10.25/css/jquery.dataTables.min.css">
    <script src="https://code.jquery.com/jquery-3.6.0.js"
        integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk=" crossorigin="anonymous"></script>
    <script src="//cdn.datatables.net/1.10.25/js/jquery.dataTables.min.js"></script>


    <title>iNotes- make notes easy</title>
</head>

<body>

    <!--Edit-modal -->
    <!-- <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#editModal">
  EditModal
</button> -->

    <!--Edit- Modal -->
    <div class="modal fade" id="editModal" tabindex="-1" aria-labelledby="editModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="editModalLabel">Edit -Modal</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <form action="/crud/index.php" method="post">
                    <div class="modal-body">
                        <input type="hidden" name="snoEdit" id="snoEdit">
                        <div class="mb-3">
                            <label for="title" class="form-label">Note Title</label>
                            <input type="text" class="form-control" id="titleEdit" name="titleEdit"
                                aria-describedby="emailHelp">
                        </div>


                        <div class="mb-3">
                            <label for="description" class="form-label">Note Description</label>
                            <textarea class="form-control" id="descriptionEdit" name="descriptionEdit"
                                rows="3"></textarea>
                        </div>

                        
                    </div>
                    <div class="modal-footer d-block mr-auto">
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                        <button type="submit" class="btn btn-primary">Save changes</button>
                    </div>
                </form>
            </div>
        </div>
    </div>


    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#"> <img src="/crud/logo.svg" height="28px"> </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact Us</a>
                    </li>

                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
            </div>
        </div>
    </nav>
    <?php
    if($insert){
       echo  "<div class='alert alert-success alert-dismissible fade show' role='alert'>
        <strong>Success!</strong> your data has been submitted successfully.
        <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
      </div>";
    }
    if($delete){
       echo  "<div class='alert alert-success alert-dismissible fade show' role='alert'>
        <strong>Success!</strong> your data has been deleted successfully.
        <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
      </div>";
    }
    if($update){
       echo  "<div class='alert alert-success alert-dismissible fade show' role='alert'>
        <strong>Success!</strong> your data has been updated successfully.
        <button type='button' class='btn-close' data-bs-dismiss='alert' aria-label='Close'></button>
      </div>";
    }
    ?>

    <div class="container my-4">
        <h2>Add a note to iNotes app</h2>
        <form action="/crud/index.php" method="post">
            <div class="mb-3">
                <label for="title" class="form-label">Note Title</Title></label>
                <input type="text" class="form-control" id="title" name="title" aria-describedby="emailHelp">
            </div>


            <div class="mb-3">
                <label for="description" class="form-label">Note Description</label>
                <textarea class="form-control" id="description" name="description" rows="3"></textarea>
            </div>

            <button type="submit" class="btn btn-primary">Add Note</button>
        </form>
    </div>
    <div class="container my-4 ">

        <table class="table" id="myTable">
            <thead>
                <tr>
                    <th scope="col">sno</th>
                    <th scope="col">Title</th>
                    <th scope="col">Decription</th>
                    <th scope="col">Actions</th>
                </tr>
            </thead>
            <tbody>
                <?php
        // running a sql query
     
        $sql="SELECT * FROM `notes`";
        $result=mysqli_query($conn,$sql); 

        // fetching all the data of respective table of notes
        $s_no=1;
        while($row=mysqli_fetch_assoc($result)){
           echo  "<tr>
                    <th scope='row' >". $s_no ." </th>
                    <td>". $row['title'] ."</td>
                    <td>" . $row['description'] ."  </td>
                    <td> <button id= ".$row['sno']." class='edit btn btn-sm btn-primary'>Edit</button><button id= d".$row['sno']." class='delete btn btn-sm btn-primary'>Delete</button>
                    </td>
                </tr>";
            $s_no+=1;
            
            echo "<br>";
        }
        
       
       
        ?>

            </tbody>
        </table>
    </div>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4"
        crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
    -->
    <script>
        $(document).ready(function () {
            $('#myTable').DataTable();
        });
    </script>

    <script>
        edits = document.getElementsByClassName("edit");
        Array.from(edits).forEach((element) => {
            element.addEventListener("click", (e) => {
                console.log("edit",);
                tr = e.target.parentNode.parentNode;
                title = tr.getElementsByTagName("td")[0].innerText;
                description = tr.getElementsByTagName("td")[1].innerText;
                console.log(title, description);
                titleEdit.value = title;
                descriptionEdit.value = description;
                snoEdit.value = e.target.id;
                console.log(e.target.id);
                $('#editModal').modal('toggle');
            })

        })
        deletes = document.getElementsByClassName("delete");
        Array.from(deletes).forEach((element) => {
            element.addEventListener("click", (e) => {
                console.log("edit",);
                sno = e.target.id.substr(1,);
                if (confirm("Are you sure! you want to delete this note")) {
                    console.log("yes");
                    window.location = `/crud/index.php?delete=${sno}`;
                }
                else {
                    console.log("no");
                }
            })

        })
    </script>
</body>

</html>
