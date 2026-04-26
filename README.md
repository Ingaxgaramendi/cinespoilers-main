<img width="1896" height="1075" alt="image" src="https://github.com/user-attachments/assets/23106515-fe54-4c1f-b806-66828862eb34" /># 🎬 CINESPOILERS API - DIRECTORES

API REST desarrollada con Django Rest Framework para la gestión de **Directores**.

---

## 👥 Integrantes

* Anderson Jair Rivera Pucuhuayla
* Yojhan Leodan Hunaca Yucra 

---

## 🚀 Tecnologías utilizadas<img width="1148" height="764" alt="image" src="https://github.com/user-attachments/assets/ce80c57c-102c-4a71-92dc-d63c238aca88" />


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

# Yojhan Huancca Yucra

## Evidencias
## movies
### 1. Listar Películas (GET)
**Ruta:** `GET /api/movies/`  
<img width="1411" height="677" alt="image" src="https://github.com/user-attachments/assets/f230cbff-cdaf-46f6-81ea-2e602caa8b60" />

### 2. Crear Películas (POST)
**Ruta:** `POST /api/movies/`  
<img width="1718" height="853" alt="image" src="https://github.com/user-attachments/assets/c5fc2d86-bc32-4271-b90f-7c7c3a645d74" />

### 3. Actualizar Películas (PUT)
**Ruta:** `PUT /api/movies/{id}/`  
<img width="1633" height="773" alt="image" src="https://github.com/user-attachments/assets/2d0dadb7-c3ab-4cab-92aa-a29e6136d728" />

### 4. Actualización parcial (PATCH)
**Ruta:** `PATCH /api/movies/{id}/`  
<img width="1413" height="788" alt="image" src="https://github.com/user-attachments/assets/e89e68a8-d06f-4257-bc59-8702bb706186" />

### 5. Eliminar Películas (DELETE)
**Ruta:** `DELETE /api/movies/{id}/`  
<img width="1421" height="695" alt="image" src="https://github.com/user-attachments/assets/80f78ed7-e6a1-4c05-babf-a13ff75d15a4" />

### 6. Data Base
<img width="1877" height="647" alt="image" src="https://github.com/user-attachments/assets/684db0eb-8fe7-49df-810d-1d780a01c146" />

## Genres
**Ruta:** `GET /api/genres/`
<img width="1909" height="1020" alt="image" src="https://github.com/user-attachments/assets/65a74e02-f4bd-4f7f-8c4b-e47abd814dbb" />

**Ruta:** `POST /api/genres/`
<img width="1904" height="1078" alt="image" src="https://github.com/user-attachments/assets/5f8f9d8e-856e-4315-95be-00edaf8a3133" />

**Ruta:** `GET /api/genres/1/`
<img width="1919" height="1057" alt="image" src="https://github.com/user-attachments/assets/49f5bb71-bf6b-4489-927d-70a722e44139" />


**Ruta:** `PUT /api/genres/2/`
<img width="1883" height="1079" alt="image" src="https://github.com/user-attachments/assets/db313f49-8fff-4174-a689-35cf35241369" />

**Ruta:** `PATCH /api/genres/1/`
<img width="1912" height="1079" alt="image" src="https://github.com/user-attachments/assets/4064d1d3-a193-4b70-b3ab-3aa6d4cd7b8c" />

**Ruta:** `DELETE /api/genres/3/`
<img width="1898" height="1070" alt="image" src="https://github.com/user-attachments/assets/ed012a14-519b-4623-a8db-829bc7e56a50" />

**Ruta:** `GET /api/genres/3/`
<img width="1420" height="1051" alt="image" src="https://github.com/user-attachments/assets/d49ce635-c74a-4c16-aca8-b8f00c110c4c" />

### 6. Data Base
<img width="1896" height="1075" alt="image" src="https://github.com/user-attachments/assets/15494900-2ec2-4f5d-a369-bff6a8ac2fc4" />









