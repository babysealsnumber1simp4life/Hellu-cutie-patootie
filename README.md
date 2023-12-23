# Hellu-cutie-patootie
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ask Out</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
      background: url(https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.freepik.com%2Ffree-photos-vectors%2Fcute-heart-background&psig=AOvVaw3YOdNqG_Zjl1VkZzmj4Mqj&ust=1703411999660000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCLDj0rKmpYMDFQAAAAAdAAAAABAD) no-repeat center center fixed;
      background-size: cover;
    }
    .container {
      margin-top: 50px;
      color: pink;
    }
    h2 {
      color: pink;
    }
    button {
      font-size: 16px;
      margin: 10px;
      padding: 10px 20px;
      cursor: pointer;
      background-color: pink;
      border: none;
      color: white;
      border-radius: 5px;
    }
  </style>
</head>
<body>

<div class="container">
  <h2>Dear baby seal,</h2>
  <h1>Would you like to be my date for 2024 and forever?</h1>
  <button onclick="displayMessage('yes')">Yes</button>
  <button onclick="displayMessage('no')">No</button>
</div>

<script>
  function displayMessage(response) {
    if (response === 'yes') {
      alert("Yes, that's right! You're stuck with me, hehehe. Don't even try to say no.");
    } else if (response === 'no') {
      alert("Aww, don't be like that. Try again.");
      window.location.href = 'index.html'; // Replace 'index.html' with the actual home page URL
    }
  }
</script>

</body>
</html>
