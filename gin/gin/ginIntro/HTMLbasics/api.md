# Gin Web Server API - cURL Commands

## 1️⃣ GET - Hello World

```sh
curl -X GET http://localhost:8080/hello
```

## 2️⃣ GET - Greet Page

```sh
curl -X GET http://localhost:8080/greet
```

## 3️⃣ GET - Greet by Name

```sh
curl -X GET http://localhost:8080/greet/DuyNghia
```

## 4️⃣ GET - Many Data

```sh
curl -X GET http://localhost:8080/many
```

## 5️⃣ GET - Form Page

```sh
curl -X GET http://localhost:8080/form
```

## 6️⃣ POST - Submit Form

```sh
curl -X POST http://localhost:8080/form \
     -H "Content-Type: application/x-www-form-urlencoded" \
     -d "name=DuyNghia&food=Pizza"
```
