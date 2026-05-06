<!DOCTYPE html>
<html>

<body>
    <h1>Social Media Post Analysis</h1>

    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#technologies-used">Technologies Used</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#usage">Usage</a></li>
    </ul>

    <h2 id="introduction">Introduction</h2>
    <p>
        Social Media Post Analysis is a web-based application that uses Natural Language Processing (NLP)
        techniques to analyze text data from social media posts. The system extracts keywords, generates
        relevant hashtags, and assigns confidence scores to each hashtag. The backend is built using Python
        Flask to handle API requests and responses in JSON format.
    </p>

    <h2 id="features">Features</h2>
    <ul>
        <li>Analyze text data from social media posts.</li>
        <li>Automatic keyword extraction using NLP.</li>
        <li>Hashtag generation based on content.</li>
        <li>Confidence score for each generated hashtag.</li>
        <li>JSON-based API for sending and receiving data.</li>
        <li>Lightweight and fast Flask backend.</li>
    </ul>

    <h2 id="technologies-used">Technologies Used</h2>
    <ul>
        <li><strong>Front-end</strong>: HTML, CSS</li>
        <li><strong>Back-end</strong>: Python, Flask</li>
        <li><strong>NLP Libraries</strong>: NLTK, spaCy</li>
        <li><strong>Data Format</strong>: JSON</li>
    </ul>

    <h2 id="installation">Installation</h2>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/khushiojha/Post-analysis.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd Post-analysis</code></pre>
        </li>
        <li>Install dependencies:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li>Download spaCy model:
            <pre><code>python -m spacy download en_core_web_sm</code></pre>
        </li>
        <li>Run the Flask server:
            <pre><code>python app.py</code></pre>
        </li>
    </ol>

    <h2 id="usage">Usage</h2>
    <p>1. Run the Flask application.</p>
    <p>2. Send a POST request with text data in JSON format.</p>
    <pre><code>{
  "text": "Your social media post content here"
}</code></pre>
    <p>3. The system will return:</p>
    <ul>
        <li>Extracted keywords</li>
        <li>Generated hashtags</li>
        <li>Confidence scores</li>
    </ul>

</body>

</html>
