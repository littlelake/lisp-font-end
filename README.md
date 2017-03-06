##概述
  该模板框架主要服务于用gulp进行打包的小型项目。

##目录结构

    ```
    |-project-name(项目名称)
      |-src
        |-app(项目源代码主要目录)
          |-page(单个活动页文件夹)
            |-images(单个活动页所需要的图片文件夹)
            |-page.html
            |-page.js
            |-page.scss
            |-README.md
        |-assets(静态资源文件目录)
          |-fonts(字体)
          |-images(图片)
          |-javascript(脚本)
          |-styles(样式)
          |-README.md
        |-vender(第三方脚本文件目录)
          |-zepto.js
          |-README.md
      |-favicon.ico
      |-package.json
      |-gulpfile.js(打包配置文件)
      |-README.md
    ```

##各结构说明

###src
  src主要放置核心核心代码文件、静态文件和第三方脚本文件

###favicon.ico
  网站图标

###gulpfile.js
  打包脚本配置文件，用gulp进行打包

###package.json
  npm包管理文件