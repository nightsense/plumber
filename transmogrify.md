## vim

- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-light.vim> `c1c3e6c`
- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-dark.vim> `c1c3e6c`

```
3,10d | 4d | 5d | 36d | 42,49d |
4s#.*/#execute "silent !/bin/sh $HOME/.nightshell/# |
4s/\.sh// |
%s/base16-default/plumber/ |

%s/181818/000000/ |
%s/282828/183c5c/ |
%s/383838/183c5c/ |
%s/585858/008088/ |
%s/b8b8b8/008088/ |
%s/d8d8d8/bcbcbc/ |
%s/e8e8e8/bcbcbc/ |
%s/f8f8f8/fcfcfc/ |

%s/ab4642/d82800/ |
%s/dc9656/c84c0c/ |
%s/f7ca88/fc9838/ |
%s/a1b56c/00a800/ |
%s/86c1b9/008088/ |
%s/7cafc2/5c94fc/ |
%s/ba8baf/fc74b4/ |
%s/a16946/e40058/ |

%s/Character",    s:gui08, "", s:cterm08/Character",    s:gui0B, "", s:cterm0B/ |
%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui00, s:gui0B, s:cterm00, s:cterm0B/ |
%s/Identifier",   s:gui08, "", s:cterm08, "", "none/Identifier",   s:gui0B, "", s:cterm0B, "", "bold/ |
%s/LineNr",        s:gui03, s:gui01, s:cterm03, s:cterm01/LineNr",        s:gui09, s:gui0A, s:cterm09, s:cterm0A/ |
%s/Search",        s:gui03, s:gui0A, s:cterm03, s:cterm0A,  "", "")/Search",        s:gui00, s:gui0A, s:cterm00, s:cterm0A,  "", "")/ |
%s/statusline",    s:gui04, s:gui02, s:cterm04, s:cterm02/statusline",    s:gui00, s:gui0B, s:cterm00, s:cterm0B/ |
%s/StatusLineNC",  s:gui03, s:gui01, s:cterm03, s:cterm01/StatusLineNC",  s:gui05, s:gui01, s:cterm05, s:cterm01/ |
%s/Visual",        "", s:gui02, "", s:cterm02/Visual",        s:gui06, s:gui02, s:cterm06, s:cterm02/ |
%s/VisualNOS",     s:gui08, "", s:cterm08, "", ""/VisualNOS",     "", s:gui01, "", s:cterm01, "none"/ |
%s/WildMenu",      s:gui08, s:gui0A, s:cterm08, ""/WildMenu",      s:gui00, s:gui06, s:cterm00, s:cterm06/ |

%s/CursorLineNr",  s:gui04, s:gui01, s:cterm04, s:cterm01/CursorLineNr",  s:gui09, s:gui0A, s:cterm09, s:cterm0A/ |
if @% =~ 'dark' | 125s/09/05/g | 125s/0A/01/g | 133s/09/05/g | 133s/0A/01/g | endif |

normal =gg
```




## nightshell

- <https://raw.githubusercontent.com/chriskempson/base16-shell/master/scripts/base16-default-light.sh> `376294b`
- <https://raw.githubusercontent.com/chriskempson/base16-shell/master/scripts/base16-default-dark.sh> `376294b`

```
2,4d |

%s#18/18/18#00/00/00# |
%s#28/28/28#18/3c/5c# |
%s#38/38/38#18/3c/5c# |
%s#58/58/58#00/80/88# |
%s#b8/b8/b8#00/80/88# |
%s#d8/d8/d8#bc/bc/bc# |
%s#e8/e8/e8#bc/bc/bc# |
%s#f8/f8/f8#fc/fc/fc# |
%s#ab/46/42#d8/28/00# |
%s#dc/96/56#c8/4c/0c# |
%s#f7/ca/88#fc/98/38# |
%s#a1/b5/6c#00/a8/00# |
%s#86/c1/b9#00/80/88# |
%s#7c/af/c2#5c/94/fc# |
%s#ba/8b/af#fc/74/b4# |
%s#a1/69/46#e4/00/58# |

%s/181818/000000/ge |
%s/383838/183c5c/g |
%s/d8d8d8/bcbcbc/g |
%s/f8f8f8/fcfcfc/ge |

call append(123,["",
"echo -ne '\\e]12;#d47546\\a'"])
```
