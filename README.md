# EduAgent.ai - Personalized Learning Paths

**EduAgent** is an intelligent educational agent that uses "ScaleDown" methodology to compress massive course catalogs into highly personalized, efficient learning paths.

## 🚀 Key Features

### 1. Agents & Intelligence
-   **ScaleDown Agent**: Compresses mock course catalogs (14,000+ items) by 75% by filtering irrelevant content and extracting only high-value metadata based on your profile.
-   **Skill Gap Analyzer**: Automatically detects missing skills by comparing your *Current Skills* with your *Target Role* (e.g., Full Stack Developer).
-   **Path Optimizer**: Generates a linear, prerequisite-aware learning roadmap.
-   **Peer Matcher**: Finds other learners on similar paths to form study groups.

### 2. Personalized Dashboard
-   **Visual Path**: Interactive timeline of your learning journey.
-   **AI Learning Companion**: A chat widget to discuss your progress and get advice.
-   **Market Insights**: Real-time (simulated) data on salary trends and job demand for your target role.
-   **Skill Analysis**: Visual breakdown of your skill acquisition.

## 🛠️ Tech Stack
-   **Frontend**: React + Vite
-   **Styling**: Vanilla CSS (Glassmorphism, Dark Mode, Animations)
-   **Icons/Fonts**: Google Fonts (Outfit)

## 📦 How to Run

1.  **Install Dependencies**
    ```bash
    npm install
    ```

2.  **Start Development Server**
    ```bash
    npm run dev
    ```
    The app will open automatically at [http://localhost:5173](http://localhost:5173).

## 📄 Project Structure
-   `src/agents/`: Logic for ScaleDown, SkillGap, PathOptimizer, etc.
-   `src/components/`: UI Widgets (Dashboard, Charts, Visualizers).
-   `src/services/`: Mock data integrations (Coursera/Udemy).

## 📊 ScaleDown Outcome
The system is designed to improve learning efficiency by **40%** by eliminating redundant "introductory" modules for learners who already possess baseline knowledge.
