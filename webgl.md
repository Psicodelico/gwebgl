什么是WEBGL描述不准确啊。 从字面意思就知道它是一个web 绘图库，这个绘图库把OpenGL ES 2.0 和Javascript 做了绑定，这样的Web开发人员就可以利用显卡来渲染3D场景和模型并展示到浏览器中

webgl四大场景：  
相机、几何体、场景、渲染器

opengl是一套显卡渲染标准
opengl es是简化版标准
浏览器中实现的是opengl es

1. 场景  
    THREE.Scene = function()  
    一个页面可以放多个场景  
2. 相机  
    Camera  
    PerspectiveCamera  
    正投影相机：并非近大远小  
    视角  
    纵横比  
    近平面  
    远平面  
3. 渲染器
    计算过程被称为渲染  
    WebGLRenderer
4. 物体
    网格模型

