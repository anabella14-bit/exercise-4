<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Registration Page</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            height: 100%;
            font-family: cursive, sans-serif;
            background: linear-gradient(135deg, #002a6c, #fbb040)
        }
          .wrapper {
            background: rgba(400, 400, 400, 0.50);
            width: 500px;
            border: 2px solid #ccc;
            display: grid;
            justify-content: center;
            align-items: center;
            padding: 20px;
            border-radius: 8px;
            margin-top: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        #header {
            background-image: url("11.png");
            background-position: center;
            background-repeat: no-repeat;
            background-size: contain;
            width: 500px;
            height: 200px;
            display: flex;
            justify-content: center;
            align-items: center;    
            margin: 0;
            border: 0;
        }
        .details {
            margin: 20px 0;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input {
            padding: 10px;
            width: 100%;
            max-width: 500px;
            box-sizing: border-box;
            border-radius: 10px; 
        }
        select {
             padding: 10px;
            width: 100%;
            max-width: 500px;
            box-sizing: border-box;
            border-radius: 10px; 
        }

        #buttonWrapper{
            width: 30px;
            display: flex;
            justify-content: center;
            margin: 20px 0 10px 230px;
        }
        button {
            font-family: cursive;
            border-radius: 10px;
            padding: 10px 20px;
            margin: 0 10px;
        }
        #submit:hover{
            background-color: skyblue;
        }
        #cancel:hover {
            background-color: gray;
        }
    </style>
</head>
<body>
<div class="wrapper">
    <div id="header"> 
        <img src="imageslogo.jpeg" alt="Logo" class="logo"> 
    </div>
    <p style="font-family: Arial; font-weight: bold; font-size: 25px; text-align: center;" >Account Registration</p>
    <form>

        <div class="details">
            <label>Enter First Name</label>
            <input type="text" placeholder="First Name" required>
        </div>
        <div class="details">
            <label>Enter Middle Name</label>
            <input type="text" placeholder="Middle Name" required>
        </div>
        <div class="details">
            <label>Enter Last Name</label>
            <input type="text" placeholder="Last Name" required>
        </div>
        <div class="details">
            <label>Suffix</label>
            <select required>
            <option value="">Select Suffix</option>
            <option value="None">None</option>
            <option value="Jr.">Jr.</option>
            <option value="Sr.">Sr.</option>
            <option value="II">II</option>
            <option value="III">III</option>
            <option value="IV">IV</option>
    </select>
        </div>
         <div class="details">
            <label>Enter Birthdate</label>
            <input type="date" required>
        </div>
        <div class="details">
            <label>Email Address</label>
            <input type="email" placeholder="Email" required>
        </div>

        <div class="details">
            <label>Enter Username</label>
            <input type="password" placeholder="Password" required>
        </div>
        <div class="details">
            <label>Enter Password</label>
            <input type="password" placeholder="Password" required>
        </div>
        <div class="details">
            <label>Confirm Password</label>
            <input type="password" placeholder="Confirm Password" required>
        </div>
        <div id="buttonWrapper">
        <button type="submit" id="submit" >Submit</button>
        <button type="reset" id="cancel" >Cancel</button>
    </div>
    </form>
