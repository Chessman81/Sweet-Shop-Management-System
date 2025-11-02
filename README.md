# 🍬 Sweet Shop Management System  
### A Full-Stack Test-Driven Development (TDD) Project with AI Integration  

---

## 🎯 Objective  
The **Sweet Shop Management System** demonstrates full-stack software development skills through a **Test-Driven Development (TDD)** approach.  
It includes authentication, inventory management, and AI-assisted workflows.  
This project integrates backend APIs, frontend UI, and database operations with modern best practices and transparent AI usage.  

---

## ⚙️ Core Features  

### 🧠 Backend API (RESTful)  
A robust backend serving as the “brain” of the Sweet Shop System.  

**Technologies Used:**  
- Node.js (Express) + TypeScript  
- Prisma ORM  
- PostgreSQL  
- JWT Authentication  
- Jest (for testing)  

**Functionalities:**  
#### 🧍‍♀️ User Authentication  
- `POST /api/auth/register` → Register new users  
- `POST /api/auth/login` → Login and receive JWT  

#### 🍭 Sweets Management (Protected)  
- `POST /api/sweets` → Add new sweet  
- `GET /api/sweets` → View all sweets  
- `GET /api/sweets/search` → Search sweets by name, category, or price  
- `PUT /api/sweets/:id` → Update sweet details  
- `DELETE /api/sweets/:id` → Delete a sweet (Admin only)  

#### 📦 Inventory Management (Protected)  
- `POST /api/sweets/:id/purchase` → Purchase a sweet (reduce stock)  
- `POST /api/sweets/:id/restock` → Restock a sweet (Admin only)  

Each sweet includes:  
✅ **Unique ID** | ✅ **Name** | ✅ **Category** | ✅ **Price** | ✅ **Quantity**

---

### 💻 Frontend Application  
A single-page React app that interacts seamlessly with the backend API.  

**Technologies Used:**  
- React.js (Vite)  
- Tailwind CSS  
- Axios  
- React Router  

**Functionalities:**  
- User registration and login  
- Dashboard displaying sweets  
- Search and filter sweets  
- Purchase button (disabled when out of stock)  
- Admin CRUD operations  

**Design Focus:**  
Responsive, visually appealing, and user-friendly.

---

## 🧪 Process & Technical Guidelines  

### 1️⃣ Test-Driven Development (TDD)  
Followed the **Red → Green → Refactor** cycle:  
- Write failing tests  
- Implement minimal code to pass  
- Refactor for maintainability  

✅ Achieved high test coverage with meaningful test cases.

### 2️⃣ Clean Coding Practices  
- Followed **SOLID** principles  
- Modular, well-documented code  
- Meaningful variable and function names  
- Inline documentation  

### 3️⃣ Git & Version Control  
- Used Git for version tracking  
- Clear, descriptive commits  
- AI co-authorship where relevant  

---

## 🤖 My AI Usage  

AI was used responsibly to improve **efficiency** without replacing understanding.  

**AI Tools Used:**  
- ChatGPT (OpenAI GPT-5)  
- GitHub Copilot  

**How AI Helped:**  
- Brainstorming API routes and structures  
- Generating boilerplate & validation logic  
- Writing unit tests  
- Debugging & optimization  
- Creating documentation  

**Commit Example:**  
```bash
git commit -m "feat: Implement user registration endpoint  
Co-authored-by: GPT-5 <AI@users.noreply.github.com>"
