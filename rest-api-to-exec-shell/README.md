# REST API to Execute Shell Commands
It is a golang REST API application to execute shell command

## Usage
```
# clone a repo
git clone https://github.com/jhaabhishek115/go-projects.git

# go rest-api-to-exec-shell dir
cd rest-api-to-exec-shell

# run

go run main.go


# sample payload to list files and folder under /mnt/d/go-projects dir
{
    "command": "ls",
    "arguments": ["-l","/mnt/d/go-projects"]
}

# Sample response
{
    {"Msg":"total 0\ndrwxrwxrwx 1 jhaabhishek115 jhaabhishek115 4096 Dec  1 22:56 rest-api-to-exec-shell\n"}
}
```
