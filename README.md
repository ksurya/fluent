# Fluent

A simple Markdown editor with live preview. Write freely, adjust the page to suit
you, and keep your notes in your browser.

## Start writing

Choose either option:

- **Open online:** [ksurya.github.io/fluent](https://ksurya.github.io/fluent/).
- **Download:** Open [index.html](./index.html), use GitHub's **Download raw file**
  button, and open the downloaded file in your browser. This copy works offline.

No installation is needed. The editor focuses when you open it, so you can start
typing. On phones, tap the page if needed to bring up the keyboard.

Fluent formats Markdown as you type. Click formatted text to edit it; the relevant
Markdown symbols reappear as you move the cursor through them. Your original text
stays intact. Leave a blank line between paragraphs or different kinds of blocks.
Up and Down follow the visible rows of wrapped text; hold Shift to select as you go.

## Formatting

| To write | Type |
| --- | --- |
| A heading | `# Heading` |
| A smaller heading | `## Heading` or `### Heading` |
| Bold | `**bold**` |
| Italic | `*italic*` |
| Strikethrough | `~~crossed out~~` |
| Highlight | `==highlighted==` |
| A link | `[link text](https://example.com)` |
| Inline code | `` `code` `` |
| A link to another note | `[[note]]` or `[[/personal/ideas]]` |
| A quote | `> Quoted text` |
| A bullet list | Start each line with `- ` |
| A numbered list | Start each line with `1. `, `2. `, and so on |

Indent a list item by two spaces to nest it:

```markdown
- Things to explore
  - A smaller idea
- Next steps
```

For a code block, put three backticks before and after your code. You can add a
language name after the opening backticks:

````markdown
```js
const greeting = "Hello";
```
````

For a table:

```markdown
| Item | Notes |
| --- | --- |
| First idea | Something to explore |
```

For math, write `$E = mc^2$` inline, or put a formula between `$$` on separate lines:

```text
$$
E = mc^2
$$
```

To add a Properties block, put this at the very beginning of your note:

```yaml
---
title: Ideas
status: Draft
tags: [writing, personal]
---
```

Click the block to edit its fields as text.

## Make yourself comfortable

Open **Settings** to choose a light, dark, or system theme; a narrow, page, wide,
or full-width column; a font available on your device; and a text size. Text starts
larger on phones, and headings scale with it. You can also toggle
line numbers and highlighting of the current line, both off by default. Fluent
remembers your choices.
Settings opens from the bottom on phones and from the right on larger screens.
Close it with **Done**, Escape, or a tap outside it.

Spell-checking, autocorrection, and keyboard word suggestions use your browser's
or operating system's settings. Enable them there if they are turned off. Fluent
requests writing assistance for prose and turns it off inside code blocks.

## Keep multiple notes

In **Settings → Notes**, enter a name such as `/personal/ideas` in **Open or create
a note**, then select **Open**. Use search to find saved notes by their paths.

The part of the URL after `#` identifies the note:

```text
#/personal/ideas
#/personal/work/project/ideas
```

You can nest names as deeply as you like. Trailing slashes are ignored:
`/personal/work/` and `/personal/work` open the same note. Use browser tabs,
bookmarks, and Back/Forward to move between notes. Opening a new path starts an
empty note; opening an existing path brings its text back.

Link notes with `[[ideas]]` for another note in the current folder, or
`[[/personal/ideas]]` for a full path. Click or tap the link to open it; a path
that doesn't exist yet opens an empty note. Command-click on Mac or Ctrl-click
elsewhere opens it in another browser tab. Move the cursor into a link with the
arrow keys to edit its Markdown syntax. Hover over a link to see a short text
preview of the destination note. Links use a subtle inline highlight and follow
your text size. Links open notes saved in your browser;
they don't share the contents with other people.

## Saving your writing

Existing slash-suffixed notes are moved to their matching path when opened. If
both paths held different text, the extra version appears as a `(recovered trailing
slash)` note.

Notes save automatically as you write. Check the status at the top for
**Saved on this device**. If another tab has changed the same note, Fluent saves
your stale edit as a separate `(conflict …)` copy to help preserve both versions.
Each browser tab remembers your cursor, selected text, and scroll position for
each note across refreshes and note switches. Closing the tab may discard that
position; your saved notes remain. Undo history resets when you switch notes or
reload.

Your notes stay in this browser at this site address. There are no accounts or
cloud sync, and sharing a note URL does not share its contents. Clearing browser
site data removes your notes. Moving a downloaded HTML file or switching between
the downloaded and hosted versions does not transfer them; saving local files
also varies by browser.

If Fluent says it cannot save, copy your text somewhere safe before closing or
reloading. You can also select and copy your writing to keep a backup. There are
no built-in export, rename, delete, or recovery controls yet.
