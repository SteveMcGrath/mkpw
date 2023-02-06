# A simple memorable password generator

The goal here was a simple password generator that will smash words together to
create a memorable password with a special character in between each word.  One
of the words will be uppercased.  The only options really available is the
number of words to be used.

The tool was written using the memorable library to enable offline wordlists.

```
❯ mkpw --help

 Usage: mkpw [OPTIONS] [NUM_WORDS]

 Memorable Password Generator
 Generates a password that should be able to be easily remembered

╭─ Arguments ──────────────────────────────────╮
│   num_words      [NUM_WORDS]  [default: 5]                                │
╰─────────────────────────────────────────╯
╭─ Options ───────────────────────────────────╮
│ --clip   -c               Send the password to the clipboard              │
│ --timer  -t      INTEGER  How many seconds to keep the password in in     │
│                           the clipboard? [default: None]                  │
│ --help                    Show this message and exit.                     │
╰─────────────────────────────────────────╯


❯ mkpw
Generated Pasword: golden-perch+intentionally-IRRELEVANTLY0lumpy7dacentrurus
❯ mkpw 3
Generated Pasword: coaxingly_STUPENDOUS?worker
```
