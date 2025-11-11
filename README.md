## Step 1: Create a Codespace
1. Go to the **Code** button (the green `<> Code`) in your repository.  
2. Click **Create Codespace on main** in the Codespaces sidebar.  

---

## Step 2: Set up Ad-Free Branch
Once your Codespace loads and you see the terminal at the bottom:

```bash
git fetch --all
git checkout Ad-Free
pnpm i
pnpm start
```

- `git fetch --all` – Updates all branches.  
- `git checkout Ad-Free` – Switches to the ad-free version.  
- `pnpm i` – Installs all required dependencies.  
- `pnpm start` – Starts the application server.  

> **Tip:** If you run into port issues, prepend the PORT environment variable, e.g.:  
> `PORT=8080 pnpm start`  

---

## Step 3: Open the Ad-Free App
1. Go to the **Ports** tab in your Codespace.  
2. Hover over the **Forwarded Address** column.  
3. Click the 🌐 **Open in Browser** icon next to your port.  

You now have the app running **ad-free**

---

## Step 4: Reopening Later
Anytime you want to open the app again:  
1. Go to [GitHub Codespaces](https://github.com/codespaces)  
2. Open your saved Codespace  
3. Repeat **Step 3** to access the forwarded URL  

---
