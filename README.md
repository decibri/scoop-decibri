# scoop-decibri

Scoop bucket for decibri command-line tools.

## Prerequisites

Scoop must be installed. If it is not, run this once in PowerShell (no admin required):

```powershell
irm get.scoop.sh | iex
```

## Install

Add the bucket, then install:

```powershell
scoop bucket add decibri https://github.com/decibri/scoop-decibri
scoop install decibri-cli
```

Verify the install:

```powershell
decibri --version
```

## Update and uninstall

```powershell
scoop update decibri-cli
scoop uninstall decibri-cli
```

## Available tools

- `decibri-cli`: audio capture, playback, and device listing from the terminal. See the [decibri CLI documentation](https://decibri.com/docs/apis/cli).
