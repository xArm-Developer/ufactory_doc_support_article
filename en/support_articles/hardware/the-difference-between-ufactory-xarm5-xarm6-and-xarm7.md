

# The difference between UFACTORY xArm5, xArm6 and xArm7

The purpose of this article is to describe the differences between UFACTORY
  xArm5, xArm6 and xArm7.
### 1. Specifications

<table data-header-hidden data-full-width="true"><thead><tr><th width="237"></th><th align="center">SPECIFICATION</th><th align="center"></th><th align="center"></th></tr></thead><tbody><tr><td></td><td>xArm 5 Lite</td><td>xArm 6</td><td>xArm 7</td></tr><tr><td>Payload(kg)</Payload></mark></td><td>3kg</td><td>5kg</td><td>3.5kg</td></tr><tr><td>Reach(mm)</td><td>700mm</td><td>700mm</td><td>700mm</td></tr><tr><td>Degrees of Freedom</td><td>5</td><td>6</td><td>7</td></tr><tr><td>Maximum Speed(m/s)</td><td>1m/s</td><td>1m/s</td><td>1m/s</td></tr><tr><td>Weight(kg, body only)</td>11.2kg</td><td>12.2kg</td><td>13.7kg</td></tr></tbody></table>

<table data-header-hidden data-full-width="true"><thead><tr><th width="181"></th><th width="185" align="center"></th><th width="194" align="center"></th><th align="center"></th></tr></thead><tbody><tr><td></td><td>xArm 5 Lite</td><td>xArm 6</td><td>xArm 7</td></tr><tr><td>Maximum Speed</td><td>180°/s</td><td>180°/s</td><td>180°/s</td></tr><tr><td>Joint1</td><td>±360°</td><td>±360°</td><td>±360°</td></tr><tr><td>Joint2</td><td>-118° ~ 120°</td><td>-118°～120°</td><td>-118°～120°</td></tr><tr><td>Joint3</td><td>-225°~11°</td><td>-225°~11°</td><td>±360°</td></tr><tr><td>Joint4</td><td>-97°~180°</td><td>±360°</td><td>-11°～225°</td></tr><tr><td>Joint5</td><td>±360°</td><td>-97°~180°</td><td>±360°</td></tr><tr><td>Joint6</td><td></td><td>±360°</td><td>-97°~180°</td></tr><tr><td>Joint7</td><td></td><td></td><td>±360°</td></tr></tbody></table>

### 2. Motion Characteristics

* Cartesian control

xArm 5 Lite: Due to the robot configuration,**the actual flexible degrees**of freedom of linear and circular motions **in Cartesian space is 4**, which is \[x, y, z, yaw], similar to a SCARA manipulator with four degrees of freedom. Before initiating Cartesian control movement, it is necessary to ensure that the end flange surface of xArm5 and the base are completely parallel. If mounted on a horizontal plane, the roll and pitch should be \[± 180 degrees, 0 degrees], otherwise the trajectory is likely to have no solution.

[How to align the tool end flange of xArm 5 Lite?](../faq/how-to-align-the-tool-end-flange-of-xarm-5-lite.md)
