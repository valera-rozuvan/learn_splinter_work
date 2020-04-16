# Learn splinter work

Learning the splinter testing framework for web apps.

## Setup

1. Installing latest `splinter` via `pip3` did not give a successful result. Scripts ran with an error:

```
local variable 'e' referenced before assignment
```

Reading issue https://github.com/cobrateam/splinter/issues/748 - I tried to install latest source from GitHub, and the error went away.

2. You need a working `geckodriver` in your PATH. Download latest binary release from https://github.com/mozilla/geckodriver/releases . Make sure it's in some location, where it can be found by Python.

## Running

Try:

```
python3 simple_test/main.py
```

If everything goes OK, you should see:

```
Yes, the official website was found!
```
