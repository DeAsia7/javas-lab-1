// learning how to simplify a song using javascript functions. 
// using \n to break the lines 
// finding a way to write repetitve lines without typing them out over and over 


function printedSong(){

console.log("i need to know, i need to know, which way to go \n");

console.log("i need to know, i need to know, which way to go \n");

console.log("oh how i miss you, i miss you in my arms. \n");

console.log("i stare at the pictures i keep in my car, \n");

console.log("i'll sit on this empty bench \n");

console.log("and wait till we meet again. \n");

}

function refrain(){

console.log("i need to know, i need to know, which way to go \n");

console.log("i need to know, i need to know, which way to go \n");
}

function song(){

refrain();

console.log("oh how i miss you, i miss you in my arms. \n");

console.log("i stare at the pictures i keep in my car, \n");

console.log("i'll sit on this empty bench \n");

console.log("and wait till we meet again. \n");

refrain();

}

song();

function refactoredRefrain(){

return "i need to know, i need to know, which way to go \n";

}

function refactoredSong(){

console.log("oh how i miss you, i miss you in my arms. \n");

console.log("i stare at the pictures i keep in my car, \n");

console.log("i'll sit on this empty bench \n");

console.log("and wait till we meet again. \n");

}

refactoredSong(); 
