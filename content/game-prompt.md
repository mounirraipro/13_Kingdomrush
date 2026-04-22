# AI Content Prompt - Kingdom Rush
> Paste this entire file into your AI. It will return a complete game.json.

---

## YOUR TASK

Fill in every "..." in the JSON structure at the bottom of this file.
Return ONLY the completed JSON - no markdown fences, no explanation, no comments.

---

## GAME DETAILS

| Field      | Value       |
|------------|-------------|
| Name       | Kingdom Rush      |
| Domain     | kingdomrush.online    |
| Slug       | kingdomrush      |
| Genre      | Tower Defense         |
| Iframe URL | /game/index.html    |

---

## GENRE CONTEXT - TOWER DEFENSE

Use this knowledge to write accurate, specific content. Do NOT treat this as a generic game.

- **Core mechanics:** place defensive towers along a path to prevent enemies from reaching the base
- **Target audience:** strategy fans aged 15-40
- **Key player benefits:** strategic depth, satisfying enemy-wave clearance, good replayability
- **Playstyle:** planning-heavy; watch waves, adapt placements
- **Level structure:** wave-based per map; unlock new towers and maps
- **SEO angles to use:** free tower defense browser, online TD game no download, play tower defense free
- **Tip writing style:** cover chokepoints, upgrade a few towers rather than spreading thin, save for emergencies

---

## CONTENT GUIDELINES

### Tone
- Knowledgeable but approachable. Write as a game expert, not a marketer.
- Confident and direct. No hedging ("might", "perhaps", "could").
- British English spelling throughout (colour, favourite, recognise, analyse).

### What to avoid
- Placeholder text or obvious template phrases ("exciting journey", "look no further").
- Repeating the game name more than once per short paragraph.
- Generic gaming cliches ("immersive", "epic", "addictive" as the first word).
- First-person plural ("we", "our team", "our game").

### Stats block (homepage.stats)
- First two stats should be concrete and game-specific (e.g. number of levels, puzzle types, game modes).
- Keep the last two as given: "0 Downloads Needed" and "100% Free Forever".

### Categories block (homepage.categories)
- Name five real difficulty tiers or game-mode categories that fit Tower Defense games.
- Examples for puzzle: Beginner, Intermediate, Advanced, Expert, Master.
- Examples for action: Recruit, Soldier, Veteran, Elite, Legendary.
- Match the category names to the genre - don't use generic placeholders.

### Features block (homepage.features)
- Each feature highlights a real selling point of this genre/game type.
- Icons are fixed (bolt, target, device, image, shield, music) - match title/desc to icon meaning.
- "device" = cross-platform/mobile; "shield" = safe for kids; "music" = sound/audio.

### Blog posts
- Each paragraph: 80-150 words. Short sentences. No passive voice.
- Content must be genuinely useful - tips, explanations, cognitive research hooks.
- The parents-guide post must mention: no ads targeting children, no in-app purchases, safe browser play.

---

## SEO WRITING RULES

- Meta title: 50-60 characters. Include game name + main keyword.
- Meta description: 140-155 characters. Primary keyword in first 20 words. Include a call to action.
- Keywords: 5-8 terms. Mix exact-match, long-tail, and genre terms.
- Body text: Natural language. One primary keyword per ~100 words.
- FAQ answers: 2-4 sentences each. Direct.
- Use British English spelling.
- Avoid: "we", "our game", filler phrases, keyword stuffing.

---

## JSON TO FILL IN

