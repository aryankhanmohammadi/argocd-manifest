---

1) kubectl applay -f create-namespace.yaml or create manually argocd namespace (create namespaace argocd) 

2) kubectl applay -f argomanifest.yaml -n argocd ( create argocd pods )

3) kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d; echo                 ( get First Password )

4) user is Admin and Plz Change Password


