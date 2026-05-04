FORGE Platform — Combined V1 + V2
==================================

FOLDER STRUCTURE
  v1/   → Original FORGE spec site (5-agent pipeline, no Architecture Agent)
  v2/   → Updated FORGE spec site (6-agent pipeline, Architecture Agent, Swim Lanes)

NETLIFY SETUP
  V1 site: set Publish directory = v1
  V2 site: set Publish directory = v2
           set Functions directory = v2/netlify/functions
           add env var: ANTHROPIC_API_KEY

TOML FILES (for reference — Netlify reads these automatically)
  netlify-v1.toml  → V1 build config
  netlify-v2.toml  → V2 build config

See full setup instructions at theforgeplatform.netlify.app
