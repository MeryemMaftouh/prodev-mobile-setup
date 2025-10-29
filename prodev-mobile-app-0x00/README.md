# 📱 prodev-mobile-setup

## 🎯 Objective

Create a first mobile app using **Expo Router**, understand its structure, and observe the effects of resetting the project.

---

## ⚙️ Steps

1. **Navigate to project**

```bash
   cd prodev-mobile-setup
```

2. **Initialize Expo project**

```bash
npx create-expo-app@latest .
```

3. **Edit Home Screen**

Open app/(tabs)/index.tsx

Replace:

```bash
 <ThemedText type="title">Welcome!</ThemedText>
```

with:

```bash
 <ThemedText type="title">First App Created</ThemedText>
```

4. **Run the App**

```bash
npx expo start
```

Scan the QR code with Expo Go (Android) or Camera (iOS).

5. **Reset the Project**

Stop the server (Ctrl + C)

Run:

```bash
npm run reset-project
```

When prompted, choose Y to move old files into /app-example.

🧾 Observations
The script moved existing folders (app, components, etc.) to /app-example/.

A fresh /app folder was created with new starter files.

This keeps a backup while resetting the environment.
