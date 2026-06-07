# 📰 NeuralScraper

NeuralScraper is a full-stack web application that automatically scrapes news headlines from multiple news sources, stores them in a MongoDB database, and allows users to create, edit, organize, and download notes based on the collected news.

## 🚀 Features

- Automated news scraping using Puppeteer
- Fetches headlines from multiple news websites
- Stores scraped news data in MongoDB
- Create and manage personal notes
- Edit existing notes
- Delete notes when no longer needed
- Download notes for offline use
- Responsive and user-friendly interface
- REST API architecture

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Web Scraping
- Puppeteer

### Version Control
- Git
- GitHub

---

## 📂 Project Structure

```bash
NeuralScraper/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.js
│
├── controller/
├── models/
├── routes/
├── Server.js
├── package.json
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/ayushkumar2020/TheNewsscrapper.git
```

### 2. Navigate to the project directory

```bash
cd TheNewsscrapper
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the root directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### 5. Start the backend server

```bash
npm start
```

### 6. Start the frontend

```bash
cd Newsscrapper
npm start
```

---

## 🔄 Workflow

1. User requests latest news.
2. Puppeteer scrapes headlines from configured news sources.
3. Scraped data is stored in MongoDB.
4. News is displayed on the frontend.
5. Users can:
   - Create notes
   - Edit notes
   - Delete notes
   - Download notes

---

## 📸 Key Modules

### News Scraping Module
- Extracts headlines from news websites.
- Handles dynamic content rendering.
- Stores results in the database.

### Notes Management Module
- Create notes from news articles.
- Update and delete notes.
- Download notes for future reference.

### Database Module
- Stores news articles.
- Stores user-generated notes.

---

## 🔮 Future Enhancements

- AI-powered news summarization
- Sentiment analysis of news articles
- User authentication and authorization
- Category-wise news filtering
- Bookmark favorite articles
- Export notes as PDF
- Real-time news updates

---

## 👨‍💻 Author

**Ayush Kumar**

- Computer Science Engineer
- Frontend Developer
- Machine Learning Enthusiast

GitHub: https://github.com/ayushkumar2020

---

## 📜 License

This project is licensed under the MIT License.

Feel free to fork, modify, and contribute to this project.
