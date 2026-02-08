# "Will You Be My Valentine?" - Implementation Plan

## Project Overview
A playful, romantic, interactive single-page website to ask **Bujji Baby** to be your Valentine.
Personalized from: **Mee Priyamaina Husband**

---

## Implementation Checklist

### Phase 1: Project Setup
- [x] Create project folder structure
- [x] Write implementation plan document

### Phase 2: Build Core Page (index.html)
- [ ] Create HTML structure with semantic layout
- [ ] Add Google Fonts (playful romantic font)
- [ ] Style the page with CSS:
  - Soft pink/red/white color palette
  - Centered layout with Flexbox
  - Responsive design for mobile and desktop
- [ ] Add tiled hearts/romantic placeholder background with subtle overlay
- [ ] Add the "asking" GIF (cute bear with roses)
- [ ] Add personalized heading: "Hey Bujji Baby..."
- [ ] Add the question: "Will You Be My Valentine?"
- [ ] Style the Yes button (large, inviting, pink/red)
- [ ] Style the No button (visible but will dodge)

### Phase 3: Interactive Behavior (JavaScript)
- [ ] **No Button - Desktop**: Moves to random position on hover
- [ ] **No Button - Mobile**: Moves away on tap/touch
- [ ] **No Button - Escalating phrases**: Cycles through guilt-trip messages on each attempt
- [ ] **Yes Button - Growing size**: Gets bigger each time "No" is attempted
- [ ] **Edge case**: No button never moves fully off-screen
- [ ] **Edge case**: Works with both mouse and touch input

### Phase 4: Celebration State
- [ ] On "Yes" click, switch to celebration view:
  - Swap GIF to celebratory bear kiss GIF
  - Change message to "Yay!! I knew it, Bujji Baby! I love you forever!"
  - Trigger confetti burst animation
  - Add floating hearts animation
  - Soft pink/red background color overlay
- [ ] Confetti animation (CSS + JS, no library needed)
- [ ] Floating hearts animation (CSS keyframes)

### Phase 5: Polish & Extras
- [ ] Typewriter effect for the question text
- [ ] Random romantic phrases when "No" is attempted
- [ ] Smooth transitions between states
- [ ] Page title and favicon
- [ ] Performance: optimize for fast loading
- [ ] Test on mobile viewport sizes

### Phase 6: Preview & Feedback
- [ ] Open in browser for local preview
- [ ] Get user feedback on design, wording, and behavior
- [ ] Iterate based on feedback

### Phase 7: Deploy to GitHub Pages
- [ ] Initialize git repository
- [ ] Create GitHub repo (public or private)
- [ ] Push code to GitHub
- [ ] Enable GitHub Pages
- [ ] Test the live URL
- [ ] Share the public URL

---

## Tech Stack
- **HTML5** - Single page structure
- **CSS3** - Animations, responsive layout, styling
- **Vanilla JavaScript** - Interactivity, no frameworks needed
- **GitHub Pages** - Free hosting with shareable URL

## Assets
- Asking GIF: Cute bear with roses (from gifdb.com)
- Celebration GIF: Bear kiss (from Tenor)
- Background: CSS-generated hearts pattern (placeholder)
- Font: Google Fonts (romantic/playful style)

## Key Personalization
- **Her name**: Bujji Baby
- **From**: Mee Priyamaina Husband
- **Tone**: Cute, romantic, playful, Telugu-inspired endearment
