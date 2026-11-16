V3 规则发布（与 v2 并存，不影响已安装的 v2 设备）。
surge/<设备>/        Surge 固定地址规则文件，12 个，供本地主配置引用。
rules/<版本>/<设备>/  带版本号的规则文件，供 Clash Verge 基础订阅和小火箭基础配置引用，不会被改写。
mihomo/              Clash Verge 基础订阅（Windows、Mac 各一份），不含节点；使用前必须安装私密的本地脚本。
shadowrocket-core.conf  小火箭基础配置，不含节点。
android/             NekoBox 路由规则用的域名清单，手工粘贴到应用内的路由规则。
本目录不含节点名称、服务器地址、密码或订阅地址。
