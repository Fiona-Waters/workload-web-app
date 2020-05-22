# workload-web-app
A test app for simulating the workload on the openshift cluster based on end-user use cases in order to monitor the downtime of component products in integreatly during an upgrade.


## Deploying the Application on the cluster

To deploy the webapp on your cluster:

> Note: 
🍎 (Mac users) - install gtimeout util and create a symbolic link (so it can be referenced as timeout):
```brew install coreutils && sudo ln -s /usr/local/bin/gtimeout /usr/local/bin/timeout```

### Steps

 Login to your cluster using ` oc login ` command and run 

> ```make deploy```

Try to access the route displayed in your terminal from any browser.
