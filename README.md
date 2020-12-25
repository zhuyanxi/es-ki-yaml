1. First apply es01-svc, es01, es02-svc, es02
2. Then es-nginx-config, kibana-config
3. Last es-nginx, es-nginx-svc, kibana, kibana-svc

# If you want another port, just change the nodePort value in kibana-svc and es-nginx-svc yaml file

# But if you have `kubectl` command, just cd into this directory and run `kubectl apply -f .`