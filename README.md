<html>
<head>
<title>ehekk</title>

<script type="text/javascript">
flag=1
function f1()
{
    alert("TARA G NA")
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1> TARA VALO? </h1>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgDRHnCKrOFFlC8MH-8mzQDBMAO3xMGERS8w&usqp=CAU" height="200" />
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" YES " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" NO " onMouseOver="f()" />
</div>

</body>
</html>
