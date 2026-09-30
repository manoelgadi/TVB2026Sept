Below is a complete `README.md` you can paste directly into the repository. I’ve structured it so students can understand the **entire journey of the workshop** from the repository homepage.

# 🚀 Tech Venture Bootcamp 2026 — AI Prototyping Workshop

Welcome to the **Tech Venture Bootcamp (TVB) — September 2026** AI workshop.

The objective of this session is to explore how Generative AI can be used to move quickly from a **startup idea to a working prototype**.

We will approach this from two directions:

1. **No-Code / Low-Code AI** — build useful prototypes without having to program everything yourself.
2. **AI through code** — understand how the OpenAI API can be integrated into Python applications and ultimately into a real web application.

The workshop journey is:

```text
💡 STARTUP IDEA
       ↓
🌐 BUILD IT
   v0.app + Vercel
       ↓
🎵 BRAND IT
   Suno AI
       ↓
🤖 PROGRAM IT
   OpenAI API
       ↓
🐍 BUILD THE APPLICATION
   Python + Flask
       ↓
☁️ DEPLOY IT
   PythonAnywhere
       ↓
🚀 AI-POWERED PROTOTYPE
```

---

# 📚 Workshop Structure

The workshop is divided into three main parts:

### Part 1 — No-Code / Low-Code AI

We will start by using AI tools to rapidly create things for your startup.

You will complete two practical exercises:

1. 🌐 **Build your startup waiting-list landing page with v0.app + Vercel**
2. 🎵 **Make a jingle for your startup with Suno AI**

Have a look at the **workshop PDF included in this repository** for the presentation and instructions used during the session.

---

# 🌐 Practice 1 — Build Your Startup Waiting-List Landing Page

For the first exercise, we will use:

👉 **v0.app**  
https://v0.app/

v0 allows us to describe an application using natural language and use AI to generate the application.

The objective is to create a **real landing page for your startup**, including a functional waiting list.

You will then publish the application using **Vercel** so that it can be accessed from anywhere.

---

## 📝 Prompt to Adapt

Start with the following prompt:

> **Create a modern, responsive landing page for your startup with an email-only waiting list.**
>
> **WAITING LIST**  
> Visitors can register with their email.
>
> **COUNTER**  
> Show the number of registered users on the homepage.
>
> **DATA**  
> Add `/waitinglist` and allow the emails to be downloaded in Excel-compatible format.
>
> **PERSISTENCE**  
> Registrations must remain after refreshing the page.
>
> **STARTUP NAME**  
> `<Insert your startup name>`
>
> **DESCRIPTION**  
> `<Describe your startup and its value proposition>`
>
> **LOOK & FEEL**  
> `<Describe the desired layout, colors and visual style>`

Do not simply copy the prompt unchanged.

**Adapt it to your startup.**

Think about your:

- Startup name
- Problem
- Value proposition
- Target customer
- Main message
- Call to action
- Visual identity
- Colors
- Style

---

## 🛠️ What to Do

### 1. Create the application

Go to:

https://v0.app/

Use your adapted prompt to generate your startup landing page.

---

### 2. Iterate

Do not expect the first generation to be perfect.

Continue talking to v0 and ask it to:

- Change the design
- Improve the copy
- Modify the layout
- Fix functionality
- Improve the waiting list
- Add or remove elements

This is part of the exercise.

You are learning how to **iterate with AI as a development tool**.

---

### 3. Deploy with Vercel

Once you are happy with your application, publish/deploy it.

Your final application should have a **public URL** that anybody can access.

---

### 4. Test it

Do not assume that because the page looks correct, the application actually works.

Test it.

Open your deployed application in an **Incognito / Private browser window**.

Then:

1. Enter a test email into the waiting list.
2. Submit the registration.
3. Refresh the website.
4. Confirm that the registration counter is still correct.
5. Visit:

```text
/waitinglist
```

6. Download the waiting-list data.
7. Open the downloaded file.
8. Confirm that your test email is there.

### 🎯 Goal

Go from:

```text
STARTUP IDEA
      ↓
AI PROMPT
      ↓
WORKING WEBSITE
      ↓
PUBLICLY DEPLOYED APPLICATION
```

without having to manually build the entire application from scratch.

---

# 🎵 Practice 2 — Make a Jingle for Your Startup

Software is only one part of building a startup.

Generative AI can also help with:

- Branding
- Marketing
- Music
- Communication
- Storytelling
- Creative content

For the second exercise, we will use:

👉 **Suno AI**  
https://suno.com/

Your challenge is to create an **original jingle for your startup**.

---

## 🎤 Think About Your Startup Message

Before generating the song, think about:

### What does your startup do?

Try to explain it in one sentence.

### What is your value proposition?

Why should somebody care?

### Who is your customer?

