# Terribly-Tiny-Tales

CREATE TABLE  "RESULT"   

   (    "ROLLNO" NUMBER,   
    "NAME" VARCHAR2(40),   
    "RESULT" VARCHAR2(40),   
    "GRADE" VARCHAR2(40),   
     CONSTRAINT "RESULT_PK" PRIMARY KEY ("ROLLNO") ENABLE  
   )  


 
<html>  
<body>  
<form action="servlet/Search">  
Enter your Rollno:<input type="text" name="roll"/><br/>  
  
<input type="submit" value="search"/>  
</form>  
</body>  
</html> 
