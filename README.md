<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>T1WI与T2WI医学影像对比</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; background-color: #f0f8ff; }
        h1 { color: #2c3e50; border-bottom: 2px solid #3498db; }
        h2 { color: #3498db; }
        h3 { color: #2980b9; }
        table { border-collapse: collapse; width: 100%; margin: 20px 0; }
        th, td { border: 1px solid #3498db; padding: 10px; text-align: left; }
        th { background-color: #3498db33; }
        .highlight { background-color: #fff3cd; padding: 15px; border-radius: 5px; }
        .example { background-color: #e8f4f8; padding: 15px; margin: 15px 0; border-left: 4px solid #3498db; }
    </style>
</head>
<body>
    <h1>MRI中T1WI与T2WI的核心区别与应用</h1>

    <div class="highlight">
        <h2>核心概念</h2>
        <p>通过调节MRI的<strong>TR（重复时间）</strong>和<strong>TE（回波时间）</strong>参数，突出不同组织的弛豫特性：</p>
        <ul>
            <li>💡 T1WI：短TR（<1000ms）、短TE（<30ms）</li>
            <li>💡 T2WI：长TR（>2000ms）、长TE（>80ms）</li>
        </ul>
    </div>

    <h2>对比表格</h2>
    <table>
        <tr>
            <th>特征</th>
            <th>T1加权成像（T1WI）</th>
            <th>T2加权成像（T2WI）</th>
        </tr>
        <tr>
            <td>信号特点</td>
            <td>脂肪亮，水暗</td>
            <td>水亮，脂肪相对暗</td>
        </tr>
        <tr>
            <td>临床用途</td>
            <td>解剖结构、出血检测</td>
            <td>水肿、炎症观察</td>
        </tr>
    </table>

    <h2>临床应用示例</h2>
    <div class="example">
        <h3>🧠 脑部成像</h3>
        <ul>
            <li><strong>T1WI</strong>: 灰质（暗）与白质（稍亮）对比清晰</li>
            <li><strong>T2WI</strong>: 脑室（亮）与白质病变（如多发性硬化）</li>
        </ul>

        <h3>🩺 腹部成像</h3>
        <ul>
            <li><strong>T1WI</strong>: 显示肝脏脂肪变性（亮）</li>
            <li><strong>T2WI</strong>: 胆管扩张/囊肿（亮）</li>
        </ul>
    </div>

    <h2>记忆技巧</h2>
    <div style="background-color: #dff0d8; padding: 15px; border-radius: 5px;">
        <p>✅ <strong>T1WI</strong>: 想象"1"像注射器 → 用于对比剂增强成像</p>
        <p>✅ <strong>T2WI</strong>: 水（Two）的拼音首字母 → 水呈高信号</p>
    </div>
</body>
</html>
