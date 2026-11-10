# Seapider Sediment Sampling Robot

Seapider is a marine robotics course project designed to collect nearshore sediment samples in Macao for heavy-metal monitoring. The current SOLIDWORKS model includes four articulated legs, four independently driven sampling grabs, a stereo camera on a two-axis gimbal, and a recessed buoyancy plate with a central cable opening.

## Repository layout

| Folder | Contents |
| --- | --- |
| [All](All/) | Complete robot assembly and its referenced CAD files. Start here to open the whole robot. |
| [Body](Body/) | Body and sampling components, including the frame, buoyancy plate, and grab hardware. Camera and leg files are grouped separately from this collection. |
| [camera](camera/) | Camera housing and dome, stereo gimbal, and related CAD parts. |
| [Grab](Grab/) | Standalone sampling grab models and their referenced parts. Use the current revision in [Grab/DualBrace](Grab/DualBrace/). |

## Open the CAD models

Use **SOLIDWORKS 2023** and keep the referenced parts and subassemblies with their assembly files.

1. [Complete robot assembly](All/Seapider_RotatedCorners_NoBottom.SLDASM)
2. [Stereo camera gimbal](camera/Seapider_Stereo_Gimbal.SLDASM)
3. [Current standalone grab assembly](Grab/DualBrace/Jaw_RaisedLiftEnds_DualBrace.SLDASM)

The robot assembly uses **+X** forward toward the camera, **+Y** upward, and **Z** across the robot from side to side.

## Grab revisions

- **Current** — [Grab/DualBrace](Grab/DualBrace/) includes two green side braces that connect the jaw pivot bracket to the opening actuator housing.
- The previous grab revision lacked the two side braces and was removed from the current branch.
