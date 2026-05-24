# Background Color Changer 🎨

A simple React application that changes the background color of the page using colorful buttons. Built with React and Tailwind CSS.

## 🚀 Features

- Change background color instantly
- Smooth transition effect
- Responsive button layout
- Clean and minimal UI
- Built using React Hooks (`useState`)

---

## 🛠️ Technologies Used

- React
- Tailwind CSS
- JavaScript (ES6)

---


## 📂 Project Structure

```bash
src/
│── App.jsx
│── main.jsx
│── index.css
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/background-color-changer.git
```

### 2️⃣ Navigate to the project folder

```bash
cd background-color-changer
```

### 3️⃣ Install dependencies

```bash
npm install
```

### 4️⃣ Start the development server

```bash
npm run dev
```

---

## 💡 How It Works

- The app uses React's `useState` hook to store the current background color.
- Clicking a button updates the state.
- The background color changes dynamically using inline styles.

Example:

```jsx
const [color, setColor] = useState("orange");
```

```jsx
style={{ backgroundColor: color }}
```

---

## 🎯 Future Improvements

- Add dark/light mode
- Add custom color picker
- Add animations
- Save selected color in local storage

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is open source and available under the MIT License.

---

## 👨‍💻 Author

Made with ❤️ by Your Name
