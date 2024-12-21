# college-demo
This is my first git repository
<br>
Author- Yash Badola


BASIC CSS COMMAND &
HTML COMMAND

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet"href="style.css">
</head>
<body>
    <h1> hello from yash badola!</h1>
    <P> Yash Badola improve your skill</P>
    <button> click here</button>
<br>
<h2>Flexbox Playground</h2>
    <div id="container">
        <div id="box1">box1</div>
        <div id="box2">box2</div>
        <div id="box3">box3</div>
        <div id="box4">box4</div>
        <div id="box5">box5</div>
    </div>
</body>
</html>

CSS COMMAND

body{
    text-align: center;
}
    h1{
    color: rgb(5, 5, 5);
}
p{
    font-size: larger;
    color:rgb(0, 0, 0);
}
button{
color:darkgoldenrod;
}
body{
    background-color: black;
}
div{
    height: 100px;
    width: 100px;
    color:rgb(247, 171, 9);
    display: inline-block;
    border: 2px solid black;
    position: absolute;
    top:100px;
    left:100px;
    justify-content:center;
    flex-wrap: wrap;
    align-items: center;
    transition-property: all;
    transition-duration: 2s;
    transform: rotate(45deg);
    animation-name:colorAnimate ;
    animation-duration:3s;
    animation-timing-function:ease-in;
    animation-delay:1s;
    animation-iteration-count:5;
}
@keyframes colorAnimate{
    from{background-color:black};
    to{background-color:greenyellow;}

}
div:hover{
    background-color: red;
    color:white;
    font-size: 20px;
    transform: skew(30deg);
}
div:active{
    background-color: pink;
}
@media(width:600px){
div{
    background-color:red;
}
}
@media(min-width:600px){
    div{
        background-color:red;
    }
}
body{
    background-image:url("https://icdn.isrgrajan.com/in/2021/02/kumaoni-culture-kumaoni-people-kumaon-division-kumaon-girls-696x399.jpg");
    background-size: cover;
}
#container{
    width:800px;
    height:200px;
    display: flex;
}
#box1{
color: darkkhaki;
}
#box2{
    color: blueviolet;
}
#box3{
    color: blanchedalmond;
}
#box4{
    color: brown;
}
#box5{
    color: aliceblue;
}
