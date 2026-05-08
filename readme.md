# Todo App Assignment

# Features

## Backend

Create APIs for:

- Get all todos
- Create todo
- Update todo status
- Delete todo

### Todo Model

```ts
{
  id: number;
  title: string;
  completed: boolean;
}
```

### Validation

- Title is required
- Empty title should return error

---

## Frontend

Build a simple UI to:

- Display todos
- Add new todo
- Mark todo as completed/uncompleted
- Delete todo

### UI Notes

- Keep UI simple and clean
- Show loading state during API calls

---

### Bonus

- Search todo by title
