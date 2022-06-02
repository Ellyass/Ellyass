<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
.example-radio {
display: block;
position: relative;
padding-left: 35px;
margin-bottom: 15px;
cursor: pointer;
font-size: 18px;
}
.example-radio input {
opacity: 0;
}
.checkmark-radio {
position: absolute;
top: 4;
left: 0;
height: 18px;
width: 18px;
background-color: #bbb;
border-radius: 50%;
}
.example-radio input:checked ~ .checkmark-radio {
background-color: #E7512F;
}
.checkmark-radio:after {
content: "";
position: absolute;
display: none;
}
.example-radio input:checked ~ .checkmark-radio:after {
display: block;
}
.example-radio .checkmark-radio:after {
top: 6px;
left: 6px;
width: 6px;
height: 6px;
border-radius: 50%;
background: white;
}



    </style>
    </head>
<body>
    <h3>Cinsiyet</h3>
<label class="example-radio">
Erkek
<input type="radio" checked="checked" name="radio">
<span class="checkmark-radio"></span>
</label>
<label class="example-radio">
Kadın
<input type="radio" name="radio">
<span class="checkmark-radio"></span>
</label>
</body>
</html>
