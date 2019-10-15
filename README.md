# myvim

## Copy a line
```sh
yyp # paste after
yyP # paste before
# or :t.  paste below
# :t 10   paste after line 10
yy10p # paste 10 times after
```
## Cursor move
^ moves the cursor to the first non-blank character of a line
0 always moves the cursor to the "first column"

- gg : first line beginning
- GG : last line beginning
- G$ : last line end
- +  : next line beginning
- j0 : next line beginning
- g_ : last non whitespace of line
- $  : end ot the line

## Undo
- u
- U

## Searching and replacing
- /pattern : search pattern forward
- ?pattern : search pattern backward
- n        : forward search
- N        : backward search
- :set ignorecase : ignore case
- :set smartcase  : use case if any caps used
- :set incsearch  : show match as search proceeds
- :set hlsearch   : search highlighting
- :%s/search_for_this/replace_with_this/    : search whole file and replace
- :%s/search_for_this/replace_with_this/c   : confirm each replace

