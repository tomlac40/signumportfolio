# signumportfolio
Integration for Home-Assistant to load and accumulate your crypto portfolio from Signum blockchain

This is a fork from https://github.com/wsdt/sensor.cryptoportfolio

## Installation

### Manual

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `signumportfolio`.
1. Download _all_ the files from the `custom_components/signumportfolio/` directory (folder) in this repository.
1. Place the files you downloaded in the new directory (folder) you created.
1. Add wanted currency to `configuration.yaml`
   ```
   sensor:   
     - platform: signumportfolio
       name: "signum 1st"
       address: "S-xxxx-xxxx-xxxx-xxxx"
    
   ```
1. Restart Home Assistant
1. Sensors created:
   ```
   sensor.signum_1st
   ```   
