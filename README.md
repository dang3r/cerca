# Cerca

----

Cerca is a library and set of scripts used to determine if any links on a given domain link a list of
blacklisted domains.

----

## Install

```
pip3 install cerca
```

## Example

```
$ cerca https://www.google.ca
200 https://www.google.ca
200 https://www.google.ca/preferences?hl=en
200 https://www.google.ca/advanced_search?hl=en&authuser=0
200 https://www.google.ca/language_tools?hl=en&authuser=0
200 https://www.google.ca/intl/en/ads/
200 https://www.google.ca/services/
200 https://www.google.ca/intl/en/about.html
...
```
