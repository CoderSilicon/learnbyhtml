# Contributing to learnbyhtml

First of all: thank you for being here. 🎉

This project is for absolute beginners, so the most useful contribution you can
make is anything that makes a lesson easier to understand for someone who has
never written a line of code. You do **not** need to be an expert to help.
Fixing one confusing sentence is a real contribution.

By participating, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## Ways to contribute

| What | How |
| :--- | :--- |
| Fix a typo, broken link, or confusing explanation | Edit the `.html` file and open a pull request |
| Add a brand-new lesson | Read the golden rules below, then create `learn-<topic>.html` |
| Improve accessibility or mobile layout | Adjust HTML/CSS in any lesson and show us the before/after |
| Report a bug or confusing part | Open an issue using the **Bug report** template |
| Suggest a topic for a future lesson | Open an issue using the **Feature request** template |
| Test in a browser we haven't tried | Tell us which browser/version you used in an issue or PR |

---

## The Golden Rules for lessons

Every lesson in this repo is **one self-contained `.html` file**. Keep it that
way:

1. **One file, zero setup.** No build step, no framework, no `node_modules`,
   no external CSS/JS files, and no CDN dependencies. Someone should be able to
   double-click the file and learn from it offline.
2. **Explain like you're five.** Say *what* it is, *why* it exists, and *how* it
   works using everyday analogies. Define jargon the first time you use it.
3. **Show, don't just tell.** Demonstrate the concept live on the page whenever
   you can — the page itself is the example.
4. **Let people look under the hood.** Keep the source readable: meaningful tag
   and class names, sensible indentation, and short comments where they help.
5. **Build on what came before.** Link back to earlier lessons when a concept
   depends on them (HTML → CSS → JavaScript).
6. **Be kind and inclusive.** Avoid "it's obvious" / "anyone knows this"
   phrasing. Assume the reader knows nothing.
7. **Keep it human and simple as hell.** AI tools are allowed, but the result
   must still sound like a person teaching a friend — short, clear, and
   understood by you. See [Using AI tools](#using-ai-tools).

### File checklist

- [ ] Named `learn-<topic>.html` (lowercase, hyphens for spaces)
- [ ] Has a descriptive `<title>` and `<meta name="viewport" ...>`
- [ ] Uses semantic HTML headings (`<h1>` → `<h2>` → `<h3>`, no skipped levels)
- [ ] Works offline with no external requests
- [ ] Readable on a phone as well as a desktop
- [ ] Text has sufficient contrast; interactive elements work with a keyboard
- [ ] Opened in at least two browsers (for example Firefox and Chrome) and checked
- [ ] Added to the "What's Inside This Repo?" table in `README.md`
- [ ] I can explain every line myself; if AI helped, I rewrote and tested it
      (see [Using AI tools](#using-ai-tools))

---

## Using AI tools

AI assistants are welcome here. They're handy for catching typos, suggesting a
clearer analogy, or helping you understand a topic you're new to. But they are
**tools, not authors** — you are responsible for everything you submit.

Two rules decide whether an AI-assisted contribution fits this project:

1. **Simple as hell.** AI loves long, polished, buzzword-heavy explanations.
   Cut them. If a beginner needs a dictionary to read a paragraph, rewrite it.
   Prefer short sentences, one idea at a time, and a real example over a
   three-paragraph definition. No giant auto-generated boilerplate, no 600-line
   lesson that could be 60 lines.
2. **Should be human.** The page should sound like a person teaching a friend,
   not a chatbot summary. Bring your own analogies, examples, and the mistakes
   *you* actually made while learning. Never paste raw AI output straight into
   a lesson, an issue, or a PR description. If you wouldn't say it out loud to a
   beginner, don't ship it.

**Fine:**

- Asking an AI to explain a topic to you while you learn it
- Using it to spot typos, broken HTML, or accessibility problems
- Getting a second opinion on wording, then rewriting it in your own voice
- Generating a small snippet that you read, understand, test, and can explain

**Not fine:**

- Submitting untouched AI-generated lessons, comments, or reviews
- Filling issues with generic "Great contribution!"-style AI noise
- Letting an AI open PRs or reply to issues without you reviewing and owning
  every word
- Keeping verbose, jargon-heavy, copy-pasted text just because it "looks complete"
- AI-generated images or media served from external sites — that breaks the
  one-file, works-offline rule

**Before you open a PR, ask yourself:**

- Can I explain every line of this to a 10-year-old without reading the AI's answer?
- Did I trim the fluff from the first draft?
- Does it sound like me, or like a manual written by a robot?

If you used AI, just say so in the PR — *"used AI to draft the examples, rewrote
the text in my own words, and tested it in Firefox"* is perfect. No need to hide
it; honesty makes review easier.

---

## Step by step: your first pull request

If you've never done this before, follow along exactly. Nothing here is magic.

### 1. Fork and clone

Click **Fork** at the top of the GitHub repo, then clone your fork:

```bash
git clone https://github.com/<your-username>/learnbyhtml.git
cd learnbyhtml
```

### 2. Make a branch

```bash
git checkout -b fix-html-typo
```

Pick a short, descriptive name like `add-git-lesson` or `fix-flexbox-example`.

### 3. Make your change

Open the file in any editor. Save it. Double-click the `.html` file in your
browser to check it still works.

### 4. Commit with a clear message

```bash
git add learn-html.html README.md
git commit -m "Fix typo in the id vs class explanation"
```

Good prefixes: `Fix`, `Add`, `Improve`, `Update`, `Document`.

### 5. Push and open a pull request

```bash
git push origin fix-html-typo
```

Then click **Compare & pull request** on GitHub. Fill in the pull request
template: what changed, why, and how you tested it. Link any related issue with
`Closes #12` so it closes automatically when the PR merges.

### 6. Be ready for feedback

We may ask for small changes — that's normal and meant kindly. Push more commits
to the same branch and they'll appear in the PR automatically. Once approved,
a maintainer will merge it. Thank you! 🙌

---

## Quick checks before you open a PR

- [ ] I read the [Code of Conduct](CODE_OF_CONDUCT.md)
- [ ] My change matches the Golden Rules above
- [ ] I tested the page in a browser
- [ ] `README.md` is updated if I added a new lesson
- [ ] My commit messages describe *what* changed

---

## License

This project is licensed under the [Apache License 2.0](LICENSE). By
contributing, you agree that your contribution is licensed under the same
terms, and that you have the right to submit it. See [NOTICE](NOTICE) for the
copyright notice.

---

## Questions?

Open an issue, or email the maintainer at **staticcodersilicon@gmail.com**.
No question is too small — this whole project exists for people asking them.
