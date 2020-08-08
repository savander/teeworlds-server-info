Teeworlds Servers Info tool to extract details about servers to JSON.

# Usage

Give list of servers to gather information from and the application with generate file (`servers.json` by default) with server information.
You can use it futher in other applications.

The port in address `127.0.0.1:<port>` is not required, `8303` will be used by default.

```bash
python app.py --server "Server_01" "127.0.0.1:8304"
```

You can change filename as well as path where the file will be stored by using parameters `-f`, `--file`, `-p`, `--path`

```bash
python app.py --path "/home/teeworlds" --file "custom_servers.json" --server "Server_01" "127.0.0.1:8304"
```
