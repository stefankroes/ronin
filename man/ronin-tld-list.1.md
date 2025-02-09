# ronin-tld-list 1 "May 2022" Ronin "User Manuals"

## SYNOPSIS

`ronin tld-list` [*options*]

## DESCRIPTION

Updates and parses the TLD list file.

## OPTIONS

`-v`, `--verbose`
  Enables verbose output.

`-u`, `--update`
  Updates the TLD list file.

`-U`, `--url` *URL*
  The URL to the TLD list. Defaults to
  `https://data.iana.org/TLD/tlds-alpha-by-domain.txt`.

`-p`, `--path` *FILE*
  The Path to the TLD list file. Defaults to
  `~/.cache/ronin/ronin-support/tlds-alpha-by-domain.txt` if not given.

`-h`, `--help`
  Print help information

## FILES

`~/.cache/ronin/ronin-support/tlds-alpha-by-domain.txt`
  The location of the downloaded TLD list.

## AUTHOR

Postmodern <postmodern.mod3@gmail.com>

## SEE ALSO

ronin-public-suffix-list(1)
