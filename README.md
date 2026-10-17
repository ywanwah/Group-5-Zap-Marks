# Our Zap Marks

A small static site that shows four group Zaps on the course's two-by-two map, with a five-line card for each.

## How to update it

Open `index.html` and edit only the `agents` list near the bottom, inside the `<script>` tag:

- `owner` and `name`: who built it and what it is called.
- `quadrant`: `"tl"` (A person leads, AI inside), `"tr"` (Agents run it, a person judges), `"bl"` (AI alone, with checks), `"br"` (A person decides, AI alongside), or `""` if not marked yet.
- `card`: the five lines (Trigger, Action, Filtering, Output, Off switch).

Commit the change on GitHub and Vercel redeploys automatically.

## Keep it safe (this repository is public)

- No email addresses, client data, API keys or exported JSON files.
- Crop email addresses out of any screenshots.
- Turn every Zap off after class on Wednesday 21 October.
