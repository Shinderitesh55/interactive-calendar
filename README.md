 # 📅  interactive-calendar 
A high-fidelity, interactive React application developed for the **Frontend Engineering Summer Intern** technical assessment. This project reimagines a traditional wall calendar as a dynamic, context-aware digital experience.

## 🌟 Unique Features
* **Dynamic Seasonal UI:** The application automatically detects the month being viewed and pulls unique, high-definition nature imagery (Spring, Summer, Autumn, Winter) via the Unsplash API to reflect the current season.
* **Aesthetic Physical Design:** Includes custom-styled "binder rings" and bold, oversized typography to maintain the creative "Wall Calendar" aesthetic requested in the brief.
* **Intelligent Range Selection:** Implemented a non-linear date selection logic that allows users to pick a start and end date with immediate visual feedback (connected pill-style highlighting).
* **Data Persistence:** Integrated `localStorage` hooks to ensure that "Monthly Memos" are saved locally on the user's browser, persisting through page refreshes.
* **Responsive Fluidity:** Engineered a mobile-first layout that seamlessly transitions from a vertical stack (mobile) to a sophisticated side-by-side dashboard (desktop).

## 🛠️ Technical Implementation
* **React 18:** Leveraged functional components and Hooks (`useState`, `useEffect`) for state management.
* **Tailwind CSS:** Used for rapid utility-first styling and managing complex responsive states.
* **Zero-Dependency Date Logic:** Built the calendar grid calculation from scratch using the native JS `Date` object to demonstrate core logic proficiency.
* **Babel Standalone:** Utilized for real-time JSX transpilation, allowing the project to run as a portable, single-file application without complex build-steps.

## 🚀 Deployment & How to Run
To ensure the best experience and to bypass browser security (CORS) when loading dynamic images:

1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/seasonal-calendar.git
    ```
2.  **Run with Live Server:**
    * Open the folder in **VS Code**.
    * Right-click `index.html` and select **"Open with Live Server"**.
3.  **No Installation Required:** This version is optimized for portability and does not require `npm install`.

## 🧠 Project Decisions
* **Why Single-File?** I chose a single-file architecture to ensure the recruiter could run the project instantly without fighting environment/versioning issues.
* **Creative Liberty:** I added seasonal keyword filtering to the image engine (e.g., searching for "Snow" in December vs "Flowers" in April) to make the "Nature" theme feel intentional and unique.

---
*Developed as part of the 2026 SWE Internship Technical Challenge.*
