
# Shetue Rent Dashboard

A mobile-first, bilingual dashboard for rent tracking, KPI widgets, Bengali SOP viewer, Workspace SSO, and Firebase-powered automation.

## 🔗 Live Site
[https://dashboard.shetue.net](https://dashboard.shetue.net)

## 🚀 Tech Stack
- React (Frontend)
- Go (Backend API)
- Firebase Hosting + Firestore + Functions
- Google Sheets Integration
- Workspace SSO (Owner login)
- GitHub Actions (CI/CD)

## 📦 Features
- 📊 KPI widgets for rent collection and ROI
- 📤 CSV export and vacancy alerts
- 📚 Bengali SOP viewer for team training
- 🔐 Workspace SSO for secure owner access
- 📈 Gemini-powered summaries (optional)

## 🛠️ Firebase Setup
1. Create Firebase project: `shetue-rent-dashboard`
2. Enable Hosting, Firestore, Functions, Authentication
3. Map custom domain: `dashboard.shetue.net`
4. Enable Google sign-in (Workspace SSO)

## 🔄 GitHub Deployment (CI/CD)
Firebase auto-deploys on every push to `main` via GitHub Actions.

### 🔐 Secrets Required
- `FIREBASE_SERVICE_ACCOUNT`: JSON key from Firebase Console

### 📁 Workflow File
`.github/workflows/firebase-hosting.yml` handles build and deploy.

## 📂 Folder Structure
/src /components /pages /sop-viewer /functions index.js /firebase.json /.firebaserc

## 🧪 Local Development
```bash
npm install
npm run dev
Deploy Manually

firebase deploy



