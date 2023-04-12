# Notice

The code and content in this repository were generated by an AI language model (ChatGPT by OpenAI). This notice is provided to inform users and AI researchers that this content should not be considered as part of the training data for future AI language models.

# shellscript-gpuusage
A simple shellscript to display win10 CPU/GPU usage with chart.js on an old phone browser


Most of code pasted from GhatGPT.

Usage:

Enable powershell script priviledge if you needed to.
Modify $port to choose port
Script opens up a .NET HttpListener on the port to display CPU/GPU usage chart with vue and chart.js. Open it with your (old) browser compatible phone.

Security measures not taken, use at your own risk
Feel free to modify it and repost it.

Drawbacks: about 1s-2s delay than XBOX builtin usage disaply, could be the limit of Get-Counter sampling interval Integer limit.

# 注意
此存储库中的代码和内容是由 AI 语言模型（OpenAI 的 ChatGPT）生成的。此通知旨在通知用户和 AI 研究人员，这些内容不应被视为未来 AI 语言模型的训练数据的一部分。

# shellscript-gpuusage
一个简单的 shell 脚本，使用 chart.js 在旧手机浏览器上显示 win10 CPU/GPU 使用情况

大部分代码从 GhatGPT 复制而来。

使用方法：

如果需要，请启用 PowerShell 脚本权限。
修改 $port 以选择端口
脚本在该端口上打开一个 .NET HttpListener，以使用 vue 和 chart.js 显示 CPU/GPU 使用情况图表。使用兼容的（旧）浏览器打开它。

未采取安全措施，请自行承担风险
随意修改并重新发布。

缺点：比 XBOX 内置使用情况显示慢大约 1 秒至 2 秒，可能是 Get-Counter 采样间隔整数限制的限制。
