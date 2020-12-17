[Home](README.md)
<DOCTYPE html>
<html>
<link rel="stylesheet" href="style.css" />
<title>DISCUSSION.08.md</title>
<body>
    <h1>Operators and Loops</h1>
        <h2>Comparison Operators: Evaluating Conditions</h2>
                You can assess a situation by comparing one value in the script to what you think it might be. The result will be a boolean (true or false).
<table style="width:100%">
    <thead>
        <tr>
            <th align="center">Is equal to</th>
            <th align="center">Is not equal to</th>
            <th align="center">Strict equal to</th>
            <th align="center">Strict not equal to</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">==</td>
            <td align="center">!=</td>
            <td align="center">===</td>
            <td align="center">!==</td>
        </tr>
        <tr>
            <td align="center">This operator compares two values such as numbers, strings or booleans to see if they are the same.</td>
            <td align="center">This operator compares two values such as numbers, strings, or booleans to see if they are not the same.</td>
            <td align="center">This is the prefered operator to use which compares two values to check if both the data type and the value are the same.</td>
            <td align="center">This is the prefered operator to use which compares two values to check if both the data type and the value are not the same.</td>
        </tr>
        <tr>
            <td align="center">'<span class="pinkText">Hello</span>' == '<span class="pinkText">Goodbye</span>'<br /> returns <span class="deepPink">false</span> because they are not the same string.<br />'<span class="pinkText">Hello</span>' === '<span class="pinkText">Hello</span>'<br /> returns <span class="greenText">true</span> because they are the same string</td>
            <td align="center">'<span class="pinkText">Hello</span>' != '<span class="pinkText">Goodbye</span>'<br /> returns <span class="greenText">true</span> because they are not the same string.<br />'<span class="pinkText">Hello</span>' === '<span class="pinkText">Hello</span>'<br /> returns <span class="deepPink">false</span> because they are the same string</td>
            <td align="center">'<span class="pinkText">3</span>' === <span class="pinkText">3</span><br /> returns <span class="deepPink">false</span> because they are not the same data type or value.<br /> '<span class="pinkText">3</span>' === '<span class="pinkText">3</span>'<br /> returns <span class="greenText">true</span> because they are the same data type and value.</td>
            <td align="center">'<span class="pinkText">3</span>' === <span class="pinkText">3</span><br /> returns <span class="greenText">true</span> because they are not the same data type or value.<br /> '<span class="pinkText">3</span>' === '<span class="pinkText">3</span>'<br /> returns <span class="deepPink">false</span> because they are the same data type and value.</td>
        </tr>
    </tbody>
</table>
<table style="width:100%">
    <thead>
        <tr>
            <th align="center">Greater Than</th>
            <th align="center">Less Than</th>
            <th align="center">Greater Than or Equal To</th>
            <th align="center">Less Than or Equal to</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">&gt;</td>
            <td align="center">&lt;</td>
            <td align="center">&gt;=</td>
            <td align="center">&lt;=</td>
        </tr>
        <tr>
            <td align="center">This operator makes sure the number on the left is greater than the number on the right.</td>
            <td align="center">This operator makes sure the number on the right is greater than the number on the left.</td>
            <td align="center">This operator makes sure the number on the left is greater than or equal to the number on the right.</td>
            <td align="center">This operator makes sure the number on the right is greater than or equal to the number on the left.</td>
        </tr>
        <tr>
            <td align="center">
                <span class="pinkText">4</span> &gt; <span class="pinkText">3</span> returns <span class="greenText">true</span><br />
                <span class="pinkText">3</span> &gt; <span class="pinkText">4</span> returns <span class="deepPink">false</span><br />
            </td>
            <td align="center">
                <span class="pinkText">4</span> &lt; <span class="pinkText">3</span> returns <span class="deepPink">false</span><br />
                <span class="pinkText">3</span> &lt; <span class="pinkText">4</span> returns <span class="greenText">true</span><br />
            </td>
            <td align="center">
                <span class="pinkText">4</span> &gt;= <span class="pinkText">3</span> returns <span class="greenText">true</span><br />
                <span class="pinkText">3</span> &gt;= <span class="pinkText">4</span> returns <span class="deepPink">false</span><br />
                <span class="pinkText">3</span> &gt;= <span class="pinkText">3</span> returns <span class="greenText">true</span><br />
            </td>
            <td align="center">
                <span class="pinkText">4</span> &lt;= <span class="pinkText">3</span> returns <span class="deepPink">false</span><br />
                <span class="pinkText">3</span> &lt;= <span class="pinkText">4</span> returns <span class="greenText">true</span><br />
                <span class="pinkText">3</span> &lt;= <span class="pinkText">3</span> returns <span class="greenText">true</span>
            </td>
        </tr>
    </tbody>
