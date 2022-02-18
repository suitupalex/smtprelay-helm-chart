# smtprelay-helm-chart

Helm chart for [smtprelay](https://github.com/decke/smtprelay). Uses the
[grafana/smtprelay](https://hub.docker.com/r/grafana/smtprelay) image by default.

## Configuration

The following `smtprelay` command line flags are supported:

| Parameter            | Description                                                      | Default               |
| -------------------- | ---------------------------------------------------------------- | --------------------- |
| `config.remote_host` | Remote SMTP Hostname and Port                                    | `smtp.example.com:25` |
| `config.remote_user` | Remote SMTP Username. This will automatically be base64 encoded. | `username`            |
| `config.remote_pass` | Remote SMTP Password. This will automatically be base64 encoded. | `password`            |
