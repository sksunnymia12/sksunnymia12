<!doctype html>
<html>
<head>
<style>
#clear{
 width:100px;
}
</style>
</head>
<body>
<div class="formstyle">
<form name="forms">
<input type="text" name="answer"><br></br>
<input type="button" value="1"onclick="forms.answer.value+='1'">
<input type="button" value="2"onclick="forms.answer.value+='2'">
<input type="button" value="3"onclick="forms.answer.value+='3'">
<br></br>
<input type="button" value="4"onclick="forms.answer.value+='4'">
<input type="button" value="5"onclick="forms.answer.value+='5'">
<input type="button" value="6"onclick="forms.answer.value+='6'">
<br></br>
<input type="button" value="7"onclick="forms.answer.value+='7'">
<input type="button" value="8"onclick="forms.answer.value+='8'">
<input type="button" value="9"onclick="forms.answer.value+='9'">
<br></br>
<input type="button" value="+"onclick="forms.answer.value+='+'">
<input type="button" value="-"onclick="forms.answer.value+='-'">
<input type="button" value="*"onclick="forms.answer.value+='*'">
<input type="button" value="="onclick="forms.answer.value = eval(forms.answer.value)">
<br></br>

<input type="button" value="clear all" onclick="forms.answer.value+=''" id="clear">

</body>
</html>
