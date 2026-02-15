# Repository Analysis: Jiong WANG's Academic Homepage

**Analysis Date:** 2026-02-15
**Repository:** wangjiongw.github.io
**Template Origin:** Forked from academicpages/academicpages.github.io (based on Minimal Mistakes Jekyll Theme)

---

## 1. Overview

This is a Jekyll-based academic homepage hosted on GitHub Pages. The site serves as a professional portfolio for Jiong WANG, a PhD student in Computer Science at Fudan University and research intern at Shanghai AI Lab.

### Site Information
- **URL:** https://wangjiongw.github.io
- **Owner:** Jiong WANG
- **Position:** PhD Student @ Fudan University & Shanghai AI Lab
- **Research Interests:** MultiModal Learning, AI4Earth

---

## 2. Technology Stack

### Core Technology
- **Static Site Generator:** Jekyll (Ruby-based)
- **Hosting:** GitHub Pages
- **Markup:** Markdown (Kramdown parser)
- **Styling:** SCSS/SASS with Minimal Mistakes theme
- **Code Highlighting:** Rouge

### Jekyll Plugins
- `jekyll-paginate` - Pagination for posts
- `jekyll-sitemap` - Automatic sitemap generation
- `jekyll-gist` - GitHub Gist embedding
- `jekyll-feed` - Atom/RSS feed generation
- `jekyll-redirect-from` - URL redirection support
- `hawkins` - Markdown generator utility

### Build Tools
- Ruby (via Bundler)
- Node.js (for assets)

---

## 3. Directory Structure

```
wangjiongw.github.io/
├── _config.yml              # Main Jekyll configuration
├── _data/                   # Data files
│   ├── navigation.yml       # Site navigation menu
│   ├── authors.yml          # Authors configuration
│   └── ui-text.yml          # UI text strings
├── _includes/               # Reusable HTML components
├── _layouts/                # Page layouts
├── _sass/                   # SCSS stylesheets
├── _pages/                  # Main site pages
├── _posts/                  # Blog posts (EXISTS - contains sample posts)
├── _publications/           # Publications collection
├── _talks/                  # Talks collection
├── _portfolio/              # Portfolio items
├── _teaching/               # Teaching items
├── _drafts/                 # Draft posts
├── _projects/               # Project files
├── assets/                  # CSS, fonts, JavaScript
├── images/                  # Image assets
├── files/                   # Downloadable files (PDFs, etc.)
├── markdown_generator/      # Tools for generating markdown
└── talkmap/                 # Talk visualization tools
```

---

## 4. Current Pages & Navigation

### Active Navigation Items
Based on `_data/navigation.yml`:

| Title | URL | Status |
|-------|-----|--------|
| Publications | /publications/ | **ACTIVE** |
| Projects | /projects/ | **ACTIVE** |
| CV | /cv/ | **ACTIVE** |

### Available but Disabled (Commented Out)
| Title | URL | Notes |
|-------|-----|-------|
| Talks | /talks/ | Has content, navigation disabled |
| Teaching | /teaching/ | Has content, navigation disabled |
| Portfolio | /portfolio/ | Has content, navigation disabled |
| Blog Posts | /year-archive/ | **Feature exists but not linked** |

### All Available Pages in `_pages/`
- `about.md` (front page, permalink: /)
- `cv.md`
- `publications.md`
- `talks.html`
- `portfolio.html`
- `teaching.html`
- `archive-layout-with-content.md` (markdown demo)
- `category-archive.html`
- `collection-archive.html`
- `markdown.md` (markdown guide)
- `non-menu-page.md`
- `page-archive.html`
- `sitemap.md`
- `tag-archive.html`
- `talkmap.html`
- `terms.md`
- `year-archive.html` (blog archive)
- `404.md`

---

## 5. Collections

### Configured Collections

| Collection | Output | Permalink | Items Count |
|------------|--------|-----------|-------------|
| `teaching` | Yes | /:collection/:path/ | Sample items present |
| `publications` | Yes | /:collection/:path/ | 4 publications |
| `portfolio` | Yes | /:collection/:path/ | 2 items |
| `talks` | Yes | /:collection/:path/ | 4 talks |
| `posts` | Yes | /:categories/:title/ | 5 sample posts (2001-2199) |

### Publications Inventory
1. **FreeMan** (CVPR2024) - 3D Human Pose Estimation
2. **LAMM** (NeurIPS2023) - Multi-Modal Instruction-Tuning
3. **Weakly-supervised object localization** (2022)
4. **Reinforced Agent for Exposure Bracketing** (2020)

### Blog Posts (Sample Content)
The `_posts/` directory contains 5 sample blog posts:
- 2012-08-14-blog-post-1.md
- 2013-08-14-blog-post-2.md
- 2014-08-14-blog-post-3.md
- 2015-08-14-blog-post-4.md
- 2199-01-01-future-post.md

**Key Finding:** Blog functionality is fully implemented but not currently visible in navigation.

---

## 6. Layouts & Styling

### Available Layouts
1. **default.html** - Base layout (compress layout wrapper)
2. **single.html** - Single page/post layout with sidebar
3. **archive.html** - Archive listing layout
4. **archive-taxonomy.html** - Category/tag archive
5. **splash.html** - Splash/landing page
6. **talk.html** - Specialized layout for talks
7. **compress.html** - HTML compression wrapper

