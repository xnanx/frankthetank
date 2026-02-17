# Frank's Personal Website

A clean, responsive personal website hosted on GitHub Pages.

## 📁 Project Structure

```
.
├── index.html      # Main HTML file
├── styles.css      # Styling and responsive design
├── README.md       # This file
└── .gitignore      # Git ignore rules
```

## 🚀 Deployment on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Create a new repository named `frankthetank` (or any name you prefer)
3. Choose "Public" (required for free GitHub Pages)

### Step 2: Push Your Code to GitHub

```bash
# Navigate to your project directory
cd /Users/franwang/mine/frankthetank

# Initialize git (if not already initialized)
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: personal website"

# Add remote repository
git remote add origin https://github.com/YOUR_USERNAME/frankthetank.git

# Push to GitHub (main branch)
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages** (in the left sidebar)
3. Under "Source", select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Click **Save**
5. GitHub will show your site URL (usually `https://username.github.io/frankthetank`)

### Step 4: Connect Custom Domain (Optional)

To use your custom domain `frankthetank.top`:

1. In Repository Settings → Pages, under "Custom domain", enter: `frankthetank.top`
2. Click **Save**
3. Update your domain registrar's DNS settings:
   - Add these DNS records:
     ```
     A record: 185.199.108.153
     A record: 185.199.109.153
     A record: 185.199.110.153
     A record: 185.199.111.153
     ```
   - Or add a CNAME record pointing to: `username.github.io`

4. Wait for DNS propagation (5 minutes to 48 hours)
5. Ensure "Enforce HTTPS" is checked in GitHub Pages settings

## 📱 Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ No dependencies - pure HTML/CSS
- ✅ Fast loading
- ✅ SEO friendly
- ✅ Customizable

## 🎨 Customization

Edit `index.html` to:
- Change name and tagline
- Update your bio
- Add/remove social links
- Modify contact information

Edit `styles.css` to:
- Change colors (see `:root` section)
- Adjust fonts and sizes
- Modify spacing and layout

## 📝 License

Feel free to use this as a template for your own personal website!
