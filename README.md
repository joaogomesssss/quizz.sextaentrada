# quizz.sextaentrada
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz: Processos de Influência</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .question {
            margin-bottom: 20px;
        }
        .choices button {
            display: block;
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            font-size: 16px;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .choices button:hover {
            background-color: #0056b3;
        }
        .result {
            display: none;
            padding: 15px;
            border-radius: 5px;
            margin-top: 20px;
        }
        .correct {
            background-color: #d4edda;
            color: #155724;
        }
        .incorrect {
            background-color: #f8d7da;
            color: #721c24;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Quiz: Processos de Influência</h1>

        <!-- Pergunta 1 -->
        <div class="question">
            <h2>Pergunta 1: O que é influência social normativa?</h2>
            <div class="choices">
                <button onclick="showResult('correct1')">A) Ajustar o comportamento para ser aceito pelo grupo.</button>
                <button onclick="showResult('incorrect1')">B) Procurar informações de outros para decidir.</button>
            </div>
            <div id="correct1" class="result correct">Resposta correta!</div>
            <div id="incorrect1" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 2 -->
        <div class="question">
            <h2>Pergunta 2: Quem conduziu o famoso estudo sobre obediência?</h2>
            <div class="choices">
                <button onclick="showResult('correct2')">A) Stanley Milgram.</button>
                <button onclick="showResult('incorrect2')">B) Solomon Asch.</button>
            </div>
            <div id="correct2" class="result correct">Resposta correta!</div>
            <div id="incorrect2" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 3 -->
        <div class="question">
            <h2>Pergunta 3: O que é conformidade?</h2>
            <div class="choices">
                <button onclick="showResult('correct3')">A) Ajustar o comportamento para se alinhar ao grupo.</button>
                <button onclick="showResult('incorrect3')">B) Questionar o comportamento do grupo.</button>
            </div>
            <div id="correct3" class="result correct">Resposta correta!</div>
            <div id="incorrect3" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 4 -->
        <div class="question">
            <h2>Pergunta 4: Qual experimento demonstrou o poder da conformidade?</h2>
            <div class="choices">
                <button onclick="showResult('correct4')">A) Experiência das linhas de Asch.</button>
                <button onclick="showResult('incorrect4')">B) Experimento do boneco Bobo.</button>
            </div>
            <div id="correct4" class="result correct">Resposta correta!</div>
            <div id="incorrect4" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 5 -->
        <div class="question">
            <h2>Pergunta 5: Qual é um dos princípios da teoria do impacto social?</h2>
            <div class="choices">
                <button onclick="showResult('correct5')">A) O impacto aumenta com a proximidade.</button>
                <button onclick="showResult('incorrect5')">B) O impacto diminui com a autoridade.</button>
            </div>
            <div id="correct5" class="result correct">Resposta correta!</div>
            <div id="incorrect5" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 6 -->
        <div class="question">
            <h2>Pergunta 6: Qual dos seguintes é um exemplo de conformidade?</h2>
            <div class="choices">
                <button onclick="showResult('correct6')">A) Alterar sua opinião para alinhar-se com o grupo, mesmo achando que eles estão errados.</button>
                <button onclick="showResult('incorrect6')">B) Seguir instruções de uma figura de autoridade.</button>
            </div>
            <div id="correct6" class="result correct">Resposta correta!</div>
            <div id="incorrect6" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 7 -->
        <div class="question">
            <h2>Pergunta 7: No estudo de Bandura, qual foi o nome do famoso experimento?</h2>
            <div class="choices">
                <button onclick="showResult('correct7')">A) Experimento do boneco Bobo.</button>
                <button onclick="showResult('incorrect7')">B) Experimento da linha de conformidade.</button>
            </div>
            <div id="correct7" class="result correct">Resposta correta!</div>
            <div id="incorrect7" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 8 -->
        <div class="question">
            <h2>Pergunta 8: Qual é um dos fatores que aumentam a conformidade em um grupo?</h2>
            <div class="choices">
                <button onclick="showResult('correct8')">A) Tamanho maior do grupo.</button>
                <button onclick="showResult('incorrect8')">B) Maior anonimato dentro do grupo.</button>
            </div>
            <div id="correct8" class="result correct">Resposta correta!</div>
            <div id="incorrect8" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 9 -->
        <div class="question">
            <h2>Pergunta 9: O que a influência social informacional envolve?</h2>
            <div class="choices">
                <button onclick="showResult('correct9')">A) Buscar informações de outras pessoas para decidir o que fazer.</button>
                <button onclick="showResult('incorrect9')">B) Ajustar seu comportamento para ser aceito socialmente.</button>
            </div>
            <div id="correct9" class="result correct">Resposta correta!</div>
            <div id="incorrect9" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>

        <!-- Pergunta 10 -->
        <div class="question">
            <h2>Pergunta 10: Qual era o objetivo principal do estudo de Solomon Asch?</h2>
            <div class="choices">
                <button onclick="showResult('correct10')">A) Entender como as pessoas se conformam à opinião do grupo.</button>
                <button onclick="showResult('incorrect10')">B) Analisar o impacto da autoridade no comportamento.</button>
            </div>
            <div id="correct10" class="result correct">Resposta correta!</div>
            <div id="incorrect10" class="result incorrect">Resposta errada. A resposta correta é: A.</div>
        </div>
    </div>

    <script>
        function showResult(resultId) {
            const results = document.querySelectorAll('.result');
            results.forEach(result => result.style.display = 'none');
            const result = document.getElementById(resultId);
            if (result) {
                result.style.display = 'block';
            }
        }
    </script>
</body>
</html>
