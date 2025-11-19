# 📘 Documentation — Structure des données (MVP EduTechBurkina)

## 1️⃣ Course (Cours)
Représente un cours dans la plateforme.

```json
{
  "id": "course_01",
  "title": "Nom du cours",
  "description": "Description du cours",
  "lessons": ["lesson_01", "lesson_02"],
  "packId": "pack_01"
}
{
  "id": "lesson_01",
  "title": "Titre de la leçon",
  "content": "Texte, vidéo, exercices",
  "quizId": "quiz_01"
}
{
  "id": "quiz_01",
  "questions": [
    {
      "question": "Qu'est-ce qu'une variable ?",
      "answers": ["A", "B", "C"],
      "correct": "A"
    }
  ]
}             
{
  "id": "pack_01",
  "name": "Nom du pack",
  "courses": ["course_01", "course_02"]
}