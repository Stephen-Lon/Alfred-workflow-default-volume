# Alfred-workflow-default-volume
An Alfred workflow to set the output volume on your Mac to your desired default

# Note

Version 2.0 of this workflow uses Alfred 5.5's Number Slider in the workflow configuration. If you are using an older version of Alfred please use [version 1.1](https://github.com/Stephen-Lon/Alfred-workflow-default-volume/releases/tag/v1.1) of this workflow.

# Usage

Type `defvol` (or other keyword if you have changed the default) and <kbd>⏎</kbd> to reset the sound output of your Mac to the default. You can change the default sound level here in the User Configuration to anything between 0 (which means muted) to 100 (the meximum).  

Note also that the workflow can use an Inbound Configuration (called `Set default volume`): so you can call *this* workflow by using Alfred's `Call External Trigger` direct from another workflow that changes the volume.
