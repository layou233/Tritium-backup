# Tritium-backup
A backup source for Minecraft PVP-focused client made by LEF-ganga.  
  
## We are happy to make Tritium available again!  
我们很高兴让 Tritium 再次可用！  
  
Because the other LEF-ganga (aka ImFlowow) has deleted the resource repo originally deployed on Gitee, some code files cannot be downloaded. (such as' me. Imflow: authlib: 1.2 ')  
由于彼岸花已经把原先部署在 Gitee 上的资源仓库删除，导致部分依赖文件无法下载。（如`me.imflowow:authlib:1.2`）  
  
We have retrieved this part of the file from the old computer and re uploaded it to this GitHub repo.  
我们已经从旧电脑中找回了这部分文件，并且重新上传到本GitHub仓库。  
  
In ` client.json`, we will use the GitHub mirror download service provided by jsDelivr to help users complete dependency, so as to avoid the problem of user download failure in Chinese mainland.  
在 `client.json` 中，我们将使用 jsDelivr 提供的 GitHub 镜像下载服务来帮助用户补全依赖，以此避免中国大陆用户下载失败的问题。
  
At the same time, we modify `log4j2.xml` to help users avoid the Remote Code Execution Vulnerability of log4j2! (CVE-2021-44228/CVE-2021-45046)  
So your games are secured if you use our version of Tritium!  
同时，我们通过修改 Tritium 主体中的 `log4j2.xml` 文件，帮助用户避免了 log4j2 的远程代码执行漏洞！（CVE-2021-44228/CVE-2021-45046）  
所以如果你使用我们提供的 Tritium ，那么你的游戏是安全的！  

### Log4j2 Vulnerability Solution Reference
[Mojang's announcement](https://www.minecraft.net/en-us/article/important-message--security-vulnerability-java-edition)  
[Fixed XML file (Mojang)](https://launcher.mojang.com/v1/objects/4bb89a97a66f350bc9f73b3ca8509632682aea2e/log4j2_17-111.xml)
