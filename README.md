# UroVoidAnalysisApp
Matlab application for UroVoid data analysis<br>
Requires MatLab Report Generator<br>
<br>
Create data reports from raw urovoid data<br>
**Version History:**<br>
5.1 - 10/15/2025 fixed void summary calculations in new light/dark cycle detection code<br>
5.0 - 10/9/2025 replaced light/dark cycle detection code with a new function (generateLightDarkCycles) to better detect light and dark cycles, regardless of when an experiment starts and ends.<br>
4.1 - 10/2/2025 added code to remove Inf values froms scale trace due to extreme noise on scale (removing weigh pan, e.g.)<br>
4.0 - 8/5/24 replaced xlswrite with writecell<br>
3.0 - fixed issue when experiment ended in a dark cycle and the voids in last dark cycle couldn't be counted<br>
