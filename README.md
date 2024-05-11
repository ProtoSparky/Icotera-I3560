# Icotera-I3560
My trial at reverse engineering and getting access to the Icotera I3560

## Backstory and goal with this project:
I got this accesspoint form my "housing estate" as part of a free network upgrade to multi gigabit speeds.
The problem i and many people noticed with these accesspoints is that you have absolutealy no access to modify anything whatsoever. There is no WebUI or app that would allow me to modify the SSID or other settings on this network gear, and that's a shame as this is a seriously powerful accesspoint which i cant properly utilize. 
The WebUI os locked down probably on accident when they were flashing custom SSIDs and passwords, as the HTTP service is not even running/exposed on the ethernet/wlan, so there's no way to modify anything on it. 
And the bigger problem ive noticed is that the accesspoint does not "support" any IP subnets that are not 192.168.1.XXX, which means that no devices can even connect to the AP on networks with other subnets. 
So let's get to the goals for this project
* Get console access via UART 
* Figure out how to modify the configs
* Get the webui open and running
* Maybe find a way to get OpenWRT running on this thing

### Current progress

| Stage | Progress |
|----|-----|
| [Get Uart access](./get_serial_access/README.md) | 50% |
|Modify configs|0%|



