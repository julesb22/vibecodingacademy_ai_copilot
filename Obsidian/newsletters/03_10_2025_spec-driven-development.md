**Vibe Coding Academy's news**

---

### **I'm open-sourcing my entire Claude Code setup** 🎁

---

Last week, I shared a step-by-step tutorial on setting up Claude Code agents and custom commands. But I didn't just write a guide—I made my entire setup publicly available so you can "steal" my agents and adapt them for your business. The tutorial covers creating agents from scratch, copying configurations, and customizing workflows for maximum productivity.

These agents automate newsletter writing, LinkedIn content, competitive research, growth experiments, and more. Whether you're building a SaaS product or managing a tech business, this setup can drastically impact your productivity. [Check it out here.](https://www.linkedin.com/posts/jules-boiteux_20month-just-gave-me-an-entire-company-activity-7378677596110360576-_9qy)

---

### **Speaking at EXA Paris next week** 🎤

---

I'm speaking at EXA next week—Paris's most famous startup incubator. The talk is "How to become a better product manager with Vibe Coding," and I'll share the stage with incredible AI thinkers. In a world where AI writes code, the barrier between ideation and implementation has collapsed. PMs who embrace Vibe Coding validate ideas faster and ship features without waiting on engineering.

I'll cover practical frameworks, real-world examples from Vibe Coding Academy, and actionable strategies you can implement immediately. Whether you're a PM curious about AI-assisted development or a founder looking to move faster, this talk will give you a roadmap. [Grab your spot here.](https://www.linkedin.com/posts/jules-boiteux_vibe-coding-paris-meetup-1-luma-activity-7373970220643749889-za_g)

---

### **Hackathon highlights from the Lovable Paris event** 🚀

---

Last weekend, I participated in a Lovable hackathon in Paris. For those unfamiliar, Lovable is a powerful AI-powered frontend development tool—and seeing first-timers use it was electric. Users shipped functional products within hours. We saw productivity tools and consumer apps emerge, proving you don't need to be a traditional developer to build real software anymore.

I met fellow vibe coders building businesses with these tools, plus complete beginners who left with their first deployed application. These moments remind me why I started Vibe Coding Academy—to democratize building and empower people to bring ideas to life. Keep an eye out for upcoming workshops. [Check out event highlights.](https://www.linkedin.com/posts/abouninecabale_meetup-ia-freemiumpro-activity-7379489076208623616-Ck-j)

---

## Bi-Weekly digest

---

Here are some news I shared that you may have missed:

**Prototyping is easier than ever. And more pointless than ever:** Most prototypes have zero connection to your actual product, creating unrealistic expectations. I explored three solutions: teaching your team Git and Claude Code, using Figma Make with a design system, and browser-based prototyping. [Read more.](https://www.linkedin.com/posts/jules-boiteux_prototyping-is-easier-than-ever-and-more-activity-7376535571688476672-L3lv)

**Companies are hunting Product Engineers, not traditional Product Managers:** Developer productivity jumped 2-10x with AI. Recruiters now want professionals who own the entire cycle—specs, prototyping, and shipping. This means fewer traditional PM jobs and more demand for hybrid technical-product skills. [Check it out.](https://www.linkedin.com/posts/jules-boiteux_been-discussing-with-recruiters-lately-activity-7377227945561497601--Tsu)

**Everyone's talking about Anthropic and OpenAI, but we're sleeping on Vercel:** Vercel raised $300M and built the most comprehensive AI product ecosystem—V0 design generation to AI SDK with observability to one-click deployment. What took weeks now ships in days. I broke down their entire stack. [Link here.](https://www.linkedin.com/posts/jules-boiteux_everyones-talking-about-anthropic-openai-activity-7379406037394669568-fb7Y)

---

# The Future of Building: AI Spec Driven Development

Here's a hard truth: the best developers in 2025 aren't necessarily writing the best code. They're writing the best specifications.

That would have sounded like heresy a few years. But stick with me for five minutes, and I'll show you why the methodology your tech team adopts right now will determine whether AI makes you 2x more productive or 10x more productive.

## The Great Developer Productivity Explosion (and Why Some Are Missing Out)

We're living through a wild transformation. I meet every month Product Manager, who tell me their developing team isn't coding anymore. At least not in the traditional sense. Instead, they're prompting AI agents to perform tasks, review pull requests, and architect entire systems. The results? Productivity increases ranging from 2x to 10x.

But here's where it gets interesting: two developers using the exact same AI tools can see vastly different productivity gains. One might plateau at 2x while another rockets to 10x. Why?

Most people assume it's prompt quality. Better prompts equals better output, right? Wrong.

The real differentiator isn't *how* you prompt AI, it's *what* you prompt it to create. And the 10x developers have figured out something crucial: they iterate extensively on specifications before they ever let AI touch a single line of code.

## What Exactly is Spec Driven Development?

Think of building software like constructing a house. In the old world, PMs were the architects and developers were the builders. PMs would sketch rough plans, developers would start hammering nails, and if something didn't fit, they'd adjust on the fly.

With AI, we're asking developers to become the architects—AI is now the builder. This is why you hear about the shift from a "developer mindset" to a "product engineering mindset." But if your team hands AI a rough sketch and says "build this," they'll get a rough house. The magic happens when your developers become exceptional architects.

Spec Driven Development means shifting where your team creates value—from code quality to specification quality. Instead of step-by-step prompting ("add a button here," "now make it blue," "actually, make it responsive"), your team prompts AI to create rigorous documentation first:

**The Four Pillars of Specs:**

1. **EPICs**: High-level features or initiatives (e.g., "User Authentication System")
2. **User Stories**: Specific scenarios from the user's perspective (e.g., "As a new user, I want to sign up with my email so I can access my personalized dashboard")
3. **Acceptance Criteria**: Concrete, testable conditions that define "done" (e.g., "Password must contain 8+ characters, 1 uppercase letter, 1 number")
4. **Technical Specifications**: Architecture decisions, API endpoints, data models, security considerations

Here's what this looks like in practice: Instead of having your developers prompt "create a login page," they first prompt AI to generate a complete specification document. This might include 15 user stories covering edge cases (What happens when passwords don't match? When the email is already registered? When the server times out?), detailed acceptance criteria for each story, API endpoint specifications, and even a QA checklist.

Only *then* does your team hand that specification to AI for implementation.

## Why This Methodology is Eating the World

Remember when mid-level developers looked at senior developers with 10 years more of experience and thought, "I'll get there eventually"? That gap is collapsing.

AI is democratizing technical implementation in ways we've never seen. Tasks that previously required specialized knowledge like setting up Redis Counter Cache, writing Terraform configurations, implementing OAuth2 flows are now accessible to anyone who can articulate what they need.

A mid-level developer with excellent specifications can now ship features that previously required a senior engineer. The code quality? Essentially identical, because AI is writing it in both cases.

This creates a fascinating shift: **since code implementation is accessible to everyone, the competitive advantage comes entirely from specification quality.**

At the feature level, the difference between a well-crafted feature and a badly implemented one boils down to how thoroughly you spec'd it out. Did you consider edge cases? Define error states? Specify loading behaviors? Plan for accessibility? A comprehensive spec catches these before AI writes a single line.

## Your Implementation Roadmap: From Theory to Practice

Alright, enough philosophy. Let's talk execution. Here's how your team can actually implement Spec Driven Development:

**Step 1: Have Your Team Create Specification Agents**

Your developers shouldn't manually write specs—that defeats the purpose. Instead, they should create AI agents whose sole job is transforming feature ideas into comprehensive specifications.

Input: "I need a user dashboard that shows analytics"

Output: A complete specification document with EPICs, user stories ("As a user, I want to see my engagement metrics from the last 30 days"), acceptance criteria ("Chart must display data points for each day," "Loading state appears within 200ms"), technical specs (API endpoints, data models), and QA checkpoints.

If your team is using Claude Code, I've shared a detailed tutorial on setting up custom agents. The key is creating a reusable template that consistently generates thorough specs.

**Step 2: Add Human Validation Checkpoints**

This is critical: you're not removing humans from the loop, you're elevating their role. After AI generates specs, your team reviews them. This is where product and technical expertise matters most.

Key questions to ask:
- Did AI miss any edge cases?
- Are the acceptance criteria actually testable?
- Does this align with our broader product vision?
- Are we creating technical debt?

**Step 3: Leverage Existing Frameworks**

Your team doesn't have to build this from scratch. Two powerful frameworks have emerged:

**The BMAD Method** (https://github.com/bmad-code-org/BMAD-METHOD) uses multiple AI agent roles (Analyst, Product Manager, Architect, Developer, and QA) to systematically plan features. It emphasizes agentic planning with context-engineered development, meaning each agent has specific context and responsibilities.

**GitHub Spec Kit** (https://github.com/github/spec-kit) provides a CLI and templates for a structured workflow: **Specify → Plan → Break into Tasks → Implement**. It includes built-in human checkpoints at each stage, preventing AI from running wild with half-baked ideas.

**Step 4: Set Up Parallel Execution**

Here's where productivity explodes: have your developers configure AI coding tools to work on multiple tasks simultaneously, just like a traditional development team where multiple engineers work in parallel.

Tools like **GitHub worktrees** create isolated working directories for different features, allowing multiple AI agents to implement separate specs at the same time. In Cursor, Claude Code, or Codex, your team can launch multiple agents in parallel—one implementing the authentication flow while another builds the dashboard analytics.

The key is treating AI agents like team members: give each one a complete spec and let them work independently. While Agent 1 implements Feature A, Agent 2 tackles Feature B, and your product team is already iterating on specs for Features C and D. The bottleneck shifts from implementation time to specification quality.

This parallel workflow is impossible with traditional coding but natural with Spec Driven Development.

## The Mindset Shift

The hardest part isn't learning new tools—it's the psychological shift your engineering team needs to make from "I am a code writer" to "I am a systems architect and specification designer."

For your developers, value no longer comes from knowing the perfect React pattern—AI knows that. It comes from understanding *what* to build, *why* to build it, and *how* it should behave with real users. The teams that thrive are those who know exactly which features to implement and how to define them with crystal clarity.
