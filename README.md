# Budget Calculator

## What It Does
A simple budget calculator web application that helps users track their income and expenses. Users can add income sources, track spending categories, and see their remaining budget in real-time.

## Live Demo
🔗 https://thriving-speculoos-a86aa2.netlify.app/

## Screenshots
<img width="1047" height="844" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/0daea28d-f762-4b9b-8fbf-08b67cea493e" />


## Tools Used
- **Bolt.new** - AI tool for generating React code
- **React** - Frontend framework
- **Tailwind CSS** - Styling
- **Vite** - Build tool
- **Netlify** - Deployment platform
- **GitHub** - Code repository



### Initial Build Prompt:
```
Build a simple budget calculator app with React and Tailwind CSS. 
Features: Input for income, add expense categories with amounts, 
show remaining budget with color coding (green if positive, red if negative), 
make it mobile responsive, use a clean modern design.
```

**Why it worked:** Very specific about features, mentioned exact technologies, and described the visual behavior.

### Styling Improvement Prompt:
```
Make the UI more spacious and modern. Add smooth transitions, 
use card layouts, improve button hover states, and add subtle shadows.
```

**Why it worked:** Specific about what to improve rather than just saying "make it better."

## What I Learned

### About AI Prompting:
- Being extremely specific gets much better results than vague requests
- Mentioning the exact tech stack (React, Tailwind) helps AI generate compatible code
- Describing user behavior and visual feedback makes the AI understand what you want
- Breaking features into small chunks works better than asking for everything at once

### About Deployment:
- Netlify Drop is incredibly easy - just drag and drop the `dist` folder
- The `dist` folder contains the built/compiled version of your app
- You need to build the project first before deploying (the build creates the `dist` folder)

### About GitHub:
- All code should be committed even if AI-generated
- Good README documentation is as important as the code itself
- GitHub repos are like portfolios - they show what you can build

## What Didn't Work

### Failed Attempts:
1. **Vercel deployment failed initially** - Got build errors related to import paths
2. **First prompt was too vague** - Said "make a calculator" and AI wasn't sure what type
3. **Tried to manually edit generated code** - Broke some functionality, learned to let AI fix its own code

### How I Fixed Them:
1. Switched to Netlify Drop which was much simpler
2. Rewrote prompt with specific features listed
3. Asked AI to debug by showing it the error message instead of manually editing

## Setup Instructions (Run Locally)

If you want to run this project on your computer:
```bash
# Clone the repository
git clone https://github.com/Vipingautam-tech/budgetcalculator.git

# Navigate to project folder
cd budgetcalculator

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## Known Limitations
- Data doesn't persist after page refresh (no database/localStorage)
- No user authentication
- Can't export budget reports
- Mobile layout could be more optimized for very small screens

## Future Improvements
- Add localStorage to save budget data
- Export budget as PDF
- Add charts/graphs to visualize spending
- Dark mode toggle
- Multiple budget categories with subcategories

---

**Built as part of Vibe Coding Assignment**  
Created using AI-powered development tools • December 2025
```

5. **IMPORTANT:** Replace `[Paste your Netlify URL here]` with your actual Netlify URL

6. **Click "Commit changes"** (green button at bottom)

