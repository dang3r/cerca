# Cerca

----

Cerca is a tool used to determine if any links on a given domain link a list of
blacklisted domains.

----

## Example

```
$ python3 cerca.py -h
usage: cerca.py [-h] domain blacklist

Cerca recursively searches a website for links to other websites. The website
must be static because a headless browser is not used.

positional arguments:
  domain      Website to search for blacklisted links
  blacklist   Blacklisted urls. Check if they are linked to from the website.

optional arguments:
  -h, --help  show this help message and exit
```
