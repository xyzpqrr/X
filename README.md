# 🐦 XClone – A Mini Twitter/X Frontend

**XClone** is a simple front-end project inspired by Twitter (X.com), built using **HTML, CSS, Bootstrap, and JavaScript**.  
It demonstrates a social media-like interface where users can post updates, comment, edit profiles, and contact the platform — all without a backend.

---

## 🚀 Features

- 🏠 **Home Feed:** Create posts (tweets) and add comments dynamically.  
- 🔑 **Login / Register:** Simulated authentication using static forms.  
- 👤 **Profile Page:** Update your display name and bio.  
- 💬 **Contact Page:** Send feedback or report issues.  
- 🌙 **Responsive UI:** Built entirely with Bootstrap for mobile-first design.  

---


## 🧭 Navigation Flow

Each page is connected via a shared **Bootstrap Navbar** for smooth navigation:

- **Home** → `index.html`  
- **Profile** → `profile.html`  
- **Login** → `login.html`  
- **Register** → `register.html`  
- **Contact** → `contact.html`

Since there’s **no backend routing**, navigation uses simple HTML links (`<a href="page.html">`).

---

## 🧩 Forms Included (5 Total)

| # | Form Name | Location | Purpose |
|---|------------|-----------|----------|
| 1 | Register Form | `register.html` | Create a new user |
| 2 | Login Form | `login.html` | Simulate user login |
| 3 | Post Form | `index.html` | Create new posts/tweets |
| 4 | Comment Form | `index.html` | Add comments under posts |
| 5 | Contact Form | `contact.html` | Send feedback/messages |

---

## ⚙️ Technologies Used

- **HTML5** – Structure and semantic layout  
- **CSS3** – Custom styles and visual enhancements  
- **Bootstrap 5** – Responsive grid system and UI components  
- **JavaScript (Vanilla JS)** – Dynamic post/comment handling and form interactions  

---

## 🧠 How It Works

- Posts and comments are added dynamically to the feed using JavaScript DOM manipulation.  
- LocalStorage can optionally be used to persist posts between sessions.  
- All forms currently simulate behavior (no real backend or database connection).  

---

## 🖥️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/xclone.git

2. Open the folder:
    cd xclone

3. Run locally by opening index.html in any modern browser.