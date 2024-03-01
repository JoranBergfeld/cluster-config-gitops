### External Secrets

This folder configures external secrets for the cluster. One manual step is needed. 
You should configure a service principal to be authorized to read from the secret store configured.
The `ClusterSecretStore` reads from a secret called `azure-secret-sp`.