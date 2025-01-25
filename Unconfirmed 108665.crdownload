function handleSubmit(event) {
    event.preventDefault();
  
    // Get form data
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;
  
    // Display a simple success message
    const responseMessage = document.getElementById('response-message');
    responseMessage.style.color = "green";
    responseMessage.innerHTML = `Thank you, ${name}! Your message has been received.`;
  
    // Optionally, you can send this data to your server here (e.g., using fetch to submit the form).
    
    // Reset form
    document.getElementById('contact-form').reset();
  }
  