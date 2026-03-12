<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS Ultimate Test</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            max-width: 800px;
            width: 100%;
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }

        .timer-section {
            background: rgba(255, 255, 255, 0.2);
            padding: 15px;
            border-radius: 10px;
            margin-top: 15px;
            display: inline-block;
        }

        .timer {
            font-size: 2em;
            font-weight: bold;
            font-family: 'Courier New', monospace;
        }

        .timer.warning {
            color: #ff6b6b;
            animation: pulse 1s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.6; }
        }

        .content {
            padding: 40px;
        }

        .welcome-screen {
            text-align: center;
        }

        .welcome-screen h2 {
            color: #333;
            margin-bottom: 20px;
            font-size: 2em;
        }

        .welcome-screen p {
            color: #666;
            margin-bottom: 15px;
            font-size: 1.1em;
            line-height: 1.6;
        }

        .welcome-screen ul {
            text-align: left;
            max-width: 500px;
            margin: 20px auto;
            background: #f8f9fa;
            padding: 20px 40px;
            border-radius: 10px;
        }

        .welcome-screen li {
            color: #555;
            margin-bottom: 10px;
            font-size: 1.05em;
        }

        .start-btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 15px 50px;
            font-size: 1.2em;
            border-radius: 50px;
            cursor: pointer;
            margin-top: 30px;
            transition: transform 0.2s, box-shadow 0.2s;
            font-weight: bold;
        }

        .start-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(102, 126, 234, 0.4);
        }

        .question-container {
            display: none;
        }

        .progress-bar {
            background: #e0e0e0;
            height: 8px;
            border-radius: 10px;
            margin-bottom: 30px;
            overflow: hidden;
        }

        .progress-fill {
            background: linear-gradient(90deg, #667eea 0%, #764ba2 100%);
            height: 100%;
            transition: width 0.3s ease;
        }

        .question-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }

        .question-number {
            color: #667eea;
            font-weight: bold;
            font-size: 1.1em;
        }

        .difficulty-badge {
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: bold;
        }

        .difficulty-easy {
            background: #d4edda;
            color: #155724;
        }

        .difficulty-medium {
            background: #fff3cd;
            color: #856404;
        }

        .difficulty-hard {
            background: #f8d7da;
            color: #721c24;
        }

        .question-text {
            font-size: 1.3em;
            color: #333;
            margin-bottom: 25px;
            line-height: 1.5;
        }

        .options {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-bottom: 30px;
        }

        .option {
            background: #f8f9fa;
            border: 2px solid #e0e0e0;
            padding: 15px 20px;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.2s;
            font-size: 1.05em;
        }

        .option:hover {
            border-color: #667eea;
            background: #f0f4ff;
            transform: translateX(5px);
        }

        .option.selected {
            border-color: #667eea;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .code-editor {
            margin-bottom: 30px;
        }

        .code-editor textarea {
            width: 100%;
            min-height: 200px;
            padding: 15px;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            font-family: 'Courier New', monospace;
            font-size: 14px;
            resize: vertical;
            background: #1e1e1e;
            color: #d4d4d4;
        }

        .code-editor textarea:focus {
            outline: none;
            border-color: #667eea;
        }

        .code-hint {
            background: #fff3cd;
            border-left: 4px solid #ffc107;
            padding: 10px 15px;
            margin-top: 10px;
            border-radius: 5px;
            font-size: 0.95em;
            color: #856404;
        }

        .submit-btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 12px 40px;
            font-size: 1.1em;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.2s;
            font-weight: bold;
            float: right;
        }

        .submit-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .submit-btn:disabled {
            background: #ccc;
            cursor: not-allowed;
            transform: none;
        }

        .results-screen {
            display: none;
            text-align: center;
        }

        .results-screen h2 {
            color: #333;
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .score-display {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px;
            border-radius: 20px;
            margin: 30px 0;
        }

        .score-display .big-score {
            font-size: 4em;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .score-breakdown {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 15px;
            margin: 20px 0;
            text-align: left;
        }

        .score-breakdown h3 {
            color: #667eea;
            margin-bottom: 20px;
            font-size: 1.5em;
        }

        .breakdown-item {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid #e0e0e0;
            font-size: 1.1em;
        }

        .breakdown-item:last-child {
            border-bottom: none;
        }

        .breakdown-label {
            color: #666;
        }

        .breakdown-value {
            color: #333;
            font-weight: bold;
        }

        .performance-message {
            font-size: 1.3em;
            color: #666;
            margin: 20px 0;
            line-height: 1.6;
        }

        .loading {
            text-align: center;
            padding: 20px;
            color: #667eea;
            font-size: 1.2em;
        }

        .spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid #667eea;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 1s linear infinite;
            margin: 20px auto;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        @media (max-width: 600px) {
            .header h1 {
                font-size: 1.8em;
            }

            .content {
                padding: 20px;
            }

            .question-text {
                font-size: 1.1em;
            }

            .score-display .big-score {
                font-size: 3em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>⚡ JS Ultimate Test</h1>
            <div class="timer-section" id="timerSection" style="display: none;">
                <div>Time Remaining</div>
                <div class="timer" id="timer">30:00</div>
            </div>
        </div>

        <div class="content">
            <!-- Welcome Screen -->
            <div class="welcome-screen" id="welcomeScreen">
                <h2>Welcome to the JavaScript Ultimate Test!</h2>
                <p>Test your JavaScript knowledge from basics to advanced concepts.</p>
                <ul>
                    <li>📝 15 carefully crafted questions</li>
                    <li>🎯 Mix of MCQ and code-writing challenges</li>
                    <li>⏱️ 30 minutes to complete</li>
                    <li>📊 Progressive difficulty (Easy → Medium → Hard)</li>
                    <li>🏆 Instant results and performance analysis</li>
                </ul>
                <button class="start-btn" onclick="startQuiz()">Start Test</button>
            </div>

            <!-- Question Container -->
            <div class="question-container" id="questionContainer">
                <div class="progress-bar">
                    <div class="progress-fill" id="progressFill"></div>
                </div>

                <div class="question-header">
                    <span class="question-number" id="questionNumber">Question 1 of 15</span>
                    <span class="difficulty-badge" id="difficultyBadge">Easy</span>
                </div>

                <div class="question-text" id="questionText"></div>

                <div id="answerArea"></div>

                <button class="submit-btn" id="submitBtn" onclick="submitAnswer()">Next Question</button>
                <div style="clear: both;"></div>
            </div>

            <!-- Results Screen -->
            <div class="results-screen" id="resultsScreen">
                <h2>🎉 Test Complete!</h2>
                <div class="score-display">
                    <div class="big-score" id="finalScore">0/15</div>
                    <div>Your Performance</div>
                </div>

                <div class="performance-message" id="performanceMessage"></div>

                <div class="score-breakdown">
                    <h3>Detailed Breakdown</h3>
                    <div class="breakdown-item">
                        <span class="breakdown-label">Total Questions</span>
                        <span class="breakdown-value" id="totalQuestions">15</span>
                    </div>
                    <div class="breakdown-item">
                        <span class="breakdown-label">Correct Answers</span>
                        <span class="breakdown-value" id="correctAnswers">0</span>
                    </div>
                    <div class="breakdown-item">
                        <span class="breakdown-label">Accuracy</span>
                        <span class="breakdown-value" id="accuracy">0%</span>
                    </div>
                    <div class="breakdown-item">
                        <span class="breakdown-label">Time Taken</span>
                        <span class="breakdown-value" id="timeTaken">0:00</span>
                    </div>
                </div>

                <div class="loading" id="sendingMessage" style="display: none;">
                    <div class="spinner"></div>
                    <p>Sending results to Discord...</p>
                </div>
            </div>
        </div>
    </div>

    <script>
        const QUIZ_DURATION = 30 * 60; // 30 minutes in seconds
        const DISCORD_WEBHOOK = 'https://discord.com/api/webhooks/1481694121214218442/gcEraYM8LORfYSFltlZ9qewtoZ9BRgQxagd56wp5imSt4dYd3v4VSN-eGs2c8YeNgitY';
        
        // Detect if running from file:// protocol
        const isLocalFile = window.location.protocol === 'file:';

        const questions = [
            // EASY QUESTIONS (1-5)
            {
                id: 1,
                difficulty: 'easy',
                type: 'mcq',
                question: 'What is the correct way to declare a variable in JavaScript?',
                options: [
                    'variable myVar = 5;',
                    'let myVar = 5;',
                    'var myVar == 5;',
                    'declare myVar = 5;'
                ],
                correct: 1
            },
            {
                id: 2,
                difficulty: 'easy',
                type: 'mcq',
                question: 'Which of the following is NOT a primitive data type in JavaScript?',
                options: [
                    'String',
                    'Boolean',
                    'Array',
                    'Number'
                ],
                correct: 2
            },
            {
                id: 3,
                difficulty: 'easy',
                type: 'code',
                question: 'Write a function called "sum" that takes two numbers as parameters and returns their sum.',
                hint: 'Use the function keyword and return statement',
                testCases: [
                    { input: [5, 3], expected: 8 },
                    { input: [10, 20], expected: 30 },
                    { input: [-5, 5], expected: 0 }
                ]
            },
            {
                id: 4,
                difficulty: 'easy',
                type: 'mcq',
                question: 'What does "===" operator do in JavaScript?',
                options: [
                    'Compares only values',
                    'Compares values and types',
                    'Assigns a value',
                    'Checks if a variable exists'
                ],
                correct: 1
            },
            {
                id: 5,
                difficulty: 'easy',
                type: 'code',
                question: 'Write a function called "isEven" that returns true if a number is even, false otherwise.',
                hint: 'Use the modulo operator (%) to check if a number is divisible by 2',
                testCases: [
                    { input: [4], expected: true },
                    { input: [7], expected: false },
                    { input: [0], expected: true }
                ]
            },

            // MEDIUM QUESTIONS (6-10)
            {
                id: 6,
                difficulty: 'medium',
                type: 'mcq',
                question: 'What will be the output of: console.log(typeof null)?',
                options: [
                    '"null"',
                    '"undefined"',
                    '"object"',
                    '"number"'
                ],
                correct: 2
            },
            {
                id: 7,
                difficulty: 'medium',
                type: 'code',
                question: 'Write a function called "reverseString" that takes a string and returns it reversed.',
                hint: 'You can use split(), reverse(), and join() methods or a loop',
                testCases: [
                    { input: ['hello'], expected: 'olleh' },
                    { input: ['JavaScript'], expected: 'tpircSavaJ' },
                    { input: [''], expected: '' }
                ]
            },
            {
                id: 8,
                difficulty: 'medium',
                type: 'mcq',
                question: 'What is a closure in JavaScript?',
                options: [
                    'A function that has been closed',
                    'A function that has access to variables in its outer scope',
                    'A method to close connections',
                    'A way to end a program'
                ],
                correct: 1
            },
            {
                id: 9,
                difficulty: 'medium',
                type: 'code',
                question: 'Write a function called "removeDuplicates" that takes an array and returns a new array with duplicates removed.',
                hint: 'You can use Set or filter method',
                testCases: [
                    { input: [[1, 2, 2, 3, 4, 4, 5]], expected: [1, 2, 3, 4, 5] },
                    { input: [['a', 'b', 'a', 'c', 'b']], expected: ['a', 'b', 'c'] },
                    { input: [[1, 1, 1]], expected: [1] }
                ]
            },
            {
                id: 10,
                difficulty: 'medium',
                type: 'mcq',
                question: 'What is the difference between "let" and "var"?',
                options: [
                    'No difference',
                    'let is block-scoped, var is function-scoped',
                    'var is block-scoped, let is function-scoped',
                    'let can be redeclared, var cannot'
                ],
                correct: 1
            },

            // HARD QUESTIONS (11-15)
            {
                id: 11,
                difficulty: 'hard',
                type: 'mcq',
                question: 'What will be the output of: console.log(0.1 + 0.2 === 0.3)?',
                options: [
                    'true',
                    'false',
                    'undefined',
                    'NaN'
                ],
                correct: 1
            },
            {
                id: 12,
                difficulty: 'hard',
                type: 'code',
                question: 'Write a function called "debounce" that takes a function and a delay, and returns a debounced version of that function.',
                hint: 'Use setTimeout and clearTimeout. The function should only execute after the specified delay has passed without being called again.',
                testCases: [] // Manual testing for debounce
            },
            {
                id: 13,
                difficulty: 'hard',
                type: 'mcq',
                question: 'What is the output of: console.log([1, 2, 3] + [4, 5, 6])?',
                options: [
                    '[1, 2, 3, 4, 5, 6]',
                    '"1,2,34,5,6"',
                    '[5, 7, 9]',
                    'Error'
                ],
                correct: 1
            },
            {
                id: 14,
                difficulty: 'hard',
                type: 'code',
                question: 'Write a function called "flattenArray" that takes a nested array and returns a flattened version (all nested arrays merged into one).',
                hint: 'Use recursion or the flat() method',
                testCases: [
                    { input: [[1, [2, [3, 4], 5], 6]], expected: [1, 2, 3, 4, 5, 6] },
                    { input: [[[1], [2], [3]]], expected: [1, 2, 3] },
                    { input: [[1, 2, 3]], expected: [1, 2, 3] }
                ]
            },
            {
                id: 15,
                difficulty: 'hard',
                type: 'mcq',
                question: 'What is "hoisting" in JavaScript?',
                options: [
                    'Moving code to the cloud',
                    'Variable and function declarations are moved to the top of their scope during compilation',
                    'Lifting heavy objects in code',
                    'A way to optimize code execution'
                ],
                correct: 1
            }
        ];

        let currentQuestionIndex = 0;
        let userAnswers = [];
        let timerInterval;
        let timeRemaining = QUIZ_DURATION;
        let startTime;

        function startQuiz() {
            document.getElementById('welcomeScreen').style.display = 'none';
            document.getElementById('questionContainer').style.display = 'block';
            document.getElementById('timerSection').style.display = 'block';
            
            startTime = Date.now();
            startTimer();
            displayQuestion();
        }

        function startTimer() {
            updateTimerDisplay();
            timerInterval = setInterval(() => {
                timeRemaining--;
                updateTimerDisplay();

                if (timeRemaining <= 60) {
                    document.getElementById('timer').classList.add('warning');
                }

                if (timeRemaining <= 0) {
                    clearInterval(timerInterval);
                    finishQuiz(true); // true indicates time's up
                }
            }, 1000);
        }

        function updateTimerDisplay() {
            const minutes = Math.floor(timeRemaining / 60);
            const seconds = timeRemaining % 60;
            document.getElementById('timer').textContent = 
                `${minutes}:${seconds.toString().padStart(2, '0')}`;
        }

        function displayQuestion() {
            const question = questions[currentQuestionIndex];
            
            // Update progress
            const progress = ((currentQuestionIndex + 1) / questions.length) * 100;
            document.getElementById('progressFill').style.width = progress + '%';
            
            // Update question info
            document.getElementById('questionNumber').textContent = 
                `Question ${currentQuestionIndex + 1} of ${questions.length}`;
            document.getElementById('difficultyBadge').className = 
                `difficulty-badge difficulty-${question.difficulty}`;
            document.getElementById('difficultyBadge').textContent = 
                question.difficulty.charAt(0).toUpperCase() + question.difficulty.slice(1);
            document.getElementById('questionText').textContent = question.question;
            
            // Display answer area
            const answerArea = document.getElementById('answerArea');
            
            if (question.type === 'mcq') {
                answerArea.innerHTML = `
                    <div class="options" id="options">
                        ${question.options.map((option, index) => `
                            <div class="option" onclick="selectOption(${index})">
                                ${option}
                            </div>
                        `).join('')}
                    </div>
                `;
            } else if (question.type === 'code') {
                answerArea.innerHTML = `
                    <div class="code-editor">
                        <textarea id="codeInput" placeholder="Write your code here..."></textarea>
                        ${question.hint ? `<div class="code-hint">💡 Hint: ${question.hint}</div>` : ''}
                    </div>
                `;
            }
            
            // Update button text
            document.getElementById('submitBtn').textContent = 
                currentQuestionIndex === questions.length - 1 ? 'Finish Test' : 'Next Question';
        }

        function selectOption(index) {
            // Remove previous selection
            document.querySelectorAll('.option').forEach(opt => {
                opt.classList.remove('selected');
            });
            
            // Add selection to clicked option
            document.querySelectorAll('.option')[index].classList.add('selected');
        }

        function submitAnswer() {
            const question = questions[currentQuestionIndex];
            let answer;
            
            if (question.type === 'mcq') {
                const selected = document.querySelector('.option.selected');
                if (!selected) {
                    alert('Please select an answer!');
                    return;
                }
                answer = Array.from(document.querySelectorAll('.option')).indexOf(selected);
            } else if (question.type === 'code') {
                answer = document.getElementById('codeInput').value.trim();
                if (!answer) {
                    alert('Please write some code!');
                    return;
                }
            }
            
            userAnswers.push({
                questionId: question.id,
                answer: answer,
                question: question
            });
            
            currentQuestionIndex++;
            
            if (currentQuestionIndex < questions.length) {
                displayQuestion();
            } else {
                finishQuiz(false);
            }
        }

        function finishQuiz(timeUp) {
            clearInterval(timerInterval);
            
            const timeTaken = QUIZ_DURATION - timeRemaining;
            const results = calculateResults();
            
            displayResults(results, timeTaken, timeUp);
            sendToDiscord(results, timeTaken, timeUp);
        }

        function calculateResults() {
            let correctCount = 0;
            const detailedResults = [];
            
            userAnswers.forEach(userAnswer => {
                const question = userAnswer.question;
                let isCorrect = false;
                
                if (question.type === 'mcq') {
                    isCorrect = userAnswer.answer === question.correct;
                } else if (question.type === 'code') {
                    isCorrect = evaluateCode(userAnswer.answer, question);
                }
                
                if (isCorrect) correctCount++;
                
                detailedResults.push({
                    questionId: question.id,
                    difficulty: question.difficulty,
                    type: question.type,
                    isCorrect: isCorrect
                });
            });
            
            return {
                total: questions.length,
                correct: correctCount,
                percentage: Math.round((correctCount / questions.length) * 100),
                detailedResults: detailedResults
            };
        }

        function evaluateCode(code, question) {
            if (!question.testCases || question.testCases.length === 0) {
                // For questions without test cases (like debounce), just check if code is provided
                return code.length > 20; // Basic check for substantial code
            }
            
            try {
                // Create function from code
                const userFunction = new Function('return ' + code)();
                
                // Test all cases
                return question.testCases.every(testCase => {
                    try {
                        const result = userFunction(...testCase.input);
                        if (Array.isArray(testCase.expected)) {
                            return JSON.stringify(result) === JSON.stringify(testCase.expected);
                        }
                        return result === testCase.expected;
                    } catch (e) {
                        return false;
                    }
                });
            } catch (e) {
                return false;
            }
        }

        function displayResults(results, timeTaken, timeUp) {
            document.getElementById('questionContainer').style.display = 'none';
            document.getElementById('resultsScreen').style.display = 'block';
            
            document.getElementById('finalScore').textContent = `${results.correct}/${results.total}`;
            document.getElementById('correctAnswers').textContent = results.correct;
            document.getElementById('accuracy').textContent = results.percentage + '%';
            
            const minutes = Math.floor(timeTaken / 60);
            const seconds = timeTaken % 60;
            document.getElementById('timeTaken').textContent = 
                `${minutes}:${seconds.toString().padStart(2, '0')}`;
            
            // Performance message
            let message = '';
            if (timeUp) {
                message = '⏰ Time\'s up! ';
            }
            
            if (results.percentage >= 90) {
                message += 'Outstanding! You\'re a JavaScript master! 🏆';
            } else if (results.percentage >= 75) {
                message += 'Great job! You have a solid understanding of JavaScript! 🌟';
            } else if (results.percentage >= 60) {
                message += 'Good effort! Keep practicing to improve! 💪';
            } else if (results.percentage >= 40) {
                message += 'Not bad! There\'s room for improvement. Keep learning! 📚';
            } else {
                message += 'Keep studying! Practice makes perfect! 🚀';
            }
            
            document.getElementById('performanceMessage').textContent = message;
        }

        async function sendToDiscord(results, timeTaken, timeUp) {
            document.getElementById('sendingMessage').style.display = 'block';
            
            const minutes = Math.floor(timeTaken / 60);
            const seconds = timeTaken % 60;
            const timeString = `${minutes}:${seconds.toString().padStart(2, '0')}`;
            
            // Count by difficulty
            const easyCorrect = results.detailedResults.filter(r => r.difficulty === 'easy' && r.isCorrect).length;
            const mediumCorrect = results.detailedResults.filter(r => r.difficulty === 'medium' && r.isCorrect).length;
            const hardCorrect = results.detailedResults.filter(r => r.difficulty === 'hard' && r.isCorrect).length;
            
            const embed = {
                title: '⚡ JS Ultimate Test Results',
                color: timeUp ? 16744272 : (results.percentage >= 75 ? 5763719 : results.percentage >= 50 ? 16776960 : 15548997),
                fields: [
                    {
                        name: '📊 Overall Score',
                        value: `${results.correct}/${results.total} (${results.percentage}%)`,
                        inline: true
                    },
                    {
                        name: '⏱️ Time Taken',
                        value: timeUp ? `${timeString} (Time's Up!)` : timeString,
                        inline: true
                    },
                    {
                        name: '🎯 Accuracy',
                        value: `${results.percentage}%`,
                        inline: true
                    },
                    {
                        name: '✅ Easy Questions',
                        value: `${easyCorrect}/5`,
                        inline: true
                    },
                    {
                        name: '📝 Medium Questions',
                        value: `${mediumCorrect}/5`,
                        inline: true
                    },
                    {
                        name: '🔥 Hard Questions',
                        value: `${hardCorrect}/5`,
                        inline: true
                    }
                ],
                timestamp: new Date().toISOString(),
                footer: {
                    text: 'JS Ultimate Test'
                }
            };
            
            const payload = {
                username: 'JS Ultimate Test Bot',
                embeds: [embed]
            };
            
            // If running from file://, show warning
            if (isLocalFile) {
                document.getElementById('sendingMessage').innerHTML = `
                    <p style="color: #ff9800;">⚠️ Cannot send from local file</p>
                    <p style="color: #666; font-size: 0.9em; margin-top: 10px;">
                        To send results to Discord, you need to:<br><br>
                        <strong>Option 1:</strong> Run a local web server:<br>
                        <code style="background: #f0f0f0; padding: 5px 10px; border-radius: 5px; display: inline-block; margin: 5px 0;">python -m http.server 8000</code><br>
                        Then open: <code style="background: #f0f0f0; padding: 5px 10px; border-radius: 5px;">http://localhost:8000/js-ultimate-test.html</code><br><br>
                        
                        <strong>Option 2:</strong> Host it online (GitHub Pages, Netlify, etc.)<br><br>
                        
                        <strong>Your results:</strong> ${results.correct}/${results.total} (${results.percentage}%) in ${timeString}
                    </p>
                `;
                return;
            }
            
            try {
                const response = await fetch(DISCORD_WEBHOOK, {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json',
                    },
                    body: JSON.stringify(payload)
                });
                
                if (response.ok) {
                    document.getElementById('sendingMessage').innerHTML = 
                        '<p style="color: #28a745; font-size: 1.2em;">✅ Results sent to Discord successfully!</p>';
                } else {
                    const errorText = await response.text();
                    console.error('Discord API Error:', response.status, errorText);
                    document.getElementById('sendingMessage').innerHTML = 
                        `<p style="color: #dc3545;">❌ Failed to send results.</p>
                         <p style="color: #666; font-size: 0.9em;">Status: ${response.status} - ${errorText || 'Unknown error'}</p>
                         <p style="color: #666; font-size: 0.9em;">Your score: ${results.correct}/${results.total} (${results.percentage}%)</p>`;
                }
            } catch (error) {
                console.error('Network Error:', error);
                document.getElementById('sendingMessage').innerHTML = 
                    `<p style="color: #dc3545;">❌ Network error</p>
                     <p style="color: #666; font-size: 0.9em;">${error.message}</p>
                     <p style="color: #666; font-size: 0.9em; margin-top: 10px;">
                        Make sure you're running this from a web server (http://), not a local file (file:///)
                     </p>
                     <p style="color: #666; font-size: 0.9em;">Your score: ${results.correct}/${results.total} (${results.percentage}%)</p>`;
            }
        }
    </script>
</body>
</html>
