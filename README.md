# Package Helm GHCR Action

Package a helm chart and deploy to an GHCR repository using OCI
## Full Example usage

```yaml
- name: Package and Push a Helm Chart to GHCR
  uses: explorium-ai/package-helm-ghcr-action@main
  with:
    gh-token: fadsfads********
    gh-repo-owner: mycompany
    chart-path: ./charts/mychart
```