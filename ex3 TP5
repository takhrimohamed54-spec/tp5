let QUESTIONS = [
    ["Quelle est la capitale de la France ?", "Paris"],
    ["2 + 2 = ?", "4"],
    ["Couleur du ciel ?", "bleu"],
    ["JavaScript est un langage de ?", "programmation"]
];
function lancerQuiz() {
    let score = 0;
    for (let i = 0; i < QUESTIONS.length; i++) {
        let question = QUESTIONS[i][0];
        let bonneReponse = QUESTIONS[i][1];
        let reponse = prompt(question);
        if (reponse === bonneReponse) {
            alert("Réponse juste");
            score++;
        } else {
            alert("Réponse fausse");
        }
    }
    alert("Vous avez répondu correctement à " + score + " questions sur " + QUESTIONS.length);
}
