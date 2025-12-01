## GIT PUSH INSTRUCTIONS

### If Git is NOT installed:
1. Download from: https://git-scm.com/download/win
2. Install with default settings
3. Restart PowerShell/Terminal

### Once Git is installed:

```powershell
cd c:\Users\trezz\Desktop\icy-unblocked-games

# Configure Git (one-time)
git config --global user.name "Your Name"
git config --global user.email "your.email@gmail.com"

# Push to GitHub
git add .
git commit -m "Release: ICY UNBLOCKED - Best Unblocked Games Site"
git push origin main
```

### What happens next:
1. GitHub Actions automatically builds your site
2. Deploys to gh-pages branch
3. Live at: `https://YOUR_USERNAME.github.io/icy-unblocked-games/`
4. Takes 2-3 minutes

### Check deployment status:
- Go to your repo
- Click "Actions" tab
- See build progress in real-time
- Green checkmark = Success ✅

### All set! Your site is live!
