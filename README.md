### Opencloudcx Helm Chart
- helm install opencloud ./opencloudcx-helm 
- helm uninstall opencloud
- helm install opencloudcx https://opencloudcx.github.io/grafana-helm/opencloudcx-0.0.1.tgz

### Modify and Regenerate Helm Chart
1. Modify as needed
2. Delete index.yaml and the .tgz file
3. Generate .tgz: hepm package .
4. Generate index.yaml: helm repo index . --url https://opencloudcx.github.io/grafana-helm
5. Test as above.
6. Commit and push your changes to: https://github.com/OpenCloudCX/grafana-helm