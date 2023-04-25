# Argo Rollouts Operator

**Project Status: BETA**

Not all planned features are completed. The API, spec, status and other user facing objects may change.

## Summary

A Kubernetes operator for managing [Argo Rollouts](https://github.com/argoproj/argo-rollouts/). This operator provides an easy way to install, upgrade and manage the lifecycle of Argo Rollouts.

This operator is built using `operator-sdk`, version - `v1.28.0`.

## What exactly the operator does ?

When Installed, this operator creates a Custom Resource Definition called ArgoRollout. 

Operator will then wait for the users to deploy the corresponding Custom Resource with required fields to create the rollout controller and other resources.






