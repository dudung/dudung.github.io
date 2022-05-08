# dudung.github.io

20220509 Install jekyll and bundler gems

url https://jekyllrb.com/docs/

L:\home\dudung.github.io>ruby -v
ruby 3.1.1p18 (2022-02-18 revision 53f5fc4236) [x64-mingw-ucrt]

L:\home\dudung.github.io>gem -v
3.3.7

L:\home\dudung.github.io>gcc -v
Using built-in specs.
COLLECT_GCC=gcc
COLLECT_LTO_WRAPPER=C:/Strawberry/c/bin/../libexec/gcc/x86_64-w64-mingw32/8.3.0/lto-wrapper.exe
Target: x86_64-w64-mingw32
Configured with: ../../../src/gcc-8.3.0/configure --host=x86_64-w64-mingw32 --build=x86_64-w64-mingw32 --target=x86_64-w64-mingw32 --prefix=/mingw64 --enable-shared --enable-static --disable-multilib --enable-languages=c,c++,fortran,lto --enable-libstdcxx-time=yes --enable-threads=posix --enable-libgomp --enable-libatomic --enable-lto --enable-graphite --enable-checking=release --enable-fully-dynamic-string --enable-version-specific-runtime-libs --enable-libstdcxx-filesystem-ts=yes --disable-libstdcxx-pch --disable-libstdcxx-debug --disable-bootstrap --disable-rpath --disable-win32-registry --disable-nls --disable-werror --disable-symvers --with-gnu-as --with-gnu-ld --with-arch=nocona --with-tune=core2 --with-libiconv --with-system-zlib --with-gmp=/opt/build/prerequisites/x86_64-w64-mingw32-static --with-mpfr=/opt/build/prerequisites/x86_64-w64-mingw32-static --with-mpc=/opt/build/prerequisites/x86_64-w64-mingw32-static --with-isl=/opt/build/prerequisites/x86_64-w64-mingw32-static --with-pkgversion='x86_64-posix-seh, Built by strawberryperl.com project' --with-bugurl=https://sourceforge.net/projects/mingw-w64 CFLAGS='-O2 -pipe -fno-ident -I/opt/build/x86_64-830-posix-seh-rt_v6/mingw64/opt/include -I/opt/build/prerequisites/x86_64-zlib-static/include -I/opt/build/prerequisites/x86_64-w64-mingw32-static/include' CXXFLAGS='-O2 -pipe -fno-ident -I/opt/build/x86_64-830-posix-seh-rt_v6/mingw64/opt/include -I/opt/build/prerequisites/x86_64-zlib-static/include -I/opt/build/prerequisites/x86_64-w64-mingw32-static/include' CPPFLAGS=' -I/opt/build/x86_64-830-posix-seh-rt_v6/mingw64/opt/include -I/opt/build/prerequisites/x86_64-zlib-static/include -I/opt/build/prerequisites/x86_64-w64-mingw32-static/include' LDFLAGS='-pipe -fno-ident -L/opt/build/x86_64-830-posix-seh-rt_v6/mingw64/opt/lib -L/opt/build/prerequisites/x86_64-zlib-static/lib -L/opt/build/prerequisites/x86_64-w64-mingw32-static/lib ' LD_FOR_TARGET=/opt/build/x86_64-830-posix-seh-rt_v6/mingw64/bin/ld.exe
Thread model: posix
gcc version 8.3.0 (x86_64-posix-seh, Built by strawberryperl.com project)

