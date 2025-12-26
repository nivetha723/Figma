# Ex09 Event Registration Web Application
## Date:26.12.25
## ref no: 25013558

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
~~~
screen 1

<!DOCTYPE html>
<html>
<head>
    <title>Sports Day</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="center">

    <h1>SPORTS DAY EVENTS</h1>

    <button onclick="location.href='events.html'">LOGIN</button>
    <button onclick="location.href='events.html'">REGISTER</button>

</body>
</html>


screen 2

<!DOCTYPE html>
<html>
<head>
    <title>Events</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="events">

    <h2>Sports Day Events</h2>

    <ul>
        <li>Cricket</li>
        <li>Badminton</li>
        <li>Volleyball</li>
        <li>100 MTS</li>
        <li>200 MTS</li>
        <li>4 x 100 Relay</li>
    </ul>

    <button onclick="location.href='register.html'">Next</button>

</body>
</html>


screen 3

<!DOCTYPE html>
<html>
<head>
    <title>Register</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="form">

    <h2>Sports Day Registration</h2>

    <form action="thankyou.html">
        <input type="text" placeholder="Full Name" required>
        <input type="text" placeholder="Register Number" required>
        <input type="text" placeholder="Department" required>
        <input type="email" placeholder="Email ID" required>
        <input type="tel" placeholder="Mobile Number" required>

        <button type="submit">Submit</button>
    </form>

</body>
</html>


screen 4

<!DOCTYPE html>
<html>
<head>
    <title>Thank You</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="thankyou">

    <h2>THANK YOU FOR REGISTERING</h2>
    <p>Your support and enthusiasm are greatly appreciated!</p>

</body>
</html>


style.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    height: 100vh;
}

/* Center screen */
.center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(#e3f2fd, #bbdefb);
}

button {
    width: 200px;
    padding: 12px;
    margin: 10px;
    border: none;
    background-color: #4CAF50;
    color: white;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background-color: #388E3C;
}

/* Events screen */
.events {
    padding: 40px;
    background: linear-gradient(#ffe0b2, #ffcc80);
}

.events ul {
    font-size: 18px;
}

/* Form screen */
.form {
    background: linear-gradient(#e8f5e9, #c8e6c9);
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 40px;
}

form {
    width: 300px;
}

input {
    width: 100%;
    padding: 10px;
    margin: 8px 0;
}

/* Thank you screen */
.thankyou {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(#ede7f6, #d1c4e9);
}
~~~


## OUTPUT:
<img width="1314" height="759" alt="Screenshot 2025-12-26 104343" src="https://github.com/user-attachments/assets/0e76175a-050f-4a70-b1b9-5ae9f8433746" />

![menu](https://github.com/user-attachments/assets/8f82c72b-f5e3-4069-b81b-a2b33ae92269)



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
