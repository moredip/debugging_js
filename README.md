# How do I...?

All developer tasks - like running tests or starting a server in dev mode - are handled via our `./go` script. 

Run `./go` to see a list of commands.

Run `./go <COMMAND>` to run a specific command. For example `./go test` will run our automated tests.

### the gory details 

If you're wondering what's happening under the hood, that `./go` script is simply delegating to a dockerized "workshop" container which is responsible for managing all our dev tooling and dependencies. See [this](https://www.thoughtworks.com/insights/blog/praise-go-script-part-i) article for some backgroun.