</table>
        <h2>Local Operators</h2>
        <p>
            Logical operators are evaluated from left to right. If the first condition has enough information and can determine the answer there no need for the second condition. 
        </p>
            <table style="width:100%">
    <thead>
        <tr>
            <th align="center">Logical And</th>
            <th align="center">Logical Or</th>
            <th align="center">Logical Not</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">This operator tests more than one condition.</td>
            <td align="center">This operator tests at least one condition.</td>
            <td align="center">This operator takes a single boolean value and inverts it.</td>
        </tr>
        <tr>
            <td align="center">((2 &lt; 5) &amp;&amp; (3 &gt;= 2))<br /> returns <span class="greenText">true</span></td>
            <td align="center">((2 &lt; 5) || (2 &lt; 1))<br /> returns <span class="greenText">true</span></td>
            <td align="center">!(2 &lt; 1) returns <span class="greenText">true</span></td>
        </tr>
        <tr>
            <td align="center">
                <span class="greenText">true</span> &amp;&amp; <span class="greenText">true</span> returns <span class="greenText">true</span><br />
                <span class="greenText">true</span> &amp;&amp; <span class="deepPink">false</span> returns <span class="deepPink">false</span><br />
                <span class="deepPink"> false</span> &amp;&amp; <span class="greenText">true</span> returns <span class="deepPink">false</span><br />
                <span class="deepPink"> false</span> &amp;&amp; <span class="deepPink">false</span> returns <span class="deepPink">false</span>
            </td>
            <td align="center">
                <span class="greenText">true</span> || <span class="greenText">true</span> returns <span class="greenText">true</span><br />
                <span class="greenText"> true</span> || <span class="deepPink">false</span> returns <span class="greenText">true</span><br />
                <span class="deepPink">false</span> || <span class="greenText">true</span> returns <span class="greenText">true</span><br />
                <span class="deepPink"> false</span> || <span class="deepPink">false</span> returns <span class="deepPink">false</span>
                </td>
            <td align="center">
                !<span class="greenText">true</span> returns <span class="deepPink">false</span><br />
                !<span class="deepPink">false</span> returns <span class="greenText">true</span>
            </td>
        </tr>
    </tbody>
</table>
            Comparison operators usually give only one of two values which are: <span class="greenText">true</span> or <span class="deepPink">false</span>. Logical operators give you the ability to compare the results of more than one comparison operator.<br />
            <span class="pinkText">(</span><span class="blueText">(5 &lt; 2)</span> <span class="yellowText">&amp;&amp;</span> <span class="lightPurple">(2 &gt;= 3)</span><span class="pinkText">)</span><br />
            There are a total of three expressions which will resolve to either <span class="greenText">true</span> or <span class="deepPink">false</span>. The expressions on the left and the right (expressions 1 and 2) both use comparison operators and both return <span class="deepPink">false</span>. The third expression uses a logical operator. The logical and operator check to see if both expressions on the sides return <span class="greenText">true</span> but in this case they don't so the whole thing evaluates to <span class="deepPink">false</span>.<br />
            <span class="blueText">(5 &lt; 2)</span>: Expression 1: Is five less than two? The result is <span class="deepPink">false</span>.<br />
            <span class="lightPurple">(2 &gt;= 3)</span>: Expression 2: Is two greater than or equal to three? The result is also <span class="deepPink">false</span>.<br />
            <span class="pinkText">()</span>: Everything within these parenthesis are Expression 3<br />
            <span class="yellowText">&amp;&amp;</span>: This is a Logical Operator<br />
        <h2>Loops</h2>    
            Loops check a condition. If it returns true, a code block will run, again and again and repeats until the condition returns false. There are three common types of loops: <br />
            <b>For:</b> This is the most common loop, which has a condition that is usually a counter which is used to tell how times a loop should run.<br />
            <b>While:</b> If you don't know how many times you want the code to run, this will loop as long as the condition is true.<br />
            <b>Do While:</b> This is very similar to the while loop, the difference is it will always run the statements inside the curly braces no matter the condition. It can even evaluate to false.<br />
            <span class="pinkText">for</span> <span class="blueText">(var i = 0; i &lt; 10; i++)</span> <span class="greenText">{<br />document.write(i);<br />}</span><br />
            <span class="pinkText">for</span>: Keyword<br />
            <span class="blueText">(var i = 0; i &lt; 10; i++)</span>: Condition<br />
            <span class="greenText">{ document. write(i); }</span>: Code that will execute during the loop<br />
            As you can see this is a for loop. This condition is a counter that counts to ten. The result would be "0123456789".<br />
        <h2>Example of a while loop</h2>
            <span class="greenText">var i = 1</span>        <span class="grayText">// Set counter to 1</span><br />
            <span class="greenText">var msg = '';</span>        <span class="grayText">// message</span><br />
            <span class="grayText">Store 5 times table in a variable</span><br />
            <span class="greenText">while (i &lt; 10) {</span><br />
            <span class="greenText">msg += i + ' x 5 = ' + (i * 5) + '&lt;br/&gt;';</span><br />
            <span class="greenText">i++;</span><br />
            <span class="greenText">}</span><br />
            <span class="greenText">document.getElementById('answer').innerHTML = msg;</span><br />
        <h3>Result:</h3>
            1 x 5 = 5<br />
            2 x 5 = 10<br />
            3 x 5 = 15<br /> 
            4 x 5 = 20<br />
            5 x 5 = 25<br />
            6 x 5 = 30<br />
            7 x 5 = 35<br />
            8 x 5 = 40<br />
            9 x 5 = 45<br />
</body>
</html>
