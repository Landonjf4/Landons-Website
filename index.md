<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Center Top Text</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            height: 100vh;
            justify-content: flex-start;
        }
        .top-center-text {
            text-align: center;
            margin-top: 20px; /* Adjusts distance from top */
        }
        .middle-box {
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f0f0f0;
            border-radius: 10px;
            padding: 20px;
            margin-top: 20px;
            width: fit-content;
        }
        .middle-box a {
            display: flex;
            align-items: center;
            margin-top: 10px;
            text-decoration: none;
            color: black;
        }
        .middle-box img {
            width: 30px;
            height: 30px;
            margin-left: 10px;
        }
        .button-container {
            display: flex;
            gap: 10px;
            margin-top: 20px;
        }
        .button {
            background-color: #007bff; /* Blue color */
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #0056b3; /* Darker blue on hover */
        }
        .green-button {
            background-color: #28a745; /* Green color */
        }
        .green-button:hover {
            background-color: #218838; /* Darker green on hover */
        }
        .red-button {
            background-color: #dc3545; /* Red color */
        }
        .red-button:hover {
            background-color: #c82333; /* Darker red on hover */
        }
    </style>
</head>
<body>
    <div class="top-center-text">
        <h1>Landon's Website!</h1>
        <p>This website will show all my work done in Roblox, things like scripts or games will be shown here!</p>
    </div>

    <div class="middle-box">
        <p><b> My profiles! </b></p>

        <a href="https://www.youtube.com/@landonjf4" target="_blank">
            <span>My Github:</span>
            <img src="https://pngimg.com/uploads/github/github_PNG40.png">
        </a>

        <a href="https://www.youtube.com/@landonjf4" target="_blank">
            <span>My Channel:</span>
            <img src="https://static.vecteezy.com/system/resources/previews/023/986/704/original/youtube-logo-youtube-logo-transparent-youtube-icon-transparent-free-free-png.png" alt="YouTube Icon">
        </a>
        
        <a href="https://www.roblox.com/users/93301110/profile" target="_blank">
            <span>Roblox Profile:</span>
            <img src="https://tr.rbxcdn.com/30DAY-Avatar-18C3EAB52B2FA7FD440E7E94F8BA8467-Png/352/352/Avatar/Webp/noFilter" alt="Roblox Profile">
        </a>
    </div>

    <div class="top-center-text">
        <h1>Games I have worked on!</h1>
    </div>
    
    <div class="top-center-text"> 
        <h2>Landon's Pizzeria</h2>
        <p>Landon's Pizzeria is a myth hunting game where people can view myth games and what the myth is about!</p>
    </div>

    <div class="button-container">
        <a href="https://www.roblox.com/games/108197971724960/Landons-Pizzeria" target="_blank" class="button red-button">Landon's Pizzeria</a> 
        <a href="https://www.roblox.com/groups/34864519/Landons-Pizzeria" target="_blank" class="button green-button">Landon's Pizzeria Group</a> 
        <a href="https://discord.gg/mGJ24H8gz9" target="_blank" class="button">Discord Server</a>
    </div>
    
<h5> Website Version: 0.0.1 </h5>
</body>
</html>