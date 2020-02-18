# ssr-acl
#**********************************************************************
# 注明转自ACL4SSR，为达到免流加去广告效果加以修改，默认代理，删除[bypass_list] 直连列表以及[proxy_list] 代理列表
# 09.16
# 2018年9月16日01:27:51
# 转载需要注明版权和来源
#
# 屏蔽常用网站、视频、手机rom广告&运营商劫持广告&数据跟踪&开屏广告
#
# 参照lhie1的surge规则改编，致谢!! https://github.com/lhie1/Surge
# 参照scomper的surge规则改编，致谢!! https://gist.github.com/scomper/915b04a974f9e11952babfd0bbb241a8/revisions
#
# 参数解释：
# [proxy_all] 默认代理-本规则使用
# [bypass_all] 默认直连
# [outbound_block_list] 禁止访问列表 在25行
# [bypass_list] 直连列表 在1207多行
# [proxy_list] 代理列表 在6874多行
# [remote_dns] 远程 DNS 解析 -不加使用本地 DNS
#
#**********************************************************************
