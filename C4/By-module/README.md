sena-management/
│
├── modules/
│   │
│   ├── ambiente/
│   │   ├── controller/
│   │   │   └── AmbienteController.java
│   │   │
│   │   ├── service/
│   │   │   ├── IAmbienteService.java
│   │   │   └── AmbienteService.java
│   │   │
│   │   ├── repository/
│   │   │   ├── IAmbienteRepository.java
│   │   │   └── AmbienteRepository.java
│   │   │
│   │   ├── entity/
│   │   │   └── Ambiente.java
│   │   │
│   │   ├── dto/
│   │   │   ├── AmbienteDTO.java
│   │   │   └── IAmbienteDTO.java
│   │   │
│   │   └── utils/
│   │       └── AmbienteValidator.java
│   │
│   ├── horario/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── entity/
│   │   ├── dto/
│   │   └── utils/
│   │
│   ├── instructor/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── entity/
│   │   ├── dto/
│   │   └── utils/
│   │
│   └── ficha/
│       ├── controller/
│       ├── service/
│       ├── repository/
│       ├── entity/
│       ├── dto/
│       └── utils/
│
├── shared/
│   ├── exceptions/
│   ├── security/
│   ├── database/
│   └── utils/
│
└── main/
    └── Application.java