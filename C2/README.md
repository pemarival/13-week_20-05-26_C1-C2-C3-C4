┌────────────────────────────┐
│          Usuarios          │
│----------------------------│
│ • Coordinador Académico    │
│ • Instructor               │
│ • Administrador            │
└─────────────┬──────────────┘
              │ HTTPS
              ▼

┌──────────────────────────────────────────┐
│             Frontend Web                 │
│------------------------------------------│
│ Aplicación Web de Gestión SENA           │
│                                          │
│ • Gestión de ambientes                   │
│ • Gestión de horarios                    │
│ • Gestión de fichas                      │
│ • Gestión de instructores                │
│ • Reportes y consultas                   │
└────────────────┬─────────────────────────┘
                 │ REST / HTTPS
                 ▼

┌──────────────────────────────────────────┐
│             Backend API                  │
│------------------------------------------│
│ Lógica de negocio                        │
│ Validaciones                             │
│ Autenticación                            │
│ Gestión académica                        │
│ Reglas de disponibilidad                 │
└───────────┬───────────────┬──────────────┘
            │               │
            │ SQL           │ Events / Async
            ▼               ▼

┌──────────────────┐   ┌──────────────────┐
│   PostgreSQL     │   │ Message Broker   │
│------------------│   │ Kafka/RabbitMQ   │
│ Datos académicos │   │ Eventos sistema  │
└──────────────────┘   └──────────────────┘


            │
            │ SMTP/API
            ▼

┌──────────────────┐
│ NotificationSvc  │
│------------------│
│ Correos/Alertas  │
└──────────────────┘