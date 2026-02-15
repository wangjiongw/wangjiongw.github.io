# Improvement Todo List: Jiong WANG's Academic Homepage

**Created:** 2026-02-15
**Status:** Analysis Complete - Ready for Implementation
**Goal:** Enhance visualization, increase professional impact for job market

---

## Priority Legend

- 🔴 **High Priority** - Quick wins with significant impact
- 🟡 **Medium Priority** - Moderate effort, good impact
- 🟢 **Low Priority** - Nice to have, lower urgency

---

## Section 1: User-Requested Improvements

### 1.1 Blog Component [🔴 HIGH PRIORITY]
**Status:** Feature exists, needs activation

**Discovery:** Blog functionality is already fully implemented via Jekyll's `_posts` collection. The archive page exists at `/year-archive/` but is not linked in navigation.

**Tasks:**
- [ ] Add "Blog" to navigation menu in `_data/navigation.yml`
- [ ] Remove or replace sample blog posts (2001-2199 dates)
- [ ] Create 3-5 genuine blog posts about research/topics
  - Suggested topics: MultiModal Learning, AI4Earth, research experiences, paper reviews
- [ ] Configure blog post metadata (categories, tags, featured images)
- [ ] Test blog display on homepage (if recent posts widget enabled)

**Estimated Effort:** 2-3 hours
**Impact:** High - Shows thought leadership, research depth

---

## Section 2: Visualization & Design Enhancements

### 2.1 Custom Visual Identity [🔴 HIGH PRIORITY]
**Goal:** Stand out from default template, strengthen personal brand

**Tasks:**
- [ ] Define custom color scheme (currently uses Minimal Mistakes defaults)
- [ ] Update `_sass/_variables.scss` with brand colors
- [ ] Add custom logo/favicon (currently using default)
- [ ] Enhance about page with professional photo gallery
- [ ] Add visual separator/divider elements between sections

**Estimated Effort:** 3-4 hours
**Impact:** High - Professional appearance, memorable

---

### 2.2 Enhanced Publication Display [🔴 HIGH PRIORITY]
**Goal:** Showcase publications more prominently for job market

**Tasks:**
- [ ] Add publication statistics (citation counts, venue rankings)
- [ ] Create featured publications section on homepage
- [ ] Add PDF/download links to publications
- [ ] Include publication images/thumbnails
- [ ] Add "Selected Publications" filter or badge system
  - badges: "Best Paper", "Most Cited", "Recent"
- [ ] Integrate Google Scholar citation count display

**Estimated Effort:** 4-5 hours
**Impact:** High - Critical for academic job applications

---

### 2.3 Project Showcase Enhancement [🔴 HIGH PRIORITY]
**Goal:** Visual portfolio to demonstrate research impact

**Tasks:**
- [ ] Add project thumbnails/images for all portfolio items
- [ ] Create project cards with visual hierarchy
- [ ] Add demo/video links where available
- [ ] Include impact metrics (users, downloads, citations)
- [ ] Add technology stack badges to projects
- [ ] Create "Featured Projects" section on homepage

**Estimated Effort:** 4-6 hours
**Impact:** High - Shows practical research applications

---

### 2.4 CV Timeline Visualization [🟡 MEDIUM PRIORITY]
**Goal:** Make CV more engaging and scannable

**Tasks:**
- [ ] Convert CV to vertical timeline layout
- [ ] Add visual icons for different experience types
- [ ] Highlight current position with visual indicator
- [ ] Add skill progress bars or visualization
- [ ] Include award/honor badges

**Estimated Effort:** 3-4 hours
**Impact:** Medium - Improves readability, professional appearance

---

### 2.5 Interactive Elements [🟡 MEDIUM PRIORITY]
**Goal:** Increase engagement and modern feel

**Tasks:**
- [ ] Add smooth scroll animations
- [ ] Implement hover effects on publication/project cards
- [ ] Add back-to-top button
- [ ] Create interactive research interest tags
- [ ] Add publication filtering by year/venue/topic
- [ ] Implement search functionality (Algolia or simple JS search)

**Estimated Effort:** 5-7 hours
**Impact:** Medium - Better user experience

---

### 2.6 Dark Mode Support [🟢 LOW PRIORITY]
**Goal:** Modern UX, accessibility

**Tasks:**
- [ ] Implement dark mode toggle
- [ ] Create dark theme color palette
- [ ] Add theme persistence (localStorage)
- [ ] Test all pages in both themes

**Estimated Effort:** 4-5 hours
**Impact:** Low - Nice to have, but not critical

---

## Section 3: Impact & Engagement

### 3.1 Analytics Configuration [🔴 HIGH PRIORITY]
**Goal:** Track visitor engagement, understand traffic sources

