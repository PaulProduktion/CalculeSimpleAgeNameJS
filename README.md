# Conditions

const userName = prompt("quelle st ton nim")

if (userName === "Bob") {
  const Age = prompt("quelle ? ")
  if (parseInt(Age) === 30) {
    console.log("welcomme")
  }
 else{
  console.log("go away ")
 }
}
else{
  console.log("go away ")
}


/// Name et passwoard 

const userName = "Paul";
const userPassword = "secret";

if(userName === "Bob" || userName === "Paul") {
  console.log("welcome")
}
if(userName === "Paul" && userPassword === "secret") {
  console.log("welcome too")
}

// siwth jour de la semaine 

const today = new Date().getDay();

switch(today){
  case 0:
    console.log("it's sunday");
    break;
  case 1:
    console.log("it's Monday");
    break;
  case 2:
    console.log("it's tusday");
    break;
  case 3:
    console.log("it's wensday");
    break;
  case 4:
    console.log("it's thiday");
    break;
  case 5:
    console.log("it's fryday");
    break;
  case 6:
    console.log("it's Saturday");
    break;
  default:
    console.log("pas un jour comme les autres");
    break;
}

/// coonditiond ternaires plus simpel

const name = "Paul"
const Age = 30

name === "Paul" && Age === 30 ? console.log("bienvenue") : console.log("go away ");

const animal = {
  name: "Lucky", 
  species: "Cat", 
  age: "3",
}

animal.name === "Lucky" ? console.log("bienvenue ") : console.log("go away ")
