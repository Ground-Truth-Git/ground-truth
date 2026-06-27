# GroundTruth - Project Tracker

## Status
Build session 1 complete. Site at launch-candidate status for initial review.

## Decisions locked

- Site name: **GroundTruth** (styled as one word, capital G and T)
- Hosting: Netlify free subdomain (no custom domain yet)
- GitHub: NEW anonymous account - Josh to create manually (new email first)
- Visual language: dark navy (#0A0F1E), sans-serif led (Inter + DM Serif Display), monospaced diagnostic codes (JetBrains Mono) - fully distinct from theMap
- Author presence: none on site - framework speaks for itself
- Homepage lead: ten failure modes with FM-01 through FM-10 diagnostic codes
- Secondary CTA: AI prompt tool
- LinkedIn post angle: civic/democracy problem
- No connection to theMap in any direction - different hosting, GitHub, email, visual language

## Files

- `index.html` - complete single-page site
- `netlify.toml` - redirect config
- `LINKEDIN-POST.md` - draft post, do not publish until domain confirmed

## Setup steps still needed (Josh to do manually)

1. Create new ProtonMail (or similar) - no connection to existing accounts
2. Create new GitHub account using that email
3. Create new repo (suggested name: `groundtruth-site` or `evframework`)
4. Run these commands from /home/claude/evframework/ (with new GitHub credentials):
   ```
   git init
   git add .
   git commit -m "Initial build"
   git branch -M main
   git remote add origin https://github.com/NEWACCOUNT/NEWREPO.git
   git push -u origin main
   ```
5. Connect new GitHub repo to Netlify (netlify.com > New site from Git)
6. Note the actual subdomain Netlify assigns
7. Update LINKEDIN-POST.md with real URL before posting

## Content decisions locked

- Ten failure modes: FM-01 through FM-10 with diagnostic code styling
- Five-band rating with credence intervals (anchored to intel community + legal standards)
- Mirror rule: full text on site
- Eight source categories
- Universal AI prompt (rewritten from source, topic-neutral, no conflict references)

## Standing rules

- Plain hyphens only, no em dashes
- No Wikipedia sourcing
- No connection to theMap - not in code, not in prose, not in git history
- Mobile-first throughout
- Proactively critique all public moves before Josh acts

## Outstanding

- Josh to review site visually and confirm design direction
- Confirm Netlify subdomain
- Final check: nothing in HTML source that fingerprints theMap authorship
- LinkedIn post timing decision (suggest Tue/Wed morning Melbourne)
