# Welcome User Element

This element simply displays 'Welcome [User]'. 
## Options

| Name | Type | Default | Description
| ---- | ---- | ------- | -----------
| type | string | **Required** | `custom:welcome-user-element`

## Installation

### Step 1

Install `welcome-user-element` by copying `welcome-user-element.js`from this repo to `<config directory>/www/welcome-user-element.js` on your Home Assistant instanse.

### Step 2

Link `welcome-user-element` inside you `ui-lovelace.yaml`.

```yaml
resources:
  - url: /local/welcome-user-element.js
    type: js
```

### Step 3

Add a custom element in your `ui-lovelace.yaml`

```yaml
      - type: custom:welcome-user-element
```
