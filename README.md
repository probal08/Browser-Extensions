# Task 7 – Identify and Remove Suspicious Browser Extensions

## 🎯 Objective
To review all installed browser extensions, inspect their permissions, identify any suspicious or unnecessary ones, and remove them to improve security and privacy.

---

## 🛠 Tools Used
- Google Chrome Browser  
- Chrome Extensions Manager (`chrome://extensions`)  
- Built-in screenshot tool  

---

## 📝 Steps Performed

### 1️⃣ Viewed Installed Extensions
I opened Google Chrome and checked all installed extensions:


Screenshot before review:  
➡️ `screenshots/01_extensions_before.png`

At this stage, I had:
- **Google Docs Offline**  
- **K7 WebProtection**

---

### 2️⃣ Reviewed Extension Details

I inspected the detailed permissions and behavior of each extension using the **Details** page.

#### ✔ Safe Extension Details: Google Docs Offline  
- Installed by default  
- Minimal permissions  
- Only accesses Docs and Drive  
- Safe and required  
Screenshot:  
➡️ `screenshots/02_extension_details_google_docs.png`

#### ❌ Suspicious Extension Details: K7 WebProtection  
- Installed by K7 Antivirus (not by me)  
- Permissions included:  
  - Read browsing history  
  - Read and modify data on all websites  
- Not required for browser usage  
- High privacy risk  
Screenshot:  
➡️ `screenshots/03_extension_details_k7.png`

---

### 3️⃣ Removed Suspicious Extension

I removed **K7 WebProtection** because:
- It had access to all browsing activity  
- It was unnecessary  
- It increased privacy and security risks  

---

### 4️⃣ Confirmed Cleanup

After removal, only **Google Docs Offline** remained.

Screenshot after cleanup:  
➡️ `screenshots/04_extensions_after.png`

---

## 🔐 Findings

### ✔ Safe Extension (Kept)
**Google Docs Offline**  
- Trusted, official Google extension  
- Useful for offline editing  
- Minimal permissions  
- No security concerns  

### ❌ Removed Extension
**K7 WebProtection**  
- Unnecessary  
- Installed automatically by antivirus  
- Excessive permissions  
- Potential privacy risk  

---

## 🧠 What I Learned
- Browser extensions can access sensitive user data  
- Some extensions request broad permissions unnecessarily  
- Antivirus-installed extensions are not always safe  
- Best practices include:  
  - Reviewing permissions  
  - Checking the extension source  
  - Removing all non-essential extensions  

---

## 📸 Screenshots Included

screenshots/01_extensions_before.png
screenshots/02_extension_details_google_docs.png
screenshots/03_extension_details_k7.png
screenshots/04_extensions_after.png


---

## 📁 Project Structure

Task-7-Browser-Extensions/
├── README.md
├── extensions_before.txt
├── extensions_after.txt
└── screenshots/
├── 01_extensions_before.png
├── 02_extension_details_google_docs.png
├── 03_extension_details_k7.png
└── 04_extensions_after.png


---

## ✅ Conclusion
All installed browser extensions were reviewed. A suspicious one (K7 WebProtection) was identified and removed.  
The browser is now secure with only trusted extensions installed.

