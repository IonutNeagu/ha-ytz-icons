## Usage:
Install the plugin and use it like in this example:

```yaml
title: YTZ Icon Pack
type: entities
entities:
  - entity: sensor.demo_icon
    icon: ytz:air-conditioner
```

![Example](https://raw.githubusercontent.com/IonutNeagu/ha-ytz-icons/main/docs/screenshot.png)

### Systemwide availability (Optional)
The steps above will make the icons available, but limited to the Lovelace UI only. If you want the icons to be available throughout Home Assistant, add the following to the `frontend` section of your `configuration.yaml`

```yaml
frontend:
  extra_module_url:
    - /hacsfiles/ha-ytz-icons/ha-ytz-icons.js
```

For this step, a system restart is needed.