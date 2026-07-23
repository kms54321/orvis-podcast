# Orvis Podcast Archive Feeds — Done

Two finished feeds. Pick one, host it, subscribe in Overcast.

| File | Episodes | Range |
|---|---|---|
| `feed_pre2022.xml` | 481 | Apr 2008 – Dec 2021 |
| `feed_full.xml` | 701 | Apr 2008 – Jul 2026 |

**Use `feed_pre2022.xml`** — that's the material Overcast lost, with no
duplication of your existing subscription. `feed_full.xml` is there if you'd
rather have everything in one place and drop the original subscription.

All 701 episodes matched a publication date. Nothing dropped, nothing undated.

---

## Host it

Must be served over **HTTPS**. Free options:

**GitHub Pages** — new public repo, commit the .xml, Settings → Pages →
deploy from `main` / root. URL: `https://<user>.github.io/<repo>/feed_pre2022.xml`

**Cloudflare Pages** — connect a repo or drag the file in.

**Netlify** — drag-and-drop, no git.

**Neocities** — plain upload, lowest friction.

All four serve `.xml` with the right content type automatically.

---

## Subscribe

Overcast → **+** (top right) → **Add URL** → paste your feed URL.

Free tier. Add URL is not a Premium feature — that's uploads, which this
doesn't use. Playback position, Smart Speed, and Voice Boost all work.

---

## Notes

- The feed **references** Orvis's own MP3 URLs. Nothing is rehosted.
- 19 entries are video episodes (`.mp4`), tagged as `video/mp4`. Overcast
  handles them; skip them if you'd rather not see them.
- No episode artwork — the feed has no channel image. Harmless.
- The feed URL is unlisted, not private. Anyone with the link could
  subscribe. It points at public Orvis audio, so no real exposure.
- If Orvis ever moves or expires those MP3 URLs, the feed breaks.
- For your own listening. Don't submit it to a podcast directory.

---

## Worth doing anyway

Email `podcast@orvis.com` and ask them to raise the Libsyn episode limit.
The old episodes are live on their own site — it's a feed setting, not
missing media. That fix restores the back catalog for every listener.
