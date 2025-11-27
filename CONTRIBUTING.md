# Contributing to OpenFutbol

Thanks for your interest in contributing to OpenFutbol. This project aims to make community soccer infrastructure more discoverable using FAIR principles.

## Ways to Contribute

### Add an Organization
Know a soccer organization that should be listed? Open an issue with:
- Organization name
- What they do (pickup games, youth programs, leagues, etc.)
- Neighborhoods/areas served
- Contact info or website
- Any relevant tags (coed, women's, youth ages, etc.)

### Improve the Map
- Add new neighborhood markers
- Fix coordinates for existing locations
- Enhance popup information

### Build Features
Check the [issues](https://github.com/openfutbol/openfutbol.github.io/issues) for items on the roadmap:
- Meetup API integration
- Organization submission form
- Search and filter functionality
- Multi-city architecture

### Fork for Your City
The codebase is designed to be city-agnostic. Fork the repo, update the neighborhood data, and deploy for your community.

## Development Setup

```bash
# Clone the repo
git clone https://github.com/openfutbol/openfutbol.github.io.git
cd openfutbol.github.io

# Install dependencies
bundle install

# Run locally
bundle exec jekyll serve

# View at http://localhost:4000
```

For simple HTML/CSS changes, you can edit files directly and open in a browser without Jekyll.

## Project Structure

```
index.html          → Community Soccer webapp
youth.html          → Youth Programming webapp
developers.html     → Developer/contributor info
assets/css/main.css → Design system and styles
```

## Code Style

- Vanilla HTML/CSS/JS (no frameworks)
- CSS custom properties for theming
- Semantic HTML
- Mobile-first responsive design
- Keep it simple and readable

## Pull Requests

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/add-neighborhood`)
3. Make your changes
4. Test locally
5. Commit with a clear message
6. Push and open a PR

## Questions?

Open an issue or reach out to [@ADParedes](https://github.com/ADParedes).

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
