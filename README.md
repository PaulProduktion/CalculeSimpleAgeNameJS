# CalculeSimpleAgeNameJS

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
