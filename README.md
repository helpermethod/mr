# mr
A Bash script to open GitLab Merge Requests from the commandline.

## Installation

```sh
curl -sSL https://raw.githubusercontent.com/helpermethod/mr/master/mr > /usr/local/bin/mr && chmod u+x !$
```

## Usage

After you have pushed a commit, type `mr on the commandline.

```sh
git commit -a -m 'Update README.md'
git push
mr
```

A browser window with the new Merge Request will open in your browser.
