# change the default interpreter 
in the terminal window type `where python`

![](./images/aa.png)

should look like this 

![](./images/aaa.png)

copy the one that has `Programs\Python\Python*\python.exe`  in it, then open vs code settings and past this in the search `@ext:ms-python.python python.defaultInterpreterPath`

![](./images/aaaa.png)

then past the path you copied in the text box 

![](./images/aaaaa.png)

restart vs-code

# install pip
in the terminal type `curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`

![](./images/p.png)

should look like this

![](./images/pp.png)

then type `python get-pip.py`

![](./images/ppp.png)

# install mysql connector

in the terminal type `pip install mysql-connector-python`

![](./images/pppp.png)

everything should work now : )

