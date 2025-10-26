<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>azazaev</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Courier New', monospace;
            background: #000000;
            color: #ffffff;
            min-height: 100vh;
            overflow-x: hidden;
        }

        .background-gif {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.3;
        }

        .background-gif img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            filter: grayscale(100%) contrast(150%);
        }

        .container {
            position: relative;
            z-index: 2;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 2rem;
            background: rgba(0, 0, 0, 0.7);
        }

        .nickname {
            font-size: 4rem;
            font-weight: bold;
            margin-bottom: 3rem;
            text-shadow: 0 0 10px #ffffff, 0 0 20px #ffffff;
            animation: glow 2s ease-in-out infinite alternate;
            filter: grayscale(100%);
        }

        @keyframes glow {
            from {
                text-shadow: 0 0 10px #ffffff, 0 0 20px #ffffff;
            }
            to {
                text-shadow: 0 0 15px #ffffff, 0 0 30px #ffffff, 0 0 40px #ffffff;
            }
        }

        .music-widget {
            background: rgba(0, 0, 0, 0.95);
            border: 1px solid #ffffff;
            border-radius: 8px;
            padding: 15px;
            max-width: 300px;
            width: 100%;
            margin-bottom: 2rem;
            font-size: 12px;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.2);
        }

        .widget-header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 10px;
            padding-bottom: 8px;
            border-bottom: 1px solid #333;
        }

        .track-info {
            text-align: left;
            flex: 1;
        }

        .track-title {
            font-size: 11px;
            font-weight: bold;
            margin-bottom: 2px;
            color: #fff;
        }

        .track-artist {
            font-size: 10px;
            color: #ccc;
        }

        .player-controls {
            display: flex;
            align-items: center;
            gap: 8px;
            margin: 10px 0;
        }

        .control-btn {
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid #ffffff;
            color: #ffffff;
            width: 25px;
            height: 25px;
            border-radius: 3px;
            cursor: pointer;
            font-size: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
        }

        .control-btn:hover {
            background: rgba(255, 255, 255, 0.2);
        }

        .play-btn {
            width: 30px;
            height: 30px;
            font-size: 12px;
        }

        .progress-container {
            width: 100%;
            height: 4px;
            background: #333;
            border-radius: 2px;
            margin: 8px 0;
            cursor: pointer;
        }

        .progress-bar {
            height: 100%;
            background: #ffffff;
            border-radius: 2px;
            width: 0%;
            transition: width 0.1s ease;
        }

        .time-info {
            display: flex;
            justify-content: space-between;
            font-size: 9px;
            color: #999;
            margin-top: 5px;
        }

        .volume-control {
            display: flex;
            align-items: center;
            gap: 5px;
            margin-top: 8px;
        }

        .volume-slider {
            flex: 1;
            height: 3px;
            background: #333;
            border-radius: 1px;
            cursor: pointer;
        }

        .volume-progress {
            height: 100%;
            background: #ffffff;
            border-radius: 1px;
            width: 70%;
        }

        .terminal {
            background: rgba(0, 0, 0, 0.9);
            border: 1px solid #ffffff;
            border-radius: 10px;
            padding: 2rem;
            max-width: 500px;
            width: 100%;
            filter: grayscale(100%);
        }

        .line {
            margin: 1rem 0;
            text-align: left;
        }

        .prompt {
            color: #ffffff;
        }

        .cursor {
            animation: blink 1s infinite;
        }

        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0; }
        }

        @media (max-width: 768px) {
            .nickname {
                font-size: 2.5rem;
            }
            
            .music-widget, .terminal {
                padding: 1rem;
                max-width: 280px;
            }
        }
    </style>