{
  "name": "Kingdom Rush",
  "domain": "kingdomrush.online",
  "slug": "kingdomrush",
  "genre": "Tower Defense",
  "iframeUrl": "/game/index.html",

  "seo": {
    "title": "...",
    "description": "...",
    "keywords": ["...", "..."]
  },

  "homepage": {
    "heroHeadline": "...",
    "heroSubtitle": "...",
    "lede": "...",
    "stats": [
      { "value": "...", "label": "..." },
      { "value": "...", "label": "..." },
      { "value": "0",    "label": "Downloads Needed" },
      { "value": "100%", "label": "Free Forever" }
    ],
    "about": {
      "kicker": "What is Kingdom Rush?",
      "headline": "...",
      "paragraph1": "...",
      "paragraph2": "..."
    },
    "howToPlay": {
      "headline": "...",
      "subheading": "..."
    },
    "steps": [
      { "icon": "folder",       "title": "...", "desc": "..." },
      { "icon": "eye",          "title": "...", "desc": "..." },
      { "icon": "refresh",      "title": "...", "desc": "..." },
      { "icon": "puzzle",       "title": "...", "desc": "..." },
      { "icon": "check-circle", "title": "...", "desc": "..." }
    ],
    "categories": [
      { "name": "...", "icon": "star",   "color": "#10b981", "bg": "#d1fae5", "img": "/level-thumbs/category-1.webp" },
      { "name": "...", "icon": "target", "color": "#3b82f6", "bg": "#dbeafe", "img": "/level-thumbs/category-2.webp" },
      { "name": "...", "icon": "zap",    "color": "#f59e0b", "bg": "#fef3c7", "img": "/level-thumbs/category-3.webp" },
      { "name": "...", "icon": "trophy", "color": "#8b5cf6", "bg": "#ede9fe", "img": "/level-thumbs/category-4.webp" },
      { "name": "...", "icon": "crown",  "color": "#ef4444", "bg": "#fee2e2", "img": "/level-thumbs/category-5.webp" }
    ],
    "features": [
      { "icon": "bolt",   "title": "...", "desc": "..." },
      { "icon": "target", "title": "...", "desc": "..." },
      { "icon": "device", "title": "...", "desc": "..." },
      { "icon": "image",  "title": "...", "desc": "..." },
      { "icon": "shield", "title": "...", "desc": "..." },
      { "icon": "music",  "title": "...", "desc": "..." }
    ],
    "faq": [
      { "q": "What is Kingdom Rush?",             "a": "..." },
      { "q": "Is Kingdom Rush free?",             "a": "..." },
      { "q": "Does Kingdom Rush work on mobile?", "a": "..." },
      { "q": "How many levels are there?",  "a": "..." },
      { "q": "Is Kingdom Rush safe for kids?",    "a": "..." },
      { "q": "Do I need an account?",       "a": "..." }
    ],
    "cta": {
      "headline": "...",
      "subtext": "..."
    }
  },

  "playPage": {
    "howItWorksSubtitle": "...",
    "steps": [
      { "title": "...", "desc": "..." },
      { "title": "...", "desc": "..." },
      { "title": "...", "desc": "..." }
    ]
  },

  "faqPage": {
    "items": [
      { "q": "Is Kingdom Rush really free?",          "a": "..." },
      { "q": "What devices can I play on?",      "a": "..." },
      { "q": "How does the game work?",          "a": "..." },
      { "q": "How many levels are there?",       "a": "..." },
      { "q": "Can I play offline?",              "a": "..." },
      { "q": "Is my progress saved?",            "a": "..." },
      { "q": "Is Kingdom Rush safe for children?",     "a": "..." },
      { "q": "Do I need to create an account?",  "a": "..." }
    ]
  },

  "howToPlayPage": {
    "intro": "...",
    "steps": [
      { "title": "...", "desc": "..." },
      { "title": "...", "desc": "..." },
      { "title": "...", "desc": "..." }
    ],
    "mechanic": { "title": "...", "desc": "..." },
    "difficultyProgression": "...",
    "tips": [
      { "title": "...", "desc": "..." },
      { "title": "...", "desc": "..." },
      { "title": "...", "desc": "..." },
      { "title": "...", "desc": "..." },
      { "title": "...", "desc": "..." }
    ]
  },

  "blog": {
    "headline": "Guides &amp; Strategy",
    "subheading": "...",
    "introParagraph": "...",
    "posts": [
      {
        "slug": "getting-started",
        "title": "Getting Started with Kingdom Rush: A Complete Beginner's Guide",
        "excerpt": "...",
        "category": "Guide",
        "readTime": "5 min read",
        "date": "2026-01-01",
        "icon": "🗺️",
        "sections": [
          { "heading": "What Is Kingdom Rush?",    "paragraphs": ["...", "..."] },
          { "heading": "How to Open the Game",    "paragraphs": ["...", "..."] },
          { "heading": "Your First Five Minutes", "paragraphs": ["...", "..."] },
          { "heading": "Ready to Play?",          "paragraphs": ["..."] }
        ]
      },
      {
        "slug": "tips-and-tricks",
        "title": "Top Tips & Tricks for Kingdom Rush",
        "excerpt": "...",
        "category": "Strategy",
        "readTime": "7 min read",
        "date": "2026-01-05",
        "icon": "💡",
        "sections": [
          { "heading": "Master the Fundamentals",  "paragraphs": ["...", "..."] },
          { "heading": "Think Before You Act",     "paragraphs": ["...", "..."] },
          { "heading": "Recognise Patterns Early", "paragraphs": ["...", "..."] },
          { "heading": "Advanced Techniques",      "paragraphs": ["...", "..."] }
        ]
      },
      {
        "slug": "game-benefits",
        "title": "The Cognitive Benefits of Playing Kingdom Rush",
        "excerpt": "...",
        "category": "Science",
        "readTime": "6 min read",
        "date": "2026-01-10",
        "icon": "🧠",
        "sections": [
          { "heading": "Games and the Brain", "paragraphs": ["...", "..."] },
          { "heading": "Problem-Solving",     "paragraphs": ["...", "..."] },
          { "heading": "Stress Relief",       "paragraphs": ["...", "..."] },
          { "heading": "Safe Screen Time",    "paragraphs": ["...", "..."] }
        ]
      },
      {
        "slug": "how-to-improve",
        "title": "How to Get Better at Kingdom Rush",
        "excerpt": "...",
        "category": "Strategy",
        "readTime": "8 min read",
        "date": "2026-01-15",
        "icon": "📈",
        "sections": [
          { "heading": "Focus on Consistency",  "paragraphs": ["...", "..."] },
          { "heading": "Analyse Your Mistakes", "paragraphs": ["...", "..."] },
          { "heading": "Build a Strategy",      "paragraphs": ["...", "..."] },
          { "heading": "Practice Regularly",    "paragraphs": ["...", "..."] }
        ]
      },
      {
        "slug": "parents-guide",
        "title": "Kingdom Rush for Kids: A Parent's Complete Guide",
        "excerpt": "...",
        "category": "Family",
        "readTime": "6 min read",
        "date": "2026-01-20",
        "icon": "👨‍👩‍👧",
        "sections": [
          { "heading": "Is Kingdom Rush Safe for Children?", "paragraphs": ["...", "..."] },
          { "heading": "What Will My Child Learn?",    "paragraphs": ["...", "..."] },
          { "heading": "Tips for Healthy Screen Time", "paragraphs": ["...", "..."] },
          { "heading": "COPPA Compliance",             "paragraphs": ["...", "..."] }
        ]
      }
    ]
  }
}