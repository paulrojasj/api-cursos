# api-cursos

API REST hecha en Python para la gestión de cursos. Permite buscar, crear, actualizar y eliminar cursos de una base de datos de manera sencilla.

Características
Buscar cursos por nombre u otros criterios
Crear, actualizar y eliminar cursos
Arquitectura sencilla y fácil de entender
100% Python
Requisitos
Python 3.7 o superior
Dependencias (recomendado usar un entorno virtual)
Instalación
Clona el repositorio:

bash
git clone https://github.com/paulrojasj/api-cursos.git
cd api-cursos
Instala las dependencias:

bash
pip install -r requirements.txt
Uso
Ejecuta la API:

bash
python main.py
O el archivo principal correspondiente.

Endpoints principales
GET /cursos — Lista todos los cursos
GET /cursos/<id> — Obtiene detalles de un curso por ID
POST /cursos — Crea un nuevo curso
PUT /cursos/<id> — Actualiza un curso existente
DELETE /cursos/<id> — Elimina un curso
Estructura del proyecto
Code
api-cursos/
├── main.py
├── BuscarCurso.py
├── models.py
├── requirements.txt
└── README.md
Contribuciones
¡Las contribuciones son bienvenidas! Por favor, abre un issue o haz un pull request si deseas mejorar la API.

Licencia
Este proyecto está bajo la licencia MIT.

