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

3. Set up your tracks according to your reference.

<img src="/images/Scr-01.png" alt="Selected Track" title="Selected Track">

4. Edit Curve preview. Set timeline marker to 2:00. Select curveAnimation slider in Edit Value Graph mode. You can also use plugin like Flow to set curve.

<img src="/images/Scr-02.png" alt="Edit Curve Preview" title="Edit Curve Preview">

5. You can duplicate tracks using ctrl+D and move it along Y axis. Also you can duplicate description text, after duplicating text set LinkLayer to related track.

<img src="/images/Scr-03.png" alt="Link Text" title="Link Text">

6. Settings

<img src="/images/Scr-06.png" alt="Settings" title="Settings">

