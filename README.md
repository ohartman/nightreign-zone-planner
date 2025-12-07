# Nightreign Zone Strategy Planner

A zone-based strategy planner for Elden Ring: Nightreign's procedurally generated 3-day expeditions.

## Features
- Select zones that spawned in your run
- Plan route order and priorities
- Track landmarks (bosses, loot, NPCs, shrines, hazards, objectives)
- Add strategy notes per zone
- Save and load complete plans
- Supports the 3-day/night cycle structure

## Quick Deploy to GitHub Pages

### First Time Setup

```bash
# Navigate to where you want to create the project
cd ~/projects

# Create a new directory
mkdir nightreign-zone-planner
cd nightreign-zone-planner

# Initialize git
git init

# Copy your files here (index.html and nightreign-zone-planner.jsx)
# Then add them to git
git add .
git commit -m "Initial commit - Nightreign Zone Planner"

# Create a new repository on GitHub (https://github.com/new)
# Then connect your local repo to GitHub (replace YOUR-USERNAME and REPO-NAME)
git remote add origin https://github.com/YOUR-USERNAME/nightreign-zone-planner.git
git branch -M main
git push -u origin main

# Enable GitHub Pages
# Go to: Settings → Pages → Source: Deploy from branch → Branch: main → Save
```

### Your site will be live at:
```
https://YOUR-USERNAME.github.io/nightreign-zone-planner/
```

---

## Update Existing Repository

```bash
# Make changes to your files, then:
git add .
git commit -m "Update planner with new features"
git push
```

---

## Local Development

Simply open `index.html` in your browser - no build process needed!

```bash
# Or use a simple HTTP server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

---

## Files
- `index.html` - Main HTML file
- `nightreign-zone-planner.jsx` - React component with all the app logic

---

## Copy-Paste Commands

### Create and Deploy (All in One)
```bash
mkdir nightreign-zone-planner && cd nightreign-zone-planner
git init
# (Copy your files here first)
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR-USERNAME/nightreign-zone-planner.git
git branch -M main
git push -u origin main
```

### Quick Update
```bash
git add .
git commit -m "Updates"
git push
```

### Clone Your Repo
```bash
git clone https://github.com/YOUR-USERNAME/nightreign-zone-planner.git
cd nightreign-zone-planner
```
