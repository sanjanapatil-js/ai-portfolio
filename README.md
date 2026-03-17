# 👋 Hey, I'm Sanjana Patil

**Frontend Developer | Vibe-Coder | React.js Enthusiast**

Welcome to my AI Portfolio! I'm a passionate developer who believes in the power of **"vibe-coding"** — building modern, responsive web apps with creativity at the intersection of technology and design. Currently based in Pune, India, I recently completed my MCA and love crafting digital experiences that feel alive.

---

## 🚀 What I Built

This is my **AI-Powered Portfolio** — not just a static resume, but an interactive experience where visitors can chat with an AI assistant (trained on my background) to learn about my skills, projects, and experience. Think of it as a conversation with my digital twin!

### Key Features:
- **Interactive Chat Interface** — Ask questions about my experience, skills, or projects
- **Bento Grid Layout** — Modern, responsive card-based design
- **Smooth Animations** — Progressive loading with Framer Motion
- **Streaming AI Responses** — Real-time, typewriter-style replies
- **Mobile-First Design** — Fully responsive across all devices

---

## 🛠️ Tech Stack & Concepts

### **Core Framework: React.js**

Built with **React 18** using modern patterns and hooks:

| Hook | Purpose | Where I Used It |
|------|---------|-----------------|
| **`useState`** | Managing component state | Chat messages, input value, loading states, chat visibility |
| **`useEffect`** | Side effects & lifecycle | Auto-scrolling chat to bottom when new messages arrive |
| **`useRef`** | DOM references | Scrolling to bottom of chat container smoothly |

### **TypeScript for Type Safety**

Defined custom types for clean code:
```typescript
type Message = {
  id: string;
  role: 'user' | 'assistant';
  content: string;
};
```

### **Animation: Framer Motion**

Used **`motion`** components and **`AnimatePresence`** for:
- Staggered card entrance animations
- Smooth hover interactions (`whileHover`)
- Chat panel slide-up transitions
- Icon spring animations

### **UI Components & Icons**

- **Lucide React** — Clean, consistent iconography (User, Mail, Github, LinkedIn, Code, etc.)
- **Tailwind CSS** — Utility-first styling with custom color palette
- **React Markdown** — Rendering formatted AI responses

### **Styling: Tailwind CSS**

**Design System Colors:**
- `#F4B942` — Warm Yellow (Primary accent)
- `#F25C3B` — Coral Orange (Contact card)
- `#2B8BFF` — Electric Blue (CTA buttons)
- `#FF9EC8` — Soft Pink (Summary & Education)
- `#B4E135` — Lime Green (Skills)
- `#3E1C15` — Deep Brown (Projects & Experience)
- `#FDF8F5` — Cream Background

### **AI Integration**

Connected to an AI model for conversational interactions:
- **Streaming responses** — Real-time text generation
- **System prompting** — AI trained with my background, skills, and personality
- **Message history** — Context-aware conversations

---

## 📱 Responsive Design Approach

**Mobile-first grid system:**
- `grid-cols-1` — Mobile (stacked vertically)
- `sm:grid-cols-2` — Tablet (2 columns)
- `lg:grid-cols-4` — Desktop (bento grid layout)

Cards adapt seamlessly with:
- Fluid typography (`text-xs` → `sm:text-sm` → `md:text-base`)
- Aspect ratio preservation on mobile
- Touch-friendly button sizes (44px minimum)

---

## 🎨 What "Vibe-Coding" Means to Me

> *"Thriving at the intersection of creativity and technology"*

I leverage AI-assisted development tools (Cursor, Windsurf, GitHub Copilot) to accelerate my workflow. It's not about replacing coding skills — it's about amplifying them. I focus on:
- **Prompt engineering** — Getting the best out of AI tools
- **Rapid prototyping** — Building MVPs fast
- **Clean architecture** — Maintainable, scalable code
- **Modern UX** — Animations that feel natural, not overwhelming

---

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Run locally
npm run dev

# Build for production
npm run build
```

---

## 📫 Let's Connect

- **Email:** patilsanjana10008@gmail.com
- **LinkedIn:** linkedin.com/in/sanjana-patil-26a08b222
- **GitHub:** github.com/sanjanapatil-js
- **Portfolio:** https://sanjana-patil.web.app

---

*Built with React.js, TypeScript, Tailwind CSS, and a lot of ☕ coffee.*

**Thanks for stopping by! 👋**
