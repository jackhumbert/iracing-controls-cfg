# iRacing controls.cfg

This is a [010 Editor](https://www.sweetscape.com/010editor/) template for iRacing's `controls.cfg` file, located in the `iRacing` folder in your user documents.

To update a control's device, you can edit the `guid` property for each control listed in the template results. The `joyCalib.yaml` (located in the same folder) file lists the GUIDs (`InstanceGUID` in this file) that iRacing sees.

You can use `replace_guid.1sc` (run on `controls.cfg` with `controls.cfg.bt` in the same directory as `replace_guid.1sc`) to replace all instances of a GUID in the file with a new one.