# JavaScript
Hello word, promt add or minus, swap, math.sqr ect...

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>


<script>
    
    console.log('Hello, World!');

    alert('Welcome to JavaScript')

    document.write('My Name is Faizan Khan')

</script>


    <script type="text/javascript">

    var base = prompt('please enter the base value')
    var height = prompt('please enter the height value')
    var area = (base * height)/2;
    console.log('base: '+ base + 'height: '+ height + ' area: '+area);
    
</script>





    <script type="text/javascript">

        var a = 10;
        var b = 10;
        var c = 10;
        var s = (a+b+c)/2;
        var temp = s*(s-a)*(s-b)*(s-c);
        var area = Math.sqrt(temp)
        console.log(s)

</script>

    
    <script type="text/javascript">
    
var a = prompt('please enter the a value');
var b = prompt('please enter the b value');
console.log('The value of a is: ${a}, The value of b is: ${b}');

</script>




    <script src=" script.js">


    </script>



</body>

</html>
