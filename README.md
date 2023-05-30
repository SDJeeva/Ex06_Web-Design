# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<title>JavaScript program to display the result of a student</title>
<head>

 <script type="text/javascript">

 function fun()

      { 
         var mark1, mark2, mark3, mark4, mark5, total, percentage;

              mark1 = parseInt(prompt("Enter Subject-1 Marks")); 
              mark2 = parseInt(prompt("Enter Subject 2 Marks")); 
              mark3 = parseInt(prompt("Enter Subject 3 Marks"));
              mark4 = parseInt(prompt("Enter Subject 4 Marks")); 
              mark5 = parseInt(prompt("Enter Subject 5 Marks")); 
              total = mark1 + mark2 + mark3 + mark4 + mark5; 
              percentage = total / 5;

if (percentage >= 91 && percentage <= 100)
{
    alert("O Grade");
}
else if (percentage >= 81 && percentage <= 90)
{
    alert("A+ Grade");
}
else if (percentage >= 71 && percentage <= 80)
{
    alert("A Grade");
}
else if (percentage >= 61 && percentage <= 70)
{
    alert("B+ Grade");
}
else if (percentage >= 51 && percentage <= 60)
{
    alert("B Grade"); 
}
else
{
    alert("RA Grade");
}
}  
</script>
</head>
<body   onload="fun()">


CLICK ME TO FIND THE RESULT

</body>
</html>
```


## OUTPUT\

![Screenshot from 2023-05-30 08-42-24](https://github.com/SDJeeva/Ex06_Web-Design/assets/127816889/1f6b6878-ab14-4317-a181-cb97886937c6)

![Screenshot from 2023-05-30 08-42-21](https://github.com/SDJeeva/Ex06_Web-Design/assets/127816889/84c4b28f-c56c-4c1b-979e-b67fd40bd0b0)

## RESULT
  Student result using JavaScript is created successfully.
