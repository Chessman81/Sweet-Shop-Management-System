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
Installation & Setup
🔧 Prerequisites



Node.js (v18+)

npm or yarn

PostgreSQL

Git

⚙️ Backend Setup
# Clone the repository
git clone https://github.com/<your-username>/Sweet-Shop-Management-System.git
cd sweet-shop-management-system/backend

# Install dependencies
npm install

# Create .env file
DATABASE_URL=postgresql://user:password@localhost:5432/sweetshop  
JWT_SECRET=your_jwt_secret  
PORT=5000

# Run Prisma migrations
npx prisma migrate dev --name init

# Start the backend
npm run dev


👉 Backend runs at http://localhost:5000

💅 Frontend Setup
cd ../frontend
npm install
npm run dev


👉 Frontend runs at http://localhost:4000

🧩 Running Tests
cd backend
npm test

📦 Deliverables

✅ Public Git Repository
✅ Comprehensive README (this file)
✅ Jest Test Report
✅ Screenshots of UI


🖼️ Screenshots

Include screenshots of:

Login & Register Page

Dashboard

Admin CRUD Panel

Purchase Confirmation Popup

☁️ Optional Deployment

Frontend: Vercel / Netlify

Backend: Render / Railway / Heroku

Database: Supabase / Neon.tech



🚀 Future Enhancements

Sweet categories & filters

Order history per user

Payment gateway (Stripe)

Dark mode

Admin analytics dashboard



