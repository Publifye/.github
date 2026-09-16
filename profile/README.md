## Publifye AS

Norwegian publishing house in Oslo. We publish Bibles and books, build the tools they are studied
and written with, and run those tools as **MCP servers your AI assistant can call directly**.

Registered as PUBLIFYE AS, org.nr [826 774 622](https://virksomhet.brreg.no/nb/oppslag/enheter/826774622)
· publishing since 2016 · [publifye.com](https://publifye.com)

---

### Five hosted MCP servers

Paste this into your MCP client and sign in from the browser — OAuth 2.1 with PKCE and open
Dynamic Client Registration, so there is no key to create first and nothing to install.

```jsonc
{
  "mcpServers": {
    "darash":  { "type": "http", "url": "https://darash-api.publifye.com/mcp" },
    "junifye": { "type": "http", "url": "https://junifye.publifye.com/mcp" },
    "lexifye": { "type": "http", "url": "https://lexifye.publifye.com/mcp" },
    "brreg":   { "type": "http", "url": "https://brreg.publifye.com/mcp" },
    "lexar":   { "type": "http", "url": "https://lexar-api.publifye.pro/mcp" }
  }
}
```

Take only the lines you want — each server stands alone.

| | What it gives your assistant | |
|---|---|---|
| **Darash** | The Hebrew and Greek text as data — 59 translations, word-by-word morphology, 446,544 cross-references, 13 dictionaries and four scholarly lexicons | [site](https://darash.publifye.com) · [docs](https://darash.publifye.com/docs) |
| **Junifye** | Write a book, study or sermon series with your AI, then publish it — print-ready PDF, EPUB 3, web reader, real ISBN | [site](https://junifye.publifye.com) |
| **Lexifye** | Build a dictionary with versions, per-definition sources and revert | [site](https://lexifye.publifye.com) · [docs](https://lexifye.publifye.com/docs) |
| **Brreg** | Norwegian organisations by number or by name, from Enhetsregisteret, with key financials | [site](https://brreg.publifye.com) |
| **Lexar** | The current text of Norwegian law from Lovdata — statutes, central regulations, announcements | [site](https://lexar.publifye.com) |

**→ [Publifye/mcp](https://github.com/Publifye/mcp)** — every tool with its full input schema, and
the provenance of every dataset behind them. Generated from the live services, not written by hand.

---

### We publish what we could not prove

The reference repository states, for each dataset, the printed edition, the licence, and **what is
not established about it**. That is unusual and deliberate.

We once served a dictionary under the name *Thayer* that was not Thayer. We found it, archived the
old text with its digest, and rebuilt the lexicon from the 1889 page scans: 716 pages, two
collated transcription passes agreeing at 98.91% across 856,793 tokens, five rounds of adversarial
review, and a rule that no character may exist in the shipped text that is not on the page. An
ambiguous headword refuses to resolve rather than guess.

Lexar publishes the share of legal cross-references that point *outside* its corpus — about 57% —
rather than only the ones that resolve. Brreg says in every response that it is not the
authoritative register.

A corpus that claims perfection has stopped looking.

---

### Also from us

[blog.publifye.com](https://blog.publifye.com) — how this work is done, in English, Norwegian,
Spanish, Chinese and Korean · [tbtm.sale](https://tbtm.sale) — 4,200+ DRM-free ePub Bibles in 30+
languages · [publifye.org/gift](https://publifye.org/gift) — free Bibles for churches and missions

[Privacy](https://publifye.com/privacy.html) · [Terms](https://publifye.com/terms.html) ·
[Contact](https://publifye.com/connect.html)
