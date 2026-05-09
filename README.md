# 🏦 Meezan Banking System (ATM Simulator)

Yeh ek C++ based console application hai jo ek real-life ATM machine ke basic functions ko simulate karti hai. Is project mein user PIN verification ke baad balance check, deposit, withdraw aur fund transfer jaise kaam asani se kar sakta hai.

---

# ✨ Features

- **Multi-Account Support:** 3 different accounts (`11111`, `22222`, `33333`) ke liye alag data handling.
- **Security:** Har account ke liye unique PIN code verification.

## Banking Operations

- 💰 **Check Balance:** Current available cash dekhna.
- 📥 **Deposit:** Account mein paise jama karna.
- 📤 **Withdraw:** Account se paise nikalna (balance check ke saath).
- 💸 **Transfer:** Ek account se doosre account mein paise bhejna.

- **Receipt Generation:** Har transaction ke baad ek clean receipt display hoti hai.

---

# 🛠️ Tech Stack

- **Language:** C++
- **Libraries:** `iostream`, `string`, `cmath`
- **Platform:** Windows (uses `system("cls")` for UI cleanup)

---

# 🚀 How to Run

## 1. Compile

Aapke paas GCC compiler hona chahiye. Terminal mein ye command likhein:

```bash
g++ main.cpp -o MeezanATM
```

## 2. Run

```bash
./MeezanATM
```

---

# 🔐 Default Credentials (Testing)

Aap in accounts ko testing ke liye use kar sakte hain:

| Account Number | PIN Code | Initial Balance |
|----------------|----------|-----------------|
| 11111 | 1111 | 5,000 |
| 22222 | 2222 | 10,000 |
| 33333 | 3333 | 15,000 |

---

# 📂 Logic Flow

1. **Login:** User apna Account Number aur PIN enter karta hai.
2. **Verification:** System check karta hai ke credentials sahi hain ya nahi.
3. **Menu:** Verification ke baad user ko 4 options milte hain:
   - Balance
   - Deposit
   - Withdraw
   - Transfer
4. **Processing:** User ki choice ke mutabiq balance update hota hai aur receipt display hoti hai.
