A collection of [UltiSnips] snippets for writing [LaTeX] in [Vim], originally
presented by [Gilles Castel][castel] ([gillescastel] on GitHub) in their blog
post [“How I'm able to take notes in mathematics lectures using LaTeX and
Vim”][notes].

Sample `vimrc` usage with @junegunn's [vim-plug](/junegunn/vim-plug):

    call plug#begin()
    Plug 'SirVer/ultisnips'
    Plug '9999years/tex-snippets'
    call plug#end()

    let g:UltiSnipsSnippetDirectories = [
        \ expand('~/.vim/plugged/tex-snippets/snippets')]

[UltiSnips]: /SirVer/ultisnips
[LaTeX]: https://en.wikipedia.org/wiki/LaTeX
[Vim]: https://en.wikipedia.org/wiki/Vim_(text_editor)
[castel]: https://castel.dev/
[gillescastel]: https://github.com/gillescastel
[notes]: https://castel.dev/post/lecture-notes-1/
