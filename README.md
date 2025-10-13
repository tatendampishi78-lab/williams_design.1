# 🧩 Brand Strategy Research Project

### Learn to Collaborate, Think Strategically, and Design with Purpose

In this project, you and your teammates will learn how **brands use psychology, design, and storytelling** to connect with people — and how to use **GitHub** to work together like real developers and designers.

You’ll explore:
- **Brand Archetypes** (the personality behind a brand)
- **Cialdini’s Principles of Persuasion**
- **Sales Funnels** (how websites turn visitors into customers)
- **Competitor Analysis** (how real companies use these ideas online)

Then you’ll bring it all together by researching a real product or business category (like coffee, pizza, gyms, etc.) and building your own simple, well-researched brand strategy website.

---

## 🧭 Project Overview

**Goal:**  
Work as a team to research, write, and organize information about your chosen business type — using GitHub to collaborate safely without overwriting each other’s work.

Each student will take ownership of **one topic** (archetype, persuasion, funnel, or a competitor) and contribute their findings in Markdown files inside a shared GitHub repository.

By the end, your team will have created:
- A small **knowledge base** on brand psychology and marketing strategy  
- A **collaborative research workflow** using GitHub branches and pull requests  
- The foundation for your **first team website project**

---

## 🧰 Repository Structure

Your team’s repo should look like this:

```

/docs
archetype.md
persuasion.md
sales-funnel.md
/competitors/
competitor1.md
competitor2.md
competitor3.md
README.md

```

🟢 *Tip:* Use folders to stay organized. Each `.md` file is a research page.

---

## 👥 Team Roles

| Role | Focus | File to Edit |
|------|--------|--------------|
| **Archetype Researcher** | Researches your chosen brand archetype (colors, fonts, tone) | `/docs/archetype.md` |
| **Persuasion Analyst** | Explains Cialdini’s 6 persuasion methods and real examples | `/docs/persuasion.md` |
| **Funnel Strategist** | Explains what a sales funnel is and how websites guide users | `/docs/sales-funnel.md` |
| **Competitor Analyst(s)** | Each student analyzes one competitor website | `/docs/competitors/[brand].md` |

---

## 🌱 Step-by-Step Instructions

### 1. Create and Clone the Repository
- One team member creates the repo (or uses the GitHub Classroom link).
- Everyone else clones it:
```

git clone [https://github.com/yourteam/brand-strategy-[teamname].git](https://github.com/yourteam/brand-strategy-[teamname].git)

```

---

### 2. Create Your Own Branch
Each student should **work in their own branch** to avoid conflicts.

```

git checkout -b yourname-topic

```

Example:
```

git checkout -b keith-archetype

```

---

### 3. Work on Your Assigned File
Only edit your assigned Markdown file.  
Do **not** change teammates’ files.

Example:
```

/docs/archetype.md

```

🟢 *Why?* This prevents merge conflicts and teaches you clean collaboration.

---

### 4. Add, Commit, and Push
When you’re ready to save your work:

```

git add docs/archetype.md
git commit -m "Added Explorer archetype research"
git push origin keith-archetype

````

---

### 5. Open a Pull Request (PR)
On GitHub.com:
1. Go to your repository.
2. Click **Compare & pull request**.
3. Ask teammates to **review** before merging into `main`.

---

### 6. Merge Once Approved
After review, click **Merge pull request**.  
You’ve now contributed safely to the shared project!

---

## 📄 What to Include in Each File

### 🧠 `/docs/archetype.md`
**Purpose:** Research and describe your brand’s archetype.

Include:
- Definition and motivation  
- Color palette and font styles  
- Typical imagery or symbols  
- Vocabulary and tone  
- Real brand examples  

Example:
```markdown
# Explorer Archetype
- **Core Traits:** Freedom, discovery, authenticity  
- **Colors:** Earthy greens, blues, neutrals  
- **Fonts:** Clean sans-serif (Montserrat, Open Sans)  
- **Tone:** Bold, inviting, adventurous  
- **Example Brands:** Starbucks, Patagonia, Jeep
````

---

### 💬 `/docs/persuasion.md`

**Purpose:** Explain how brands persuade users using Cialdini’s 6 principles.

Sections to include:

* Reciprocity (free samples, loyalty points)
* Scarcity (limited editions)
* Authority (expert opinions, certifications)
* Consistency (habit and identity)
* Liking (friendly design, personalization)
* Social Proof (testimonials, reviews)

Add examples and screenshots from real sites.

---

### 🌀 `/docs/sales-funnel.md`

**Purpose:** Explain how websites guide users through the sales funnel.

Stages to explain:

1. Awareness — attract attention
2. Interest — build curiosity
3. Desire — create emotional connection
4. Action — encourage conversion

Example:

## Example: Local Coffee Shop
| Stage | Section | Goal |
|--------|----------|------|
| Awareness | Hero image | Introduce the brand |
| Interest | Menu or products | Engage curiosity |
| Desire | Testimonials | Build emotional connection |
| Action | "Order Now" button | Drive conversion |

---

### 🔎 `/docs/competitors/[brand].md`

**Purpose:** Each teammate researches one competitor website.

Template:

# Competitor Analysis: Starbucks
- **URL:** https://www.starbucks.com
- **Archetype:** Explorer
- **Persuasion Techniques:** Social Proof, Liking, Reciprocity
- **Sales Funnel Highlights:**
  - Awareness: Lifestyle imagery + hero headline
  - Interest: Menu and product stories
  - Desire: Coffee journey storytelling
  - Action: “Order Ahead” CTA
- **Strengths:** Strong global brand, consistent UX
- **Weaknesses:** Price and saturation

---

## 🧾 README Requirements

Include the following in your main `README.md`:

* Project title and description
* Team members and roles
* Short summary of chosen business or product
* Links to each research file
* (Later) Link to your published GitHub Pages site

---

## 🧮 Grading Rubric (100 Points)

| Category                        | Points | Description                                               |
| ------------------------------- | ------ | --------------------------------------------------------- |
| **Individual Research Quality** | 25     | Depth and clarity of your assigned page                   |
| **Team Integration**            | 25     | Alignment between archetype, persuasion, and funnel ideas |
| **Git Collaboration**           | 25     | Proper branching, commits, pull requests                  |
| **Presentation & Reflection**   | 25     | Clear final presentation and insights shared in class     |

---

## 💡 Tips for Success

* Communicate regularly with your team using GitHub Discussions or chat.
* Commit often — don’t wait until the end!
* Reference real brands and include visuals where possible.
* Keep your Markdown clean and readable.
* Be curious. This project is about *learning how ideas shape design.*

---

### ✅ End Goal

By the end of this project, your team will have:

* A clear understanding of how branding and persuasion work online
* Hands-on experience collaborating in GitHub
* Research content ready to turn into a real website in the next phase

---

**Instructor Contact:**
If you have merge issues, conceptual questions, or want feedback — open an **Issue** in your repo or ask during lab.


---

Would you like me to generate a matching **repo template folder** (with all empty `.md` files pre-created, including placeholder comments and instructions inside each) that you can zip and upload to GitHub Classroom?  
That would let students instantly fork a structured starting point with no setup friction.
