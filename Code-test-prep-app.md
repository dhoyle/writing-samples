## What I Learned Building and Deploying a Next.js App with AI Assistance

---

### Opening

I built a small interview code test app using Next.js, Supabase, and Vercel to learn the modern frontend stack and explore how AI can accelerate real product development.

The goal wasn’t to build something perfect. It was to build something real with:

- Authentication
- Data persistence
- Multiple user flows
- Deployment to production

Then evaluate whether the idea and the workflow actually held up.

---

### The Stack: Why I Chose It

I intentionally chose a modern stack I wasn’t deeply familiar with:

- **Next.js (App Router)** for structure and routing
- **Vercel** for frictionless deployment
- **Supabase** for auth and database

This combination reflects a growing pattern: front-end-heavy applications with minimal custom backend code.

What stood out immediately:
- Deployment is no longer a “phase”—it’s part of development
- You can go from idea to a live app in hours, not days
- The complexity shifts from infrastructure to structure

---

### Building the App

The app itself is simple:
- SQL and Python crash courses
- Warmup questions (no timer)
- Timed tests (simulated pressure)

The interesting part wasn’t the feature set -- it was the implementation.

Key challenges:
- Structuring routes with the App Router
- Managing state across interactive flows
- Designing a clean separation between public and authenticated pages
- Avoiding subtle React issues (like duplicate keys in dynamic lists)

---

### Where AI Helped

AI dramatically accelerated development in specific areas:

- Generating component scaffolding
- Debugging runtime errors
- Creating structured question datasets
- Explaining unfamiliar framework patterns

Instead of searching and stitching together docs, I could iterate conversationally.

---

### Where AI Didn’t Help (and Why That Matters)

AI did not replace decision-making.

It struggled with:
- Architectural tradeoffs
- UI/UX clarity
- Knowing when something was “good enough”
- Avoiding over-engineering

For example, fixing a duplicate React key issue required understanding *why* keys matter—not just applying a patch.

This reinforced an important pattern:
> AI accelerates execution, but humans still define direction and quality.

---

### Deployment with Vercel

Vercel removed almost all friction from deployment:

- Connect GitHub repo
- Set environment variables
- Click Deploy

Every push automatically created a new deployment.

This changes how you think about shipping:
- You don’t “prepare” for deployment
- You deploy constantly

---

### Product Reality Check

After building the MVP, I evaluated the market.

Platforms such as DataLemur and W3Schools already provide:
- Large question banks
- Established trust
- Broader coverage

My version was simpler and faster, but not differentiated enough.

So I made a decision:
> Stop building the product, and focus on what I learned from building it.

---

### What This Project Demonstrates

This project is less about the app itself and more about the process:

- I can learn and apply a modern stack quickly
- I can ship a real, working product
- I can use AI as a tool—not a crutch
- I can evaluate an idea and change direction based on evidence
- I can explain all of this clearly

---

### Closing

The most valuable outcome wasn’t the product.

It was understanding how modern tools—especially AI and platforms like Vercel—change the speed, structure, and expectations of building software.

That shift is what I’m most interested in exploring and writing about.