# Power Cookie Challenge (picoCTF)

This challenge requires the use of BurpSuite tools. Once we open the website in the browser included with Burp, we go to the proxy tab to see all the requests and responses. We see that there's an option called isAdmin, which is initially set to 0, sending this request to repeater and setting it to 1, we get the flag. 
```
flag=picoCTF{gr4d3_A_c00k13_65fd1e1a}
```
