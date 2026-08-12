# Course Schedule & Module Planner — Beginner User Guide

Welcome to the **Course Schedule & Module Planner (v3.0 Multi-Course Edition)**! This interactive web application is designed for academic leaders, curriculum designers, and course managers to easily structure, schedule, map, and audit multi-year academic courses.

This guide will take you step-by-step from launching the application for the first time to creating custom multi-year curriculum plans, managing module widgets, conducting credit audits, and saving your workspace.

---

## 📖 Key Concepts

Before diving in, here are a few core concepts used throughout the app:

* **Course Offer Structures**:
  * **3-Year Course**: Standard 12 Terms (6 Semesters) structure including Sector Foundation, Core, and Specialisation modules.
  * **2-Year Direct Entry**: 8 Terms (4 Semesters) structure for direct-entry students, skipping foundation modules.
  * **Accelerated Pathway**: 9 Terms (5 Semesters) structure with Foundation in Terms 1–2, Preparatory modules in Term 3, Core in Terms 4–5, and Specialisation in Terms 6–9.
* **Multi-Course Workspace Tabs**: Manage multiple course structures simultaneously side-by-side using top navigation tabs.
* **Tab Display Name vs. Full Course Title**:
  * **Tab Display Name (Short Form)**: Short label used on the navigation tab bar (e.g. `3-Yr SD`, `2-Yr Direct`, `Accelerated SE`).
  * **Full Course Title**: Official full course title printed in the active course container and audit reports (e.g. `Higher Nitec in Software Development`).
* **6-Month Module Spanning**: 6-month modules visually span across 2 consecutive terms without merging cells, preserving independent term columns.

---

## 🚀 Step-by-Step Walkthrough

### Step 1: Setting Up Course Tabs & Workspace

1. **Creating a New Course Tab**:
   - Click the **`+ New Course Tab`** button on the top-right of the tab navigation bar.
   - Enter a **Tab Display Name (Short Form)** (e.g., `3-Yr SD`).
   - Enter the **Full Official Course Title** (e.g., `Higher Nitec in Software Development`).
   - Select your **Course Offer Structure** (`3-Year`, `2-Year`, or `Accelerated Pathway`).
   - Choose a **Starter Template** (Preset Template, Clone Current Active Tab, or Blank Plan).
   - Click **Create Course Tab**.

2. **Renaming & Switching Tabs**:
   - Click any tab to switch between course plans. Each tab has a distinct pastel theme color.
   - **Double-click** a tab title to edit its short tab name inline, then press **Enter**.
   - Click the **`×`** button on any tab to delete it (workspace requires at least 1 tab).

---

### Step 2: Configuring Course Header Metadata

Directly above the schedule table matrix is the **Active Course Metadata Bar**:

* **Effective Date**: Type the intake effect date (e.g., `With effect from Jan 2027`).
* **Course Title**: Edit the full official course title anytime without changing the short tab label.
* **College / Campus**: Specify the campus location (e.g., `College West`).
* **Term 1 Start Date**: Select the starting month and year (e.g., `Jan 2027`). All 12 term headers across the table will automatically calculate and display their exact calendar dates (e.g. `Term 1, Jan 2027`, `Term 2, Apr 2027`).

---

### Step 3: Adding & Editing Module Widgets

1. **Adding a New Module Widget**:
   - Click the **`+ Add Module Widget`** button in the active course toolbar.
   - Fill in the module details:
     * **Module Code**: e.g., `IC33002FP`
     * **Module Title**: e.g., `Operating Systems Essentials`
     * **Category / Selection**: Choose between `Sector Foundation`, `Preparatory Modules`, `Cluster Core`, `Specialisation`, `CDC`, `Elective`, `Life-skills`, `Sports`, or `Internship`.
     * **Assessment Type**: Select `Type A (Final Exam)`, `Type B (In-Course Assessment)`, or `General (Non-Exam)`.
     * **Credit Units**: Specify the credit value. *Non-credit or preparatory modules can be set to `0` credits.*
     * **Duration**: Select `3 Months (1 Term)` or `6 Months (2 Terms)`.
     * **Teaching Hours Breakdown**: Input **Theory Hours** and **Practical Hours**. Total Hours and weekly rate (`hrs/wk`) will auto-calculate.
     * **Start Term**: Select which term the module starts.
   - Click **Save Module**.

