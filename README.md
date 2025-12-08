## INSTAY v1.0.0

This is a test version of the Instay project, built with Go Gin and Nextjs

### Contributors
- Frontend: [Đặng Quân Bảo](https://github.com/baoo04)
- Backend: [Cao Tiến Hải](https://github.com/tienhai2808)

### Introduction
This is the entire source code of the project including Frontend, Backend and Deployment. The project uses technologies including AWS S3, RabbitMQ, Redis, PostgreSQL, SMTP, IMAP, JWT, Nginx, ... deployed on AWS EC2. The project is a hotel management system and provides services to customers during in-stay.

### Project structure
```
instay/
├── backend/
│   ├── cmd/
│   ├── configs/
│   ├── docs/
│   ├── internal/
│   ├── logs/
│   ├── pkg/
│   └── Dockerfile
├── frontend/
│   ├── public/
│   ├── src/
│   └── Dockerfile
└── docker-compose.yaml
```

### Installation & Running

1. **Clone the repository**
```bash
git clone https://github.com/InstaySystem/is-fullstack.git instay
cd instay
```

2. **Start the complete development environment**
```bash
docker-compose up -d
```

