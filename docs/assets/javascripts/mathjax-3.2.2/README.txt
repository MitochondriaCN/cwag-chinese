MathJax 3.2.2 (Apache-2.0)

Source: the official npm package mathjax@3.2.2
https://www.npmjs.com/package/mathjax/v/3.2.2
Package SHA-1: c754d7b46a679d7f3fa03543d6b8bf124ddf9f6b

Vendored files: LICENSE, es5/tex-mml-chtml.js, es5/core.js,
es5/loader.js, es5/startup.js, and the es5/input, es5/output,
es5/a11y, es5/ui, es5/sre, es5/adaptors directories.
Other combined entry-point bundles and Node.js utilities are omitted.

Keep the es5 directory structure intact. MathJax derives its resource
root from the tex-mml-chtml.js script URL and loads extensions, fonts,
and accessibility resources relative to it. MkDocs copies these files
into the generated site, so no math-rendering CDN is needed at runtime.

To update, replace these files with the corresponding files from a
fixed official npm release, preserve its LICENSE, and update the path
in mkdocs.yml and the version and package hash above.
