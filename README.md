# Job App
Aplicație web realizată folosind stack-ul Java (Spring Boot) pentru backend, React pentru frontend și PostgreSQL ca bază de date.
 
## Autor
Cristea Bianca-Ștefania
 
## Tehnologii folosite
- Java 21, Spring Boot, Spring Data JPA, Spring Security
- PostgreSQL (runtime)
- H2 (testare/profil alternativ)
- React
- JUnit 5 (testare de integrare)
- Spring Profiles (dev/test), logging
 
## Funcționalități cheie
- CRUD complet pentru toate entitățile
- Relații JPA: OneToOne, OneToMany, ManyToOne, ManyToMany
- Validări, tratarea excepțiilor
- Autentificare cu Spring Security (JDBC)
- Paginare și sortare
- Testare unitară și integrată
- Profiluri multiple pentru baze de date

## Structura
- `backend/` – Spring Boot
- `frontend/` – React

## Rulare rapidă
##### Backend
./mvnw spring-boot:run

#### Frontend
cd frontend

npm install

npm start
