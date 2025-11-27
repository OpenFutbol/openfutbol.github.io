# OpenFutbol

Open-source platform applying FAIR principles to community soccer infrastructure.

## About

OpenFutbol makes existing soccer infrastructure more discoverable. The platform is agnostic — it doesn't favor any organization. It helps surface what already exists in communities and bridges technology gaps for organizations that lack digital resources.

**Live:** [openfutbol.github.io](https://openfutbol.github.io)

## Platform

### Community Soccer
Find pickup games across Chicago neighborhoods. Interactive map with organization directory and game listings.

→ [openfutbol.github.io](https://openfutbol.github.io)

### Youth Programming
Transparent directory of youth soccer programs. Helps families find programs and helps grassroots organizations get discovered.

→ [openfutbol.github.io/youth.html](https://openfutbol.github.io/youth.html)

## FAIR Principles

This project applies data science principles to community sports infrastructure:

| Principle | Application |
|-----------|-------------|
| **Findable** | Organizations discoverable by search, maps, and directories |
| **Accessible** | No login required, mobile-friendly, open data |
| **Interoperable** | Standard formats, linkable resources, API-ready architecture |
| **Reusable** | Fork for your city, MIT license, documented codebase |

## Tech Stack

- **Frontend**: Vanilla HTML, CSS, JavaScript
- **Maps**: Leaflet.js with OpenStreetMap
- **Fonts**: Inter + Space Grotesk (Google Fonts)
- **Hosting**: GitHub Pages with Jekyll
- **Design**: CSS custom properties, responsive grid

No framework dependencies. Easy to understand, modify, and deploy.

## Project Structure

```
openfutbol.github.io/
├── index.html              # Community Soccer webapp
├── youth.html              # Youth Programming webapp
├── developers.html         # Contributor information
├── assets/
│   └── css/main.css        # Design system
├── favicon.svg             # Site favicon
├── _config.yml             # Jekyll configuration
├── Gemfile                 # Ruby dependencies
├── .github/
│   └── CODEOWNERS          # Repository ownership
├── CONTRIBUTING.md         # Contribution guidelines
└── README.md               # This file
```

## Local Development

### Prerequisites
- Ruby 2.5+ with Bundler
- Git

### Setup
```bash
git clone https://github.com/openfutbol/openfutbol.github.io.git
cd openfutbol.github.io
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`

### Quick Edit
For simple changes, you can edit HTML/CSS directly and open `index.html` in a browser. Jekyll is only needed for the build pipeline.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Quick ways to contribute:
- **Add organizations** — Open an issue with org details
- **Improve maps** — Add neighborhoods, fix coordinates
- **Build features** — Check issues for roadmap items
- **Fork for your city** — Architecture is city-agnostic

## Roadmap

- [ ] Meetup API integration for live game data
- [ ] Organization submission form
- [ ] Multi-city support architecture
- [ ] Working search and filters
- [ ] Calendar aggregation

## Links

- [NBHD Soccer](https://nbhdsoccer.github.io) — Community partner
- [Chicago Neighborhood Soccer](https://www.meetup.com/chicago-neighborhood-soccer/) — Meetup group
- [GitHub Organization](https://github.com/openfutbol)

## License

MIT License — see [LICENSE](LICENSE) for details.

## Creator

**Andre D Paredes**
GitHub: [@ADParedes](https://github.com/ADParedes)

---

Built in partnership with [NBHD Soccer](https://nbhdsoccer.github.io), an Illinois 501(c)(3) nonprofit.
