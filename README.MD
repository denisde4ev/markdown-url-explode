I want to have 1 bookmark that opens multiple urls

example:
https://denisde4ev.github.io/markdown-url-explode/#(ddg)[https://ddg.gg](g.co)[https://g.co]

js example:
https://denisde4ev.github.io/markdown-url-explode/#${encodeURIComponent(markdownString)}

NOTE: due to simplicity it does not match the entire markdown,
just what is in `(no backslash in front)[...(no backslash in front)]` and opens it
