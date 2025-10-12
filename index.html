```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>ERIS Network Terminal</title>
<style>
/* --- Styles have been modified for new layout --- */
* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Consolas', 'Courier New', monospace; -webkit-user-select: none; user-select: none; }
body { display: flex; justify-content: center; align-items: center; min-height: 100vh; background-color: #111; }
.phone-container { width: 360px; height: 640px; border: 8px solid #1a1a1a; border-radius: 36px; background-color: #000; position: relative; overflow: hidden; box-shadow: 0 0 40px rgba(255, 0, 0, 0.4); }
.screen, .modal-overlay { position: absolute; top: 0; left: 0; width: 100%; height: 100%; opacity: 0; pointer-events: none; transition: opacity 0.5s ease-in-out; display: flex; flex-direction: column; background: radial-gradient(circle, #1a0000 0%, #000000 100%); }
.screen.visible, .modal-overlay.visible { opacity: 1; pointer-events: auto; }
.content-view { padding: 15px; z-index: 50; }
.view-header { display: flex; align-items: center; margin-bottom: 15px; flex-shrink: 0; padding: 0 5px; position: relative; } /* Added position: relative */
.back-button { background: none; border: 1px solid #888; color: #888; width: 30px; height: 30px; border-radius: 50%; cursor: pointer; font-size: 20px; line-height: 28px; text-align: center; transition: all 0.3s ease; }
.back-button:hover { border-color: #ff1a1a; color: #ff1a1a; }
.view-title { color: #e0e0e0; font-size: 20px; margin-left: 15px; text-shadow: 0 0 5px rgba(255, 255, 255, 0.3); }
.content-body { flex-grow: 1; overflow-y: auto; padding-right: 5px; }
.content-body::-webkit-scrollbar{width:4px}.content-body::-webkit-scrollbar-track{background:transparent}.content-body::-webkit-scrollbar-thumb{background:#ff1a1a;border-radius:4px}.content-body::-webkit-scrollbar-thumb:hover{background:#ff4d4d}
#login-screen{justify-content:center;align-items:center;padding:20px;z-index:100}.login-box{width:100%;text-align:center}.login-title{color:#ff1a1a;font-size:14px;letter-spacing:4px;margin-bottom:5px;text-shadow:0 0 10px #ff1a1a}.login-box input{width:80%;background:transparent;border:none;border-bottom:2px solid #555;color:#e0e0e0;padding:10px;margin-bottom:20px;font-size:18px;text-align:center;transition:all .3s ease}.login-box input:focus{outline:none;border-bottom-color:#ff1a1a;box-shadow:0 5px 15px -10px #ff1a1a}.login-box input[type=password]::-ms-reveal,.login-box input[type=password]::-ms-clear{display:none}.login-button{background:transparent;border:2px solid #ff1a1a;color:#ff1a1a;padding:10px 30px;cursor:pointer;font-size:16px;letter-spacing:2px;transition:all .3s ease;box-shadow:0 0 10px rgba(255,26,26,.5)}.login-button:hover{background:#ff1a1a;color:#000;box-shadow:0 0 20px #ff1a1a}#welcome-screen{justify-content:center;align-items:center;z-index:90}#welcome-message{color:#ff1a1a;font-size:1.2em;letter-spacing:3px;text-shadow:0 0 5px #ff1a1a,0 0 10px #ff1a1a,0 0 15px #ff1a1a;animation:glitch 1.5s linear infinite}@keyframes glitch{2%,64%{transform:translate(2px,0) skew(0deg)}4%,60%{transform:translate(-2px,0) skew(0deg)}62%{transform:translate(0,0) skew(5deg)}}#main-platform{padding:20px;justify-content:space-between;flex-direction:column}
.welcome-header{color:#e0e0e0;font-size:18px;text-align:center;margin-bottom:20px;text-shadow:0 0 5px rgba(255,255,255,.3);flex-shrink:0}.welcome-header span{color:#ff4d4d;font-weight:bold}
#main-platform-content { width: 100%; flex-grow: 1; display:flex; justify-content: center; align-items:center;}
#main-grid-container { display: grid; width: 100%; grid-template-columns: repeat(2, 1fr); gap: 20px; align-content: center; padding: 20px; }
.nav-button{background:rgba(26,26,26,.5);border:1px solid #444;border-radius:12px;padding:20px;display:flex;flex-direction:column;align-items:center;justify-content:center;cursor:pointer;transition:all .3s ease;backdrop-filter:blur(5px)}.nav-button:hover:not(.disabled){transform:translateY(-5px);border-color:#ff1a1a;box-shadow:0 0 20px rgba(255,26,26,.4)}.nav-button svg{width:48px;height:48px;fill:#ccc;margin-bottom:12px;transition:fill .3s ease}.nav-button:hover:not(.disabled) svg{fill:#ff1a1a}.nav-button span{color:#ccc;font-size:14px;text-align:center;transition:color .3s ease}.nav-button:hover:not(.disabled) span{color:#ff1a1a}
.nav-button.disabled{opacity:.4;cursor:not-allowed;background:rgba(10,10,10,.5);border-color:#2a2a2a}.nav-button.disabled:hover{transform:none;border-color:#2a2a2a;box-shadow:none}.nav-button.disabled svg{fill:#666}.nav-button.disabled span{color:#666}
.shop-item-card { background: rgba(10, 10, 10, 0.8); border: 1px solid #333; padding: 15px; margin-bottom: 12px; border-radius: 8px; transition: all .3s ease; display: flex; flex-direction: column; }
.shop-item-card:hover { border-color: #f2c94c; background: rgba(30, 25, 10, 0.7); }
.item-content { flex-grow: 1; }
.item-header { display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 10px; }
.item-name { color: #eee; font-size: 16px; font-weight: bold;}
.item-price { color: #f2c94c; font-size: 14px; }
.item-description { color: #aaa; font-size: 13px; line-height: 1.5; margin-bottom: 12px; }
.item-stock { color: #888; font-size: 12px; text-align: right; margin-bottom: 15px; }
.stock-rare { color: #e74c3c; font-weight:bold; }
.stock-common { color: #27ae60; }
.buy-button { background: #f2c94c; color: #000; border: none; padding: 8px 15px; border-radius: 5px; cursor: pointer; font-size: 14px; font-weight: bold; align-self: flex-end; transition: background .3s; }
.buy-button:hover { background: #ffeb99; }
#loading-view { justify-content: center; align-items: center; gap: 20px; z-index: 150; }
#loading-text { font-size: 1em; color: #ff1a1a; text-shadow: 0 0 10px #ff1a1a; text-align: center; letter-spacing: 1px; }
.loader { width: 60px; height: 60px; border: 4px solid #555; border-top-color: #ff1a1a; border-radius: 50%; animation: spin 1s linear infinite; }
@keyframes spin { to { transform: rotate(360deg); } }
.modal-overlay { justify-content: center; align-items: center; background: rgba(0,0,0,0.7); z-index: 200; backdrop-filter: blur(5px); }
.modal-content { background: #1a1a1a; border: 1px solid #444; border-radius: 10px; padding: 25px; width: 90%; text-align: center; box-shadow: 0 0 20px rgba(0,0,0,0.5); }
.modal-content h3 { color: #ff4d4d; font-size: 18px; margin-bottom: 20px; }
.modal-content p { color: #ccc; font-size: 14px; line-height: 1.6; margin-bottom: 25px; }
.modal-content .modal-button, .modal-content button { background: #ff1a1a; color: #000; border: none; padding: 10px 25px; border-radius: 5px; cursor: pointer; font-size: 16px; font-weight: bold; transition: background .3s; }
.modal-content .modal-button:hover, .modal-content button:hover { background: #ff4d4d; }
.delivery-option-button{display:block;width:100%;background:transparent;border:1px solid #888;color:#ccc;padding:12px;margin-bottom:15px;border-radius:5px;cursor:pointer;transition:all .3s}.delivery-option-button:hover{border-color:#f2c94c;background:rgba(242,201,76,.1);color:#f2c94c}.delivery-option-button .fee{font-size:12px;color:#888;display:block;margin-top:4px}
#cleaner-delivery-modal .setup-field{margin-bottom:15px;text-align:left}#cleaner-delivery-modal .setup-field label{font-size:12px}#cleaner-delivery-modal .setup-field input{text-align:left;padding:8px 12px}
#career-setup-view { justify-content: center; align-items: center; padding: 20px; text-align: center; z-index: 60; }
.setup-box { background: rgba(20, 20, 20, 0.8); padding: 30px; border-radius: 10px; border: 1px solid #444; }
.setup-box h3 { color: #ff4d4d; margin-bottom: 25px; font-size: 18px; letter-spacing: 1px; }
.setup-field { margin-bottom: 20px; }
.setup-field label { display: block; color: #aaa; font-size: 14px; margin-bottom: 8px; }
.setup-field input { width: 100%; background: #111; border: 1px solid #555; color: #ddd; padding: 10px; border-radius: 5px; font-size: 16px; text-align: center; }
.setup-field input:focus { outline: none; border-color: #ff1a1a; }
.setup-box .confirm-button { background: #ff1a1a; color: #000; border: none; padding: 12px 30px; border-radius: 5px; cursor: pointer; font-size: 16px; font-weight: bold; transition: background .3s; }
.setup-box .confirm-button:hover { background: #ff4d4d; }
.public-channel-message { display: flex; margin-bottom: 12px; max-width: 95%; align-self: flex-start; background: #222; padding: 8px 12px; border-radius: 8px; border-left: 3px solid #555;}
.public-channel-message .meta { font-size: 12px; color: #888; margin-bottom: 5px; }
.public-channel-message .content { font-size: 14px; color: #ddd; line-height: 1.5; word-wrap: break-word; }
.username-clickable { color: #4da6ff; cursor: pointer; text-decoration: none; }
.username-clickable:hover { text-decoration: underline; }
.chat-input-area { flex-shrink: 0; display: flex; gap: 10px; padding: 10px 5px 5px 5px; border-top: 1px solid #333; }
.chat-input-area input { flex-grow: 1; background-color: #1a1a1a; border: 1px solid #444; color: #ddd; padding: 10px; border-radius: 20px; font-size: 14px; }
.chat-input-area input:focus { outline: none; border-color: #ff1a1a; }
.chat-input-area button { background-color: #ff1a1a; color: #000; border: none; font-weight: bold; border-radius: 50%; width: 40px; height: 40px; cursor: pointer; flex-shrink: 0;transition: background-color .3s ease; }
.chat-input-area button:hover { background-color: #ff4d4d; }
.chat-content-container { flex-grow: 1; display:flex; flex-direction:column-reverse; overflow-y: auto; padding-right: 5px; }
#private-chat-messages-specific {flex-direction: column;}
#public-channel-messages {flex-direction: column;}
.message-item { display: flex; margin-bottom: 12px; max-width: 90%; align-self: flex-start; }
.message-item.user-message { align-self: flex-end; flex-direction: row-reverse; }
.message-meta { font-size: 11px; color: #888; margin: 0 8px 4px 8px; }
.user-message .message-meta { text-align: right; }
.message-bubble { padding: 8px 12px; border-radius: 12px; font-size: 14px; line-height: 1.5; word-wrap: break-word; }
.other-message .message-bubble { background: #262626; color: #ddd; border-top-left-radius: 2px; }
.user-message .message-bubble { background: #4a2525; color: #f0f0f0; border-top-right-radius: 2px; }
.typing-indicator { font-style: italic; color: #888; font-size: 13px; padding: 10px; }
.context-message { font-size: 12px; color: #888; text-align: center; margin: 10px auto; padding: 5px 10px; background-color: #222; border-radius: 10px; width: 80%; }
#private-chat-list { display: flex; flex-direction: column; }
.chat-list-item { background: rgba(26,26,26,.7); padding: 12px 15px; border-bottom: 1px solid #333; cursor: pointer; transition: background .3s ease, transform 0.2s; position: relative; overflow: hidden; }
.chat-list-item:hover { background: rgba(40,20,20,.7); }
.chat-list-item.deleting { transform: translateX(-100%); opacity: 0; transition: transform 0.4s ease, opacity 0.4s ease; }
.delete-progress { position: absolute; bottom: 0; left: 0; height: 3px; background-color: #ff1a1a; width: 0%; transition: width 0.1s linear; }
.chat-list-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 6px; }
.chat-list-sender { color: #ff4d4d; font-weight: bold; font-size: 16px; }
.chat-list-time { color: #888; font-size: 12px; }
.chat-list-last-msg { color: #aaa; font-size: 14px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
.mission-card{background:rgba(26,26,26,.7);border-left:3px solid #666;padding:15px;margin-bottom:12px;border-radius:4px;transition:all .3s ease}.mission-card:hover{border-left-color:#ff1a1a;background:rgba(40,20,20,.7)}.mission-title{color:#eee;font-size:16px;margin-bottom:5px}.mission-publisher{color:#aaa;font-size:12px;margin-bottom:10px}.mission-publisher span{color:#ff4d4d}.mission-description{color:#ccc;font-size:13px;margin-bottom:12px;border-left:2px solid #555;padding-left:10px}.mission-meta{display:flex;justify-content:space-between;align-items:center;font-size:12px}.mission-reward,.mission-difficulty{color:#aaa}.mission-reward{color:#f2c94c}.mission-status-open{color:#27ae60}.mission-status-locked{color:#e74c3c}
.view-details-button{background:transparent;border:1px solid #888;color:#888;padding:5px 10px;font-size:12px;border-radius:4px;cursor:pointer;margin-top:15px;transition:all .3s ease}.view-details-button:hover{background:#ff1a1a;color:#000;border-color:#ff1a1a}.view-details-button:disabled{border-color:#444;color:#444;cursor:not-allowed;background:transparent}
#mission-detail-content,#mission-contact-content{padding:10px;color:#ccc}.detail-section{margin-bottom:20px}.detail-section h4{color:#ff4d4d;font-size:14px;border-bottom:1px solid #555;padding-bottom:5px;margin-bottom:10px;letter-spacing:1px}.detail-section p,.detail-line{margin-bottom:8px;font-size:14px;line-height:1.6}.detail-line{display:flex}.detail-line strong{color:#aaa;width:85px;flex-shrink:0}.reputation-stars{color:#f2c94c;letter-spacing:2px}.special-requirement{color:#ff9999;border:1px dashed #7c2424;padding:10px;border-radius:4px;background:rgba(255,0,0,.05)}.mission-detail-footer{text-align:center;margin-top:20px;padding-top:20px;border-top:1px solid #333}.action-button{background:transparent;border:2px solid #27ae60;color:#27ae60;padding:12px 40px;cursor:pointer;font-size:16px;letter-spacing:2px;transition:all .3s ease;box-shadow:0 0 10px rgba(39,174,96,.5);border-radius:5px}.action-button:hover{background:#27ae60;color:#000;box-shadow:0 0 20px #27ae60}.action-button.red-action{border-color:#e74c3c;color:#e74c3c;box-shadow:0 0 10px rgba(231,76,60,.5)}.action-button.red-action:hover{background:#e74c3c;color:#000;border-color:#e74c3c;box-shadow:0 0 20px #e74c3c}
#mission-contact-content{display:none}
.view-toggle-btn { position: absolute; right: 5px; top: 50%; transform: translateY(-50%); background: transparent; border: 1px solid #888; color: #888; padding: 5px 10px; font-size: 12px; border-radius: 4px; cursor: pointer; transition: all 0.3s ease; }
.view-toggle-btn:hover { border-color: #ff1a1a; color: #ff1a1a; }
#acceptance-view, #data-packet-view { justify-content: center; align-items: center; text-align: center; z-index: 70; }
.acceptance-message { color: #27ae60; font-size: 24px; text-shadow: 0 0 10px #27ae60; letter-spacing: 2px; }
.acceptance-message span { display: block; font-size: 14px; color: #ccc; margin-top: 15px; text-shadow: none; }
#view-info-btn { background: transparent; border: 2px solid #f2c94c; color: #f2c94c; padding: 10px 30px; margin-top: 30px; font-size: 16px; cursor: pointer; transition: all 0.3s ease; box-shadow: 0 0 15px rgba(242, 201, 76, 0.5); display: none; }
#view-info-btn:hover { background: #f2c94c; color: #000; }
#data-packet-content { width: calc(100% - 20px); color: #27ae60; font-size: 14px; white-space: pre-wrap; text-align: left; height: 80%; border: 1px solid #333; padding: 15px; background: rgba(39, 174, 96, 0.05); }
#data-packet-content::after { content: "▋"; animation: blink 1s step-end infinite; }
@keyframes blink { 50% { opacity: 0; } }
#home-button-container { position: absolute; bottom: 0; left: 0; width: 100%; height: 50px; display: flex; justify-content: center; align-items: center; z-index: 250; }
</style>
</head>
<body>

<div class="phone-container">
    <div id="login-screen" class="screen visible"> <div class="login-box"> <h2 class="login-title">ERIS NETWORK TERMINAL</h2> <input type="text" id="username" placeholder="[ USERNAME ]" autocomplete="off"> <input type="password" id="password" placeholder="[ PASSWORD ]"> <button class="login-button" onclick="handleLogin()">ACCESS</button> </div> </div>
    <div id="welcome-screen" class="screen"> <h2 id="welcome-message"></h2> </div>

    <div id="main-platform" class="screen">
        <div class="welcome-header"> 已连接, <span id="welcome-user-main"></span>. </div>
        <div id="main-platform-content">
            <div id="main-grid-container">
                <div id="nav-btn-mall" class="nav-button" onclick="showMallCategories(true, event)"> <svg viewBox="0 0 24 24"><path d="M7 18c-1.1 0-1.99.9-1.99 2S5.9 22 7 22s2-.9 2-2-.9-2-2-2zM1 2v2h2l3.6 7.59-1.35 2.44C4.52 15.37 5.24 17 6.5 17H20v-2H6.5c-.32 0-.58-.23-.65-.54l.01-.01L7.1 12h8.55c.75 0 1.41-.41 1.75-1.03l3.58-6.49A1.003 1.003 0 0020.27 3H5.21L4.27 1H1zm16 16c-1.1 0-1.99.9-1.99 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"/></svg> <span>佣兵商场</span> </div>
                <div id="nav-btn-missions" class="nav-button" onclick="showMissionPlatform(true, event)"> <svg viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-1-13h2v6h-2zm0 8h2v2h-2z"/></svg> <span>任务平台</span> </div>
                <div id="nav-btn-chats" class="nav-button" onclick="showPrivateChatList(true, event)"> <svg viewBox="0 0 24 24"><path d="M20 2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zM9 11H7V9h2v2zm4 0h-2V9h2v2zm4 0h-2V9h2v2z"/></svg> <span>私聊</span> </div>
                <div id="nav-btn-public" class="nav-button" onclick="showPublicChannel(true, event)"> <svg viewBox="0 0 24 24"><path d="M16 11c1.66 0 2.99-1.34 2.99-3S17.66 5 16 5c-1.66 0-3 1.34-3 3s1.34 3 3 3zm-8 0c1.66 0 2.99-1.34 2.99-3S9.66 5 8 5C6.34 5 5 6.34 5 8s1.34 3 3 3zm0 2c-2.33 0-7 1.17-7 3.5V19h14v-2.5c0-2.33-4.67-3.5-7-3.5zm8 0c-.29 0-.62.02-.97.05 1.16.84 1.97 1.97 1.97 3.45V19h6v-2.5c0-2.33-4.67-3.5-7-3.5z"/></svg> <span>公共频道</span> </div>
            </div>
        </div>
        <div style="height: 50px; flex-shrink:0;"></div> <!-- Placeholder to balance welcome-header -->
    </div>
    <div id="loading-view" class="screen content-view"> <div class="loader"></div> <p id="loading-text">正在从量子纠缠网络中检索数据...</p> </div>
    <div id="mission-report-modal" class="modal-overlay"> <div class="modal-content"> <h3 id="report-modal-title">任务完成</h3> <p id="report-modal-content">报告内容...</p> <p style="font-weight: bold; color: #27ae60;" id="report-modal-reward">奖励: ...</p> <button class="modal-button" onclick="closeReportModal()">关闭</button> </div> </div>
    <div id="delivery-options-modal" class="modal-overlay"> <div class="modal-content"> <h3>选择配送方式</h3><p id="delivery-item-info" style="margin-bottom: 10px;"></p><p id="delivery-total-cost" style="font-size: 16px; color: #f2c94c;"></p><div style="margin-top: 25px;"><button id="delivery-option-deaddrop" class="delivery-option-button" onclick="initiatePurchase('dead_drop')">死信箱<span class="fee"></span></button><button id="delivery-option-cleaner" class="delivery-option-button" onclick="initiatePurchase('cleaner')">'清道夫'直送<span class="fee"></span></button></div><button style="margin-top: 10px; background: transparent; border: 1px solid #888; color: #888;" onclick="closeAllModals()">取消</button></div> </div>
    <div id="cleaner-delivery-modal" class="modal-overlay"> <div class="modal-content"> <h3>'清道夫'直送详情</h3> <div class="setup-field"><label for="cleaner-address">交货地址</label><input type="text" id="cleaner-address" placeholder="例如：7区，锈蚀小巷，3号垃圾箱后"></div> <div class="setup-field"><label for="cleaner-time">接头时间</label><input type="text" id="cleaner-time" placeholder="例如：今晚午夜，或 3小时后"></div><div class="setup-field"><label for="cleaner-method">接头暗号</label><input type="text" id="cleaner-method" placeholder="例如：'我来找我的猫' / '雨还在下'"></div> <button class="modal-button" onclick="handleCleanerFormSubmit()">确认并支付</button><button style="margin-top: 10px; background: transparent; border: 1px solid #888; color: #888;" onclick="closeAllModals()">取消</button></div> </div>
    <div id="purchase-status-modal" class="modal-overlay"> <div class="modal-content"> <h3 id="purchase-status-title"></h3> <p id="purchase-status-message"></p> <button class="modal-button" onclick="closeAllModalsAndRefreshLists()">关闭</button> </div> </div>
    <div id="content-views-container">
        <div id="mission-platform-view" class="screen content-view"> <div class="view-header"> <button class="back-button" onclick="showMainMenu()">‹</button> <h2 class="view-title">任务平台</h2> </div> <div id="mission-list" class="content-body"></div> </div>
        <div id="public-channel-view" class="screen content-view"> <div class="view-header"> <button class="back-button" onclick="showMainMenu()">‹</button> <h2 class="view-title">公共频道</h2></div> <div id="public-channel-messages" class="chat-content-container"></div> <div class="chat-input-area"> <input type="text" id="public-channel-input" placeholder="广播消息..."> <button onclick="sendPublicMessage()">➤</button> </div> </div>
        <div id="private-chat-list-view" class="screen content-view"> <div class="view-header"> <button class="back-button" onclick="showMainMenu()">‹</button> <h2 class="view-title">私聊</h2> </div> <div id="private-chat-list" class="content-body"></div> </div>
        <div id="private-chat-specific-view" class="screen content-view"> <div class="view-header"> <button class="back-button" onclick="backFromPrivateChat()">‹</button> <h2 id="private-chat-contact-name" class="view-title"></h2> </div> <div id="private-chat-messages-specific" class="chat-content-container"></div> <div class="chat-input-area"> <input type="text" id="private-chat-input" placeholder="输入消息... (空内容点击发送以请求回复)"> <button onclick="sendPrivateMessage()">➤</button> </div> </div>
        <div id="career-setup-view" class="screen"> <div class="setup-box"> <h3>创建您的佣兵档案</h3> <p style="color:#aaa; font-size:14px; margin: -15px 0 25px 0;">档案是您在暗网中行动的基础。</p> <div class="setup-field"> <label for="initial-earnings">初始佣金 (联邦币)</label> <input type="number" id="initial-earnings" placeholder="例如: 5000" value="5000"> </div> <div class="setup-field"> <label for="initial-missions">初始已完成任务数</label> <input type="number" id="initial-missions" placeholder="例如: 3" value="3"> </div> <button class="confirm-button" onclick="handleCareerSetupConfirm()">确认并生成档案</button> </div> </div>
        <div id="mission-detail-view" class="screen content-view">
            <div class="view-header">
                <button id="mission-detail-back-btn" class="back-button" onclick="showMissionPlatform(false)">‹</button>
                <h2 id="mission-detail-title" class="view-title">任务详情</h2>
                <button id="mission-view-toggle-btn" class="view-toggle-btn" onclick="toggleDetailView()" style="display:none;">切换</button>
            </div>
            <div class="content-body">
                <div id="mission-detail-content"></div>
                <div id="mission-contact-content"></div>
                <div class="mission-detail-footer">
                    <button id="accept-mission-button" class="action-button" onclick="acceptMission()">接受任务</button>
                    <button id="submit-mission-button" class="action-button red-action" style="display:none;" onclick="submitCurrentMission()">提交任务</button>
                </div>
            </div>
        </div>
        <div id="mall-categories-view" class="screen content-view">
            <div class="view-header"> <button class="back-button" onclick="showMainMenu()">‹</button> <h2 class="view-title">佣兵商场</h2> </div>
            <div class="content-body" style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; padding: 10px;">
                <div class="nav-button" onclick="showMallItemList('武器与弹药')"> <svg viewBox="0 0 24 24"><path d="M20.57 4.22c-.17-.17-.39-.27-.62-.27H4.05c-.23 0-.44.09-.62.27L2 5.61V18h2V7.43l2-1.43h12l2 1.43V18h2V5.61l-1.43-1.39zM12 9c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6zm0 10c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4z"/></svg> <span>武器与弹药</span> </div>
                <div class="nav-button" onclick="showMallItemList('义体与改装')"> <svg viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-2-9c0-1.1.9-2 2-2s2 .9 2 2v2c0 1.1-.9 2-2 2s-2-.9-2-2v-2zm-3-1l1.5-1.5 1.41 1.41L8.5 9.41 7.5 10.5zm7.59-1.41L16.5 7.5l-1.41 1.41 1.41 1.42 1.09-1.09zM8.5 15.59L7.09 14.5l-1.09 1.09L7.41 17l1.09-1.41zM15.5 14.5l1.41 1.09-1.41 1.41-1.09-1.09L15.5 14.5z"/></svg> <span>义体与改装</span> </div>
                <div class="nav-button" onclick="showMallItemList('情报')"> <svg viewBox="0 0 24 24"><path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8z"/><path d="M12.5 7H11v6l5.25 3.15.75-1.23-4.5-2.67z"/></svg> <span>情报</span> </div>
                <div class="nav-button" onclick="showMallItemList('后勤与服务')"> <svg viewBox="0 0 24 24"><path d="M21.99 4c0-1.1-.89-2-1.99-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h14l4 4-.01-18zM17 14H7c-.55 0-1-.45-1-1s.45-1 1-1h10c.55 0 1 .45 1 1s-.45 1-1 1zm-4-4H7c-.55 0-1-.45-1-1s.45-1 1-1h6c.55 0 1 .45 1 1s-.45 1-1 1z"/></svg> <span>后勤与服务</span> </div>
            </div>
        </div>
        <div id="mall-item-list-view" class="screen content-view">
            <div class="view-header"> <button class="back-button" onclick="showMallCategories(false)">‹</button> <h2 id="mall-item-list-title" class="view-title">商品列表</h2> </div>
            <div id="mall-item-list-content" class="content-body"></div>
        </div>
    </div>
    <div id="acceptance-view" class="screen">
        <p class="acceptance-message">
            任务已锁定
            <span id="countdown-message">正在同步加密信道... 倒计时 <span id="timer">5</span></span>
        </p>
        <button id="view-info-btn" class="info-button" onclick="viewDataPacket()">读取数据包</button>
    </div>
    <div id="data-packet-view" class="screen content-view">
        <div class="view-header">
            <button class="back-button" onclick="showActiveMissionDetail()">‹</button>
            <h2 class="view-title">加密数据包</h2>
        </div>
        <div id="data-packet-content" class="content-body"></div>
    </div>

    <!-- Removed the home button / sync button container -->
</div>

<audio id="clickSound" src="https://assets.mixkit.co/active_storage/sfx/2568/2568-preview.mp3" preload="auto"></audio>
<audio id="accessSound" src="https://assets.mixkit.co/sfx/preview/mixkit-sci-fi-interface-zoom-994.mp3" preload="auto"></audio>
<audio id="acceptSound" src="https://assets.mixkit.co/sfx/preview/mixkit-futuristic-secure-interface-beep-921.mp3" preload="auto"></audio>
<audio id="deleteSound" src="https://assets.mixkit.co/sfx/preview/mixkit-small-hit-in-a-game-2072.mp3" preload="auto"></audio>
<audio id="purchaseSound" src="https://assets.mixkit.co/sfx/preview/mixkit-futuristic-payment-processing-1927.mp3" preload="auto"></audio>
<audio id="errorSound" src="https://assets.mixkit.co/sfx/preview/mixkit-gaming-lock-2848.mp3" preload="auto"></audio>

<script>
// --- CORE VARIABLES ---
let currentUsername = "Operator",  currentContactData = '', currentMissionId = null, currentPrivateChatContact = '', privateChatOrigin = 'chat_list';
let appState = { careerProfile: null, activeChats: {}, purchaseHistory: [] };
let tempPurchaseData = {};

// --- CONSTANTS ---
const DATA_WRAPPER_START = '<!-- ERIS_STATE_BEGIN -->';
const DATA_WRAPPER_END = '<!-- ERIS_STATE_END -->';
const LAST_USERNAME_KEY = 'eris_last_username';
const DEAD_DROP_FEE = 1500;
const CLEANER_FEE = 10000;

// --- AUDIO ---
const clickSound = document.getElementById("clickSound"), accessSound = document.getElementById("accessSound"), acceptSound = document.getElementById("acceptSound"), deleteSound = document.getElementById("deleteSound"), purchaseSound = document.getElementById("purchaseSound"), errorSound = document.getElementById("errorSound");
function playClickSound() { clickSound.currentTime = 0; clickSound.play().catch(e => {}); }
function playAcceptSound() { acceptSound.currentTime = 0; acceptSound.play().catch(e => {}); }
function playDeleteSound() { deleteSound.currentTime = 0; deleteSound.play().catch(e => {}); }

// --- UI & NAVIGATION ---
function showView(viewId) { document.querySelectorAll(".screen:not(.modal-overlay)").forEach(e => e.classList.remove("visible")); const view = document.getElementById(viewId); if (view) view.classList.add("visible"); else if (viewId) console.error(`View with ID "${viewId}" not found.`); }
function showModal(modalId) { const modal = document.getElementById(modalId); if(modal) modal.classList.add("visible"); }
function hideModal(modalId) { const modal = document.getElementById(modalId); if(modal) modal.classList.remove("visible"); }
function closeAllModals() { document.querySelectorAll('.modal-overlay').forEach(m => m.classList.remove('visible')); }
function scrollToBottom(element) { if(element) element.scrollTop = element.scrollHeight; }
function handleAIFailure(message, fallbackAction) { alert(`错误: ${message}\n\n即将返回上一界面。`); document.getElementById('loading-view').classList.remove('visible'); if (fallbackAction && typeof fallbackAction === 'function') fallbackAction(); else { console.error("No fallback action provided!"); showMainMenu(); } }
function typewriterEffect(element, data, onComplete = null) { let lineIndex = 0, charIndex = 0; (function type() { if (lineIndex < data.length) { if (charIndex < data[lineIndex].length) { element.innerHTML += data[lineIndex].charAt(charIndex); charIndex++; setTimeout(type, 20); } else { lineIndex++; charIndex = 0; setTimeout(type, 100); } } else if (onComplete) onComplete(); })(); }


// =========================================================================
// +++ 新增：世界书交互辅助函数 +++
// =========================================================================

/**
 * 更新或创建一个世界书条目
 * @param {string} entryName - 世界书条目的名称, e.g., '用户信息'
 * @param {string} content - 要写入的内容
 */
async function updateWorldBookEntry(entryName, content) {
    try {
        // SillyTavern的setLorebookEntries可以自动创建或覆盖同名条目
        await setLorebookEntries(world_name, [{
            name: entryName,
            content: content,
            // 你可以根据需要添加其他参数，如 keys, position 等
        }]);
        console.log(`[WB] World book entry '${entryName}' updated successfully.`);
    } catch (error) {
        console.error(`[WB] Failed to update world book entry '${entryName}':`, error);
        alert(`错误：无法更新世界书条目 '${entryName}'。`);
    }
}

/**
 * 读取一个世界书条目的内容
 * @param {string} entryName - 世界书条目的名称
 * @returns {Promise<string|null>} - 返回条目内容，如果找不到则返回null
 */
async function readWorldBookEntry(entryName) {
    try {
        const entries = await getLorebookEntries(world_name);
        const entry = entries.find(e => e.name === entryName);
        if (entry) {
            console.log(`[WB] Read content from '${entryName}'.`);
            return entry.content;
        } else {
            console.log(`[WB] World book entry '${entryName}' not found.`);
            return null;
        }
    } catch (error) {
        console.error(`[WB] Failed to read world book entry '${entryName}':`, error);
        return null; // 出错时也返回null
    }
}

/**
 * 从INI格式的字符串中解析数据
 * @param {string} content - "key=value" 格式的字符串
 * @returns {Object} - 解析后的数据对象
 */
function parseIniFromString(content) {
    const data = {};
    if (!content) return data;
    content.split('\n').forEach(line => {
        const parts = line.split('=');
        if (parts.length === 2) {
            data[parts[0].trim()] = parts[1].trim();
        }
    });
    return data;
}

// =========================================================================
// --- AI & DATA (State management is unchanged) ---
// =========================================================================
function serializeAppState() { let careerXml = ''; if (appState.careerProfile) { let profile = appState.careerProfile; let currentTaskXml = ''; if (profile.currentTask) { currentTaskXml = ` <currentTask> <id>${profile.currentTask.id}</id> <title>${btoa(unescape(encodeURIComponent(profile.currentTask.title)))}</title> <briefingHtml>${btoa(unescape(encodeURIComponent(profile.currentTask.briefingHtml)))}</briefingHtml> <contactData>${btoa(unescape(encodeURIComponent(profile.currentTask.contactData)))}</contactData> </currentTask>`; } careerXml = `<eris_career> <summary>评级: ${profile['评级'] || 'N/A'}, 佣金: ${profile['佣金'] || 0}, 任务接取: ${profile['任务接取'] || 0}, 任务完成: ${profile['任务完成'] || 0}, 任务失败: ${profile['任务失败'] || 0}</summary>${currentTaskXml} </eris_career>`; } let chatsXml = ''; if (appState.activeChats && Object.keys(appState.activeChats).length > 0) { let chatContacts = ''; for (const sender in appState.activeChats) { const chat = appState.activeChats[sender]; chatContacts += `<contact sender="${sender}"> <history>${btoa(unescape(encodeURIComponent(chat.history)))}</history> <last_message>${btoa(unescape(encodeURIComponent(chat.last_message)))}</last_message> <last_time>${chat.last_time}</last_time> </contact>\n`; } chatsXml = `<eris_chats>\n${chatContacts}</eris_chats>`; } let purchasesXml = ''; if (appState.purchaseHistory && appState.purchaseHistory.length > 0) { purchasesXml = `<eris_ledger>${btoa(unescape(encodeURIComponent(JSON.stringify(appState.purchaseHistory))))}</eris_ledger>`; } return `${DATA_WRAPPER_START}\n${careerXml}\n${chatsXml}\n${purchasesXml}\n${DATA_WRAPPER_END}`; }
function parseAndUpdateAppState(aiResponse) { const dataMatch = aiResponse.match(new RegExp(`${DATA_WRAPPER_START}([\\s\\S]+?)${DATA_WRAPPER_END}`)); if (!dataMatch) { console.warn("[STATE] No persistent data block found in AI response. State is not updated."); return; } const dataContent = dataMatch[1]; const profileMatch = dataContent.match(/<eris_career>([\s\S]+?)<\/eris_career>/); if (profileMatch) { const profileContent = profileMatch[1]; const summaryMatch = profileContent.match(/<summary>([\s\S]+?)<\/summary>/); const newProfile = {}; if (summaryMatch) { summaryMatch[1].split(',').forEach(pair => { const parts = pair.split(':'); if (parts.length > 1) newProfile[parts[0].trim()] = parts.slice(1).join(':').trim(); }); } const taskMatch = profileContent.match(/<currentTask>([\s\\S]+?)<\/currentTask>/); if (taskMatch) { try { newProfile.currentTask = { id: (taskMatch[1].match(/<id>([^<]+)<\/id>/) || [])[1], title: decodeURIComponent(escape(atob((taskMatch[1].match(/<title>([^<]+)<\/title>/) || [])[1]))), briefingHtml: decodeURIComponent(escape(atob((taskMatch[1].match(/<briefingHtml>([^<]+)<\/briefingHtml>/) || [])[1]))), contactData: decodeURIComponent(escape(atob((taskMatch[1].match(/<contactData>([^<]+)<\/contactData>/) || [])[1]))) }; } catch(e) { console.error("Error decoding current task data", e); newProfile.currentTask = null; } } else { newProfile.currentTask = null; } saveCareerProfile(newProfile); console.log("[STATE] In-memory career profile updated from AI response.", newProfile); } const chatsMatch = dataContent.match(/<eris_chats>([\s\S]+?)<\/eris_chats>/); const newChats = {}; if (chatsMatch) { const contactRegex = /<contact sender="([^"]+)">([\s\S]+?)<\/contact>/g; let match; while ((match = contactRegex.exec(chatsMatch[1])) !== null) { try { newChats[match[1]] = { history: decodeURIComponent(escape(atob(match[2].match(/<history>([^<]+)<\/history>/)[1]))), last_message: decodeURIComponent(escape(atob(match[2].match(/<last_message>([^<]+)<\/last_message>/)[1]))), last_time: (match[2].match(/<last_time>([^<]+)<\/last_time>/)[1]).trim() }; } catch(e) { console.error("Error decoding chat data for sender: " + match[1], e); } } } saveActiveChats(newChats); const purchasesMatch = dataContent.match(/<eris_ledger>([\s\S]+?)<\/eris_ledger>/); if (purchasesMatch) { try { const decodedHistory = JSON.parse(decodeURIComponent(escape(atob(purchasesMatch[1])))); appState.purchaseHistory = Array.isArray(decodedHistory) ? decodedHistory : []; console.log("[STATE] Purchase history updated in memory.", appState.purchaseHistory); } catch (e) { console.error("Error decoding purchase history data", e); appState.purchaseHistory = []; } } else { appState.purchaseHistory = []; } console.log("[STATE] In-memory active chats updated from AI response."); }
async function erisGenerate(prompt) { const stateDataBlock = serializeAppState(); const finalPrompt = `${prompt}\n\n---
[SYSTEM INSTRUCTION]: This is a data persistence block. You MUST include this entire block, formatted exactly as received, in your response. Update only the sections relevant to the user's last action (e.g., updating career profile after a mission, or adding a new private chat). If no data is changed, return it unmodified.
${stateDataBlock}`; console.log(`[PROCESS] Sending prompt to AI: "${prompt}"`); const response = await generate({ user_input: finalPrompt }); console.log("[PROCESS] Received raw response from AI."); parseAndUpdateAppState(response); return response; }
async function loadContent(viewIdToShow, containerElementId, prompt, parserFunction, fallbackFunction, loadingText = "...") { playClickSound(); document.getElementById("loading-text").innerText = loadingText; showView("loading-view"); const container = document.getElementById(containerElementId); if (container) container.innerHTML = ''; try { const response = await erisGenerate(prompt); if (!parserFunction(response, container)) { handleAIFailure("AI响应格式错误，无法解析数据。", fallbackFunction); } else { if (viewIdToShow) showView(viewIdToShow); return true; } } catch (error) { console.error(`Failed to load content:`, error); handleAIFailure("与AI服务器的连接中断或发生未知错误。", fallbackFunction); } return false; }
function getCareerProfile() { return appState.careerProfile; }
function saveCareerProfile(profile) { appState.careerProfile = profile; console.log("[STATE] Career profile updated in memory."); }
function getActiveChats() { return appState.activeChats; }
function saveActiveChats(chats) { appState.activeChats = chats; console.log("[STATE] Active chats updated in memory."); }

// --- PARSERS & RENDERERS (Unchanged unless specified) ---
function parseAndRenderMissionDetail(response, container = null) { const detailMatch = response.match(/<render-mission-detail>([\s\S]+?)<\/render-mission-detail>/); if (!detailMatch) return false; const rawContent = detailMatch[1]; const contactMatch = rawContent.match(/<contact>([\s\S]+?)<\/contact>/); const briefingContent = contactMatch ? rawContent.substring(0, contactMatch.index) : rawContent; currentContactData = contactMatch ? contactMatch[1].trim() : "联络数据丢失。"; const lines = briefingContent.trim().split('\n'); let details = {}; lines.forEach(line => { const parts = line.split(':'); if (parts.length > 1) { details[parts[0].trim()] = parts.slice(1).join(':').trim(); } }); document.getElementById('mission-detail-title').innerText = details['标题'] || '任务详情'; let specialReqHtml = details['对接要求']?.includes('❗️') ? `<p class="special-requirement">${details['对接要求']}</p>` : ''; let briefingHtml = `<div class="detail-section"><div class="detail-line"><strong>发布人:</strong> <p>${details['发布人'] || '未知'}</p></div><div class="detail-line"><strong>信誉:</strong> <p class="reputation-stars">${details['信誉'] || ''}</p></div><div class="detail-line"><strong>奖励:</strong> <p>${details['奖励'] || '面议'}</p></div><div class="detail-line"><strong>难度:</strong> <p>${details['难度'] || '未知'}</p></div><div class="detail-line"><strong>截止日期:</strong> <p>${details['截止日期'] || '长期'}</p></div></div><div class="detail-section"><h4>任务描述</h4><p>${details['详细描述']?.replace(/\n/g, '<br>') || '无'}</p></div><div class="detail-section"><h4>元信息</h4><p><strong>潜在威胁:</strong> ${details['潜在威胁'] || '评估中...'}</p><p><strong>最低要求:</strong> ${details['最低要求'] || '无特殊要求'}</p></div>${specialReqHtml ? `<div class="detail-section"><h4>特殊条款</h4>${specialReqHtml}</div>` : ''}`; document.getElementById('mission-detail-content').innerHTML = briefingHtml; document.getElementById('mission-contact-content').innerHTML = `<div class="detail-section"><h4>加密数据包</h4><p>${currentContactData.replace(/\n/g, '<br>')}</p></div>`; document.getElementById('accept-mission-button').style.display = 'block'; document.getElementById('submit-mission-button').style.display = 'none'; document.getElementById('mission-view-toggle-btn').style.display = 'none'; toggleDetailView(true); return true; }
function parseAndRenderPublicChannel(response, container) { const channelData = response.match(/<render-public-chat>([\s\S]+?)<\/render-public-chat>/); if (!channelData) return false; container.innerHTML = ''; const messages = channelData[1].trim().split('\n'); let messagesHtml = ''; messages.forEach(msg => { const parts = msg.split('--'); if (parts.length < 3) return; const time = parts[0].trim(); const user = parts[1].trim(); const content = parts.slice(2).join('--').trim(); const escapedContent = content.replace(/"/g, '"'); const isSelf = user.trim() === currentUsername.trim(); const senderHtml = isSelf ? user : `<span class="username-clickable" onclick="startPrivateChatFromPublic(this)" data-contact-name="${user}" data-context-message="${escapedContent}">${user}</span>`; if (user === currentUsername) { messagesHtml += `<div class="message-item user-message"><div><div class="message-meta">${senderHtml} - ${time}</div><div class="message-bubble">${content}</div></div></div>`; } else { messagesHtml += `<div class="message-item other-message"><div><div class="message-meta">${senderHtml} - ${time}</div><div class="message-bubble">${content}</div></div></div>`; } }); container.innerHTML += messagesHtml; scrollToBottom(container); return true; }
function parseAndRenderPrivateChatList(response, container) { const activeChats = getActiveChats(); let html = ''; const sortedChats = Object.entries(activeChats).sort(([, a], [, b]) => (b.last_time > a.last_time) ? 1 : -1); for (const [sender, chat] of sortedChats) { html += `<div class="chat-list-item" data-sender="${sender}" onclick="openPreloadedPrivateChat(this)"><div class="chat-list-header"><span class="chat-list-sender">${sender}</span><span class="chat-list-time">${chat.last_time}</span></div><p class="chat-list-last-msg">${chat.last_message}</p><div class="delete-progress"></div></div>`; } container.innerHTML = html || '<p style="color:#888; text-align:center; padding: 20px;">[无私密通讯]</p>'; container.querySelectorAll('.chat-list-item').forEach(addLongPressHandler); return true; }
function parseAndRenderMissions(response, container) { const data = response.match(/<render-missions-list>([\s\S]+?)<\/render-missions-list>/); if (!data) return false; const regex = /<mission id="([a-zA-Z0-9]{6})">(.+?)<\/mission>/g; let html = ''; let match; while ((match = regex.exec(data[1])) !== null) { const [_, id, content] = match; const parts = content.split('--').map(p => p.trim()); if (parts.length < 6) continue; const [title, publisher, reward, difficulty, description, status] = parts; const statusClass = status === '可接取' ? 'mission-status-open' : 'mission-status-locked'; const isClickable = status === '可接取'; html += `<div class="mission-card"><div class="mission-title">${title}</div><div class="mission-publisher">发布方: <span>${publisher}</span></div><p class="mission-description">${description}</p><div class="mission-meta"><span class="mission-reward">赏金: ${reward}</span><span class="mission-difficulty">难度: ${difficulty}</span><span class="${statusClass}">${status}</span></div><button class="view-details-button" ${isClickable ? `onclick="showMissionDetails('${id}')"` : 'disabled'}>${isClickable ? '查看详细' : '权限锁定'}</button></div>`; } container.innerHTML = html || '<p style="color:#888; text-align:center;">[无可用任务]</p>'; return true; }
function parseAndRenderMallItems(response, container) { const data = response.match(/<render-mall-items>([\s\S]+?)<\/render-mall-items>/); if (!data) return false; const items = data[1].trim().split('\n'); let html = ''; items.forEach(item => { const parts = item.split('--'); if (parts.length < 4) return; const [name, priceStr, description, stock] = parts.map(p => p.trim()); const price = parseInt(priceStr.replace(/[^\d]/g, '')); const stockClass = stock.includes('稀少') || stock.includes('受限') ? 'stock-rare' : 'stock-common'; html += ` <div class="shop-item-card"> <div class="item-content"> <div class="item-header"> <span class="item-name">${name}</span> <span class="item-price">${priceStr}</span> </div> <p class="item-description">${description}</p> <div class="item-stock"><span class="${stockClass}">${stock}</span></div> </div> <button class="buy-button" data-item-name="${name}" data-item-price="${price}">购买</button> </div>`; }); container.innerHTML = html || '<p style="color:#888; text-align:center;">[当前分类无商品]</p>'; container.querySelectorAll('.buy-button').forEach(btn => { btn.onclick = () => showDeliveryOptions(btn.dataset.itemName, parseInt(btn.dataset.itemPrice)); }); return true; }


// =========================================================================
// +++ 修改：主菜单与档案创建流程 +++
// =========================================================================
function showMainMenu() {
    playClickSound();
    // 这里的逻辑保持不变，依然依赖内存中的appState.careerProfile来判断
    // 这样做的原因是，档案创建后，我们依然会把档案信息存入appState，以供其他功能（如购买）使用
    if (!getCareerProfile()) {
        showView('career-setup-view');
        return;
    }
    const hasProfile = !!getCareerProfile();
    document.querySelectorAll('#main-grid-container .nav-button').forEach(btn => {
        btn.classList.toggle('disabled', !hasProfile);
    });

    showView('main-platform');
}

/**
 * [需求 1] 修改：处理档案创建，不再调用AI，直接写入世界书
 */
async function handleCareerSetupConfirm() {
    // 1. 获取输入值
    const earnings = document.getElementById('initial-earnings').value || 0;
    const missions = document.getElementById('initial-missions').value || 0;

    // 2. 显示加载动画
    showView("loading-view");
    document.getElementById("loading-text").innerText = '正在将初始档案写入区块链...';

    // 3. 构造要写入世界书的内容 (key=value 格式)
    const userInfoContent = `当前金额=${earnings}\n已完成任务=${missions}`;

    try {
        // 4. 调用辅助函数，将内容写入名为 "用户信息" 的世界书条目
        await updateWorldBookEntry('用户信息', userInfoContent);
        console.log('[WB] Initial user profile created in world book.');

        // 5. 成功后，也在内存中创建一个简单的profile，以便UI能正常解锁
        // 注意：这里的内存profile简化了，因为主要数据源现在是世界书
        saveCareerProfile({
            '佣金': earnings,
            '任务完成': missions,
            '评级': '新兵', // 可以给个默认值
            '任务接取': '0',
            '任务失败': '0',
            currentTask: null
        });

        // 6. 延迟一小会儿，然后跳转到主菜单
        setTimeout(() => {
            showMainMenu();
        }, 1000); // 模拟写入耗时

    } catch(err) {
        // 如果写入世界书失败
        handleAIFailure("档案写入失败，请检查插件权限或联系管理员。", handleLogin);
    }
}

function showMissionPlatform(refetch = true, event) {
    if (event && event.currentTarget.classList.contains('disabled')) { playClickSound(); return; }

    const profile = getCareerProfile();
    if (profile && profile.currentTask) {
        playClickSound();
        showActiveMissionDetail();
    } else {
        const prompt = `// 暗网指令: 任务列表\n暗网.任务列表(user: '${currentUsername}', action: 'refresh');\n[MANDATORY FORMAT]请返回用 <render-missions-list> 标签包裹的任务列表。`;
        if (refetch) {
            loadContent('mission-platform-view', 'mission-list', prompt, parseAndRenderMissions, showMainMenu, '正在接入任务服务器...');
        } else {
            playClickSound();
            showView('mission-platform-view');
        }
    }
}
function showMissionDetails(missionId) { currentMissionId = missionId; const prompt = `// 暗网指令: 任务详情\n暗网.任务详情(user: '${currentUsername}', mission_id: '${missionId}');\n[MANDATORY FORMAT]请返回用 <render-mission-detail> 标签包裹的任务详情。`; document.getElementById('mission-detail-back-btn').onclick = () => showMissionPlatform(false); loadContent('mission-detail-view', null, prompt, parseAndRenderMissionDetail, () => showMissionPlatform(false), `正在解密任务 ${missionId}...`); }
function showPublicChannel(refetch = true, event) { if (event && event.currentTarget.classList.contains('disabled')) { playClickSound(); return; } const prompt = `// 暗网指令: 公共频道\n暗网.公共频道(user: '${currentUsername}', action: 'fetch');\n[MANDATORY FORMAT]请返回用 <render-public-chat> 标签包裹的聊天记录。`; if (refetch) { loadContent('public-channel-view', 'public-channel-messages', prompt, parseAndRenderPublicChannel, showMainMenu, '正在同步公共信道...'); } else { playClickSound(); showView('public-channel-view'); scrollToBottom(document.getElementById('public-channel-messages')); } }


