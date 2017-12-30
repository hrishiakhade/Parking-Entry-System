# Parking-Entry-System
A QR code based Parking Management System using MySQL

 To Test this app on your Local Machine :
 
 1. Download MySQL Command Line Client
 2. Complete the setup
 3. Create database names 'parking'  
 4. Create table entry with following schema  
 +------------+------------+------+-----+---------+-------+  
| Field      | Type       | Null | Key | Default | Extra |  
+------------+------------+------+-----+---------+-------+  
| Vehicle_No  | char(10)   | NO   | PRI | NULL    |       |  
| Mobile       | bigint(10) | YES  |     | NULL    |       |  
| date_time   | datetime   | YES  |     | NULL    |       |  
+------------+------------+------+-----+---------+-------+  

5. Insert Some entries from command line(if u wish)

  6. Open command prompt
  7. Type 'git clone https://github.com/hrishiakhade/Parking-Entry-System.git'  
   8. cd Parking-Entry-System
   9.   Give path where QR Codes will be saved (in my case following is the path)  
    String defaultpath="C:\\Users\\owner\\Documents\\NetBeansProjects\\Parking Entry System\\qrcode\\" (in Menu.java file )  
    
  10. Give username and password of your database (in my case username and password is 'root')    
 con=DriverManager.getConnection("jdbc:mysql://localhost:3306/parking?autoReconnect=true&useSSL=false","root","root");  
   
 
 
