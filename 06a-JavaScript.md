[Home](README.md)
<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<h1>JavaScript</h1>
<h2>What is JavaScript?</h2>
- JavaScript allows you to add interactivity to your page. Like opening a little menu asking you to put in a number 1 through 5 or something like that.
- The <p style="color:blueText">document</p>: object represents the whole web page. This is recognized by all web browsers.
- The <p style="color:greenText">write()</p>:  method of the document object allows for new content to be added where the &lt;script&gt; element sits in the html document. 
- The <p style="color:lightPurple">Member Operator</p>: This is used by putting a dot between the object name and the member you to want to have access to.
- The <p style="color:blueText">Parameter</p>: Is whatever is inside the parenthesis which contains the info that is needed in order to work.
<p style="color:blueText">document</p><p style="color:lightPurple">.</p><p style="color:greenText">write&lt;</p><p style="color:blueText">'Good afternoon!'</p><p style="color:greenText">&gt;;</p>
<h2>What is a script?</h2>
- A script is a series of instructions kind of like a script that we would read. The computer reads the code and each and every instruction or command.
<h2>Statements, Curly braces, and which codes should run</h2>
<p style="color:greenText">
    var today = new Date(); <br>
    var hourNow = today.getHours(); <br>
    var greeting; <br>
</p>
<p style="color:blueText">if (hourNow &gt; 18)</p><p style="color:pinkText"> {</p><br>
<p style="color:greenText">greeting = 'Good evening';</p><br>
<p style="color:pinkText">}</p><p style="color:blueText"> else if (hourNow &gt;; 12)</p><p style="color:pinkText"> {</p><br>
<p style="color:greenText">greeting = 'Good afternoon';</p><br>
<p style="color:pinkText">}</p><p style="color:blueText"> else if (hourNow &gt;; 0)</p><p style="color:pinkText"> {</p><br>
<p style="color:greenText">greeting = 'Good morning';</p><br>
<p style="color:pinkText">} </p><p style="blueText"> else</p><p style="pinkText"> {</p><br>
<p style="color:greenText">greeting = 'Welcome';</p><br>
<p style="color:pinkText">} </p><br>
<p style="color:greenText">document.write(greeting);</p><br>

<p style="color:greenText">Statement</p><br>
<p style="color:pinkText">Indicates starts and end of a code block</p><br>
<p style="color:blueText">Indicates which code should run</p>

<h2>Some facts to know about JavaScript</h2>
<ol>
    <li>JavaScript IS case sensitive.</li>
    <li>Statements should start on a new line.</li>
    <li>Statements can be organized into code blocks.</li>
    <li>/* This is for a multi line comment */</li>
    <li>// This is a single line comment</li>
</ol>

JavaScript is so confusing to me. lol
</body>
</html>