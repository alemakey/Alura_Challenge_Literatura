# literatura-backend-one-g9

Challenge **LiterAlura** (Oracle Next Education + Alura) — Backend en Java con Spring Boot.  
Permite buscar libros/autores (consumiendo API), guardar información en base de datos y consultar historial desde un menú en consola.

## 🧩 Funcionalidades
- Buscar libros por título
- Listar libros registrados
- Listar autores registrados
- Listar autores vivos en un año determinado
- Listar libros por idioma
- (Opcional) Historial de búsquedas

## 🛠️ Tecnologías
- Java 17+
- Spring Boot
- Spring Data JPA (Hibernate)
- Maven
- Base de datos: (PostgreSQL / H2 / MySQL) *(ajusta según tu proyecto)*
- Jackson (JSON)

## 📦 Requisitos
- Java 17 o superior
- Maven 3.8+
- (Si aplica) PostgreSQL instalado y corriendo

## ▶️ Cómo ejecutar
1. Clona el repositorio:
   ```bash
   git clone https://github.com/alemakey/literatura-backend-one-g9.git
   cd literatura-backend-one-g9


Configura application.properties (si aplica DB):

URL, usuario y contraseña

Ejecuta:

mvn spring-boot:run

⚙️ Configuración de base de datos (ejemplo PostgreSQL)

En src/main/resources/application.properties:

spring.datasource.url=jdbc:postgresql://localhost:5432/literatura
spring.datasource.username=postgres
spring.datasource.password=TU_PASSWORD
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

📁 Estructura sugerida

model → Entidades JPA (Libro, Autor)

repository → Repositorios Spring Data

service → Lógica de negocio + consumo de API

dto → DTOs para mapear respuestas JSON

main → Menú/runner de consola

👤 Autor

Víctor Martínez Reyna
GitHub: alemakey

✅ Estado

Proyecto finalizado para el Challenge Backend ONE G9.


Cuando lo guardes, haz commit + push:

```bash
git add README.md
git commit -m "Docs: actualizar README y nombre del proyecto"
git push
