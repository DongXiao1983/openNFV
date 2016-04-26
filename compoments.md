###其他支持NFV实施的核心OpenStack项目


Astara：为连接、保护多租户OpenStack环境提供整合的网络服务协调（路径、防火墙、负载均衡、VPN）。Wiki—— https://wiki.openstack.org/wiki/Astara



Blazar（旧称：Climate）: 为预订即服务（Reservation-as-a-Service），包括资源预订、预订更新及“按需求推送”/最尽力预订，及预订排期。可提供满足OPNFV Promise项目需求的解决方案。Wiki—— https://wiki.openstack.org/wiki/Blazar



Congress：策略即服务。可提供跨任何云服务组合的管治服务以于动态基础架构监控、执行、审计策略。Wiki—— https://wiki.openstack.org/wiki/Congress



Mistral：工作流程服务。可将复杂的业务流程（工作流程）作为任务及任务关系描述，使Mistral可处理状态管理、更正执行顺序、并行、同步及高可用。 Mistral还可提供灵活的任务调度。Wiki—— https://wiki.openstack.org/wiki/Mistral
Neutron：一个被其他OpenStack项目（例如Nova）管理、于接口设备（例如vNIC）间提供“网络即服务”的OpenStack项目。Neutron提供灵活性与选择性，其驱动器及插件来自众多主流电信运营商，使用户无需担心更换底层实施技术时须更改API或修改代码。本报告已介绍Neutron于NFV性能的功能。88%的OpenStack用户已实施Neutron。具体参考 http://docs.openstack.org/developer/neutron/

  

Neutron“Stadium”子项目：为Neutron的官方子项目集，Stadium包含众多NFV相关项目，维护主流驱动器及插件。完整列表可见 http://governance.openstack.org/reference/projects/neutron.html



Senlin：于管理被其他OpenStack服务外露的同质对象组的库与服务集。Wiki:  https://wiki.openstack.org/wiki/Senlin
