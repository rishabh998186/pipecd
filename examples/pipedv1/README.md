# PipeCD v1 (Plugin-Arch) Examples

Examples demonstrating pipedv1 usage with plugin-based architecture.

## Examples

- `kubernetes/`: Basic Kubernetes deployment with pipedv1

## Key Differences from Legacy Piped

- Use `kind: Application` instead of `kind: KubernetesApp`
- Configure `plugins` instead of `platformProviders`  
- Use `deployTargets` in plugin config

## Prerequisites

- PipeCD control plane v1.0.0-rc0 or later
- Pipedv1 agent installed and configured
- Kubernetes cluster access
