Contribute
==========

You may buy me a Beer, a Tea or help with Server fees with a paypal donation to
the address <paypal@rapsys.eu>.

Don't forget to show your love for this project, feel free to report bugs to
the author, issues which are security relevant should be disclosed privately
first.

Patches are welcomed and grant credit when requested.

Installation
============

Install cpack and jpack binaries
--------------------------------

You need to have cpack and jpack scripts from this repository
set as executable and installed in /usr/local/bin.

### Step 1: Install the required perl packages

To install cpack and jpack required packages open a root console and execute
the following command:

```console
# urpmi perl-base perl-CSS-Packer perl-JavaScript-Packer
```

or stone age distributions:

```console
# apt-get install libcss-packer-perl libjavascript-packer-perl
```

or other distributions through cpan:

```console
# cpan App::cpanminus
# cpanm CSS::Packer
# cpanm JavaScript::Packer
```

### Step 2: Install the binaries

To install cpack and jpack binaries open a root console and execute the
following command:

```console
# cp cpack jpack /usr/local/bin/
```

Use cpack and jpack binaries
----------------------------

To use local binaries you may execute the following commands:

```console
$ cpack < input.css > output.css
```

```console
$ jpack < input.js > output.js
```
