#### Deploy Integrations as CAR file

### Running CAR Deploy with Environment (-D) and Profile with (-P) :

You can build CAR with below command and default profile is deploy
```mvn clean install```

You can run deploy (Local is default). 
```mvn clean deploy -P deploy -D env=dev```

Configured environment are 
* dev
* prod

Configured Profile are 
* build - all modules are build
* deploy - deploy cars in all car modules