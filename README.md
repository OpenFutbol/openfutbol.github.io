# OpenFutbol Chicago

> **Open-source platform connecting pickup soccer communities**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://openfutbol.github.io)
[![Open Source](https://img.shields.io/badge/Open%20Source-❤️-red)](https://github.com/OpenFutbol)
[![Powered by NBHD Soccer](https://img.shields.io/badge/Powered%20by-NBHD%20Soccer-blue)](https://nbhdsoccer.github.io)

Find pickup soccer games across Chicago neighborhoods through our interactive map platform. Built with open-source principles and powered by the [NBHD Soccer](https://nbhdsoccer.github.io) community.

## 🌟 Features

- **Interactive Chicago Map** with real neighborhood positioning
- **Geographic Accuracy** based on actual Chicago layout with Lake Michigan, Chicago River
- **Frequency Indicators** showing how often games happen in each area
- **Professional Design** with Chicago flag-inspired colors
- **Mobile Responsive** optimized for all devices
- **SEO Optimized** for discovery through search
- **NBHD Soccer Integration** connecting to weekly Meetup games

## 🚀 Technology

Built using modern web technologies optimized for GitHub Pages:

- **Vanilla HTML/CSS/JavaScript** - Fast, accessible, no heavy frameworks
- **Jekyll** - Static site generation with GitHub Pages optimization
- **Chicago Flag Color Palette** - Professional nonprofit design
- **Geographic SVG** - Interactive map with real Chicago features
- **NBHD Soccer Branding** - Partnership with established community organization

## 🛠️ Local Development

### Prerequisites
- Ruby 2.5+ with Bundler
- Git
- Modern web browser

### Setup
```bash
# Clone the repository
git clone https://github.com/OpenFutbol/openfutbol.github.io.git
cd openfutbol.github.io

# Install dependencies
bundle install

# Start local development server
bundle exec jekyll serve

# Visit http://localhost:4000
```

### File Structure
```
├── index.html                 # Main pickup finder (Chicago)
├── chicago-pickup-soccer.html # SEO-optimized Chicago page
├── _config.yml               # Jekyll configuration
├── Gemfile                   # Dependencies
├── README.md                 # This file
├── robots.txt               # SEO configuration
├── assets/img/              # Images and logos
└── .github/workflows/       # GitHub Pages deployment
```

### Development Notes
- Site auto-reloads on file changes during development
- All CSS is inline in HTML files for simplicity
- Interactive map uses vanilla JavaScript

## 🌐 GitHub Pages Deployment

### How it Works
OpenFutbol automatically deploys to GitHub Pages using GitHub Actions:

1. **Push to `main` branch** triggers automatic deployment
2. **Jekyll builds** the static site from your HTML/CSS/JS
3. **GitHub Actions** deploys to `https://openfutbol.github.io`
4. **Global CDN** serves your site worldwide

### Timeline
- **Code push → build start**: Immediate
- **Build completion**: 1-5 minutes
- **Global deployment**: 5-10 minutes for worldwide CDN

### Success Indicators
- ✅ Green checkmark in GitHub Actions tab
- ✅ New commit SHA in GitHub Pages settings
- ✅ Site accessible at openfutbol.github.io

### Troubleshooting Failed Builds
If deployment fails:
1. **Check GitHub Actions tab** for error details
2. **Test locally first**: `bundle exec jekyll serve`
3. **Common issues**: Missing frontmatter, invalid YAML in `_config.yml`
4. **Verify file structure**: Ensure `index.html` exists in root

### Best Practices
- **Test locally** before pushing to main
- **Small commits** for easier debugging
- **Monitor GitHub Actions** after pushing
- **Check build logs** if deployment fails

## 🏙️ Current Status

**Chicago (Live)**: Fully operational with 8+ neighborhoods mapped
- **Active Games**: Weekly YMCA Rauner games via NBHD Soccer Meetup
- **Neighborhoods**: Logan Square, Wicker Park, Pilsen, Bridgeport, and more
- **Community**: 50+ regular players through NBHD Soccer network
- **SEO**: Optimized landing page at `/chicago-pickup-soccer.html`

**Expansion**: Framework ready for other cities - see our expansion roadmap in the main OpenFutbol organization.

## 🤝 Get Involved

### For Players
- **Join games**: Visit [NBHD Soccer Meetup](https://www.meetup.com/chicago-neighborhood-soccer/) for weekly pickup
- **Explore neighborhoods**: Use our interactive map to discover new areas
- **Community**: Connect with Chicago's pickup soccer network

### For Organizers
- **Start a chapter**: Use our Chicago model as a framework for your city
- **Community building**: Learn from NBHD Soccer's grassroots approach
- **Open source**: All code and organizing methods freely available

### For Developers
- **Contribute code**: Improve the platform, add features, fix bugs
- **City expansion**: Help adapt the framework for new cities
- **Open source**: MIT licensed, community-driven development

## 📞 Contact

- **GitHub Organization**: [@OpenFutbol](https://github.com/OpenFutbol)
- **Chicago Games**: [NBHD Soccer Meetup](https://www.meetup.com/chicago-neighborhood-soccer/)
- **Issues & Contributions**: [GitHub Issues](https://github.com/OpenFutbol/openfutbol.github.io/issues)
- **NBHD Soccer**: [nbhdsoccer.github.io](https://nbhdsoccer.github.io)

## 🏆 Recent Updates

- **July 2025**: Complete redesign with Chicago map accuracy and NBHD Soccer partnership
- **Professional color scheme**: Chicago flag-inspired design
- **Enhanced SEO**: Dedicated Chicago pickup soccer landing page
- **Community integration**: Direct links to active Meetup games
- **Mobile optimization**: Responsive design for all devices

---

**OpenFutbol Chicago** - *Making pickup soccer accessible, one neighborhood at a time* ⚽

Powered by [NBHD Soccer](https://nbhdsoccer.github.io) 🤝 Built with ❤️ in Chicago