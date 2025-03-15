# 🧮 Calculator

## 🌟 Overview
This is a **simple, stylish, and interactive web-based calculator** built using **HTML, CSS, and JavaScript**. It supports basic arithmetic operations with a clean and modern UI.

## 🚀 Features
✅ **Easy-to-use interface** - Click buttons or use your keyboard for input!  
✅ **Basic arithmetic operations** - Addition, subtraction, multiplication, and division  
✅ **Real-time calculations** - Get instant results with the `=` button  
✅ **Error handling** - Displays `Error` for invalid expressions  
✅ **Responsive design** - Works on desktops, tablets, and mobile devices  

## 🛠️ Technologies Used
🔹 **HTML** - Structuring the calculator  
🔹 **CSS** - Styling for a modern and sleek UI  
🔹 **JavaScript** - Handles calculations and button interactions  

## 🎯 How to Use
1️⃣ Click on the number buttons to enter values.  
2️⃣ Use the operator buttons (`+`, `-`, `*`, `/`) for calculations.  
3️⃣ Press the `=` button to see the result.  
4️⃣ Click `C` to clear the display and start fresh!  

🔹 **Pro Tip:** You can also use your keyboard for faster input! 🎉

## 📂 Project Files
📄 `index.html` - Structure of the calculator  
🎨 `style.css` - Stylish design for an eye-catching UI  
📝 `script.js` - The logic behind calculations  

## 📌 Installation and Usage
No setup needed! Just **open `index.html` in your browser**, and you're ready to calculate. 🎯

## 👀 Live Preview
💻 Want to try it now? **[Click here](#)** to see the live demo! *(Replace `#` with your live link if hosted.)*

## 🔎 Code Preview
### 🏗️ HTML Structure
```html
<div id="calculator">
    <input id="display" readonly>
    <div id="keys">
        <button onclick="appendToDisplay('+')" class="operator-btn">+</button>
        <button onclick="appendToDisplay('7')">7</button>
        <button onclick="appendToDisplay('8')">8</button>
        <button onclick="appendToDisplay('9')">9</button>
        <button onclick="appendToDisplay('-')" class="operator-btn">-</button>
        <button onclick="appendToDisplay('4')">4</button>
        <button onclick="appendToDisplay('5')">5</button>
        <button onclick="appendToDisplay('6')">6</button>
        <button onclick="appendToDisplay('*')" class="operator-btn">*</button>
        <button onclick="appendToDisplay('1')">1</button>
        <button onclick="appendToDisplay('2')">2</button>
        <button onclick="appendToDisplay('3')">3</button>
        <button onclick="appendToDisplay('/')" class="operator-btn">/</button>
        <button onclick="appendToDisplay('0')">0</button>
        <button onclick="appendToDisplay('.')">.</button>
        <button onclick="Calculate()">=</button>
        <button onclick="clearDisplay()" class="operator-btn">C</button>
    </div>
</div>
```

### ⚡ JavaScript Logic
```javascript
const display = document.getElementById("display");

function appendToDisplay(value) {
  display.value += value;
}

function clearDisplay() {
  display.value = "";
}

function Calculate() {
    try {
        display.value = eval(display.value);
    } catch (error) {
        display.value = "Error";
    }
}
```

## 📜 License
🆓 This project is open-source! Feel free to modify and improve it.

## 🤝 Contribution
🚀 **Want to improve this project?** Fork it, enhance the UI, add features, and submit a pull request!

📬 **Have suggestions or found a bug?** Open an issue, and let's make this calculator even better! 💡

---
🎉 **Happy Coding!** 🚀

