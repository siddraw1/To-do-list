# To-do-list
This is a full-stack To-Do List web application that helps users manage their daily tasks. It allows users to add new tasks, update them, mark them as completed, and delete them when no longer needed. 
# html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://kit.fontawesome.com/f30fac2c61.js" crossorigin="anonymous"></script>
    <link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Catamaran:wght@200&family=Courgette&family=Edu+TAS+Beginner:wght@700&family=Lato:wght@300;900&family=Mukta:wght@700&family=Mulish:wght@300&family=Open+Sans&family=PT+Sans:ital,wght@1,700&family=Poppins:wght@300&family=Raleway:wght@100&family=Roboto+Condensed:wght@700&family=Roboto+Slab&family=Roboto:wght@300;400&family=Source+Sans+Pro:wght@300&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="Todo.css">
</head>
<body>
   <div class="container">
    <h1>ToDo App</h1>
    <div class="inputs">
        <input type="text" placeholder="Enter Your Task" id="inp">
        <button onclick="Add()">Add</button>
    </div>
    <div class="text">
        
    </div>
   </div>

    <script src="Todo.js"></script>
</body>
</html>
