
# 1️⃣ Initialize Git (if not already initialized)
git init


Option 1 — Change user for a single repository
git config user.name "Anas Ahmed"
git config user.email "anotheruser@example.com"

Option 2 — Change user globally (for all repositories)
git config --global user.name "Anas Ahmed"
git config --global user.email "anas@gmail.com"


# 2️⃣ Add all project files
git add .

# 3️⃣ Commit your changes
git commit -m "Initial commit"

# 4️⃣ Add your remote repository (replace with your actual GitHub repo link)
git remote add origin https://github.com/USERNAME/REPOSITORY-NAME.git

# 5️⃣ Push your code to GitHub
git push -u origin main






Add, Commit, and Push

git add .
git commit -m "Initial commit"
git push -u origin main
