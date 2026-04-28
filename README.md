# EpiBot – Public Health Chatbot

EpiBot is a web-based public health chatbot designed to provide insights on diseases, outbreak alerts, and global health trends. It integrates the Groq API with Llama 3 to generate real-time, context-aware responses.

The application is implemented as a static web project using HTML, CSS, and JavaScript, and runs entirely in the browser without requiring a backend service.

---

## Features

- AI-powered chatbot using Groq API (Llama 3)
- Interactive disease statistics dashboard
- Disease comparison module
- Outbreak alerts and monitoring
- Voice input support
- Chat export functionality
- Basic login system (client-side demo)

---

## Disease Topics Covered

- Influenza  
- COVID-19  
- Measles  
- Tuberculosis  
- Dengue  
- HIV/AIDS  

---

## Technology Stack

- HTML5  
- CSS3  
- JavaScript  
- Groq API (Llama 3)

---

## Project Structure

    epibot-project/
    │
    ├── public_health_chatbot_groq.html   # Main chatbot interface
    ├── index.html                        # Redirect entry point
    ├── vercel.json                       # Vercel deployment configuration
    ├── netlify.toml                      # Netlify deployment configuration
    ├── README.md                         # Project documentation

---

## Setup and Usage

1. Clone or download the repository  
2. Open `index.html` in any modern web browser  
3. Enter your Groq API key  
4. Start interacting with the chatbot  

---

## Deployment

This project can be deployed as a static site on the following platforms:

### Netlify
- Upload the project folder directly  
- No build configuration required  

### Vercel
- Import the repository  
- Select "Other" as the framework  
- Deploy without build step  

---

## Important Note

The current authentication system is implemented using client-side session storage and is intended for demonstration purposes only. It is not secure for production environments.

For production deployment, integrate a secure authentication mechanism such as:
- Firebase Authentication  
- Auth0  
- Supabase Auth  
- Custom backend with JWT  

---

## Use Cases

- Educational tool for understanding public health data  
- Demonstration of AI-powered chatbot integration  
- Academic or portfolio project  

---

## Author

Sagar Shakya  
B.Tech Student  
Interested in Artificial Intelligence, Software Development, and Real-Time Systems  

---

## License

This project is intended for educational and demonstration purposes.
