# Fluent

A simple Markdown editor with live preview. Write freely, adjust the page to suit
you, and keep your notes in your browser.

## Start writing

Open Fluent in your browser and click the page to write. You can also download
[index.html](./index.html) and open the downloaded file directly. No installation
or internet connection is needed for writing.

Fluent formats Markdown as you type. Click formatted text to edit it; the relevant
Markdown symbols reappear as you move the cursor through them. Your original text
stays intact. Leave a blank line between paragraphs or different kinds of blocks.

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
| A quote | `> Quoted text` |
| A bullet list | Start each line with `- ` |
| A numbered list | Start each line with `1. `, `2. `, and so on |

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

## Make yourself comfortable

Open **Settings** to choose a light, dark, or system theme; a narrow, page, wide,
or full-width column; and a font available on your device. You can also toggle
line numbers and highlighting of the current line. Fluent remembers your choices.
Close the sidebar with **Done**, Escape, or a click outside it.

Spell-checking uses your browser's or operating system's language and dictionary
settings. Enable spelling checks there if they are turned off.

## Keep multiple notes

In **Settings → Notes**, enter a name such as `/personal/ideas` in **Open or create
a note**, then select **Open**. Use search to find saved notes by their paths.

The part of the URL after `#` identifies the note:

```text
#/personal/ideas
#/personal/work/project/ideas
```

You can nest names as deeply as you like. A trailing slash is part of the name:
`/personal/work/` and `/personal/work` open different notes. Use browser tabs,
bookmarks, and Back/Forward to move between notes. Opening a new path starts an
empty note; opening an existing path brings its text back.

## Saving your writing

Notes save automatically as you write. Check the status at the top for
**Saved on this device**. If another tab has changed the same note, Fluent saves
your stale edit as a separate `(conflict …)` copy to help preserve both versions.

Your notes stay in this browser at this site address. There are no accounts or
cloud sync, and sharing a note URL does not share its contents. Clearing browser
site data removes your notes. Moving a downloaded HTML file or switching between
the downloaded and hosted versions does not transfer them; saving local files
also varies by browser.

If Fluent says it cannot save, copy your text somewhere safe before closing or
reloading. You can also select and copy your writing to keep a backup. There are
no built-in export, rename, delete, or recovery controls yet.
