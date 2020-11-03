# Emdee five for life  
## HackTheBox Web Challenge  
In this challenge, a webpage is shown to the user and asks him/her to calculate md5 hash of a string. When I calculated it manually, the response was "Too Slow!".  
So I decided to automate it using python.  
The exploit code is available in `exploit.py`.  
The response was this:  
```html
<html>
<head>
<title>emdee five for life</title>
</head>
<body style="background-color:powderblue;">
<h1 align='center'>MD5 encrypt this string</h1><h3 align='center'>w9fiRoY3OtJQbMUVw1zO</h3><p align='center'>HTB{N1c3_ScrIpt1nG_B0i!}</p><center><form action="" method="post">
<input type="text" name="hash" placeholder="MD5" align='center'></input>
</br>
<input type="submit" value="Submit"></input>
</form></center>
</body>
</html>
```  
As you can see, the flag is extracted.  
Enjoy!
