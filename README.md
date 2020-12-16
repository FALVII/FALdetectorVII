# FALdectectorVII

## 目标:

进行图片真假判断与扭曲预测恢复

## 目录结构：<br>
        .
        ├── doc
        │   ├── 1-论证启动
        │   │   ├── 启动过程
        │   │   │   ├── 干系人登记册(高恒达).pdf
        │   │   │   ├── 核心团队说明(高恒达).pdf
        │   │   │   ├── 里程碑进度计划(高恒达).pdf
        │   │   │   └── 项目章程(高恒达).pdf
        │   │   └── 项目论证
        │   │       ├── 1.问题描述（张世禹）.pdf
        │   │       ├── 2.产品愿景和商业机会（张世禹，李少航）.pdf
        │   │       ├── 3.用户分析（张世禹，李少航）.pdf
        │   │       ├── 4.技术分析（张世禹，高恒达）.pdf
        │   │       ├── 5.资源需求估计（李少航）.pdf
        │   │       ├── 6.风险分析（张世禹）.pdf
        │   │       ├── 7.产品构思（张世禹，李少航）.pdf
        │   │       └── 界面原型
        │   │           ├── 1_主页.png
        │   │           ├── 2_注册_2.png
        │   │           ├── 3_账户信息_3.png
        │   │           ├── 4_主功能_4.png
        │   │           ├── 5_历史记录_5.png
        │   │           ├── 6_主功能延伸_6.png
        │   │           └── 7_复原信息_7.png
        │   └── 2-项目规划
        │       ├── 高恒达
        │       │   ├── FAL排列工作包顺序-高恒达.pdf
        │       │   └── FAL.mpp
        │       ├── 李少航
        │       │   ├── FAL排列工作包顺序-李少航.pdf
        │       │   └── FAL.mpp
        │       └── 张世禹
        │           ├── FAL排列工作包顺序-张世禹.pdf
        │           └── FAL.mpp
        ├── proj
        │   └── WeChat program
        │       ├── app.js
        │       ├── app.json
        │       ├── app.wxss
        │       ├── icon
        │       │   ├── 11.png
        │       │   ├── friend.png
        │       │   ├── home.png
        │       │   └── index.png
        │       ├── pages
        │       │   ├── camera
        │       │   │   ├── camera.js
        │       │   │   ├── camera.json
        │       │   │   ├── camera.wxml
        │       │   │   └── camera.wxss
        │       │   ├── canvas
        │       │   │   ├── canvas.js
        │       │   │   ├── canvas.json
        │       │   │   ├── canvas.wxml
        │       │   │   └── canvas.wxss
        │       │   ├── content
        │       │   │   ├── content.js
        │       │   │   ├── content.json
        │       │   │   ├── content.wxml
        │       │   │   └── content.wxss
        │       │   ├── editor
        │       │   │   ├── editor.js
        │       │   │   ├── editor.json
        │       │   │   ├── editor.wxml
        │       │   │   └── editor.wxss
        │       │   ├── frontcamera
        │       │   │   ├── frontcamera.js
        │       │   │   ├── frontcamera.json
        │       │   │   ├── frontcamera.wxml
        │       │   │   └── frontcamera.wxss
        │       │   ├── home
        │       │   │   ├── home.js
        │       │   │   ├── home.json
        │       │   │   ├── home.wxml
        │       │   │   └── home.wxss
        │       │   └── index
        │       │       ├── index.js
        │       │       ├── index.json
        │       │       ├── index.wxml
        │       │       └── index.wxss
        │       ├── project.config.json
        │       ├── sitemap.json
        │       └── utils
        │           └── util.js
        └── README.md

        21 directories, 63 files

## 研究记录：

+ [PSNR图像评价指标与ML的二阶混淆矩阵(gao)](https://blog.csdn.net/m0_43414114/article/details/110350577)
+ [git版本控制与协作模式(gao)](https://blog.csdn.net/m0_43414114/article/details/109721686)
+ [新人Flask框架基础学习(gao)](https://blog.csdn.net/m0_43414114/article/details/110348431)
+ [Detecting Photoshopped Faces by Scripting Photoshop论文翻译_V1](https://blog.csdn.net/m0_43414114/article/details/109777265)
+ [tools注释（张世禹）](https://blog.csdn.net/therain123/article/details/110003262)
+ [DRN 与 GAN相关知识(gao)](https://blog.csdn.net/m0_43414114/article/details/109952842)
+ [eval注释（张世禹）](https://blog.csdn.net/therain123/article/details/109957073)
+ [ubuntu下的git命令（li）](https://blog.csdn.net/Only_Big/article/details/109956624)
+ [读eval.py代码总结（li）](https://blog.csdn.net/Only_Big/article/details/109800580)
+ [drn&drn_seg代码(gao)](https://blog.csdn.net/m0_43414114/article/details/109984401)
+ [local_detector.py注释（张世禹）](https://blog.csdn.net/therain123/article/details/110122039)
+ [global_classifier.py注释(张世禹)](https://blog.csdn.net/therain123/article/details/110122136)
+ [flask(张世禹)](https://blog.csdn.net/therain123/article/details/110350764)
+ [卷积残差神经网络(张世禹)](https://blog.csdn.net/therain123/article/details/109957176)
+ [读参考文献13、17、18总结(li)](https://blog.csdn.net/Only_Big/article/details/110663043)
+ [adam算法介绍和总结(li)](https://blog.csdn.net/Only_Big/article/details/110660813)
+ [读Xception: Deep Learning with Depthwise Separable Convolutions论文总结(li)](https://blog.csdn.net/Only_Big/article/details/110657600)
+ [inception网络模型(li)](https://blog.csdn.net/Only_Big/article/details/110656131)
+ [读参考文献8-11总结(li)](https://blog.csdn.net/Only_Big/article/details/110654994)
+ [FaceForensics和FaceForensics++【参考文献30和31】(li)](https://blog.csdn.net/Only_Big/article/details/110823971)
+ [用于检测数字化和打印扫描变形人脸图像的可转换深层CNN特征【参考文献29】(li)](https://blog.csdn.net/Only_Big/article/details/110823677)
+ [像素递归神经网络简要概况【参考文献27】(li)](https://blog.csdn.net/Only_Big/article/details/110823601)
+ [拷贝移动图像伪造检测技术综述【参考文献22】(li)](https://blog.csdn.net/Only_Big/article/details/110823459)
+ [读参考文献32总结(li)](https://blog.csdn.net/Only_Big/article/details/110823365)
+ [读参考文献40总结Colorful Image Colorization(li)](https://blog.csdn.net/Only_Big/article/details/110823322)
+ [读参考文献39论文总结 Dilated residual networks(li)](https://blog.csdn.net/Only_Big/article/details/110823241)
+ [参考文献33 《video-tovideo Synthesis》论文总结(转载)](https://blog.csdn.net/Only_Big/article/details/110821038)




