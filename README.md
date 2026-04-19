# 🎬 CINESPOILERS API

API REST desarrollada con Django Rest Framework para la gestión de películas y directores.

---

## 👥 Integrantes

* Anderson Jair Rivera Pucuhuayla
* yojhan huancca

---

## 🚀 Tecnologías utilizadas

* Python
* Django
* Django Rest Framework
* SQLite
* Thunder Client (VS Code)
* Git & GitHub

---

## 🧠 Descripción del proyecto

Cinespoilers es una API REST que permite gestionar información de películas y directores.
Se implementó siguiendo buenas prácticas de desarrollo backend, incluyendo:

* Arquitectura por apps
* Uso de ModelViewSet
* Serializers para transformación de datos
* Relaciones entre entidades (ForeignKey)
* Consumo de API mediante Thunder Client

---

## 🧱 Modelos principales

### 🎬 Movie

* title
* description
* release_date
* is_active
* director (ForeignKey)

### 🎥 Director

* name
* nationality
* birth_date

---

## 🔗 Endpoints principales

| Método | Endpoint        | Descripción       |
| ------ | --------------- | ----------------- |
| GET    | /api/movies/    | Listar películas  |
| POST   | /api/movies/    | Crear película    |
| GET    | /api/directors/ | Listar directores |
| POST   | /api/directors/ | Crear director    |

---

## 🧪 Pruebas con Thunder Client

### 🔥 Crear Director (POST)

📌 Endpoint:

```
http://127.0.0.1:8000/api/directors/
```

📌 Body:

```json
{
  "name": "Christopher Nolan",
  "nationality": "British-American",
  "birth_date": "1970-07-30"
}
```

📸 Evidencia:
![POST Director](./screenshots/director_post.png)

---

### 🎬 Crear Película (POST)

📌 Endpoint:

```
http://127.0.0.1:8000/api/movies/
```

📌 Body:

```json
{
  "title": "Inception",
  "description": "Un ladrón roba secretos dentro de los sueños.",
  "release_date": "2010-07-16",
  "director": 1,
  "is_active": true
}
```

📸 Evidencia:
![POST Movie](./screenshots/movie_post.png)

---

### 🔍 Listar Películas (GET)

📌 Endpoint:

```
http://127.0.0.1:8000/api/movies/
```

📸 Evidencia:
![GET Movies](./screenshots/movies_get.png)

---

## 🖥️ Panel de Administración

Se utilizó el panel admin de Django para gestionar datos manualmente.

📸 Evidencia:
![Admin Movies](./screenshots/admin_movies.png)

---

## 👨‍💻 Evidencia de trabajo en equipo

### Integrante 1 - Anderson

📸 Desarrollo de modelos y API:
![Trabajo Anderson](./screenshots/anderson_work.png)

---

### Integrante 2 - Compañero

📸 Desarrollo de pruebas y endpoints:
![Trabajo Compañero](./screenshots/compa_work.png)

---

## 🗂️ Estructura del proyecto

```
cinespoilers/
├── apps/
│   └── movies/
├── config/
├── manage.py
```

---

## ⚙️ Instalación

```bash
git clone --recurse-submodules <repo_url>
cd cinespoilers
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## 🎯 Conclusiones

* Se logró implementar una API REST funcional
* Se aplicaron buenas prácticas de desarrollo backend
* Se trabajó de forma colaborativa usando Git
* Se validó el funcionamiento mediante pruebas con Thunder Client

---

## 📌 Autor

Proyecto académico - 2026
