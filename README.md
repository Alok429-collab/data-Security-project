# Data Security Project 2

Simple project with a Python backend and a small frontend for a data security demo.

Structure
- backend/: Flask/simple Python server and helper scripts
- frontend/: static HTML/CSS/JS

How to push to GitHub

1. Install Git and (optionally) GitHub CLI `gh`.
2. Initialize and push:

   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/<username>/<repo>.git
   git branch -M main
   git push -u origin main

If you have `gh` installed and authenticated you can run:

   gh repo create <repo> --public --source=. --remote=origin --push
