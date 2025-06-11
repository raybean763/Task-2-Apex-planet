# Task-2-Apex-planet
#This is apex planet Task 2 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact Form</title>
  <link rel="stylesheet" href="task2R.css" />
</head>
<body>
  <header>
    <nav>
      <h1>My Website</h1>
    </nav>
  </header>

  <main class="grid-container">
    <section class="form-section">
      <h2>Contact Us</h2>
      <form id="contactForm">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit">Submit</button>
      </form>
    </section>
    
    <section class="todo-section">
      <h2>To-Do List</h2>
      <div id="todoApp">
        <input type="text" id="todoInput" placeholder="Add a task" />
        <button onclick="addTodo()">Add</button>
        <ul id="todoList"></ul>
      </div>
    </section>
  </main>

  <script src="task2R.js"></script>
</body>
</html>
