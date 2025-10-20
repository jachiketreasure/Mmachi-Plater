# MMACHI PLATTER - Restaurant Website

A responsive restaurant website built with HTML, CSS, JavaScript, and Bootstrap.

## Deployment Instructions

### For Render.com:

1. **Connect your GitHub repository** to Render
2. **Create a new Static Site** (not Web Service)
3. **Configure the following settings:**
   - **Build Command:** `echo "Static site - no build needed"`
   - **Publish Directory:** `public`
   - **Root Directory:** Leave empty
4. **Deploy**

The files are now in the `public` folder, which is the standard convention for static sites.

## Project Structure

```
├── public/
│   ├── index.html          # Main HTML file
│   ├── assets/
│   │   ├── css/           # Compiled CSS
│   │   ├── js/            # JavaScript files
│   │   ├── images/        # Gallery images
│   │   ├── imgs/          # Other images
│   │   └── vendors/       # Third-party libraries
│   └── _redirects         # SPA routing config
├── render.yaml            # Render deployment config
└── README.md              # This file
```

## Features

- Responsive design
- Table reservation system
- Availability checking
- Image gallery
- Contact information
- Mobile-friendly navigation
