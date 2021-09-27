# GoatCounter partial template for Hugo

## Usage

### Template

{{ partial "goat-counter.html"}}

### Configuring with goatcounter.com subdomain

config.yaml

```yaml
params:
  goatCounterId: [goatCounter subdomain]
```

### Configuring with custom domain

config.yaml

```yaml
params:
  goatCounterUri: https://[your-domain]/count
```
