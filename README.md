# Simple To-Do List

A clean, modern to-do list web application built with vanilla HTML, CSS, and JavaScript. Features persistent storage and a beautiful gradient design.

## Features

- **Add Tasks** - Quickly add new tasks with keyboard support
- **Mark Complete** - Check off tasks as you complete them
- **Delete Tasks** - Remove tasks you no longer need
- **Persistent Storage** - Tasks are automatically saved to browser localStorage
- **Task Counter** - Track your progress with a completion counter
- **Responsive Design** - Works beautifully on all screen sizes
- **No Dependencies** - Pure HTML/CSS/JS with no external libraries

## Getting Started

### Local Development

Simply open `index.html` in your web browser:

```bash
open index.html
```

Or double-click the file in your file explorer.

### Deploy to Vercel

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin your-repo-url
   git push -u origin main
   ```

2. **Deploy to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New Project"
   - Import your GitHub repository
   - Vercel will auto-detect the settings
   - Click "Deploy"

Your app will be live at `your-project.vercel.app`

## Project Structure

```
claude/to-do-list/
├── index.html          # Main application file
├── requirements.md     # Project requirements documentation
├── README.md          # This file
├── .gitignore         # Git ignore rules
└── vercel.json        # Vercel configuration
```

## Technologies Used

- HTML5
- CSS3 (with animations and gradients)
- Vanilla JavaScript (ES6+)
- localStorage API

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## License

Free to use and modify as needed.
