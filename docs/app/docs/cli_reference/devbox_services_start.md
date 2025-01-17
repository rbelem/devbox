# devbox services start

Starts a service or list of services. If no service is specified, starts all services + process-compose.

```bash
devbox services start [service]... [flags]
```

:::info
  Note: We recommend using `devbox services up` if you are starting all your services and process-compose. This command lets you specify your process-compose file and whether to run process-compose in the foreground or background.
:::

## Options

<!-- Markdown Table of Options -->
| Option | Description |
| --- | --- |
| `-h, --help` | help for start |
| `-q, --quiet` | Quiet mode: Suppresses logs. |

## SEE ALSO

* [devbox services](devbox_services.md)	 - Interact with devbox services
