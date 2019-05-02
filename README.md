# This project is now archived and replaced by snowdrop/kreate (https://github.com/snowdrop/kreate)


---


# Snowdrop `scaffold` command

- `git clone` this project *outside* of your `$GOPATH` (since it uses `go modules`)
- Build: `go build -o scaffold cmd/scaffold.go`
- Run: `./scaffold`
- Enjoy!

## Use as `kubectl`-style plugin for `odo`

- Build the `kubectl-style-plugins` branch of `odo`
- `git clone` this project *outside* of your `$GOPATH` (since it uses `go modules`)
- Create (if it doesn't already exist) the `$HOME/.odo/plugins` directory
- Build: `go build -o scaffold.odo.plugin cmd/scaffold.go`
- Move the plugin to the `odo` plugins directory: `mv scaffold.odo.plugin ~/.odo/plugins/`
- Run: `odo scaffold`
- Enjoy!
