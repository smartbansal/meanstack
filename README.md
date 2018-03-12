<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <script src="js/item.js"></script>
    <script src="js/itemOperations.js"></script>
    <script src="js/controller.js"></script>
</head>

<body>
    <table>
        <tr>
            <td><label for="">Id</label></td>
            <td><input type="text" id="id" placeholder="Type Item Id"></td>
        </tr>
        <tr>
            <td><label for="">Name</label></td>
            <td><input type="text" id="name" placeholder="Type Item Name"></td>
        </tr>
        <tr>
            <td><label for="">Price</label></td>
            <td><input min="1" value="10" max="100" type="range" id="price">
                <output id="output">0</output>
            </td>

        </tr>
        <tr>
            <td><label for="">Date</label></td>
            <td><input type="date" id="date"></td>
        </tr>
        <tr>
            <td><label for="">Color</label></td>
            <td><input type="color" id="color"></td>
        </tr>
        <tr>
            <td><label for="">Desc</label></td>
            <td><textarea id="desc" cols="30" rows="10"></textarea></td>
        </tr>
        <tr>
            <td colspan="2">
                <table>
                    <tr>
                        <td><button id="add">Add</button></td>
                        <td><button>Delete</button></td>
                        <td><button>Update</button></td>
                        <td><button>Save</button></td>
                        <td><button>Load</button></td>
                        <td><button>Search</button></td>
                        <td><button>Sort</button></td>
                        <td><button>Load From Server</button></td>
                        <td><button>Clear All</button></td>

                    </tr>
                </table>
            </td>

        </tr>
    </table>
    <fieldset>
        <legend>Item List</legend>
        <table border="1">
            <thead>
                <tr>
                    <td>Id</td>
                    <td>Name</td>
                    <td>Price</td>
                    <td>Color</td>
                    <td>Date</td>
                    <td>Desc</td>
                    <td>Operations</td>
                </tr>
            </thead>
            <tbody id="items">

            </tbody>
        </table>
    </fieldset>
</body>

</html>
