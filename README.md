# Quizzes de reforço
Esse projeto é composto por diversos quizzes de 10 questões para reforço de conceitos abordados em aula.

Padrão de dados do quiz:
```typescript
interface Question {
  question: string;
  options: string[];
  correct: number;
  feedback: string[];
}

type Quiz = Question[];
// quiz deve ser um json e o nome do arquivo deve ser slug-da-aula.json. e.g., aula-01.json
```

