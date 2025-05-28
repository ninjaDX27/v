# v
Backend Developer's Vibe-Coding Guide
I’m a software engineer since 2017 and I'm looking to share some practical advice for non-developers or those new to coding to build projects quickly and simply.

Principles
1. Write Clear Prompts
Small, detailed prompts prevent errors, especially with LLMs.

Vague: “Add authentication.”

Clear: “Use Firebase Auth to add Google sign-in at src/pages/signup.js. Create a user document in Firestore’s users collection with email and UID. Reference ENVIRONMENT_VARIABLE_NAME from .env. Do not hardcode values from .env."

Clear prompts save cost and debugging time.

2. Delay Backend Development
I realize this is somewhat ironic for a backend developer to say but hear me our.
Backends add complexity. Avoid them early to save time and cost.

Use Next.js with Firebase for frontend-database communication.

Firebase’s free tier supports initial development.

Next.js server-side functions handle basic logic.

Warning: On Firebase’s paid tier, inefficient database queries (e.g., loops) can increase costs. Test queries and set budget alerts.

3. Make an MVP and Launch
Build an MVP with limited features to launch quickly. Personally, launching helped motivate me to continue development, unlike trying to perfect an app that nobody is using. User feedback also helps guid what to prioritize next.

Basic operations can run on frontend or Next.js server-side.

Optimize only when issues arise.

Choosing a Stack
Pick tools you’re comfortable with to maintain momentum. Familiarity speeds up development, while unfamiliar tools can slow you down. If you want to learn something new, ensure it aligns with your project goals.

What I use and why:

Editor/LLM: Cursor + Claude 3.7 Sonnet (effective with detailed prompts).

Auth: Firebase Authentication (simple, works with Firestore).

Database: Firestore (easy setup, integrates with Firebase).

Frontend: Next.js (large community, many examples).

Backend: Go (familiar to me). Newcomers: try Node.js for simplicity.

Cloud: GCP (familiar). Firebase’s free tier is great for starters.

Side Project
For anyone interested, compare16types.com is the latest app I built while vibe-coding. Feedback welcome.


Cimavotar
46

Baixovotar

23
Ir para os comentários


Partilhar
