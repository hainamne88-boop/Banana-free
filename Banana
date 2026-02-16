<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Get Banana Free 🍌 | Blox Banana Hub</title>
    <!-- Font Awesome 6 (Free) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        }

        body {
            min-height: 100vh;
            background: radial-gradient(circle at 30% 10%, #1a1a2e, #0d0d1a);
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 16px;
            position: relative;
            overflow-x: hidden;
        }

        /* hiệu ứng ánh sáng nền */
        body::before {
            content: '';
            position: absolute;
            width: 300px;
            height: 300px;
            background: rgba(255, 215, 0, 0.15);
            border-radius: 50%;
            filter: blur(120px);
            top: -50px;
            left: -50px;
            z-index: 0;
        }
        body::after {
            content: '';
            position: absolute;
            width: 400px;
            height: 400px;
            background: rgba(255, 140, 0, 0.1);
            border-radius: 50%;
            filter: blur(150px);
            bottom: -100px;
            right: -50px;
            z-index: 0;
        }

        .card {
            width: 100%;
            max-width: 700px;
            background: rgba(20, 20, 35, 0.75);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
            border: 2px solid rgba(255, 215, 0, 0.3);
            border-radius: 48px;
            padding: 36px 28px;
            box-shadow: 0 30px 50px rgba(0, 0, 0, 0.7), 0 0 30px rgba(255, 200, 0, 0.3);
            position: relative;
            z-index: 10;
            transition: transform 0.2s ease;
        }

        /* AURA VIP 10 (giống Liên Quân) - viền sáng lấp lánh */
        .card::before {
            content: '';
            position: absolute;
            inset: -4px;
            border-radius: 52px;
            padding: 4px;
            background: linear-gradient(145deg, 
                #ffd966, #ffb347, #ff8c42, #ffd966, 
                #f9e076, #ffaa33, #ff6b6b, #ffd966);
            -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
            -webkit-mask-composite: xor;
            mask-composite: exclude;
            opacity: 0.8;
            animation: rotateAura 6s linear infinite;
            pointer-events: none;
        }

        @keyframes rotateAura {
            0% { background-position: 0% 0%; }
            100% { background-position: 200% 0%; }
        }

        /* ảnh đại diện + khung aura */
        .avatar-wrapper {
            display: flex;
            justify-content: center;
            margin-bottom: 25px;
            filter: drop-shadow(0 0 20px gold);
        }

        .avatar {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            background: linear-gradient(145deg, #ffe68f, #ffb347);
            padding: 5px;
            box-shadow: 0 0 30px #ffb800, 0 0 60px #ffaa33;
            animation: avatarPulse 3s infinite alternate;
        }

        .avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 50%;
            border: 3px solid #1e1e2f;
            background: #2a1e0f;
        }

        @keyframes avatarPulse {
            0% { box-shadow: 0 0 20px #ffb800, 0 0 40px #ff8800; }
            100% { box-shadow: 0 0 40px #ffdd55, 0 0 80px #ffaa33; }
        }

        h1 {
            font-size: 3rem;
            font-weight: 800;
            text-align: center;
            background: linear-gradient(135deg, #ffe484, #ffad4d);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            letter-spacing: 2px;
            text-shadow: 0 0 15px #ffa600, 0 0 30px #ff7b00;
            margin-bottom: 10px;
        }

        .sub {
            text-align: center;
            color: #b9b9d6;
            font-weight: 500;
            margin-bottom: 30px;
            font-size: 1.2rem;
            background: rgba(0,0,0,0.3);
            padding: 8px 20px;
            border-radius: 60px;
            display: inline-block;
            margin-left: auto;
            margin-right: auto;
            width: fit-content;
            backdrop-filter: blur(5px);
            border: 1px solid #ffbb3355;
        }

        .get-banana-btn {
            width: 100%;
            background: linear-gradient(145deg, #f9c851, #f79d2e);
            border: none;
            border-radius: 80px;
            padding: 22px 20px;
            font-size: 2.2rem;
            font-weight: bold;
            color: #1e1e2f;
            text-shadow: 2px 2px 0 #ffd966;
            letter-spacing: 3px;
            box-shadow: 0 20px 30px #b85e00, 0 0 30px #ffb700;
            cursor: pointer;
            transition: all 0.15s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            margin-bottom: 35px;
            border: 2px solid #ffec9e;
        }

        .get-banana-btn:active {
            transform: scale(0.97);
            box-shadow: 0 10px 20px #b85e00;
        }

        .tasks-container {
            background: rgba(0, 0, 0, 0.35);
            border-radius: 50px;
            padding: 24px 20px;
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255,215,0,0.3);
            margin-bottom: 25px;
        }

        .task-item {
            display: flex;
            align-items: center;
            gap: 16px;
            background: rgba(255,255,240,0.05);
            padding: 16px 20px;
            border-radius: 60px;
            margin-bottom: 15px;
            border: 1px solid rgba(255,200,50,0.4);
            transition: 0.2s;
            font-size: 1.2rem;
            font-weight: 500;
            color: #f0e6c5;
            cursor: pointer;
        }

        .task-item:hover:not(.completed) {
            background: rgba(255,215,0,0.15);
            border-color: gold;
        }

        .task-item.completed {
            background: rgba(50,200,50,0.15);
            border-color: #5eff7e;
            color: #b0ffb0;
            pointer-events: none;
            opacity: 0.9;
        }

        .task-item i {
            width: 32px;
            font-size: 1.8rem;
            color: gold;
        }

        .task-item.completed i {
            color: #5eff7e;
        }

        .task-status {
            margin-left: auto;
            font-size: 1.3rem;
        }

        .countdown-box {
            text-align: center;
            background: #1e1e30;
            padding: 15px;
            border-radius: 60px;
            font-size: 1.8rem;
            font-weight: 600;
            letter-spacing: 3px;
            border: 1px solid #ffa600;
            color: #ffe28b;
            margin: 20px 0;
            box-shadow: inset 0 0 15px #00000055, 0 0 20px #ffbb00;
        }

        .script-area {
            background: #0c0c18;
            border-radius: 40px;
            padding: 25px;
            border: 2px solid #ffaa33;
            box-shadow: 0 0 30px #ffa60033, inset 0 0 15px #00000077;
        }

        .script-box {
            background: #010014;
            padding: 22px 18px;
            border-radius: 30px;
            color: #b5ffb5;
            font-family: 'Fira Code', monospace;
            font-size: 0.9rem;
            line-height: 1.5;
            border: 1px solid #f90;
            word-break: break-word;
            white-space: pre-wrap;
            max-height: 250px;
            overflow-y: auto;
            box-shadow: 0 0 20px #00aa8822;
            margin-bottom: 20px;
        }

        .copy-btn {
            background: linear-gradient(145deg, #ffcf5c, #ff9f2f);
            border: none;
            border-radius: 50px;
            padding: 18px 30px;
            font-size: 1.7rem;
            font-weight: bold;
            color: #12121c;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            box-shadow: 0 10px 0 #9b4a00, 0 0 30px #ffb700;
            cursor: pointer;
            transition: 0.1s;
            border: 2px solid #ffdc88;
        }

        .copy-btn:active {
            transform: translateY(5px);
            box-shadow: 0 5px 0 #9b4a00, 0 0 40px gold;
        }

        .note {
            margin-top: 15px;
            color: #aaaac0;
            font-size: 1rem;
            text-align: center;
            border-top: 1px dashed #ffaa3355;
            padding-top: 15px;
        }

        .note i {
            color: #ff3b3b;
        }

        .hidden {
            display: none !important;
        }

        .footer {
            color: #7a7a9e;
            margin-top: 15px;
            font-size: 0.9rem;
            text-align: center;
        }

        .fa-spinner {
            animation: spin 1s linear infinite;
        }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    </style>
</head>
<body>
    <div class="card">
        <!-- ảnh đại diện + aura -->
        <div class="avatar-wrapper">
            <div class="avatar">
                <!-- hình đại diện (biểu tượng banana) -->
                <img src="https://i.imgur.com/6U0rV6M.png" alt="Banana Avatar" onerror="this.src='https://via.placeholder.com/200/ffb347/000000?text=🍌'">
            </div>
        </div>

        <h1>GET BANANA FREE</h1>
        <div class="sub">🍌 tab blox banana · no key hub</div>

        <!-- nút to GET BANANA -->
        <button class="get-banana-btn" id="getBananaBtn">
            <i class="fas fa-banana"></i> GET BANANA <i class="fas fa-bolt"></i>
        </button>

        <!-- KHU VỰC TASKS (ẩn ban đầu) -->
        <div id="tasksSection" class="hidden">
            <div class="tasks-container">
                <!-- task 1: follow + video -->
                <div class="task-item" id="task1">
                    <i class="fab fa-tiktok"></i>
                    <span>Follow <strong>hnam.script</strong> & đăng lại video</span>
                    <span class="task-status"><i class="fas fa-circle-notch"></i></span>
                </div>
                <!-- task 2: tim (tìm) hnam.script -->
                <div class="task-item" id="task2">
                    <i class="fas fa-search"></i>
                    <span>Tim và follow <strong>hnam.script</strong></span>
                    <span class="task-status"><i class="fas fa-circle-notch"></i></span>
                </div>
                <!-- task 3: follow thứ hai (theo mô tả) thực chất cũng là follow, nhưng làm 3 dòng => chúng ta có 3 dòng -->
                <div class="task-item" id="task3">
                    <i class="fab fa-tiktok"></i>
                    <span>Follow <strong>hnam.script</strong> (xác nhận lần 2)</span>
                    <span class="task-status"><i class="fas fa-circle-notch"></i></span>
                </div>
            </div>

            <!-- đồng hồ đếm 5 giây (ẩn) -->
            <div id="countdownDiv" class="countdown-box hidden">
                <i class="fas fa-hourglass-half"></i> Chờ <span id="timer">5</span> giây để lấy script...
            </div>

            <!-- script và copy (ẩn) -->
            <div id="scriptReveal" class="hidden">
                <div class="script-area">
                    <div class="script-box" id="scriptContent">
                        -- Blox Fruits Banana Hub (No Key) <br>
                        repeat wait() until game:IsLoaded() and game.Players.LocalPlayer <br>
                        getgenv().Team = "Marines" <br>
                        loadstring(game:HttpGet("https://raw.githubusercontent.com/obiyeueim/vthangsitink/main/BananaHub.lua"))()
                    </div>
                    <button class="copy-btn" id="copyScriptBtn">
                        <i class="fas fa-copy"></i> COPY TO CLIPBOARD <i class="fas fa-clipboard"></i>
                    </button>
                </div>
                <div class="note">
                    <i class="fas fa-skull"></i> script no key · hub hỗ trợ Blox Fruit  <i class="fas fa-red"></i>
                </div>
            </div>
        </div>

        <div class="footer">
            🛡️ ấn get banana và hoàn thành 3 bước follow nhận script ngay
        </div>
    </div>

    <script>
        (function() {
            // DOM elements
            const getBananaBtn = document.getElementById('getBananaBtn');
            const tasksSection = document.getElementById('tasksSection');
            const task1 = document.getElementById('task1');
            const task2 = document.getElementById('task2');
            const task3 = document.getElementById('task3');
            const countdownDiv = document.getElementById('countdownDiv');
            const timerSpan = document.getElementById('timer');
            const scriptReveal = document.getElementById('scriptReveal');
            const copyBtn = document.getElementById('copyScriptBtn');
            const scriptContent = document.getElementById('scriptContent');

            // Biến trạng thái
            let tasksCompleted = [false, false, false];
            let countdownInterval = null;
            let countdownActive = false;
            let canGetScript = false;

            // URL tiktok cần mở
            const tiktokVideoURL = 'https://vt.tiktok.com/ZSmBvV21y/';
            const tiktokProfile = 'https://www.tiktok.com/@hnam.script'; // dùng cho tim và follow

            // update giao diện tasks
            function updateTaskUI() {
                updateSingleTaskUI(task1, 0);
                updateSingleTaskUI(task2, 1);
                updateSingleTaskUI(task3, 2);

                // nếu cả 3 đều hoàn thành và chưa kích hoạt đếm ngược thì bắt đầu đếm
                if (tasksCompleted.every(v => v === true) && !countdownActive && !canGetScript) {
                    startCountdown();
                }
            }

            function updateSingleTaskUI(taskElement, index) {
                const statusIcon = taskElement.querySelector('.task-status i');
                if (tasksCompleted[index]) {
                    taskElement.classList.add('completed');
                    statusIcon.className = 'fas fa-check-circle';
                } else {
                    taskElement.classList.remove('completed');
                    statusIcon.className = 'fas fa-circle-notch';
                }
            }

            // mỗi task khi click (chỉ khi chưa completed)
            function handleTaskClick(e, index) {
                // nếu đã hoàn thành thì không làm gì (class completed đã ngăn click nhờ pointer-events)
                // nhưng để chắc chắn:
                if (tasksCompleted[index]) return;

                // tuỳ theo task
                if (index === 0) {
                    // task 1: follow + đăng lại video (mở link video)
                    window.open(tiktokVideoURL, '_blank');
                    // giả sử sau khi mở thì coi như hoàn thành (demo)
                } else if (index === 1) {
                    // tim và follow hnam.script (mở profile)
                    window.open(tiktokProfile, '_blank');
                } else if (index === 2) {
                    // follow lần nữa (cũng mở profile)
                    window.open(tiktokProfile, '_blank');
                }

                // đánh dấu hoàn thành (mô phỏng, trong thực tế có thể verify nhưng demo thì cho phép)
                tasksCompleted[index] = true;
                updateTaskUI();

                // kiểm tra nếu cả 3 xong thì countdown sẽ được kích từ updateTaskUI (bên trên đã gọi startCountdown nếu all true)
            }

            // Gán sự kiện click
            task1.addEventListener('click', (e) => handleTaskClick(e, 0));
            task2.addEventListener('click', (e) => handleTaskClick(e, 1));
            task3.addEventListener('click', (e) => handleTaskClick(e, 2));

            // Bắt đầu đếm ngược 5 giây
            function startCountdown() {
                if (countdownActive || canGetScript) return;
                countdownActive = true;
                countdownDiv.classList.remove('hidden');
                let seconds = 5;
                timerSpan.innerText = seconds;

                countdownInterval = setInterval(() => {
                    seconds -= 1;
                    timerSpan.innerText = seconds;

                    if (seconds <= 0) {
                        clearInterval(countdownInterval);
                        countdownInterval = null;
                        countdownActive = false;
                        canGetScript = true;
                        countdownDiv.classList.add('hidden');
                        // hiện script
                        scriptReveal.classList.remove('hidden');
                    }
                }, 1000);
            }

            // Nút GET BANANA: ẩn nút và hiện tasks
            getBananaBtn.addEventListener('click', () => {
                // reset lại trạng thái (nếu muốn dùng lại thì reset, nhưng yêu cầu không nói reset, cứ để tích lũy)
                // Tuy nhiên để demo lần đầu: nếu tasksSection chưa hiện thì hiện
                if (tasksSection.classList.contains('hidden')) {
                    tasksSection.classList.remove('hidden');
                    // reset tasks (nếu cần trải nghiệm lại) ; để ban đầu false hết
                    tasksCompleted = [false, false, false];
                    canGetScript = false;
                    if (countdownInterval) {
                        clearInterval(countdownInterval);
                        countdownInterval = null;
                    }
                    countdownActive = false;
                    countdownDiv.classList.add('hidden');
                    scriptReveal.classList.add('hidden');
                    updateTaskUI();
                }
                // nếu đã hiện rồi thì không làm gì thêm
            });

            // COPY TO CLIPBOARD
            copyBtn.addEventListener('click', async () => {
                // lấy text nội dung script (loại bỏ thẻ html <br>)
                const rawText = scriptContent.innerText; 
                // Hoặc có thể lấy từ data-attribute. nhưng innerText sẽ cho chuỗi.
                // chuẩn hóa: thay xuống dòng đúng
                const scriptRaw = `repeat wait() until game:IsLoaded() and game.Players.LocalPlayer\ngetgenv().Team = "Marines"\nloadstring(game:HttpGet("https://raw.githubusercontent.com/obiyeueim/vthangsitink/main/BananaHub.lua"))()`;
                
                try {
                    await navigator.clipboard.writeText(scriptRaw);
                    alert('✅ Đã copy script vào clipboard!');
                } catch (err) {
                    // fallback
                    const textarea = document.createElement('textarea');
                    textarea.value = scriptRaw;
                    document.body.appendChild(textarea);
                    textarea.select();
                    document.execCommand('copy');
                    document.body.removeChild(textarea);
                    alert('✅ Đã copy (phương thức dự phòng)');
                }
            });

            // khởi tạo giao diện (ẩn tasks)
            tasksSection.classList.add('hidden');
            updateTaskUI();

            // bổ sung: nếu ai đó muốn hoàn thành nhanh, có thể dev tool, nhưng demo là đủ
        })();
    </script>

    <!-- Lưu ý: ảnh đại diện dùng imgur, nếu lỗi sẽ hiện placeholder 🍌 -->
</body>
</html>
