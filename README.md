# Back-End Development: Pictures Microservice

A Python Flask-based microservice designed to manage and serve picture metadata via a RESTful API. This service is containerized using Docker and configured for cloud deployment on **IBM Code Engine**.

## Features

* **RESTful Endpoints**: Retrieve all pictures, query specific pictures by ID, count total entries, and handle creation/updates/deletions.
* **Health Check**: Built-in `/health` endpoint to monitor application status.
* **Containerized**: Packaged with Docker for seamless portability and deployment.
* **Cloud Native**: Deployed and scaled using IBM Code Engine.

---

## Tech Stack

* **Language**: Python 3.9+
* **Framework**: Flask
* **Containerization**: Docker
* **Cloud Platform**: IBM Code Engine / IBM Container Registry
* **Testing**: Pytest

---

## API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/health` | Returns the health status of the application |
| `GET` | `/count` | Returns the total number of picture records |
| `GET` | `/picture` | Retrieves the full list of pictures |
| `GET` | `/picture/<id>` | Retrieves a specific picture by its unique ID |
| `POST` | `/picture` | Creates a new picture entry |
| `PUT` | `/picture/<id>` | Updates an existing picture entry |
| `DELETE` | `/picture/<id>` | Deletes a picture entry by ID |

---

## Local Development & Testing

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/JanatByakagabaBirungi/Back-End-Development-Pictures.git](https://github.com/JanatByakagabaBirungi/Back-End-Development-Pictures.git)
   cd Back-End-Development-Pictures
