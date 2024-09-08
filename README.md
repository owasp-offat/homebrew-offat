# owasp-offat Homebrew Tap

## What is Homebrew?

Package manager for macOS (or Linux), see more at https://brew.sh

## What is a Tap?

A third-party (in relation to Homebrew) repository providing installable
packages (formulae) on macOS and Linux.

See more at https://docs.brew.sh/Taps

## How do I install packages from here?

* Install offat

    ```bash
    # Formulae
    brew install owasp-offat/tap/offat
    ```

## Hook Tap

You can also only add the tap which makes formulae within it
available in search results (`brew search` output):

* Tap using SSH 
    
    ```bash
    brew tap owasp-offat/tap
    ```

* Tap using https

    ```bash
    brew tap owasp-offat/tap https://github.com/owasp-offat/homebrew-tap
    ```

While you may search across taps, it is necessary to always use
fully qualified name (incl. the `owasp-offat/tap/` prefix)
when refering to formulae in external taps such as this one
outside of search.

## What packages are available?

With the following commands, you can install the latest generally available (GA) version of each product:



