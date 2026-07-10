<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - Echoes of the Abyss</title>
    <style>
        /* 全局重置与深色主题 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background: radial-gradient(circle at center, #111d33 0%, #050a12 100%);
            color: #dce6f0;
            line-height: 1.7;
            padding: 40px 20px;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* 主容器 - 模拟游戏内的弹窗卡片 */
        .container {
            max-width: 820px;
            width: 100%;
            background: rgba(11, 22, 38, 0.85);
            backdrop-filter: blur(8px);
            -webkit-backdrop-filter: blur(8px);
            border: 1px solid rgba(91, 194, 231, 0.25);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.8), inset 0 0 30px rgba(91, 194, 231, 0.05);
            border-radius: 16px;
            padding: 50px 45px;
            transition: all 0.3s ease;
        }

        /* 头部游戏标题 */
        .app-header {
            text-align: center;
            margin-bottom: 35px;
            border-bottom: 1px solid rgba(91, 194, 231, 0.15);
            padding-bottom: 25px;
        }

        .app-header h1 {
            font-size: 28px;
            font-weight: 300;
            letter-spacing: 6px;
            color: #5bc2e7;
            text-shadow: 0 0 20px rgba(91, 194, 231, 0.4);
            margin-bottom: 8px;
        }

        .app-header p {
            font-size: 14px;
            color: #7a90a8;
            letter-spacing: 1.5px;
        }

        /* 主内容区 */
        h2 {
            color: #8fe0ff;
            font-size: 18px;
            font-weight: 500;
            margin: 30px 0 15px 0;
            letter-spacing: 0.5px;
        }

        h2:first-of-type {
            margin-top: 0;
        }

        p {
            margin-bottom: 16px;
            font-size: 15px;
            color: #c6d2df;
        }

        ul {
            list-style: none;
            padding-left: 0;
            margin-bottom: 20px;
        }

        ul li {
            padding: 8px 0 8px 24px;
            position: relative;
            font-size: 15px;
            color: #c6d2df;
            border-bottom: 1px solid rgba(255, 255, 255, 0.03);
        }

        ul li:last-child {
            border-bottom: none;
        }

        /* 自定义列表项符号 (深渊水滴状) */
        ul li::before {
            content: "•";
            position: absolute;
            left: 4px;
            top: 8px;
            color: #5bc2e7;
            font-size: 18px;
        }

        strong {
            color: #ffffff;
            font-weight: 600;
        }

        /* 联系邮箱占位符高亮 */
        .email-placeholder {
            display: inline-block;
            background: rgba(91, 194, 231, 0.1);
            border: 1px solid rgba(91, 194, 231, 0.2);
            border-radius: 4px;
            padding: 2px 12px;
            font-family: monospace;
            font-size: 14px;
            color: #5bc2e7;
            margin-top: 4px;
        }

        /* 底部版权 */
        .footer {
            margin-top: 45px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            text-align: center;
            font-size: 12px;
            color: #526477;
            letter-spacing: 1px;
        }

        /* 响应式设计 (适配移动设备) */
        @media (max-width: 600px) {
            body {
                padding: 20px 12px;
                align-items: flex-start;
            }
            .container {
                padding: 25px 20px;
                border-radius: 12px;
            }
            .app-header h1 {
                font-size: 22px;
                letter-spacing: 4px;
            }
            p, ul li {
                font-size: 14px;
            }
            h2 {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- 头部标识 -->
        <div class="app-header">
            <h1>ECHOES OF THE ABYSS</h1>
            <p>Privacy Policy & Local Data Statement</p>
        </div>

        <!-- 隐私协议正文 -->
        <div class="content">
            <p><strong>Last Updated:</strong> July 10, 2026</p>
            
            <p>Welcome to <em>Echoes of the Abyss</em> ("the App"). We value your privacy and are committed to providing a secure, transparent, and worry-free experience. This Privacy Policy explains our practices regarding the collection, use, and disclosure of your information when you use the App.</p>

            <h2>1. NO DATA COLLECTION (We Collect Nothing)</h2>
            <p><em>Echoes of the Abyss</em> does <strong>not</strong> collect, store, transmit, or share any personal information or sensitive data. Specifically, we do <strong>not</strong> collect:</p>
            <ul>
                <li>Your name, email address, phone number, or physical address.</li>
                <li>Device identifiers, advertising IDs, or IP addresses.</li>
                <li>Location data (GPS or network-based).</li>
                <li>Information regarding how you use the App (usage analytics).</li>
                <li>Photos, media, or files from your device.</li>
            </ul>

            <h2>2. LOCAL-ONLY DATA PROCESSING</h2>
            <p><em>Echoes of the Abyss</em> is designed to be entirely offline and <strong>self-contained</strong>. All data generated within the game—including your current dive depth, oxygen levels, narrative progress, unlocked endings, and game settings—is stored <strong>exclusively on your own device</strong> (local storage).</p>
            <p><strong>No data is ever uploaded to our servers, cloud services, or any third-party networks.</strong> Your gameplay progress remains completely private and under your direct control.</p>

            <h2>3. NO THIRD-PARTY SERVICES</h2>
            <p>We do <strong>not</strong> integrate any third-party analytics tools, advertising SDKs, crash reporting services, or social media plugins into the App. Because there is no data to share, no external companies or services can access your information through our App.</p>

            <h2>4. PERMISSIONS</h2>
            <p>The App may request standard permissions to read/write to your device's local storage. This permission is used <strong>solely</strong> to save your local game progress and settings. The App does <strong>not</strong> require or use network access (Wi-Fi / cellular data).</p>

            <h2>5. SECURITY</h2>
            <p>Since the App operates entirely offline on your local device, there is no risk of a server-side data breach. Your security is protected by the built-in security protocols of your device's operating system. However, please be aware that no method of local storage is completely immune from local device physical access; we recommend using standard device security measures to protect your privacy.</p>

            <h2>6. CHILDREN’S PRIVACY</h2>
            <p>We do not collect information from anyone, including children under the age of 13. Because we collect no data whatsoever, the App complies with the Children's Online Privacy Protection Act (COPPA) and similar international child privacy regulations.</p>

            <h2>7. YOUR DATA RIGHTS</h2>
            <p>Because we do not collect any of your personal data:</p>
            <ul>
                <li>You have no data to request access to, correct, or delete from our servers.</li>
                <li>If you wish to completely erase all locally saved game data, you can simply uninstall <em>Echoes of the Abyss</em> from your device, which will automatically remove all associated local files. Alternatively, you can clear the App's local data in your device's system settings.</li>
            </ul>

            <h2>8. CHANGES TO THIS PRIVACY POLICY</h2>
            <p>We may update this Privacy Policy from time to time to reflect changes in our operational practices. We will post the updated policy within the App or on our official website. You are advised to review this policy periodically.</p>

            <h2>9. CONTACT US</h2>
            <p>If you have any questions or concerns regarding this Privacy Policy or the App's operation, please feel free to contact us at:</p>
            <p>
                <span class="email-placeholder">[Insert Your Developer Email Address Here]</span>
            </p>
        </div>

        <!-- 底部免责声明 -->
        <div class="footer">
            <p>&copy; 2026 Echoes of the Abyss. All rights reserved.</p>
        </div>
    </div>

</body>
</html>
