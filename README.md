<h1>🎥 YouTube Q&A Chatbot</h1>

<p>This is a Streamlit web application that allows users to ask questions about the content of a YouTube video. It uses <strong>LangChain</strong>, <strong>OpenAI's language models</strong>, and <strong>vector similarity search</strong> to retrieve the most relevant answers from the video transcript.</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>Load transcript from any public YouTube video</li>
  <li>Split and embed video transcript using OpenAI Embeddings</li>
  <li>Search for answers using FAISS vector database</li>
  <li>Ask natural language questions and get relevant answers</li>
</ul>

<hr>

<h2>🧰 Tech Stack</h2>
<ul>
  <li><strong>Frontend:</strong> Streamlit</li>
  <li><strong>LLM:</strong> OpenAI GPT-3.5 / GPT-4 (via LangChain)</li>
  <li><strong>Embeddings:</strong> OpenAI Embeddings</li>
  <li><strong>Vector Store:</strong> FAISS</li>
  <li><strong>Transcripts:</strong> LangChain YouTubeLoader</li>
</ul>

<hr>

<h2>📦 Installation</h2>

<pre><code>git clone https://github.com/your-username/youtube-qa-chatbot.git
cd youtube-qa-chatbot
pip install -r requirements.txt
</code></pre>

<p>Set your OpenAI API Key:</p>

<pre><code>export OPENAI_API_KEY=your-api-key-here
</code></pre>

<hr>

<h2>🏃 Running the App</h2>

<pre><code>streamlit run streamlit_app.py
</code></pre>

<p>Then open <a href="http://localhost:8501" target="_blank">http://localhost:8501</a> in your browser.</p>

<hr>

<h2>📌 Example Usage</h2>

<ol>
  <li>Paste a YouTube video URL</li>
  <li>Ask questions like: <em>"What is the main topic?"</em>, <em>"What are the key takeaways?"</em></li>
  <li>See answers with context from the video transcript</li>
</ol>

<hr>

<h2>🔐 Environment Variables</h2>
<ul>
  <li><code>OPENAI_API_KEY</code> – Required</li>
</ul>

<hr>

<h2>📄 License</h2>
<p>This project is licensed under the MIT License.</p>
