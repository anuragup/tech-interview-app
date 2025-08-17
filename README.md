# tech-interview-app
A Helm chart for deploying the gradyent/tech-interview:latest application

Packaged the Docker image into a Helm chart under charts/.

Configured readiness probe (/ returns OK) and liveness probe.

Chart supports overrides via values.yaml for multi-tenant deployments.

Optional Ingress (ALB) and Horizontal Pod Autoscaler can be enabled.
