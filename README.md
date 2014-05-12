# Sublime Preferences


## Plugin

[Package Control](https://sublime.wbond.net/)

1. Open Console `Menu / View / Show Console`

1. Paste and execute

  ```python
  import urllib.request,os,hashlib; h = '7183a2d3e96f11eeadd761d777e62404e330c659d4bb41d3bdf022e94cab3cd0'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
  ```

[SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements)

[AutoFileName](https://github.com/BoundInCode/AutoFileName)

[Bracket Highlighter](https://github.com/facelessuser/BracketHighlighter)

[Color Picker](http://weslly.github.io/ColorPicker/)

Keyboard shortcut `ctrl+shift+c`

[Emmet](http://docs.emmet.io/)

[Tag](https://github.com/SublimeText/Tag)

[Trailing Spaces](https://github.com/SublimeText/TrailingSpaces)

[Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview)

[SFTP](http://wbond.net/sublime_packages/sftp)

[AngularJS](https://github.com/angular-ui/AngularJS-sublime-package)

## Syntax
[Jquery](https://github.com/SublimeText/jQuery)

[LESS](https://github.com/danro/LESS-sublime)

[SASS](https://sublime.wbond.net/packages/Sass)


## Snippets

Local Folder

* Windows

  `C:\Users\Name User\AppData\Roaming\Sublime Text 3\Packages\User`

[Comment Snippets](https://github.com/hachesilva/Comment-Snippets)

[JavaScript Console snippets](https://github.com/caiogondim/js-console-sublime-snippets)

[Readme](https://gist.github.com/zenorocha/4526327) - Snippet from Zeno Rocha

[Create Plugin jQuery](http://tableless.com.br/tudo-que-voce-gostaria-de-saber-sobre-plugins-jquery-e-ninguem-teve-paciencia-de-explicar/) - Code by Zeno Rocha

Jquery


## Key Bindings

### Mac OS

Super + b = `<strong>selection</strong>`

Super + i = `<em>selection</em>`

Super + u = `<u>selection</u>`

Super + alt + 7 = `encode_html_entities`

### Windows

Ctrl + b = `<strong>selection</strong>`

Ctrl + i = `<em>selection</em>`

Ctrl + u = `<u>selection</u>`

Ctrl + alt + 7 = `encode_html_entities`