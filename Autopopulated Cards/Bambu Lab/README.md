# Bambu Lab Dashboard Card
This yaml code will look into the integration entities of the Bambu Lab and grab all the printers, AMS and External Spool devices.
Will display a picture entity for each device and show infos accordingly.
No need to enter entity - device names.

### Power switch also supported. 
If you have a switch that controls the power of a printer, give it the label name '3d-printer' and another label with the config entry of the printer which is shown in the Integration Bambu Lab (the serial number of the printer).

![X1C + AMS](https://github.com/user-attachments/assets/a0fb80e2-7f34-4791-8991-6da3b9ca3372)

## Instructions
Visit: [@Wolfwithsword page](https://wolfwithsword.com/bambulab-home-assistant-dashboard/) (it's all his work, I just made the auto-populated template)

1) Download the necessary cards & integrations from HACS (don't worry, they are many but you will definetely need them again in the future...):
Please follow the instructions for each one, as some require additional steps to install (FontAwesome)

### Cards:
* [card-mod](https://github.com/thomasloven/lovelace-card-mod)
* [layout-card](https://github.com/thomasloven/lovelace-layout-card)
* [hui-element](https://github.com/thomasloven/lovelace-hui-element)
* [button-card](https://github.com/custom-cards/button-card)
* [mushroom](https://github.com/piitaya/lovelace-mushroom)
* [custom-ui](https://github.com/Mariusthvdb/custom-ui)
* [auto-entities](https://github.com/thomasloven/lovelace-auto-entities)

### Integrations:
* [FontAwesome](https://github.com/thomasloven/hass-fontawesome) (after installing via HACS, you need to add it again in Devices & Services)
* [Custom Templates](https://github.com/PiotrMachowski/Home-Assistant-custom-components-Custom-Templates) (add: `
custom_templates:` in your configuration.yaml, needed for the translations)
 
2) Download & extract the file [media](https://nightly.link/WolfwithSword/Bambu-HomeAssistant-Flows/workflows/media_archive/main/bambu-ha-media-files.zip) to your /config

3) Restart HA

4) Insert the yaml code in a Dashboard Card