**Tasks:**
- [ ] Set up Google Analytics account
- [ ] Add tracking ID to `_config.yml`
- [ ] Configure event tracking for publications/projects
- [ ] Set up goal tracking (PDF downloads, contact clicks)
- [ ] Create monthly traffic reports

**Estimated Effort:** 1-2 hours
**Impact:** High - Data-driven improvements

---

### 3.2 Social Media Integration [🟡 MEDIUM PRIORITY]
**Goal:** Expand online presence, networking

**Tasks:**
- [ ] Add LinkedIn profile link (currently missing)
- [ ] Add ResearchGate profile (if applicable)
- [ ] Enable social sharing on publications/blog posts
- [ ] Add social media follow buttons to sidebar
- [ ] Include latest tweets/updates section (optional)

**Estimated Effort:** 1-2 hours
**Impact:** Medium - Better networking, discoverability

---

### 3.3 Comments & Engagement [🟡 MEDIUM PRIORITY]
**Goal:** Enable discussion on blog posts

**Tasks:**
- [ ] Choose comment system (Disqus, Utterances, giscuss recommended)
- [ ] Configure comment provider in `_config.yml`
- [ ] Test comment functionality
- [ ] Add moderation guidelines

**Estimated Effort:** 1-2 hours
**Impact:** Medium - Community engagement

---

### 3.4 Newsletter/Email List [🟢 LOW PRIORITY]
**Goal:** Keep visitors updated on new publications

**Tasks:**
- [ ] Set up newsletter service (Substack, Buttondown, etc.)
- [ ] Add newsletter signup form
- [ ] Create email automation for new posts

**Estimated Effort:** 2-3 hours
**Impact:** Low - Optional, depends on goals

---

## Section 4: Navigation & UX

### 4.1 Expanded Navigation [🔴 HIGH PRIORITY]
**Goal:** Better content discoverability

**Tasks:**
- [ ] Add "Blog" to navigation (currently commented out)
- [ ] Consider adding "Talks" to navigation (4 talks available)
- [ ] Consider adding "Teaching" to navigation (content exists)
- [ ] Add dropdown menu structure if needed
- [ ] Ensure mobile menu is working properly

**Estimated Effort:** 30 minutes
**Impact:** High - Content is currently hidden

---

### 4.2 Homepage Optimization [🔴 HIGH PRIORITY]
**Goal:** Make strong first impression for recruiters

**Tasks:**
- [ ] Add hero section with professional tagline
- [ ] Include quick stats (publications, citations, projects)
- [ ] Add "Recent Publications" preview section
- [ ] Add "Latest Blog Posts" preview section
- [ ] Include clear call-to-action (Download CV, Contact)
- [ ] Optimize about section for quick scanning

**Estimated Effort:** 2-3 hours
**Impact:** High - Critical for job market

---

### 4.3 SEO Optimization [🟡 MEDIUM PRIORITY]
**Goal:** Improve search ranking, discoverability

**Tasks:**
- [ ] Add meta descriptions to all pages
- [ ] Optimize publication titles and descriptions
- [ ] Add schema.org markup for person/author
- [ ] Create robots.txt if missing
- [ ] Submit sitemap to Google Search Console
- [ ] Add alt text to all images

**Estimated Effort:** 2-3 hours
**Impact:** Medium - Better search visibility

---

### 4.4 Performance Optimization [🟡 MEDIUM PRIORITY]
**Goal:** Faster load times, better UX

**Tasks:**
- [ ] Optimize and compress images
- [ ] Enable lazy loading for images
- [ ] Minify CSS/JS
- [ ] Test page speed with Google PageSpeed Insights
- [ ] Implement caching headers

**Estimated Effort:** 2-3 hours
**Impact:** Medium - Better user experience

---

## Section 5: Content Strategy

### 5.1 Blog Content Creation [🔴 HIGH PRIORITY]
**Goal:** Establish thought leadership

**Tasks:**
- [ ] Write introduction post about research interests
- [ ] Create series on MultiModal Learning
- [ ] Write paper summaries for own publications
- [ ] Share conference/talk experiences
- [ ] Post about research tools/tips
- [ ] Create blog content calendar (1-2 posts/month)

**Estimated Effort:** Ongoing
**Impact:** High - Shows expertise, keeps site fresh

---

### 5.2 Publication Presentation [🔴 HIGH PRIORITY]
**Goal:** Make publications more accessible

**Tasks:**
- [ ] Write plain-English summaries for each paper
- [ ] Add presentation slides (PDF/PPT)
- [ ] Include poster images from conferences
- [ ] Add video explanations where available
- [ ] Create "Why this matters" section for each publication

