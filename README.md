# 🪟 Modal Window Project

A simple **modal window** project built with pure **HTML, CSS, and JavaScript**.  
Clicking on any of the "Show Modal" buttons displays a modal popup, and you can close it by:
- Clicking the close (`×`) button  
- Clicking outside the modal (on the overlay)  
- Pressing the **Escape (Esc)** key on your keyboard  

---

## 🧠 Features

- 🖱️ Open modal by clicking any of the “Show modal” buttons  
- ❌ Close modal by clicking outside or pressing `Esc`  
- 🎨 Smooth overlay and modal design with CSS  
- ⚡ Implemented using pure JavaScript (no libraries)  
- 🧩 Reusable and easy to integrate in other projects  

---

## 🛠️ Built With

- **HTML5** – Structure of the modal and buttons  
- **CSS3** – Styling, layout, and animations  
- **JavaScript (ES6)** – Event handling and DOM manipulation  

---

## 🧩 How It Works

1. The modal and overlay are hidden by default using the `.hidden` CSS class.  
2. When any button with class `.show-modal` is clicked, JavaScript removes the `.hidden` class from both elements to display them.  
3. Clicking the close button, the overlay, or pressing the `Escape` key adds the `.hidden` class again — hiding the modal.  

---

## 📦 Installation & Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Yegannee/modal-window.git
