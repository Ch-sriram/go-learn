# Golang

- Learn fundamentals and advanced concepts of the Go programming language.

## Getting Started

1. Install go from <https://go.dev/dl/>
   - Verify `go` installation as follows:

     ```terminal
     user@local $ ~: go version 
     ```

2. Install VS Code from <https://code.visualstudio.com/download> (or use any existing text editor).

## `GO` CLI

| Command      | What does it do?                                            |
| ------------ | ----------------------------------------------------------- |
| `go build`   | Compiles go source code files and generates an executable.  |
| `go run`     | Compiles and executes one or two go source code files.      |
| `go fmt`     | Formats all the code in each file in the current directory. |
| `go install` | Compiles and "installs" a package.                          |
| `go get`     | Downloads the raw source code of someone else's package.    |
| `go test`    | Runs any tests associated with the current project.         |

### Useful Commands

1. `go run <file.go>`:

   ```sh
   go run main.go
   ```

2. `go build <file.go>`:

   ```sh
   go build main.go
   ```

   > Generates a `main` executable file which can be run as: `./main`s
