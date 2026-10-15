# paper-to-bullets

A Claude Code plugin that turns a research paper into five bullets:

- **Title:** the paper's title
- **Question:** the main question or problem
- **Method:** how the authors tried to answer it
- **Result:** the main finding
- **Limitation:** the most important weakness or caveat

If the paper doesn't state one of these, the skill says "Not stated in the paper" instead of guessing.

## Install

This repository is its own plugin marketplace, called `ncohen1-skills`. Run these commands inside Claude Code:

```
/plugin marketplace add Ncohen1/paper-to-bullets
/plugin install paper-to-bullets@ncohen1-skills
```

Then restart Claude Code so the skill loads.

To try it from a local copy before publishing, point the first command at the folder:

```
/plugin marketplace add ./paper-to-bullets
```

## Use

Share a paper (for example a PDF in your project) and ask Claude to triage it or turn it into bullets. You can also call the skill directly:

```
/paper-to-bullets:paper-to-bullets path/to/paper.pdf
```

## Update or remove

```
/plugin marketplace update ncohen1-skills
/plugin uninstall paper-to-bullets@ncohen1-skills
```

## License

MIT
