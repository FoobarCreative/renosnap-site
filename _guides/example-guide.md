---
published: false                # Delete this line to publish the guide.
title: "How to Do Something on iPhone (Long-Tail Keyword Title)"
short_title: "Do Something"     # Used in breadcrumbs and related-guide cards.
description: "One or two sentences answering the search intent — shown under the title and on the guides index."
settings_url: "photos-redirect://"   # Optional deep link button (e.g. photos-redirect://, App-prefs:root=CASTLE). Omit to hide.
cta_label: "Open Photos →"
date: 2026-01-01
last_updated: 2026-01-01
item_id: "example_guide"        # Unique ID other guides can reference in their `related` list.
redirect_from:
  - /guides/example-guide/
related:                        # Optional list of other guides' item_ids, shown as cards at the end.
  - another_guide_item_id
---

Open with a sentence that meets the searcher where they are, then explain the fix.

## Step-by-step

### 1. First step

Keep each step to one action. Put images in their own paragraph (blank line before the `![...]` line) so they render as blocks:

![Describe the screenshot](/assets/guides/example-guide/step-1.webp)

### 2. Second step

✅ **Done!** Tell the reader what they achieved.

## Tips

- Guides live in `_guides/` and are published at `/guides/<filename>`.
- Set `enable_guides: true` in `_config.yml` to link the `/guides` index from the header and footer.
- Keep guide images at ~640px wide WebP; they display capped at 414px and centered.
