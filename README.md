# Helm chart not automerge #36920 

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

I have setup my helm charts to automerge with patch, minor changes.  
However only my kube-prometheus-stack chart is automerging.  
The envoy-gateway is not automerging only creating PR's with updates.

## Expected behavior

Both the kube-prometheus-stack and envoy-gateway charts should automerge.

