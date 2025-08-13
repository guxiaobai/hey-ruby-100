# Hey Ruby 100



## Ubuntu

> `22.04`

```bash
sudo apt-get install -y ruby ruby-dev ruby-bundler
```



## macOS

> `Ventura`

```bash
brew install ruby@3.3
```

> 没有自动创建这个目录，以前是会创建的

```bash
# gem update --system --verbose -N
# gem env |grep 'EXECUTABLE DIRECTORY'
mkdir -p /usr/local/lib/ruby/gems/3.3.0/bin
```

> `Apple silicon`

```bash
fish_add_path /opt/homebrew/opt/ruby@3.3/bin
fish_add_path /opt/homebrew/lib/ruby/gems/3.3.0/bin
```

> `Intel-based`

```bash
fish_add_path /usr/local/opt/ruby@3.3/bin
fish_add_path /usr/local/lib/ruby/gems/3.3.0/bin
```







## Ref



* <https://www.ruby-lang.org/en/>