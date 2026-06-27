```
PART I: WEB-PAGES

├── Home
├── Philosophy
├── Solutions & Engineering
└── Get in Touch

--------------------------------------
PART II: WEB-PAGES EXPANDED

Home Page
│
├── HERO SECTION
│   ├── Title
│   ├── Description
│   ├── Background Image
│   └── CTA Button
│
├── PHILOSOPHY SECTION
│   ├── Title
│   ├── Tags[]
│   └── Description
│
├── SOLUTIONS AND ENGINEERING SECTION
│   └── Projects[]
│       ├── Name
│       ├── Logo
│       ├── Link
│       └── Description
│
└── Footer

-----------------------------------------
PART III: FOLDER STRUCTURE

sovereon-v2/
│
├── public/
│   ├── favicon.svg
│   ├── images/
│   └── fonts/
│
├── src/
│
│   ├── pages/
│   │   ├── index.astro                         # Home
│   │   ├── philosophy.astro                    # Philosophy
│   │   ├── solutions_and_engineering.astro     # Core services / microsaas hub
│   │   └── get_in_touch.astro                  # Contact page
│   │
│   │   └── solutions/                          # optional future expansion
│   │       ├── saas-1.astro
│   │       ├── saas-2.astro
│   │       └── saas-3.astro
│
│   ├── layouts/
│   │   ├── BaseLayout.astro     # global wrapper (nav + footer + SEO)
│   │   └── PageLayout.astro     # standard page layout wrapper
│
│   ├── components/
│   │
│   │   ├── layout/
│   │   │   ├── Navbar.astro
│   │   │   ├── Footer.astro
│   │   │   └── Container.astro
│   │   │
│   │   ├── home/
│   │   │   ├── Hero.astro
│   │   │   ├── IntroSection.astro
│   │   │
│   │   ├── philosophy/
│   │   │   ├── PhilosophyHero.astro
│   │   │   ├── PrincipleCard.astro
│   │   │   └── PhilosophyGrid.astro
│   │   │
│   │   ├── solutions/
│   │   │   ├── SolutionsHero.astro
│   │   │   ├── ServiceCard.astro
│   │   │   └── ServiceGrid.astro
│   │   │
│   │   ├── contact/
│   │   │   ├── ContactForm.astro
│   │   │   ├── ContactHero.astro
│   │   │
│   │   └── ui/
│   │       ├── Button.astro
│   │       ├── Section.astro
│   │       └── Badge.astro
│
│   ├── content/
│   │   ├── philosophy/
│   │   │   ├── vision.md
│   │   │   ├── principles.md
│   │   │
│   │   ├── solutions/
│   │   │   ├── microsaas-list.md
│   │   │   ├── automation.md
│   │   │   └── engineering.md
│
│   ├── data/
│   │   ├── navigation.ts
│   │   ├── services.ts
│   │   └── siteConfig.ts
│
│   ├── lib/
│   │   ├── seo.ts
│   │   ├── format.ts
│   │   └── cn.ts
│
│   ├── styles/
│   │   └── global.css
│
├── astro.config.mjs
├── package.json
└── tailwind.config.js


```