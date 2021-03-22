# HACS Install - Step by Step

### Find the plugin and install
<img src="./docs/find.png" width="600" ><br />
<img src="./docs/install.png" width="600" ><br />

### Reload
<img src="./docs/reload.png"  width="600" ><br />

The icons will be available under the `ytz` namespace, eg ytz:air-conditioner

There is no need to restart.

### Systemwide availability (Optional)
The steps above will make the icons available, but limited to the Lovelace UI only. If you want the icons to be available throughout Home Assistant, add the following to the `frontend` section of your `configuration.yaml`

```yaml
frontend:
  extra_module_url:
    - /hacsfiles/ha-ytz-icons/ha-ytz-icons.js
```

For this step, a system restart is needed.