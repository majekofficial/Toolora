TOOLORA V1.1 (compact design)

Folder layout:
- index.html + one .html file per calculator
- source/ (design + logic master copies, used by Claude to rebuild pages; not needed on the live site)
- sitemap.xml, robots.txt -> for Google

Before going live:
1. Choose your domain, then replace YOUR-DOMAIN.com in every file (ask Claude to do it for you).
2. Upload this folder to a GitHub repository.
3. Connect the repository to Netlify (or Cloudflare Pages). Publish directory: root. No build command.
4. Add the custom domain and enable HTTPS.
5. Submit sitemap.xml in Google Search Console.

GPA/CGPA use a 5.0 scale: A=5, B=4, C=3, D=2, E=1, F=0.
Policy: no interest-based calculators (loans, mortgages, compound interest, etc.).

V1.3 FEATURES
- Instant results (no button), copy result, share link with numbers prefilled
- "How it's calculated" + worked example on every calculator
- Currency picker (saved on the visitor's device), dark mode, working Tools menu with search
- Empty ad slots (data-slot="below-tool" and "content") ready for AdSense
- Analytics: open source/app.js and put your Google Analytics ID in GA_ID (ask Claude to do this for you)

V1.4 (Part 1: Mathematics)
- New: Algebra Solver, Linear Equation, Quadratic Equation, Simultaneous Equations, Change the Subject, plus the Mathematics page (mathematics.html)
- Copy and Share are icons inside the result box. Share offers image, PDF, link and text
- source/math.js = algebra engine, source/solvers.js = screens, graphs and sharing

V1.5
- Fixed: the "solve for / subject" dropdown no longer types letters into the equation box
- Answers are typeset like a textbook (stacked fractions, square roots, boxed answer)
- "Show workings" button hides/shows the step-by-step; 2-equation systems use the multiply-and-subtract method

V1.6 (Part 2)
- New tools: Area, Volume, Slope, Calorie, Statistics, Permutation & Combination, Sequence, Logarithm, Exponent, Surd, Matrix, Inequality, Word Problem Solver
- source/tools2.js holds these tools; to add a tool, ask Claude

V1.7 (Part 3: Physics)
- New: 13 physics tools + Physics page (physics.html); dark mode now applies instantly on every page; contact email added
- source/physics.js holds the physics tools

V1.8 (Part 4)
- Pages now load shared files from the assets folder (much faster). To test on your computer, keep the whole folder together.
- New: install as an app (works after the site is on https), works offline for visited pages, favourites and recently used tools, report-a-mistake button
- See GO-LIVE-GUIDE.md for the launch steps
