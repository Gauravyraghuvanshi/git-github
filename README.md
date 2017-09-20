<!DOCTYPE html>
<html>
<head><title>Calculator</title>
<style>
.button {
    background-color: #4CAF50; /* Green */
    border: none;
    color: black;
    padding: 16px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    cursor: pointer;
}

.button1 {
    background-color: #4CAF50; 
    color: aqua; 
    border: 2px solid grey;
}

.button1:hover {
    background-color: #4CAF50;
    color: red;
}

.button2 {
    background-color: white; 
    color: black; 
    border: 2px solid #008CBA;
}

.button2:hover {
    background-color: #008CBA;
    color: white;
}
#rcorners2 {
    border-radius: 25px;
    border: 2px solid #73AD21;
    padding: 20px; 
    width: 350px;
    height: 400px;    
}

</style>
</head>
<body><center>
<div id="rcorners2">
<form>
<input type="textbox" name="text"  style="width:320px; height:100px" ><br/><br/>
<button class="button button5">1</button>
<button class="button button5">2</button>
<button class="button button5">3</button>
<button class="button button1">+</button><br/>
<button class="button button5">4</button>
<button class="button button5">5</button>
<button class="button button5">6</button>
<button class="button button1">-</button><br/>
<button class="button button5">7</button>
<button class="button button5">8</button>
<button class="button button5">9</button>
<button class="button button1">/</button><br/>
<button class="button button5">.</button>
<button class="button button5">0</button>
<button class="button button5">=</button>
<button class="button button1">*</button><br/>


</form>
</div>
</body>
</html>
