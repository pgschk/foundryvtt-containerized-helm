# Foundry VTT containerized Helm chart

Helm chart for https://github.com/pgschk/foundryvtt-containerized.

## Important Helm values

| Helm value              | Description                                                                                   | Example     |
|-------------------------|-----------------------------------------------------------------------------------------------|-------------|
| foundryVTTDownloadURL   | Timed Download URL you obtained through your [FoundryVTT.com](https://foundryvtt.com) account | https://... |
| persistence.installSize | Size of the volume for the FoundryVTT installation as Kubernetes quantinty                    | 2Gi         |
| persistence.dataSize    | Size of the volume for your FoundryVTT data as Kubernetes quantinty                           | 20Gi        |

