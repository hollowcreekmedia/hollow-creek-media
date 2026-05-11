# BLOG POST SCHEDULING & PUBLISHING — INSTRUCTIONS

## SHORT ANSWER
Your blog is **static HTML on GitHub Pages** (no backend, no automatic scheduling). You will **manually publish blog posts** one per day by committing the HTML file to GitHub.

**Publishing Schedule:**
- **May 15:** Publish "The Buyer Who Didn't Call"
- **May 16:** Publish "The Math Behind Consistent Posting"
- **May 17:** Publish "Why Rural Agents Lose Deals to Agents Who Post Stories"

**How:** One file commit per day on your chosen date = post goes live within 2 minutes.

---

## DETAILED EXPLANATION

### **Why No Auto-Scheduling Right Now?**

Your website runs on:
- **GitHub Pages** (free static hosting)
- **Pure HTML/CSS/JavaScript** (no database, no backend)
- **Manual file uploads** (you or I add files, then push to GitHub)

A scheduling system would require:
- A backend server (costs money)
- A database (to store post metadata)
- A cron job or scheduler (to publish posts automatically)

This adds complexity and cost that you probably don't need.

---

## YOUR THREE OPTIONS

### **OPTION A: MANUAL FILE ADDITION (SIMPLEST - RECOMMENDED)**

**How It Works:**
1. You give me 3 new blog posts (or HTML files)
2. I create the HTML files and save them to your project folder
3. When you're ready for Post #1 to go live, you:
   - Tell me "publish post 1"
   - I commit the file to GitHub
   - It goes live immediately (within 2 minutes)
4. Repeat on day 2 for Post #2, day 3 for Post #3

**Pros:**
✓ No technical setup required  
✓ Complete control over timing  
✓ Can change publish times up until the moment you say "go"  
✓ Zero cost  

**Cons:**
✗ Requires coordination (I need to be available to commit)  
✗ Not truly "automatic"  

---

### **OPTION B: SETUP A SCHEDULING SYSTEM (MOST AUTOMATED)**

**What This Would Look Like:**

We could set up:
- **Netlify** (free tier, similar to GitHub Pages but with more features)
- **Scheduled Builds** using a pre-commit script
- **Publish dates in file metadata** that automatically control visibility

OR

- **Simple Node.js backend** + **Vercel** (deployment platform)
- **API endpoint** that checks scheduled posts and generates pages

**Pros:**
✓ Truly automatic (set it and forget it)  
✓ Professional feel  
✓ Can schedule weeks in advance  

**Cons:**
✗ Requires initial setup (2-4 hours)  
✗ Adds complexity to your site  
✗ Netlify does have limits on free tier  
✗ You lose pure simplicity of static HTML  

**Cost:** Free (using free tiers of Netlify/Vercel) to ~$10/month if scaling

---

### **OPTION C: BATCH SCHEDULE (HYBRID APPROACH)**

**How It Works:**
1. You give me 3 blog posts now
2. I create all 3 HTML files now
3. We agree on publish dates: Post 1 = May 10, Post 2 = May 11, Post 3 = May 12
4. I do all 3 commits on May 10th with commit messages like:
   - "Blog: 5 Types of Posts (publish May 10)"
   - "Blog: Design Principles (publish May 11)"
   - "Blog: Marketing Strategy (publish May 12)"
5. I **manually** push each file to live on the correct date

**Pros:**
✓ Files are ready early (no rush)  
✓ I'm not waiting for your signal  
✓ You can still adjust timing if needed  
✓ Professional/planned approach  

**Cons:**
✗ Still requires manual commits on specific dates  
✗ Not truly automatic  

---

## MY RECOMMENDATION

**Use Option A (Manual File Addition)** for right now because:

1. You're just starting out (only 3 posts)
2. It's the simplest, lowest-friction approach
3. You keep complete control
4. No technical setup needed
5. Easy to scale later if needed

**How It Would Work:**

**Day 1 — You Give Me Content:**
"Here are 3 new blog posts I want to publish. Can you prepare the HTML files?"

**I Respond:**
"I've created blog-post-1.html, blog-post-2.html, and blog-post-3.html in your outreach-materials folder. Ready to publish whenever you are."

**Day 5 — You're Ready:**
"Publish blog post 1 tomorrow at 9am."

**I Respond:**
*Commits file to GitHub*
"Post 1 is live! Ready for post 2 whenever you say."

---

## IF YOU WANT AUTO-SCHEDULING LATER

If you decide you want automatic scheduling (post every Monday at 9am, etc.), we can:

1. **Migrate to Netlify** (30 min setup, free, your site stays the same)
2. **Add Jekyll** (static site generator with scheduling built-in)
3. **Add a simple backend** (if you want more control)

But this is 100% optional and can wait until you have more content.

---

## BEST PRACTICE FOR 3 BLOG POSTS

**Timeline:**

**Monday (May 13):**
- You send me 3 blog posts (or content outlines)
- I create HTML files and add them to your project

**Tuesday (May 14):**
- I show you previews (how they'll look on the site)
- You request any edits

**Wednesday (May 15):**
- Publish Post 1 (you tell me "go")
- I commit to GitHub

**Thursday (May 16):**
- Publish Post 2

**Friday (May 17):**
- Publish Post 3

---

## FORMAT I'LL NEED FOR BLOG POSTS

Please provide blog posts in one of these formats:

**Option 1: Word document or Google Doc**
- Just write naturally
- I'll format it as HTML in your site style

**Option 2: Markdown (.md file)**
- Simpler format, easier for me to convert
- I can format quickly

**Option 3: HTML**
- If you've already written it in HTML
- I'll integrate and style

**Option 4: Content outline**
- Just give me the main points
- I can flesh it out if needed

---

## WHAT TO INCLUDE WITH EACH POST

When you give me blog post content, please include:

- [ ] **Title** (clear, descriptive)
- [ ] **Category/Tag** (Strategy, Design, Efficiency, etc. — match your existing blog)
- [ ] **Date** (when it was written or published)
- [ ] **Body content** (the actual blog post)
- [ ] **Excerpt** (2-3 sentences for the blog card preview)
- [ ] **Featured image URL** (if you have one; can use Unsplash/Pexels links)
- [ ] **Suggested publish date** (when you want it to go live)

---

## EXAMPLE: WHAT THIS WOULD LOOK LIKE

### **Email with Blog Post #1:**

```
Subject: New Blog Post — "The Ghost Agent Effect (Expanded)"

Hi,

Here's the first blog post for the site. Details below:

**Title:** The Ghost Agent Effect (Expanded Version)

**Category:** Strategy

**Date:** May 4, 2026

**Excerpt:** How to maintain a high-end digital presence while you are miles out of cell range deep in the timber. The "Ghost Agent" model and how it works for solo agents.

**Featured Image:** https://images.unsplash.com/photo-1500382017468-9049fed747ef

**Content:** [Full blog post text here]

**Publish Date:** May 15, 2026 (ready to go whenever)

---

When can you add this to the site?
```

---

## I'M READY WHEN YOU ARE

Just send over:
1. The 3 blog posts (in any format)
2. Whether you want them published (Option A = manual coordination)
3. Your preferred publishing dates (if you have them)

Then we'll set them up and you'll have control over the timing.

---

**Last Updated:** May 2026
