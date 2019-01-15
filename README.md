# mr

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/helpermethod/mr/master/LICENSE)

A Bash script to open GitLab Merge Requests from the commandline.

## Features

* uses `open` on Mac OS X and `xdg-open`on Linux

## Installation

```sh
curl -sSL https://raw.githubusercontent.com/helpermethod/mr/master/mr > /usr/local/bin/mr && chmod +x /usr/local/bin/mr
```

## Usage

After you have pushed a commit, type `mr` on the commandline.

```sh
git commit -a -m 'Update README.md'
git push
mr
```

A window with the new Merge Request will open in your browser.
