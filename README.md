# 🎬 CINESPOILERS API - DIRECTORES

API REST desarrollada con Django Rest Framework para la gestión de **Directores**.

---

## 👥 Integrantes

* Anderson Jair Rivera Pucuhuayla
* Yojhan Leodan Hunaca Yucra 

---

## 🚀 Tecnologías utilizadas

* Python
* Django
* Django Rest Framework
* SQLite
* Thunder Client (VS Code)
* Git & GitHub

---

## 🧠 Descripción

Este módulo permite realizar operaciones CRUD sobre la entidad **Director**, incluyendo validaciones y pruebas mediante Thunder Client.

---

## 🧱 Modelo Director

Campos:

* `name` → Nombre del director
* `nationality` → Nacionalidad
* `birth_date` → Fecha de nacimiento

---

## 🔗 Endpoint Base

```id="ep1"
http://127.0.0.1:8000/api/directors/
```

---

#  PRUEBAS CON THUNDER CLIENT
## Anderson rivera 
---

##  1. Crear Director (POST)

```id="ep2"
POST /api/directors/
```

Body:

```json id="json1"
{
  "name": "Christopher Nolan",
  "nationality": "British-American",
  "birth_date": "1970-07-30"
}
```

📸 Evidencia:
![POST Director](./docs/postdirector.png)

---

## 📋 2. Listar Directores (GET)

```id="ep3"
GET /api/directors/
```

📸 Evidencia:
![GET Directors](./docs/getdirectors.png)

---

##  3. Obtener Director por ID (GET)

```id="ep4"
GET /api/directors/1/
```

📸 Evidencia:
![GET Director ID](./docs/image.png)

---

## 4. Actualizar Director (PUT)

```id="ep5"
PUT /api/directors/1/
```

📌 Body:

```json id="json2"
{
  "name": "Christopher Nolan Updated",
  "nationality": "British",
  "birth_date": "1970-07-30"
}
```

📸 Evidencia:
![PUT Director](./docs/put.png)

---

##  5. Actualización Parcial (PATCH)

```id="ep6"
PATCH /api/directors/1/
```

📌 Body:

```json id="json3"
{
  "nationality": "UK"
}
```

📸 Evidencia:
![PATCH Director](./docs/patch.png)

---

##  6. Eliminar Director (DELETE)

```id="ep7"
DELETE /api/directors/1/
```

📸 Evidencia:
![DELETE Director](./docs/delete.png)
---

## yojhan huancca 
## 1. Crear Películas (POST)

`POST /api/movies/`

## 2. Listar Películas (GET)

`GET /api/movies/`

## 3. Ver Película por ID (GET)

`GET /api/movies/{id}/`

## 4. Actualizar Película (PUT)

`PUT /api/movies/{id}/`

## 5. Eliminar Película (DELETE)

`DELETE /api/movies/{id}/`



