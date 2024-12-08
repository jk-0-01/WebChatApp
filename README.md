# WebChatApp
<h1>Steps to run.</h1> 
<p>Clone this repository, create a <a href="https://render.com/">Render</a> account with your Github account and follow the preceeding steps:</p>
<ol>
    <li>Click on "+ New" on the top right.
    <li>Choose "Web Service".
    <li>Choose your cloned repository.
    <li>Press "Connect->".
    <li>Name your web service if desired.
    <li>Look for the "Start Command" section and replace "node index.js" with "npm start".
    <li>Choose your Instance Type.
    <li>Expand the "Advanced" section to make sure auto-deploy is set to "Yes"
    <li>Press "Deploy Service".
    <li>Get your generated URL (the url ends with ".onrender.com")
    <li>Go to the app.js file and edit the first line -> const socket = io('<strong><em>Your generated render URL</em></strong>').
    <li>Back to your render web service, choose "Manual Deploy" on the top right then choose "Deploy latest commit".
    <li>Wait until the logs shows, "Your service is live", before clicking your render URL or pasting it in the browser address bar.
</ol>