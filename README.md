# Create-new-APp-in-React-Nativ
Using these commond setup or create new app in react natve app 
🔁 Step 1: Delete Broken Project
Delete the broken MyApp folder from Desktop or use PowerShell:

powershell
Copy code
Remove-Item -Recurse -Force "C:\Users\tushar prajapati\MyApp"
✅ Step 2: Install the Latest Working CLI
Run this to install the official CLI:

bash
Copy code
npm install -g @react-native-community/cli
🆕 Step 3: Create a Clean React Native App
bash
Copy code
npx @react-native-community/cli init MyApp --version 0.73.6
💡 Make sure your internet is stable — this command downloads ~200 MB.

📁 Step 4: Check Folder Contents
Go to the new project:

bash
Copy code
cd "C:\Users\tushar prajapati\MyApp"
Now run:

bash
Copy code
dir
You MUST see:

plaintext
Copy code
android/
ios/
App.js
babel.config.js
metro.config.js
package.json
node_modules/
💻 Step 5: Open in VS Code
bash
Copy code
code .
If code command doesn't work, open VS Code manually and go to File > Open Folder.

💥 If This Still Fails…
🟠 Last Resort: Use Pre-Built Starter Project (Download)
Let me know — I will:

Create the project on my end.

Zip it.

Give you a Google Drive link to download and run directly.

