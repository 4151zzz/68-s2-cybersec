# Cyber Security

## 6702041510181

- Piyapong Yajanto
- email : s6702041510181@email.kmutnb.ac.th 


## Environment
```sh
cp env.example .env
```

## Running service

### Database

```sh
docker compose -f db.yaml up -d
docker compose -f admin.yaml up -d
docker compose -f app.yaml up -d