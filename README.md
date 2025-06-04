# EbongLabs

A full-stack project with a **Ktor** backend and an **Angular** frontend, organized in a monorepo structure.

---

## Project Structure

```
EbongLabs/
│
├── backend/    # Ktor (Kotlin) backend API
├── frontend/   # Angular frontend application
├── .gitignore
├── README.md
└── ...
```

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (for frontend)
- [Angular CLI](https://angular.io/cli)
- [Java 17+](https://adoptopenjdk.net/) (for backend)
- [Gradle](https://gradle.org/) (optional, wrapper included in backend)

---

### Clone the Repository

```bash
git clone https://github.com/yourusername/EbongLabs.git
cd EbongLabs
```

---

## Frontend (Angular)

```bash
cd frontend
npm install
ng serve
```

- The app will run at `http://localhost:4200/` by default.

---

## Backend (Ktor)

```bash
cd backend
./gradlew run
```

- The API will be available at `http://localhost:8080/` by default.

---

## Development

- **Frontend code:** `frontend/`
- **Backend code:** `backend/`
- Use the root `.gitignore` to manage ignored files for both projects.

---

## Scripts

| Task                | Command                        |
|---------------------|-------------------------------|
| Start frontend      | `cd frontend && ng serve`      |
| Start backend       | `cd backend && ./gradlew run`  |
| Build frontend      | `cd frontend && ng build`      |
| Build backend       | `cd backend && ./gradlew build`|

---

## License

[MIT](LICENSE) (or specify your license here)

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## Contact

For questions or support, please contact [your-email@example.com](mailto:your-email@example.com).