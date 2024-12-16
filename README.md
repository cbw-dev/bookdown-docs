# CBW's Bookdown Documentation

This is the repo that hosts the CBW's bookdown documentation website.

DEV RULES:
- all links to the web should create a new tab for it: use html code:
```
<a href="placeholder.com" target="_blank">Opens in new tab</a>
```

More Helpful Code:
- `<p style="font-size: 8px;"></p>` creates a line with height=8px


BUGS:
- enforcing links to create a new tab, when they are headers, makes a weird sidebar issue, see sidebar for GitHub Instructions

To-Do List
- EXPLAIN MERGE CONFLICTS
- FIND A BETTER WAY TO SHOW TABLES
- update favicon.ico image in template with one with higher quality

Suggestions:
- add timing of downloads/installations (R/RStudio, developer tools, reticulate)
- add code chunk option to the file setup explanation code chunk, so that this takes up the width of the entire page?
- add border (css styling) to instruction pictures
- change callout colours ??
- best practices section ?


Potential Colour Template? (see the blue, green and red)
currently used: https://coolors.co/8db580-4d4730-301a4b-f39a9d-acd2ed
https://coolors.co/45b69c-d46d63-202030-6495ed-fff9ec
https://coolors.co/303a2b-d84444-9cc0fa-7cbf73-615d6c



Figure this out:
- currently, the share links are based on what we put in the '_output.yml' file? This is not that important but we should figure this out at some point.
```
## Metadata for sharing

Bookdown HTML books will provide HTML metadata for social sharing on platforms like Twitter, Facebook, and LinkedIn, using information you provide in the `index.Rmd` YAML. To setup, set the `url` for your book and the path to your `cover-image` file. Your book's `title` and `description` are also used.

This `gitbook` uses the same social sharing data across all chapters in your book- all links shared will look the same.

Specify your book's source repository on GitHub using the `edit` key under the configuration options in the `_output.yml` file, which allows users to suggest an edit by linking to a chapter's source file.
```