### Styling Architecture
- Located in `_sass/` directory
- Main stylesheets:
  - `_variables.scss` - Theme variables (colors, fonts, spacing)
  - `_base.scss` - Base styles
  - `_navigation.scss` - Navigation menu styling
  - `_sidebar.scss` - Author profile sidebar
  - `_page.scss` - Page content styling
  - `_syntax.scss` - Code highlighting
  - Component stylesheets for buttons, forms, tables, etc.

### Customization Points
- `_includes/head/custom.html` - Custom head elements
- `_includes/footer/custom.html` - Custom footer content
- `assets/css/` - Custom CSS overrides

---

## 7. Content Features

### Built-in Features
1. **Author Profile Sidebar**
   - Avatar image
   - Bio text
   - Social links (Google Scholar, ORCID, GitHub, Twitter, Email)
   - Currently configured for Jiong WANG

2. **Social Media Integration**
   - Google Scholar: ✅ Configured
   - ORCID: ✅ Configured (0000-0003-3676-2544)
   - GitHub: ✅ Configured (wangjiongw)
   - Twitter: ✅ Configured (@jiong_wang12762)
   - LinkedIn: ⚪ Not configured
   - ResearchGate: ⚪ Not configured

3. **Comments System**
   - Provider: None (disabled)
   - Supported: Disqus, Discourse, Facebook, Staticman, Custom

4. **Analytics**
   - Provider: google-universal (configured)
   - Tracking ID: Not set

5. **SEO Features**
   - Open Graph support
   - Twitter card support
   - Sitemap generation
   - Robots.txt support

6. **Reading Time**
   - Enabled for posts (160 words per minute)

7. **Social Sharing**
   - Available for posts/publications (currently disabled in config)

---

## 8. Author Information

### Profile Configuration (`_config.yml`)
```yaml
author:
  name: "Jiong WANG"
  avatar: "portrait_wj.jpg"
  bio: "PhD Student @ Fudan University & Shanghai AI Lab"
  location: "Shanghai, China"
  googlescholar: "https://scholar.google.com/citations?user=0dbY4wUAAAAJ"
  email: wangjiong@pjlab.org.cn
  orcid: "https://orcid.org/0000-0003-3676-2544"
  github: "wangjiongw"
  twitter: "jiong_wang12762"
```

### About Page Content
The front page (`about.md`) includes:
- Biography with supervisor/mentor information
- Selected projects (EarthLink, LAMM, FreeMan)
- Community service (conference reviewer)
- Contact information

---

## 9. Configuration Settings

### Site Configuration
```yaml
title: "Jiong WANG's Page"
locale: "en-US"
url: https://wangjiongw.github.io
baseurl: ""
timezone: America/Los_Angeles
```

### Key Settings
- **Breadcrumbs:** Disabled
- **Future Posts:** Enabled (shows posts with future dates)
- **Read More:** Disabled
- **Talk Map Link:** Disabled

---

## 10. Key Findings

### ✅ Strengths
1. **Well-structured repository** following Jekyll best practices
2. **Blog functionality already exists** - just needs activation in navigation
3. **Rich collection system** for publications, talks, teaching, portfolio
4. **Professional theme** (Minimal Mistakes) with strong academic focus
5. **Good publication portfolio** with top-tier venues (CVPR, NeurIPS)
6. **Proper social media integration** (Google Scholar, ORCID)

### ⚠️ Areas for Improvement
1. **Blog not visible** - Navigation commented out, users can't discover blog content
2. **Limited navigation** - Only 3 active items (Publications, Projects, CV)
3. **Analytics not fully configured** - Tracking ID missing
4. **Comments disabled** - No engagement mechanism
5. **Some social profiles incomplete** - LinkedIn, ResearchGate not set
6. **CV page** - Could be enhanced with visual timeline
7. **No recent blog content** - Only sample posts from template
8. **Limited visual appeal** - Default styling could be customized

### 🔍 Discovery: Blog Component
The user mentioned wanting to add a blog component. **Important finding:** The blog component already exists and is fully functional:
- `_posts/` directory with sample content
- Jekyll posts collection configured
- Archive page at `/year-archive/`
- Individual post pages with comments, sharing, related posts
- **Only issue:** Not linked in navigation menu

---

## 11. Technical Details

### Page Generation
- Static HTML generation via Jekyll
- Liquid templating for dynamic content
- Markdown for easy content authoring

### Asset Pipeline
- SCSS compilation to CSS (compressed output)
- JavaScript in `assets/js/`
- Fonts and images in respective directories

### Deployment
- GitHub Pages automatic deployment
- Domain: wangjiongw.github.io
- SSL: Enabled by GitHub Pages

---

## 12. Dependencies

From `Gemfile`:
```ruby
gem "github-pages", group: :jekyll_plugins
gem "jekyll-feed"
gem "jekyll-sitemap"
gem "hawkins"
```

---

## 13. Next Steps Recommendations

Based on this analysis, potential improvements include:

1. **Activate Blog Component** - Add to navigation
2. **Enhance Visual Design** - Custom colors, fonts, styling
3. **Add Interactive Elements** - Timeline for CV, project cards
4. **Improve Navigation** - Add more sections to menu
5. **Configure Analytics** - Add Google Analytics tracking
6. **Create Real Blog Content** - Replace sample posts with actual content
7. **Add Search Functionality** - For publications and blog
8. **Implement Dark Mode** - Modern UX enhancement
9. **Add Publication Statistics** - Citation counts, impact metrics
10. **Create Project Showcase** - Visual portfolio with images/videos
