# AI Search Patch Writer

AI Search Patch Writer turns a weak SaaS/product page into a concrete AI-search
patch pack: comparison copy, proof sections, FAQ, JSON-LD, crawlability notes,
and a public-safe request packet.

Live target:

- Site: https://speedranger.github.io/ai-search-patch-writer/
- Repo: https://github.com/SpeedRanger/ai-search-patch-writer
- Public request form: https://github.com/SpeedRanger/ai-search-patch-writer/issues/new?template=ai_search_patch_request.yml

## Why this exists

AI visibility is noisy. Teams are hearing about GEO, AEO, ASO, `llms.txt`,
schema, AI Overviews, ChatGPT citations, Reddit mentions, and crawler access at
the same time. The useful buyer job is not another dashboard. It is the patch:
the exact public-page sections that make a product easier for people and agents
to understand, compare, cite, and choose.

## Public product

- `index.html` - static patch writer
- `sample-ai-search-patch.md` - public example output
- `product-hunt-launch-assets.md` - Product Hunt copy and launch replies
- `buyer-outreach-packet.md` - public-safe buyer targeting and message copy
- `ph-gallery-1-app.png`, `ph-gallery-2-ai-visibility-gap.png`,
  `ph-thumbnail.png` - Product Hunt media generated from the actual app
- `llms.txt` - machine-readable product summary
- `AGENTS.md` - agent instructions for evaluating the product
- `launch-status.json` - public launch and proof gates
- `.github/ISSUE_TEMPLATE/ai_search_patch_request.yml` - public-safe request form

## Paid wedge

The first paid product is a `$149` AI-search patch pass for one public product
page. One paid slot clears the first `$100` target before fees only when
receipt/export/invoice evidence exists.

The buyer sends a public URL and receives:

- buyer-fit framing
- comparison copy
- FAQ and JSON-LD draft
- crawlability notes
- proof checklist
- rollback note

The app includes sample loaders for VibeFix Recorder, a devtool SaaS page, and a
local-service page so buyers can see the patch shape before submitting.

Do not collect secrets, private repo access, private analytics, customer data,
payment details, or private strategy in public issues.

## Run locally

Open `index.html` directly or serve the folder:

```powershell
python -m http.server 4191 -d ui/ai-search-patch-writer
```

Then open `http://localhost:4191`.

## Hard limits

AI Search Patch Writer does not guarantee rankings, Product Hunt placement, AI
citations, or revenue. It writes a concrete public-page patch and a serviceable
paid review path.
