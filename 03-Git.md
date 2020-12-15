[Home](README.md)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h1>About Git</h1>

<h2>Version Control</h2>
- A Version Control System is a system that allows you to look at several versions of a file and records all of the changes of a version. There are a few different Version Controls
<ol type="1">
    <li>Local Version Control</li>
    - Stores changes to files that are on your hard disk
    <li>Centralized Version Control</li>
    - A single server stores all of the changes and file versions that have taken place. They also track what team members have all done with certain files and helps with making more control with who gets what privileges.
    <li>Distributed Version Control</li>
    - If you don't have internet access you will still be able to work on your code. Once you get internet access again all you have to do is push out those commit changes. Without Distributed Version Control you will lose all of your progress and won't be able to go back if someone messes something up on accident. 
</ol>

<h2>What is Git and what does it do?</h2>
- Git is a DVCS that stores data in a file by using snapshots. Every time you make a change or make a commit it is snapshotted and stored.  
- Git relies mostly on local operations because the most important info is found in local resources. 
- Git will always detect and look for file corruption. And if you have made a change and wish you could go back to your previous commit you are able to.

<h2>How do you clone a Git Repository?</h2>
<ol type="1">
    <li>Go into your Terminal</li>
    <li>Make sure you are on your Desktop by typing "cd" and "cd Desktop"</li>
    <li>Then go to your repository on GitHub and click on the green "Code" button towards the right middle and copy that link</li>
    <li>Go to your Terminal again and type in git clone (the link your copied) and press enter</li>
    <li>To open your file in your Text Editor type in "code ." in your Terminal</li>
    <li>Have fun with coding in your Text Editor!</li>
</ol>
<h3>How do I save the changes I made in my cloned Git Repository?</h3>
<ol type="1">
    <li>Go to your Termninal</li>
    <li>Type "git add ." or "git add (files you have added or made changes to)</li>
    <li>Type "Git commit -m "some message here"</li>
    <li>Type "git push" and that's it. Congrats you have just saved your first change!</li>
</ol>

<h2>Some additional commands</h1>
<table style="width:100%">
<tr>
    <td>Command</td>
    <td>What it does</td>
</tr>
<tr>
    <td>git remote</td>
    <td>shows you the short names, what may show up is "origin"</td>
</tr>
<tr>
    <td>git remote -v</td>
    <td>shows you all of the remote URLs along with their corresponding short names</td>
</tr>






</body>
</html>