# Spring Rest Music Track API

Spring Boot REST API for managing music tracks.

Created during **Capgemini training on 20 March**.

## Endpoints

Base URL: `/music`

| Method | Endpoint                           | Purpose         |
| ------ | ---------------------------------- | --------------- |
| POST   | /music/tracks                      | Create track    |
| GET    | /music/tracks                      | List tracks     |
| GET    | /music/tracks/{id}                 | Get by ID       |
| GET    | /music/tracks/search?title={title} | Search by title |

## Run

```bash
./mvnw spring-boot:run
```

## Postman Screenshots

### 1. Create Track

![Create Track](PostmanScreenshots/image1.png)

### 2. Get All Tracks

![Get All Tracks](PostmanScreenshots/image2.png)

### 3. Get Track By ID

![Get Track By ID](PostmanScreenshots/image3.png)

### 4. Search Track By Title

![Search Track By Title](PostmanScreenshots/image4.png)

### 5. Additional Response

![Additional Response](PostmanScreenshots/image5.png)
