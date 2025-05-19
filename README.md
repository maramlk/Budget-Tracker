# Budget Tracker CLI Application

A C-based budget management application designed for educational purposes in the **COMP 348 - Principles of Programming Languages** course at Concordia University.

## Features

- **Display All Entries**: View all financial records in a structured table format.
- **Expense Distribution**: Analyze income vs. expense distribution with category breakdown.
- **Sort Entries**: Sort by ID, date, amount, or description.
- **Add Entries**: Add new income or expense records.
- **Modify Entries**: Update existing records.
- **Filter by Month**: Display records for a specific year and month.
- **Extra Credit Features**:
  - **Visual Expense Breakdown**: Console-based bar chart of needs, wants, and other expenses.
  - **Search by Amount Range**: Find transactions within a specified range.
  - **Undo Last Action**: Undo the most recent addition or modification.

## Usage

### Compilation
```bash
gcc -o budgetTracker main.c budget.c data.c ordering.c