// --- PURCHASE FLOW (Unchanged) ---
function showMallCategories(playSound=true, event) { if (event && event.currentTarget.classList.contains('disabled')) { playClickSound(); return; } if (playSound) playClickSound(); showView('mall-categories-view'); }
function showMallItemList(category) { document.getElementById('mall-item-list-title').innerText = category; const prompt = `// 暗网指令: 浏览商店\n暗网.商店(user: '${currentUsername}', category: '${category}');\n[MANDATORY FORMAT]请返回用 <render-mall-items> 标签包裹的商品列表。`; loadContent('mall-item-list-view', 'mall-item-list-content', prompt, parseAndRenderMallItems, ()=>showMallCategories(false), `正在加载 ${category}...`); }
function showDeliveryOptions(itemName, itemPrice) { playClickSound(); tempPurchaseData = { itemName, itemPrice }; document.getElementById('delivery-item-info').innerText = `商品: ${itemName}\n价格: ${itemPrice.toLocaleString()} 联邦币`; document.getElementById('delivery-option-deaddrop').querySelector('.fee').innerText = `(配送费: ${DEAD_DROP_FEE.toLocaleString()} 联邦币)`; document.getElementById('delivery-option-cleaner').querySelector('.fee').innerText = `(配送费: ${CLEANER_FEE.toLocaleString()} 联邦币)`; showModal('delivery-options-modal'); }
function initiatePurchase(deliveryType) { playClickSound(); hideModal('delivery-options-modal'); tempPurchaseData.deliveryType = deliveryType; if (deliveryType === 'cleaner') { showModal('cleaner-delivery-modal'); } else { executePurchase(); } }
function handleCleanerFormSubmit() { playClickSound(); const details = { address: document.getElementById('cleaner-address').value.trim(), time: document.getElementById('cleaner-time').value.trim(), method: document.getElementById('cleaner-method').value.trim() }; if (!details.address || !details.time || !details.method) { alert("请填写所有配送信息。"); return; } tempPurchaseData.deliveryDetails = details; hideModal('cleaner-delivery-modal'); executePurchase(); }
async function executePurchase() { const { itemName, itemPrice, deliveryType, deliveryDetails } = tempPurchaseData; const deliveryFee = deliveryType === 'cleaner' ? CLEANER_FEE : DEAD_DROP_FEE; const totalCost = itemPrice + deliveryFee; const profile = getCareerProfile(); const balance = parseInt(profile['佣金'] || 0); if (balance < totalCost) { errorSound.play(); document.getElementById('purchase-status-title').innerText = "交易失败"; document.getElementById('purchase-status-message').innerText = `资金不足。\n需要: ${totalCost.toLocaleString()} 联邦币\n可用: ${balance.toLocaleString()} 联邦币`; showModal('purchase-status-modal'); return; } document.getElementById("loading-text").innerText = "正在处理交易..."; let prompt = `// 暗网指令: 购买商品\n暗网.购买(user: '${currentUsername}', item: '${itemName}', delivery: '${deliveryType}'`; if (deliveryType === 'cleaner') { prompt += `, details: { address: '${deliveryDetails.address}', time: '${deliveryDetails.time}', signal: '${deliveryDetails.method}' })`; } else { prompt += `)`; } prompt += `\n[MANDATORY FORMAT] 你的回复必须包含 <render-tx-confirm> 标签，内含新聊天信息。格式：<render-tx-confirm><contact_name>联络员名称</contact_name><message>第一条消息</message></render-tx-confirm>`; try { const response = await erisGenerate(prompt); if (parseAndHandlePurchaseResponse(response)) { profile['佣金'] = balance - totalCost; saveCareerProfile(profile); if(!appState.purchaseHistory) appState.purchaseHistory = []; appState.purchaseHistory.push({ itemName, deliveryType, totalCost, date: new Date().toISOString() }); purchaseSound.play(); document.getElementById('purchase-status-title').innerText = "交易成功"; document.getElementById('purchase-status-message').innerText = `已支付 ${totalCost.toLocaleString()} 联邦币。相关通讯已建立，请在“私聊”中查看详情。`; } else { throw new Error("AI response format error for purchase confirmation."); } } catch(err) { console.error("Purchase failed:", err); errorSound.play(); document.getElementById('purchase-status-title').innerText = "交易错误"; document.getElementById('purchase-status-message').innerText = "无法确认交易，资金未扣除。网络可能不稳定，请稍后再试。"; } finally { showView('mall-categories-view'); showModal('purchase-status-modal'); tempPurchaseData = {}; } }
function parseAndHandlePurchaseResponse(response) { const confirmMatch = response.match(/<render-tx-confirm>([\s\S]+?)<\/render-tx-confirm>/); if (!confirmMatch) return false; const content = confirmMatch[1].trim(); const nameMatch = content.match(/<contact_name>([\s\S]+?)<\/contact_name>/); const msgMatch = content.match(/<message>([\s\S]+?)<\/message>/); if (!nameMatch || !msgMatch) return false; const contactName = nameMatch[1].trim(); const message = msgMatch[1].trim(); const d = new Date(); const time = `${d.getHours().toString().padStart(2, '0')}:${d.getMinutes().toString().padStart(2, '0')}`; const chatHistory = `${time}--${contactName}--${message}`; const activeChats = getActiveChats(); activeChats[contactName] = { history: chatHistory, last_message: message, last_time: time }; saveActiveChats(activeChats); console.log(`[PURCHASE] New chat created with '${contactName}'.`); return true; }
function closeAllModalsAndRefreshLists() { closeAllModals(); showPrivateChatList(false); showMainMenu(); }


