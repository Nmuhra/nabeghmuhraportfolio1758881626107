# Nabegh Muhra - Portfolio Website

This is a React-based portfolio website generated automatically from your CV data.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation and Running

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Start the development server:**

   ```bash
   npm start
   ```

3. **Open your browser:**
   The app will automatically open at [http://localhost:3000](http://localhost:3000)

### Building for Production

To create a production build:

```bash
npm run build
```

This creates a `build` folder with optimized files ready for deployment.

### Deployment Options

#### GitHub Pages

This portfolio is automatically deployed to GitHub Pages using GitHub Actions. The deployment workflow is configured in `.github/workflows/deploy.yml` and will automatically build and deploy your portfolio whenever you push changes to the main branch.

#### Netlify

1. Drag and drop the `build` folder to [Netlify](https://netlify.com)
2. Or connect your GitHub repository for automatic deployments

#### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel` in your project directory

## Customization

### Updating Your Information

Edit the file `src/data/portfolioData.js` to update your personal information, skills, experience, and projects.

### Styling

The main styles are in `public/index.html`. You can modify the CSS to change colors, fonts, and layout.

### Adding New Sections

Modify `src/App.js` to add new sections or change the layout.

## Project Structure

```
portfolio-website/
├── public/
│   └── index.html          # Main HTML template
├── src/
│   ├── data/
│   │   └── portfolioData.js # Your personal data
│   ├── App.js              # Main React component
│   └── index.js            # Entry point
├── package.json            # Dependencies and scripts
└── README.md              # This file
```

## Support

If you need help customizing your portfolio or have questions about deployment, feel free to reach out!

---

Built with modern web technologies for professional portfolio creation.
