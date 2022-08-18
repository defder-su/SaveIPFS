<h1 align="center">SaveIPFS</h1>

<p align="center">The collection of scripts for ipfs.</p>

## Features:

- Save (pin) content, specified by hashes.
- Save (nonrecursive pin) catalogs.
- Save by lists.

---

## Installation (Linux, macOS):

Install [ipfs](https://github.com/ipfs/go-ipfs).

Open a terminal in the folder and run `chmod +x save*`.

---

## Installation (Windows):

Install [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (requires about 2GB disk space), [Cygwin](https://www.cygwin.com/), [Git Bash](http://git-scm.com), or some other tool that enables Bash functionality in Windows.

Follow the above section.

---

## Usage:

Open a terminal in the folder and run `./save` or other script with arguments.

### Save content (recursive pin with 5 min timeout):
`./save QmbnQ5FPFVDFvBQ1oTW6YskpbXKSD1c9nfFkhUFbxBL9cE`

### Save list:
`./save_by_list example.txt`

### Save catalog (non-recursive pin):
`./save_catalog QmP7LM9yHgVivJoUs48oqe2bmMbaYccGUcadhq8ptZFpcD`

---

## TODO:

Implement pinning subdirectories in the `save_catalog` command.

---

## Related Projects:

- [SaveSites](https://github.com/defder-su/SaveSites)

- [SaveMedia](https://github.com/defder-su/SaveMedia)

- [RatBrowser](http://ratbrowser.com)

- [IPFS](https://ipfs.io)

- [ZeroNet](https://zeronet.dev)

