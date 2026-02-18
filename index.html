<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>전란의 겁화 계산기</title>
    <style>
        body { background-color: #1a1a1b; color: #e8eaed; font-family: 'Malgun Gothic', sans-serif; display: flex; justify-content: center; padding: 20px; }
        .container { background-color: #2c2c2e; padding: 25px; border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.5); width: 450px; border: 1px solid #444; }
        h2 { text-align: center; color: #ffca28; margin-bottom: 20px; border-bottom: 2px solid #ffca28; padding-bottom: 10px; }
        .input-group { display: grid; grid-template-columns: 100px 1fr 60px; align-items: center; margin-bottom: 12px; gap: 10px; }
        label { font-weight: bold; font-size: 14px; }
        input { background: #3a3a3c; border: 1px solid #555; color: #fff; padding: 8px; border-radius: 4px; text-align: right; }
        .result-box { margin-top: 25px; background: #1a1a1b; padding: 20px; border-radius: 8px; border-left: 5px solid #ffca28; }
        .result-item { display: flex; justify-content: space-between; margin-bottom: 10px; font-size: 16px; }
        .highlight { color: #ffca28; font-weight: bold; }
        .target { color: #ff5252; font-weight: bold; }
        .progress-container { background: #444; height: 12px; border-radius: 6px; margin-top: 10px; overflow: hidden; }
        #progress-bar { background: linear-gradient(90deg, #ffca28, #ffa000); height: 100%; width: 0%; transition: width 0.3s; }
        footer { margin-top: 15px; font-size: 12px; color: #888; text-align: center; }
    </style>
</head>
<body>

<div class="container">
    <h2>전란의 겁화 계산기</h2>
    
    <div class="input-group">
        <label>하급 결정석</label>
        <input type="number" id="in1" value="0" min="0" oninput="calc()">
        <span>개</span>
    </div>
    <div class="input-group">
        <label>중급 결정석</label>
        <input type="number" id="in2" value="0" min="0" oninput="calc()">
        <span>개</span>
    </div>
    <div class="input-group">
        <label>상급 결정석</label>
        <input type="number" id="in3" value="0" min="0" oninput="calc()">
        <span>개</span>
    </div>
    <div class="input-group">
        <label>특급 결정석</label>
        <input type="number" id="in4" value="0" min="0" oninput="calc()">
        <span>개</span>
    </div>
    <div class="input-group">
        <label>불멸 결정석</label>
        <input type="number" id="in5" value="0" min="0" oninput="calc()">
        <span>개</span>
    </div>

    <div class="result-box">
        <div class="result-item">
            <span>🔥 전란의 불씨 소모량:</span>
            <span id="total-fire" class="highlight">0</span>
        </div>
        <div class="result-item">
            <span>🌑 전란의 겁화 획득량:</span>
            <span id="total-result" class="highlight">0</span>
        </div>
        <hr style="border:0; border-top:1px solid #444;">
        <div class="result-item" style="margin-top:10px;">
            <span>✨ 황혼+여명 제작까지:</span>
            <span id="need-more" class="target">400</span>
        </div>
        <div style="font-size: 12px; text-align: right; color: #aaa;">진행률: <span id="percent">0</span>%</div>
        <div class="progress-container">
            <div id="progress-bar"></div>
        </div>
    </div>
    
    <footer>황혼(200개) + 여명(200개) = 총 400개 기준</footer>
</div>

<script>
function calc() {
    const v1 = parseInt(document.getElementById('in1').value) || 0;
    const v2 = parseInt(document.getElementById('in2').value) || 0;
    const v3 = parseInt(document.getElementById('in3').value) || 0;
    const v4 = parseInt(document.getElementById('in4').value) || 0;
    const v5 = parseInt(document.getElementById('in5').value) || 0;

    // 불씨 소모량 계산
    const totalFire = (v1 * 30) + (v2 * 40) + (v3 * 50) + (v4 * 60) + (v5 * 70);
    // 겁화 획득량 계산
    const totalResult = (v1 * 1) + (v2 * 3) + (v3 * 5) + (v4 * 10) + (v5 * 30);
    
    const target = 400;
    const needMore = Math.max(0, target - totalResult);
    const percent = Math.min(100, (totalResult / target * 100)).toFixed(1);

    document.getElementById('total-fire').innerText = totalFire.toLocaleString();
    document.getElementById('total-result').innerText = totalResult.toLocaleString();
    document.getElementById('need-more').innerText = needMore <= 0 ? "제작 가능!" : needMore.toLocaleString() + "개 부족";
    document.getElementById('percent').innerText = percent;
    document.getElementById('progress-bar').style.width = percent + "%";
}
</script>

</body>
</html>
