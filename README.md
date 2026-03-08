# AgentGate Helm Charts

Helm chart repository for AgentGate.

## Add repository

```bash
helm repo add agentgate https://raw.githubusercontent.com/EaCognitive/agentgate-charts/main
helm repo update
```

## Install

```bash
helm install agentgate agentgate/agentgate --namespace agentgate --create-namespace
```

## Artifact Hub metadata

The `artifacthub-repo.yml` file in this repository enables ownership claim and publisher verification workflow on Artifact Hub.
