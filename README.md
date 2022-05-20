### Georeferenced task management


### Requsitos

- [] Deve ser possivel crir uma task
- [] Deve ser possivel buscar uma task
- [] Deve ser possivel alterar o titulo ou deadline em uma task
- [] Deve ser possivel marcar uma task como concluída
- [] Deve ser possivel deletar uma task

---

### Regras de negócio

- [] Não deve ser possivel crir uma task quando as coordenadas não estiverem dentro do territótio brasileiro.

---

### Model fields

- Task { 
    id: uuid,
    title: string, 
    latitude: string,  
    longetudi: string,
    status: false, 
    achievementDate: new date, 
    created_at: new date 
    }
    - create (POST /tasks)
    - find todo (GET /tasks )
    - Update todos (PUT /tasks/:id)
    - Upadate done (PATCH /tasks/:id/done)
    - Delete todo (DELETE /tasks/:id )