L:\home\dudung.github.io>gem install jekyll bundler
Fetching safe_yaml-1.0.5.gem
Fetching rouge-3.28.0.gem
Fetching terminal-table-2.0.0.gem
Fetching forwardable-extended-2.6.0.gem
Fetching unicode-display_width-1.8.0.gem
Fetching pathutil-0.16.2.gem
Fetching mercenary-0.4.0.gem
Fetching liquid-4.0.3.gem
Fetching kramdown-2.4.0.gem
Fetching kramdown-parser-gfm-1.1.0.gem
Fetching ffi-1.15.5-x64-mingw-ucrt.gem
Fetching rb-inotify-0.10.1.gem
Fetching rb-fsevent-0.11.1.gem
Fetching listen-3.7.1.gem
Fetching jekyll-watch-2.2.1.gem
Fetching sassc-2.4.0.gem
Fetching jekyll-sass-converter-2.2.0.gem
Fetching concurrent-ruby-1.1.10.gem
Fetching i18n-1.10.0.gem
Fetching http_parser.rb-0.8.0.gem
Fetching eventmachine-1.2.7.gem
Fetching em-websocket-0.5.3.gem
Fetching colorator-1.1.0.gem
Fetching jekyll-4.2.2.gem
Fetching public_suffix-4.0.7.gem
Fetching addressable-2.8.0.gem
Successfully installed unicode-display_width-1.8.0
Successfully installed terminal-table-2.0.0
Successfully installed safe_yaml-1.0.5
Successfully installed rouge-3.28.0
Successfully installed forwardable-extended-2.6.0
Successfully installed pathutil-0.16.2
Successfully installed mercenary-0.4.0
Successfully installed liquid-4.0.3
Successfully installed kramdown-2.4.0
Successfully installed kramdown-parser-gfm-1.1.0
Successfully installed ffi-1.15.5-x64-mingw-ucrt
Successfully installed rb-inotify-0.10.1
Successfully installed rb-fsevent-0.11.1
Successfully installed listen-3.7.1
Successfully installed jekyll-watch-2.2.1
Temporarily enhancing PATH for MSYS/MINGW...
Building native extensions. This could take a while...
Successfully installed sassc-2.4.0
Successfully installed jekyll-sass-converter-2.2.0
Successfully installed concurrent-ruby-1.1.10
Successfully installed i18n-1.10.0
Building native extensions. This could take a while...
Successfully installed http_parser.rb-0.8.0
Building native extensions. This could take a while...
Successfully installed eventmachine-1.2.7
Successfully installed em-websocket-0.5.3
Successfully installed colorator-1.1.0
Successfully installed public_suffix-4.0.7
Successfully installed addressable-2.8.0
Successfully installed jekyll-4.2.2
Parsing documentation for unicode-display_width-1.8.0
Installing ri documentation for unicode-display_width-1.8.0
Parsing documentation for terminal-table-2.0.0
Installing ri documentation for terminal-table-2.0.0
Parsing documentation for safe_yaml-1.0.5
Installing ri documentation for safe_yaml-1.0.5
Parsing documentation for rouge-3.28.0
Installing ri documentation for rouge-3.28.0
Parsing documentation for forwardable-extended-2.6.0
Installing ri documentation for forwardable-extended-2.6.0
Parsing documentation for pathutil-0.16.2
Installing ri documentation for pathutil-0.16.2
Parsing documentation for mercenary-0.4.0
Installing ri documentation for mercenary-0.4.0
Parsing documentation for liquid-4.0.3
Installing ri documentation for liquid-4.0.3
Parsing documentation for kramdown-2.4.0
Installing ri documentation for kramdown-2.4.0
Parsing documentation for kramdown-parser-gfm-1.1.0
Installing ri documentation for kramdown-parser-gfm-1.1.0
Parsing documentation for ffi-1.15.5-x64-mingw-ucrt
Installing ri documentation for ffi-1.15.5-x64-mingw-ucrt
Parsing documentation for rb-inotify-0.10.1
Installing ri documentation for rb-inotify-0.10.1
Parsing documentation for rb-fsevent-0.11.1
Installing ri documentation for rb-fsevent-0.11.1
Parsing documentation for listen-3.7.1
Installing ri documentation for listen-3.7.1
Parsing documentation for jekyll-watch-2.2.1
Installing ri documentation for jekyll-watch-2.2.1
Parsing documentation for sassc-2.4.0
Installing ri documentation for sassc-2.4.0
Parsing documentation for jekyll-sass-converter-2.2.0
Installing ri documentation for jekyll-sass-converter-2.2.0
Parsing documentation for concurrent-ruby-1.1.10
Installing ri documentation for concurrent-ruby-1.1.10
Parsing documentation for i18n-1.10.0
Installing ri documentation for i18n-1.10.0
Parsing documentation for http_parser.rb-0.8.0
unknown encoding name "chunked\r\n\r\n25" for ext/ruby_http_parser/vendor/http-parser-java/tools/parse_tests.rb, skipping
Installing ri documentation for http_parser.rb-0.8.0
Parsing documentation for eventmachine-1.2.7
Installing ri documentation for eventmachine-1.2.7
Parsing documentation for em-websocket-0.5.3
Installing ri documentation for em-websocket-0.5.3
Parsing documentation for colorator-1.1.0
Installing ri documentation for colorator-1.1.0
Parsing documentation for public_suffix-4.0.7
Installing ri documentation for public_suffix-4.0.7
Parsing documentation for addressable-2.8.0
Installing ri documentation for addressable-2.8.0
Parsing documentation for jekyll-4.2.2
Installing ri documentation for jekyll-4.2.2
Done installing documentation for unicode-display_width, terminal-table, safe_yaml, rouge, forwardable-extended, pathutil, mercenary, liquid, kramdown, kramdown-parser-gfm, ffi, rb-inotify, rb-fsevent, listen, jekyll-watch, sassc, jekyll-sass-converter, concurrent-ruby, i18n, http_parser.rb, eventmachine, em-websocket, colorator, public_suffix, addressable, jekyll after 107 seconds
Fetching bundler-2.3.13.gem
Successfully installed bundler-2.3.13
Parsing documentation for bundler-2.3.13
Installing ri documentation for bundler-2.3.13
Done installing documentation for bundler after 0 seconds
27 gems installed

