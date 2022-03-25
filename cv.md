## _George Kopylov_
---
### Contacts:
* Location:   _Vitebsk, Belarus_
* Phone: _+375 29 515-55-55_ 
* Email: _kopylov.gv@mail.ru_       
* Github: _[GeorgKop](https://github.com/GeorgKop)_
---
### About me:
_After graduation, I was writing applications in the Visual Basic IDE._  
_Having signed up for the courses, I have a goal to learn new programming language,_  
_to join the community of programmers and achieve new opportunities in programming._ 

---
### Skills:
* _C#_
* _HTML (Basic)_
* _Python (Basic)_
* _JavaScript (Basic)_
* _Git_
___

### Code Example:
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>changing the text size</title> 
    </head>
    <body>
        <dif class="buttons">
            <input type="button" id = "butm"  value="- size">
            <input type="button" id = "butp"  value="+ size">
        </dif>	
        <p id= "text" style= "font-size: 3em">Изменение размера шрифта</p>
    </body>

    <script>
        butm.onclick= function() {chng(-0.5)}
        butp.onclick= function() {chng(0.5)}
        function chng(delt) {
            let CurSize= document.getElementById("text").style.fontSize
            let NewSize = Number(CurSize.slice(0,-2))+delt
            if (NewSize > 0 && NewSize < 10) {
                document.getElementById("text").style.fontSize = NewSize+'em'
            }
        }
    </script>
</html>
~~~
___
### Experience:
_I have ten years of experience writing applications_

---
### Education:  
_Moscow Engineering Physics Institute, Faculty of Cybernetics_

---
### English:
_A2_

---


