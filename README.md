# 🏦 Meezan Banking System (ATM Simulator)

A C++ based console application that simulates the basic functions of a real-life ATM machine. In this project, users can easily perform operations such as balance checking, deposit, withdrawal, and fund transfer after PIN verification.

---

# ✨ Features

- **Multi-Account Support:** Separate data handling for 3 different accounts (`11111`, `22222`, `33333`).
- **Security:** Unique PIN code verification for each account.

## Banking Operations

- 💰 **Check Balance:** View the currently available balance.
- 📥 **Deposit:** Add money to the account.
- 📤 **Withdraw:** Withdraw money from the account with balance verification.
- 💸 **Transfer:** Transfer money from one account to another.

- **Receipt Generation:** A clean receipt is displayed after every transaction.

---

# 🛠️ Tech Stack

- **Language:** C++
- **Libraries:** `iostream`, `string`, `cmath`
- **Platform:** Windows (uses `system("cls")` for UI cleanup)

---

# 🚀 How to Run

## 1. Compile

Make sure you have a GCC compiler installed. Open Terminal or Command Prompt and run:

```bash
g++ main.cpp -o MeezanATM
```

## 2. Run

```bash
./MeezanATM
```

---

# 🔐 Default Credentials (For Testing)

You can use the following accounts for testing purposes:

| Account Number | PIN Code | Initial Balance |
|----------------|----------|-----------------|
| 11111 | 1111 | 5,000 |
| 22222 | 2222 | 10,000 |
| 33333 | 3333 | 15,000 |

---

# 📂 Logic Flow

1. **Login:** The user enters the Account Number and PIN.
2. **Verification:** The system checks whether the credentials are correct or not.
3. **Menu:** After successful verification, the user gets 4 options:
   - Balance
   - Deposit
   - Withdraw
   - Transfer

4. **Processing:** According to the selected option, the balance is updated and a receipt is displayed.
