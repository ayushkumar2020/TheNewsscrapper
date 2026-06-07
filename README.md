# 📰 NewsScrapper

NewsScrapper is a full-stack web application that automatically scrapes news headlines from multiple news sources using Puppeteer and stores them in MongoDB. Users can view the latest news, create notes based on articles, edit existing notes, and download them for future reference.

---

## 🚀 Features

- Automated news scraping using Puppeteer
- Collects headlines from multiple news websites
- Stores scraped news in MongoDB
- Create, edit, and delete notes
- Download notes for offline use
- Responsive user interface
- RESTful API architecture

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Web Scraping
- Puppeteer

### Tools
- Git
- GitHub
- VS Code

---

## 📂 Project Structure

```bash
NewsScrapper/
│
├── Newsscrapper/          # React Frontend
│   ├── public/
│   ├── src/
│   ├── package.json
│
├── controller/
├── models/
├── routes/
├── Server.js
├── .env
├── package.json
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/ayushkumar2020/TheNewsscrapper.git
```

### Install Backend Dependencies

```bash
npm install
```

### Install Frontend Dependencies

```bash
cd Newsscrapper
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### Run Backend Server

```bash
npm start
```

### Run Frontend

```bash
cd Newsscrapper
npm start
```

---

## 🔄 Application Workflow

1. News headlines are scraped from online news websites using Puppeteer.
2. Scraped data is processed and stored in MongoDB.
3. Users can browse the latest news.
4. Users can create notes from important articles.
5. Notes can be edited, deleted, or downloaded.

---

## 📌 Key Functionalities

### News Scraping
- Automated headline extraction
- Dynamic content handling with Puppeteer
- Database storage for retrieved news

### Notes Management
- Create notes
- Edit notes
- Delete notes
- Download notes

### Database Management
- Store scraped articles
- Store user-generated notes

---

## 🔮 Future Improvements

- AI-powered news summarization
- News categorization
- Sentiment analysis
- User authentication
- Bookmark articles
- PDF export functionality
- Real-time news updates

---

## 👨‍💻 Author

**Ayush Kumar**

- Computer Science Engineering
- Full Stack Developer
- Machine Learning Enthusiast

GitHub: https://github.com/ayushkumar2020

---

## 📄 License

This project is licensed under the MIT License.