// =========================================================================
// +++ 修改：任务流程 +++
// =========================================================================

/**
 * [需求 2] 修改：接受任务时，将任务信息写入"当前任务"世界书
 */
async function acceptMission() {
    playAcceptSound();
    let profile = getCareerProfile();
    if (!profile || profile.currentTask) return;

    // 1. 从UI中获取任务简报HTML和联络信息
    const missionTitle = document.getElementById('mission-detail-title').innerText;
    const briefingHtml = document.getElementById('mission-detail-content').innerHTML;
    const contactInfo = currentContactData; // 这个变量在打开任务详情时就已经赋值了

    // 2. 将数据保存到内存中的 profile (维持现有逻辑)
    profile.currentTask = { id: currentMissionId, title: missionTitle, briefingHtml: briefingHtml, contactData: contactInfo };
    saveCareerProfile(profile);
    console.log(`[MISSION] Accepted: "${missionTitle}". Data staged in memory.`);

    // 3. 构造将要写入"当前任务"世界书的内容
    const missionWBContent = `
[任务简报]
${briefingHtml}

<hr>

[加密通讯]
${contactInfo}
    `.trim();

    // 4. (核心) 调用辅助函数写入世界书
    try {
        await updateWorldBookEntry('当前任务', missionWBContent);
        console.log('[WB] Active mission details injected into "当前任务" world book.');
    } catch (err) {
        // 即使写入失败，也让流程继续，只是提醒用户
        alert('警告：任务信息写入世界书失败，但这不影响您继续任务。');
    }

    // 5. 更新UI (保持不变)
    document.getElementById('accept-mission-button').style.display = 'none';
    document.getElementById('submit-mission-button').style.display = 'block';

    // 6. 开始倒计时 (保持不变)
    document.getElementById('countdown-message').innerHTML = '正在同步加密信道... 倒计时 <span id="timer">5</span>';
    document.getElementById('view-info-btn').style.display = 'none';
    showView('acceptance-view');
    startAcceptanceCountdown();
}

