/* 기본 설정 */
:root {
    --primary: #4a90e2;
    --ep-color: #ff7675;
    --ek-color: #00cec9;
    --bg-color: #f4f6f9;
    --text-color: #2d3436;
}

body {
    font-family: 'Malgun Gothic', 'Apple SD Gothic Neo', sans-serif;
    background-color: var(--bg-color);
    color: var(--text-color);
    margin: 0;
    padding: 20px;
}

.container {
    max-width: 800px;
    margin: 0 auto;
}

header {
    text-align: center;
    background-color: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    margin-bottom: 20px;
}

h1 { color: var(--primary); margin-top: 0; }
h2 { border-bottom: 2px solid #dfe6e9; padding-bottom: 10px; }

section {
    background-color: white;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    margin-bottom: 20px;
}

/* 시뮬레이션 영역 */
.sim-container {
    display: flex;
    gap: 30px;
    flex-wrap: wrap;
    margin-top: 20px;
}

.drop-zone {
    flex: 1;
    min-width: 200px;
    height: 350px;
    background-color: #e0e6ed;
    border-radius: 8px;
    position: relative;
    overflow: hidden;
}

#ball {
    width: 40px;
    height: 40px;
    background-color: #fdcb6e;
    border-radius: 50%;
    position: absolute;
    top: 20px;
    left: calc(50% - 20px);
    box-shadow: inset -5px -5px 10px rgba(0,0,0,0.2);
    /* 낙하 애니메이션 (가속도 느낌을 위해 ease-in 사용) */
    transition: top 1.5s cubic-bezier(0.5, 0, 1, 1);
}

.ground {
    position: absolute;
    bottom: 0;
    width: 100%;
    background-color: #636e72;
    color: white;
    text-align: center;
    padding: 10px 0;
    font-weight: bold;
}

.graph-zone {
    flex: 1;
    min-width: 250px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 20px;
}

.bar-container {
    background-color: #dfe6e9;
    height: 30px;
    border-radius: 15px;
    overflow: hidden;
    margin-top: 5px;
}

.bar {
    height: 100%;
    transition: width 1.5s cubic-bezier(0.5, 0, 1, 1);
}

.ep { background-color: var(--ep-color); width: 100%; }
.ek { background-color: var(--ek-color); width: 0%; }

.total {
    background-color: #fff3cd;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
}

/* 버튼 */
.controls { display: flex; gap: 10px; margin-top: 10px; }
.btn {
    flex: 1;
    padding: 12px;
    border: none;
    border-radius: 8px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
    transition: opacity 0.2s;
}
.btn:hover { opacity: 0.8; }
.primary { background-color: var(--primary); color: white; }
.secondary { background-color: #b2bec3; color: white; }
.btn:disabled { background-color: #bdc3c7; cursor: not-allowed; }

/* 퀴즈 영역 */
.quiz-card {
    background-color: #f8f9fa;
    padding: 20px;
    border-radius: 8px;
    margin-bottom: 20px;
}

.question { font-weight: bold; font-size: 1.1em; }
.options { display: flex; flex-direction: column; gap: 10px; }

.quiz-btn {
    text-align: left;
    padding: 15px;
    border: 1px solid #dcdde1;
    background-color: white;
    border-radius: 8px;
    font-size: 15px;
    cursor: pointer;
    transition: background-color 0.2s;
}
.quiz-btn:hover { background-color: #f1f2f6; }