</head>
<body>
    <div class="background-gif">
        <img src="https://media1.tenor.com/m/zFTUi43HePQAAAAC/flowers-beautiful-flowers.gif" alt="Background">
    </div>

    <div class="container">
        <div class="nickname">azazaev</div>
        
        <div class="music-widget">
            <div class="widget-header">
                <div class="track-info">
                    <div class="track-title">Pass Out</div>
                    <div class="track-artist">fixupboy</div>
                </div>
                <div style="font-size: 10px; color: #ccc;">♪</div>
            </div>
            
            <div class="player-controls">
                <button class="control-btn" onclick="changeTime(-10)" title="-10 sec">«</button>
                <button class="control-btn" onclick="changeTime(-5)" title="-5 sec">‹</button>
                <button class="control-btn play-btn" onclick="togglePlay()">▶</button>
                <button class="control-btn" onclick="changeTime(5)" title="+5 sec">›</button>
                <button class="control-btn" onclick="changeTime(10)" title="+10 sec">»</button>
            </div>
            
            <div class="progress-container" onclick="seekAudio(event)">
                <div class="progress-bar" id="progressBar"></div>
            </div>
            
            <div class="time-info">
                <span id="currentTime">0:00</span>
                <span id="duration">0:00</span>
            </div>
            
            <div class="volume-control">
                <span style="font-size: 9px;">🔊</span>
                <div class="volume-slider" onclick="changeVolume(event)">
                    <div class="volume-progress" id="volumeProgress"></div>
                </div>
            </div>
        </div>

        <div class="terminal">
            <div class="line">
                <span class="prompt">$</span> whoami
            </div>
            <div class="line">
                > azazaev
            </div>
            <div class="line">
                <span class="prompt">$</span> status --online
            </div>
            <div class="line">
                > available
            </div>
            <div class="line">
                <span class="prompt">$</span> _<span class="cursor">|</span>
            </div>
        </div>
    </div>

    <audio id="audioPlayer" preload="metadata">
        <source src="fixupboy_-_pass_out_(mp3.mn).mp3" type="audio/mpeg">
        Ваш браузер не поддерживает аудио элементы.
    </audio>

    <script>
        const audio = document.getElementById('audioPlayer');
        const progressBar = document.getElementById('progressBar');
        const volumeProgress = document.getElementById('volumeProgress');
        const currentTimeEl = document.getElementById('currentTime');
        const durationEl = document.getElementById('duration');
        const playBtn = document.querySelector('.play-btn');

        audio.volume = 0.7;

        function togglePlay() {
            if (audio.paused) {
                audio.play();
                playBtn.innerHTML = '⏸';
            } else {
                audio.pause();
                playBtn.innerHTML = '▶';
            }
        }

        function changeTime(seconds) {
            audio.currentTime += seconds;
        }

        function seekAudio(e) {
            const rect = e.currentTarget.getBoundingClientRect();
            const percent = (e.clientX - rect.left) / rect.width;
            audio.currentTime = percent * audio.duration;
        }

        function changeVolume(e) {
            const rect = e.currentTarget.getBoundingClientRect();
            const percent = (e.clientX - rect.left) / rect.width;
            audio.volume = percent;
            volumeProgress.style.width = (percent * 100) + '%';
        }

        audio.addEventListener('timeupdate', function() {
            if (!isNaN(audio.duration)) {
                const percent = (audio.currentTime / audio.duration) * 100;
                progressBar.style.width = percent + '%';
                
                currentTimeEl.textContent = formatTime(audio.currentTime);
                durationEl.textContent = formatTime(audio.duration);
            }
        });

        audio.addEventListener('ended', function() {
            playBtn.innerHTML = '▶';
            progressBar.style.width = '0%';
        });

        audio.addEventListener('loadedmetadata', function() {
            if (!isNaN(audio.duration)) {
                durationEl.textContent = formatTime(audio.duration);
            }
        });

        function formatTime(seconds) {
            const min = Math.floor(seconds / 60);
            const sec = Math.floor(seconds % 60);
            return `${min}:${sec < 10 ? '0' : ''}${sec}`;
        }

        document.addEventListener('DOMContentLoaded', function() {
            const elements = document.querySelectorAll('.nickname, .music-widget, .terminal');
            elements.forEach((el, index) => {
                el.style.opacity = '0';
                el.style.transform = 'translateY(20px)';
                
                setTimeout(() => {
                    el.style.transition = 'all 0.5s ease';
                    el.style.opacity = '1';
                    el.style.transform = 'translateY(0)';
                }, index * 300);
            });
        });
    </script>
</body>
</html>
