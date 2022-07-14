# Kubernetes tasks

1. Using `helm`, provision `podinfo` as follows:

   - Use the chart in the local `podinfo/` subdirectory
   - Use the `custom-values.yaml`
   - Use the release name `interview-podinfo`
   - Use the namespace `interview-podinfo` (create if necessary)

2. Fix deployment issues & show troubleshooting
3. Scale the `interview` deployment up to 2 replicas
4. Trigger a rolling restart the `interview` deployment
5. Show the recent Helm history for the `interview` release
6. Uninstall Helm `interview` Helm chart
