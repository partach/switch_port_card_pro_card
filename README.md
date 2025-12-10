# switch_port_card_pro_card
The card that is complementary to the [switch_port_card_pro](https://github.com/partach/switch_port_card_pro) integration.

[![Home Assistant](https://img.shields.io/badge/Home_Assistant-00A1DF?style=flat-square&logo=home-assistant&logoColor=white)](https://www.home-assistant.io)
[![HACS](https://img.shields.io/badge/HACS-Default-41BDF5?style=flat-square)](https://hacs.xyz)
[![HACS Action](https://img.shields.io/github/actions/workflow/status/partach/switch_port_card_pro_card/validate-hacs.yml?label=HACS%20Action&style=flat-square)](https://github.com/partach/switch_port_card_pro_card/actions)
[![Installs](https://img.shields.io/github/downloads/partach/switch_port_card_pro_card/total?color=28A745&label=Installs&style=flat-square)](https://github.com/partach/switch_port_card_pro_card/releases)
[![License](https://img.shields.io/github/license/partach/switch_port_card_pro_card?color=ffca28&style=flat-square)](https://github.com/partach/switch_port_card_pro_card/blob/main/LICENSE)
[![HACS validated](https://img.shields.io/badge/HACS-validated-41BDF5?style=flat-square)](https://github.com/hacs/integration)

This repository is only made because home assistant does not allow an integration-card combo installation.

<p align="center">
  <img src="https://github.com/partach/switch_port_card_pro/blob/main/pro%20card%20visual.png" width="600"/>
  <br>
  <em>Live port status per switch with color coding: 10M/100M (orange), 1G (green), 10G (blue), DOWN (black)</em>
</p>

## Quick Install (with Integration)
See [switch_port_card_pro](https://github.com/partach/switch_port_card_pro) integration
1. Install the **integration** first: HACS > Integrations > Search "Switch Port Card Pro" > Install.
2. Install this **card**: HACS > Frontend > Search "Switch Port Card Pro" > Install.
3. Reload page → Add to dashboard: `type: custom:switch-port-card-pro`.

## Manual (No HACS)
1. Download `switch-port-card-pro.js` from [releases](https://github.com/partach/switch_port_card_pro_card/releases).
2. Save to `/config/www/community/switch-port-card-pro/switch-port-card-pro.js`.
3. Settings > Dashboards > Resources > + Add: URL `/local/community/switch-port-card-pro/switch-port-card-pro.js` (Type: JS Module).
4. Reload → Done.
