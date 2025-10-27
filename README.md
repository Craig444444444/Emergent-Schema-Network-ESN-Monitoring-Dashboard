# ESN Architecture Dashboard

**Author:** Craig Huckerby

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

An interactive and fully functional web dashboard designed to visualize and simulate the **Emergent Schema Network (ESN)**, a conceptual next-generation AI architecture. This project brings to life the core components of the ESN, demonstrating how they interact to achieve advanced reasoning, self-correction, and persistent learning.

## 🌟 Key Features

-   **Interactive Force-Directed Graph:** Explore the Causal Schema Core (CSC) as a dynamic knowledge graph. Drag nodes, search for concepts, and inspect Datalog-style facts on hover.
-   **Functional Self-Correction Loop:** Watch the Critic module identify and repair a "causal cycle" violation in the graph in real-time, demonstrating a key feature of the ESN's robustness.
-   **Simulated Data Pipeline:** Interactively apply sequential data enhancements—from programming and statistics to marketing and software—to see how raw data is prepared for the ESN.
-   **Real-time API Logging:** A unified log tracks all system activity, providing a live feed of the interactions between different components.
-   **Component Visualizations:** See the flow of data between the Linguistic Front-End (LFE) and the CSC via the Schema Projection Module (SPM), and monitor the system's persistent state.

## 🚀 How to Run

This project is a single, self-contained HTML file. No build process is required.

1.  Clone this repository to your local machine.
    ```bash
    git clone https://github.com/your-username/esn-dashboard.git
    ```
2.  Navigate to the project directory.
    ```bash
    cd esn-dashboard
    ```
3.  Open the `index.html` file in your favorite web browser.

For the best experience, you can also serve the files from a local web server (e.g., using the `Live Server` extension in VS Code or `python -m http.server`).

## 🧠 Conceptual Background

The Emergent Schema Network (ESN) is a theoretical AI architecture proposed to overcome the limitations of current stateless Large Language Models (LLMs). The core idea is to introduce a persistent, non-linguistic **Causal Schema Core (CSC)** that builds a true world model, separate from the language processing unit. This allows for deeper causal reasoning, genuine creativity, and real-time self-improvement.

This dashboard visualizes the key components of that architecture:

1.  **Causal Schema Core (CSC):** The persistent, graph-based knowledge base.
2.  **Persistent State & Memory:** The system's ability to save and recall its state.
3.  **Schema Projection Module (SPM):** The bridge between linguistic and conceptual data.
4.  **Dynamic Self-Correction Loop (Critic):** The mechanism for identifying and fixing logical inconsistencies.
5.  **Linguistic Front-End (LFE):** The specialized language model for processing text.
6.  **Unified API & Monitoring Dashboard:** The interface for interacting with and observing the entire system.

## 🛠️ Technologies Used

-   **HTML5 Canvas & SVG:** For rendering the interactive graphs and animations.
-   **CSS3:** For styling, transitions, and a modern dark theme.
-   **Tailwind CSS:** A utility-first CSS framework for rapid UI development.
-   **Vanilla JavaScript:** For all logic, simulations, and interactivity, with no external frameworks.

## 🔮 Future Enhancements

-   **Data Persistence:** Implement `localStorage` or `IndexedDB` to allow users to save and load the state of the CSC graph.
-   **Performance Scaling:** Use Web Workers to offload the force-directed graph calculations, enabling the visualization of much larger knowledge graphs.
-   **Accessibility:** Add ARIA labels and keyboard navigation to make the dashboard fully accessible.

## 👨‍💻 Author

Created and designed by Craig Huckerby.

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
