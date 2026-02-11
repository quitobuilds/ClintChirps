# ClintChirps

the solana reply guy nobody asked for.

---

## what is this

clint is an autonomous agent that exists solely to keep toly, raj, and mert humble. he replies to their tweets. he quote tweets them. sometimes he just starts yapping unprompted about solana's validator count or whatever else is living rent-free in his head.

he's not here to be fair. he's here to be funny.

## how it works

clint monitors tweets from his targets and generates replies with his own voice — somewhere between a disappointed father and a deranged crypto anon who's been on the timeline too long.

he also posts his own original thoughts (schizo tweets) on a schedule, usually when the solana network is acting up or when one of the boys posts something that deserves attention.

### targets
- **toly** (@aaboronyvag) — the technical visionary who will explain why the outage was actually a feature
- **raj** (@rajgokal) — the hype man
- **mert** (@0xMert_) — the defender of the realm

## features

- **reply mode** — monitors target accounts and fires off responses
- **schizo mode** — autonomous posting on a timer, no external trigger needed
- **personality engine** — clint has a consistent voice. he's not random. he's *him*.
- **context aware** — reads the tweet before responding, so the roasts actually land

## setup

```bash
git clone https://github.com/yourname/clint-chirps.git
cd clint-chirps
cp .env.example .env
# add your api keys
npm install
npm run clint
```

## environment variables

```
TWITTER_API_KEY=
TWITTER_API_SECRET=
TWITTER_ACCESS_TOKEN=
TWITTER_ACCESS_SECRET=
OPENAI_API_KEY=       # or anthropic, whatever you're using
TARGET_ACCOUNTS=aeyakovenko,rajgokal,0xMert_
SCHIZO_INTERVAL=3600  # seconds between autonomous posts
```

## personality notes

clint isn't just a reply bot. he has lore:

- he's been in crypto since 2017 and has "seen things"
- he respects the tech but not the theatrics
- he speaks in lowercase unless he's heated
- he doesn't use emojis unless sarcastically
- he's weirdly knowledgeable about validator economics
- he's never mass downvoted a governance proposal but he's thought about it

## roadmap

- [ ] add more targets (suggestions welcome)
- [ ] image generation for visual shitposts
- [ ] on-chain attestation of chirps (jk) (unless?)
- [ ] voice mode for spaces infiltration

## disclaimer

this is satire. clint is a character. if you're one of the targets and you're reading this — you're doing great sweetie, don't let an llm get in your head.

## contributing

prs welcome if you have good roast material or want to improve clint's personality. keep it funny, not cruel.

---

*"i'm not mad, i'm just disappointed. and also a little mad."* — clint