Who should identify with the song?

### What should people remember?

Your startup name?

A phrase?

A benefit?

An emotion?

---

## 🎶 Create Your Jingle

Use Suno AI to experiment with:

- Lyrics
- Musical styles
- Genres
- Tempo
- Voice
- Mood
- Different versions of the same idea

Your first song does not need to be your final song.

Generate several versions and iterate.

### 🎯 Goal

Use Generative AI to turn your startup's **value proposition into memorable creative content**.

After Practices 1 and 2, your startup has started to become something people can:

> **SEE 👀 — USE 🖱️ — HEAR 🎵**

---

# 🤖 Part 2 — From Prompts to Products: OpenAI API

We now move from **using AI applications** to understanding how developers can put AI **inside their own applications**.

This is an important distinction.

When you use ChatGPT, Suno or v0, you are using somebody else's AI application.

When you use an **API**, your own application can communicate directly with an AI model.

Conceptually:

```text
YOUR APPLICATION
       ↓
   API REQUEST
       ↓
   OPENAI API
       ↓
    AI MODEL
       ↓
   API RESPONSE
       ↓
YOUR APPLICATION
```

---

# 📓 OpenAI API Primer

The repository contains a **Python/Jupyter notebook introducing the OpenAI API**.

We will work through examples showing how Python can communicate programmatically with AI models.

The notebook explores capabilities such as:

### 💬 Text Generation

Send a question or instruction from Python and receive an AI-generated response.

```text
Python → OpenAI API → AI response
```

---

### 😊 Sentiment Analysis

Use an AI model to classify the sentiment of text.

For example:

```text
"This hotel is fantastic!"

        ↓

    positive
```

This demonstrates how AI can become a **component of another application**, rather than simply a chatbot.

---

### 🌍 Translation

Use the model to translate text between languages.

This could become part of:

- Customer support
- International applications
- Travel applications
- Communication tools

---

### 📣 Startup Taglines

Generate marketing content programmatically.

For example:

```text
STARTUP DESCRIPTION
        ↓
   OPENAI API
        ↓
MARKETING TAGLINE
```

---

### 🎨 Image Generation

We then move beyond text and generate images from Python.

```text
TEXT PROMPT
     ↓
OPENAI IMAGE MODEL
     ↓
GENERATED IMAGE
```

This demonstrates how image generation can be incorporated into an application or service.

---

### 👁️ Vision

AI can also receive an image as an input and understand its contents.

```text
IMAGE + QUESTION
       ↓
   AI MODEL
       ↓
   DESCRIPTION
```

This opens the door to applications involving:

- Image analysis
- Product recognition
- Document understanding
- Visual assistants
- Quality control

---

### 🔊 Text-to-Speech

Turn generated text into audio.

```text
TEXT
 ↓
AI
 ↓
AUDIO
```

---

### 🎤 Speech-to-Text

We can also do the reverse:

```text
AUDIO
 ↓
AI
 ↓
TEXT
```

This enables applications involving:

- Voice interfaces
- Transcription
- Meeting notes
- Voice assistants

---

### ⚡ Streaming

Finally, we explore streaming responses.

Instead of waiting for the entire AI response to be completed, applications can display the response progressively as it is generated.

This is similar to the experience you see when using modern AI assistants.

---

# 🔑 API Keys

To communicate with the OpenAI API, the application needs to authenticate.

For the workshop examples, credentials are stored separately from the Python source code.

For example:

```text
api_key.txt
api_org.txt
```

The Python application reads these files:

```python
filename = "api_key.txt"

with open(filename, "r") as file:
    api_key = file.read().strip()
```

and similarly for the organization information.

## ⚠️ IMPORTANT SECURITY RULE

**Never upload a real API key to GitHub.**

Do not put your real API key inside:

```python
api_key = "my-real-secret-key"
```

and do not commit `api_key.txt` containing a real key to a public repository.

API keys should remain private.

---

# 🐍 Part 3 — From Notebook to a Real Web Application

A Jupyter notebook is excellent for learning and experimentation.

But startups normally need applications that **other people can actually use**.

So our final step is to take the concepts from the OpenAI API notebook and put them inside a web application.

For this we will use:

- 🐍 **Python**
- 🌶️ **Flask**
- 🤖 **OpenAI API**
- 🌐 **HTML**
- ☁️ **PythonAnywhere**

---

# 📦 TVB Flask OpenAI Application

A Flask starter application will be shared for this part of the workshop.

The ZIP contains the files required to turn several of the notebook examples into a simple web application.

The structure will look approximately like:

```text
TVB_Flask_OpenAI/
│
├── flask_app.py
│
├── api_key.txt
├── api_org.txt
│
├── templates/
│   └── index.html
│
└── static/
```

The exact package shared during the workshop may contain additional supporting files.

