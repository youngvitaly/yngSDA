<div align="center">
  <img src="icon.png" width="100" height="100" />
<h1>yngSDA (Steam Desktop Authenticator)</h1>
  <p><b>A modern, lightweight, and secure desktop authenticator for Steam.</b></p>

  [![Version](https://img.shields.io/badge/version-v0.1--beta-blue.svg)](#)
  [![OS](https://img.shields.io/badge/os-Windows_10%2B-lightgrey.svg)](#)
  [![License](https://img.shields.io/badge/license-All_Rights_Reserved-red.svg)](#)
</div>

---

## 📥 Download & Install
Unlike older authenticators, **yngSDA is completely standalone**. You do NOT need to install any .NET frameworks or extra software.

1. Go to the [**Releases Page**](https://github.com/youngvitaly/yngSDA/releases/latest).
2. Download the latest `yngSDA_vX.X-beta.zip` file.
3. Extract it to a **safe and permanent** folder on your PC.
4. Run `yngSDA.exe`.

---

## ⚠️ CRITICAL WARNINGS (READ BEFORE USE)

> 🛑 **BACKUP YOUR `maFiles` AND R-CODE**
> If you lose your `maFiles` folder or forget your PIN, AND you didn't save your Revocation Code (R-Code), **you will lose access to your Steam account.** Always make backups of your `maFiles` folder and write down the `R-Code` (e.g., R12345) somewhere offline.

> 🛑 **ACCOUNT SECURITY**
> Using a desktop authenticator inherently bypasses the physical separation of 2FA. If your PC is infected with malware, attackers can steal your `maFiles` and your Steam items. **Use this application at your own risk.** We highly recommend using a strong PIN inside the app.

> 🛑 **BEWARE OF SCAMS**
> Never download yngSDA from YouTube links, Discord, or unknown websites. **The ONLY official and safe source is this GitHub repository.**

---

## ✨ Features
* **Modern UI:** Clean, responsive, and easy to navigate.
* **Account Import:** Seamlessly drop your existing `.maFile` backups into the `maFiles` folder to load them instantly.
* **Trade & Market Confirmations:** View, accept, or cancel your pending Steam confirmations directly from the app.
* **AES-256 Security:** Your local data is encrypted using industry-standard AES-256 encryption protected by your custom PIN.
* **Portable:** Runs out of the box with zero dependencies.

---

## ⚙️ Setup Instructions

1. **Launch the App:** Open `yngSDA.exe`.
2. **Set a PIN:** On your first launch, you will be prompted to create a Master PIN. This encrypts your session and `maFiles`. Do not forget it!
3. **Add an Account:**
   * **Import (Recommended):** If you already have `.maFile` backups from the original SDA or other tools, place them in the newly created `maFiles` folder next to the `.exe` and restart the app.
   * **Link New Account (BETA):** Click the button to link a new Steam account via credentials and SMS. *(Note: Due to recent strict Steam API limits, fresh account binding is currently in Beta and may occasionally be rejected by Steam).*
4. **Confirmations:** Select your account and navigate to the Confirmations tab to manage your trades.

---

## 🛠️ Troubleshooting

* **Confirmations list is blank or failing to load:**
  * Wait a few seconds and try refreshing.
  * If the issue persists, your session token may have expired. You may need to re-authenticate the account.
* **"Steam rejected this phone number" / Status 2 Error:**
  * This is a known Steam API rate-limit for new bindings. Try again later, use a different phone number, or use an existing `.maFile`.

---
*Disclaimer: This project is run by independent developers and is not affiliated with, endorsed by, or connected to Valve Corporation or Steam. The software is provided "as is" with no warranties.*
