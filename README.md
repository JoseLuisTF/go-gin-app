
# ToDoTasks Go con Framework Web Gin

Aplicacion web desarrollada con el framework Gin usando el lenguaje de programacion Go


## Requerimientos

- Go
- MySQL

## Ejecutar

- git clone
- crear database MySQL
```
	USER := "root"
	PASS := ""
	HOST := "localhost"
	PORT := "3306"
	DBNAME := "bookCRUD"
```
- ejecutar desde la raiz del projecto
```
go run main.go
```

## API Reference

| Method | URL | Decription |
| ------ | --- | ---------- |
| GET   | /tasks | obtiene todas las tareas |
| POST   | /tasks | crea una tarea |
| GET   | /tasks/id | obtiene una tarea por id |
| PATCH   | /tasks/id | actualiza una tarea por id|
| DELETE   | /tasks/id | elimina una tarea por id |





## JSON Request Bodys

#### Crear una Tarea 

```json
{
    "assignedTo":"name",
    "task":"task",
    "deadline":"2022-06-06"
}
```
