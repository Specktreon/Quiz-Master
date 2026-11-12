# Quiz Master (Unity)

A timed multiple-choice quiz game built in Unity.

## Features

- **Questions as ScriptableObjects** (`QuestionSO`): question text, 4 answers and the correct answer index, editable from the Inspector without touching code.
- **Timer** per question, shown as a radial fill; time spent reading the answer is separate from answering time.
- **Answer feedback**: the correct answer is highlighted after each choice or when time runs out.
- **Score keeping** with a live percentage and a progress bar.
- **End screen** with the final score and a replay option.
- UI text with TextMesh Pro.

## Tech stack

Unity 2022.3 LTS · C# · TextMesh Pro

## Scripts

| Script | Role |
|---|---|
| `Quiz.cs` | shows questions, handles answers and feedback |
| `QuestionSO.cs` | ScriptableObject for one question |
| `Timer.cs` | answer and review phases |
| `ScoreKeeper.cs` | correct answers and score percentage |
| `GameManager.cs` | switches between quiz and end screen, replay |
| `EndScreen.cs` | final score display |

## Run it

Open the folder with Unity Hub (Unity 2022.3.53f1 or a later 2022.3 LTS), open `Assets/Scenes/Game.unity` and press Play.

## Credits

Built while following the GameDev.tv Unity 2D course.

## Author

Ridha Lezzar · [LinkedIn](https://linkedin.com/in/ridha-lezzar-8322222b5)