---

# 🌶️ What Is Flask?

Flask is a lightweight Python web framework.

It allows us to connect a webpage to Python code.

Instead of:

```text
JUPYTER NOTEBOOK
       ↓
OPENAI API
```

we can build:

```text
USER
 ↓
WEB BROWSER
 ↓
HTML PAGE
 ↓
FLASK
 ↓
PYTHON
 ↓
OPENAI API
 ↓
AI MODEL
 ↓
FLASK
 ↓
WEB PAGE
```

Now our AI code has become part of an **actual web application**.

---

# 🧪 What Can We Test in the Flask Application?

The Flask application translates several concepts from the API Primer into things that can be tested from a browser.

Depending on the final version used during the workshop, these may include:

- 💬 Ask AI
- 😊 Sentiment analysis
- 🌍 Translation
- 📣 Startup tagline generation
- 🎨 Image generation
- 👁️ Vision
- 🔊 Text-to-Speech
- 🎤 Speech-to-Text
- 🌍 Audio translation
- ⚡ Streaming responses

This is the same basic idea we explored in the notebook, but now the user interacts through a **web interface instead of Python cells**.

---

# ☁️ Part 4 — Deploy with PythonAnywhere

Finally, we will deploy our Flask application using:

👉 **PythonAnywhere**  
https://www.pythonanywhere.com/

PythonAnywhere allows us to run Python applications on the web.

The Flask application package and deployment instructions will be shared during the workshop.

---

# 🏗️ Final Architecture

At this point, we have built a simple version of the architecture behind many AI-powered products:

```text
                    USER
                      │
                      ▼
               ┌─────────────┐
               │ WEB BROWSER │
               └─────────────┘
                      │
                      ▼
               ┌─────────────┐
               │ HTML / UI   │
               └─────────────┘
                      │
                      ▼
               ┌─────────────┐
               │    FLASK    │
               └─────────────┘
                      │
                      ▼
               ┌─────────────┐
               │   PYTHON    │
               └─────────────┘
                      │
                      ▼
               ┌─────────────┐
               │ OPENAI API  │
               └─────────────┘
                      │
                      ▼
               ┌─────────────┐
               │  AI MODEL   │
               └─────────────┘
                      │
                      ▼
                 AI RESPONSE
                      │
                      ▼
                 WEB BROWSER
```

The important point is that the **OpenAI API is not the application**.

It is one component inside the application.

Your startup controls:

- The user experience
- The interface
- The prompts
- The business logic
- The data
- What information is sent to the model
- What happens with the model's response

---

# 🎯 What You Should Learn

By the end of this workshop, you should understand three different approaches to building with AI.

## 1️⃣ Use AI Tools

```text
YOU → v0 / Suno → OUTPUT
```

Use existing AI products to rapidly prototype.

---

## 2️⃣ Use AI Programmatically

```text
PYTHON → OPENAI API → AI MODEL
```

Use AI as a capability inside your own code.

---

## 3️⃣ Build AI Into a Product

```text
USER
 ↓
WEB APP
 ↓
PYTHON / FLASK
 ↓
OPENAI API
 ↓
AI
```

Turn AI capabilities into something that another person can actually use.

---

# 🚀 The Complete TVB Journey

During this workshop we move progressively through:

```text
                         💡
                    STARTUP IDEA
                         │
                         ▼
                ┌─────────────────┐
                │     v0.app      │
                │  + Vercel       │
                └─────────────────┘
                         │
                         ▼
                 🌐 LANDING PAGE
                         │
                         ▼
                ┌─────────────────┐
                │     Suno AI     │
                └─────────────────┘
                         │
                         ▼
                  🎵 STARTUP JINGLE
                         │
                         ▼
                ┌─────────────────┐
                │ OPENAI API      │
                │ Python Notebook │
                └─────────────────┘
                         │
                         ▼
                    🤖 AI CODE
                         │
                         ▼
                ┌─────────────────┐
                │ Python + Flask  │
                └─────────────────┘
                         │
                         ▼
                   🌐 WEB APP
                         │
                         ▼
                ┌─────────────────┐
                │ PythonAnywhere  │
                └─────────────────┘
                         │
                         ▼
                 🚀 AI PROTOTYPE
```

---

# 💡 The Main Idea

You do **not** need to build everything from scratch.

Modern startup prototyping can combine:

**No-Code + Low-Code + AI + APIs + Traditional Code**

The important skill is understanding **which tool to use, what it can do, and how the different pieces can work together**.

The progression of this workshop is therefore intentional:

> **Use AI → Understand AI → Program AI → Embed AI → Deploy AI**

---

# 🚀 Tech Venture Bootcamp 2026

### From Ideas → Prototypes → AI-Powered Products

Experiment. Build. Test. Iterate.
