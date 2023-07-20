<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| check-retry-count | Check retry count | 5 | false |
| check-retry-interval | Check retry interval (in seconds) | 10 | false |
| expected\_state | Commit status state wait for. Valid values 'success', 'error', 'failure', 'pending' | success | false |
| repository | Repository | N/A | true |
| sha | Commit SHA | N/A | true |
| status | Commit status name | N/A | true |
| token | Github authentication token | ${{ github.token }} | false |


<!-- markdownlint-restore -->
