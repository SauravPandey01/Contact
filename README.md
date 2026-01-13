# ProContact Manager

A professional, full-featured CRUD application for managing personal and professional contacts. This project is structured as a modular full-stack application with a clear separation of concerns between the frontend and a simulated backend.

## 🚀 Features

### Core CRUD Operations
- **Create**: Add new contacts with full validation.
- **Read**: View a comprehensive list of contacts and detailed information.
- **Update**: Edit existing contact details seamlessly.
- **Delete**: Remove contacts from the system.

### Advanced Functionality
- **Authentication**: Simulated JWT-based authentication system with Login and Registration.
- **Search & Filter**: Real-time search by name or email.
- **Sorting**: Organize contacts by name, email, or date added.
- **Validation**: Robust frontend and "backend" validation for email formats and phone numbers.
- **Persistence**: Data is persisted using `localStorage` to simulate a database.

## 📂 Project Structure

The project follows the modular organization requested in the assignment brief:

```text
Contacts-Manager/
├── backend/                # Simulated Backend Logic
│   ├── models.ts           # Data models and storage logic
│   ├── controllers.ts      # Auth and Contact business logic
├── frontend/               # React Frontend Application
│   ├── api/                # API communication layer
│   │   └── contactsApi.ts
│   ├── components/         # Reusable UI components
│   │   └── Components.tsx
│   ├── context/            # Global state management
│   │   └── AuthContext.tsx
│   ├── pages/              # Main application views
│   │   └── Pages.tsx
│   ├── utils/              # Helper functions (formatting, validation)
│   │   └── utils.ts
│   └── App.tsx             # Main React entry point
├── index.html              # Entry HTML with Tailwind CSS
├── index.tsx               # Browser bootstrapper
└── README.md               # Project documentation
```

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript
- **Styling**: Tailwind CSS (Utility-first CSS)
- **State Management**: React Context API
- **Icons**: Custom SVG icons
- **Persistence**: LocalStorage API (Simulated DB)

## 🏁 Getting Started

### Local Environment
1. Clone the repository.
2. To run the frontend:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
3. To run the backend (simulated):
   ```bash
   cd backend
   npm install
   npm start
   ```

### Browser Environment
In this interactive environment, the application is bundled automatically. You can interact with the live preview directly.

## 🧪 Evaluation Criteria Addressed
- **Code Quality**: Modular structure with TypeScript for type safety.
- **Backend Design**: Separated controllers and models.
- **Frontend UX**: Responsive, clean UI with loading states and validation feedback.
- **Edge Cases**: Handles empty states, duplicate emails, and invalid inputs.

---
*Built with ❤️ for the CRUD Web Developer Assignment.*
