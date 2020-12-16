[Home](README.md)
<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<h1>CSS</h1>
<h2>What is CSS?</h2>
- CSS Stands for Cascading Style Sheets. CSS allows you to put in a background image or color, placement of images, and just the overall design.
<h2>How does CSS work?</h2>
- CSS works by relating rules with HTML elements. The rules tell you how the specified elements will be shown. CSS rules contain 2 parts. 1 which goes on the outsite of the brackets which is called the <p style color="blueText">Selector</p>. And the <p style color="pinkText">Declaration</p>, which is whatever that is inside of the brackets. 
<p style color="blueText">Selector:</p> Tells which element(s) it's going to be applied to.
<p style color="pinkText">Declaration:</p> Tells how the element in the Selector is going to be displayed or styled. 
- Inside of the brackets are 2 parts of each Declaration: the <p style color="lightPurple">Property</p> and <p style color="greenText">Value</p>.
<p style color="lightPurple">Property:</p> Indicates which part you are changing, such as; font, color, width, height etc. 
<p style color="greenText">Value:</p> Indicates how you are going to change the property. For example if your changing the color you are going to put which color you want. 
<h2>Different types of Selectors</h2>
<table style="width:100%">
<tr>
    <td>Selector</td>
    <td>What it does</td>
    <td>Example</td>
</tr>
<tr>
    <td>Universal Selector</td>
    <td>Applies to all elements</td>
    <td>*{}</td>
</tr>
<tr>
    <td>Type Selector</td>
    <td>Matches element names</td>
    <td>h1, h2, h3 {}</td>
</tr>
<tr>
    <td>Class Selector</td>
    <td>Targets any element that is after . In the example it targets any element with attribute of note</td>
    <td>.note{}</td>
</tr>
<tr>
    <td>ID Selector</td>
    <td>Matches an element which ID attribute contains the pound sign or hashtag sign</td>
    <td>#introduction {}</td>
</tr>
<tr>
    <td>Child Selector</td>
    <td>Matches an element that is a child of another</td>
    <td>li&gt;a {}</td>
</tr>
<tr>
    <td>Descendant Selector</td>
    <td>Matches a specified element</td>
    <td>p a {}</td>
</tr>
<tr>
    <td>Adjacent Sibling Selector</td>
    <td>Matches an element that is a sibling of another</td>
    <td>h1+p {}</td>
</tr>
<tr>
    <td>General Sibling Selector</td>
    <td>Matches an element that is a sibling but doesn't have to be the one directly after the element</td>
    <td>hp~p {}</td>
</tr>
<h2>Colors of CSS</h2>
- There are 4 different ways you can get colors; RGB Values, Hex Codes, HSL, and Color Names.
<ol type="1">
    <li>RGB Values</li>: RGB stands for Red Green Blue. The colors are made up of how much red, green or blue are mixed.
    <li>Hex Codes</li>: These are 6 digit codes that are followed by a # and they represent how much red, green, and blue are in a color.
    <li>Color Names</li>: There are 147 predefined color names that are recognized by most browsers. The color names such as red, blue, green, etc.
    <li>HSL</li>: HSL stands for Hue Saturation and Lightness. Hue is expressed as an angle (0 to 360), Saturation and Lightness are both expressed as percentages.
</ol>









</body>
</html>