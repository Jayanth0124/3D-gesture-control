# Fingr Lab - Interactive 3D Gesture Control

<img src="logo.png" alt="Fingr Lab Demo Screenshot">

**Fingr Lab** is an interactive WebGL demo that allows you to control and manipulate 3D objects in real-time using your hand gestures. Powered by MediaPipe and Three.js, this project brings a unique, intuitive way to interact with digital content directly in your web browser.

## ✨ Live Demo

Experience it live: **[https://fingrlab.netlify.app/](https://fingrlab.netlify.app/)**

---

## Features

* **Real-Time Hand Tracking**: Utilizes Google's MediaPipe Hands to accurately detect and track up to two hands via your webcam.
* **Intuitive Gesture Control**: Use natural hand gestures to manipulate 3D objects.
* **Dynamic Shape Switching**:
    * Switch between a **Sphere**, **Cube**, and **Torus**.
* **Interactive Controls**:
    * **Right Hand**: Control the object's **size** by pinching your thumb and index finger.
    * **Left Hand**: Change the object's **color** by "touching" it with your index finger.
* **Professional UI**: A clean, modern interface with a "frosted glass" effect for the header, footer, and settings panels.
* **Onboarding Instructions**: A helpful pop-up modal explains the controls to new users.
* **Responsive Design**: Works seamlessly on desktop browsers with a webcam.

---

## 🖐️ How to Use

The controls are designed to be simple and intuitive. Once you grant camera access, use your hands as follows:

| Hand         | Gesture                     | Action                               |
| :----------- | :-------------------------- | :----------------------------------- |
| **Left Hand** | Pinch Thumb & Index Finger  | Adjust the **size** of the object.   |
| **Right Hand** | Touch object with Index Finger | Change the object's **color**.        |


You can also use the **Settings Panel** on the top right to manually select a shape.

---

## 🛠️ Technologies Used

* **[Three.js](https://threejs.org/)**: For 3D rendering and scene management.
* **[MediaPipe Hands](https://mediapipe.dev/)**: For high-fidelity, real-time hand and finger tracking.
* **HTML5 Canvas**: To draw hand landmarks for visual feedback.
* **JavaScript**: For all the real-time interaction logic.

---

## 🚀 Setup for Local Development

To run this project on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Jayanth0124/3D-gesture-control.git](https://github.com/Jayanth0124/3D-gesture-control.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd 3D-gesture-control
    ```

3.  **Run a local web server.**
    Because browser security policies require a secure context (`https`) to access the webcam, you cannot simply open the `index.html` file. The easiest way to run a local server is with Python.

    ```bash
    # For Python 3
    python -m http.server

    # For Python 2
    python -m SimpleHTTPServer
    ```

4.  **Open your browser** and navigate to `http://localhost:8000`.

---

## ☁️ Deployment

This project is a static website and is deployed on **[Netlify](https://www.netlify.com/)**. Any push to the `main` branch of the GitHub repository will automatically trigger a new deployment.

## Credits & Contact

This project was designed and developed by **Donavalli Jayanth**.

* **Portfolio:** [jayanth.site](http://www.jayanth.site)
* **GitHub:** [@Jayanth0124](https://github.com/Jayanth0124)
* **LinkedIn:** [jayanth-donavalli](https://www.linkedin.com/in/jayanth-donavalli)