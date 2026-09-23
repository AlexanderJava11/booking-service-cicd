---

## 🚀 DevOps – CI/CD

Projektet använder en CI/CD-pipeline med:

- GitHub Actions för automatiska tester
- Docker för containerisering
- Docker Hub för lagring av Docker-image
- Railway för automatisk deployment

Vid push till `master` körs testerna automatiskt. Om testerna lyckas byggs en ny Docker-image och pushas till Docker Hub.