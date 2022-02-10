# Build

```
NFPM_DEFAULT_RPM_PASSPHRASE=123456789 goreleaser release --snapshot --rm-dist
```

With gorleaser < 1.2.0 above command works - for newer versions it does not work anymore.
