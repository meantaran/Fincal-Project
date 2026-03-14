Financial Pro - Investment Planning Suite

Financial Pro is a high-performance, responsive financial planning dashboard built with React, Tailwind CSS, and Firebase. It provides users with advanced calculators for SIP, SWP, Goal Planning, and Retirement, featuring real-time data visualization and persistent history tracking.

🚀 Features

1. Financial Calculators

SIP Calculator: Estimate future wealth for regular monthly investments.

SWP (Systematic Withdrawal Plan): Plan monthly income from a lump sum while tracking remaining balance.

Top-Up SIP: Calculate growth with annual percentage increases in investment.

Goal Planner: Reverse-calculate the required monthly SIP to reach a specific financial target.

Retirement Planner: Comprehensive tool considering current age, retirement age, and inflation-adjusted expenses.

2. Data Visualization

Interactive Projections: Utilizes recharts for fluid Area Charts showing investment vs. wealth growth.

Export to PDF: Professional report generation functionality using native print CSS optimization.

3. Smart Persistence

Firebase Integration: Secure, anonymous authentication.

Cloud History: Automatically saves every calculation to Firestore so users can track their planning history across sessions.

4. Modern UI/UX

Responsive Design: Fully optimized for Mobile, Tablet, and Desktop.

Dark/Light Themes: Sophisticated color palette (Royal Blue & Crimson).

Lucide Icons: High-quality vector icons for better accessibility.

🛠️ Tech Stack

Frontend: React.js (Hooks, Functional Components)

Styling: Tailwind CSS

Charts: Recharts

Icons: Lucide React

Backend: Firebase (Authentication & Firestore)

Mathematical Engine: Custom JavaScript Finance Logic (Compound Interest, Real Rate of Return, Inflation Adjustment)

📦 Installation & Setup

Clone the repository:

git clone [https://github.com/your-username/financial-pro.git](https://github.com/your-username/financial-pro.git)
cd financial-pro


Install dependencies:

npm install


Configure Firebase:
Create a .env file or update the configuration block in App.js with your Firebase credentials:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};


Run the application:

npm start


📈 Usage

Dashboard: Select a planning tool from the main grid.

Inputs: Use sliders or text inputs to adjust investment amounts, interest rates, and time horizons.

Calculate: Click "Calculate Results" to trigger the math engine and save the entry to your history.

Analysis: View the "Growth Projection" chart to see your wealth trajectory.

Export: Click "Export Report" to generate a clean, print-ready PDF summary of your plan.
