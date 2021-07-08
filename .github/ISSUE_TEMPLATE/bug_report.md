---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

For asking questions, see:
- [GitHub Discussions (Q&A)](https://github.com/golang/vscode-go/discussions/categories/q-a)
- [`#vscode` channel in Gophers Slack](https://invite.slack.golangbridge.org/messages/vscode)

Before filing an issue, please review our troubleshooting guides
* [Troubleshooting problems with debugging](https://github.com/golang/vscode-go/blob/master/docs/debugging.md#troubleshooting)
* [Troubleshooting other problems](https://github.com/golang/vscode-go/tree/master/docs/troubleshooting.md)

Please answer these questions before submitting your issue. Thanks!

### What version of Go, VS Code & VS Code Go extension are you using?
* Run `go version` to get version of Go from _the VS Code integrated terminal_.
	- <Paste go version here>
* Run `gopls -v version` to get version of Gopls from _the VS Code integrated terminal_.
	- <Paste gopls version here>
* Run `code -v` or `code-insiders -v` to get version of VS Code or VS Code Insiders.
	- <Paste VS Code version here>
* Check your installed extensions to get the version of the VS Code Go extension
	- <Paste Go extension version here>
* Run Ctrl+Shift+P (Cmd+Shift+P on Mac OS) > `Go: Locate Configured Go Tools` command.
	- <Paste the output here>

### Share the Go related settings you have added/edited

Run `Preferences: Open Settings (JSON)` command to open your settings.json file.
Share all the settings with the `go.` or `["go"]` or `gopls` prefixes.

### Describe the bug
A clear and concise description of what the bug.
A clear and concise description of what you expected to happen.

### Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. See error

### Screenshots or recordings
If applicable, add screenshots or recordings to help explain your problem.
