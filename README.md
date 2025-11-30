<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz Interactif : Principes Stratigraphiques</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; }
        .question { margin-bottom: 20px; }
        .options { margin-left: 20px; }
        button { padding: 10px 20px; background-color: #4CAF50; color: white; border: none; cursor: pointer; }
        button:hover { background-color: #45a049; }
        #results { margin-top: 20px; font-weight: bold; }
    </style>
</head>
<body>
    <h1>Quiz Interactif : Principes Stratigraphiques</h1>
    <p>Ce quiz contient 15 questions à choix multiples (QCM), chacune avec 5 propositions. Une seule réponse est correcte par question. Répondez à toutes les questions, puis cliquez sur "Soumettre" pour voir votre score.</p>

    <form id="quizForm">
        <div class="question">
            <p>1. Quel principe stipule que dans une séquence sédimentaire non perturbée, les couches les plus anciennes sont situées en bas et les plus récentes en haut ?</p>
            <div class="options">
                <input type="radio" name="q1" value="A"> A) Principe de continuité latérale<br>
                <input type="radio" name="q1" value="B"> B) Principe de superposition<br>
                <input type="radio" name="q1" value="C"> C) Loi de Walther<br>
                <input type="radio" name="q1" value="D"> D) Principe de failles<br>
                <input type="radio" name="q1" value="E"> E) Principe de corrélation<br>
            </div>
        </div>

        <div class="question">
            <p>2. Le principe de continuité latérale affirme que :</p>
            <div class="options">
                <input type="radio" name="q2" value="A"> A) Les couches sédimentaires sont horizontales à l'origine.<br>
                <input type="radio" name="q2" value="B"> B) Les couches peuvent être interrompues par des failles.<br>
                <input type="radio" name="q2" value="C"> C) Une couche sédimentaire s'étend latéralement jusqu'à ce qu'elle s'amincisse ou rencontre un obstacle.<br>
                <input type="radio" name="q2" value="D"> D) Les intrusions magmatiques sont plus jeunes que les roches encaissantes.<br>
                <input type="radio" name="q2" value="E"> E) Les fossiles permettent de dater les couches.<br>
            </div>
        </div>

        <div class="question">
            <p>3. Selon la loi de Walther, les faciès sédimentaires :</p>
            <div class="options">
                <input type="radio" name="q3" value="A"> A) Sont toujours superposés dans le même ordre.<br>
                <input type="radio" name="q3" value="B"> B) Changent latéralement en fonction de l'environnement de dépôt.<br>
                <input type="radio" name="q3" value="C"> C) Sont perturbés par les intrusions.<br>
                <input type="radio" name="q3" value="D"> D) Sont datés uniquement par les fossiles.<br>
                <input type="radio" name="q3" value="E"> E) Sont horizontaux à l'origine.<br>
            </div>
        </div>

        <div class="question">
            <p>4. Le principe des failles et des intrusions indique que :</p>
            <div class="options">
                <input type="radio" name="q4" value="A"> A) Les couches sédimentaires sont continues.<br>
                <input type="radio" name="q4" value="B"> B) Les failles et les intrusions sont plus anciennes que les roches qu'elles traversent.<br>
                <input type="radio" name="q4" value="C"> C) Les failles et les intrusions sont plus jeunes que les roches qu'elles traversent.<br>
                <input type="radio" name="q4" value="D"> D) Les faciès changent verticalement.<br>
                <input type="radio" name="q4" value="E"> E) Les fossiles sont identiques dans toutes les couches.<br>
            </div>
        </div>

        <div class="question">
            <p>5. Quel principe permet de corréler des couches sédimentaires entre différentes régions ?</p>
            <div class="options">
                <input type="radio" name="q5" value="A"> A) Principe de superposition<br>
                <input type="radio" name="q5" value="B"> B) Principe de continuité latérale<br>
                <input type="radio" name="q5" value="C"> C) Principe de corrélation<br>
                <input type="radio" name="q5" value="D"> D) Loi de Walther<br>
                <input type="radio" name="q5" value="E"> E) Principe de failles<br>
            </div>
        </div>

        <div class="question">
            <p>6. Dans une séquence stratigraphique, si une couche A est coupée par une faille et recouverte par une couche B, alors :</p>
            <div class="options">
                <input type="radio" name="q6" value="A"> A) A est plus ancienne que B.<br>
                <input type="radio" name="q6" value="B"> B) B est plus ancienne que A.<br>
                <input type="radio" name="q6" value="C"> C) La faille est plus ancienne que A et B.<br>
                <input type="radio" name="q6" value="D"> D) La faille est plus jeune que A et B.<br>
                <input type="radio" name="q6" value="E"> E) A et B sont contemporaines.<br>
            </div>
        </div>

        <div class="question">
            <p>7. Le principe d'horizontalité originale stipule que :</p>
            <div class="options">
                <input type="radio" name="q7" value="A"> A) Les couches sédimentaires sont déposées horizontalement.<br>
                <input type="radio" name="q7" value="B"> B) Les couches peuvent être pliées après dépôt.<br>
                <input type="radio" name="q7" value="C"> C) Les intrusions sont verticales.<br>
                <input type="radio" name="q7" value="D"> D) Les fossiles indiquent l'âge relatif.<br>
                <input type="radio" name="q7" value="E"> E) Les faciès sont latéraux.<br>
            </div>
        </div>

        <div class="question">
            <p>8. Quel principe est illustré par l'exemple où des couches marines passent latéralement à des couches continentales ?</p>
            <div class="options">
                <input type="radio" name="q8" value="A"> A) Principe de superposition<br>
                <input type="radio" name="q8" value="B"> B) Loi de Walther<br>
                <input type="radio" name="q8" value="C"> C) Principe de continuité latérale<br>
                <input type="radio" name="q8" value="D"> D) Principe de failles<br>
                <input type="radio" name="q8" value="E"> E) Principe de corrélation<br>
            </div>
        </div>

        <div class="question">
            <p>9. Les principes stratigraphiques sont principalement utilisés pour :</p>
            <div class="options">
                <input type="radio" name="q9" value="A"> A) Étudier les tremblements de terre.<br>
                <input type="radio" name="q9" value="B"> B) Déterminer l'âge relatif des roches sédimentaires.<br>
                <input type="radio" name="q9" value="C"> C) Analyser la composition chimique des minéraux.<br>
                <input type="radio" name="q9" value="D"> D) Prévoir les éruptions volcaniques.<br>
                <input type="radio" name="q9" value="E"> E) Mesurer la vitesse des courants océaniques.<br>
            </div>
        </div>

        <div class="question">
            <p>10. Si une intrusion magmatique traverse des couches sédimentaires, elle est :</p>
            <div class="options">
                <input type="radio" name="q10" value="A"> A) Plus ancienne que les couches.<br>
                <input type="radio" name="q10" value="B"> B) Contemporaine des couches.<br>
                <input type="radio" name="q10" value="C"> C) Plus jeune que les couches.<br>
                <input type="radio" name="q10" value="D"> D) Identique en âge aux couches.<br>
                <input type="radio" name="q10" value="E"> E) Datée par les fossiles des couches.<br>
            </div>
        </div>

        <div class="question">
            <p>11. Le principe de superposition s'applique uniquement aux :</p>
            <div class="options">
                <input type="radio" name="q11" value="A"> A) Roches ignées.<br>
                <input type="radio" name="q11" value="B"> B) Roches métamorphiques.<br>
                <input type="radio" name="q11" value="C"> C) Roches sédimentaires non perturbées.<br>
                <input type="radio" name="q11" value="D"> D) Roches volcaniques.<br>
                <input type="radio" name="q11" value="E"> E) Roches plutoniques.<br>
            </div>
        </div>

        <div class="question">
            <p>12. Dans la loi de Walther, la succession verticale des faciès correspond à :</p>
            <div class="options">
                <input type="radio" name="q12" value="A"> A) Une succession latérale dans l'espace.<br>
                <input type="radio" name="q12" value="B"> B) Une succession temporelle inversée.<br>
                <input type="radio" name="q12" value="C"> C) Une perturbation tectonique.<br>
                <input type="radio" name="q12" value="D"> D) Une intrusion magmatique.<br>
                <input type="radio" name="q12" value="E"> E) Une faille normale.<br>
            </div>
        </div>

        <div class="question">
            <p>13. Quel principe permet d'affirmer qu'une couche fossile trouvée dans deux régions différentes a le même âge ?</p>
            <div class="options">
                <input type="radio" name="q13" value="A"> A) Principe de superposition<br>
                <input type="radio" name="q13" value="B"> B) Principe de continuité latérale<br>
                <input type="radio" name="q13" value="C"> C) Principe de corrélation<br>
                <input type="radio" name="q13" value="D"> D) Loi de Walther<br>
                <input type="radio" name="q13" value="E"> E) Principe de failles<br>
            </div>
        </div>

        <div class="question">
            <p>14. Les principes stratigraphiques ont été formulés principalement par :</p>
            <div class="options">
                <input type="radio" name="q14" value="A"> A) Charles Darwin.<br>
                <input type="radio" name="q14" value="B"> B) Nicolas Steno.<br>
                <input type="radio" name="q14" value="C"> C) Alfred Wegener.<br>
                <input type="radio" name="q14" value="D"> D) James Hutton.<br>
                <input type="radio" name="q14" value="E"> E) Charles Lyell.<br>
            </div>
        </div>

        <div class="question">
            <p>15. Si une couche est pliée, le principe d'horizontalité originale indique qu'elle était :</p>
            <div class="options">
                <input type="radio" name="q15" value="A"> A) Déposée verticalement.<br>
                <input type="radio" name="q15" value="B"> B) Déposée horizontalement à l'origine.<br>
                <input type="radio" name="q15" value="C"> C) Toujours pliée.<br>
                <input type="radio" name="q15" value="D"> D) Intrudée par du magma.<br>
                <input type="radio" name="q15" value="E"> E) Corrompue par des fossiles.<br>
            </div>
        </div>

        <button type="button" onclick="checkAnswers()">Soumettre</button>
    </form>

    <div id="results"></div>

    <script>
        function checkAnswers() {
            const answers = {
                q1: 'B', q2: 'C', q3: 'B', q4: 'C', q5: 'C',
                q6: 'D', q7: 'A', q8: 'B', q9: 'B', q10: 'C',
                q11: 'C', q12: 'A', q13: 'C', q14: 'B', q15: 'B'
            };

            let score = 0;
            const form = document.getElementById('quizForm');
            const formData = new FormData(form);

            for (let i = 1; i <= 15; i++) {
                const selected = formData.get('q' + i);
                if (selected === answers['q' + i]) {
                    score++;
                }
            }

            const resultsDiv = document.getElementById('results');
            resultsDiv.innerHTML = `Votre score : ${score}/15. ${score >= 12 ? 'Excellent !' : score >= 8 ? 'Bien joué !' : 'Réessayez pour améliorer.'}`;
        }
    </script>
</body>
</html>
