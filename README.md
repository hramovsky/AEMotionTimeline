# AE Motion Timeline

AE Motion Timeline is an After Effects template for UI motion designers that can help to present UI animations.

# Quick note

It's not an automated tool, so you will use your animation as a reference and set up necessary tracks manually.

# Tutorial

1. Place your Reference to MotionTimeline comp. 

<img src="/images/Scr-05.png" alt="Screen Animation Reference" title="Screen Animation Reference">

2. Add Time Remapping to the Reference and link it to the PositionSlider(ms) on Marker layer.

```
thisComp.layer("Marker").effect("curTime")(1) / 1000
```

<img src="/images/Scr-04.png" alt="Link Time Remapping" title="Link Time Remapping">




<img src="/images/Scr-01.png" alt="Selected Layer" title="Selected Layer">

<img src="/images/Scr-02.png" alt="Edit Curve Preview" title="Edit Curve Preview">

<img src="/images/Scr-03.png" alt="Link Text" title="Link Text">






<img src="/images/Scr-06.png" alt="Settings" title="Settings">