**Estimated Effort:** 4-6 hours
**Impact:** High - Broader audience reach

---

### 5.3 Teaching/Talks Content [🟡 MEDIUM PRIORITY]
**Goal:** Showcase communication skills

**Tasks:**
- [ ] Add teaching materials/slides to teaching section
- [ ] Upload talk slides and posters
- [ ] Add talk recordings (YouTube link)
- [ ] Write summaries for each talk/teaching experience

**Estimated Effort:** 2-3 hours
**Impact:** Medium - Shows teaching/mentoring ability

---

## Section 6: Technical Improvements

### 6.1 Contact Form [🟡 MEDIUM PRIORITY]
**Goal:** Easy way for recruiters to reach out

**Tasks:**
- [ ] Choose contact form solution (Formspree, Netlify Forms, etc.)
- [ ] Add contact form to dedicated page
- [ ] Add spam protection
- [ ] Test form functionality

**Estimated Effort:** 1-2 hours
**Impact:** Medium - Better than just email link

---

### 6.2 Automated Citation Badges [🟢 LOW PRIORITY]
**Goal:** Dynamic citation counts from Google Scholar

**Tasks:**
- [ ] Implement citation badge widget
- [ ] Add to each publication
- [ ] Update automatically

**Estimated Effort:** 2-3 hours
**Impact:** Low - Nice to have visual element

---

## Implementation Roadmap

### Phase 1: Quick Wins (Week 1)
**Total Effort:** 6-8 hours
**Goal:** Maximum impact with minimal effort

1. ✅ Activate blog navigation (30 min)
2. ✅ Add LinkedIn/social links (30 min)
3. ✅ Configure Google Analytics (1 hour)
4. ✅ Add featured publications to homepage (2 hours)
5. ✅ Enhance project showcase with images (2 hours)
6. ✅ Optimize homepage for first impression (2 hours)

**Expected Outcome:** Significantly improved visual presence and trackable engagement

---

### Phase 2: Content & Visualization (Week 2-3)
**Total Effort:** 10-15 hours
**Goal:** Professional polish, job-market ready

1. ✅ Create 3-5 genuine blog posts (4-6 hours)
2. ✅ Custom visual identity implementation (3-4 hours)
3. ✅ Publication enhancement with images/links (3-4 hours)
4. ✅ CV timeline visualization (3-4 hours)

**Expected Outcome:** Professional, personalized site ready for job applications

---

### Phase 3: Advanced Features (Week 4+)
**Total Effort:** 10-15 hours
**Goal:** Ongoing improvements and engagement

1. ✅ Interactive elements and animations (5-7 hours)
2. ✅ Comments system setup (1-2 hours)
3. ✅ SEO optimization (2-3 hours)
4. ✅ Performance optimization (2-3 hours)

**Expected Outcome:** Modern, engaging, high-performance site

---

### Phase 4: Optional Enhancements (As Needed)
**Total Effort:** Variable

1. ⬜ Dark mode implementation
2. ⬜ Newsletter setup
3. ⬜ Advanced search functionality
4. ⬜ Additional interactive visualizations

---

## Metrics to Track

After implementation, track these metrics to measure impact:

- **Visitor Analytics:** Monthly visitors, page views, session duration
- **Content Performance:** Most viewed publications/projects/blog posts
- **Acquisition:** Traffic sources (Google, social media, direct links)
- **Engagement:** PDF downloads, contact form submissions
- **SEO:** Ranking for name and research keywords

---

## Notes

### Important Considerations
1. **No code changes in this phase** - This is analysis and planning only
2. **Blog already exists** - Just needs activation and real content
3. **Job market timeline** - Prioritize Phase 1 & 2 for immediate impact
4. **GitHub Pages limitations** - Some features may require workarounds

### Risks & Mitigations
- **Risk:** Breaking existing functionality during customization
  - **Mitigation:** Test on feature branch before merging to main
- **Risk:** Image hosting for publications/projects
  - **Mitigation:** Use GitHub repository or imgur for hosting
- **Risk:** Comment system maintenance
  - **Mitigation:** Choose maintenance-free option (Utterances/giscuss)

### Resources
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Minimal Mistakes Theme Docs](https://mmistakes.github.io/minimal-mistakes/docs/)
- [Academic Homepage Examples](https://github.com/academicpages/academicpages.github.io/wiki/Examples)

---

## Summary

**Total Improvements:** 40+ tasks across 6 categories
**Recommended Implementation:** 4-phase approach over 3-4 weeks
**Highest Priority Items:** Blog activation, publication enhancement, homepage optimization, analytics setup

**Next Step:** Begin Phase 1 implementation for immediate job market impact.
