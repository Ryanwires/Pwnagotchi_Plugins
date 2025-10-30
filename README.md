# Pwnagotchi_Plugins

Battery_Status_2 is for the pi sugar two, works on three too but the amp readings dont show, thus the eta doesnt show. oof (i made one for the 3 that doesnt clog up your screen with the nonesense that doesnt work dont worry)


Battery_status_2
Config.toml

main.plugins.Battery_Status_2.enabled = true
main.plugins.battery_status_2.update_interval = 1
#main.plugins.battery_status_2.ma = 50               # comment out for adaptive amp readings so better eta and live amp draw or set your own power draw but like why would you


Battery_status_3     works on the pisugar 2 to but ya dont get the live amp draw so like use the Battery_status_2 silly

main.plugins.Battery_Status_3.enabled = true
