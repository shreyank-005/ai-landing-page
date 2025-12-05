Prompt Engineering Assignment – Summary
Tools Used:
AI Model: ChatGPT (GPT-4o / GPT-4 model)
Framework: Tailwind CSS (via CDN)
Hosting: Netlify
Recording: Loom/Vidyard
1. Prompt Strategy My approach was to use a "Meta-Prompt" technique. Instead of asking for a website all at once, I first established a "Master Rule" prompt. This set the constraints:
Tech Stack: HTML5 + Tailwind CSS (No external CSS files).
Responsiveness: Mobile-first design was mandatory.
Design Style: Modern, clean, SaaS-oriented aesthetic.
By setting these global rules first, I ensured that every subsequent section (Navbar, Hero, etc.) was visually consistent without needing to repeat the design rules every time.
2. Execution Process I generated the website in modular blocks:
Navbar: Focus on responsive toggle functionality.
Hero Section: Focus on visual hierarchy and immediate impact.
Features: Used Grid layout for responsiveness.
Contact: Added form validation attributes.
Footer: Clean navigation links.
Finally, I used a "Combiner Prompt" to assemble these blocks into a single valid index.html file to ensure the structure was correct and the scripts were placed properly.
3. Challenges & Solutions
Challenge: The mobile menu button often requires complex JavaScript.
Solution: I specifically prompted for "Vanilla JavaScript only" to keep the code lightweight and avoid React/Vue dependencies for a simple landing page.
Challenge: Ensuring consistent padding across sections.
Solution: The Master Meta-Prompt enforced Tailwind utility classes like py-20 and max-w-7xl to maintain alignment.
4. Final Prompts Used (See the attached video for the live generation workflow).
Master Meta-Prompt: "You are an expert Front-End Developer... Output Production-ready HTML5... Styled exclusively using Tailwind CSS..."
(Note: I have used the specific section prompts as demonstrated in the screen recording)

