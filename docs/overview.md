# Overview

[简体中文](overview.zh-CN.md) | [Docs Index](README.md)

## Purpose

Inbound flow-control handlers for Gnalloy pipelines with bounded pending message and byte budgets.

This module provides Pipeline handlers. A handler observes, transforms, rejects, delays, records, or protects messages after a Channel already exists. It does not own listening sockets or application protocols unless explicitly named.

## Repository Identity

- Module path: `gnalloy.org/handler-flow`
- GitHub repository: `github.com/gnalloy/handler-flow`
- Default branch: `dev`
- License: Apache-2.0

## Package Map
- `gnalloy.org/handler-flow` (`flow`)

## Direct Gnalloy Dependencies
- `gnalloy.org/gnalloy`

## Direct Dependents in the Current Module Plan
- No repository in the current module plan depends on this module directly.

## Architecture Position

Gnalloy keeps the core small and dependency-light. This repository is a replaceable module around one responsibility, connected through explicit Go packages instead of runtime discovery.

## Compatibility

The public import path is `gnalloy.org/handler-flow`. Until the first stable tag is published, use `@dev` or an explicit pseudo-version selected by your dependency policy.
