---

1) create argocd namespace or kubectl applay -f create-namespace.yaml 

2) kubectl applay -f install -n argocd ( create argocd pod )

3) kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d; echo  ( get First Password )

4) Change password 


