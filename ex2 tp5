let nombreSecret = Math.floor(Math.random() * 10) + 1;
let tentative = 0;
let proposition;
do {
    proposition = parseInt(prompt("Devinez un nombre entre 1 et 10 :"));
    tentative++;
    if (proposition < nombreSecret) {
        alert("Plus grand");
    } 
    else if (proposition > nombreSecret) {
        alert("Plus petit");
    } 
    else {
        alert("Bravo ! Vous avez trouvé le nombre.");
    }
} while (proposition !== nombreSecret);
console.log("Score : " + tentative + " tentatives");
