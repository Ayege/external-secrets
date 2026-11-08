# Deploy ESO securely: Relationship with risk model

## What is to be learned

<!-- the security model of ESO (SecretStore, ClusterSecretStore, ExternalSecret, Generators, ... , SA, and RBAC altogether) -->

## Where they will be going

<!-- Build a secure multi-tenant ESO setup with a single controller. Along the way, you will encounter the risks of deploying ESO in a way or another. -->

## Show visible results

### A single tenant

<!-- Show a single tenant deploying a secret store and an ES using a fake provider. You are on the right path: Observe the secret. -->

### Another tenant

<!-- Show another tenant being completely isolated... in apparence: do two ES, one within the tenant (observe the secret), the other trying to manipulate something outside the ns (observe the errors). Observe restrictions. -->

### SecretStore RBAC importance

<!-- Show SecretStore RBAC importance. Observe traversal. -->

### Generators

<!-- Do the same with Generators. -->
