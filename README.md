# ManufactureLLM

基于lagent开发的智能制造领域的agent，用来解决智能制造领域的各种问题。

## 技术实现
internlm2+lagent，通过微调调用智能制造领域的问题，如FJSP问题等，内置算法接口，以供调用。

## 使用步骤



## demo
本地demo运行如下，后续会配置web端使用
<img width="749" alt="lagent_run" src="https://github.com/wzl0329/ManufactureLLM/assets/52845811/f9c1e026-4563-4bee-8675-8c66f2cefa95">
<img width="864" alt="lagent_run1" src="https://github.com/wzl0329/ManufactureLLM/assets/52845811/45997dd5-436f-43fa-81d8-7a48fdfa16ae">




## 未来展望

将LLM作为大脑，作为专家解决制造业问题，并调用如传感器、机器人接口。

1、完善现有工具，如读取本地文件功能，提高可易用性；

2、加入更多调度算法工具，如遗传算法等进化算法；

3、接入其他接口，如视觉模块，识别实体机器和工件，自动编码成标准格式进行输入；

4、使用RAG、finetune等方法定制化模型，赋予模型更多专家知识和经验，兼具对话和算法能力；

5、加入智能制造中其他算法和工具，如诊断算法。
