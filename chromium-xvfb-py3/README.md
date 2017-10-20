## 这是一个基于Debian8制作Python3.6的Dockerfile文件

# Python环境包括：
    1、scrapy
    2、wheel
    3、scrapy-redis
    4、scrapy-splash
    5、pika
    6、requests
    7、redis
    8、selenium
    9、pyscreenshot
    10、entrypoint2
    11、pyvirtualdisplay
    12、Chromeium浏览器

### 可以正常运行Selenium驱动Chrome

#### 如需要安装额外的包按照格式写入pip.txt即可。

# 注意Chromeium可能无法正常下载导致编译失败。

# 这儿有一个已经将Chromeium打包好的镜像，可基于此二次打包

### docker pull thsheep/chromium-xvfb-scrapy-py3:V1