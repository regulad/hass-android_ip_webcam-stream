# HACS Template

This is a super-simple template to get started with creating a HACS-compatible repository.

Remember to update the `hacs.json` with your own information.

Also update this file!

## Integration

Your `custom_components/awesome/manifest.json` should look like this:

```json
{
  "domain": "lacrosseview",
  "name": "La Crosse View",
  "documentation": "https://github.com/regulad/hass-lacrosseview",
  "issue_tracker": "https://github.com/regulad/hass-lacrosseview/issues",
  "dependencies": [],
  "codeowners": [
    "@regulad"
  ],
  "version": "0.1.2",
  "requirements": [
    "pylacrosseview==0.1.5"
  ],
  "iot_class": "cloud_polling",
  "config_flow": true,
  "loggers": [
    "pylacrosseview"
  ]
}
```
