# Hostinger Promotional Jekyll Site

This is a Jekyll-based website designed to promote Hostinger web hosting services and the Horizon AI website builder.

## Project Structure

```
jekyll-hostinger-promo/
├── _config.yml                  # Jekyll configuration file
├── _layouts/                    # Layout templates
│   ├── default.html             # Main layout template
│   └── page.html                # Page layout template
├── _includes/                   # Reusable components
│   ├── header.html              # Site header with navigation
│   ├── footer.html              # Site footer with links
│   └── cta.html                 # Call-to-action component
├── _sass/                       # SCSS files
│   ├── main.scss                # Main stylesheet
│   └── _variables.scss          # CSS variables
├── assets/                      # Static assets
│   ├── css/                     # Compiled CSS
│   ├── js/                      # JavaScript files
│   └── images/                  # Site images
├── _posts/                      # Blog posts about hosting
├── pages/                       # Additional pages
│   ├── about.md                 # About page
│   ├── horizon.md               # Dedicated Horizon service page
│   └── pricing.md               # Pricing information
├── index.md                     # Homepage
├── Gemfile                      # Ruby dependencies
└── README.md                    # Project documentation
```

## Features

- Clean, semantic HTML5 structure with Jekyll templating
- Modern, professional CSS styling using SCSS
- Multiple content sections highlighting Hostinger's features and benefits
- Special emphasis on the Horizon AI website builder service
- All links to Hostinger use the provided referral link: https://hostinger.it?REFERRALCODE=RABBITWORLD
- Proper Jekyll directory structure with layouts, includes, and content pages
- Responsive design that works well on all devices
- Clear calls-to-action throughout the site

## Getting Started

### Prerequisites

- Ruby version 2.7.0 or higher
- RubyGems
- GCC and Make

### Installation

1. Clone this repository
2. Install dependencies:
   ```
   bundle install
   ```
3. Run the Jekyll site locally:
   ```
   bundle exec jekyll serve
   ```
4. Open your browser and navigate to `http://localhost:4000`

## Customization

- Edit `_config.yml` to change site-wide settings
- Modify SCSS files in `_sass/` to adjust styling
- Update content in `pages/` and `_posts/` directories
- Add images to `assets/images/` directory

## Deployment

This site can be deployed to any static site hosting service like GitHub Pages, Netlify, or Vercel.

## License

This project is created for promotional purposes for Hostinger services.