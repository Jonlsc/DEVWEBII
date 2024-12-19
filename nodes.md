
# LISTA DE TAREFAS


# BASE DE DADOS
    users
        id
        username
        password
        created_at
        updated_at

    tasks
        id
        id_user
        task_text
        task_status(new | in progress | canceled | done)
        created_at
        updated_at
