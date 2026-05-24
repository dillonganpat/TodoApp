# To-Do List Application

A simple yet elegant task management application built with vanilla JavaScript, HTML5, and CSS3. Manage your daily tasks efficiently with persistent data storage using browser LocalStorage.

## 🎯 Features

- ✅ **Add Tasks** - Create new tasks with a single click or press Enter
- ✅ **Mark Complete** - Toggle task completion status with visual feedback
- ✅ **Delete Tasks** - Remove tasks from your list instantly
- ✅ **Persistent Storage** - Tasks are automatically saved to LocalStorage and restored on page reload
- ✅ **Responsive Design** - Fully optimized for mobile and desktop devices
- ✅ **Clean UI** - Modern gradient design with smooth animations and hover effects

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Storage:** Browser LocalStorage API
- **Styling:** CSS Flexbox, CSS Gradients
- **Deployment:** Static HTML/CSS/JS

## 📋 Project Structure

```
├── index.html       # Main HTML structure
├── script.js        # JavaScript functionality
├── style.css        # Styling and responsive design
├── images/
│   ├── icon.png     # App header icon
│   ├── checked.png  # Checked checkbox icon
│   └── unchecked.png # Unchecked checkbox icon
└── README.md        # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No dependencies or build tools required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
   cd todo-list-app
   ```

2. **Open in browser**
   - Double-click `index.html` to open in your default browser
   - Or use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server installed)
     http-server
     ```

3. **Access the app**
   - Open `http://localhost:8000` in your browser

## 💡 How to Use

1. **Add a Task**
   - Type your task in the input field
   - Click the "Add" button or press `Enter`

2. **Mark as Complete**
   - Click on any task to toggle completion status
   - Completed tasks show a checkmark and strikethrough text

3. **Delete a Task**
   - Click the "×" button on the right side of any task to delete it

4. **Persistent Storage**
   - All tasks are automatically saved to your browser's LocalStorage
   - Tasks will remain even after closing and reopening the browser

## 🎨 Design Features

- **Gradient Background:** Purple and blue gradient for a modern look
- **Responsive Layout:** Mobile-first design with Flexbox
- **Custom Icons:** Unchecked/checked checkbox images for visual feedback
- **Smooth Interactions:** Hover effects and transitions for better UX
- **Accessible Design:** Semantic HTML and proper spacing

## 🔧 Key JavaScript Concepts Demonstrated

- **DOM Manipulation:** Creating, appending, and removing HTML elements dynamically
- **Event Delegation:** Efficient event handling for dynamically created elements
- **LocalStorage API:** Saving and retrieving data from browser storage
- **ES6 JavaScript:** Arrow functions, template literals, and modern syntax
- **Event Listeners:** Keyboard (Enter key) and mouse click event handling

## 📱 Responsive Breakpoints

- **Desktop:** Full layout with 540px max-width container
- **Tablet:** Adjusted padding and font sizes
- **Mobile:** Optimized for screens under 480px width

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

Dillon Ganpat (https://github.com/dillonganpat)

## 🙏 Acknowledgments

- Icons designed with attention to user experience
- Gradient color scheme inspired by modern web design trends
- Built as a learning project for JavaScript fundamentals
