Jitsi 会议 —— 一款安全、简便且可扩展的视频会议工具，你既可以将其作为独立应用使用，也能嵌入到网页应用中。
补充说明
术语细节
Jitsi Meet 是该工具的官方名称，国内常用译法为 Jitsi 会议，也可保留原名直接写作 Jitsi Meet。
standalone app 译为 独立应用，强调无需依赖其他软件即可运行；embed in 译为 嵌入，符合技术文档的常用表达。
句式调整
原文用 that 引导定语从句，翻译时拆分为两个分句，更符合中文短句习惯，避免长句带来的阅读卡顿。
你是否需要我提供该翻译在技术文档场景下的不同表述版本？
# <p align="center">Jitsi Meet</p> Jitsi Meet is a set of Open Source projects which empower users to use and deploy video conferencing platforms with state-of-the-art video quality and features. <hr /> <p align="center"> <img src="https://raw.githubusercontent.com/jitsi/jitsi-meet/master/readme-img1.png" width="900" /> </p> <hr /> Amongst others here are the main features Jitsi Meet offers: * Support for all current browsers * Mobile applications * Web and native SDKs for integration * HD audio and video * Content sharing * Raise hand and reactions * Chat with private conversations * Polls * Virtual backgrounds And many more! ## Using Jitsi Meet Using Jitsi Meet is straightforward, as it's browser based. Head over to [meet.jit.si](https://meet.jit.si) and give it a try. It's scalable and free to use. All you need is a Google, Facebook or GitHub account in order to start a meeting. All browsers are supported! Using mobile? No problem, you can either use your mobile web browser or our fully-featured mobile apps: | Android | Android (F-Droid) | iOS | |:-:|:-:|:-:| | [<img src="resources/img/google-play-badge.png" height="50">](https://play.google.com/store/apps/details?id=org.jitsi.meet) | [<img src="resources/img/f-droid-badge.png" height="50">](https://f-droid.org/packages/org.jitsi.meet/) | [<img src="resources/img/appstore-badge.png" height="50">](https://itunes.apple.com/us/app/jitsi-meet/id1165103905) | If you are feeling adventurous and want to get an early scoop of the features as they are being developed you can also sign up for our open beta testing here: * [Android](https://play.google.com/apps/testing/org.jitsi.meet) * [iOS](https://testflight.apple.com/join/isy6ja7S) ## Running your own instance If you'd like to run your own Jitsi Meet installation head over to the [handbook](https://jitsi.github.io/handbook/docs/devops-guide/) to get started. We provide Debian packages and a comprehensive Docker setup to make deployments as simple as possible. Advanced users also have the possibility of building all the components from source. You can check the latest releases [here](https://jitsi.github.io/handbook/docs/releases). ## Jitsi as a Service If you like the branding capabilities of running your own instance but you'd like to avoid dealing with the complexity of monitoring, scaling and updates, JaaS might be for you. [8x8 Jitsi as a Service (JaaS)](https://jaas.8x8.vc) is an enterprise-ready video meeting platform that allows developers, organizations and businesses to easily build and deploy video solutions. With Jitsi as a Service we now give you all the power of Jitsi running on our global platform so you can focus on building secure and branded video experiences. ## Documentation All the Jitsi Meet documentation is available in [the handbook](https://jitsi.github.io/handbook/). ## Security For a comprehensive description of all Jitsi Meet's security aspects, please check [this link](https://jitsi.org/security). For a detailed description of Jitsi Meet's End-to-End Encryption (E2EE) implementation, please check [this link](https://jitsi.org/e2ee-whitepaper/). For information on reporting security vulnerabilities in Jitsi Meet, see [SECURITY.md](./SECURITY.md). ## Contributing If you are looking to contribute to Jitsi Meet, first of all, thank you! Please see our [guidelines for contributing](CONTRIBUTING.md). <br /> <br /> <footer> <p align="center" style="font-size: smaller;"> Built with ❤️ by the Jitsi team at <a href="https://8x8.com" target="_blank">8x8</a> and our community. </p> </footer>
翻译为中文（简体）
<p align="center">Jitsi 会议</p>
Jitsi 会议是一套开源项目，助力用户搭建和部署视频会议平台，提供顶尖水准的音视频质量与丰富功能。
<hr />
<p align="center"><img src="https://raw.githubusercontent.com/jitsi/jitsi-meet/master/readme-img1.png" width="900" /></p>
<hr />
Jitsi 会议的核心功能如下：
支持所有主流浏览器
提供移动应用程序
配备网页及原生软件开发工具包（SDK），便于集成
高清音视频通话
屏幕内容共享
举手发言与互动表情
私聊及群聊功能
会议投票
虚拟背景
以及更多实用功能！
使用 Jitsi 会议
Jitsi 会议基于浏览器运行，操作简便。访问官网 meet.jit.si 即可免费试用，且支持灵活扩展。只需登录谷歌、脸书或 GitHub 账号，就能发起会议，全浏览器兼容无压力。
使用移动设备？轻松搞定！你可以直接用手机浏览器访问，也能下载功能完备的官方移动应用：
安卓版	安卓版（F-Droid 应用商店）	苹果版
<img src="resources/img/google-play-badge.png" height="50">	<img src="resources/img/f-droid-badge.png" height="50">	<img src="resources/img/appstore-badge.png" height="50">
如果你乐于尝鲜，想抢先体验开发中的新功能，可注册参与公开测试版计划：
安卓测试版
苹果测试版
搭建自有部署实例
若你希望搭建专属的 Jitsi 会议部署实例，可查阅 官方手册 开启部署流程。
我们提供 Debian 系统安装包与完善的 Docker 配置方案，最大限度简化部署操作。高级用户也可选择从源代码编译所有组件。
最新版本信息可点击 此处 查看。
Jitsi 会议即服务
如果你既想要搭建自有实例的品牌定制能力，又不想耗费精力处理监控、扩容与版本更新等复杂运维工作，那么 JaaS 服务或许是你的理想之选。
8x8 公司旗下 Jitsi 会议即服务（JaaS） 是一款企业级视频会议平台，能帮助开发者、各类组织及企业轻松构建并部署视频会议解决方案。借助 JaaS 服务，你可直接调用 Jitsi 的全部功能，且由我们的全球平台提供技术支撑，让你专注于打造安全合规、具备品牌特色的视频会议体验。
官方文档
Jitsi 会议的完整使用及开发文档，均可在 官方手册 中查阅。
安全说明
如需了解 Jitsi 会议在安全方面的详细说明，可访问 此链接。
关于 Jitsi 会议端到端加密（E2EE）的具体实现机制，详见 官方白皮书。
若需报告 Jitsi 会议的安全漏洞，请参考 SECURITY.md 文件中的指引。
贡献代码
如果你有意为 Jitsi 会议项目贡献代码，首先向你表示感谢！请务必阅读我们的 贡献指南。
<footer><p align="center" style="font-size: smaller;">由 8x8 公司 Jitsi 团队与全球社区开发者 <br /> 满怀热忱 打造 ❤️ <br /> 官网：<a href="https://8x8.com" target="_blank">https://8x8.com</a></p></footer>
