# Day 5 - CMOS power supply and device variation robustness evaluation

CMOS invertor robustness - power supply scaling

Scripting in .spice

<br>![](assets/2025-10-18-14-18-16-image.png)<br>

gain for plot with vdd=2.5V = 7.38

<br>![](assets/2025-10-18-14-24-57-image.png)<br>

energy = 0.5cv^2

where v = vdd

<br>![](assets/2025-10-18-14-29-18-image.png)<br>

performance impact - transition time (rise and fall time) increases when vdd is reduced

<br>![](assets/2025-10-18-14-30-10-image.png)<br>

<br>![](assets/2025-10-18-14-30-20-image.png)<br>

# Lab - Supply Variation

<br>![](assets/2025-10-18-15-25-35-image.png)<br>

out vs in on left | gain on right:

<br>![](assets/2025-10-18-15-30-44-image.png)<br>

# Device Variation - Sources of variation

1. Etching process

<br>![](assets/2025-10-18-15-05-03-image.png)<br>

<br>![](assets/2025-10-18-15-07-21-image.png)<br>

<br>![](assets/2025-10-18-15-09-21-image.png)<br>

2. oxide thickness

<br>![](assets/2025-10-18-15-12-17-image.png)<br>

## SPICE simulation for device variations

<br>![](assets/2025-10-18-15-15-19-image.png)<br>

dc1 - strong pmos, weak nmos| dc5- weak pmos, strong nmos

<br>![](assets/2025-10-18-15-19-56-image.png)<br>

<br>![](assets/2025-10-18-15-21-02-image.png)<br>

# Lab - Device Variation

<br>![](assets/2025-10-18-15-36-26-image.png)<br>

switching threshold - 0.98. the variation in switching threshold is minimal. CMOS invertor is robust.
