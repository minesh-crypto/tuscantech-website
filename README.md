# TuscanTech IT Services — Website (Antigravity project)

Open this folder in Antigravity and prompt the agent — `AGENTS.md` gives it full
project context (brand tokens, hard facts, conventions).

## Run locally
No build step. Either open `index.html` directly, or serve it:

    python3 -m http.server 8000
    # → http://localhost:8000

## Structure
    index.html          the entire site (embedded CSS + JS)
    assets/logo-dark.png    logo for light backgrounds (nav)
    assets/logo-light.png   logo for dark backgrounds (footer)
    AGENTS.md           agent/brand instructions
