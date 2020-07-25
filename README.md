# 吕良的简历

## 基本信息
 * 男， 28岁
 * 联系方式：araragi222@gmail.com
## 教育
 * 本科
   * 上海理工大学 电子信息工程专业
 * 研究生
   * 日本九州大学 信息学专攻 信息安全方向
   * 研究生课题：基于随机森林检测BOT攻击的早期预兆
## 工作经历
 ### 2017/4-至今 日本富士通 云整合部门 Fujitsu co.ltd; Cloud Integration Department
 ### 项目经验（方向多为云平台网络整合/虚拟化后台控制器的开发）
   * Openstack tacker（NFV管理组件）的容器控制开发
     * 对openstack tacker组件进行升级，使其可以对容器化的NFV组件进行部署，为openstack victuora版的开源项目。
     * 根据用户的api请求及提交的配置文件，在openstack生成虚拟机并部署k8s环境，再调用k8s python api生成对应nvf容器
     * 我负责将openstack spec具体化实现的设计，以及实际的代码开发、测试。并带领子公司3名开发人员进行项目。以及与客户进行交流。
     * 开发团队：5人（日方母公司2人，国内子公司3人<-由我带领）
     * 技术栈：python/openstack/kubernetes
     * 项目链接（openstack）：https://wiki.openstack.org/wiki/Tacker
     * 最新spec：https://review.opendev.org/#/c/733454/
     
   * IoT平台虚拟网关（容器）自动化部署控制器
     * 在客户的IoT平台上对虚拟网关实行自动化部署的后端控制器
     * 根据用户api来调用docker python api，生成相应的容器并对其内部的路由表、防火墙表、gre-tunnel进行配置，使其连通用户的edge服务器和aws上的运算服务器
     * 我负责控制器功能开发，测试及冗长化监视功能的设计及开发
     * 开发团队：4人
     * 技术栈：python flask docker ansible gitlab-ci 
     
   * openstack云整合（非开发项目）
     * 为公司云服务整合SDN控制模块
     * 主要负责整合过程中的trouble-shooting及一个检测api投入正确脚本的开发
  
   * vmware NSX 云（非开发项目）
     * 为一汽车企业设计vmware NSX云，并将此overlay云与原有公司内网进行整合，以及迁移旧云平台的虚拟机至新平台
     * 我主要负责NSX云的网络拓扑设计以及和公司内网之间的整合
     * 制作发表资料，与客户的技术代表进行多次交流
     
## 技术经验
  * 代码类
    * python
    * java
    * C
    * perl
  * 框架类
    * flask
    * django
  * 云平台类
    * openstack
    * vmware
    * nuage vsd/vsc
    * aws/gcp
  * 开发/测试工具类
    * Git
    * Gitlab CI
    * Ansible
    * Unittest
  * 虚拟化
    * docker/k8s
  * 网络技术
    * 基本网络技术（路由/防火墙/...)，持有CCNA
    * SDN
    * Overlay网络
    
