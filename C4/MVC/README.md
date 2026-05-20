sena-management/
│
├── models/
│   ├── entities/
│   │   ├── Ambiente.java
│   │   ├── Horario.java
│   │   ├── Instructor.java
│   │   └── Ficha.java
│   │
│   ├── dtos/
│   │   ├── AmbienteDTO.java
│   │   ├── HorarioDTO.java
│   │   ├── InstructorDTO.java
│   │   └── FichaDTO.java
│   │
│   ├── repositories/
│   │   ├── IAmbienteRepository.java
│   │   ├── IHorarioRepository.java
│   │   ├── IInstructorRepository.java
│   │   └── IFichaRepository.java
│   │
│   └── services/
│       ├── IAmbienteService.java
│       ├── AmbienteService.java
│       ├── HorarioService.java
│       └── FichaService.java
│
├── views/
│   ├── ambientes/
│   │   ├── listar.html
│   │   ├── crear.html
│   │   └── editar.html
│   │
│   ├── horarios/
│   ├── instructores/
│   └── fichas/
│
├── controllers/
│   ├── AmbienteController.java
│   ├── HorarioController.java
│   ├── InstructorController.java
│   └── FichaController.java
│
├── utils/
│   ├── ValidationUtils.java
│   └── DateUtils.java
│
└── main/
    └── Application.java