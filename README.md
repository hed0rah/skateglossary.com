# Skateboarding Tricks Glossary

A comprehensive, searchable reference for skateboarding tricks - from fundamentals to obscure variations.

## Features

- **268 unique tricks** with detailed descriptions
- **Smart search** - handles abbreviations (fs, bs, cab) and spaces
- **Multi-select filtering** - terrain, style, difficulty (AND logic)
- **S.K.A.T.E random picker** - respects active filters
- **Historical context** - inventor credits and origins
- **Obstacle reference** - street, transition, and bowl terminology
- **Video links** - 15+ tricks with example videos
- **Dark theme** - brutalist terminal aesthetic

## Quick Deploy to Railway

1. Fork or clone this repo
2. Connect to Railway
3. Railway will auto-detect the Dockerfile
4. Deploy!

No build configuration needed - just point and deploy.

## Local Development

```bash
# Serve locally with any static server
python -m http.server 8000
# or
npx serve .
```

Then open http://localhost:8000

## Tech Stack

- Single-file HTML with embedded CSS/JS
- No dependencies, no build process
- Nginx for production serving
- 200KB total size

## Features Breakdown

### Search
- Space-aware matching ("bigger flip" finds "Biggerflip")
- Abbreviation expansion (fs→frontside, bs→backside)
- Excludes nomenclature section from results

### Filters
- **Terrain**: Flatground, Ledge, Rail, Gap, Transition, Vert, Bank
- **Style**: Old School, Technical, Grab
- **Difficulty**: Fundamental, Advanced, Rare
- Multi-select with AND logic

### Content
- Fundamentals (Ollie, Kickflip, etc.)
- Grinds (50-50, Smith, Feeble, etc.)
- Flips (Hardflip, Laser, Impossible, etc.)
- Grabs (Indy, Stalefish, Method, etc.)
- Weird tricks (Nerd Flip, Dragon Flip, etc.)
- Kook stuff (what NOT to do)

## Contributing

### Submit Tricks or Videos
Click the "SUBMIT TRICK / VIDEO" button in the glossary, or email:
**killengn77@gmail.com**

Include:
- Trick name
- Description
- Video link (optional)
- Any additional context

### Code Contributions
Pull requests welcome! Priority areas:
- Additional video links
- Missing tricks from weskate.com list
- Corrections to existing definitions
- New features

## Credits

**Maintainer**: Shekk  
**Assistant**: Claude (Anthropic)  
**Development Time**: 40+ hours over multiple sessions  
**Last Updated**: 2026-02-03

## License

This project is open source. Feel free to use, modify, and distribute.

---

**Live Site**: [Deploy your own on Railway →](https://railway.app)  
**Portfolio**: [hed0rah.github.io](https://hed0rah.github.io)
