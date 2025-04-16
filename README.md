# 🔐 Lab 3: Password Cracking  
**IS 3513 – William Adams – 11/26/23**

## 🧪 Summary  
Used **Johnny (John the Ripper GUI)** and **Ophcrack** to crack sample password hashes from `shadow` and `sam/system` files.

## 🧰 Tools  
- Johnny  
- Ophcrack  
- Kali Linux VM  

## ✅ Results  
**Cracked with Johnny:**  
- `ccwhite`, `derf`, `secret`, `redbox` (all weak)  

**Cracked with Ophcrack:**  
- `N3verm0RE`, `Chrys4nth3mum`, `Heywood1211935`, `000000`  
- Strength ranged from very weak (`000000`) to strong (`Chrys4nth3mum`)

## 🔐 Takeaways  
- Strong passwords = length + mix of characters  
- MFA adds vital security (like UTSA’s Duo system)  
- IAM relies on password policy, complexity, and layered defense  

## 📚 Citations  
Gitten, 2023; Witts, 2021
