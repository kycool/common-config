address: ~/.editorconfig

```
root = true

# Unix-style newlines with a newline ending every file
[*]
end_of_line = lf
insert_final_newline = true

# Matches multiple files with brace expansion notation
# Set default charset
[*.{js,py}]
charset = utf-8

[*.{js,ts,jsx,tsx,css,scss}]
indent_style = space
indent_size = 2

# 4 space indentation
[*.py]
indent_style = space
indent_size = 4

# Tab indentation (no size specified)
[Makefile]
indent_style = tab

# Matches the exact files either package.json or .travis.yml
[*.{json,yml}]
indent_style = space
indent_size = 4
```
