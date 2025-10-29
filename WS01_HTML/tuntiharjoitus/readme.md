# 🧭 Task: Create a Simple `index.html` File and Subfolders in Each Main Folder

In this activity, you’ll create a consistent folder structure for your web project.  
Each main folder will contain:
- A simple `index.html` file  
- Two subfolders: `images` and `styles`

You’ll use **PowerShell** commands to automate the process.

---

## 🪟 Step-by-Step Instructions

### Step 1: Open PowerShell

1. Navigate to your project’s **root folder** (where all your main folders are located).  
2. Right-click the folder → **"Open in Terminal"** (or **PowerShell**).

2. **Run the following PowerShell command:**

   ```powershell
   Get-ChildItem -Directory | ForEach-Object { @"
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>$($_.Name)</title>
   </head>
   <body>
       <h1>$($_.Name)</h1>
   </body>
   </html>
   "@ | Out-File -FilePath "$($_.FullName)\index.html" -Encoding UTF8 }

### Step 2: Create Subfolders (`images` and `styles`)

Run this command in PowerShell:

```powershell
Get-ChildItem -Directory | ForEach-Object { 
    New-Item -Path "$($_.FullName)\images" -ItemType Directory -Force
    New-Item -Path "$($_.FullName)\styles" -ItemType Directory -Force
}