```sh
nix-shell -p tinyproxy --command "tinyproxy -d -c tinyproxy.conf"
nix-shell -p chromium --command "chromium --proxy-server=localhost:8888"
```

