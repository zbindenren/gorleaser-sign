# Build

```
NFPM_DEFAULT_RPM_PASSPHRASE=123456789 goreleaser release --snapshot --rm-dist
```

With gorleaser < 1.2.0 I get a valid gpg signature - with all later versions I get rubbish...
