# SonarQube Helm Chart

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Scalified/helm-sonarqube/blob/master/LICENSE)
[![Release](https://img.shields.io/github/v/release/Scalified/helm-sonarqube?style=flat-square)](https://github.com/Scalified/helm-sonarqube/releases/latest)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/scalified-sonarqube)](https://artifacthub.io/packages/helm/scalified-sonarqube/sonarqube)

## Requirements

* [Helm 3+](https://helm.sh)

## Installation

```bash
helm repo add scalified-sonarqube https://scalified.github.io/helm-sonarqube/
helm upgrade --install sonarqube scalified-sonarqube/sonarqube --create-namespace --namespace sonarqube
```

---

**Made with ❤️ by [Scalified](http://www.scalified.com)**
