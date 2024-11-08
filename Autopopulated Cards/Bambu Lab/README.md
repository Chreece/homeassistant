[Bambu Lab Lovelace Card]
This yaml code will look into the integration entities of the Bambu Lab and grab all the printers, AMS and External Spool devices.
Will display a picture entity for each device and show infos accordingly.
No need to enter entity - device names.

Power switch also supported. 
If you have a switch that controls the power of a printer, give the label name '3d-printer' and the config entry of the printer which is shown in the Integration Bambu Lab (the serial number of the printer).

[Instructions]
Visit: https://wolfwithsword.com/bambulab-home-assistant-dashboard/ (it's all his work, I just made the autopopulate template)
Download the necessary cards - integrations:
  Please follow the instructions for each one, as some require additional steps to install (FontAwesome)

  card-mod
  lovelace-layout-card
  hui-element
  button-card
  mushroom
  config-template-card
  FontAwesome (in HACS integrations, not frontend) (after installing via HACS, you need to add it again in Devices & Services)
  custom-ui
  tabbed-card (only if using my NodeRed version)
Restart HA
Insert the yaml code in Lovelace
Ready!