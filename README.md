# mr

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/helpermethod/mr/master/LICENSE)
[![Maintainability](https://api.codeclimate.com/v1/badges/30893dd0a73aa942ce18/maintainability)](https://codeclimate.com/github/helpermethod/mr/maintainability)

Open GitLab Merge Requests from the commandline.

## Features

* no dependencies except `git`

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

A window with a new Merge Request will open in your browser.
