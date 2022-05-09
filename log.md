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

cd

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

L:\home\dudung.github.io>bundle exec jekyll serve
Configuration file: L:/home/dudung.github.io/_config.yml
            Source: L:/home/dudung.github.io
       Destination: L:/home/dudung.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 5.118 seconds.
  Please add the following to your Gemfile to avoid polling for changes:
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?
 Auto-regeneration: enabled for 'L:/home/dudung.github.io'
                    ------------------------------------------------
      Jekyll 4.2.2   Please append `--trace` to the `serve` command
                     for any additional information or backtrace.
                    ------------------------------------------------
C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/commands/serve/servlet.rb:3:in `require': cannot load such file -- webrick (LoadError)
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/commands/serve/servlet.rb:3:in `<top (required)>'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/commands/serve.rb:179:in `require_relative'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/commands/serve.rb:179:in `setup'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/commands/serve.rb:100:in `process'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/command.rb:91:in `block in process_with_graceful_fail'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/command.rb:91:in `each'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/command.rb:91:in `process_with_graceful_fail'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/commands/serve.rb:86:in `block (2 levels) in init_with_program'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `block in execute'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `each'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `execute'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary/program.rb:44:in `go'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary.rb:21:in `program'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/exe/jekyll:15:in `<top (required)>'
        from C:/Ruby31-x64/bin/jekyll:32:in `load'
        from C:/Ruby31-x64/bin/jekyll:32:in `<main>'


https://jekyllrb.com/docs/
If you are using Ruby version 3.0.0 or higher, step 5 may fail. You may fix it by adding webrick to your dependencies: bundle add webrick

https://github.com/github/pages-gem/issues/752


L:\home\dudung.github.io>bundle add webrick
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
Using bundler 2.3.13
Using public_suffix 4.0.7
Using colorator 1.1.0
Using concurrent-ruby 1.1.10
Using eventmachine 1.2.7
Using http_parser.rb 0.8.0
Using ffi 1.15.5 (x64-mingw-ucrt)
Using forwardable-extended 2.6.0
Using rexml 3.2.5
Using rb-fsevent 0.11.1
Using liquid 4.0.3
Using rouge 3.28.0
Using safe_yaml 1.0.5
Using mercenary 0.4.0
Using unicode-display_width 1.8.0
Using addressable 2.8.0
Using em-websocket 0.5.3
Fetching webrick 1.7.0
Using i18n 1.10.0
Using sassc 2.4.0
Using rb-inotify 0.10.1
Using kramdown 2.4.0
Using pathutil 0.16.2
Using terminal-table 2.0.0
Using jekyll-sass-converter 2.2.0
Using listen 3.7.1
Using kramdown-parser-gfm 1.1.0
Using jekyll-watch 2.2.1
Using jekyll 4.2.2
Using jekyll-feed 0.16.0
Using jekyll-seo-tag 2.8.0
Using minima 2.5.1
Installing webrick 1.7.0

L:\home\dudung.github.io>bundle exec jekyll serve
Configuration file: L:/home/dudung.github.io/_config.yml
            Source: L:/home/dudung.github.io
       Destination: L:/home/dudung.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 3.192 seconds.
  Please add the following to your Gemfile to avoid polling for changes:
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?
 Auto-regeneration: enabled for 'L:/home/dudung.github.io'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
