# *💰 Finance Tracker*

A simple and interactive *Personal Finance Tracker* built using *Python* and *Tkinter* to help you manage your income, expenses, and balance in one place.

## *🚀 Features*

- 📥 Add income entries  
- 📤 Add expense entries  
- 📊 Real-time balance tracking  
- 🧾 Summary view of all transactions within a data range  
- 🖱 Easy-to-use GUI with Tkinter
- Summary of total income, expenses, and savings
- Optional visualization of trends using Matplotlib



## *🖼 Screenshot*



## *🛠 Installation*

1. *Clone the repository*
   ```bash
   git clone https://github.com/Debdotta26/Finance-Tracker.git
   cd Finance-Tracker
   ## *📂 Project Structure*

Finance-Tracker/ │
├── main.py   # Main application file (GUI + logic)
├── transactions.csv  # CSV file to store transaction data 
├── README.md          # Project documentation
└── requirements.txt   # (Optional) Required Python libraries



## 🛠️ Requirements

- **Python** 3.x  
- **Required Libraries**:  
  - `pandas`  
  - `matplotlib`

Install dependencies using:

```bash
pip install pandas matplotlib
```

---

## 📋 Features

This program allows you to manage and visualize transactions via a simple menu:

1. **Add a transaction**  
2. **View transactions in a date range**  
3. **Exit**

---


## 📝 Data Format (CSV)

Transactions are stored in a CSV file with the following structure:

| Field       | Description                          |
|-------------|--------------------------------------|
| `date`      | Date of transaction (`dd-mm-yyyy`)   |
| `amount`    | Positive float (e.g., `250.75`)      |
| `category`  | `"Income"` or `"Expense"`            |
| `description` | Optional short description (text)  |

---



## *🔧 Technologies Used*

- *Python* – Core programming language
- *Tkinter* – For creating the GUI
- *CSV module* – To store and manage data in .csv format

## *📌 Usage Tips*

- Use the GUI to:
  - Add *income* entries
  - Add *expense* entries
  - View the *current balance*
- All data is saved in transactions.csv
- To reset your data, you can manually clear the contents of transactions.csv


## *📈 Future Improvements*

- 📊 *Charts and graphs* using matplotlib or plotly
- 📁 *Categorization* of transactions (e.g., Food, Rent, Salary)
- 📤 *Export to PDF* for monthly summaries
- 🔐 *Login functionality* for multiple users


## *🤝 Contributing*

Contributions are welcome!

1. *Fork* this repository
2. Create your *feature branch*  
   ```bash
   git checkout -b feature-name

3. Commit your changes

    git commit -m "Add some feature"


4. Push to the branch

git push origin feature-name


5. Open a Pull Request




---

## 📄 License

This project is licensed under the **MIT License**.  

---

## 🙌 Author

Built with ❤️ by **Debdotta**  
Feel free to **fork**, **use**, and **contribute** to this project!

---

