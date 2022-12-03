# gotests-templates
Custom templates for https://github.com/cweill/gotests

## Example usage

Use go get to install and update gotests:

```
$ go get -u github.com/cweill/gotests/...
```

Clone gotests-templates:

```
$ cd ~
$ git clone https://github.com/djjuhasz/gotests-templates.git
```

Use the templates when generating tests:

```
$ cd ~/go/myproject
$ gotests -w -parallel -template_dir ~/gotests-templates/templates -all main.go
```
