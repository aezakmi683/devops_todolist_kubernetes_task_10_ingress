@"
# INSTRUCTION

## Validation

1. Start the Kind Kubernetes cluster using the provided `cluster.yml` configuration.

2. Deploy the application and install the NGINX Ingress Controller using `bootstrap.sh`.

3. Apply the Ingress manifest:

   ````powershell
   kubectl apply -f .\.infrastructure\ingress\ingress.yml