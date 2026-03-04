<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fumeto Reader - Privacy Policy</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            color: #e0e0e0;
            background: #121212;
            padding: 2rem 1rem;
        }
        .container {
            max-width: 720px;
            margin: 0 auto;
        }
        h1 {
            font-size: 1.75rem;
            color: #fff;
            margin-bottom: 0.25rem;
        }
        .subtitle {
            color: #888;
            font-size: 0.875rem;
            margin-bottom: 2rem;
        }
        h2 {
            font-size: 1.1rem;
            color: #fff;
            margin-top: 1.75rem;
            margin-bottom: 0.5rem;
        }
        p { margin-bottom: 0.75rem; }
        ul {
            margin: 0.5rem 0 0.75rem 1.5rem;
        }
        li { margin-bottom: 0.35rem; }
        li strong { color: #ccc; }
        .footer {
            margin-top: 3rem;
            padding-top: 1.5rem;
            border-top: 1px solid #333;
            text-align: center;
            color: #666;
            font-size: 0.8rem;
        }
        .footer a { color: #888; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Fumeto Reader</h1>
        <p class="subtitle">Privacy Policy &mdash; Effective March 1, 2026</p>

        <h2>No Data Collection</h2>
        <p>
            Fumeto Reader does not collect, transmit, or store any personal data,
            usage analytics, or telemetry. There are no analytics SDKs, crash
            reporting services, or tracking code in the app.
        </p>

        <h2>No Ads</h2>
        <p>
            The app contains no advertisements and no advertising SDKs.
        </p>

        <h2>Local Storage Only</h2>
        <p>
            All your data &mdash; imported comics, translations, settings, and
            reading progress &mdash; is stored locally on your device in the
            app's private storage. Nothing is sent to external servers unless you
            explicitly configure it.
        </p>

        <h2>User-Configured Network Access</h2>
        <p>The app only connects to the internet when you:</p>
        <ul>
            <li>Connect to a self-hosted library server (YACReader, Komga, or Kavita) that you configure</li>
            <li>Send translation requests to an LLM provider (e.g., OpenRouter) that you configure with your own API key</li>
            <li>Download the on-device TranslateGemma translation model</li>
        </ul>

        <h2>API Key Security</h2>
        <p>
            API keys you enter for translation providers are encrypted locally on
            your device using AES-256-GCM encryption. They are never transmitted
            anywhere except to the provider you configured.
        </p>

        <h2>Permissions Used</h2>
        <ul>
            <li><strong>Internet:</strong> Required for connecting to your configured library servers and translation providers.</li>
            <li><strong>Foreground Service:</strong> Used to keep batch translations running when the app is in the background.</li>
            <li><strong>Wake Lock:</strong> Prevents the device from sleeping during long-running batch translations.</li>
            <li><strong>Notifications:</strong> Shows translation progress when running in the background.</li>
        </ul>

        <h2>No Third-Party Sharing</h2>
        <p>
            Your data is never shared with, sold to, or accessible by any third party.
        </p>

        <h2>Contact</h2>
        <p>
            If you have questions about this privacy policy, you can reach the
            developer via <a href="https://github.com/DJSlapNutzDev" style="color: #7dd3fc;">GitHub</a>.
        </p>

        <div class="footer">
            <p>&copy; 2026 DJSlapNutz &mdash; <a href="https://github.com/DJSlapNutzDev">github.com/DJSlapNutzDev</a></p>
        </div>
    </div>
</body>
</html>
