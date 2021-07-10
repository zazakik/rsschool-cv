# Zaza Kiknadze

## Contact Info

* __Email:__ zazakiknadze96@gmail.com
* __Phone:__ +995598337950

## Summary

###### My goal is to become a successful Web Developer.

## Skills

```
HTML5
CSS3
JavaScript
```

## Code examples

```
let number = Math.trunc(Math.random() * 20 + 1);


document.querySelector(".btn_check").addEventListener("click", function () {
    const guess = Number(document.querySelector(".guess").value);

    if (guess > 20 || guess < 1) {
        alert("Enter number between 1 and 20");
        document.querySelector(".guess").value = null;
    } else {
        if (number === guess) {
            document.querySelector(".number").textContent = guess;
            document.querySelector(".message").textContent = "Correct Number!";
            document.querySelector(".highscore").textContent = document.querySelector(".score").textContent;
        }
        else {
            document.querySelector(".score").textContent = Number(document.querySelector(".score").textContent) - 1;
            if (number > guess) {
                document.querySelector(".message").textContent = "Too low...";
            } else {
                document.querySelector(".message").textContent = "Too high...";
            }
            if (Number(document.querySelector(".score").textContent) === 0) {
                document.querySelector(".main_text").textContent = "Game Over";
                document.querySelector(".guess").value = null;
                alert("Click Again button!");
            }
        }
    }
})
```

## Experience

###### Unfortunately I have no experience

## Education

* Tbilisi State University - ___Bachelor degree___ (Computer Science)
* Tbilisi State University - ___Master degree___ (Information Technologies)

## English

* __B2__