<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Todo App</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link href="style.css" rel="stylesheet">
</head>

<body>
  <header>
    <h1 class="my-4">TODO APPLICATION</h1>
  </header>
  <div class="container">
    <h2>Add Tasks</h2>
   <div class="input-group mb-3">
      <input type="text" id="taskInput" class="form-control" placeholder="Task Name"> &nbsp;
      <input type="datetime-local" id="dateTimeInput" class="form-control" value="">
      <div class="input-group-append">
        <button class="btn btn-primary" onclick="addTask()">Add</button>
      </div>
    </div>
    <ul id="taskList" class="list-group mt-3">
    </ul>
    <div class="form-check">
      <input type="checkbox" id="completedFilter" class="form-check-input" onclick="filterTasks()">
      <label class="form-check-label">Completed tasks</label>
    </div>
  </div>

  <footer class="footer">
    <div class="container2">
      <div class="row">
        <div class="footer-col">
          <h4>Created by</h4>
          <ul>
            <li><a href="https://github.com/MAHESH3779" >20MH1A0551 - Mahesh Babu Sabbathi</a></li>
            <li><a href="https://github.com/harshithvulisetti">20MH1A0564 - Harshith Vulisetti</a></li>
            <li><a href="https://github.com/SANJEEV2980">21MH5A0508 - Sanjeev Kumar Nela</a></li>
            <li><a href="https://github.com/avanthikaMandapati">21MH5A0504 - Avanthika Mandapati</a></li>
          </ul>
        </div>
        <div class="footer-col">
          <h4>Help</h4>
          <ul>
            <li><a href="instructions.html" >Instructions</a></li>
            <li><a href="about.html" >About</a></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>

</html># TODO-App
