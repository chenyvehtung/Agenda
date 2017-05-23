## IMPLEMENT CODES for SYSU SS TRNG 2014 - Agenda using Qt

I add a Qt front end to the code just for fun!     
The original terminal based version located in the `backend/` folder.    


```sh
sudo apt install sqlite3
sudo apt install libsqlite3-dev
```  

![](backend/pic/3.png)     

![](backend/pic/4.png)      

![](backend/pic/5.png)


# For Developer

This project is developed using Qt5

```sh
export PATH=/opt/Qt5.7.0/5.7/gcc_64/bin:$PATH
qmake Agenda.pro -r -spec linux-g++
make
```
