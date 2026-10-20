# CURSE RAT v3.0.0 🚀

**CURSE RAT** is a sophisticated, open-source Remote Administration Tool (RAT) designed for Android. It features a high-performance Node.js C2 server and a feature-rich Java-based Android client. This project is built for educational purposes and security research, demonstrating advanced networking, APK surgery, and real-time telemetry.

---

## 🎨 THOR Cyber Dashboard
The project features the **THOR Cyber Dashboard**, a high-fidelity SPA (Single Page Application) that provides:
- **3D Global Targeting**: Interactive globe centered on connected nodes.
- **Multi-Port Listener**: Manage multiple TCP listeners dynamically.
- **Real-Time Telemetry**: Live tracking of data rates (KB/s), packet counts, and system health.
- **Advanced Client Center**: Triple-pane command center for managing all active nodes.

## 🛠️ Key Features
- **Advanced Payload Builder**: Deep APK surgery (Package renaming, Manifest patching, Resource injection).
- **Live Surveillance**: Real-time Camera streaming (5 FPS hardware throttled) and Screen Sharing.
- **Data Management**: Interactive File Manager, SMS logs, Contacts, and Call logs.
- **Security Research Tools**: Keylogger, GPS tracking (Leaflet integration), and Device Telemetry.
- **Stability**: Optimized for Android 8.0 to 14 with robust foreground service persistence.

---

## 📋 Requirements
- **Server**: Node.js (v16+) & npm
- **Client Build**: Java 11 (JDK) & Android SDK
- **OS**: Linux (Recommended) or Windows

---

## 📸 Screenshots Gallery

<p align="center">
  <img src="assets/1_Main_Index.png" width="45%" alt="Main Dashboard">
  <img src="assets/4_Client_Control_Lab.png" width="45%" alt="Command Center">
</p>

<p align="center">
  <img src="assets/2_Apk_Build.png" width="45%" alt="Builder Interface">
  <img src="assets/3_Building_Apk.png" width="45%" alt="Build Process">
</p>

---

## 🚀 Installation

### 🐧 Linux (Recommended)
1. **Clone the repository**:
   ```bash
   git clone https://github.com/thorthehacker/Curse_RAT.git
   cd Curse_RAT
   ```
2. **Install Dependencies**:
   ```bash
   cd server && npm install
   ```
3. **Setup Environment**: Ensure `apktool`, `jarsigner`, and `zipalign` are in your PATH.
4. **Run Server**:
   ```bash
   node server.js or npm start
   ```

### 🪟 Windows
1. **Clone the repository**:
   ```powershell
   git clone https://github.com/thorthehacker/Curse_RAT.git
   cd Curse_RAT
   ```
2. **Install Dependencies**:
   ```powershell
   cd server; npm install
   ```
3. **Setup Environment**:
   - Install **Java 11 JDK** and add to Environment Variables.
   - Download **apktool.jar** and place it in the server folder or PATH.
   - Ensure `jarsigner` (from JDK) and `zipalign` (from Android SDK) are accessible.
4. **Run Server**:
   ```powershell
   node server.js
   ```

---

## 📂 Project Structure
- **/server**: Node.js C2 Server, Builder logic, and Web Dashboard.
- **/client**: Java source code for the Android application (Gradle project).
- **/output**: Location for generated/patched APKs.

---

## ⚖️ Disclaimer
This project is for **educational purposes only**. The authors are not responsible for any misuse of this tool. Use it only on devices you own or have explicit permission to test.

## 🙏 Credits
Special thanks to **AhMyth**, from whose project I referred and learned many concepts that made CURSE RAT possible.

---
**Keywords**: Android RAT, Remote Administration Tool, C2 Server, Node.js, Java Android, Malware Analysis, Security Research, APK Builder, RAT Dashboard.
