
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>基本 HTML 範例</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .content-block {
            border: 1px solid #ccc;
            padding: 20px;
            margin-bottom: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <!-- 標題 -->
    <h1>我的網站標題</h1>

    <!-- 區塊 -->
    <div class="content-block">
        <h2>這是一個內容區塊</h2>
        <p>這裡可以放置一些描述或段落，介紹你的網站或內容。</p>
    </div>

    <!-- 清單 -->
    <div class="content-block">
        <h2>我的待辦事項清單</h2>
        <ul>
            <li>學習 HTML</li>
            <li>學習 CSS</li>
            <li>學習 JavaScript</li>
        </ul>
    </div>

    <!-- 表格 -->
    <div class="content-block">
        <h2>聯絡人列表</h2>
        <table>
            <tr>
                <th>姓名</th>
                <th>電話</th>
                <th>電子郵件</th>
            </tr>
            <tr>
                <td>小明</td>
                <td>0912345678</td>
                <td>xiaoming@example.com</td>
            </tr>
            <tr>
                <td>小華</td>
                <td>0987654321</td>
                <td>xiaohua@example.com</td>
            </tr>
        </table>
    </div>

    <!-- 按鈕 -->
    <div class="content-block">
        <h2>按鈕範例</h2>
        <button onclick="alert('按鈕已被點擊！')">點擊我</button>
    </div>

    <!-- 圖片 -->
    <div class="content-block">
        <h2>[這是一張圖片](https://i.imgur.com/2j9Xpk7.jpeg)</h2>
        <img src="https://i.imgur.com/2j9Xpk7.jpeg" alt="範例圖片" width="300" height="200">
    </div>

</body>
</html>
