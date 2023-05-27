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
```<html>
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function student()
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
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
```


## OUTPUT
![webassignment62](https://github.com/Thennunagaraj/Ex06_Web-Design/assets/128386061/e1e77ee3-34db-48f0-9f4b-4deaf7c51096)
![webassignment63](https://github.com/Thennunagaraj/Ex06_Web-Design/assets/128386061/12ccd274-3301-4e74-975a-aecaf3bcd2f7)
![webassignment64](https://github.com/Thennunagaraj/Ex06_Web-Design/assets/128386061/357a6a9b-c5e9-440e-b76f-4c5dc777b6ba)
![webassignment65](https://github.com/Thennunagaraj/Ex06_Web-Design/assets/128386061/f78edc74-7705-456f-909d-6ec2de207f7c)
![webassignment66](https://github.com/Thennunagaraj/Ex06_Web-Design/assets/128386061/0f05e36b-7875-46ca-8eb7-8e8c38fb49af)
![webassignment67](https://github.com/Thennunagaraj/Ex06_Web-Design/assets/128386061/e3db322b-cf03-442b-843b-aa85f2c88917)



## RESULT
  Student result using JavaScript is created successfully.
