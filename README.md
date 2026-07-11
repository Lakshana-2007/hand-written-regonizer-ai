# 💰 FinanceTracker Dashboard

[![React](https://img.shields.io/badge/React-v18.x-61dafb.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-v5.x-blue.svg)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-v5.x-646cff.svg)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v3.x-38bdf8.svg)](https://tailwindcss.com/)
[![ShadcnUI](https://img.shields.io/badge/UI_Library-Shadcn/UI-black.svg)](https://ui.shadcn.com/)

**FinanceTracker** is a clean, interactive, and modern dashboard designed to help users track personal income, manage expenses, monitor savings goals progress, and build long-term saving streaks. Featuring an elegant dark mode dashboard, responsive visualizations, dynamic summaries, and alerts, it provides a seamless interface to command your financial future.

> [!NOTE]
> This project code is currently residing in the repository named `hand-written-regonizer-ai`. It is highly recommended to rename the repository to **`finance-tracker`** or **`financial-guardian`** in GitHub settings to align with the codebase.

---

## 🌟 Key Features

* **Financial Summary Cards:** Real-time visibility into your **Total Income**, **Total Expenses**, and **Net Savings** with percentage indicators showing monthly trends.
* **Saving Streak Counter:** Active visual gamified counter checking if you are consistently meeting savings rules daily to build financial habits.
* **Target Savings Goals:** Add savings goals with names and milestones. Visual progress bars track current savings against the target amount.
* **Interactive Transaction Form:** Create transaction entries with detailed parameters:
  * Amount, Category (e.g. Salary, Groceries, Rent, Utilities, Entertainment, Investment).
  * Transaction Type (Income vs Expense).
  * Custom Dates and notes.
* **Detailed Transaction Registry:** Orderly ledger history list allowing search, quick modification, and deletion.
* **Quick Stats Summary:** Automated breakdown showing data entries counter for active goals, income ratios, and transactions data.

---

## 🛠️ Technology Stack

* **Core UI / Rendering:** React (v18) with SWC compiler, TypeScript.
* **Build System:** Vite.
* **Styling & Theme:** Tailwind CSS, next-themes (for dark/light mode toggle support), tailwindcss-animate.
* **Primitives & Design:** Shadcn/UI (Radix UI components: accordion, alert-dialog, progress, slider, select, switch, tabs, etc.).
* **Icons:** Lucide React icons.
* **State Management:** Custom React queries and local storage sync hook (`useFinancialData`).
* **Package Manager:** NPM / Bun support.

---

## 📂 Project Structure

```
hand-written-regonizer-ai/
├── public/                 # Static assets and icons
├── src/
│   ├── components/
│   │   └── financial/      # UI components (FinancialCard, TransactionForm, GoalsProgress, etc.)
│   ├── hooks/              # Custom hook handlers (useFinancialData.ts)
│   ├── lib/                # Utility modules (Tailwind merge utils.ts)
│   ├── pages/              # Main Route pages (Index.tsx, NotFound.tsx)
│   ├── types/              # TypeScript interface schemas (financial.ts)
│   ├── App.tsx             # Application router and layout
│   └── main.tsx            # Application entrypoint
├── components.json          # Shadcn CLI configuration file
├── tailwind.config.ts      # Tailwind styling customizations
└── tsconfig.json           # TypeScript configuration
```

---

## 🚀 Getting Started

To run the application locally on your computer:

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Lakshana-2007/hand-written-regonizer-ai.git
   cd hand-written-regonizer-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Fire up the local Vite development server:
   ```bash
   npm run dev
   ```

4. Open the development link (typically `http://localhost:5173`) in your browser to view the interface.
