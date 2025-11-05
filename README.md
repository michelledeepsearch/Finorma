<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI 금융 서비스 고도화 제안</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;700&display=swap" rel="stylesheet">
    
    <style>
        /* 기본 설정 */
        body {
            font-family: 'Noto Sans KR', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa; /* 밝은 배경 */
            color: #333;
        }

        /* 컨테이너 및 레이아웃 */
        .proposal-header {
            background-color: #007bff; /* 메인 색상 (파란색) */
            color: white;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .proposal-header h1 {
            font-weight: 700;
            margin: 0 0 10px 0;
            font-size: 2.5em;
        }

        .proposal-header .subtitle {
            font-weight: 300;
            font-size: 1.2em;
        }

        .proposal-content {
            max-width: 1000px;
            margin: 30px auto;
            padding: 0 20px;
        }

        section {
            margin-bottom: 40px;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }

        hr {
            border: 0;
            height: 1px;
            background: #dee2e6;
            margin: 40px 0;
        }

        h2 {
            color: #007bff;
            font-size: 1.8em;
            border-bottom: 3px solid #007bff;
            padding-bottom: 10px;
            margin-top: 0;
            margin-bottom: 25px;
            font-weight: 700;
        }

        h3 {
            color: #495057;
            font-size: 1.3em;
            margin-top: 25px;
            margin-bottom: 15px;
            font-weight: 700;
        }

        h4 {
            color: #28a745; /* 강조 색상 (녹색) */
            font-size: 1.1em;
            margin-bottom: 5px;
            font-weight: 700;
        }

        ul {
            padding-left: 20px;
            margin-bottom: 20px;
        }

        li {
            margin-bottom: 8px;
        }

        /* 문제점 및 어려움 카드 스타일 */
        .problem-card, .difficulty-card {
            border-left: 5px solid #dc3545; /* 빨간색 (문제점 강조) */
            padding: 15px;
            margin-bottom: 20px;
            background-color: #fff3f3;
            border-radius: 4px;
        }

        .difficulty-card {
            border-left-color: #ffc107; /* 노란색 (어려움 강조) */
            background-color: #fffbe6;
        }

        /* 솔루션 섹션 스타일 */
        .solution-section h3 {
            color: #28a745;
            border-left: 5px solid #28a745;
            padding-left: 10px;
        }

        .solution-content ul {
            list-style-type: '✔️ '; /* 리스트 스타일 변경 */
        }

        .solution-content li {
            font-weight: 500;
        }

        /* 활용 사례 스타일 */
        .case-group {
            margin-bottom: 30px;
            padding: 15px;
            border: 1px solid #dee2e6;
            border-radius: 6px;
        }

        .case-group h3 {
            color: #007bff;
            margin-top: 0;
            border: none;
            padding-left: 0;
        }

        .case-card {
            background-color: #e9ecef;
            padding: 10px 15px;
            border-radius: 4px;
            margin-bottom: 10px;
        }

        .case-card p {
            margin-top: 5px;
            font-size: 0.95em;
        }

        /* 푸터 */
        .proposal-footer {
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            background-color: #e2e6ea;
            border-radius: 8px;
            font-size: 1.1em;
            font-weight: 500;
        }

        /* 반응형 디자인 */
        @media (max-width: 768px) {
            .proposal-header h1 {
                font-size: 2em;
            }
            .proposal-header .subtitle {
                font-size: 1em;
            }
            .proposal-content {
                margin: 20px auto;
            }
        }
    </style>
</head>
<body>

    <header class="proposal-header">
        <h1>AI 금융 서비스 고도화 제안</h1>
        <p class="subtitle">딥서치 AI 플랫폼을 통한 신속한 의사결정 및 실시간 서비스 구현</p>
    </header>

    <main class="proposal-content">
        
        <section class="problem-section">
            <h2>🚨 기존 서비스의 비효율성 문제</h2>
            
            <div class="problem-card">
                <h3>1. 실시간 분석
