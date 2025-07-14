# **HoloNet**


HoloNet is a holographic AI-powered chat interface designed for intuitive and engaging user interactions. It combines advanced natural language processing, contextual analysis, and a visually appealing UI with a focus on adaptability and humor.



![Liana Logo](https://github.com/user-attachments/assets/3ff22b3e-d71c-494a-90b8-b6fcefa5fd94)


Liana is a cutting-edge holographic AI interface (HoloNet v2.1) designed to deliver intelligent conversations, perform in-depth concept analysis, and adapt to user communication styles. Powered by π-resonance networks and holographic memory, Liana integrates advanced text analysis with a sleek, mobile-friendly UI. It also supports dynamic SVG-based visualizations using the W3C SVG namespace (`http://www.w3.org/2000/svg`).

## Features

- **Interactive UI**: A sleek, mobile-friendly UI with animated message transitions and a dynamic, pulsating background.
- **Holographic AI (Holo)**: A self-described “golographic AI” with π-resonance networks and graph-based memory for contextual understanding.
- **Semantic Analysis**: Detects intent, topics, emotions, and keywords using a custom SemanticCore class.
- **Contextual Memory**: Utilizes a `ContextGraph` for maintaining conversation context and a `SemanticCore` for intent, topic, and emotion detection.
- **Knowledge Agent**: Fetches information from Wikipedia, DuckDuckGo, and a local knowledge base, with support for deep search and caching.
- **Responsive Design**: Optimized for both desktop and mobile devices with a dark/light theme toggle.
- **Adaptive Responses**: Adjusts response depth and tone based on user input complexity and preferences (e.g., "deeper" or "simpler").
simpler").
- **SVG Integration**: Generates dynamic visualizations using the W3C SVG namespace (see [W3C SVG Specification](https://www.w3.org/TR/SVG/)).
- **Extensible Architecture**: Supports future integration with GitHub agents for automated repository management.



## Installation

### Prerequisites

- **Node.js**: Version 16 or higher
- **npm**: For package management
- **Modern Web Browser**: For the UI (e.g., Chrome, Firefox, Safari)

### Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/0penAGI/Holographic-AI-Liana.git
   cd Holographic-AI-Liana

2. **Install**:
   ```bash
   npm install
   
3. **Run the Application**:
   Open index.html in a modern web browser, or start a local:
   ```bash
   npm start

### Usage

- **Chat Interface**: Enter your query in the input field and press Enter or click the send button. Liana responds with context-aware answers, leveraging its knowledge agent and holographic memory.
- **Context Menu**: Right-click on messages to copy, search online, or save to memory.
- **Special Commands**:
- **кто ты** • Learn about Liana’s architecture and capabilities.
- **как дела?** • View current thinking settings (e.g., analysis depth).
- **проще** • (simpler) to simplify responses.
- **глубже** • Trigger deeper analysis for complex queries.
- **настройки** • (settings) to view current configuration.

### Technical Details

**Frontend**

- HTML/CSS: Responsive design with a gradient background, animations, and a glassmorphism-inspired UI.
- JavaScript: Handles dynamic message rendering, context menus, and AI logic.
- SVG: Uses the SVG namespace for the send button icon (see W3C SVG Specification).

**Backend Logic**

- SemanticCore: Tokenizes input, detects intent, topics, and emotions, and builds a context graph.
- NeoCore: Generates personalized responses based on user profiles and semantic analysis.
- KnowledgeAgent: Fetches data from Wikipedia, DuckDuckGo, and a local knowledge base with caching and timeout handling.

#### License
This project is licensed under the MIT License. See the LICENSE file for details.
#### About
Developed by 0penAGI. For more information, contact us via GitHub Issues.
© 2025 0penAGI. ∴ Built with ∵ for the future of AI.