function startAcceptanceCountdown() { const countdownMessage = document.getElementById('countdown-message'); const viewInfoBtn = document.getElementById('view-info-btn'); const timerSpan = document.getElementById('timer'); let timeLeft = 5; const interval = setInterval(() => { timeLeft--; if (timeLeft > 0) { timerSpan.textContent = timeLeft; } else { clearInterval(interval); timerSpan.textContent = '0'; setTimeout(() => { countdownMessage.textContent = '通信已建立。请查收加密信息。'; viewInfoBtn.style.display = 'block'; }, 500); } }, 1000); }
function viewDataPacket() { playClickSound(); document.getElementById('mission-view-toggle-btn').style.display = 'block'; toggleDetailView(true); showView('data-packet-view'); document.getElementById('mission-detail-back-btn').onclick = showMainMenu; const dataPacketContent = document.getElementById('data-packet-content'); dataPacketContent.innerHTML = ''; const data = ['DECRYPTING DATA PACKET...\n', 'ENCRYPTION: AES-2048 (Quantum Resistant)\n', 'STATUS: DECRYPTION COMPLETE.\n\n', '>>> PAYLOAD RECEIVED <<<\n\n', '--BEGIN TRANSMISSION--\n\n', currentContactData + '\n\n', '--END TRANSMISSION--\n\n', 'NOTICE: This communication channel is one-time use and will auto-erase upon disconnection.']; typewriterEffect(dataPacketContent, data); }

