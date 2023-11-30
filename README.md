# Bank-management-
This project simulates Bank server and client communication using socket programming. This project is an attempt to dive deeper into the concepts of socket programming using C.

*NOTE*
This code is not supported by Windows as some of the header files included are not supported.

Incase you have a Windows ,No worries we have a solution for that too:
  Install virtualbox/vmware and set up ubuntu.Youtube link for Installation is as provided:
  https://www.youtube.com/watch?v=Uwr3ALWHsNI 
  then open the terminal and run server :
    for eg. server file name is server.c then
    open the folder where server file is stored 
      =>  type gcc server.c and press enter ,code will compile
      =>  type sudo ./server 80 ,by this the server will connect to port 80
  similarly run client.c 
    for eg. client file is named as client.c then 
      => type gcc client.c press enter ,code will compile 
      => type ./client hostaddress 80
        here if you are running client server on same system enter hostaddr as 127.0.0.1 this is localhost address
        otherwise from the settings of virtual box go to network and select bridged adapter 
        then connect both the server from same wifi or any other common network  and enter the host address of server in place of hostaddress of client

make sure the login_file and remaing files with username as name with atleast one proper entry in all files is maintained in same folder
    
      
  
