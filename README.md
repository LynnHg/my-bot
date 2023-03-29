# ChatGPT-Vercel

API Key 由我自己免费提供，请不要滥用，不提供长期服务，请自行部署。

> 本项目基于 [chatgpt-vercel](https://github.com/ourongxing/chatgpt-vercel)

## 使用方法

- 设置

  - 系统角色指令：会在每次提问时添加，一定用加句号。主要用于对 ChatGPT 的语气，口头禅这些进行定制。

  - 思维发散程度：越高 ChatGPT 思维就越发散，开始乱答。根据不同的问题可以调节这个选项，创意性的就可以调高一点。

  - 开启连续对话：OpenAI 并没有提供 ChatGPT 那样的上下文功能，只能每次都把全部对话传过去，并且都要算 token，而且仍然有最大 4096 token 的限制。

- token 是怎么算的：OpenAI 有它自己的算法，大多数时候是一个单词 1 token，一个汉字 2 token。
- Open AI Key 要怎么获得：注册 OpenAI 的帐号，然后 [生成 Key](https://platform.openai.com/account/api-keys) 就行了。
- 输入框右边的四个按钮：
  - 对话生成图片，电脑上复制，手机上下载。
  - 对话生成 Markdown，复制到剪贴板。
  - 重新回答最近的一个问题。其实也可以用键盘的<kbd>↑</kbd>键，可以自动将最近的一次提问填到输入框里。
  - 清空对话。
- 输入框
  - <kbd>Enter</kbd>发送，<kbd>Shift</kbd>+<kbd>Enter</kbd>换行。
  - <kbd>空格</kbd> 或者 <kbd>/</kbd> 搜索 Prompt 预设，现在只显示 20 个。所有 Prompt 可以查看 [prompts.md](prompts.md) 。
  -  <kbd>↑</kbd> 将最近的一次提问填到输入框里。
- 点击顶部标题滚动到顶部，点击输入框滚动到底部。
- 发送 sk- 开头的 key，可以直接查询余额。可以换行查询多个。也可以发送 `查询填写的 Key 的余额` 来直接查询你填的 key 的余额，这个 Prompt 预设第一个就是，直接用。作为站长，你可以通过设置环境变量来定时查询所有内置 key 的余额，并发送到微信上。

## License
[MIT](./LICENSE)
