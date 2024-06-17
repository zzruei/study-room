# studyroom
自习室预约系统

## studyroom-cloud：自习室预约系统微服务版本

### 项目结构：

StudyRoom-Cloud：父工程，进行依赖管理
  - studyroom-api：服务po实体和feign客户端
  - studyroom-common：通用模块
    - studyroom-common-core：公共核心模块，存放公共资源
    - studyroom-common-redis：redis工具模块
    - studyroom-common-security：安全模块
    - studyroom-common-sendmsg：发送短信验证码模块
    - studyroom-common-uploadfile：上传文件模块
  - studyroom-geteway：网关服务
  - studyroom-modules：其他服务
    - studyroom-reservation：自习室预约服务
    - studyroom-room：自习室管理服务
    - studyroom-user：用户管理服务
  - studyroom-ui：前端项目
  - studyroom-other：其他相关文件
    - nocas-shared-config：nocas共享配置文件
    - studyroom-doc：相关文档文件
    - studyroom-sql：mysql数据库文件


