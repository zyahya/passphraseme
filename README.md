# passphraseme

A quick and simple cryptographically secure script to generate high entropy passphrases using [the Electronic Frontier Foundation's wordlists](https://www.eff.org/deeplinks/2016/07/new-wordlists-random-passphrases), including their [fandom-inspired wordlists](https://www.eff.org/deeplinks/2018/08/dragon-con-diceware).

## Usage

You can also optionally choose a different wordlist. Here are all of the command line arguments:

| Short             | Long                        | Description                                                           |
|-------------------|-----------------------------|-----------------------------------------------------------------------|
| `-h`              | `--help`                    | show help message                                                     |
|                   | `--sep`                     | Separator (default "-")                                               |
| `-l`              | `--large`                   | Use EFF's general large wordlist                                      |
| `-s1`             | `--short1`                  | Use EFF's general short wordlist (default)                            |
| `-s2`             | `--short2`                  | Use EFF's short wordlist with unique prefixes                         |
| `-got`            | `--game-of-thrones`         | Use EFF's Game of Thrones wordlist (Passwords of Westeros)            |
| `-hp`             | `--harry-potter`            | Use EFF's Harry Potter wordlist (Accio Passphrase!)                   |
| `-st`             | `--star-trek`               | Use EFF's Star Trek wordlist (Live Long and Passphrase)               |
| `-sw`             | `--star-wars`               | Use EFF's Star Wars wordlist (The Passphrase Is Strong With This One) |
| `-d [dictionary]` | `--dictionary [dictionary]` | Custom wordlist filename                                              |

## Licenses

The wordlists included were created by Electronic Frontier Foundation, and are
distributed under the Creative Commons Attribution 3.0. For the fandom wordlists
(Game of Thrones, Harry Potter, Star Trek, and Star Wars), EFF notes that "Any
trademarks within the word list are the property of their respective trademark
holders, who are not affiliated with the Electronic Frontier Foundation and do
not sponsor or endorse these passwords."
