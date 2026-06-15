# Unraid Glass Themes

Custom glass-style themes for the Unraid WebUI with matching **Purple** and **Red** variants.

These themes provide a modern translucent interface while preserving readability and the overall Unraid experience.

<img width="1708" height="1278" alt="image" src="https://github.com/user-attachments/assets/cf7452ef-2b46-43d7-b1f5-a185f65e616e" />

<img width="1708" height="1275" alt="image" src="https://github.com/user-attachments/assets/fafb8b0f-5f8b-49df-986b-83a8cccb91a9" />

<img width="1718" height="1276" alt="image" src="https://github.com/user-attachments/assets/9e17fc45-5849-46e0-b025-61d2b9d1cdad" />


## Features

* Glass / frosted-glass dashboard widgets
* Transparent header and navigation
* Theme-colored dashboard controls and icons
* Themed server name gradient
* Themed Unraid logo tint
* Consistent spacing and widget styling
* Glass-styled table containers
* Docker widget transparency improvements
* Green active navigation indicator
* Matching Purple and Red theme variants

## Included Themes

### Purple Theme

* Purple accents and controls
* Purple server-name gradient
* Purple-tinted Unraid logo

### Red Theme

* Red accents and controls
* Red server-name gradient
* Red-tinted Unraid logo

## Requirements

* Unraid 7.x
* Custom CSS plugin (or another method of loading custom CSS)
* A background image located at:

```text
/plugins/custom.css/assets/bg.jpg
```

If you use a different image location, update the CSS accordingly.

## Installation

1. Install the Custom CSS plugin.
2. Copy the desired theme CSS file.
3. Paste the contents into your Custom CSS configuration.
4. Save the configuration.
5. Refresh the Unraid WebUI.

## Custom Background

The themes expect a background image at:

```text
/plugins/custom.css/assets/bg.jpg
```

You can replace this with your own image by updating:

```css
body {
  background-image: url('/plugins/custom.css/assets/bg.jpg');
}
```

## Theme Variables

The following variables control most of the appearance:

```css
--custom-dashboard-tile-bg
--custom-dashboard-tile-border
--custom-dashboard-tile-shadow
--custom-dashboard-tile-blur

--custom-theme-accent
--custom-theme-accent-strong
--custom-theme-text
--custom-theme-icon
--custom-theme-icon-hover
```

Adjusting these values allows you to create additional color variants.

## Notes

* The themes use modern CSS features including `:has()`.
* Tested primarily with Chromium-based browsers.
* Custom plugin pages may require additional styling depending on the plugin.
* Personal overrides are best kept in a separate CSS file so updates remain simple.

## License

MIT License

Feel free to modify, redistribute, and build upon these themes.
