# 🚀 Hello World – 3 Ways (HTML | JS | React CDN)

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-orange?style=for-the-badge&logo=html5" />
  <img src="https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript" />
  <img src="https://img.shields.io/badge/React-CDN-blue?style=for-the-badge&logo=react" />
</p>

<p align="center">
  🔥 A simple project demonstrating how to render <b>Hello World</b> using three different approaches.
</p>

---

## 📌 Overview

This project showcases 3 ways to render **Hello World**:

| Approach       | Description                       |
| -------------- | --------------------------------- |
| 🟠 HTML        | Static rendering using plain HTML |
| 🟡 JavaScript  | Dynamic DOM manipulation          |
| 🔵 React (CDN) | Declarative UI using React        |

---

## 🧱 1. HTML Approach

```html
<h1>Hello World</h1>
```

### 💡 Key Points

* No JavaScript required
* Fast and simple
* Static content rendering

---

## ⚙️ 2. JavaScript Approach

```html
<div id="root"></div>

<script>
  document.getElementById("root").innerText = "Hello World";
</script>
```

### 💡 Key Points

* Direct DOM manipulation
* Imperative programming style
* Dynamic content update

---

## ⚛️ 3. React using CDN

### 🔗 CDN Setup

```html
<script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
```

### 🧪 Implementation

```html
<div id="root"></div>

<script>
  const element = React.createElement("h1", {}, "Hello World");
  const root = ReactDOM.createRoot(document.getElementById("root"));
  root.render(element);
</script>
```

---

## 🧠 Understanding `React.createElement`

```js
React.createElement(type, props, children)
```

| Parameter   | Description                                       |
| ----------- | ------------------------------------------------- |
| 🏷️ type    | HTML tag or component (e.g., `"h1"`)              |
| ⚙️ props    | Object for attributes (e.g., `{ id: "heading" }`) |
| 📦 children | Content inside the element                        |

---

## 🌐 `crossorigin` Attribute Explained

```html
<script crossorigin src="..."></script>
```

### 🔍 Why it is used?

* Enables **CORS (Cross-Origin Resource Sharing)**
* Required when loading scripts from CDN
* Improves error visibility in browser console

### 📌 Types:

* `anonymous` (default)
* `use-credentials`

---

## 🔥 Key Learnings

* 🟠 HTML → Static UI
* 🟡 JS → Imperative DOM updates
* 🔵 React → Declarative + Virtual DOM

---

## 🎯 Interview Insight

👉 **Difference between HTML, JS, and React?**

* HTML → Static rendering
* JS → Direct DOM manipulation
* React → Virtual DOM + Declarative UI

---

## 🚀 When to Use What?

| Use Case               | Best Choice |
| ---------------------- | ----------- |
| Simple static page     | HTML        |
| Small dynamic behavior | JavaScript  |
| Large scalable apps    | React       |

---

## ⭐ Final Thoughts

* CDN-based React is great for **learning & prototyping**
* For production apps, prefer tools like **Vite or Create React App**

---

<p align="center">
  💡 <i>Built for learning and interview preparation</i>
</p>
