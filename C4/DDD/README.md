# DDD + Clean Architecture (La más profesional)

sena-management/
│
├── src/
│   │
│   ├── domain/
│   │   │
│   │   ├── ambiente/
│   │   │   ├── entity/
│   │   │   │   └── Ambiente.java
│   │   │   │
│   │   │   ├── repository/
│   │   │   │   └── IAmbienteRepository.java
│   │   │   │
│   │   │   ├── service/
│   │   │   │   └── IAmbienteService.java
│   │   │   │
│   │   │   └── valueobjects/
│   │   │       └── Capacidad.java
│   │   │
│   │   ├── horario/
│   │   ├── instructor/
│   │   └── ficha/
│   │
│   ├── application/
│   │   │
│   │   ├── ambiente/
│   │   │   ├── dto/
│   │   │   │   ├── AmbienteDTO.java
│   │   │   │   └── IAmbienteDTO.java
│   │   │   │
│   │   │   ├── usecases/
│   │   │   │   ├── CrearAmbienteUseCase.java
│   │   │   │   ├── ActualizarAmbienteUseCase.java
│   │   │   │   └── ConsultarAmbienteUseCase.java
│   │   │   │
│   │   │   └── services/
│   │   │       └── AmbienteService.java
│   │   │
│   │   ├── horario/
│   │   ├── instructor/
│   │   └── ficha/
│   │
│   ├── infrastructure/
│   │   │
│   │   ├── persistence/
│   │   │   ├── repositories/
│   │   │   │   ├── AmbienteRepositoryImpl.java
│   │   │   │   ├── HorarioRepositoryImpl.java
│   │   │   │   └── InstructorRepositoryImpl.java
│   │   │   │
│   │   │   └── database/
│   │   │       └── PostgreSQLConnection.java
│   │   │
│   │   ├── web/
│   │   │   ├── controllers/
│   │   │   │   ├── AmbienteController.java
│   │   │   │   ├── HorarioController.java
│   │   │   │   └── InstructorController.java
│   │   │   │
│   │   │   └── middleware/
│   │   │
│   │   └── messaging/
│   │       └── KafkaProducer.java
│   │
│   ├── shared/
│   │   ├── utils/
│   │   ├── exceptions/
│   │   ├── constants/
│   │   └── validators/
│   │
│   └── main/
│       └── Application.java
│
└── docs/
    ├── c4/
    ├── uml/
    └── architecture/

# DDD 

ambiente/
│
├── domain/
│   ├── entity/
│   │   └── Ambiente.java
│   │
│   ├── repository/
│   │   └── IAmbienteRepository.java
│   │
│   └── service/
│       └── IAmbienteService.java
│
├── application/
│   ├── dto/
│   ├── usecases/
│   └── services/
│
├── infrastructure/
│   ├── repository/
│   ├── controller/
│   └── persistence/
│
└── shared/