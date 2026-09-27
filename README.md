# web-calculator

按钮式网页计算器。纯静态单文件实现（`index.html`，内联 CSS/JS）：无构建步骤、无框架、无外部依赖。

- 在线使用：<https://phgap.github.io/web-calculator/>
- 本地使用：直接用浏览器打开 `index.html`

计算核心为纯函数 `calculate(leftOperand, operator, rightOperand)`（返回数值结果或错误信号），UI 层只做输入转发与显示，不内嵌运算逻辑。
