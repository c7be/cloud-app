# Cloud Task Manager - Książka Azure w Praktyce by Tomasz Muskalski, 99682
 
Projekt natywnej aplikacji chmurowej realizowany w architekturze 3-warstwowej.
 
## Deklaracja Architektury (Mapowanie Azure)
Ten projekt został zaplanowany z myślą o usługach PaaS (Platform as a Service) w chmurze Azure.
 
| Warstwa | Komponent Lokalny | Usługa Azure |
| :--- | :--- | :--- |
| **Presentation** | React 19 (Vite) | Azure Static Web Apps |
| **Application** | API (.NET 9 / Node 24) | Azure App Service |
| **Data** | SQL Server (Dev) | Azure SQL Database (Serverless) |
 
## 🏗 Status Projektu i Dokumentacja
* [x] **Artefakt 1:** Zaplanowano strukturę folderów i diagram C4 (Diagram C4).
* [x] **Artefakt 2:** Konfiguracja środowiska Docker (Docker compose).
* [x] **Artefakt 3:** Działająca warstwa prezentacji (React + Vite w Dockerze).
* [x] **Artefakt 4:** Działający backend.
Podsumowanie etapu: 
czwarty etap zostal osiagniety.

> **Informacja:** Ten plik będzie ewoluował. W kolejnych etapach dodamy tutaj sekcje 'Quick Start', opis zmiennych środowiskowych oraz instrukcję wdrożenia (CI/CD).
