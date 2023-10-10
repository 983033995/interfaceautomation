<!--
 * @FilePath: /interfaceautomation/vsc-extension-quickstart.md
 * @Description: 
-->
# 欢迎使用 VS Code 扩展

## 文件夹中包含什么内容

* 这个文件夹包含了你的扩展所需的所有文件。
* `package.json` - 这是扩展的清单文件，你在其中声明你的扩展和命令。
  * 示例插件注册了一个命令，并定义了它的标题和命令名称。有了这些信息，VS Code 可以在命令面板中显示该命令。它还不需要加载插件。
* `src/extension.ts` - 这是你提供命令实现的主要文件。
  * 该文件导出一个函数 `activate`，在你的扩展第一次被激活时调用（在这种情况下是通过执行命令）。在 `activate` 函数内部，我们调用 `registerCommand`。
  * 我们将包含命令实现的函数作为第二个参数传递给 `registerCommand`。

## 设置

* 安装推荐的扩展（amodio.tsl-problem-matcher 和 dbaeumer.vscode-eslint）

## 快速上手

* 按下 `F5` 打开一个新窗口，并加载你的扩展。
* 通过按下命令面板中的 (`Ctrl+Shift+P` 或 `Cmd+Shift+P` 在 Mac 上) 并输入 `Hello World` 来运行你的命令。
* 在 `src/extension.ts` 文件中设置断点以调试你的扩展。
* 在调试控制台中查找你的扩展的输出。

## 进行更改

* 在更改 `src/extension.ts` 中的代码后，可以从调试工具栏重新启动扩展。
* 你也可以重新加载 VS Code 窗口（`Ctrl+R` 或 `Cmd+R` 在 Mac 上）以加载你的更改。

## 探索 API

* 当你打开文件 `node_modules/@types/vscode/index.d.ts` 时，你可以查看我们完整的 API。

## 运行测试

* 打开调试视图 (`Ctrl+Shift+D` 或 `Cmd+Shift+D` 在 Mac 上)，然后从启动配置下拉菜单中选择 `Extension Tests`。
* 按下 `F5` 在一个新窗口中运行测试，并加载你的扩展。
* 在调试控制台中查看测试结果的输出。
* 在 `src/test/suite/extension.test.ts` 中进行更改，或在 `test/suite` 文件夹中创建新的测试文件。
  * 提供的测试运行器只会考虑与名称模式 `**.test.ts` 匹配的文件。
  * 你可以在 `test` 文件夹中创建文件夹，以任何你想要的方式组织你的测试。

## 进一步操作

* 通过 [打包你的扩展](https://code.visualstudio.com/api/working-with-extensions/bundling-extension) 来减小扩展的大小并改善启动时间。
* 在 VS Code 扩展市场上 [发布你的扩展](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)。
* 通过设置 [持续集成](https://code.visualstudio.com/api/working-with-extensions/continuous-integration) 来自动构建。
