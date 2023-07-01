# Dotfiles 配置文件

统一管理我的配置文件，并分发到所需环境中。

# 基本思想
遵循 [6.NULL](https://missing-semester-cn.github.io/2020/command-line/) 管理配置文件的建议：配置文件应该统一在某个文件夹下，并使用**版本控制系统**进行管理，然后通过脚本将其**符号链接**到需要的地方。这么做有如下好处：
1. 安装简单：如果您登录了一台新的设备，在这台设备上应用您的配置只需要几分钟的时间
2. 可以执行：您的工具在任何地方都以相同的配置工作
3. 同步：在一处更新配置文件，可以同步到其他所有地方
4. 变更追踪：您可能要在整个程序员生涯中持续维护这些配置文件，而对于长期项目而言，版本历史是非常重要的

# 使用
Dotfiles 由 [anishathalye/dotbot](https://github.com/anishathalye/dotbot) 引导

仅需 `git clone && cd dotfiles && ./install`

安装脚本是幂等的 (idempotent) ：这意味着 `install` 可以被安全地多次执行

# 参考
[anishathalye/dotfiles](https://github.com/anishathalye/dotfiles)
