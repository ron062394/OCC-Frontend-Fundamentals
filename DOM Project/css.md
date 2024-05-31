```css
/* General Styling */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-image: linear-gradient(120deg, #ebebeb, #9fdfec);
  color: rgb(0, 0, 0);
  font-family: "Poppins", sans-serif;
  min-height: 100vh;
}

/* Header */
header {
  font-size: 1.5rem;
}

header,
form {
  min-height: 20vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Form */
form input,
form button {
  padding: 0.5rem;
  font-size: 2rem;
  border: none;
  background: white;
}

form button {
  color: #000000;
  background: white;
  cursor: pointer;
  transition: all 0.3s ease;
}

form button:hover {
  background: #000000;
  color: white;
}

/* Custom select dropdown */
select {
  -webkit-appearance: none;
  -moz-appearance: none;
  -ms-appearance: none;
  appearance: none;
  outline: 0;
  box-shadow: none;
  border: 0 !important;
  background-image: none;
}

.select {
  margin: 1rem;
  position: relative;
  overflow: hidden;
}

select {
  color: #000000;
  font-family: "Poppins", sans-serif;
  cursor: pointer;
  width: 12rem;
}

/* Arrow */
.select::after {
  content: "\25BC";
  position: absolute;
  top: 0;
  right: 0;
  padding: 1rem;
  background: #0661ca;
  cursor: pointer;
  pointer-events: none;
}

.filter-todo {
  padding: 1rem;
}

/* todo container */
.todo-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.todo-list {
  min-width: 30%;
  list-style: none;
}

.todo {
  margin: 0.5rem;
  background: white;
  color: black;
  font-size: 1.5rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  transition: all 0.5s ease;
}

.todo li {
  flex: 1;
}

/* Buttons */
.trash-btn,
.complete-btn {
  background: #000000;
  color: white;
  border: none;
  padding: 1rem;
  cursor: pointer;
  font-size: 1rem;
}

.complete-btn {
  background-color: #000000;
}

.todo-item {
  padding: 0rem 0.5rem;
}

.fa-trash,
.fa-check {
  pointer-events: none;
}

.completed {
  text-decoration: line-through;
  opacity: 0.5;
}

.fall {
  transform: translateY(8rem) rotateZ(20deg);
  opacity: 0;
}
```