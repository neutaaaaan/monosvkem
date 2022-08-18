# Deprecated

**Monosvkem** has been deprecated in favour of [**quiet**](https://github.com/vim/colorschemes/blob/master/colors/quiet.vim) which was included in `vim9` as part of a runtime update shipped alongside `patch 9.0.0130`.  
**quiet** was built as a neutral platform users could easily add their own tweaks to using autocommands. Unlike **Monosvkem** it is entirely 256colors-safe.  

As both colorschemes share a common core, it should be relatively painless to add your own tweaks in your `.vimrc`, as shown below:

```
augroup highlight_override
        autocmd!
        autocmd ColorScheme quiet hi String ctermfg=4
        autocmd ColorScheme quiet hi Special ctermfg=1
augroup END
```

----

![image](https://i.ibb.co/wdCTdXs/dark.png) ![image](https://i.ibb.co/SvK78n8/light.png)

**Monosvkem** trades the all too common angry fruit salad for the subtle hues
of the goopy mess stuck at the bottom of the cement mixer.

Monosvkem only bothers itself with `comments`, `strings`and things that get
linked to the`special` group.

It used to be a dirty hack of
[Iosvkem](https://www.github.com/neutaaaaan/iosvkem) but it has since been
rewritten from scratch to support both dark and light backgrounds.
