# Semgrep Quickstart

## How to scan

### Scan with `console` output
```
semgrep scan --config rules TARGET_REPOSITORY_PATH
```

### Scan with `json` output
```
semgrep scan --config rules --output result.json --json TARGET_REPOSITORY_PATH
```

### Scan with `sarif` output
```
semgrep scan --config rules --output result.sarif --sarif TARGET_REPOSITORY_PATH
```

## How to test rules
```
semgrep --test rules
```
