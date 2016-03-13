# The Vim Way

`dot command`  repeat the latest operation

`I` insert in the begining

`A` insert after the end

`o` new line below

`O` new line above

`s` replace and insert

`f{char}` search in line

`F{char}` backward search in line

`;` redo *f* search

`,` redo serach but revse

`t{char}` search till char, will stop before the char

`T{char}` reverse search till

`/pattern<CR>` scan doc, `n` next, `N` reverse next

`?pattern<CR>` scan doc reverse,

`:s/target/replacement` substitution inline, `&` redo

`qx{changes}q` execute a sequence of changes, `@x` redo

`*` search current word

`cw` delete to the end of the word and drop us in Insert mode
 
