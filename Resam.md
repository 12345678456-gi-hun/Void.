<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>V.O.I.D. Assistant (Pure HTML)</title>
</head>
<body style="background-color: #0f0f13; color: white; font-family: sans-serif; display: flex; height: 100vh; margin: 0; overflow: hidden;">

    <!-- Sidebar / Menu -->
    <div style="width: 250px; background-color: #1c1c21; border-right: 1px solid #2c2c35; display: flex; flex-direction: column;">
        <div style="padding: 20px; font-size: 1.2rem; font-weight: bold; border-bottom: 1px solid #2c2c35;">
            V.O.I.D. Menu
        </div>
        <div style="flex: 1; padding: 10px;">
            <p style="padding: 10px; background-color: #2c2c35; border-radius: 5px;">Previous Chat 1</p>
            <p style="padding: 10px; border-radius: 5px;">Previous Chat 2</p>
        </div>
        <div style="padding: 15px; border-top: 1px solid #2c2c35;">
            <button style="width: 100%; padding: 10px; background-color: #2c2c35; color: white; border: 1px solid #3a3a45; border-radius: 5px;">⚙️ Settings</button>
        </div>
    </div>

    <!-- Main Content Area -->
    <div style="flex: 1; display: flex; flex-direction: column; position: relative;">
        
        <!-- Status Bar -->
        <div style="position: absolute; top: 10px; right: 20px; font-size: 0.8rem; color: #8e8e93;">
            Wake-Word: Offline (No JavaScript)
        </div>

        <!-- Dashboard Buttons -->
        <div style="text-align: center; padding: 20px; margin-top: 50px;">
            <h1 style="font-size: 3rem; letter-spacing: 5px; margin-bottom: 30px;">V.O.I.D.</h1>
            <div style="display: flex; gap: 15px; justify-content: center;">
                <button style="padding: 15px 20px; background-color: #1c1c21; color: white; border: 1px solid #3a3a45; border-radius: 8px;">Chat with V.O.I.D.</button>
                <button style="padding: 15px 20px; background-color: #1c1c21; color: white; border: 1px solid #3a3a45; border-radius: 8px;">Deep Research</button>
                <button style="padding: 15px 20px; background-color: #1c1c21; color: white; border: 1px solid #3a3a45; border-radius: 8px;">Generate Image</button>
            </div>
        </div>

        <!-- Chat History Box -->
        <div style="flex: 1; padding: 20px; display: flex; flex-direction: column; gap: 15px; overflow-y: auto;">
            <!-- AI Message -->
            <div style="max-width: 70%; padding: 15px; border-radius: 12px; background-color: #1a3d66; align-self: flex-start;">
                V.O.I.D. Online. How can I assist you?
            </div>
            <!-- User Message -->
            <div style="max-width: 70%; padding: 15px; border-radius: 12px; background-color: #2c2c35; align-self: flex-end;">
                Hello V.O.I.D., give me an update.
            </div>
        </div>

        <!-- Input Area -->
        <div style="padding: 20px; background-color: #1c1c21; display: flex; gap: 10px; border-top: 1px solid #2c2c35;">
            <input type="text" placeholder="Message V.O.I.D..." style="flex: 1; background-color: #2c2c35; border: 1px solid #3a3a45; color: white; padding: 15px; border-radius: 8px;">
            <button style="padding: 15px 30px; background-color: #4a90e2; color: white; border: none; border-radius: 8px;">Send</button>
        </div>

    </div>
</body>
  </html>

