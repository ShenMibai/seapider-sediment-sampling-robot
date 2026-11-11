# Seapider Sediment Sampling Robot

Seapider is a marine robotics course project designed to collect nearshore sediment samples in Macao for heavy-metal monitoring. The current SOLIDWORKS model includes four articulated legs, four independently driven sampling grabs, a stereo camera on a two-axis gimbal, and a recessed buoyancy plate with a central lifting opening. The lifting revision adds a central lifting eye, a separate communications tether route, and cable protection. The new assembly includes an 8.230 L recessed float, rectangular power and electronics enclosures, and two clamps with crossbar base plates per enclosure.

## Repository layout

| Folder | Contents |
| --- | --- |
| [All](All/) | Complete robot assembly and its referenced CAD files, kept together for opening the full model. |
| [Body](Body/) | Body and sampling components, including the frame, recessed buoyancy plate, central lifting eye, lifting rope protection, and communications tether hardware. |
| [camera](camera/) | Camera housing and dome, stereo gimbal, and related CAD parts. |
| [Grab](Grab/) | Standalone sampling grab models and their referenced parts. Use the current revision in [Grab/DualBrace](Grab/DualBrace/). |

## Open the CAD models

Use **SOLIDWORKS 2023** and keep the referenced parts and subassemblies with their assembly files.

1. [Complete robot assembly](All/new_Seapider_Lifting_Concept.SLDASM)
2. [Stereo camera gimbal](camera/Seapider_Stereo_Gimbal.SLDASM)
3. [Current standalone grab assembly](Grab/DualBrace/Jaw_RaisedLiftEnds_DualBrace.SLDASM)

The robot assembly uses **+X** forward toward the camera, **+Y** upward, and **Z** across the robot from side to side.

## Grab revisions

- **Current** — [Grab/DualBrace](Grab/DualBrace/) includes two green side braces that connect the jaw pivot bracket to the opening actuator housing.
- The previous grab revision lacked the two side braces and was removed from the current branch.
