<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Media Post Analysis</title>
</head>
<body>

    <h1>📊 Social Media Post Analysis</h1>

    <h2>📌 Overview</h2>
    <p>
        Social Media Post Analysis is a Python-based project that analyzes text data from posts 
        to extract meaningful insights such as keywords, hashtags, and confidence scores. 
        It helps in understanding content performance and improving social media reach.
    </p>

    <h2>🚀 Features</h2>
    <ul>
        <li>🔍 Keyword extraction from text posts</li>
        <li>#️⃣ Automatic hashtag generation</li>
        <li>📊 Confidence score for each hashtag</li>
        <li>🧠 NLP-based text processing</li>
        <li>🔄 JSON-based request and response handling</li>
        <li>⚡ API support using Flask</li>
    </ul>

    <h2>🛠️ Technologies Used</h2>
    <ul>
        <li>Python</li>
        <li>Flask</li>
        <li>NLTK</li>
        <li>spaCy</li>
        <li>JSON</li>
    </ul>

    <h2>📂 Project Structure</h2>
    <pre>
Post-analysis/
│── app.py
│── utils/
│── data/
│── requirements.txt
│── README.md
    </pre>

    <h2>⚙️ Installation</h2>
    <ol>
        <li>Clone the repository:
            <pre>git clone https://github.com/khushiojha/Post-analysis.git</pre>
        </li>
        <li>Navigate to project folder:
            <pre>cd Post-analysis</pre>
        </li>
        <li>Install dependencies:
            <pre>pip install -r requirements.txt</pre>
        </li>
        <li>Download spaCy model:
            <pre>python -m spacy download en_core_web_sm</pre>
        </li>
    </ol>

    <h2>▶️ Usage</h2>
    <ol>
        <li>Run the Flask app:
            <pre>python app.py</pre>
        </li>
        <li>Send POST request in JSON format:
            <pre>
{
  "text": "Your social media post content here"
}
            </pre>
        </li>
    </ol>

    <h2>📊 Sample Output</h2>
    <pre>
{
  "keywords": ["marketing", "growth"],
  "hashtags": ["#marketing", "#growth"],
  "confidence_scores": {
    "#marketing": 0.92,
    "#growth": 0.87
  }
}
    </pre>

    <h2>💡 Future Improvements</h2>
    <ul>
        <li>Add sentiment analysis</li>
        <li>Multi-language support</li>
        <li>Dashboard integration</li>
    </ul>

    <h2>📬 Contact</h2>
    <p>
        <strong>Khushi Ojha</strong><br>
        GitHub: <a href="https://github.com/khushiojha">github.com/khushiojha</a>
    </p>

</body>
</html>
