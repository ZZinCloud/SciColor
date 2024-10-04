
**SciColor** is a visualization software designed to provide color scheme references for academic figures. It reads color scheme information from the "color_schemes.txt" file and displays various data visualizations including scatter plots, line graphs, bar charts, density plots, and pie charts. This tool helps you easily browse and select ideal color schemes while inspiring your creations. Currently, the "color_schemes.txt" file contains over 200 color schemes.

SciColor是一款为论文制图提供配色方案参考的可视化软件，能够读取"color_schemes.txt"文件中的配色方案信息，并展示包括散点图、曲线图、柱状图、密度图、相关图和饼图等多种数据图形，助您轻松浏览和选择理想的配色方案，同时为自创配色方案提供灵感。"color_schemes.txt"文件目前已包含超200种配色方案。

---

### User Guide / 操作指南

1. Select Color Count: Choose the number of colors in the scheme you need, and the table will automatically display the corresponding color schemes.
2. View Color Schemes: After selecting a preferred color scheme, click the "Select" column and the "Show examples" button to view HEX/RGB values (which can be copied) and randomly generated example data visualizations.
3. Customize Color Schemes: Edit the "color_schemes.txt" file to build your own color scheme database. Follow these input rules:
    - Enter each color scheme on a single line;
    - Input format: Color count Color1 Color2 ...;
    - For "gradient" color schemes, set the color count to 0;
    - Color information supports both HEX and RGB values.
<ol start="1">
<li>选择颜色数量：根据需要选择配色方案中所包含的颜色数量，表格将自动显示相应的配色方案。</li>
<li>查看配色方案：选择心仪的配色方案后，点击"Select"栏与"Show examples"按钮，即可查看HEX/RGB值(可复制)和随机数据示例图。</li>
<li>自定义配色方案: 通过编辑"color_schemes.txt"文件, 构建自己的配色方案数据库。输入规则如下:</li>
  <ul>
    <li> Enter each color scheme on a single line;
    <li> Input format: Color count Color1 Color2 ...;
    <li> For "gradient" color schemes, set the color count to 0;
    <li> Color information supports both HEX and RGB values.
  </ul>
</ol>

---

### Important Note / 注意事项

1. Please ensure that the "color_schemes.txt" file is in the same directory as the "SciColor.exe" file.

<ol start="1">
<li>请确保"color_schemes.txt"文件与"SciColor.exe"文件在同一目录下。</li>
</ol>

---

### Additional Information / 其它说明

1. To optimize the display of data visualizations and color schemes, the window size is currently not adjustable.
2. When a color scheme contains many colors, the table may not be able to display all color blocks. In this case, you can use the "Show examples" feature to view all color information for that scheme.
3. This program was initially intended for personal use and was programmed in Python for convenience, resulting in a larger exe file (despite using a virtual environment and upx).
4. The source code still needs improvement and is not currently open-source.
5. Hope SciColor will be helpful and inspiring to you. Wishing you good health and success in your work!

<ol start="1">
<li>为了便于数据图与配色方案的呈现，窗口大小暂时不可改变。</li>
<li>当配色方案中所包含的颜色较多时，表格可能无法展示所有颜色的色块。此时，可以通过"Show examples"查看该配色方案种的所有颜色信息。</li>
<li>该程序伊始仅作自用，为方便起见而使用Python编程，这也导致了所生成的exe文件较大(已使用虚拟环境和upx)。</li>
<li>源代码尚有提升空间，目前暂不公开。</li>
<li>希望SciColor能够对您有所帮助和启发，祝您身体健康，吃好喝好，工作顺利！</li>
