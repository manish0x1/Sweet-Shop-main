

```markdown
# 🍬 Sweet Shop Management System - TDD Kata

## 🎯 Objective

The goal of this kata is to design, build, and test a full-stack Sweet Shop Management System using **Test-Driven Development (TDD)**. This project challenges your skills in backend API development, frontend implementation, database integration, testing, and modern workflows—including AI-assisted development.

---

## 🧠 Core Features

### 1. Backend API (RESTful)

- **Tech Stack**: Python with FastAPI (or choose Node.js, Java, Ruby as preferred)
- **Database**: PostgreSQL (or MongoDB, SQLite)
- **Authentication**:
  - JWT-based token authentication
  - User registration and login
- **Endpoints**:
  - `POST /api/auth/register` – Register a new user
  - `POST /api/auth/login` – Login and receive token
  - `POST /api/sweets` – Add a sweet *(Protected)*
  - `GET /api/sweets` – List all sweets *(Protected)*
  - `GET /api/sweets/search` – Search sweets by name/category/price *(Protected)*
  - `PUT /api/sweets/:id` – Update sweet *(Protected)*
  - `DELETE /api/sweets/:id` – Delete sweet *(Admin only)*
  - `POST /api/sweets/:id/purchase` – Purchase sweet *(Protected)*
  - `POST /api/sweets/:id/restock` – Restock sweet *(Admin only)*

Each sweet includes: `id`, `name`, `category`, `price`, `quantity`.

---

### 2. Frontend Application

- **Tech Stack**: React (or Vue, Angular, Svelte)
- **Features**:
  - User registration/login forms
  - Dashboard to view sweets
  - Search and filter sweets
  - Purchase button (disabled if quantity = 0)
  - Admin UI for CRUD operations

- **Design Goals**:
  - Responsive and visually appealing
  - Intuitive user experience

---

## 🧪 Process & Technical Guidelines

### ✅ Test-Driven Development (TDD)

- Follow **Red-Green-Refactor** cycle
- Write meaningful unit/integration tests
- Maintain high test coverage

### 🧼 Clean Code

- Follow **SOLID principles**
- Use clear naming, comments, and modular design

### 🔀 Git Workflow

- Use Git for version control
- Commit frequently with descriptive messages
- Include AI co-authorship when applicable

---

## 🤖 My AI Usage

### Tools Used

- **GitHub Copilot**
- **ChatGPT**
- **Gemini**

### How I Used Them

- Used Copilot to scaffold FastAPI routes and React components
- Asked ChatGPT to generate unit tests and validation logic
- Used Gemini to brainstorm API structure and database schema

### Reflection

AI tools significantly accelerated boilerplate generation and helped me focus on business logic and testing. They were especially useful for:
- Writing repetitive test cases
- Debugging API responses
- Generating UI components with consistent styling

I ensured all AI-generated code was reviewed and customized to meet project standards.

---

## 🚀 Getting Started

### Backend Setup

```bash
git clone <your-repo-url>
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

### Environment Variables

Create `.env` files for both backend and frontend with necessary secrets (e.g., JWT secret, DB credentials).

---

## 🧪 Test Report

Run backend tests:

```bash
pytest --cov
```

Run frontend tests:

```bash
npm test
```

Test coverage reports are included in the `/tests` folder.

---


---


👉 [GitHub Repository](https://github.com/manish0x1/Sweet-Shop-main)

---

## 🏁 Deliverables

- ✅ Public Git repository
- ✅ README with setup, screenshots, and AI usage
- ✅ Test report
- ✅ (Optional) Live deployment link

---



Happy coding! 🍭
```


