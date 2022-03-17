# OSCAR
**O**pen-**s**ource **C**ommunity **A**griculture **R**obot
## Youtube video: [mobile robot planting seedlings from a greenhouse](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

<img src="https://user-images.githubusercontent.com/83112082/158695710-409a7582-68b4-4f60-8c9a-1ad10f0847a4.png" width="100%" height="100%">
<img src="https://user-images.githubusercontent.com/83112082/158697429-a6c9f0c1-c2a6-409a-b8f7-cdcd9ff8d750.png" width="70%" height="70%">

# Table of Contents
[Design](#Design) \
[Math](#Math) \
[Electronics](#Electronics) \
[Materials](#Materials) \
<a name="Design"/>
<a name="Math"/>
<a name="Electronics"/>
<a name="Materials"/>

## Design
Linkage Design Tool: [link](https://www.marginallyclever.com/other/samples/fk-ik-test.html)

CAD files: [link](https://cad.onshape.com/)

3D print files: [link](https://www.eiger.io/)

Soft Gripper:\


## Math
![ik_fk_planar_ik](https://user-images.githubusercontent.com/83112082/158498262-d42ebefd-7650-441f-95d4-f40f9f91df03.gif)\
https://gist.github.com/uupaa/f77d2bcf4dc7a294d109 \
https://stackoverflow.com/questions/34341808/is-there-a-way-to-add-a-gif-to-a-markdown-file \

Forward Kinematics:
Each set of joint angles maps to a unique end effector position.\
The nonlinear mapping is calculated through the following equations:\
<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">

Inverse Kinematics:

Control Systems:


## Electronics
Wiring diagram for the manipulator and mobile robot platform.\
![wiring](https://user-images.githubusercontent.com/83112082/158497874-c0ef5861-e687-4c1e-a27b-e2a09aff9d5e.jpg)


## Materials
The table below details all necessary parts to build your own farm robot for personal use. Please send me any suggestions that you think would improve the design or lower the cost. \

Prototype Version
| Item                | Quantity       | Cost (each)          |
| ------------------- |     :---:      |          ---:        |
| [Ball joint](https://www.tqrcracing.com/shop/product_list.asp?s_cate_id=1104)      | 16     | $1.75    | 
| [Shaft adapter](https://www.pololu.com/category/137/pololu-universal-mounting-hubs)     | 4       | $$     |
| [Stepper Motor](https://www.digikey.com/en/products/detail/pololu-corporation/1208/10449951)     | 4       | $     |
| [Stepper Driver](https://www.pololu.com/category/212/tic-stepper-motor-controllers)     | 4       | $     |
| [Springs](https://www.mcmaster.com/springs/spring-type~extension/system-of-measurement~metric/)    | 16       | $      |
| [Carbon Rod]()     | 3.5m       | $$      |      |
| [Limit Switch]()     | 8?       | digikey      |
| [3D prints]()     | lots       | Markforged      |

Production Version
| Item                | Quantity       | Cost (each)          |
| ------------------- |     :---:      |          ---:        |
| [Stepper Motor](https://www.digikey.com/en/products/detail/pololu-corporation/1208/10449951)     | 4       | $     |
| [Springs](https://www.mcmaster.com/springs/spring-type~extension/system-of-measurement~metric/)    | 16       | $      |
| [Carbon Rod]()     | 3.5m       | $$      |      |
| [Gears - small](https://www.mcmaster.com/3598N276/)    | 4 - left       | $19.74 |
| [Gears - large](https://www.mcmaster.com/3598N299/)    | 4 - right      | $29.81 |
| [Tap set screw]()     | 8       | machine shop      |
| [Optical Encoder]()     | 4       | digikey      |
| [Limit Switch]()     | 8?       | digikey      |
| [3D prints]()     | lots       | Markforged      |

## Assembly
The following instructions detail the logical assembly to build your robot.
1. These
2. are
3. the
4. necessary
5. steps


## Installation
Use the following commands to install the software on your Jetson Nano.
```
$ pip install oscar
```


## Planting Materials
The following materials are recommended planting supplies that fit with the robots specifications. \
http://www.jiffypot.com/en/products/jiffymultigrow.html
