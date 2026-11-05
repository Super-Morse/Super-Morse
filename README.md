# Hi, I'm Morse 👋

## Python / Go Developer

I am an experienced **Python** developer specializing in computer vision, machine learning, and smart data processing, combined with building high-performance backend systems in **Go**. I enjoy designing end-to-end architectures where intelligent Python-driven analysis seamlessly integrates with blazing-fast Go infrastructure.

---

## 💻 Key Projects in Focus

### 📸 1. Rubik's Cube CV Detector (Python + Computer Vision)
*⏳ Work in progress — full integration and mega-cool demo video coming soon!*

An intelligent detector designed to recognize the state of a scrambled physical Rubik's Cube from a photo/camera stream and feed its color matrix configuration directly into a high-performance solver engine.

🚀 **Live Web App:** [https://rubiks-visual-detector-and-solver.onrender.com
* **Stack:** Python, OpenCV / YOLO, NumPy.
* **Architecture:** Python acts as the "brains" of the ecosystem, handling image preprocessing, contour detection, and color classification. It generates a standard Singmaster notation string and passes it directly to the Go engine for real-time 3D state building and instant macro-solving routines.

---

### 🧩 2. Rubik's Cube 3D Solver (Go + WebAssembly)
An ultra-fast, interactive 3D Rubik's Cube application featuring a high-performance solver built with pure Go and compiled to WebAssembly to run natively in the browser.

* **🔗 Live Demo:** [super-morse.github.io/rubiks-solver](https://super-morse.github.io/rubiks-solver/)
* **Stack:** Go (Golang), WASM, JavaScript (ES6+), Three.js (WebGL).
* **Code Quality:** 100% statement coverage via unit testing, 0% duplication, absolute Grade "A" for security and maintainability via SonarCloud.

👀 Demo & Interface

<details open>
<summary><b>Click to expand live animations</b></summary>
<br>

<div align="center">
  <table border="0">
    <tr>
      <td align="center" valign="top" width="60%">
        <b>🖥️ Desktop Full-Width View</b><br><br>
        <img src="images/desktop-demo.gif" alt="Desktop Web Demo" width="100%" style="border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.3);"/>
      </td>
      <td align="center" valign="top" width="35%">
        <b>📱 Mobile View (Samsung A16)</b><br><br>
        <img src="images/mobile-demo.gif" alt="Mobile Web Demo" width="100%" style="border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.3);"/>
      </td>
    </tr>
  </table>
</div>

</details>

> 💡 **Architectural Trade-off:** The Two-Phase Kociemba solver routine executes directly in the browser in just **~40ms**. Heavy algorithmic workloads are offloaded from the server straight to the client-side binary runtime via WASM, ensuring absolute zero UI lag.

---

## 🚁 Engineering Legacy (Production Experience)

### Mobile AR Helicopter Simulator (Unity / C#)
My very first completed project, successfully **shipped and deployed to production on Google Play**. It is a mobile augmented reality helicopter simulator that maps true drone aerodynamics into an AR environment.

<img src="images/heli.gif" width="600" alt="AR Helicopter Demo">

* **Why it matters:** The repository is now safely archived as private (legacy codebase, as my current professional focus is entirely on the Go + Python ecosystem). However, building this product end-to-end provided me with a robust engineering foundation in 3D mathematics, vector physics, quaternion transformations, and the complete product release lifecycle.
* **🔊 Full Video with 3D Spatial Audio:** [Watch Demo on YouTube](https://www.youtube.com/watch?v=63eYgKwUqXM) *(Headphones recommended for spatial blade sounds)*

---

## 🛠 Tech Stack Overview

* **Languages:** Python, Go (Golang), SQL (Prior background: C#, JS)
* **Tools & Frameworks:** WebAssembly, Three.js, OpenCV, Git, Docker, SonarCloud, Linux

---
<p align="right">
  <em>Morse Code <span style="letter-spacing: 2px;">..- ._</span></em> 📟
</p>
