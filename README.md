# AE Motion Timeline

AE Motion Timeline is an After Effects template that can help UI motion designers explain or present their UI animations.


# Quick note

It's not automated tool, so you will use your animation as a reference and set up tracks manually.

# Tutorial

1. Place your Reference to MotionTimeline comp. 

<img src="/images/Scr-05.png" alt="Screen Animation Reference" title="Screen Animation Reference">

2. Add Time Remapping to the Reference and link it to the PositionSlider(ms) on Marker layer.

```
thisComp.layer("Marker").effect("curTime")(1) / 1000
```

<img src="/images/Scr-04.png" alt="Link Time Remapping" title="Link Time Remapping">

3. Set parameters.

<img src="/images/Set-parameters.png" alt="Set-parameters" title="Set-parameters">

4. Curve preview image. You can put values in the curve preview name to generate preview.

<img src="/images/Curve-name.png" alt="Edit Curve Preview" title="Edit Curve Preview">

5. You can duplicate tracks using ctrl+D and move it along Y axis. You will need to duplicate both of the layers: the group of the text info and Curve preview. The Curve preview should be linked to related texts comp.

6. Settings

<img src="/images/Scr-06.png" alt="Settings" title="Settings">

