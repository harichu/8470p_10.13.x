# 8470p_10.13.x
clover folder with needed fixes for the elitebook 8470p (i5 model) to run high sierra

Simply copy over this clover folder to your install stick ESD / main drive ESD

careful with the SSDT-FAN-QUIET.am in ACPI/patched . only tested with i5 and this specific model

If you use another CPU you want to remove the SSDT.aml and generate your own. In that case you might need NullCPUPowerManagement to boot


Still to fix:

Bluetooth not working consistently

Audio only works with VoodooHDA since AppleALC breaks with LVDS Framebufferpatch for some weird reason

maybe find a way to get tracking point stick thingy to work correctly


VOoDOOHDA seems to kill BT... weird stuff
