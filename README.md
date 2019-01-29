# ssmv-today (Screenshot Move Today)

Command line tool to move all macOS creenshots taken today into a folder labeled `screenshots_YYYY-MM-DD`.

## Installation

In your terminal, run the following commands:

```sh
git clone https://github.com/dev-cprice/ssmv-today.git
cd ssmv-today
cp ssmv-today /usr/local/bin/ssmv-today
```

## Usage

Take as many screenshots as you want with `cmd+shift+3` or `cmd+shift+4`, then in your terminal, run `ssmv-today`:

```sh
# ex: 6 screenshots taken today, located at ~/Desktop
$ ssmv-today
Making new folder at: /Users/YOUR_USERNAME/Desktop/2019-01-23
Moving 6 screenshots from today into /Users/YOUR_USERNAME/Desktop/2019-01-23
```
