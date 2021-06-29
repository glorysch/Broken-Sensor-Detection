# Broken-Sensor-Detection

This analysis was done using R for the Time Series course in the University of Chicago Master of Analytics program.<br/>

The goal of this analysis was to detect when a water pump  would fail before failure happens based on it's sensor readings. I created a solution that would use the correlation among every sensor reading, in sets of 2,and labeled outlying correlations as "Pre-Broken". Although the accuracy was difficult to measure the visualizations may show some association that the correlation among pump sensor readings could help predict when the pump will break.

In this analysis I used various R packages such as:<br/>
-tseries<br/>
-forecast<br/>
-xts<br/>
-wavelets<br/>
-gtools<br/>
-roll<br/>
-zoo<br/>
-TTR<br/>
-ggplot2<br/>
-TSstudio<br/>
-stringr<br/>
