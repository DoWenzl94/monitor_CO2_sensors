# CO2 Sensor Monitoring Blueprint

This blueprint allows you to monitor CO2 sensors in your smart home environment and receive notifications when the measured CO2 levels exceed a predefined threshold.

## Instructions

### Setting Up the Blueprint

1. Open your Home Assistant `blueprints` folder.
2. Copy and paste the blueprint code provided above into a new `.yaml` file.
3. Reload the automations or restart your Home Assistant instance to apply the changes.

### Configuring the Blueprint

1. Open the Home Assistant user interface.
2. Navigate to the **Settings** > **Automations & Scenes** section.
3. Click on **Create Automation**.
4. Choose **Monitoring of CO2 Sensors** from the list of available blueprints.
5. Follow the instructions to configure the blueprint according to the input fields described.

### Configuring the Inputs

* **Monitor CO2 Sensors:** Select the CO2 sensors to monitor. Multiple sensors can be selected.
* **Threshold:** Set the threshold for the CO2 concentration (in ppm), above which a notification will be triggered.
* **Custom Condition (Optional):** Define additional requirements that must be met for the action to be executed (e.g., only send notifications during specific times of the day, or only when someone is at home). Leave empty if you want the automation to trigger every time the threshold is exceeded.

### Actions

* The blueprint is designed to execute your defined actions (e.g., a notification) when the measured CO2 level exceeds a predefined threshold.
* The actions can be completely customized to meet your individual requirements in the UI.

## Feedback and Support

For feedback, questions, or issues with this blueprint, feel free to create an issue in this repository.

> **Note:** This blueprint was created for use in Home Assistant. A working Home Assistant instance is required.
> 
> **Disclaimer:** Please be aware that this blueprint was created by a third party and is not directly supported by Nabu Casa / Home Assistant. Use it at your own risk. We recommend thoroughly testing the functionality before use.



<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FDoWenzl94%2Fmonitor_CO2_sensors%2Fblob%2Fmain%2Fmonitor_CO2_sensors.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>
