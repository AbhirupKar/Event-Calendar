

# 📅 Event Calendar

A modern, interactive event calendar built with **React** and **Material-UI**. This application allows users to manage their schedule by adding, editing, and deleting events, with support for recurring events and drag-and-drop functionality.

---

## 🚀 Features

- Monthly calendar view with navigation  
- Add, edit, and delete events  
- Support for recurring events (daily, weekly, monthly, custom)  
- Event color customization  
- Event categories  
- Local storage persistence  
- Responsive design  
- Drag-and-drop event rescheduling  

---

## 📦 Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)  
- [npm](https://www.npmjs.com/) (v6 or higher)

---

## 🛠 Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd event-calendar

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to:
   [http://localhost:5173](http://localhost:5173)

---

## 📖 Usage

### ➕ Adding Events

* Click on any day in the calendar to add a new event.
* Fill in the event form:

  * Title (required)
  * Description
  * Start and end date/time
  * Recurrence pattern (if needed)
  * Color
  * Category

### ✏️ Editing Events

* Click on an existing event to open the edit form.
* Modify the event details.
* Click **Save Changes** to update the event.

### 🗑️ Deleting Events

* Click on an event to open the edit form.
* Click the **Delete** button to remove the event.

### 🔁 Recurring Events

Select a recurrence pattern when adding or editing:

* **Daily** – Repeats every day
* **Weekly** – Repeats on selected weekdays
* **Monthly** – Repeats on the same day each month
* **Custom** – Define a custom recurrence rule

---

## 🧰 Technologies Used

* [React](https://reactjs.org/)
* [TypeScript](https://www.typescriptlang.org/)
* [Material-UI](https://mui.com/)
* [date-fns](https://date-fns.org/)
* [React Beautiful DnD](https://github.com/atlassian/react-beautiful-dnd)
* [UUID](https://www.npmjs.com/package/uuid)

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch:

   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Commit your changes:

   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. Push to your branch:

   ```bash
   git push origin feature/amazing-feature
   ```
5. Open a Pull Request

---

## ⚠️ Special Instructions

* Make sure your browser allows pop-ups for the local server.
* If you face issues with `localStorage`, try clearing your browser cache and cookies.

---

## 🏗️ Building for Production

To create a production build, run:

```bash
npm run build
```

This will generate a `dist` folder with the optimized build.

---

