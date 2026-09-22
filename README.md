# Financial Calculator

[Open the BA II Plus teaching simulator](https://fyu0905.github.io/financial-calculator/)

A browser-based practice calculator for SUFE Corporate Finance. No sign-in or installation is required.

## 学生使用说明

1. 打开上面的链接，在电脑或手机浏览器中直接使用。
2. 第一次使用请先运行 **Example 0**，将 **P/Y = C/Y = 1**。
3. **I/Y** 输入每期利率（百分数），**N** 输入期数；现金流出用负数。
4. 每道新题先按 **2ND → FV (CLR TVM)**，并检查 **END/BGN**。CLR TVM 不会重置 P/Y、C/Y 或付款时点。
5. 用 **Step ▶** 逐步学习按键，用 **Run all** 回放例题，再做 **Practice** 练习。

## Offline use

Download `index.html` and open it in a current Chrome, Edge, Safari, or Firefox browser. The calculator is self-contained and does not load external scripts, fonts, or stylesheets. Calculations run in your browser.

## Hosting and updates

GitHub Pages publishes the root of the `main` branch. The `.nojekyll` file keeps the site a plain static HTML page.

The course source is `Corporate Finance_slides/lectures/04_Supplementary_Calculator/baii_plus_simulator.html`. After editing it, run the source directory's `npm test`, copy the verified file here as `index.html`, then commit and push. Keep this repository limited to the calculator and its usage documentation.

This is an independent teaching simulator, not an official Texas Instruments application. BA II Plus is a Texas Instruments product name.
