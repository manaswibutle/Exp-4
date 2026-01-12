<!DOCTYPE html>
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SIT Nagpur - Event Registration</title>
<style>
body {
 font-family: Arial, sans-serif;

 background-image: url('https://sitnagpur.edu.in/images/contactus_banner.webp');
 background-size: cover;
 background-repeat: no-repeat;
 background-position: center center;
 height: 100vh;
 margin: 0;
}
.form-container {
 background-color: #FFFFFF;
 padding: 20px;
 border: 2px solid #000;
 border-radius: 8px;
 width: 300px;
 position: absolute;
 top: 50%;
 left: 50%;
 transform: translate(-50%, -50%);
}
h2 {
 text-align: center;
}
label {
 display: block;
 margin-top: 10px;
 font-weight: bold;
}
input, select {
 width: 100%;
 padding: 8px;
 margin-top: 5px;
 border: 1px solid #ccc;
 border-radius: 6px;
}
input[type="submit"] {
 background-color: #BD9A7A;
 color: #Ưf;
 border: none;
 margin-top: 15px;
 cursor: pointer;
}
</style>
</head>
<body>
<div class="form-container">
 <h2>SIT Nagpur - Event Registration</h2>
 <form>
 <!-- Name -->
 <label for="name">Name:</label>
 <input type="text" id="name" name="name" required="">
 <!-- Email -->
 <label for="email">Email:</label>
 <input type="email" id="email" name="email" required="">
 <!-- Event Dropdown -->
 <label for="event">Select Event:</label>
 <select id="event" name="event" required="">
 <option value="">--Choose an event--</option>
 <option value="hackathon">Hackathon</option>
 <option value="webdesign">Web Design</option>
 </select>
 <!-- Submit -->
 <input type="submit" value="Register">
 </form>
</div>
</body>
</html> 
