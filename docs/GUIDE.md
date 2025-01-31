# ExpressGen Guide

## 1. Installation

```bash
# Method 1: Direct download
curl -o /usr/local/bin/expressgen https://raw.githubusercontent.com/<your-username>/expressgen/main/bin/expressgen
chmod +x /usr/local/bin/expressgen

# Method 2: Clone repository
git clone https://github.com/<your-username>/expressgen.git
cd expressgen
sudo ln -s $PWD/bin/expressgen /usr/local/bin/expressgen
```

## 2. Basic Usage

```bash
expressgen my-project
cd my-project
npm start
```

## 3. Project Structure

```
my-project/
├── public/
│   ├── css/styles.css    # Modern CSS reset
│   └── js/scripts.js     # Empty starter file
├── views/
│   ├── index.ejs         # Main template
│   ├── 404.ejs          # Error page
│   └── error.ejs        # Server error template
└── index.js             # Preconfigured Express server
```

## 4. Customization

Edit these files after generation:

- `public/css/styles.css` - Add custom styles
- `views/*.ejs` - Modify templates
- `index.js` - Add routes/middleware
