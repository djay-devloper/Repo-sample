function sayHello() {
  const name = document.getElementById("nameInput").value;
  const greeting = document.getElementById("greeting");

  if (name.trim() !== "") {
    greeting.textContent = `Hello, ${name}! 👋 Welcome!`;
  } else {
    greeting.textContent = "Hello! 👋 Please enter your name.";
  }
}