L:\home\dudung.github.io>jekyll -v
jekyll 4.2.2

L:\home>jekyll new dudung.github.io
Running bundle install in L:/home/dudung.github.io...
  Bundler: Fetching gem metadata from https://rubygems.org/..........
  Bundler: Resolving dependencies....
  Bundler: Using bundler 2.3.13
  Bundler: Using public_suffix 4.0.7
  Bundler: Using colorator 1.1.0
  Bundler: Using concurrent-ruby 1.1.10
  Bundler: Using eventmachine 1.2.7
  Bundler: Using http_parser.rb 0.8.0
  Bundler: Using ffi 1.15.5 (x64-mingw-ucrt)
  Bundler: Using forwardable-extended 2.6.0
  Bundler: Using rb-fsevent 0.11.1
  Bundler: Using rexml 3.2.5
  Bundler: Using liquid 4.0.3
  Bundler: Using mercenary 0.4.0
  Bundler: Using rouge 3.28.0
  Bundler: Using safe_yaml 1.0.5
  Bundler: Using unicode-display_width 1.8.0
  Bundler: Using addressable 2.8.0
  Bundler: Using i18n 1.10.0
  Bundler: Using sassc 2.4.0
  Bundler: Using rb-inotify 0.10.1
  Bundler: Using em-websocket 0.5.3
  Bundler: Using pathutil 0.16.2
  Bundler: Using kramdown 2.4.0
  Bundler: Using terminal-table 2.0.0
  Bundler: Using listen 3.7.1
  Bundler: Using jekyll-sass-converter 2.2.0
  Bundler: Using kramdown-parser-gfm 1.1.0
  Bundler: Using jekyll-watch 2.2.1
  Bundler: Using jekyll 4.2.2
  Bundler: Using jekyll-feed 0.16.0
  Bundler: Using jekyll-seo-tag 2.8.0
  Bundler: Using minima 2.5.1
  Bundler: Bundle complete! 7 Gemfile dependencies, 31 gems now installed.
  Bundler: Use `bundle info [gemname]` to see where a bundled gem is installed.
New jekyll site installed in L:/home/dudung.github.io.



--
20210827 Test access, 0847 can pull.

Sparisoma Viridi@SV04 MINGW32 /c/cygwin/home/Sparisoma Viridi/Documents/dudung.github.io (master)
$ git pull
remote: Enumerating objects: 186, done.
remote: Counting objects: 100% (186/186), done.
remote: Compressing objects: 100% (138/138), done.
remote: Total 186 (delta 127), reused 86 (delta 48), pack-reused 0
Receiving objects: 100% (186/186), 44.73 KiB | 301.00 KiB/s, done.
Resolving deltas: 100% (127/127), completed with 4 local objects.
From https://github.com/dudung/dudung.github.io
   a20f978..0f1cd2e  master     -> origin/master
Updating a20f978..0f1cd2e
Fast-forward
 README.md       |   2 +
 bibtypes.js     |  22 ++++++++
 index.html      |   2 +
 list/aipcp.js   |  79 ++++++++++++++++++++++++++
 list/intconf.js |  30 ++++++++++
 list/intjour.js |  63 +++++++++++++++++++--
 list/iopcs.js   | 169 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 list/natconf.js |  27 +++++++++
 list/natjour.js |  83 ++++++++++++++++++++++++++++
 list/osf.js     |  14 +++++
 list/snips.js   |  16 ++++++
 list/zenodo.js  | 119 +++++++++++++++++++++++++++++++++++++++
 12 files changed, 622 insertions(+), 4 deletions(-)
 create mode 100644 list/osf.js
 create mode 100644 list/zenodo.js

Sparisoma Viridi@SV04 MINGW32 /c/cygwin/home/Sparisoma Viridi/Documents/dudung.github.io (master)
$ git commit -a -m "try push"
[master 40fd883] try push
 1 file changed, 1 insertion(+)

Sparisoma Viridi@SV04 MINGW32 /c/cygwin/home/Sparisoma Viridi/Documents/dudung.github.io (master)
$ git push
Username for 'https://github.com': dudung
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/dudung/dudung.github.io/'

Sparisoma Viridi@SV04 MINGW32 /c/cygwin/home/Sparisoma Viridi/Documents/dudung.github.io (master)
$

0857 login
0900 ok, but token is too long

20210305 Can not accept, e.g. Des 2020 as year.