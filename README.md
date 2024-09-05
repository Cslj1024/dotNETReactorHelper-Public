# dotNETReactorHelpV1.1扩展使用说明

## 1，安装dotNETReactorHelper.vsix（如果VS2022无法安装，建议使用或者直接更新到最新版的VS2022）

（1） 退出所有VS

（2）双击dotNETReactorHelper.vsix安装。

（3）把dotNET_Reactor.exe 拷贝到devenv.exe所在目录。如下图：

![dotNET_Reactor目录](https://github.com/user-attachments/assets/386b4f19-98a1-4982-9b1b-60d32c998199)


（4）安装完成后，VS 工具 菜单中会加入dotNETReactorHelper菜单项。如下图：
![Snipaste_2024-08-28_09-26-24](https://github.com/user-attachments/assets/fae14cff-24b2-4fbb-be57-99c1cf1e0b12)



（5）卸载步骤（不用本工具时候步骤）：

 a. VS -- 扩展 -- 管理扩展
![Snipaste_2024-08-28_09-27-53](https://github.com/user-attachments/assets/ff14d951-eb5b-4986-8546-76fb66975df6)



b. 在已安装中找到dotNETReactorHelper，选择卸载（点击完卸载后，关闭VS，然后会自动开始卸载）。
![Snipaste_2024-08-28_09-27-12](https://github.com/user-attachments/assets/97a76062-a46e-4f63-a342-641ffafff076)



## 2，解决方案中所有项目生成目录设置到同一目录+-（因为设置成不同生成目录时，混淆代码在对应目录混淆，拷贝到exe生成目录可能和exe引用过来的没有混淆的dll混乱），暂时只支持Debug版本生成后混淆



## 3，点击VS 工具 中菜单dotNETReactorHelper后将自动执行生成解决方案和混淆(混淆过程10秒左右)
