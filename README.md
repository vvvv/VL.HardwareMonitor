# VL.HardwareMonitor

A set of nodes interfacing LibreHardwareMonitor, allowing you to retrieve various metrics from your computer hardware (GPU load/temperature, RAM load, etc).

Based on the [LibreHardwareMonitorLibCore](https://www.nuget.org/packages/LibreHardwareMonitorLibCore/) nuget which in turn is a fork of the original [OpenHardwareMonitor](https://openhardwaremonitor.org/).

## Using the library

In order to use this library with VL, you have to install the nuget that is available via nuget.org. For information on how to use nugets with VL, see [Managing Nugets](https://thegraybook.vvvv.org/reference/libraries/dependencies.html#manage-nugets) in the VL documentation. As described there, go to the command line and then type :

```
nuget install VL.HardwareMonitor -pre
```

Once the VL.HardwareMonitor nuget is installed and referenced in your VL document, you'll see the `HardwareMonitor` and `GetHardwareInfo` nodes under the `System` category in the nodebrowser.

An overview help patch is available via the Help Browser!

## Notes

- Certain sensor values require the program to run with admin rights!
