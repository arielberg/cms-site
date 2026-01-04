# cms-site

Demo portal for js.cms - a modular static site CMS.

## Setup

This repository contains js.cms as a git submodule. To get started:

1. **Clone the repository:**
   ```bash
   git clone --recurse-submodules <repository-url>
   ```
   
   Or if already cloned:
   ```bash
   git submodule update --init --recursive
   ```

2. **Start the demo:**
   ```bash
   cd js.cms
   python3 -m http.server 8080
   ```
   
   Then open http://localhost:8080 in your browser.

## Documentation

- See `demo/README.md` for detailed demo setup instructions
- See `js.cms/README.md` for js.cms documentation and features
- See `js.cms/QUICKSTART.md` for quick start guide
