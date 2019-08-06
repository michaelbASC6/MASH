# MASH

let homes = ["Mansion", "Apartment", "Shack", "House"];

let Cars = ["Fisker", "Mustang", "Lamborghini", "BatMobile"]
//Version 2//
function getHome(){
let H = Math.floor(Math.random()*homes.length)
return Homes[H]

}
//Version3//
function GetChildrenCount(){
   let i = Math.floor(Math.random()*100)
    return i
    }
//Version4//
function Mash() {
return "You will live in a " + getHome() + ", and you will have a " + getCar() + " as well as " + GetChildrenCount() + " kids!"
} 

function randomizer(range) {
    return Math.floor(Math.random() * (range + 1));
}

function getHome() {
Homes.push(process.argv[2]);
return Homes[randomizer(Homes.length-1)];

}
function getCar() {
    if(Math.randomizer() >= 0.5)
    return randomizer(100);
    else 
    return process.argv[3];
}

I tried editing the code like this, but it didn't work
