<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>테스트 웹</title>
    <style>
        .main{
            display:grid;
            place-items: center;
            grid-template-columns: repeat(2, 1fr);
            grid-template-rowss: repeat(4, 1fr);
        }
        .title{
            font-size : 40px;
            grid-column: 1 / 3;
            grid-row :1;
        }
        .list{
            font-size : 20px;
        }
        .status{
            font-size : 20px;
        }

        .help{
            grid-column : 1/3;
            grid-row:3;
        }
    </style>
</head>

<body>
    <div class="main">
        <div class="title">
            <h1>세탁기 이용 모니터링 시스템</h1>
        </div>
        <div class="list">
            <span>세탁기 리스트</span>
            <ul>
                <li>1</li>
                <li>2</li>
                <li>3</li>
                <li>4</li>
                <li>5</li>
                <li>6</li>
            </ul>
        </div>
        <div class="status">
            <span>세탁기 상태</span>
            <ul>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
            </ul>
        </div>
        <div class="help">
            <span>세탁기 상태<br>0 = 사용가능<br>1 = 사용불가능</span>
        </div>
    </div>
</body>
</html>
