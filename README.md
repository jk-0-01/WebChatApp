# WebChatApp <i>following Dave Gray's "<a href="https://youtube.com/playlist?list=PL0Zuz27SZ-6NOkbTDxKi7grs_oxJhLu07&si=YFXS_U45KZEBcAfx" target="_blank">Building a Chat App</a>" playlist</i>
<h2>Steps to run:</h2> 
<h3>As a web service</h3>
<p>Clone this repository, create a <a href="https://render.com/" target="_blank">Render</a> account with your Github account and follow the preceeding steps:</p>
<ol>
    <li>Click on "+ New" on the top right.
    <li>Choose "Web Service".
    <li>Choose your cloned repository.
    <li>Press "Connect->".
    <li>Give your web service a different name if wanted.
    <li>Look for the "Start Command" section and replace "node index.js" with "npm start".
    <li>Choose your Instance Type.
    <li>Expand the "Advanced" section to make sure auto-deploy is set to "Yes"
    <li>Press "Deploy Service".
    <li>Get your generated URL (the url ends with ".onrender.com")
    <li>Go to the app.js file and edit the first line -> const socket = io('<strong><em>Your generated render URL</em></strong>').
    <li>Back to your render web service, choose "Manual Deploy" on the top right then choose "Deploy latest commit".
    <li>Wait until the logs shows, "Your service is live", before clicking your render URL or pasting it in the browser address bar.
</ol>

<h3>Locally</h3>
<ol>
    <li>Download all files and place them in a dedicated folder.
    <li>Install VSCode if not yet installed.
    <li>Install the Live Server extension by Ritwick Dey.
    <li>Open the folder with the downloaded files in VSCode or with VSCode.
    <li>Open the terminal and type the following: <strong>npm i -D nodemon</strong>, <strong>npm i socket.io</strong>, and <strong>npm i express</strong> to add the required dependencies.
    <li>Open your <strong>index.html</strong> and change the first line -> const socket = io(<strong>'ws://localhost:3500'</strong>).
    <li>Type <strong>npm run dev</strong> in the terminal to start the web app.
    <li>Right click in your <strong>index.html</strong> and choose, "Open with Live Server".
</ol>
