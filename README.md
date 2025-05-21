# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
home page 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Home</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #6f6d46;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .phone-container {
      width: 390px;
      height: 844px;
      border-radius: 40px;
      overflow: hidden;
      border: 2px solid #ccc;
      background: linear-gradient(180deg, #fddde6, #ffe9c7, #e4d4f4); /* pastel */
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
      position: relative;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .header {
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 15px;
    }

    .header img {
      height: 50px;
    }

    .tnea-code {
      background-color: #003e91;
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 5px;
      font-size: 14px;
    }

    .logo {
      margin-top: 30px;
      width: 100px;
      height: 100px;
    }

    .btn {
      width: 200px;
      padding: 15px;
      margin: 20px 0;
      font-size: 16px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      font-weight: bold;
    }

    .btn-register {
      background-color: #a9e5ac;
    }

    .btn-login {
      background-color: rgba(255, 255, 255, 0.5);
    }
  </style>
</head>
<body>
  <div class="phone-container">
    <div class="header">
      <img src="https://i.imgur.com/T0QJ6O2.png" alt="Saveetha Logo">
      <div class="tnea-code">1216</div>
    </div>

    <img src="https://i.imgur.com/5AJJ2hH.png" alt="College Logo" class="logo"> <!-- Replace with your own if needed -->

    <button class="btn btn-register">REGISTER</button>
    <button class="btn btn-login">LOGIN</button>
  </div>
</body>
</html>

Events


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cultural Events</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #6f6d46;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .phone-container {
      width: 390px;
      height: 844px;
      border-radius: 40px;
      overflow: hidden;
      border: 2px solid #ccc;
      background: linear-gradient(180deg, #fddde6, #ffe9c7, #e4d4f4); /* pastel bg */
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
      position: relative;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
    }

    .header img {
      height: 50px;
    }

    .header .tnea-code {
      background-color: #003e91;
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 5px;
      font-size: 14px;
    }

    .title {
      text-align: center;
      font-size: 20px;
      margin: 20px 0 30px;
      font-weight: bold;
      color: #333;
    }

    .event-list {
      list-style: none;
      padding: 0 30px;
      margin: 0;
    }

    .event-item {
      display: flex;
      align-items: center;
      margin-bottom: 30px;
      font-size: 18px;
      font-weight: 500;
      color: #000;
    }

    .event-item span {
      font-size: 24px;
      margin-right: 15px;
      color: #8359a0;
    }
  </style>
</head>
<body>
  <div class="phone-container">
    <div class="header">
      <img src="https://i.imgur.com/T0QJ6O2.png" alt="Saveetha Logo" />
      <div class="tnea-code">1216</div>
    </div>
    <div class="title">CULTURAL’S DAY EVENT</div>
    <ul class="event-list">
      <li class="event-item"><span>★</span>SOLO DANCE</li>
      <li class="event-item"><span>★</span>SOLO SONG</li>
      <li class="event-item"><span>★</span>GROUP DANCE</li>
      <li class="event-item"><span>★</span>GROUP SONG</li>
      <li class="event-item"><span>★</span>DRAMA</li>
    </ul>
  </div>
</body>
</html>


Registration

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Registration Form - Saveetha</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #6f6d46;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .phone-container {
      width: 390px;
      height: 844px;
      border-radius: 40px;
      overflow: hidden;
      border: 2px solid #ccc;
      background: linear-gradient(180deg, #fddde6, #ffe9c7, #e4d4f4); /* pastel background */
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
      position: relative;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
    }

    .header img {
      height: 50px;
    }

    .header .tnea-code {
      background-color: #003e91;
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 5px;
      font-size: 14px;
    }

    .form-section {
      padding: 20px;
      margin-top: 20px;
    }

    .form-section h2 {
      text-align: center;
      color: #3e6934;
      font-size: 20px;
      margin-bottom: 10px;
    }

    .form-section label {
      display: block;
      margin-top: 15px;
      margin-bottom: 5px;
      font-weight: bold;
      color: white;
      background-color: #b36cae;
      padding: 10px;
      border-radius: 5px;
    }

    .form-section input {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 5px;
      margin-bottom: 10px;
      font-size: 16px;
    }

    .form-section button {
      width: 100%;
      padding: 12px;
      background-color: #b36cae;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 18px;
      margin-top: 20px;
      cursor: pointer;
    }

    .form-section button:hover {
      background-color: #a25aa1;
    }
  </style>
</head>
<body>
  <div class="phone-container">
    <div class="header">
      <img src="https://i.imgur.com/T0QJ6O2.png" alt="Saveetha Logo" />
      <div class="tnea-code">1216</div>
    </div>
    <div class="form-section">
      <h2>REGISTRATION FORM</h2>
      <form>
        <label for="regno">register no:</label>
        <input type="text" id="regno" name="regno" placeholder="Enter register number">

        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name">

        <label for="age">Age:</label>
        <input type="number" id="age" name="age" placeholder="Enter your age">

        <label for="department">Department:</label>
        <input type="text" id="department" name="department" placeholder="Enter your department">

        <button type="submit">Register</button>
      </form>
    </div>
  </div>
</body>
</html>


thank you

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Thank You - Saveetha</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #6f6d46; /* Outer background */
    }

    .phone-container {
      width: 390px;
      height: 844px;
      border-radius: 40px;
      border: 2px solid #ccc;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      overflow: hidden;
      background: linear-gradient(180deg, #fddde6, #ffe9c7, #e4d4f4); /* pastel gradient */
      position: relative;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
      background: transparent;
    }

    .header img {
      height: 50px;
    }

    .header .tnea-code {
      background-color: #003e91;
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 5px;
      font-size: 14px;
    }

    .thank-you {
      text-align: center;
      margin-top: 100px;
      padding: 0 20px;
    }

    .thank-you h1 {
      color: #3e6934;
      font-size: 24px;
      margin-bottom: 30px;
    }

    .thank-you p {
      color: #4d89b6;
      font-size: 18px;
      line-height: 1.4;
    }
  </style>
</head>
<body>
  <div class="phone-container">
    <div class="header">
      <img src="https://i.imgur.com/T0QJ6O2.png" alt="Saveetha Logo" />
      <div class="tnea-code">1216</div>
    </div>
    <div class="thank-you">
      <h1>THANK YOU</h1>
      <p>We are eagerly waiting for your participation in the cultural events</p>
    </div>
  </div>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-05-21 045201.png>)
![alt text](<Screenshot 2025-05-21 045210.png>)
![alt text](<Screenshot 2025-05-21 045223.png>)
![alt text](<Screenshot 2025-05-21 045233.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
