# mudexin.github.io
<!DOCTYPE HTML>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>confirm</title>
  <script type="text/javascript">
  function rec(){
    var mymessage=confirm("确定登录？")        ;
    if(mymessage==true)
    {
    	document.write("登录成功!");
    }
    else
    {
        document.write("登录失败!");
    }
  }    
  </script>
</head>
<body>
    <input name="button" type="button" onClick="rec()" value="点击，进入登录界面" />
</body>
</html>
