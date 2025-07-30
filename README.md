# garage-riviere
{
  "rewrites": [
    { "source": "/(.*)", "destination": "/index.html" }
  ]
}
cd garage-riviere
git init
git add .
git commit -m "Initial commit – Réception véhicule app"
git branch -M main
git remote add origin https://github.com/tomriviere/garage-riviere.git
git push -u origin main
