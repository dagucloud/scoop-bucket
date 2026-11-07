# Scoop bucket for Dagu

Install [Dagu](https://github.com/dagucloud/dagu) on Windows with [Scoop](https://scoop.sh):

```powershell
scoop bucket add dagu https://github.com/dagucloud/scoop-bucket
scoop install dagu
```

Upgrade with `scoop update dagu`.

The manifest in `bucket/dagu.json` is generated and committed by
[GoReleaser](https://goreleaser.com) from the Dagu release workflow on every
stable release. Do not edit it by hand; changes belong in the `scoops` section
of `.goreleaser.yaml` in the Dagu repository.
