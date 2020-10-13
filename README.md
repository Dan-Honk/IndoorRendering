# IndoorRendering
模拟室内环境的渲染的案例，自己通过unity引擎一些渲染设置，烘焙一些室内场景不同的案例，记录自己熟悉灯光设置以及烘焙的过程.
直接使用unity打开即可，unity版本：2018.4.24

Lightmapping  setting
Ambient occlusion 环境光散射，勾选上之后可以突出阴影细节

Light 灯光源相关设置
Indirect multiplier 间接系数，可以控制反射次数
shadow type 控制是否投射阴影，对应gameObject是否需要加入阴影效果可以通过设置自身meshRenderer中的 Cast Shadows系数
