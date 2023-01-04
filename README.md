# esphome_configs

powermon-sump.yaml
 - Sonoff S31 flashed with ESPHome to track power use of the Sump Pump and try to track how many times a day it runs (resetting at midnight). When not running, the pump draws 0 current, so when the Sonoff detects current draw it changes state to running and I count the times it switches to running state.

powermon-serverrack.yaml
 - Sonoff S31 flashed with ESPHome to track power use of my server rack which hosts all my networking gear and Unraid Server.