2. **Editing or Deleting a Module Widget**:
   - Click the **`Edit`** button on any module card in the table, or double-click the card.
   - Modify any fields or click **Delete Module** to remove it.

---

### Step 4: Interactive Schedule Grid Operations

* **Drag-and-Drop**: Click and hold any module widget card to drag it to another term column or row.
* **Row Routing**:
  * **Type A** modules sit in the `Type A Modules` row.
  * **Type B** modules sit in the `Type B Modules` row.
  * General/Non-Exam modules route to their category row (`CDC`, `Electives`, `Life Skills`, `Sports & Wellness`).
* **Weekly Workload Rate**: Each term column calculates the total weekly workload (`hrs/wk`). If workload exceeds your configured threshold (e.g., 28 hrs/wk), a warning tag is displayed.

---

### Step 5: Campus Classes & Term Remarks

1. **Classes in Campus Counter**:
   - Below the matrix grid, enter class counts per term for `HF3`, `HF2`, `WSD`, and `SCTP`. Term totals auto-sum in real-time.

2. **Multiline Term Remarks**:
   - Use the **Remark** row textareas at the bottom of each term column to add notes, exam schedules, or reminders. Textareas auto-expand as you type.

---

### Step 6: Certification Requirements & Credit Audit Engine

Scroll to the bottom card titled **Certification Requirements & Credit Audit Engine**:

* **Credit Audit Rows**: Automatically calculates cumulative scheduled credits for `Foundation`, `Core`, `Specialisation`, `LifeSkills`, `Sports`, `CDC`, and `Elective` categories.
* **Audit Status Badges**:
  * 🟢 **Green Badge**: Scheduled credits met or exceeded requirement.
  * 🔴 **Red Badge**: Scheduled credits fall short of requirement.
* **Custom Certification Titles**: Edit qualification titles directly in the audit table header (e.g., `Higher Nitec in Software Development`).

---

### Step 7: Saving, Exporting & Importing Workspace Data

1. **Automatic Auto-Save**: All changes auto-save instantly to your web browser's local storage (`localStorage`).
2. **Exporting Workspace Data**:
   - Click **`Export JSON`** at the far top-right corner.
   - Downloads a timestamped JSON file (e.g., `multi_course_planner_20260812_193000.json`) containing **all course tabs**, modules, settings, remarks, and audit targets.
3. **Importing Workspace Data**:
   - Click **`Import JSON`** at the top right corner.
   - Select an exported JSON file to restore your complete multi-course workspace.

---

## 💡 Summary of Frequently Used Action Buttons

| Button                    | Location         | Function                                                    |
| :------------------------ | :--------------- | :---------------------------------------------------------- |
| **`+ New Course Tab`**    | Tab Bar (Top)    | Adds a new tab for a 3-Year, 2-Year, or Accelerated course. |
| **`+ Add Module Widget`** | Metadata Bar     | Opens modal to create a new module widget.                  |
| **`Settings ⚙️`**          | Metadata Bar     | Opens sizing, font, padding, and layout display settings.   |
| **`Reset Preset`**        | Metadata Bar     | Resets current course tab back to standard default payload. |
| **`Export JSON`**         | Top Right Header | Downloads complete workspace JSON file.                     |
| **`Import JSON`**         | Top Right Header | Uploads JSON file to restore workspace tabs & data.         |
| **`Theme Toggle 🌙`**      | Top Right Header | Toggles between Dark Mode and Light Mode.                   |
| **`About ℹ️`**             | Top Right Header | Opens app overview, version info, and author credits.       |

---

*Built by Khiew Tzong Yong (ITE College West)*
