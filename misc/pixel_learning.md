---
layout: default
permalink: /learning_pixel
---

# 我的像素画学习之路

### 2023.8.19

> 线稿非常重要

> Q: 如何消除像素线条的锯齿，让其看上去更平滑 \
  A: **不要使用更大的像素来包围一行像素** \
  <img src="./assets/images/pixel/line_draft.png" alt="line-draft" style="width: 40%; height: auto;">

### 2023.8.22

> 抗锯齿（AA，anti-aliased）会使得边缘变平滑，但是也会使得画面变模糊，不是所有情况都适合使用抗锯齿

> 45°线抗锯齿：凸型曲线，中间为浅色，两端为深色；凹形曲线，中间为深色，两端为浅色 \
  <img src="./assets/images/pixel/45deg.png" alt="45-degree" style="width: 40%; height: auto;">

> 尽量避免色带，即两行像素长度一样

> 尽量避免使用纯黑色，灰色是中性色，可以利用灰色调

> 给阴影也染上颜色，不是单纯调整亮度来制作阴影，使用**色调变换**

> 每个像素都很重要，一个像素就可能影响别人对它的理解

> 绘制手部时，注重食指和拇指的表现

> 利用抖动来在有限的颜色的情况下制作渐变，但是需要在很大的空间中才能起效 \
  <img src="./assets/images/pixel/dithering.png" alt="dithering" style="width: 40%; height: auto;">

### 2023.8.23
> 练手：原图 vs 临摹 \
  <img src="./assets/images/pixel/knight_raw.gif" alt="knight_raw" style="width: 20%; height: auto;">
  <img src="./assets/images/pixel/knight_modify.png" alt="knight_modify" style="width: 20%; height: auto;">

> 收获：
  - 不要在一开始就确定所有要使用的颜色，确定基础色调，后期用到再在基础色之上修改
  - 如果灯光面对着角色，应该是前面的像素是浅色，后面的像素是深色，我在临摹时注意到原图的色带问题，修改成我觉得合适的版本



---
[back](/)