# Visual-studio-ReleaseVersion-debug  
在VisualStudio中正常调试一个Release版本的程序会有无法逐行调试的情况。  
完整的视频解决方案链接：  
  
正常情况下调试一个Release版本的程序会省略很多步骤，例如运算的合并：
![](https://github.com/Neko-yc/Visual-studio-ReleaseVersion-debug/blob/main/image/%E7%9B%B4%E6%8E%A5%E8%B7%B3%E8%BF%87.png)  
  
需要修改一下VisualStudio中的设置，使其禁用优化的调试，改为逐行调试：  
![](https://github.com/Neko-yc/Visual-studio-ReleaseVersion-debug/blob/main/image/%E4%BC%98%E5%8C%96%E8%AE%BE%E7%BD%AE.png)  
  
最后可以看到修改后的程序变为了逐行调试：  
![](https://github.com/Neko-yc/Visual-studio-ReleaseVersion-debug/blob/main/image/%E5%8F%AF%E9%80%90%E6%AD%A5%E8%B0%83%E8%AF%95.png)  
