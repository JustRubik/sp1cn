# Git Commit Convention

## Structure of commit in this Project

```
[MainTags]: [Description][Code(optional)]
```

## Explanation of Structure

### Main Tags
MainTags includes one of these tags:
- **Content**: Adding, editing, or deleting document contents (chapters, sections, paragraphs, tables, equations).
- **Style**: Changes related to the document's appearance (fonts, margins, spacing, headers/footers). *Requires mentioning the file or location of the change.*
- **Asset**: Changes to non-text assets (images, figures, external PDF pages, bib files).
- **Cons** (Construction): Structural changes of the project (folder structure, file renaming, modularizing with `\include` or `\input`, build tools/scripts).
- **Fix**: Fixing a bug, formatting glitch, compilation error, or translation mistake. *Requires [Code] if applicable.*

<small>Can be added/edited in the future.</small>

### Description Prefix Rule
For **Content** and **Asset**, the `[Description]` must start with one of these active verbs:
- **Add**: Adding new content/assets.
- **Edit**: Modifying existing content/assets.
- **Del**: Removing content/assets.

### Code
A bug code, which is listed in bugs' files.

---

## Examples

| Scenario | Commit Message |
| :--- | :--- |
| Writing a new chapter | `[Content]: Add Chapter 1 introduction` |
| Fixing a spelling error | `[Fix]: Correct typo in section 2.1 [ERR04]` |
| Changing page margins | `[Style]: Adjust margins to 2.5cm in preamble.tex` |
| Adding a new logo image | `[Asset]: Add logo.png to assets/` |
| Splitting main.tex into chapters | `[Cons]: Split main.tex into separate chapter files` |

_JustRubik_