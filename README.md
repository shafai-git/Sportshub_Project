# SportsHub — Online Sports Tournament Management System

A lightweight Java + Spring Boot starter for managing sports tournaments (players, teams, tournaments, scheduling, results, leaderboards).

Features (MVP)
- Player & Team registration
- Create tournaments (round-robin or knockout)
- Automatic match scheduling (round-robin implemented)
- Submit match results and compute leaderboard

Tech
- Java 17+, Spring Boot, Spring Data JPA
- PostgreSQL
- Maven
- Docker (docker-compose)

Quick start (development)
1. Install Java 17+, Maven, Docker.
2. Start Postgres:
   docker-compose up -d
3. Build and run:
   mvn clean package
   mvn spring-boot:run
4. API base: http://localhost:8080/api

What's included
- Basic domain model (Player, Team, Tournament, Match)
- Round-robin scheduler service
- Minimal controllers and repositories

Next steps
- Add authentication (Spring Security + JWT)
- Implement knockout scheduler
- Add UI (React or Thymeleaf)
- Add constraints (venues, times) and optimisation for scheduling

This repository is a skeleton for a minor project.
