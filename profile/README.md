# Publifye AS

We are a small publishing house in Oslo. We publish Bibles and books, and we build the tools we use
to write and study them. Those tools run as MCP servers, so your AI assistant can use them directly.

Registered in Norway as PUBLIFYE AS, org.nr 826 774 622. Publishing since 2016. [publifye.com](https://publifye.com)

## Ten servers you can connect today

Add any of these to Claude, Cursor or another MCP client. The first time you use one, you sign in
from your browser. There are no keys to create and nothing to install.

```json
{
  "mcpServers": {
    "darash":     { "type": "http", "url": "https://darash-api.publifye.com/mcp" },
    "junifye":    { "type": "http", "url": "https://junifye.publifye.com/mcp" },
    "lexifye":    { "type": "http", "url": "https://lexifye.publifye.com/mcp" },
    "audiobible": { "type": "http", "url": "https://audiobible.publifye.com/mcp" },
    "doksi":      { "type": "http", "url": "https://doksi.publifye.com/mcp" },
    "timely":     { "type": "http", "url": "https://timely.publifye.com/mcp" },
    "brreg":      { "type": "http", "url": "https://brreg.publifye.com/mcp" },
    "lexar":      { "type": "http", "url": "https://lexar-api.publifye.com/mcp" },
    "currency":   { "type": "http", "url": "https://currency.publifye.com/mcp" },
    "vitae":      { "type": "http", "url": "https://vitae.publifye.com/mcp" }
  }
}
```

You don't need all of them. Pick the ones you want.

### For Bible study and writing

| | |
|---|---|
| **[Darash](https://darash.publifye.com)** | Read the Bible in Hebrew and Greek with your assistant. Look up any word, see how it is used elsewhere, and check what the dictionaries say. |
| **[Audio Bible](https://audiobible.publifye.com)** | The World English Bible, read aloud. Listen to any chapter or download it. |
| **[Junifye](https://junifye.publifye.com)** | Write a book, a Bible study or a sermon series with your assistant, then publish it as a PDF, an ebook and a web page. |
| **[Lexifye](https://lexifye.publifye.com)** | Build a dictionary of the words you use, with sources for every definition and a full history of changes. |

### For churches and organisations

| | |
|---|---|
| **[Doksi](https://doksi.publifye.com)** | Turn letters, agreements, agendas and checklists into clean PDFs, and collect signatures by link or QR code. |
| **[Timely](https://timely.publifye.com)** | Plan a series of meetings, keep the programme up to date, and share it on your website and as a printed PDF. Nothing is published until a person approves it. |

### For yourself

| | |
|---|---|
| **[Vitae](https://vitae.publifye.com)** | Keep your CV as a document you own, in more than one language, and turn it into a clean PDF. Nobody sees it until you publish it. |

### For Norwegian public data

| | |
|---|---|
| **[Brreg](https://brreg.publifye.com)** | Look up Norwegian companies by name or number, with key figures from their annual accounts. |
| **[Lexar](https://lexar.publifye.com)** | Read the current text of Norwegian laws and regulations from Lovdata, with the source for every passage. |
| **[Currency](https://currency.publifye.com)** | Exchange rates from Norges Bank, back to about 1980. |

Every tool on every server, with its full input schema, is documented in
**[Publifye/mcp](https://github.com/Publifye/mcp)**. That repository also records where each dataset
comes from and what licence it is under.

## We tell you what we don't know

For every dataset we say which printed edition it comes from, which licence it is under, and what we
could not confirm about it.

We once served a Greek lexicon under the name Thayer that turned out not to be Thayer. When we
found out, we kept a record of the old text and rebuilt the lexicon from scans of the 1889 printed
edition, all 716 pages, checked twice against each other. If a headword is ambiguous, the tool tells
you so instead of guessing.

Lexar tells you how many legal cross-references point to laws outside what it holds (about 57%),
not just the ones it can follow. Brreg reminds you in every answer that it is not the official
register.

## Also from us

- [blog.publifye.com](https://blog.publifye.com): how we do this work, in English, Norwegian, Spanish, Chinese and Korean
- [tbtm.sale](https://tbtm.sale): over 4,000 DRM-free ePub Bibles in more than 30 languages
- [publifye.org/gift](https://publifye.org/gift): free Bibles for churches and missions

[Privacy](https://publifye.com/privacy.html) · [Terms](https://publifye.com/terms.html) · [Contact](https://publifye.com/connect.html)
