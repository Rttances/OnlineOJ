已修复问题：
1. 点LOGO回首页
2. 登录页标题字号大点
3. 系统中所有地方不要使用“学工号”这个说法，使用“账号”
4. "初始密码"不要写在登录页
5. 标签页文字修改
6. 自动刷新问题
7. 学生首页“其他功能”改成”练习场“
8. 学生首页”搜索课程“改成”所有课程“
9. 文件上传调大一点（上限调至30MB左右）
10. 教师主页中“课程公告”在导航栏不要放在上方，放在较靠下方位置
11. 集成监控平台（基于Promethues+Grafana+Node Exporter，Grafana密码位于docker-compose.yml中）
12. 教师主页中，左侧导航栏，学生成绩->成绩统计
13. 容器存储占用查看
14. 内存占用排序
15. 加入课程是否需要审批标识
16. 新建课程新增选项“该课程是否需要审批”
17. 管理员重置密码

未修复问题
1. 华师首页底部文案应做得跟华师官网底部一样
2. slogan不要写死在代码里，应由前端从后端获取
3. 管理员模块老师和学生分成两个标签页展示
4. 导入学生信息拖动不管用（部分浏览器还是有点问题，如360极速浏览器，但Chrome可以）
5. csv空白导入不了（同上，部分浏览器支持有些问题）
6. 导入学生信息后应有个按钮显示已完成
7. 上传附件支持更多格式(pptx/ppt/docx)（目前只修复了docx）
8. 导入学生成绩展示分次成绩，60分以下用绿色展示
9. 签到管理支持下载某次课程的签到记录
10. 教师可以批量通过或拒绝指定学生的申请
11. 课程踢人
12. 我的实验加下拉框，以课程名字为筛选，快到截止日期的排前面
14. 课程公告和课程资源分开
15. 主程序也包成一个容器方式运行