[2022-05-09 06:26:57] ERROR `/favicon.ico' not found.

  Please add the following to your Gemfile to avoid polling for changes:
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?


gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

L:\home\dudung.github.io>bundle exec jekyll serve

[!] There was an error parsing `Gemfile`: You cannot specify the same gem twice with different version requirements.
You specified: wdm (~> 0.1.1) and wdm (>= 0.1.0). Bundler cannot continue.

 #  from L:/home/dudung.github.io/Gemfile:30
 #  -------------------------------------------
 #
 >  gem "webrick", "~> 1.7"
 #  source "https://rubygems.org"
 #  -------------------------------------------

#gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

L:\home\dudung.github.io>bundle exec jekyll serve
Could not find gem 'wdm (>= 0.1.0)' in locally installed gems.
Run `bundle install` to install missing gems.

L:\home\dudung.github.io>bundle install
Fetching gem metadata from https://rubygems.org/.........
Resolving dependencies...
Using bundler 2.3.13
Using public_suffix 4.0.7
Using colorator 1.1.0
Using concurrent-ruby 1.1.10
Using eventmachine 1.2.7
Using http_parser.rb 0.8.0
Using ffi 1.15.5 (x64-mingw-ucrt)
Using forwardable-extended 2.6.0
Using rb-fsevent 0.11.1
Using rexml 3.2.5
Using liquid 4.0.3
Using mercenary 0.4.0
Using rouge 3.28.0
Using safe_yaml 1.0.5
Using unicode-display_width 1.8.0
Using webrick 1.7.0
Using addressable 2.8.0
Using em-websocket 0.5.3
Fetching wdm 0.1.1
Using i18n 1.10.0
Using sassc 2.4.0
Using rb-inotify 0.10.1
Using kramdown 2.4.0
Using pathutil 0.16.2
Using terminal-table 2.0.0
Using jekyll-sass-converter 2.2.0
Using listen 3.7.1
Using kramdown-parser-gfm 1.1.0
Using jekyll-watch 2.2.1
Using jekyll 4.2.2
Using jekyll-feed 0.16.0
Using jekyll-seo-tag 2.8.0
Using minima 2.5.1
Installing wdm 0.1.1 with native extensions
Bundle complete! 8 Gemfile dependencies, 33 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.

L:\home\dudung.github.io>bundle exec jekyll serve
Configuration file: L:/home/dudung.github.io/_config.yml
            Source: L:/home/dudung.github.io
       Destination: L:/home/dudung.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 4.952 seconds.
 Auto-regeneration: enabled for 'L:/home/dudung.github.io'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.

L:\home\dudung.github.io>bundle exec jekyll serve --livereload
Configuration file: L:/home/dudung.github.io/_config.yml
            Source: L:/home/dudung.github.io
       Destination: L:/home/dudung.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 3.406 seconds.
 Auto-regeneration: enabled for 'L:/home/dudung.github.io'
LiveReload address: http://127.0.0.1:35729
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.

L:\home\dudung.github.io>bundle exec jekyll serve --livereload
Configuration file: L:/home/dudung.github.io/_config.yml
            Source: L:/home/dudung.github.io
       Destination: L:/home/dudung.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 3.406 seconds.
 Auto-regeneration: enabled for 'L:/home/dudung.github.io'
LiveReload address: http://127.0.0.1:35729
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
      Regenerating: 1 file(s) changed at 2022-05-09 06:39:20
                    log.md
       Jekyll Feed: Generating feed for posts
                    ...done in 0.4334297 seconds.

        LiveReload: Browser connected
      Regenerating: 1 file(s) changed at 2022-05-09 06:40:27
                    _posts/2022-05-09-hello.markdown
       Jekyll Feed: Generating feed for posts
                    ...done in 0.3838073 seconds.

      Regenerating: 1 file(s) changed at 2022-05-09 06:40:42
                    _posts/2022-05-09-hello.markdown
       Jekyll Feed: Generating feed for posts
                    ...done in 0.3568273 seconds.

      Regenerating: 1 file(s) changed at 2022-05-09 06:40:44
                    _posts/2022-05-09-hello.markdown
       Jekyll Feed: Generating feed for posts
                    ...done in 0.307381 seconds.

yaml file edit need restart sever  --> already in _config.yml file

Edit yml

https://jun711.github.io/web/how-to-highlight-code-on-a-Jekyll-site-syntax-highlighting/

markdown: kramdown
highlighter: rouge
  input: GFM

restart

L:\home\dudung.github.io>bundle exec jekyll serve --livereload
jekyll 4.2.2 | Error:  (L:/home/dudung.github.io/_config.yml): mapping values are not allowed in this context at line 37 column 8
C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:143:in `parse': (L:/home/dudung.github.io/_config.yml): mapping values are not allowed in this context at line 37 column 8 (Psych::SyntaxError)
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:143:in `load'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:157:in `block in load_file'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:157:in `open'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:157:in `load_file'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/configuration.rb:129:in `safe_load_file'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/configuration.rb:167:in `read_config_file'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/configuration.rb:198:in `block in read_config_files'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/configuration.rb:195:in `each'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/configuration.rb:195:in `read_config_files'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll.rb:118:in `configuration'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/command.rb:44:in `configuration_from_options'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/lib/jekyll/commands/serve.rb:83:in `block (2 levels) in init_with_program'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `block in execute'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `each'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary/command.rb:221:in `execute'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary/program.rb:44:in `go'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/mercenary-0.4.0/lib/mercenary.rb:21:in `program'
        from C:/Ruby31-x64/lib/ruby/gems/3.1.0/gems/jekyll-4.2.2/exe/jekyll:15:in `<top (required)>'
        from C:/Ruby31-x64/bin/jekyll:32:in `load'
        from C:/Ruby31-x64/bin/jekyll:32:in `<main>'


Add _authors folder

https://jekyllrb.com/docs/step-by-step/09-collections/

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