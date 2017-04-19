

1. `kubectl create -f config/`
2. `kubectl proxy --port=4444 &`
3. Connect via: `http://127.0.0.1:4444/api/v1/namespaces/default/services/selenium-hub-service/proxy/wd/hub`
