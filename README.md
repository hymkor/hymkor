# HAYAMA\_Kaoru (hymkor) a.k.a zetamatta

[![Github](https://img.shields.io/github/followers/hymkor?label=Follow&style=social)](https://github.com/hymkor)

- A Go/Lua/.NET/C++/Oracle/DWG-CAD programmer

<!--![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=hymkor&hide=html)
![hymkor's github stats](https://github-readme-stats.vercel.app/api?username=hymkor&show_icons=true&count_private=true&line_height=40)

[![trophy](https://github-profile-trophy.vercel.app/?username=hymkor&column=7)](https://github.com/hymkor/github-profile-trophy)
-->

## Products

On Windows, some tools are able to be installed with [scoop-installer](https://scoop.sh).
( See also [my scoop bucket](https://github.com/hymkor/scoop-bucket/blob/master/README.md#repositories) )

```
$ scoop bucket add hymkor https://github.com/hymkor/scoop-bucket
$ scoop install hymkor/NAME
```

- Language
    - "[gmnlisp](https://github.com/hymkor/gmnlisp)" ..  A small Lisp implementation in Go
- Hybrid Commandline Shells
    - "[NYAOS-1000](https://github.com/nyaosorg/nyaos1000)" .. The 1st Generation Shell for OS/2 by C++,1996-2000
    - "[NYAOS-2000](https://github.com/nyaosorg/nyaos2000)" .. The 2nd Generation Shell for DOS,Windows &amp; OS/2 by C++,2001-2010
    - "[NYAOS-3000](https://github.com/nyaosorg/nyaos3000)" .. The 3rd Generation Shell for Windows &amp; OS/2 by C++,2010-2014
    - "[**NYAGOS**](https://github.com/nyaosorg/nyagos/)" .. The 4th Generation Shell for Windows &amp; Linux by Go,2014-Now
- TUI Tools
    - [Jegan](https://github.com/hymkor/jegan)
        .. A terminal JSON editor  
    - [Csvi](https://github.com/hymkor/csvi)
        .. A terminal CSV editor
    - [Bine](https://github.com/hymkor/bine)
        .. A terminal HEX editor
- Text-terminal automation tools similar to expect(1) 
    - [Expect-lua for Windows](https://github.com/hymkor/expect)
        .. Using GopherLua as script and ReadConsoleOutputW. Supporting Windows 7 or later
    - [Lispect](https://github.com/hymkor/lispect)
        .. Using the subset of ISLisp as script and PsudoConsole. Supporting Linux and Windows10 or later
- CUI Tools
    - [script.exe](https://github.com/hymkor/script)
        .. Make typescript of terminal session like that of Linux for Windows10 or later 
    - [sqlbless](https://github.com/hymkor/sqlbless)
        .. The Command-line Database Client
    - [pipe2excel](https://github.com/hymkor/pipe2excel)
        .. Send CSV from STDIN to Excel
    - [uncozip](https://github.com/hymkor/uncozip)
        .. UNzip COrrupted ZIP file that does not have the central directory records
    - [sponge](https://github.com/hymkor/sponge) [Go], [sponge-rs](https://github.com/hymkor/sponge-rs) [Rust]  
        .. sponge clone for Windows (Original: https://joeyh.name/code/moreutils/)
    - [make-scoop-manifest](https://github.com/hymkor/make-scoop-manifest)
        .. Make the manifest file for the scoop-installer
- Windows API wrappers for Go
    - [go-windows-mbcs](https://github.com/nyaosorg/go-windows-mbcs)
        .. Convert between ANSI and UTF8
    - [go-windows-dbg](https://github.com/nyaosorg/go-windows-dbg)
        .. OutputDebugString like VC++
    - [go-windows-junction](https://github.com/nyaosorg/go-windows-junction)
        .. Create Junction (mklink /J)
    - [go-windows-shortcut](https://github.com/nyaosorg/go-windows-shortcut)
        .. Create/Query Windows' shortcut
    - [go-windows-su](https://github.com/nyaosorg/go-windows-su)
        .. Switch or test Windows' administrator mode
    - [go-windows-subst](https://github.com/nyaosorg/go-windows-subst)
        .. Do/Query SUBST
    - [go-windows-consoleicon](https://github.com/nyaosorg/go-windows-consoleicon)
        .. Set icon to the corner of the current console (Command Prompt)
- Class library
    - [**go-readline-ny**](https://github.com/nyaosorg/go-readline-ny)
        .. readline library used on nyagos
    - [go-multiline-ny](https://github.com/hymkor/go-multiline-ny)
        .. Extended Readline package supporting multi-lines
    - [go-enex](https://github.com/hymkor/go-enex)
        .. Convert Evernote's export file(\*.enex) into HTML and images
- Generics library
    - [go-pipeline](https://github.com/hymkor/go-pipeline)
        .. channel + goroutine -&gt; pipeline
    - [go-lazy](https://github.com/hymkor/go-lazy)
        .. Lazy initialization
    - [go-minimal-optional](https://github.com/hymkor/go-minimal-optional)
        .. The minimal optional package for golang
    - [go-generics-list](https://github.com/hymkor/go-generics-list)
        .. The generics version of "container/list"

## Documents

### Articles on zenn.dev

- [Success! Making NYAGOS Speak Spontaneously](https://zenn.dev/zetamatta/articles/ukkari-talk-nyagos?locale=en)  
- [Lazy-Style Character Encoding Detection for Go on Windows](https://zenn.dev/zetamatta/articles/mbcs-to-utf8-filter?locale=en)  
- [sync.OnceValue: Lazy Initialization Function Introduced in Go 1.21.0](https://zenn.dev/zetamatta/articles/4afb2970e111c5?locale=en)
- [Processing CSVs with Line Breaks in Fields Using gawk](https://zenn.dev/zetamatta/articles/ce42498310c183?locale=en)
- [Command-Line Shell? Anyone Can Build One](https://zenn.dev/zetamatta/articles/d7b76ff6535d7d?locale=en)
- [Supporting Older Go Versions Without Dropping the Latest: Coexistence Strategies](https://zenn.dev/zetamatta/articles/use-old-new-go?locale=en)
- [Building a Terminal CSV Editor in Go for Combat in Production Environments](https://zenn.dev/zetamatta/articles/terminal-csv-editor?locale=en)
- [Developing SQL-Bless: A Multi-DB Terminal Client in Go](https://zenn.dev/zetamatta/articles/sql-bless-note?locale=en)

### Books on zenn.dev (Japanese)

- [scoop / nyagos で始めるコマンドライン生活](https://zenn.dev/zetamatta/books/5ac80a9ddb35fef9a146)
- [/bin/shに慣れた人に贈るバッチファイルの書き方](https://zenn.dev/zetamatta/books/c84cbe23093eee1b5830)
- [Windows と Unicode とボク](https://zenn.dev/zetamatta/books/b820d588f4856bcf836c)
- [君のレポジトリを領域展開 - 次世代バージョン管理システム Jujutsu (jj-vcs/jj)の世界](https://zenn.dev/zetamatta/books/c1e309aea68960)
