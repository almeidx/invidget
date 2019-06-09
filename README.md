# invidget
SVG invite widgets that look just like the ones on the Discord client!

**THIS PROJECT IS WIP!**

### Planned features
- [ ] Unit Tests
  - [x] Code Style
  - [ ] strings.json
    - [ ] JSON lint
    - [ ] ISO ISO 639-1 language codes
    - [ ] Required strings exist
- [x] Generate and serve SVGs
- [ ] Make the SVG look like the discord invite widget
- [ ] Automatically deploy to cloudflare through CircleCI

### Setting up a development environment
- Clone this repo
- `npm install`
- Run `npm start webpack-watch` and `npm start cloudworker`

### String guidelines
- Language codes should be in [ISO 639-1](https://en.wikipedia.org/wiki/ISO_639-1) format
- If Discord supports the language you're adding,  strings should perfectly match the ones on the client (capitalization too!)
- [Check if your JSON is valid](https://jsonlint.com/)
