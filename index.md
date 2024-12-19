---
title: Welcome Language Exploration
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Language Exploration Project</title>
    
    <!-- Bootstrap CSS -->
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Link to custom CSS -->
    <link rel="stylesheet" href="css/style.css">
    
    <!-- Additional styling to ensure Tableau and other embedded content work -->
    <style>
        body {
            background-color: #f0f8ff; /* Light blue color */
        }
        .tableau-container {
            width: 100%;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
        }
        .video-container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="text-center my-4">
            <h1>Exploring World Languages</h1>
            <nav>
                <a href="#about" class="btn btn-primary">About</a> 
                <a href="#content" class="btn btn-primary">Content</a> 
                <a href="index.html" class="btn btn-secondary">Back to Professional Site</a>
                <a href="riddle-generator.html" class="btn btn-primary">Riddle Generator</a>
            </nav>
        </header>

        <main>
            <section id="about" class="my-5">
                <h2>About World Languages</h2>
                <p>An exploration of linguistic diversity around the globe, showcasing the rich tapestry of human communication.</p>
            </section>

            <section id="content" class="my-5">
                <h2>Linguistic Landscape</h2>
                
                <!-- Nested List Demonstration -->
                <ol>
                    <li>Language Diversity Benefits
                        <ul>
                            <li>Geographic Distribution</li>
                            <li>Cultural and global perspectives</li>
                            <li>Language preservation</li>
                            <li>Multilingualism</li>
                            <li>Linguistic diversity in education or workplaces</li>
                        </ul>
                    </li>
                </ol>

                <!-- Custom Image -->
                <div class="image-container">
                    <img src="https://img.freepik.com/premium-vector/cartoon-flat-teacher-pupils-students-characters-study-language-class_189557-1164.jpg" alt="Language Classroom Cartoon">
                    <p class="text-center">Language Learning Illustration</p>
                </div>

                <!-- YouTube Video Embedding -->
                <div class="video-container">
                    <h3>Language Diversity Documentary</h3>
                    <iframe 
                        width="100%" 
                        height="450" 
                        src="https://www.youtube.com/embed/VQRjouwKDlU" 
                        title="Language Diversity" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                        allowfullscreen>
                    </iframe>
                </div>

                <!-- Tableau Visualization -->
                <div class="tableau-container">
                    <h3>Worldwide Language Visualization</h3>
                    <div class='tableauPlaceholder' id='viz1704162293291' style='position: relative'>
                        <noscript>
                            <a href='#'>
                                <img alt='Worldwide Language Devi Arnita 2 ' src='https://public.tableau.com/static/images/Wo/WorldwideLanguageDevitwbxPublicversion2/WorldwideLanguageDeviArnita2/1_rss.png' style='border: none' />
                            </a>
                        </noscript>
                        <object class='tableauViz' style='display:none;'>
                            <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
                            <param name='embed_code_version' value='3' /> 
                            <param name='site_root' value='' />
                            <param name='name' value='WorldwideLanguageDevitwbxPublicversion2&#47;WorldwideLanguageDeviArnita2' />
                            <param name='tabs' value='no' />
                            <param name='toolbar' value='yes' />
                            <param name='static_image' value='https://public.tableau.com/static/images/Wo/WorldwideLanguageDevitwbxPublicversion2/WorldwideLanguageDeviArnita2/1.png' />
                            <param name='animate_transition' value='yes' />
                            <param name='display_static_image' value='yes' />
                            <param name='display_spinner' value='yes' />
                            <param name='display_overlay' value='yes' />
                            <param name='display_count' value='yes' />
                            <param name='language' value='en-US' />
                            <param name='filter' value='publish=yes' />
                        </object>
                    </div>
                    <script type='text/javascript'>                    
                        var divElement = document.getElementById('viz1704162293291');                    
                        var vizElement = divElement.getElementsByTagName('object')[0];                    
                        if ( divElement.offsetWidth > 800 ) { 
                            vizElement.style.width='1000px';
                            vizElement.style.height='827px';
                        } else if ( divElement.offsetWidth > 500 ) { 
                            vizElement.style.width='1000px';
                            vizElement.style.height='827px';
                        } else { 
                            vizElement.style.width='100%';
                            vizElement.style.height='727px';
                        }                     
                        var scriptElement = document.createElement('script');                    
                        scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
                        vizElement.parentNode.insertBefore(scriptElement, vizElement);                
                    </script>
                </div>

                <!-- Web App Link -->
                <div class="text-center my-4">
                    <a href="riddle generator html>.html" class="btn btn-primary">Check Out Multilingual Riddle Generator</a>
                </div>
            </section>

            <!-- Multilingual Riddle Master Section -->
            <section id="riddle-master" class="my-5">
                <h2>Multilingual Riddle Master</h2>
                <div class="riddle-container">
                    <h1>🧩 Riddle Master</h1>
                    
                    <div class="language-selector">
                        <label for="languageSelect">Select Language:</label>
                        <select id="languageSelect">
                            <option value="en">English</option>
                            <option value="es">Spanish</option>
                            <option value="fr">French</option>
                        </select>
                    </div>

                    <div class="difficulty-selector">
                        <label for="difficultySelect">Select Difficulty:</label>
                        <select id="difficultySelect">
                            <option value="easy">Easy</option>
                            <option value="medium">Medium</option>
                            <option value="hard">Hard</option>
                        </select>
                    </div>

                    <div id="riddleText">Press "Generate Riddle" to start!</div>
                    
                    <input 
                        type="text" 
                        id="answerInput" 
                        placeholder="Type your answer here" 
                        style="display:none;"
                    >
                    
                    <div>
                        <button id="generateBtn" class="btn btn-primary">Generate Riddle</button>
                        <button id="submitBtn" class="btn btn-primary" style="display:none;">Submit Answer</button>
                    </div>

                    <div id="resultMessage"></div>
                    
                    <div style="margin-top: 20px;">
                        <a href="scratch-page.html" class="btn btn-secondary">Back to Scratch Page</a>
                    </div>

                    <div class="nested-lists">
                        <h2>Why Solve Riddles?</h2>
                        <ol>
                            <li>Mental Exercise
                                <ul>
                                    <li>Improves cognitive abilities</li>
                                    <li>Enhances problem-solving skills</li>
                                </ul>
                            </li>
                            <li>Language Skills
                                <ul>
                                    <li>Expands vocabulary</li>
                                    <li>Improves comprehension</li>
                                </ul>
                            </li>
                        </ol>
                    </div>

                    <div class="image-container">
                        <img src="https://example.com/riddle-image.jpg" alt="Riddle Illustration" width="100%">
                    </div>

                    <div class="video-container">
                        <h3>Learn About Riddles</h3>
                        <iframe width="100%" height="315" src="https://www.youtube.com/embed/some-video-id" title="Riddles" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>

                    <div class="on-page-anchor">
                        <a href="#riddleText" class="btn btn-primary">Go to Riddle</a>
                    </div>
                </div>

                <script>
                    // Multilingual Riddle Database
                    const riddleDatabase = {
                        en: {
                            easy: [
                                { riddle: "What has keys but no locks, space but no room, and you can enter but not go in?", answer: "keyboard" },
                                { riddle: "What gets wet while drying?", answer: "towel" }
                            ],
                            medium: [
                                { riddle: "I speak without a mouth and hear without ears. I have no body, but I come alive with wind. What am I?", answer: "echo" },
                                { riddle: "The more you take, the more you leave behind. What am I?", answer: "footsteps" }
                            ],
                            hard: [
                                { riddle: "I am not alive, but I grow; I don't have lungs, but I need air; I don't have a mouth, but water kills me. What am I?", answer: "fire" }
                            ]
                        },
                        es: {
                            easy: [
                                { riddle: "Tengo ciudades, pero no casas. Tengo montañas, pero no árboles. Tengo agua, pero no peces. ¿Qué soy?", answer: "mapa" }
                            ],
                            medium: [
                                { riddle: "Cuanto más le quitas, más grande se hace. ¿Qué soy?", answer: "hoyo" }
                            ],
                            hard: [
                                { riddle: "Siempre va hacia arriba, pero nunca baja. ¿Qué soy?", answer: "edad" }
                            ]
                        },
                        fr: {
                            easy: [
                                { riddle: "Je suis plein de trous, mais je peux encore contenir de l'eau. Qui suis-je?", answer: "éponge" },
                                { riddle: "Que peut voyager partout sans bouger?", answer: "image" }
                            ],
                            medium: [
                                { riddle: "Plus on me prend, plus je suis grand. Qui suis-je?", answer: "trou" }
                            ],
                            hard: [
                                { riddle: "Je suis quelque chose que vous pouvez attraper mais jamais jeter. Qui suis-je?", answer: "rhume" }
                            ]
                        }
                    };

                    const languageSelect = document.getElementById('languageSelect');
                    const difficultySelect = document.getElementById('difficultySelect');
                    const generateBtn = document.getElementById('generateBtn');
                    const submitBtn = document.getElementById('submitBtn');
                    const riddleText = document.getElementById('riddleText');
                    const answerInput = document.getElementById('answerInput');
                    const resultMessage = document.getElementById('resultMessage');

                    let currentRiddle = null;

                    function getRandomRiddle(language, difficulty) {
                        const langRiddles = riddleDatabase[language][difficulty];
                        return langRiddles[Math.floor(Math.random() * langRiddles.length)];
                    }

                    generateBtn.addEventListener('click', () => {
                        const language = languageSelect.value;
                        const difficulty = difficultySelect.value;
                        
                        currentRiddle = getRandomRiddle(language, difficulty);
                        riddleText.textContent = currentRiddle.riddle;
                        
                        answerInput.style.display = 'block';
                        submitBtn.style.display = 'inline-block';
                        resultMessage.textContent = '';
                        answerInput.value = '';
                    });

                    submitBtn.addEventListener('click', () => {
                        if (!currentRiddle) return;

                        const userAnswer = answerInput.value.toLowerCase().trim();
                        const correctAnswer = currentRiddle.answer.toLowerCase();

                        if (userAnswer === correctAnswer) {
                            resultMessage.style.color = 'green';
                            resultMessage.textContent = '🎉 Correct! You solved the riddle!';
                        } else {
                            resultMessage.style.color = 'red';
                            resultMessage.textContent = `❌ Wrong answer. The correct answer was "${currentRiddle.answer}".`;
                        }
                    });
                </script>
            </section>

            <!-- Resume Section -->
            <section id="resume" class="my-5">
                <h2>Resume</h2>
                <h3>Education</h3>
                <ul>
                    <li>Bachelor Business Management</li>
                    <li>Minor in Psychology</li>
                    <li>Minor in German</li>
                </ul>
                <h3>Work Experience</h3>
                <ul>
                    <li>Social Media Manager</li>
                    <li>German Tutor</li>
                </ul>
                <h3>Skills</h3>
                <ul>
                    <li>Knowledge in Three Languages</li>
                    <li>Proficient in Microsoft Excel</li>
                    <li>German Tutor</li>
                </ul>
                <h3>Awards and Honors</h3>
                <ul>
                    <li>Dean's List, BYU</li>
                    <li>NHS Scholar</li>
                </ul>
            </section>
        </main>

        <footer class="text-center my-4">
            <p>© 2024 Language Exploration Project. All rights reserved.</p>
        </footer>
    </div>

    <!-- Bootstrap and Tableau Visualization Scripts -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script type='text/javascript' src='https://public.tableau.com/javascripts/api/viz_v1.js'></script>
</body>
</html>
