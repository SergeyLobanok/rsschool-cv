1. Sergey Lobanok <br>
2. Contacts:
 <li>My number of mobile phone: +375(29)632-34-06</li>
 <li>Email: sergeylobanok93@gmail.com</li>
 <li>Discord: sergeylobanok#4917</li>
 <br>
3. I'm 28 and I've already have experience as sales manager. Curently I'm working as a planning specialitist in analytics department.<br>
4. My knowlages: html, css, scss and js.<br>
5. <pre> let registrationForm = document.getElementById("registration");
let email = document.getElementById("email");
let password = document.getElementById("password");
let confirmPassword = document.getElementById("confirmpassword");
let btn = document.getElementById("btn");
registrationForm.addEventListener("submit", getSubmit);
function getSubmit(e){
    if (email.value === ""){
        alert("Please enter your email");
        e.preventDefault();
        return;
    } 
    if (password.value === ""){
        alert("Please write your password ");
        e.preventDefault();
        return;
    }
    if(password.value.length < "8"){
        alert("Your password very short");
        e.preventDefault();
        return;
    }
    if(confirmPassword.value === ""){
        alert("Please write your confirm password");
        e.preventDefault();
        return;
    }
    if (password.value !== confirmPassword.value){
        alert("Yours password is not correct");
        e.preventDefault();
        return;
    } 
        let userData = {
            "email": email.value,
            "password": password.value
        }
        let usersArr = JSON.parse(localStorage.getItem("userArr") || "[]");
        usersArr.push(userData);
        localStorage.setItem("userArr", JSON.stringify(usersArr));
        window.location.replace("login/index.html");
        e.preventDefault();    
}
6. I attented "Html&CSS" course also I completed base course of JS at IT-SHUTLE school. 
7. I graduated from at the "International University MITSO".
8. I carry on studyng English B1 Level.