function showActiveMissionDetail() {
    playClickSound();
    const profile = getCareerProfile();
    if (!profile || !profile.currentTask) {
        showMainMenu();
        return;
    }
    const task = profile.currentTask;
    document.getElementById('mission-detail-title').innerText = task.title;
    document.getElementById('mission-detail-content').innerHTML = task.briefingHtml;
    document.getElementById('mission-contact-content').innerHTML = `<div class="detail-section"><h4>加密数据包</h4><p>${task.contactData.replace(/\n/g, '<br>')}</p></div>`;

    document.getElementById('accept-mission-button').style.display = 'none';
    document.getElementById('submit-mission-button').style.display = 'block';
    document.getElementById('mission-view-toggle-btn').style.display = 'block';
    document.getElementById('mission-detail-back-btn').onclick = showMainMenu;

    toggleDetailView(true);
    showView('mission-detail-view');
}

/**
 * [需求 3] 修改：提交任务时，在AI返回成功后，更新"用户信息"世界书
 */
async function submitCurrentMission() {
    playClickSound();
    const profile = getCareerProfile();
    if (!profile || !profile.currentTask) return;
    const taskTitle = profile.currentTask.title;
    const prompt = `// 暗网指令: 提交任务\n暗网.提交任务(user: '${currentUsername}', title: '${taskTitle}');\n[MANDATORY FORMAT]请返回用 <render-mission-report> 标签包裹的任务报告。格式：<render-mission-report>报告内容: [文本] 奖励结算: [数字]</render-mission-report>`;

    // loadContent的回调函数现在变成 async，以便在内部使用 await
    loadContent(null, null, prompt, async (response) => {
        const reportMatch = response.match(/<render-mission-report>([\s\S]+?)<\/render-mission-report>/);
        if (!reportMatch) return false;

        // 1. 从AI回复中解析奖励金额和报告文本
        const rewardMatch = reportMatch[1].match(/奖励结算: *([\d,]+)/);
        const reportContentMatch = reportMatch[1].match(/报告内容:([\s\S]+)/);
        const reward = rewardMatch ? parseInt(rewardMatch[1].replace(/,/g, '')) : 0;
        const reportText = reportContentMatch ? reportContentMatch[1].trim().split('奖励结算:')[0].trim() : '系统确认完成，无详细报告。';

        // 2. (核心) 读取、计算并写回 "用户信息" 世界书
        try {
            const userInfoContent = await readWorldBookEntry('用户信息');
            const data = parseIniFromString(userInfoContent);

            const currentAmount = parseInt(data['当前金额'] || '0');
            const currentMissions = parseInt(data['已完成任务'] || '0');

            const newAmount = currentAmount + reward;
            const newMissions = currentMissions + 1;

            const newUserInfoContent = `当前金额=${newAmount}\n已完成任务=${newMissions}`;
            await updateWorldBookEntry('用户信息', newUserInfoContent);
            console.log(`[WB] User info updated: Amount=${newAmount}, Missions=${newMissions}`);

            // 同时更新内存中的profile以保持UI一致性
            profile['佣金'] = newAmount;
            profile['任务完成'] = newMissions;

        } catch (err) {
            alert('警告：结算信息写入世界书失败！请手动记录您的收入。');
        }

        // 3. 更新内存中的状态，清空当前任务
        profile.currentTask = null;
        saveCareerProfile(profile);

        // 4. 最后，清空 "当前任务" 世界书，因为它已经完成了
        await updateWorldBookEntry('当前任务', '[任务已完成或中止]');

        // 5. 显示任务完成的弹窗
        document.getElementById('report-modal-reward').innerText = `奖励: ${reward.toLocaleString()} 联邦币`;
        document.getElementById('report-modal-content').innerText = reportText;
        document.getElementById('mission-report-modal').classList.add('visible');

        return true;
    }, showMainMenu, "正在提交任务报告并结算...");
}

