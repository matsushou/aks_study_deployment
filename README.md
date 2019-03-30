# aks_study で説明する echo-service をデプロイする kustomize

## 変更するファイル

- [base/deployment.yaml](base/deployment.yaml)
    - イメージをpullする先のACRのホスト名に置き換える
- [overlays/staging/service-staging.yaml](overlays/staging/service-staging.yaml)
    - ロードバランサー用に生成した静的IPに書き換える
