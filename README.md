# Challenge 1: Node.js + MongoDB CRUD Application on AKS

## Descripción
Este challenge consiste en desplegar una aplicación CRUD completa usando Node.js (Express) como backend, React como frontend, y MongoDB como base de datos en Azure Kubernetes Service (AKS).

## Arquitectura
- **Frontend**: React con Material-UI
- **Backend**: Node.js con Express y Mongoose
- **Base de datos**: Azure Cosmos DB (MongoDB API)
- **Contenedores**: Docker
- **Orquestación**: Kubernetes (AKS)
- **CI/CD**: GitHub Actions

## Estructura del Proyecto
```
node-mongo-aks/
├── backend/                 # API Node.js/Express
├── frontend/               # React App
├── infrastructure/         # Terraform para Azure
├── k8s/                   # Manifiestos Kubernetes
├── .github/workflows/     # GitHub Actions
└── scripts/               # Scripts de utilidad
```

## Objetivos del Challenge
1. Crear una API REST con Node.js/Express
2. Implementar frontend React con operaciones CRUD
3. Configurar Azure Cosmos DB con MongoDB API
4. Containerizar ambas aplicaciones
5. Desplegar en AKS usando Terraform
6. Implementar CI/CD con GitHub Actions

## Funcionalidades a Implementar
- Gestión de productos (Create, Read, Update, Delete)
- Autenticación JWT
- Validación de datos
- Paginación y filtros
- Manejo de errores
- Health checks

## Tecnologías Específicas
- Node.js 18+
- Express.js
- Mongoose ODM
- React 18
- Material-UI v5
- Azure Cosmos DB (MongoDB API)
- Docker
- Kubernetes
- Terraform