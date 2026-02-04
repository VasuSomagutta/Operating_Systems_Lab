1. Navigate to your project folder
cd "C:\path\to\your\project"



📘 2. Initialize a Git repository
git init

This creates a hidden .git folder and makes your project a local Git repo.



🧩 3. Add all project files
git add .

The . means “add everything in this folder”.



📝 4. Commit your files
git commit -m "Initial commit"



🌐 5. Create a repository on GitHub

Go to https://github.com/new

Enter a repository name (e.g., my-project)

Choose Public or Private

Don’t add a README if your local folder already has one.

Then, copy the repository’s URL — it looks like:

https://github.com/your-username/my-project.git



🔗 6. Add the remote GitHub repo
git remote add origin https://github.com/your-username/my-project.git



📤 7. Push your local repo to GitHub
git branch -M main
git push -u origin main

-u sets origin/main as the default for future pushes.



✅ 8. Verify your connection
git remote -v


You should see something like:

origin  https://github.com/your-username/my-project.git (fetch)
origin  https://github.com/your-username/my-project.git (push)

🧠 Common Follow-up Commands
Action	                            Command
Check status	                    git status
Add changed files	                git add .
Commit changes	                    git commit -m "Updated features"
Push changes	                    git push
Pull latest from GitHub	            git pull origin main
