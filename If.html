<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BBU Electricity Bill Calculator</title>
    <style>
        /* CSS resets and general body styling */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #ffffff;
        }

        /* --- Header Styling --- */
        header {
            background-color: #1a237e; /* Dark Blue */
            padding: 15px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: white;
        }
        .logo-container {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        .logo-container img {
            width: 50px; /* Adjust based on your actual logo size */
            height: auto;
        }
        .university-names h1 {
            font-size: 18px;
            font-weight: bold;
        }
        .university-names h2 {
            font-size: 14px;
            font-weight: normal;
            margin-top: 5px;
        }
        .home-btn {
            background-color: #d50000; /* Red */
            color: white;
            border: none;
            padding: 10px 30px;
            border-radius: 8px;
            font-family: 'Brush Script MT', 'Comic Sans MS', cursive;
            font-size: 24px;
            cursor: pointer;
        }

        /* --- Main Content Styling --- */
        main {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Input Section */
        .input-section {
            display: flex;
            justify-content: space-around;
            margin-bottom: 40px;
            text-align: center;
        }
        .input-group label {
            display: block;
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 15px;
        }
        .input-group input {
            width: 250px;
            padding: 15px;
            font-size: 18px;
            text-align: center;
            border: 2px solid #1a237e;
            border-radius: 30px; /* Pill shape */
            outline: none;
        }

        /* Horizontal Divider */
        hr {
            border: none;
            border-top: 1px solid #ff4d4d;
            margin-bottom: 40px;
        }

        /* Output Section */
        .output-section {
            display: flex;
            justify-content: space-around;
            gap: 20px;
        }
        .output-column {
            display: flex;
            flex-direction: column;
            gap: 20px;
            width: 45%;
        }
        .result-box {
            padding: 20px;
            border-radius: 15px;
            color: white;
            font-weight: bold;
            font-size: 18px;
            display: flex;
            justify-content: space-between;
        }
        .bg-blue {
            background-color: #1a237e;
        }
        .bg-red {
            background-color: #d50000;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <img src="RbgBBU.png" alt="BBU Logo" onerror="this.style.display='none'">
            <div class="university-names">
                <h1>Build Bright University</h1>
                <h2>សាកលវិទ្យាល័យបៀលប្រាយ</h2>
            </div>
        </div>
        <a href="index.html" class="home-btn">Home</a>
    </header>

    <main>
        <div class="input-section">
            <div class="input-group">
                <label>Previous Number (KW)</label>
                <input type="number" id="prevNum" oninput="calculateBill()" placeholder="0">
            </div>
            <div class="input-group">
                <label>Current Number (KW)</label>
                <input type="number" id="currNum" oninput="calculateBill()" placeholder="0">
            </div>
        </div>

        <hr>

        <div class="output-section">
            <div class="output-column">
                <div class="result-box bg-blue">
                    <span>Previous Number (KW):</span>
                    <span id="outPrev">0</span>
                </div>
                <div class="result-box bg-blue">
                    <span>Current Number (KW):</span>
                    <span id="outCurr">0</span>
                </div>
            </div>
            
            <div class="output-column">
                <div class="result-box bg-red">
                    <span>Used This Month:</span>
                    <span id="outUsed">0</span>
                </div>
                <div class="result-box bg-red">
                    <span>Total Payment:</span>
                    <span id="outTotal">0.00 ៛</span>
                </div>
            </div>
        </div>
    </main>

    <script>
        function calculateBill() {
            // 1. Get the values from the input fields
            let prevNum = parseFloat(document.getElementById('prevNum').value) || 0;
            let currNum = parseFloat(document.getElementById('currNum').value) || 0;
            
            // 2. Update the blue output boxes instantly
            document.getElementById('outPrev').innerText = prevNum;
            document.getElementById('outCurr').innerText = currNum;

            // 3. Calculate usage
            let used = currNum - prevNum;

            // Handle invalid input (if current reading is less than previous)
            if (used < 0) {
                document.getElementById('outUsed').innerText = "Invalid";
                document.getElementById('outTotal').innerText = "0.00 ៛";
                return; // Stop calculation
            }
            document.getElementById('outUsed').innerText = used;

            // 5. Apply the tiered pricing logic from the previous lesson
            let total = 0;
            if (used <= 10) {
                total = used * 700;
            } else if (used <= 20) {
                total = used * 800;
            } else if (used <= 30) {
                total = used * 900;
            } else {
                total = used * 1000;
            }

            // 6. Format to 2 decimal places and update the "Total Payment" box
            let formattedTotal = total.toLocaleString('en-US', {minimumFractionDigits: 2, maximumFractionDigits: 2});
            document.getElementById('outTotal').innerText = formattedTotal + " ៛";
        }
    </script>

</body>

</html>