function closeReportModal() { playClickSound(); document.getElementById('mission-report-modal').classList.remove('visible'); showMainMenu(); }

function toggleDetailView(isInitial = false) {
    if (!isInitial) playClickSound();
    const briefingContent = document.getElementById("mission-detail-content");
    const contactContent = document.getElementById("mission-contact-content");
    const toggleBtn = document.getElementById("mission-view-toggle-btn");

    if(isInitial) { // Force to briefing view on load
        briefingContent.style.display = "block";
        contactContent.style.display = "none";
        toggleBtn.innerText = "看联络";
        return;
    }

    if (briefingContent.style.display === "none") {
        briefingContent.style.display = "block";
        contactContent.style.display = "none";
        toggleBtn.innerText = "看联络";
    } else {
        briefingContent.style.display = "none";
        contactContent.style.display = "block";
        toggleBtn.innerText = "看简报";
    }
}

// --- CHAT (LOGIC MODIFIED) ---
function showPrivateChatList(refetch = true, event) { if (event && event.currentTarget.classList.contains('disabled')) { playClickSound(); return; } const prompt = `// 暗网指令: 刷新私聊\n暗网指令.私聊(user: '${currentUsername}', action: 'refresh_list');\n[MANDATORY FORMAT]与数据块中已有的私聊合并后，在持久化数据块 <eris_chats> 中输出所有聊天。此操作不需要渲染块。`; if (refetch) { loadContent('private-chat-list-view', 'private-chat-list', prompt, parseAndRenderPrivateChatList, showMainMenu, '正在解密个人通讯...'); } else { playClickSound(); parseAndRenderPrivateChatList(null, document.getElementById('private-chat-list')); showView('private-chat-list-view'); } }
function startPrivateChatFromPublic(element) { privateChatOrigin = 'public_channel'; startPrivateChat(element.dataset.contactName, `[${element.dataset.contactName} 在公共频道说: "${element.dataset.contextMessage}"]`); }
function openPreloadedPrivateChat(element) { privateChatOrigin = 'chat_list'; const sender = element.dataset.sender; const chatHistory = (getActiveChats()[sender] || {}).history; startPrivateChat(sender, null, chatHistory); }
function startPrivateChat(contactName, initialContext = null, fullHistoryString = null) { playClickSound(); currentPrivateChatContact = contactName; document.getElementById('private-chat-contact-name').innerText = contactName; const container = document.getElementById('private-chat-messages-specific'); container.innerHTML = ''; delete container.dataset.publicContext; if (fullHistoryString) { try { const messages = fullHistoryString.trim().split('\n'); let historyHtml = ''; messages.forEach(msg => { const parts = msg.split('--'); if (parts.length < 3) return; const time = parts[0].trim(); const user = parts[1].trim(); const content = parts.slice(2).join('--').trim(); const msgClass = user === currentUsername ? "user-message" : "other-message"; historyHtml += `<div class="message-item ${msgClass}"><div><div class="message-meta">${user} - ${time}</div><div class="message-bubble">${content}</div></div></div>`; }); container.innerHTML = historyHtml; } catch (e) { console.error(e) } } else if(initialContext) { container.innerHTML = `<div class="context-message">${initialContext.replace(/\[|\]/g, '')}</div>`; container.dataset.publicContext = initialContext; } document.getElementById('private-chat-input').value = ''; showView('private-chat-specific-view'); scrollToBottom(container); }
function backFromPrivateChat() { playClickSound(); if (privateChatOrigin === 'public_channel') { showPublicChannel(false); } else { showPrivateChatList(false); } }
async function sendPrivateMessage() { const input = document.getElementById('private-chat-input'); const text = input.value.trim(); const container = document.getElementById('private-chat-messages-specific'); playClickSound(); const d = new Date(); const time = `${d.getHours().toString().padStart(2,'0')}:${d.getMinutes().toString().padStart(2,'0')}`; if (text) { container.innerHTML += `<div class="message-item user-message"><div><div class="message-meta">${currentUsername} - ${time}</div><div class="message-bubble">${text}</div></div></div>`; scrollToBottom(container); input.value = ''; return; } const typingIndicatorId = 'typing-' + Date.now(); container.innerHTML += `<div id="${typingIndicatorId}" class="message-item other-message typing-indicator">${currentPrivateChatContact} 正在输入...</div>`; scrollToBottom(container); let history = ''; if (container.dataset.publicContext) { history += container.dataset.publicContext + '\n'; } Array.from(container.children).forEach(item => { if (item.classList.contains('message-item')) { const metaElem = item.querySelector('.message-meta'); const bubbleElem = item.querySelector('.message-bubble'); if (metaElem && bubbleElem) { history += `${metaElem.innerText.replace(' - ', '--')}--${bubbleElem.innerText}\n`; } }}); const prompt = `// 暗网指令: 回复私聊\n这是你（${currentPrivateChatContact}）与${currentUsername}的私聊。目前的聊天记录如下：\n${history}\n[MANDATORY FORMAT]请你以${currentPrivateChatContact}的身份，用 <render-chat-replies> 标签包裹，生成5到13条回复，每条回复占一行。`; try { const response = await erisGenerate(prompt); document.getElementById(typingIndicatorId)?.remove(); const replyData = response.match(/<render-chat-replies>([\s\S]+?)<\/render-chat-replies>/); if (replyData) { const replies = replyData[1].trim().split('\n').filter(r => r); let i = 0; let lastReplyText, lastReplyTime; (function addReply() { if (i < replies.length) { const d = new Date(); const time = `${d.getHours().toString().padStart(2, '0')}:${d.getMinutes().toString().padStart(2, '0')}`; container.innerHTML += `<div class="message-item other-message"><div><div class="message-meta">${currentPrivateChatContact} - ${time}</div><div class="message-bubble">${replies[i].trim()}</div></div></div>`; scrollToBottom(container); lastReplyText = replies[i].trim(); lastReplyTime = time; i++; setTimeout(addReply, Math.random() * 800 + 400); } else { let fullHistory = ''; if (container.dataset.publicContext) { fullHistory += `${new Date().toLocaleTimeString('en-GB',{hour12:false})}--System--${container.dataset.publicContext.replace(/\n/g, '')}\n`;} Array.from(document.querySelectorAll('#private-chat-messages-specific .message-item')).forEach(item => { const meta = item.querySelector('.message-meta'), bubble = item.querySelector('.message-bubble'); if (meta&&bubble) fullHistory += `${meta.innerText.replace(' - ', '--')}--${bubble.innerText}\n`; }); const activeChats=getActiveChats();activeChats[currentPrivateChatContact]={history:fullHistory.trim(),last_message:lastReplyText||"...",last_time:lastReplyTime||"??:??"};saveActiveChats(activeChats); }})(); } else { handleAIFailure("AI回复格式不正确，对话无法继续。", backFromPrivateChat); } } catch(error) { document.getElementById(typingIndicatorId)?.remove(); handleAIFailure("与AI的连接丢失。", backFromPrivateChat);} }
function addLongPressHandler(element) { let pressTimer; let progressInterval; const progressBar = element.querySelector('.delete-progress'); const startPress = (e) => { e.preventDefault(); let progress = 0; progressBar.style.width = '0%'; pressTimer = setTimeout(() => { clearInterval(progressInterval); playDeleteSound(); const sender = element.dataset.sender; const activeChats =getActiveChats(); delete activeChats[sender]; saveActiveChats(activeChats); element.classList.add('deleting'); element.addEventListener('transitionend', () => element.remove()); }, 1000); progressInterval = setInterval(() => { progress += 10; progressBar.style.width = `${progress}%`; if (progress >= 100) clearInterval(progressInterval); }, 100); }; const cancelPress = () => { clearTimeout(pressTimer); clearInterval(progressInterval); progressBar.style.transition = 'width 0.2s ease-out'; progressBar.style.width = '0%'; setTimeout(() => { progressBar.style.transition = 'width 0.1s linear'; }, 200); }; element.addEventListener('mousedown', startPress); element.addEventListener('touchstart', startPress); element.addEventListener('mouseup', cancelPress); element.addEventListener('mouseleave', cancelPress); element.addEventListener('touchend', cancelPress); const originalClickHandler=element.onclick;element.onclick=e=>{e.stopPropagation();if(progressBar.style.width.replace('%','')<50){clearTimeout(pressTimer);clearInterval(progressInterval);originalClickHandler.call(element,e)}}; }
async function sendPublicMessage(){const e=document.getElementById("public-channel-input"),t=e.value.trim();if(!t)return;playClickSound();const n=document.getElementById("public-channel-messages"),o=new Date,s=`${o.getHours().toString().padStart(2,"0")}:${o.getMinutes().toString().padStart(2,"0")}`;n.innerHTML+=`<div class="message-item user-message"><div><div class="message-meta">${currentUsername} - ${s}</div><div class="message-bubble">${t}</div></div></div>`,scrollToBottom(n),e.value="";const a=`// 暗网指令: 公共广播\n暗网.公共广播(user: '${currentUsername}', message: '${t}');\n[MANDATORY FORMAT]请返回用 <render-public-chat> 标签包裹的更新后的完整公共频道聊天记录。`;try{const e=await erisGenerate(a);parseAndRenderPublicChannel(e,n)||alert("AI响应格式不正确，频道可能未完全更新。")}catch(e){console.error(e),alert("与AI的连接丢失，消息可能未广播。")}}


