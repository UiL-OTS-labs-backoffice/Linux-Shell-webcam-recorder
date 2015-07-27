# Linux-Shell-webcam-recorder
A shell script to easily capture webcam video on the lab PC's of the UiL OTS Labs

There are two flags available with which the script can be called:

-r When the script is called with the -r flag, an extra window will appear before they select the save location, asking them which resolution they want to record in. They can choose SD quality (640 * 480px, 4:3), HQ (800 * 600px, 4:3, which is also the default option), HD (1280*720, 16:9 widescreen) or FHD (1920 * 1080, 16:9 widescreen). The preview window will have the same proportions as the selected resolution

-p When the script is called with the -p flag, an extra window pops up, asking the user if they want to show a live preview during recording as well as before starting recording. This can be useful if they want to moniter their subjects live. It also shows a warning that this will use a lot of CPU processing power and might therefor interfere with the experiment. That is why, by default, no live preview is shown during recording. 
