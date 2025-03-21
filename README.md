# Lyric Match 🎵

Lyric Match is a web application that challenges users to guess the title of an English song based on a short AI-generated snippet of its lyrics. The application leverages OpenAI's GPT-3.5 model through the EdenAI API to generate evocative lyrics from popular songs.

---

## 🚀 Features
- **Lyric Generation:** Generate short, recognizable lyric snippets using OpenAI's GPT-3.5 model.
- **User Guessing Interface:** Intuitive UI with input fields and buttons for generating lyrics and submitting guesses.
- **Accuracy Check:** Verifies the user's guess and displays whether it is correct or incorrect.
- **Song Title Reveal:** If the guess is wrong, shows the correct song title.

---

## 🛠️ Technologies Used
- **Frontend:** React JS
- **Backend:** Flask (Python) with Flask-CORS
- **Language Model:** OpenAI GPT-3.5 via EdenAI API
- **Environment Management:** Python Dotenv
- **Package Management:** pip
- **Hosting:** Localhost (during development)

---

## 📂 Project Structure
```
LyricMatch/
├── frontend/
│   ├── public/
│   │   └── index.html
│   └── src/
│       └── App.js
├── backend/
│   ├── app.py
│   ├── utils.py
│   └── lyrics.py
├── .env
└── requirements.txt
```

---

## 📝 Requirements
Make sure you have the following installed:
- Python 3.x
- pip (Python package installer)
- Node.js (for frontend development)

---

## 🛑 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/LyricMatch.git
cd LyricMatch
```

### 2. Setting Up Backend

#### Install Dependencies
```bash
pip install -r requirements.txt
```

#### Configure Environment Variables
Create a `.env` file in the root directory and add your EdenAI API key:
```
EDENAI_API_KEY=your_edenai_api_key
```

#### Run the Backend Server
```bash
python backend/app.py
```
The server will be running at: `http://localhost:5000`

---

### 3. Setting Up Frontend

#### Navigate to Frontend Directory
```bash
cd frontend
```

#### Open the HTML File
Open `public/index.html` in your preferred browser:
```
firefox public/index.html
```
*Replace `firefox` with your browser of choice.*

---

## 💻 Usage

1. Click the **"Generate Lyric Snippet"** button to fetch a random lyric snippet.
2. Enter your guess in the input field.
3. Click **"Check Answer"** to see if your guess is correct.
4. The application will display whether the guess was correct or not, and if not, show the correct title.

---

## 🔥 Example Songs List
- Shape of You
- Blinding Lights
- Bohemian Rhapsody
- Rolling in the Deep
- Bad Guy
- Smells Like Teen Spirit
- Hotel California
- Imagine
- Stairway to Heaven
- Sweet Child O' Mine
- Billie Jean
- Hallelujah
- Shake It Off
- Wonderwall
- Lose Yourself
- Someone Like You
- Despacito
- Thinking Out Loud
- Uptown Funk
- Hello

---

## 🐛 Troubleshooting
- Make sure the backend server is running before accessing the frontend.
- Check the API key and endpoint configuration in the `.env` file.
- Verify that the required packages are installed by running:
  ```
  pip install -r requirements.txt
  ```
- If the lyric snippet generation fails, inspect the backend console for error logs.

---

## 🤝 Contributing
Feel free to submit pull requests and suggest new features. Contributions are always welcome!

---

## 📜 License
This project is licensed under the MIT License.

---

## ✨ Acknowledgements
Special thanks to:
- [OpenAI](https://openai.com) for the GPT-3.5 model.
- [EdenAI](https://www.edenai.co/) for API integration.
