+++
title = "Godzill'hack Team"
date = 2024-03-26T14:14:04+01:00
draft = true
+++

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Godzill'hack Team</title>
<style>
html, body {
	overflow: hidden; /* Prevent scrolling */
}

    #GHlogo {
        display: flex; 
        margin: 0 auto; 
        max-width: 500px;
    }
    .social-links {   
        display: flex;  
        justify-content: center;
        margin-top: 20px;
    }
    .social-links a {   
        display: inline-block;
        margin: 0 10px;
        height: 60px;   
        max-width: 60px;
    }


    /* Media queries for responsive design on min 900px screen (desktop) */
    @media only screen and (min-width: 900px) {
        #GHlogo {
            min-width: 1600px;
            max-width: 1600px;
        }
        .social-links a {
            max-width: 60px;
        }
    }

    /* Media queries for responsive design on max 684px (mobile) */
    @media only screen and (max-width: 684px) {
        #GHlogo {
            margin-top: 50px;
            min-width: 950px;
            max-width: 950px;
        }
        .social-links a {
            max-width: 40px;
        }
    }
</style>
</head>
</head>
<body>
    <div class="GHlogo">
    	<img id="GHlogo" src="img/godzillhack-logo.png" alt="Logo Godzillhack" />
    </div>
    <div class="social-links">
        <a href="https://ctftime.org/team/221027" target="_blank"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQld9fEBZRTqk31ER_3JDwttV1g7rVWK2UEjFQIP2arpA&s" alt="CTFTime"></a>
        <a href="https://app.hackthebox.com/public/teams/overview/5452" target="_blank"><img src="https://www.svgrepo.com/show/331423/hack-the-box.svg" alt="HackTheBox"></a>
        <a href="https://github.com/Godzillhack" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub"></a>
        <a href="https://twitter.com/godzillhack" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ce/X_logo_2023.svg/800px-X_logo_2023.svg.png" alt="X"></a>
        <a href="https://bsky.app/profile/godzillhack.bsky.social" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/7/7a/Bluesky_Logo.svg" alt="BlueSky"></a>
    </div>
</body>
</html>
