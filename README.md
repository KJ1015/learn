<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>情緒調適指南 2.0 - 成為自己的情緒夥伴</title>
    <style>
        :root {
            --bg-color: #f4f7f6;
            --text-color: #333;
            --container-bg: #ffffff;
            --primary-color: #16a085;
            --secondary-color: #2980b9;
            --border-color: #e0e0e0;
            --box-bg: #e8f6f3;
            --box-border: #d0e8e1;
            --box-accent: #1abc9c;
        }
        body.dark-mode {
            --bg-color: #2c3e50;
            --text-color: #ecf0f1;
            --container-bg: #34495e;
            --primary-color: #1abc9c;
            --secondary-color: #3498db;
            --border-color: #4a627a;
            --box-bg: #2f4f4f;
            --box-border: #4a627a;
            --box-accent: #1abc9c;
        }
        body {
            font-family: 'Helvetica Neue', 'Microsoft JhengHei', '微軟正黑體', Arial, sans-serif;
            line-height: 1.8;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            transition: background-color 0.3s, color 0.3s;
        }
        .navbar {
            background-color: var(--container-bg);
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 10px 20px;
            display: flex;
            justify-content: space-around;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .navbar a {
            color: var(--secondary-color);
            text-decoration: none;
            font-weight: 600;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .navbar a:hover {
            background-color: var(--bg-color);
        }
        #theme-toggle {
            cursor: pointer;
            font-size: 1.5em;
        }
        .container {
            max-width: 800px;
            margin: 30px auto;
            background-color: var(--container-bg);
            padding: 20px 40px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
        }
        h1, h2, h3 { color: var(--text-color); font-weight: 600; }
        h1 { text-align: center; font-size: 2.2em; margin-bottom: 20px; color: var(--primary-color); border-bottom: 2px solid var(--border-color); padding-bottom: 15px; }
        h2 { font-size: 1.8em; margin-top: 40px; color: var(--secondary-color); border-left: 5px solid var(--secondary-color); padding-left: 15px; }
        h3 { font-size: 1.3em; margin-top: 25px; }
        .safety-warning, .learning-map, .practice-box, .takeaway-box, .conclusion {
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            border-left: 5px solid;
        }
        .safety-warning { background-color: #fbeaea; border-color: #e74c3c; color: #c0392b; }
        .learning-map { background-color: #eaf2f8; border-color: #3498db; }
        .practice-box { background-color: var(--box-bg); border-color: var(--box-accent); }
        .takeaway-box { background-color: #fef9e7; border-color: #f1c40f; }
        .practice-box h3, .takeaway-box h3 { margin-top: 0; color: var(--primary-color); }
        textarea {
            width: 100%;
            height: 80px;
            margin-top: 10px;
            padding: 10px;
            border: 1px solid var(--border-color);
            border-radius: 5px;
            background-color: var(--bg-color);
            color: var(--text-color);
            font-size: 1em;
            resize: vertical;
        }
        .conclusion { text-align: center; background-color: #f8f9fa; border: none; font-style: italic; color: #555; }
        footer { text-align: center; margin-top: 20px; font-size: 0.9em; color: #777; }
    </style>
</head>
<body>

    <nav class="navbar">
        <a href="#unit1">單元一</a>
        <a href="#unit2">單元二</a>
        <a href="#unit3">單元三</a>
        <div id="theme-toggle">🌙</div>
    </nav>

    <div class="container">
        
        <div class="safety-warning">
            <h3>【重要安全提示】</h3>
            <p>本教材旨在提供基礎的情緒知識與技巧，不能取代專業心理諮詢。如果您正經歷嚴重的情緒困擾、憂鬱或焦慮，或有任何自我傷害的想法，請務必立即尋求專業協助（如心理師、精神科醫師或生命線）。您的安全是最重要的。</p>
        </div>

        <h1>情緒調適指南 2.0：成為自己的情緒夥伴</h1>
        
        <div class="learning-map">
            <h3>【我們的學習地圖】</h3>
            <p>這趟旅程將分為三站，幫助你與情緒建立更健康的關係：</p>
            <p><strong>📍 第一站：傾聽情緒</strong> - 學習辨識與接納你的內在感受。</p>
            <p><strong>📍 第二站：理解情緒</strong> - 探索情緒背後的故事與想法。</p>
            <p><strong>📍 第三站：回應情緒</strong> - 建立你的情緒工具箱，並學會溫柔地對待自己。</p>
        </div>

        <!-- 單元一 -->
        <div class="unit" id="unit1">
            <h2>單元一：傾聽情緒——你的感受都是被允許的</h2>
            <p>旅程的第一步，是學習傾聽。情緒是我們內心的信差，它們的到來，是為了告訴我們一些事。讓我們練習不加評判地迎接它們，並溫柔地為它們命名。</p>
            <div class="practice-box">
                <h3>【練習：此刻的心情掃描】</h3>
                <p>現在，請花一點時間，溫柔地問自己：「我現在的感覺是什麼？」試著將感受寫下來，無論是正面、負面或模糊不清，都沒關係。只是單純地觀察與記錄。</p>
                <textarea id="practice1" placeholder="例如：我感覺有點焦慮，肩膀緊緊的。同時也有一點期待，因為快要週末了..."></textarea>
            </div>
            <div class="takeaway-box">
                <h3>【本單元回顧】</h3>
                <p>✓ 情緒是中性的，是來幫助我們的信差。<br>✓ 為情緒命名（標籤化），能幫助我們的大腦冷靜下來。<br>✓ 我們練習的目標是「觀察」，而非立即「解決」。</p>
            </div>
        </div>

        <!-- 單元二 -->
        <div class="unit" id="unit2">
            <h2>單元二：理解情緒——當個溫柔的情緒偵探</h2>
            <p>情緒的背後總有它的故事。這個故事通常包含三部分：一個「事件」、我們對事件的「想法」，以及最終產生的「情緒」。讓我們用ABC模式來溫柔地探索這個連結。</p>
            <p><strong>A (事件) → B (想法/信念) → C (情緒/結果)</strong></p>
            <p>請記得，真正影響我們心情的，往往是我們的「想法(B)」，而非「事件(A)」本身。</p>
            <div class="practice-box">
                <h3>【練習：我的情緒偵探筆記】</h3>
                <p>回想一個最近讓你情緒起伏的事件，試著在這裡寫下你的ABC分析：</p>
                <p><strong>A (觸發事件)：</strong></p>
                <textarea id="practice2a" placeholder="客觀描述發生了什麼事。例如：我傳訊息給朋友，但他很久沒回。"></textarea>
                <p><strong>B (我的想法)：</strong></p>
                <textarea id="practice2b" placeholder="我當時腦中閃過什麼念頭？例如：他是不是覺得我煩？我是不是說錯話了？"></textarea>
                <p><strong>C (我的情緒)：</strong></p>
                <textarea id="practice2c" placeholder="基於這個想法，我產生了什麼感覺？例如：感到被忽略、有點傷心和焦慮。"></textarea>
            </div>
            <div class="takeaway-box">
                <h3>【本單元回顧】</h3>
                <p>✓ 情緒常由我們對事件的「詮釋」所驅動。<br>✓ 透過ABC模式，我們可以看見想法與情緒的連結。<br>✓ 辨識出背後的想法，是改變情緒反應的第一步。</p>
            </div>
        </div>

        <!-- 單元三 -->
        <div class="unit" id="unit3">
            <h2>單元三：回應情緒——建立你的自我關懷工具箱</h2>
            <p>當我們能傾聽並理解情緒後，就能學習如何用溫柔而有效的方式來回應它。這不是壓抑，而是關懷。讓我們來建立一個專屬你的「自我關懷工具箱」。</p>
            <h3>工具選項：</h3>
            <ul>
                <li><strong>安撫身體：</strong>深呼吸、溫水澡、給自己一個擁抱。</li>
                <li><strong>轉移空間：</strong>去散步、整理房間、換個環境。</li>
                <li><strong>健康表達：</strong>向信任的人傾訴、寫日記、畫畫。</li>
                <li><strong>自我慈悲：</strong>對自己說些溫柔的話，例如：「親愛的，這真的很難受，你感到難過是完全正常的。」</li>
            </ul>
            <div class="practice-box">
                <h3>【練習：打造我的專屬工具箱】</h3>
                <p>從上面的選項或你自己的經驗中，挑選3個你最想嘗試的方法，把它們寫下來。這就是你未來可以隨時取用的寶貴工具。</p>
                <textarea id="practice3" placeholder="1. 感到焦慮時，練習4-4-6深呼吸法。\n2. 感到低落時，允許自己看一部喜歡的電影。\n3. 感到憤怒時，去快走30分鐘。"></textarea>
            </div>
            <div class="takeaway-box">
                <h3>【本單元回顧】</h3>
                <p>✓ 我們可以選擇用健康的方式回應情緒，而非被情緒淹沒。<br>✓ 建立個人化的工具箱，能讓我們在需要時有所準備。<br>✓ 「自我慈悲」是其中最強大、最溫柔的工具。</p>
            </div>
        </div>

        <div class="conclusion" id="final-step">
            <h3>【旅程的下一步：我的行動計畫】</h3>
            <p>學習最重要的部分是應用。請為自己設定一個小小的行動計畫：</p>
            <p>「下一次，當我注意到自己有強烈情緒時，我承諾會先停下來，做的第一件事是：_________________ (例如：做三次深呼吸 / 告訴自己『沒關係』)。」</p>
            <p>請記住，與情緒共處是一生的練習。對自己有耐心，每一步微小的嘗試，都值得被喝采。</p>
        </div>

        <footer>
            <p>© 2024 情緒調適指南 2.0</p>
        </footer>

    </div>

    <script>
        // --- 工程師的魔法：互動功能 ---

        // 1. 夜間模式切換
        const themeToggle = document.getElementById('theme-toggle');
        themeToggle.addEventListener('click', () => {
            document.body.classList.toggle('dark-mode');
            // 更新圖示
            if (document.body.classList.contains('dark-mode')) {
                themeToggle.textContent = '☀️';
            } else {
                themeToggle.textContent = '🌙';
            }
        });

        // 2. 將使用者的輸入儲存到瀏覽器
        const textareas = document.querySelectorAll('textarea');

        // 頁面載入時，讀取已儲存的內容
        textareas.forEach(textarea => {
            const savedText = localStorage.getItem(textarea.id);
            if (savedText) {
                textarea.value = savedText;
            }
        });

        // 當使用者輸入時，自動儲存
        textareas.forEach(textarea => {
            textarea.addEventListener('input', () => {
                localStorage.setItem(textarea.id, textarea.value);
            });
        });

    </script>

</body>
</html>
