# Desi Rush - India Survival V1 🇮🇳

Android Game - Open World Auto Survival

**Desi Rush V1** ek desi style survival game hai jisme player ko India ke map me survive karna hai.

## 🎮 Features
- Open World Map
- Desi Characters & Vehicles
- Offline No Login - Direct Play
- Smooth Controls
- Android APK Ready

## 📦 Project Structure
- `DesiRush_V1_Final_Release_Package.zip` - Main Unity Project
- `.github/workflows/get-license.yml` - Generate Unity License (.alf)
- `.github/workflows/main.yml` - GitHub Actions for Android APK Build

## 🔨 How to Build APK via GitHub (NEW Method)

### STEP 1 - Unity License (.alf) Generate karo:
1. Go to `Actions` > `Get Unity License` > `Run workflow`
2. Workflow complete hone ke baad neeche `Artifacts` me se `Unity-Manual-Activation-File` download karo - isme `.alf` file hogi

### STEP 2 - .ulf License banao:
1. Go to https://license.unity3d.com/manual
2. `.alf` file upload karo
3. Unity tumhe `.ulf` file dega - use download karo
4. `.ulf` file ko Notepad me open karo - pura text COPY karo

### STEP 3 - GitHub Secret me daalo:
1. Go to `Settings` > `Secrets and variables` > `Actions`
2. `New repository secret` dabao
3. Name: `UNITY_LICENSE`
4. Value: Jo .ulf ka text copy kiya tha wo PASTE karo
5. `Add secret` dabao

### STEP 4 - APK Build karo:
1. Go to `Actions` > `Build Android APK` > `Run workflow`
2. 15-20 min me APK build hoga
3. Neeche `Artifacts` me se `DesiRush-APK` download karo

## 👨‍💻 Developer
mysunilgupta-tech

## 📄 Version
V1 Final Release - 2026

Made with ❤️ in India
