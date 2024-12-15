## GitHub Copilot Chat

- Extension Version: 0.22.4 (prod)
- VS Code: vscode/1.95.3
- OS: Mac

## Network

User Settings:
```json
  "github.copilot.advanced": {
    "debug.useElectronFetcher": true,
    "debug.useNodeFetcher": false
  }
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 140.82.112.5 (14 ms)
- DNS ipv6 Lookup: ::ffff:140.82.112.5 (1 ms)
- Electron Fetcher (configured): HTTP 200 (136 ms)
- Node Fetcher: HTTP 200 (124 ms)
- Helix Fetcher: HTTP 200 (215 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.113.21 (20 ms)
- DNS ipv6 Lookup: ::ffff:140.82.113.21 (18 ms)
- Electron Fetcher (configured): HTTP 200 (158 ms)
- Node Fetcher: HTTP 200 (137 ms)
- Helix Fetcher: HTTP 200 (135 ms)

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copicatlot).