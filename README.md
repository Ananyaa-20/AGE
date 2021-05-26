// # AGE
// Enter your age and find how many days , weeks , months you have to turn 90 years.

var age = prompt ("what is your age")
function lifeInYears(age){
   var yearsRemaining = 90 - age;
   var days = yearsRemaining*365;
   var weeks = yearsRemaining*52;
   var months = yearsRemaining*12;
   
   alert("you have" +" "+ days +" "+ "days" +" "+ weeks +" "+"weeks" +" "+ months +" "+"months" + " "+"remaining.");
}
lifeInYears(age);
