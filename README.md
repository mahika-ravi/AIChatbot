# AIChatbot
Steps to Setup & Deploy
Create an Account on Botpress

Go to Botpress and sign up or log in using GitHub.
Once logged in, create a new bot.
Design Your Bot

Use the Botpress flow editor to add nodes, questions, and conditional logic.
Save your progress regularly.
Configure Webchat Integration

Click on the Webchat option on the left panel.
Scroll down and copy the two script tags:
<script src="https://cdn.botpress.cloud/webchat/v2.2/inject.js"></script>
<script src="https://files.bpcontent.cloud/2025/01/20/12/20250120122152-310RUKNC.js"></script>
Replace the second script’s URL with the one given for your bot if different.
Create the HTML File

Make a file called bot.html and paste the above two scripts inside <body>.
Example structure:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Gatchat Bot</title>
</head>
<body>
    <h1>Welcome to My Gatchat!</h1>
    <script src="https://cdn.botpress.cloud/webchat/v2.2/inject.js"></script>
    <script src="https://files.bpcontent.cloud/2025/01/20/12/20250120122152-310RUKNC.js"></script>
</body>
</html>
Run it using Live Server

Open folder in VS Code, right-click bot.html and select "Open with Live Server".
Or click the "Go Live" button at the bottom of VS Code.
