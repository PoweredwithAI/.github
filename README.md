<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team-Pioneer Spirit | Global Summit Countdown</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1d2b64, #f8cdda);
            color: #fff;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        h1 {
            margin-top: 40px;
            font-size: 2.5rem;
        }

        .sub-header {
            margin-top: 30px;
            font-size: 1.5rem;
            font-weight: normal;
        }

        .sub-header .highlight {
    font-weight: bold;
    color: #e0f7fa; /* soft cyan shade */
    border-bottom: 1px solid rgba(224, 247, 250, 0.5); /* soft underline */
    padding-bottom: 2px;
    text-shadow: none;
    animation: fadeIn 1.5s ease forwards;
    opacity: 0;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(8px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

        #countdown {
            display: flex;
            gap: 20px;
            justify-content: center;
            margin: 30px 0;
        }

        .time-box {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .number {
            font-size: 3rem;
            font-weight: bold;
        }

        .label {
            font-size: 0.8rem;
            letter-spacing: 1px;
            margin-top: 5px;
            text-transform: uppercase;
            color: #ccc;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            margin: 50px 0;
            width: 90%;
            align-items: start;
        }

        .grid-item {
            text-align: left;
        }

        .grid-item.center {
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
        }

        a img {
            transition: transform 0.3s ease;
            vertical-align: middle;
            width: 16px;
            margin-left: 5px;
        }

        a:hover img {
            transform: scale(1.2);
        }

        .github-logo {
            width: 20px;
            margin-right: 5px;
        }

        .github-text-link, .mentor-link {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .github-text-link:hover, .mentor-link:hover {
            color: #ddd;
        }

    </style>
</head>

<body>

    <h1>Team-Pioneer @ IIT Kanpur</h1>
    <h2 class="sub-header" id="message">
        Countdown to the launch of our platform at the <br>
        <span class="highlight">GCIEM’s 2025 Global Summit 🚀</span>
    </h2>

    <div id="countdown">
        <div class="time-box">
            <div class="number" id="days">00</div>
            <div class="label">DAYS</div>
        </div>
        <div class="time-box">
            <div class="number" id="hours">00</div>
            <div class="label">HOURS</div>
        </div>
        <div class="time-box">
            <div class="number" id="minutes">00</div>
            <div class="label">MINUTES</div>
        </div>
        <div class="time-box">
            <div class="number" id="seconds">00</div>
            <div class="label">SECONDS</div>
        </div>
    </div>

    <div class="grid">
        <!-- Mentors -->
        <div class="grid-item">
            <h3>Project Mentors</h3>
            <p>
                <a href="https://home.iitk.ac.in/~ketan/" class="mentor-link" target="_blank">
                    Prof. Ketan Rajawat (Electrical Engineering, IIT-K)
                    <img src="https://www.iitk.ac.in/new/images/page-images/logo/bluelog.jpg" alt="IITK">
                </a>
            </p>
            <p>
                <a href="https://www.iitk.ac.in/bsbe/index.php/sai-prasad-pydi" class="mentor-link" target="_blank">
                    Prof. Sai Prasad Pydi (Biological Sciences & Bioengineering, IIT-K)
                    <img src="https://www.iitk.ac.in/new/images/page-images/logo/bluelog.jpg" alt="IITK">
                </a>
            </p>
        </div>

        <!-- GitHub Hub -->
        <div class="grid-item center">
            <h3>Project Hub</h3>
            <p>
                <a href="https://github.com/PioneerSpirit/pharmacotherapyAI" class="github-text-link" target="_blank">
                    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" class="github-logo" alt="GitHub"> Visit GitHub Repository
                </a>
            </p>
        </div>

        <!-- Team -->
        <div class="grid-item">
            <h3>Meet the Team</h3>
            <p>Akshay Kakar
                <a href="https://www.linkedin.com/in/akakar/" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
                </a>
            </p>
            <p>Lokesh Kumar
                <a href="https://www.linkedin.com/in/lokesh-kumar-2556b02b/" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
                </a>
            </p>
            <p>Vasudev Gupta
                <a href="https://www.linkedin.com/in/guptavasudev/" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
                </a>
            </p>
            <p>Sujoy Kansabanik
                <a href="https://www.linkedin.com/in/sujoy-kansabanik-82679b10b/" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
                </a>
            </p>
            <p>Indradeep Chatterjee
                <a href="#" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
                </a>
            </p>
            <p>Neeraj Joshi
                <a href="https://www.linkedin.com/in/neeraj-joshi-8a478087/" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
                </a>
            </p>
        </div>
    </div>

    <script>
        const pitchStart = new Date("2025-04-06T00:00:00-05:00");
        const pitchEnd = new Date("2025-04-08T23:59:59-05:00");

        function updateCountdown() {
            const now = new Date();
            let message = "";
            let gap;

            if (now < pitchStart) {
                gap = pitchStart - now;
                message = "Countdown to the launch of our platform at the GCIEM’s 2025 Global Summit 🚀";
            } else if (now >= pitchStart && now <= pitchEnd) {
                message = "Pitch is ongoing! 🚀";
                document.getElementById("countdown").innerHTML = `<h2>${message}</h2>`;
                return;
            } else {
                message = "Pitch has ended! 🎉";
                document.getElementById("countdown").innerHTML = `<h2>${message}</h2>`;
                return;
            }

            const d = Math.floor(gap / (1000 * 60 * 60 * 24));
            const h = Math.floor((gap % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const m = Math.floor((gap % (1000 * 60 * 60)) / (1000 * 60));
            const s = Math.floor((gap % (1000 * 60)) / 1000);

            document.getElementById('days').innerText = String(d).padStart(2, '0');
            document.getElementById('hours').innerText = String(h).padStart(2, '0');
            document.getElementById('minutes').innerText = String(m).padStart(2, '0');
            document.getElementById('seconds').innerText = String(s).padStart(2, '0');
        }

        const interval = setInterval(updateCountdown, 1000);
    </script>

</body>

</html>
