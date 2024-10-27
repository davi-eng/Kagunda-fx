# Kagunda-fx.github.io
Trading forex bainary html page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Join Deriv and Download Trading Bots</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #ffffff;
            padding-top: 20px;
            min-height: 70px;
            border-bottom: #77c4d3 3px solid;
        }
        header h1 {
            text-align: center;
            font-size: 24px;
        }
        .content {
            padding: 20px;
            background: #ffffff;
            margin-top: 20px;
        }
        .download-links {
            margin-top: 20px;
        }
        .download-links a {
            display: block;
            margin: 10px 0;
            color: #0066cc;
            text-decoration: none;
            font-weight: bold;
        }
        .chart-container {
            margin-top: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <h1>Join Deriv and Download Our Trading Bots</h1>
    </header>

    <div class="container">
        <div class="content">
            <p>Click the link below to join Deriv and start trading with us:</p>
            <a href="[https://track.deriv.com/_Xc6gqn0E0asKqFKZ7JdnQ2Nd7ZgqdRLk/1/]" target="_blank" style="color: blue; font-weight: bold;">Join Deriv</a>

            <div class="download-links">
                <h2>Download Trading Bots</h2>
                <a href="[https://github.com/toptraderke/freetradingbots]" download>Download Bot 1</a>
                <a href="[YOUR_BOT_DOWNLOAD_LINK_2]" download>Download Bot 2</a>
                <!-- Add more bot links as needed -->
            </div>

            <div class="chart-container">
                <h2>Live Market Chart</h2>
                <!-- TradingView widget -->
                <div class="tradingview-widget-container">
                    <div id="tradingview_chart"></div>
                    <script src="https://s3.tradingview.com/tv.js"></script>
                    <script>
                        new TradingView.widget({
                            "width": "100%",
                            "height": 400,
                            "symbol": "FX:EURUSD",
                            "interval": "D",
                            "timezone": "Etc/UTC",
                            "theme": "light",
                            "style": "1",
                            "locale": "en",
                            "toolbar_bg": "#f1f3f6",
                            "enable_publishing": false,
                            "allow_symbol_change": true,
                            "container_id": "tradingview_chart"
                        });
                    </script>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
