<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Mots Croisés - Ennemis de Batman</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      padding: 20px;
      background-color: #1a1a1a;
      color: #f5f5f5;
    }
    h2 {
      color: #fdd835;
    }
    table {
      border-collapse: collapse;
      margin-top: 20px;
    }
    th {
      width: 30px; height: 30px; text-align: center;
      color: white; font-weight: bold;
      background-color: #1a1a1a;
      border: 1px solid #444;
    }
    td {
      width: 30px; height: 30px; text-align: center;
      border: 1px solid #444;
      background-color: #222;
      position: relative;
    }
    input {
      width: 28px; height: 28px; border: none;
      background-color: #222; color: #eee; text-align: center;
      text-transform: uppercase; font-size: 16px;
    }
    input:focus {
      outline: 2px solid #fdd835;
    }
    .black {
      background-color: #000;
      border: none;
    }
    .number {
      position: absolute;
      top: 0;
      left: 2px;
      font-size: 10px;
      color: #fdd835;
    }
    .clues {
      margin-top: 30px;
    }
    button {
      margin-top: 20px;
      padding: 10px 15px;
      background-color: #fdd835;
      border: none;
      color: #000;
      font-weight: bold;
      cursor: pointer;
    }
    .correct { background-color: #2e7d32 !important; }
    .incorrect { background-color: #c62828 !important; }
  </style>
</head>
<body>
  <h2>Mots Croisés : Ennemis emblématiques de Batman</h2>
  <p>Remplis les cases puis clique sur "Vérifier" pour voir si tes réponses sont correctes.</p>
  <table id="grid">
    <thead>
      <tr>
        <th></th>
        <!-- A à O -->
        <th>A</th><th>B</th><th>C</th><th>D</th><th>E</th><th>F</th><th>G</th><th>H</th><th>I</th><th>J</th><th>K</th><th>L</th><th>M</th><th>N</th><th>O</th>
      </tr>
    </thead>
    <tbody>
      <!-- Génération manuelle simplifiée pour 15x15 avec les mots clés -->
      <!-- Ligne 1 -->
      <tr><th>1</th><td class="black"></td><td><div class="number">1</div><input maxlength="1" data-answer="J"></td><td><input maxlength="1" data-answer="O"></td><td><input maxlength="1" data-answer="K"></td><td><input maxlength="1" data-answer="E"></td><td><input maxlength="1" data-answer="R"></td><td class="black"></td><td class="black"></td><td class="black"></td><td><input maxlength="1" data-answer="R"></td><td><input maxlength="1" data-answer="I"></td><td><input maxlength="1" data-answer="D"></td><td><input maxlength="1" data-answer="D"></td><td><input maxlength="1" data-answer="L"></td><td><input maxlength="1" data-answer="E"></td></tr>

      <!-- Ligne 3 (PENGUIN) -->
      <tr><th>3</th>
        <td><div class="number">2</div><input maxlength="1" data-answer="P"></td>
        <td><input maxlength="1" data-answer="E"></td>
        <td><input maxlength="1" data-answer="N"></td>
        <td><input maxlength="1" data-answer="G"></td>
        <td><input maxlength="1" data-answer="U"></td>
        <td><input maxlength="1" data-answer="I"></td>
        <td><input maxlength="1" data-answer="N"></td>
        <td class="black"></td><td class="black"></td>
        <td><input maxlength="1" data-answer="A"></td>
        <td><input maxlength="1" data-answer="N"></td>
        <td><input maxlength="1" data-answer="E"></td>
        <td class="black"></td><td class="black"></td><td class="black"></td>
      </tr>

      <!-- Ligne 5 (CATWOMAN) -->
      <tr><th>5</th>
        <td class="black"></td><td><div class="number">3</div><input maxlength="1" data-answer="C"></td>
        <td><input maxlength="1" data-answer="A"></td><td><input maxlength="1" data-answer="T"></td>
        <td><input maxlength="1" data-answer="W"></td><td><input maxlength="1" data-answer="O"></td>
        <td><input maxlength="1" data-answer="M"></td><td><input maxlength="1" data-answer="A"></td>
        <td><input maxlength="1" data-answer="N"></td><td class="black"></td>
        <td class="black"></td><td class="black"></td><td><input maxlength="1" data-answer="H"></td>
        <td><input maxlength="1" data-answer="A"></td><td><input maxlength="1" data-answer="R"></td>
      </tr>

      <!-- Tu peux ajouter ici d'autres lignes similaires pour POISONIVY, CLAYFACE, SCARECROW, TWOFACE, etc. -->

    </tbody>
  </table>

  <button onclick="checkAnswers()">Vérifier</button>

  <div class="clues">
    <h3>Indices horizontaux :</h3>
    <ul>
      <li>1. Clown prince du crime</li>
      <li>2. Mafieux au parapluie</li>
      <li>3. Cambrioleuse féline</li>
      <!-- etc. -->
    </ul>
    <h3>Indices verticaux :</h3>
    <ul>
      <li>6. Obsédé par les énigmes</li>
      <li>7. Briseur de dos</li>
      <li>8. Ancienne psychiatre devenue folle</li>
      <li>9. Maître de la peur</li>
    </ul>
  </div>

  <script>
    function checkAnswers() {
      const inputs = document.querySelectorAll('input[data-answer]');
      inputs.forEach(input => {
        const expected = input.getAttribute('data-answer').toUpperCase();
        const value = input.value.toUpperCase();
        if (value === expected) {
          input.classList.remove("incorrect");
          input.classList.add("correct");
        } else {
          input.classList.remove("correct");
          input.classList.add("incorrect");
        }
      });
    }
  </script>
</body>
</html>
