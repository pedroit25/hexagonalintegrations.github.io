# hexagonalintegrations.github.io
/*
COLORS
body: #f9f9f9
loginbox-border/new-border: #d8dee2
loginbox-background: #fff;
inputs-border: #d1d5da;
submit-background-color: #28a745;
submit-background-image: linear-gradient(-180deg, #34d058 0%, #28a745 90%);
ul-contact: #586069;
ul-contact-default: #0000EE;
background-color: #f9f9f9;
*/

img {
opacity: 0.5;
}

body{
    margin: 0;
    padding: 0;
    background-color: #000000;
    background-image: url("bg image.jpg");
    opacity: 0.6;
    font-family: sans-serif;
}
header img{
    left: 50%;
    transform: translate(-50%);
    top: 25;
    position: absolute;
}
h1{
    text-align: center;
    display: block;
    margin: 4em 0 1em;
    font-weight: 100;
    font-size: 24px;
    color: #FFFFFF
}
#loginbox{
    position: absolute;
    left: 50%;
    transform: translate(-50%);
    width: 300px;
    height: 230px;
    border: 1px solid #d8dee2;
    border-radius: 3%;
    padding: 20px;
    font-size: 15px;
    background-color: #fff;
    font-weight: 600;
}
input[type="text"], input[type="password"]{
    width: 100%;
    height: 34px;
    border-radius: 0.25em;
    border: 1px solid #d1d5da;
}
input[type="text"]:focus{
    box-shadow: 0 0 3pt 2pt #B0E0E6;
    box-shadow: 0 0 0 2pt #B0E0E6;
}
input[type="password"]:focus{
    box-shadow: 0 0 3pt 2pt #B0E0E6;
    box-shadow: 0 0 0 2pt #B0E0E6;
}
label p a{
    float: right;
    font-weight: 200;
    text-decoration: none;
}
#login{
    margin-top: 5px;
    margin-bottom: 15px;
    display: block;
}
#password{
    margin-top: 5px;
    margin-bottom: 15px;
    display: block;  
}
input[type="submit"]{
    width: 100%;
    border: none;
    background-color: 28a745;
    background-image: linear-gradient(-180deg, #34d058 0%, #28a745 90%);;
    color: #fff;
    display: block;
    margin-top: 20px;
    font-size: 14px;
    font-weight: 600;
    height: 34px;
    border-radius: 0.25em;
}
#new{
    width: 308px;
    height: 53px;
    position: absolute;
    border: 1px solid #d8dee2;
    background-color: #FFFFFF;
    left: 50%;
    top: 120%;
    transform: translate(-50%, -50%);
    margin-top: 16px;
    margin-bottom: 10px;
    padding: 5px 20px;
    text-align: center;
    border-radius: 3%;
    font-weight: 100;
    color: #FFFFFF;
}
#new a{
    text-decoration: none;
}
#new a:hover{
    text-decoration: underline;
}
ul li{
    display: inline;
    list-style: none;
}
#list{
    width: 308px;
    height: 53px;
    position: absolute;
    top: 135%;
    width: 100%;
    left: 50%;
    transform: translate(-50%);
    margin-top: 16px;
    margin-bottom: 10px;
    padding: 5px 20px;
    text-align: left;
    color: #FFFFFF;
}
li a{
    text-decoration: none;
}
li a:hover{
    text-decoration: underline;
}
.m3{
    margin-right: 10px;
}
#contact{
    text-decoration: none;
    color: #FFFFFF;;
}
#contact:hover{
    text-decoration: underline;
    color: #0000EE;
}
