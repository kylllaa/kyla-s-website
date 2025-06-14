function respondToQuestion() {
  const question = document.getElementById("question").value.trim();
  const responseElement = document.getElementById("response");

  if (!question) {
    responseElement.textContent = "Please type a question!";
    return;
  }

  if (question.toLowerCase().includes("name")) {
    responseElement.textContent = "I'm your friendly JavaScript bot!";
  } else if (question.toLowerCase().includes("weather")) {
    responseElement.textContent = "I can't check the weather, but it looks great in here!";
  } else {
    responseElement.textContent = "That's a great question! Let me get back to you.";
  }

  document.getElementById("question").value = "";
}
