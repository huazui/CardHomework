# CardHomework
作业主要用card布局实现三个连贯界面，主要代码在homework/CardLayout/homework.html文件里。
email: amber.d.p.chen@oocl.com
# student.html
命令行的git又拒绝上传了。。弄了好久反而更糟糕了。我先把周五作业拉到这里来
- 页面布局采用border，右边只有一个增加的表格，左边是树。
- 有根节点为allClass的树，下面有班级的节点，班级节点下面是学生叶子节点。
- 右键，可以有展示节点信息的按钮。
- 右键删除，当节点为allClass根节点时候，提示不能删除，其余节点可以删除。
- 右键增加，当为叶子节点时，在该班级下增加一个学生节点并且弹窗提示。当为班级节点时，在该班级下面增加一个学生。当为根节点时，新增一个班级。
- 表格可以有增加功能，当选中班级节点时候，为该班级增加一个学生节点。当选中根节点时，为它增加一个班级，当选中学生节点时，为它增加一个同学。这个需求是按要求做的，感觉有点奇怪，先选中节点再输入信息然后点击增加按钮增加相应的节点。
