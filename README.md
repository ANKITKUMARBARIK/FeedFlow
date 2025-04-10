# FeedFlow 📨

A professional yet beginner-friendly feedback collection system built using **Node.js Core Modules** – no external frameworks involved.

---

## 🚀 Features

✅ Clean and simple UI for feedback submission  
✅ Handles POST requests using `http` module  
✅ Parses data using `url` module  
✅ Saves feedback into a local JSON file (`feedbacks.json`)  
✅ Uses only built-in Node.js modules: `http`, `fs`, `path`, `url`

---

## 🛠️ Tech Stack

- 🟢 Node.js
- 📄 HTML
- 📁 JSON
- 📦 Core Modules: `http`, `fs`, `path`, `url`

---

## 📂 Project Structure

```
feedflow/
├── index.html          # Frontend feedback form
├── index.js            # Backend server using Node.js
├── feedbacks.json      # Stores all submitted feedbacks
├── README.md           # Project documentation
```

---

## 🔧 How to Run

1. **Clone the repo**
```bash
git clone https://github.com/ANKITKUMARBARIK/FeedFlow.git
cd FeedFlow
```

2. **Start the server**
```bash
node index.js
```

3. **Open your browser**
```
http://localhost:8000/
```

---

## 📥 Sample Feedback Format

```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "message": "Great app!",
  "time": "2025-04-09T11:47:26.776955"
}
```

---

## 📌 Use Case

A great starter project to understand:

- How HTTP POST requests work
- How to handle form data in Node.js
- How to write and read files using `fs`

---

## 👨‍💻 Author

Created with ❤️ by **ankit Dev**  
👉 [Follow me for more projects!](https://github.com/ANKITKUMARBARIK)

---

## 📃 License

Licensed under the **GNU License**
