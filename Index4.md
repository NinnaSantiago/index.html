<html>
<head>
    <title>Exercise6a</title>
	<meta name="student" content="Ninna Alessandra Santiago">
	<meta name="description" content="Table Configurations">
	<meta name="keywords" content="HTML">
    <style>
        .myDiv {
          border: 3px outset rgb(48, 42, 85); 
          text-align: center;
        }
        </style>
</head>
<body>
    <div class="myDiv" style="font-family: 'Courier New'; font-size: 12pt; text-align: center;"><b>
        <p>
            <a href="Index.html" target="_blank">Homepage</a>
        </p>
        <p>
            <a href="Index1.html" target="_blank">Activity 1</a>
            <a href="Index2.html" target="_blank">Activity 2</a>
            <a href="Index3.html" target="_blank">Activity 3</a>
        </p>
        <p>
            Activity 4.1
            <a href="Index5.html" target="_blank">Activity 4.2</a>
        </p>
        <p>
            <a href="Index6.html" target="_blank">Activity 5.1</a>
            <a href="Index7.html" target="_blank">Activity 5.2</a>
            <a href="Index8.html" target="_blank">Activity 5.3</a>
            <a href="Index9.html" target="_blank">Activity 5.4</a>
            <a href="Index10.html" target="_blank">Activity 5.5</a>
            <a href="Index11.html" target="_blank">Activity 5.6</a>
        </p>
        <p>
            <a href="Index12.html" target="_blank">Activity 6</a>
        </p>
        </b>
        </div>
<table id="t01;" style="width:15%">
<style>table, th, td {
        text-align:left; 
        border: 1px solid black;
        border-style: outset;
      }</style>
    <tr>
        <td>A</td>
        <td>B</td>
        <td>C</td>
    </tr>
    <tr>
        <td>D</td>
        <td>E</td>
        <td>F</td>
    </tr>
    <br>
    <caption>Table A</caption>
</table>
<br>
<table id="t02;"style="width:10%">
<style>
}
table, th, td {

        text-align:left; 
        border-spacing: 1px;
        border: 2px solid black;
    }
    #t02 {
    padding:50px
    }</style>
    <tr>
        <td>A</td>
        <td>D</td>
    </tr>
    <tr>
        <td>B</td>
        <td>E</td>
    </tr>
    <tr>
        <td>C</td>
        <td>F</td>
    </tr>
    <caption>Table B</caption>
</table>

<br>
<table id="t03;"style="width:18%">
<style>table, th, td {
    text-align: left;
    border-spacing: 5px;
    border: 1px solid black;
}</style>
    <tr>
        <th colspan="3;" text-align="center;">Title goes here</th>
    </tr>
    <tr>
        <td>A</td>
        <td>C</td>
        <td>E</td>
    </tr>
    <tr>
        <td>B</td>
        <td>D</td>
        <td>f</td>
    </tr>
    <caption>Table C</caption>
    </table>
<br>
<table id="t04;"style="width:25%">
<style>table, th, td {
    text-align: left;
    border-spacing: 5px;
    border: 1px solid black;
}</style>
    <tr>
        <th rowspan="3">Title goes here</th>
    </tr>
    <tr>
        <td>A</td>
        <td>B</td>
        <td>C</td>
    </tr>
    <tr>
        <td>D</td>
        <td>E</td>
        <td>F</td>
    </tr>
    <caption>Table E</caption>
</table>
<br>

<br>
<table id="t05;"style="width:5%">
<style>#t05 {
    padding:50px;
} th, td {
    text-align: center;
    border-spacing: 5px;
    border: 1px solid black;
}</style>
    <tr>
        <th rowspan="3">Title goes here</th>
    </tr>
    <tr>
        <td>A</td>
        <td>B</td>
        <td>C</td>
    </tr>
    <tr>
        <td>D</td>
        <td>E</td>
        <td>F</td>
    </tr>
    <caption>Table F</caption>
</table>
<br>
<table id="t06;"style="width:30%">
    <style>table, th, td {
        text-align: left;
        border-spacing: 5px;
        border: 1px solid black;
    }</style>
    <tr>
        <th rowspan="3">Title goes here</th>
    </tr>
    <tr>
        <td>A</td>
        <td>B</td>
        <td>C</td>
    </tr>
    <tr>
        <td>D</td>
        <td>E</td>
        <td>F</td>
    </tr>
    <caption>Table G</caption>
</table>

<br>
<table id="t07;" style="width:15%">
    <style>table, th, td {
        text-align: left;
        border-spacing: 5px;
        border: 1px solid black;
    }</style>
    <tr>
        <th rowspan="2;"colspan="3">Title goes here</th>
    </tr>
    <tr>
        <td>A</td>
        <td>B</td>
    </tr>
    <tr>
        <td rowspan="3" colspan="1">C</td>
        <td>D</td>
        <td>E</td>
        <td>F</td>
        <td>G</td>
    </tr>
    <tr>
        <td>H</td>
        <td colspan="2">I</td>
        <td rowspan="2">J</td>
    </tr>
    <tr>
        <td>K</td>
        <td>L</td>
        <td>M</td>
    </tr>
    <tr>
        <td>N</td>
        <td colspan="4">O</td>
    </tr>
    <caption>Table H</caption>
</table>
</body>
</html>