// --- INIT & MISC ---
function handleLogin() { const usernameInput = document.getElementById("username"); const newUsername = usernameInput.value.trim() || "Operator"; const lastUsername = localStorage.getItem(LAST_USERNAME_KEY); if (lastUsername && newUsername !== lastUsername) { console.log(`[AUTH] New user identity detected. Wiping in-memory data for '${lastUsername}'.`); appState = { careerProfile: null, activeChats: {}, purchaseHistory: [] }; } currentUsername = newUsername; localStorage.setItem(LAST_USERNAME_KEY, currentUsername); accessSound.play().catch(e => {}); showView(""); setTimeout(() => { document.getElementById("welcome-message").innerText = `ACCESS GRANTED, ${currentUsername.toUpperCase()}`; showView("welcome-screen"); setTimeout(() => { showView(""); setTimeout(() => { document.getElementById("welcome-user-main").textContent = currentUsername; showMainMenu(); }, 500); }, 2000); }, 500); }
function addKeypressListeners(){document.querySelectorAll("#username, #password").forEach(e=>e.addEventListener("keypress",t=>{"Enter"===t.key&&(t.preventDefault(),handleLogin())}));document.getElementById("public-channel-input").addEventListener("keypress",e=>{"Enter"===e.key&&sendPublicMessage()});document.getElementById("private-chat-input").addEventListener("keypress",e=>{"Enter"===e.key&&sendPrivateMessage()})}

document.addEventListener("DOMContentLoaded",()=>{
    const lastUsername = localStorage.getItem(LAST_USERNAME_KEY);
    if (lastUsername) {
        document.getElementById('username').value = lastUsername;
    }
    console.log("[SYSTEM] ERIS Terminal Initialized. Awaiting first AI interaction to sync state.");
    showView("login-screen");
    addKeypressListeners();
});
</script>
</body>
</html>
```
