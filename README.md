# 🚀 EKS Lab

Amazon EKS（Elastic Kubernetes Service）を使った Kubernetes の基本操作を学ぶためのハンズオン教材です。Pod、Service、RBAC、Secrets など、実践的なリソース管理を体験できます。

---

## 📝 Overview

このリポジトリでは、以下の内容を学習できます：

- EKS クラスターの構築と操作
- Kubernetes の基本リソース（Pod、Service、Deployment など）の作成
- RBAC を用いたアクセス制御
- Secrets を使った機密情報の管理

---

## ✅ Precondition

- AWS アカウント
- AWS CLI のインストールと設定
- kubectl のインストール
- eksctl のインストール（EKS クラスターの作成に使用）

## 📁 Directory structure
- chapter-01/：Pod の作成と基本操作
- chapter-02/：ReplicaSet によるスケーリング
- chapter-03/：Service（NodePort）による外部公開
- chapter-04/：Deployment を使ったローリングアップデート
- namespaces/：Namespace の活用
- rbac/：RBAC を用いたアクセス制御
- secrets/：Secrets の管理と利用
