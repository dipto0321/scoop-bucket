# dipto0321/scoop-bucket

Scoop bucket for [dipto0321/nodeup](https://github.com/dipto0321/nodeup).

## Install

```powershell
scoop bucket add dipto0321 https://github.com/dipto0321/scoop-bucket
scoop install nodeup
```

## How this is maintained

This bucket is **automatically managed** by
[GoReleaser](https://goreleaser.com/) on every `v*.*.*` tag push to
`dipto0321/nodeup`. Do not edit manifests by hand — your changes will
be overwritten on the next release.

The pipeline is configured in
[`.goreleaser.yaml`](https://github.com/dipto0321/nodeup/blob/main/.goreleaser.yaml)
under the `scoops:` section. Required secret on the nodeup repo:
`SCOOP_BUCKET_TOKEN` (fine-grained PAT with `contents:write` on this
repo).
