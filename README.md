# Race-Day
Codecademy JS Beginner Practice Project
let raceNumber = Math.floor(Math.random()*1000);
console.log(raceNumber);
let earlyRegistry = false;

//console.log(!(earlyRegistry));

let runnersAge = 18;


if (runnersAge >18 && earlyRegistry === true){
  
  raceNumber += 1000;
  
  console.log(`The runner is an "Adult" and their race number is: ${raceNumber}.`);
} 

if (runnersAge>= 18 && earlyRegistry === true) {
  console.log(`Your race will start at: 0930am. Your race number is ${raceNumber}.`);
} else if (runnersAge > 18 && earlyRegistry === false){
  raceNumber < 1000;
  console.log(`As you did not register early, your race time is: 11:00am and your race number is:${raceNumber}`)

} else if (runnersAge < 18) {
  raceNumber < 1000;
  console.log(`Your race will start at: 12:30pm. Your race number is: ${raceNumber}`);
}else {
  console.log(`If you are 18 years old, please go to the registration desk.`)
}

//console.log('The runner is "not an adult". They are ' +runnersAge+ ' years of age.');
/*if (runnersAge >17 || earlyRegistry) {
  console.log(`You\'re race time is: 09:30am. Please note your race number: ${raceNumber}.`)
} else if {
  console.log(`Late adults run at 11am. Your race will begin at 11am prompt. Please note your race number: ${raceNumber}`)
} else (runnersAge < 18) {

console.log(`Your race will begin at 12:30pm, prompt! Please note your race number is: ${raceNumber}`);
}
*/
