# JS 2 - Kompetenzcheck Quiz Web App

Ziel: Das Ziel dieser Übung ist es, eine erweiterbare Quiz-Webanwendung mit JavaScript zu erstellen. Das Thema ist frei wählbar, mögliche Themen könnten sein:  

- Serien-, Film-, Game- oder Anime-Quiz  
- Mathe-Quiz mit Rechenaufgaben 

![Structure of an URL](../img/bsp_quiz_joe.png "HTTP Request")
![Structure of an URL](../img/bsp_quiz_vidan.png "HTTP Request")

Die Anwendung besteht aus einem Spielfeld mit 9 Feldern, die jeweils eine unterschiedliche Frage repräsentieren. Die Spieler:innen gelangen nur zum nächsten Feld, wenn sie die aktuelle Frage richtig beantworten. Das Spielfeld sollte den Fortschritt und den Status jeder Frage visuell anzeigen.  

1. Baue das Spielfeld auf:  
- Erstelle eine HTML-Datei mit einem Container für das Spielfeld.  
- Unterteile den Container in 9 Felder, um die verschiedenen Fragen darzustellen.  
- Verwende CSS, um das Spielfeld und die Felder zu gestalten.

2. Erstelle ein Array von Fragen:
- Definiere ein Array mit Frage-Objekten
- Die Struktur des Objekts soll so aussehen:
```javascript
{
    question: 'In what year did the wallstreet crash take place?',
    correctAnswer: '1929',
    incorrectAnswers: ['1919', '1930', '1921']
}
```
- Jedes Frage-Objekt sollte die folgenden Attribute haben:
    - **question**: Der Text der Frage.  
    - **correctAnswer**: Die richtige Antwort auf die Frage.  
    - **incorrectAnswers**: Ein Array möglicher Antwortmöglichkeiten.

3. Baue die Logik für das Quiz:  
- JavaScript-Code, um die Quiz-Funktionalität zu behandeln.  
- Erstelle eine Variable, um den aktuellen Frageindex zu verfolgen.  
- Füge jedem Feld auf dem Spielfeld Event-Listener hinzu.  
- Wenn ein Feld angeklickt wird, zeige die entsprechende Frage an.  
- Fordere den Benutzer auf, seine Antwort einzugeben.  
- Überprüfe, ob die Antwort korrekt ist, indem du sie mit der richtigen Antwort vergleichst.  
- Wenn die Antwort korrekt ist, aktualisiere das Spielfeld, um den Fortschritt anzuzeigen (z. B. Farbänderung).  
- Wenn die Antwort falsch ist, zeige eine Fehlermeldung an.

4. Implementiere den Ablauf des Spiels:  
- Starte das Spiel, indem du die erste Frage anzeigst.  
- Wenn der Benutzer Fragen richtig beantwortet, aktualisiere das Spielfeld, um den Fortschritt anzuzeigen.  
- Wenn der Benutzer eine Frage falsch beantwortet, verhindere, dass er zur nächsten Frage gelangt.

5. Füge abschließende Details hinzu:  
- Passe das visuelle Feedback auf dem Spielfeld an, um den Status jeder Frage anzuzeigen.  
- Implementiere eine Möglichkeit, den Punktestand des Benutzers zu verfolgen und anzuzeigen.  
- Gestalte die Quiz-App, um sie visuell ansprechend zu gestalten.

6. Code-Erweiterbarkeit sicherstellen:  
-  den Code so, dass die Quiz-Webanwendung leicht erweiterbar ist. 
- Verwende Funktionen um den Code übersichtlich und wiederverwendbar zu gestalten.  
- Betrachte die Möglichkeit, das Array der Fragen dynamisch zu gestalten, damit weitere Fragen einfach hinzugefügt werden können.  

7. Teste und verfeinere:  
- Teste die Quiz-Webanwendung, um sicherzustellen, dass sie wie erwartet funktioniert.  
- Behebe auftretende Probleme oder Fehler.  
- Verfeinere den Code und das Design bei Bedarf.

**EN:**

Goal:  

The goal of this exercise is to create an expandable quiz web application using JavaScript. The theme is of your choice, and possible themes could include:  

- TV series, movie, game, or anime quiz  
- Math quiz with arithmetic problems  

Instructions:  

1. Build the game board:  
- Create an HTML file with a container for the game board.  
- Divide the container into 9 squares to represent different questions.  
- Use CSS to style the game board and squares.  

2. Create an array of questions:  
- Define an array with 9 question objects.
- The structure of the object looks like that:
```javascript
{
    question: 'In what year did the wallstreet crash take place?',
    correctAnswer: '1929',
    incorrectAnswers: ['1919', '1930', '1921']
}
```
- Each question object should have the following properties:  
    - Question: The text of the question.  
    - Answer: The correct answer to the question.  
    - Options: An array of possible answer choices.  

3. Implement the quiz logic:  
- Write JavaScript code to handle the quiz functionality.  
- Create a variable to track the current question index.  
- Add event listeners to each square on the game board.  
- When a square is clicked, display the corresponding question.  
- Prompt the user to enter their answer.  
- Check if the answer is correct by comparing it with the correct answer.  
- If the answer is correct, update the game board to show progress (e.g., change color).  
- If the answer is wrong, display an error message.  

4. Implement the flow of the game:  
- Start the game by displaying the first question.  
- If the user answers questions correctly, update the game board to show progress.  
- If the user answers a question incorrectly, prevent them from moving to the next question.  

5. Add final touches:  
- Customize the visual feedback on the game board to indicate the status of each question.  
- Implement a way to track and display the user's score.  
- Style the quiz app to make it visually appealing.  

6. Ensure code extensibility:  
- Write the code in a way that the quiz web application is easily expandable. 
- Use functions to make the code more readable and reusable.  
- Consider making the array of questions dynamic, allowing for easy addition of more questions.  

7. Test and refine:  
- Test the quiz web application to ensure it functions as expected.  
- Address any issues or bugs that arise.  
- Refine the code and design as needed.  