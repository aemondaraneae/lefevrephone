<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Martin Lefevre's iPhone</title>
<style>
  :root {
    --bg-color: #000;
    --app-bg: #000;
    --text-main: #fff;
    --text-muted: #8e8e93;
    --blue: #0a84ff;
    --green: #30d158;
    --yellow: #e6c430; /* iOS Notes Yellow */
    --bubble-received: #3a3a3c;
    --separator: #38383a;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Segoe UI", sans-serif;
    margin: 0;
    background: #0a0a0c;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }

  /* CLASSIC PHONE HARDWARE */
  .phone-hardware {
    width: 320px;
    height: 680px; 
    background: #1a1a1c;
    border-radius: 40px;
    border: 3px solid #333; 
    box-shadow: 0 10px 40px rgba(0,0,0,0.8), inset 0 0 15px rgba(0,0,0,0.5);
    position: relative;
    padding: 80px 15px; 
    box-sizing: border-box;
  }

  /* TOP BEZEL DETAILS */
  .top-camera {
    position: absolute;
    top: 35px;
    left: 110px;
    width: 12px;
    height: 12px;
    background: #050505;
    border-radius: 50%;
    box-shadow: inset 0px 0px 4px rgba(255,255,255,0.1);
  }

  .top-speaker {
    position: absolute;
    top: 38px;
    left: 50%;
    transform: translateX(-50%);
    width: 50px;
    height: 6px;
    background: #050505;
    border-radius: 10px;
    box-shadow: inset 0px 1px 2px rgba(0,0,0,0.9);
  }

  /* HOME BUTTON */
  .home-button {
    position: absolute;
    bottom: 15px;
    left: 50%;
    transform: translateX(-50%);
    width: 50px;
    height: 50px;
    background: #111;
    border-radius: 50%;
    border: 2px solid #222;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: all 0.1s;
    -webkit-tap-highlight-color: transparent;
    z-index: 9999;
  }

  .home-button:active {
    background: #050505;
    transform: translateX(-50%) scale(0.95);
  }

  .home-button-icon {
    width: 16px;
    height: 16px;
    border: 1.5px solid #333;
    border-radius: 4px;
    pointer-events: none;
  }

  /* DISPLAY AREA */
  .display {
    width: 100%;
    height: 100%;
    background: var(--bg-color);
    position: relative;
    overflow: hidden;
    border: 1px solid #000;
  }

  /* CLASSIC STATUS BAR */
  .status {
    position: absolute;
    top: 0;
    width: 100%;
    padding: 4px 6px;
    font-size: 11px;
    font-weight: 500;
    display: flex;
    justify-content: space-between;
    box-sizing: border-box;
    z-index: 998;
    pointer-events: none;
    color: white;
    text-shadow: 0 1px 3px rgba(0,0,0,0.9);
  }
  
  .status-center {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    font-weight: 600;
  }

  /* SCREEN ROUTING */
  .screen {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: var(--app-bg);
    box-sizing: border-box;
    overflow-y: auto;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.2s ease-in-out;
    z-index: 1; 
  }

  .screen:target {
    opacity: 1;
    pointer-events: auto;
    z-index: 20; 
  }

  /* HOME SCREEN */
  #home {
    opacity: 1;
    pointer-events: auto;
    z-index: 10;
    /* Moody, cinematic rain on car window at night */
    background: url('https://images.unsplash.com/photo-1508139591423-013ba0c6c747?q=80&w=1000&auto=format&fit=crop') center/cover;
    overflow: hidden; 
  }

  .app-grid {
    padding: 40px 15px 20px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px 10px;
  }

  .app-icon {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-decoration: none;
    color: #fff;
    font-size: 11px;
    font-weight: 500;
    text-shadow: 0 1px 3px rgba(0,0,0,0.8);
  }

  .icon-box {
    width: 50px;
    height: 50px;
    border-radius: 12px;
    background: #333;
    margin-bottom: 6px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 26px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.5);
  }

  .icon-messages { background: var(--green); }
  .icon-photos { background: #fff; }
  .icon-phone { background: var(--green); }

  .dock {
    position: absolute;
    bottom: 10px;
    left: 10px;
    right: 10px;
    background: rgba(20, 20, 20, 0.4);
    backdrop-filter: blur(15px);
    border-radius: 20px;
    padding: 10px;
    display: flex;
    justify-content: space-around;
  }

  .dock .icon-box { margin-bottom: 0; }
  .dock .app-label { display: none; } 

  /* APP SWITCHER MULTITASKING VIEW */
  #switcher {
    background: rgba(0, 0, 0, 0.8);
    backdrop-filter: blur(20px);
    display: flex;
    align-items: center;
    padding: 0 20px;
    overflow-x: auto;
    scroll-snap-type: x mandatory;
    gap: 15px;
  }

  .switcher-card {
    flex: 0 0 160px;
    height: 300px;
    background: #1c1c1e;
    border-radius: 20px;
    scroll-snap-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    color: white;
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
    position: relative;
    border: 1px solid #333;
  }

  .switcher-card .icon-box {
    width: 60px;
    height: 60px;
    margin-bottom: 0;
  }

  .switcher-title {
    position: absolute;
    top: -25px;
    font-size: 14px;
    font-weight: 600;
  }

  /* APP HEADERS */
  .app-header {
    padding: 35px 15px 10px;
    font-size: 28px;
    font-weight: 700;
    border-bottom: 1px solid var(--separator);
    background: rgba(0,0,0,0.85);
    backdrop-filter: blur(10px);
    position: sticky;
    top: 0;
    z-index: 50;
  }

  .nav-bar {
    display: flex;
    align-items: center;
    padding: 25px 15px 10px;
    background: rgba(0,0,0,0.85);
    backdrop-filter: blur(10px);
    position: sticky;
    top: 0;
    z-index: 50;
    border-bottom: 1px solid var(--separator);
  }

  .back-btn {
    color: var(--blue);
    text-decoration: none;
    font-size: 17px;
    display: flex;
    align-items: center;
  }
  
  .chat-title {
    margin: 0 auto;
    font-weight: 700; 
    font-size: 18px; 
    letter-spacing: 0.3px; 
    color: #ffffff;
    transform: translateX(-15px);
  }

  /* LISTS (Messages & Calls) */
  .list-item {
    display: flex;
    padding: 12px 15px;
    border-bottom: 1px solid var(--separator);
    text-decoration: none;
    color: var(--text-main);
  }

  .avatar {
    width: 45px;
    height: 45px;
    border-radius: 50%;
    background: #222;
    margin-right: 12px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 20px;
  }

  .list-content {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
    overflow: hidden;
  }

  .list-top {
    display: flex;
    justify-content: space-between;
    margin-bottom: 3px;
    align-items: baseline;
  }

  .list-name { 
    font-weight: 700; 
    font-size: 18px; 
    letter-spacing: 0.5px; 
    color: #fff; 
  }
  
  .list-time { color: var(--text-muted); font-size: 14px; }
  .list-preview { color: var(--text-muted); font-size: 14px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }

  /* CHAT VIEW */
  .chat-container {
    padding: 15px;
    padding-bottom: 20px;
    display: flex;
    flex-direction: column;
  }

  .timestamp {
    text-align: center;
    font-size: 11px;
    color: var(--text-muted);
    margin: 15px 0 5px;
    font-weight: 500;
  }

  .message {
    max-width: 75%;
    padding: 12px 16px; 
    font-size: 16px; 
    font-weight: 500; 
    line-height: 1.4; 
    letter-spacing: 0.3px; 
    color: #ffffff; 
    margin-bottom: 2px;
    position: relative;
    word-wrap: break-word;
  }

  .received {
    background: var(--bubble-received);
    align-self: flex-start;
    border-radius: 18px 18px 18px 4px;
  }

  .sent {
    background: var(--blue);
    align-self: flex-end;
    border-radius: 18px 18px 4px 18px;
  }

  .message img {
    width: 200px;
    border-radius: 12px;
    margin-top: 5px;
    cursor: pointer;
  }

  /* PHOTOS APP */
  .photo-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2px;
    padding-top: 2px;
  }

  .photo-grid img {
    width: 100%;
    aspect-ratio: 1;
    object-fit: cover;
    cursor: pointer;
  }

  .call-type { font-size: 14px; }
  .missed { color: #ff3b30; }

  /* FULLSCREEN IMAGE overlay */
  .fullscreen {
    display: none;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.95);
    justify-content: center;
    align-items: center;
    z-index: 10000;
  }

  .fullscreen img {
    max-width: 100%;
    max-height: 80%;
    object-fit: contain;
  }

  .fullscreen.show { display: flex; }

</style>
</head>
<body>

<div class="phone-hardware">

  <div class="top-camera"></div>
  <div class="top-speaker"></div>

  <div class="home-button" id="homeBtn" title="Single click: Home | Double click: App Switcher">
    <div class="home-button-icon"></div>
  </div>

  <div class="display">

    <div class="status">
      <span>📶 O2-UK</span>
      <span class="status-center">02:14</span>
      <span>12% 🔋</span> 
    </div>

    <div id="switcher" class="screen">
      <div style="flex: 0 0 10px;"></div>
      <a href="#home" class="switcher-card">
        <div class="switcher-title">Home</div>
        <div class="icon-box" style="background: transparent; box-shadow: none;">🏠</div>
      </a>
      <a href="#music-app" class="switcher-card">
        <div class="switcher-title">Music</div>
        <div class="icon-box" style="background:#fa233b;">🎵</div>
      </a>
      <a href="#messages-app" class="switcher-card">
        <div class="switcher-title">Messages</div>
        <div class="icon-box icon-messages">💬</div>
      </a>
      <a href="#photos-app" class="switcher-card">
        <div class="switcher-title">Photos</div>
        <div class="icon-box icon-photos" style="font-size:32px;">🖼️</div>
      </a>
      <a href="#maps-app" class="switcher-card">
        <div class="switcher-title">Maps</div>
        <div class="icon-box" style="background:#30d158;">🗺️</div>
      </a>
      <a href="#notes-app" class="switcher-card">
        <div class="switcher-title">Notes</div>
        <div class="icon-box" style="background:#ffcc00; color:#000;">📝</div>
      </a>
      <div style="flex: 0 0 10px;"></div>
    </div>

    <div id="home" class="screen">
      
      <div class="app-grid">
        <a href="#music-app" class="app-icon"><div class="icon-box" style="background:#fa233b;">🎵</div><span class="app-label">Music</span></a>
        <a href="#calendar-app" class="app-icon"><div class="icon-box" style="background:#fff;">📅</div><span class="app-label">Calendar</span></a>
        <a href="#clock-app" class="app-icon"><div class="icon-box" style="background:#000; border: 1px solid #333;">⏱️</div><span class="app-label">Clock</span></a>
        <a href="#weather-app" class="app-icon"><div class="icon-box" style="background:#0a84ff;">⛅</div><span class="app-label">Weather</span></a>
        <a href="#maps-app" class="app-icon"><div class="icon-box" style="background:#30d158;">🗺️</div><span class="app-label">Maps</span></a>
        <a href="#notes-app" class="app-icon"><div class="icon-box" style="background:#ffcc00; color:#000;">📝</div><span class="app-label">Notes</span></a>
        <a href="#settings-app" class="app-icon"><div class="icon-box" style="background:#8e8e93;">⚙️</div><span class="app-label">Settings</span></a>
        <a href="#camera-app" class="app-icon"><div class="icon-box" style="background:#1c1c1e;">📷</div><span class="app-label">Camera</span></a>
      </div>
      
      <div class="dock">
        <a href="#phone-app" class="app-icon">
          <div class="icon-box icon-phone">📞</div>
          <span class="app-label">Phone</span>
        </a>
        <a href="#messages-app" class="app-icon">
          <div class="icon-box icon-messages">💬</div>
          <span class="app-label">Messages</span>
        </a>
        <a href="#photos-app" class="app-icon">
          <div class="icon-box icon-photos" style="font-size:32px;">🖼️</div>
          <span class="app-label">Photos</span>
        </a>
      </div>
    </div>

    <div id="music-app" class="screen" style="background: #1c1c1e; color: white; overflow: hidden; display: flex; flex-direction: column;">
      <div class="nav-bar" style="background:transparent; border:none; justify-content: flex-start; padding-top: 30px; padding-bottom: 0;">
        <a href="#home" class="back-btn" style="color:var(--text-muted); font-size: 28px; padding: 0 15px; text-decoration: none;">⌄</a>
      </div>
      <div style="flex:1; padding: 15px 25px; display: flex; flex-direction: column; align-items: center; justify-content: center; padding-bottom: 40px;">
        
        <img src="https://i.imgur.com/wDy1cPY.jpeg" alt="Romance Album Cover" style="width: 220px; height: 220px; border-radius: 12px; box-shadow: 0 15px 35px rgba(0,0,0,0.8); margin-bottom: 30px; object-fit: cover; background: #e91e63;">
        
        <div style="width: 100%; text-align: left; margin-bottom: 20px;">
          <div style="font-size: 20px; font-weight: bold; margin-bottom: 5px;">In The Modern World</div>
          <div style="font-size: 16px; color: var(--text-muted);">Fontaines D.C.</div>
        </div>
        
        <div style="width: 100%; height: 5px; background: #333; border-radius: 3px; margin-bottom: 8px; position: relative;">
          <div style="width: 35%; height: 100%; background: #fff; border-radius: 3px;"></div>
          <div style="width: 10px; height: 10px; background: #fff; border-radius: 50%; position: absolute; left: 35%; top: 50%; transform: translate(-50%, -50%); box-shadow: 0 0 5px rgba(0,0,0,0.5);"></div>
        </div>
        
        <div style="width: 100%; display: flex; justify-content: space-between; color: var(--text-muted); font-size: 12px; margin-bottom: 30px; font-weight: 500;">
          <span>1:25</span><span>4:02</span>
        </div>
        
        <div style="width: 100%; display: flex; justify-content: space-around; align-items: center; font-size: 32px; padding: 0 10px;">
          <span style="cursor: pointer;">⏮</span>
          <span style="font-size: 48px; cursor: pointer;">⏸</span>
          <span style="cursor: pointer;">⏭</span>
        </div>
      </div>
    </div>

    <div id="calendar-app" class="screen" style="background:#1c1c1e; overflow: hidden;">
      <div class="app-header" style="background:#1c1c1e; color:#ff3b30; font-size:34px;">April</div>
      <div style="padding:20px; text-align:center; color:white;">
        <div style="font-size:28px; font-weight:bold; margin-bottom: 20px;">Saturday 4th, 2026</div>
        <div style="padding: 15px; background: #2c2c2e; border-radius: 12px; margin-bottom: 10px;">
          <strong style="color:white; font-size:18px;">Fight Night</strong><br>
          <span style="color:var(--text-muted); font-size:14px;">Lido Car Park - 9:00 PM</span>
        </div>
      </div>
    </div>

    <div id="clock-app" class="screen" style="background:#000; color:white; overflow: hidden;">
      <div class="app-header">World Clock</div>
      <div class="list-item" style="border-bottom: 1px solid #333; padding: 20px 15px;">
        <div class="list-content">
          <div class="list-time">Current Location</div>
          <div class="list-name" style="font-size:24px;">London</div>
        </div>
        <div style="font-size: 42px; font-weight:300;">02:14</div>
      </div>
    </div>

    <div id="weather-app" class="screen" style="background: linear-gradient(180deg, #1A2A42 0%, #0A1221 100%); color: white; overflow: hidden;">
      <div style="padding: 60px 20px 20px; text-align: center;">
        <h1 style="margin:0; font-size:36px; font-weight:400;">London</h1>
        <div style="font-size:80px; font-weight:200; margin:-10px 0;">8°</div>
        <h2 style="margin:0; font-size:20px; font-weight:400; color:#ddd;">Cold & Damp</h2>
      </div>
    </div>

    <div id="maps-app" class="screen" style="overflow: hidden;">
      <div style="position: absolute; top:0; width:100%; height:80px; background:linear-gradient(rgba(0,0,0,0.7), transparent); z-index:10; pointer-events:none;"></div>
      <iframe width="100%" height="100%" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://www.openstreetmap.org/export/embed.html?bbox=-0.21852493286132815%2C51.48158580554032%2C-0.03038406372070313%2C51.52972412702446&amp;layer=mapnik" style="border: none;"></iframe>
      <div style="position: absolute; bottom: 30px; left: 50%; transform: translateX(-50%); background: rgba(28, 28, 30, 0.9); padding: 10px 20px; border-radius: 20px; color: white; font-weight: bold; box-shadow: 0 4px 10px rgba(0,0,0,0.5); backdrop-filter: blur(10px);">
        📍 Central London
      </div>
    </div>

    <div id="notes-app" class="screen" style="background:#000; color:white; display:flex; flex-direction:column;">
      
      <div style="flex-shrink:0;">
        <div class="nav-bar" style="background:#000; border:none; padding-bottom:0; justify-content: space-between;">
          <a href="#home" class="back-btn" style="color:var(--yellow); font-size: 17px;">‹ Folders</a>
          <div style="color:var(--yellow); font-size:24px; font-weight:bold; margin-right: 5px; margin-top:-5px;">⋯</div>
        </div>
        <div class="app-header" style="background:#000; border:none; padding-top:5px; padding-bottom: 10px;">Notes</div>
        <div style="padding: 0 15px 15px;">
          <div style="background:#1c1c1e; color:#8e8e93; padding:8px 15px; border-radius:10px; font-size:16px; display:flex; align-items:center;">
            <span style="margin-right:8px; font-size: 14px;">🔍</span> Search
          </div>
        </div>
      </div>
      
      <div style="flex:1; overflow-y:auto; padding: 0 15px 20px;">
        <div style="background:#1c1c1e; border-radius:10px; overflow:hidden;">
          <a href="#note6" class="list-item" style="border-color:#38383a; padding: 12px 15px; display:block;">
            <div class="list-name" style="font-size:16px; margin-bottom:4px; font-weight: bold;">Thoughts</div>
            <div class="list-preview" style="color:#8e8e93; font-size:14px;">
              <span style="color:white; margin-right:5px; font-weight: 500;">02:04</span> I don't feel anything in the mo...
            </div>
          </a>
          <a href="#note1" class="list-item" style="border-color:#38383a; padding: 12px 15px; display:block;">
            <div class="list-name" style="font-size:16px; margin-bottom:4px; font-weight: bold;">Debts</div>
            <div class="list-preview" style="color:#8e8e93; font-size:14px;">
              <span style="color:white; margin-right:5px; font-weight: 500;">20:43</span> i still owe money to old guy wi...
            </div>
          </a>
          <a href="#note2" class="list-item" style="border-color:#38383a; padding: 12px 15px; display:block;">
            <div class="list-name" style="font-size:16px; margin-bottom:4px; font-weight: bold;">Car JJ Tactics</div>
            <div class="list-preview" style="color:#8e8e93; font-size:14px;">
              <span style="color:white; margin-right:5px; font-weight: 500;">Yesterday</span> Reinforce the center console. Use...
            </div>
          </a>
          <a href="#note3" class="list-item" style="border-color:#38383a; padding: 12px 15px; display:block;">
            <div class="list-name" style="font-size:16px; margin-bottom:4px; font-weight: bold;">Vhagar's Schedule</div>
            <div class="list-preview" style="color:#8e8e93; font-size:14px;">
              <span style="color:white; margin-right:5px; font-weight: 500;">Tuesday</span> Mon: Crickets (dusted). Wed:...
            </div>
          </a>
          <a href="#note4" class="list-item" style="border-color:#38383a; padding: 12px 15px; display:block;">
            <div class="list-name" style="font-size:16px; margin-bottom:4px; font-weight: bold;">Heli Parts</div>
            <div class="list-preview" style="color:#8e8e93; font-size:14px;">
              <span style="color:white; margin-right:5px; font-weight: 500;">Monday</span> Order new rotor blades for the...
            </div>
          </a>
          <a href="#note5" class="list-item" style="border-bottom:none; padding: 12px 15px; display:block;">
            <div class="list-name" style="font-size:16px; margin-bottom:4px; font-weight: bold;">Gym Routine</div>
            <div class="list-preview" style="color:#8e8e93; font-size:14px;">
              <span style="color:white; margin-right:5px; font-weight: 500;">Mar 28</span> Chest & Triceps / 4 sets of 12
            </div>
          </a>
        </div>
      </div>

      <div style="flex-shrink:0; background:rgba(28,28,30,0.95); backdrop-filter: blur(15px); padding:15px; padding-bottom: 25px; display:flex; justify-content:space-between; align-items:center; border-top:1px solid #333;">
        <div style="flex:1;"></div>
        <div style="color:white; font-size:12px; font-weight: 500;">6 Notes</div>
        <div style="flex:1; text-align:right; color:var(--yellow); display:flex; justify-content:flex-end;">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M12 20h9"></path>
            <path d="M16.5 3.5a2.12 2.12 0 0 1 3 3L7 19l-4 1 1-4L16.5 3.5z"></path>
          </svg>
        </div>
      </div>
    </div>

    <div id="note6" class="screen" style="background:#000; color:white;">
      <div class="nav-bar" style="background:#000; border:none; padding-bottom:0; justify-content: space-between;">
        <a href="#notes-app" class="back-btn" style="color:var(--yellow); font-size: 17px;">‹ Notes</a>
        <div style="display:flex; gap: 15px; color:var(--yellow); font-size:24px;">
          <span style="font-size: 18px; margin-top:2px;">↑</span>
          <span style="font-weight:bold; margin-top:-5px;">⋯</span>
        </div>
      </div>
      <div style="padding: 20px 15px;">
        <h1 style="margin: 0 0 10px 0; font-size: 26px;">Thoughts</h1>
        <img src="https://images.unsplash.com/photo-1605806616949-1e87b487bc2a?w=800&q=80" style="width: 100%; border-radius: 10px; margin-bottom: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.5);" alt="Moody street lights">
        <p style="font-size: 17px; line-height: 1.5; color: #fff;">
          I don't feel anything in the modern world.<br><br>
          Just the impact. Just the ringing in my ears after the windows break.
        </p>
      </div>
    </div>

    <div id="note1" class="screen" style="background:#000; color:white;">
      <div class="nav-bar" style="background:#000; border:none; padding-bottom:0; justify-content: space-between;">
        <a href="#notes-app" class="back-btn" style="color:var(--yellow); font-size: 17px;">‹ Notes</a>
        <div style="display:flex; gap: 15px; color:var(--yellow); font-size:24px;">
          <span style="font-size: 18px; margin-top:2px;">↑</span>
          <span style="font-weight:bold; margin-top:-5px;">⋯</span>
        </div>
      </div>
      <div style="padding: 20px 15px;">
        <h1 style="margin: 0 0 10px 0; font-size: 26px;">Debts</h1>
        <p style="font-size: 17px; line-height: 1.5; color: #fff;">
          i still owe money to old guy with weird beard.<br><br>
          Need to get it to him soon before he gets annoying about it.
        </p>
      </div>
    </div>

    <div id="note2" class="screen" style="background:#000; color:white;">
      <div class="nav-bar" style="background:#000; border:none; padding-bottom:0; justify-content: space-between;">
        <a href="#notes-app" class="back-btn" style="color:var(--yellow); font-size: 17px;">‹ Notes</a>
        <div style="display:flex; gap: 15px; color:var(--yellow); font-size:24px;">
          <span style="font-size: 18px; margin-top:2px;">↑</span>
          <span style="font-weight:bold; margin-top:-5px;">⋯</span>
        </div>
      </div>
      <div style="padding: 20px 15px;">
        <h1 style="margin: 0 0 10px 0; font-size: 26px;">Car JJ Tactics</h1>
        <p style="font-size: 17px; line-height: 1.5; color: #fff;">
          Next fight is in the old Lido car park.<br><br>
          - Need to reinforce the center console, it cracked last time.<br>
          - Remember to use the seatbelt for leverage on chokes.<br>
          - Watch out for the guy with the modified Audi, he's fast moving from the back seat.
        </p>
      </div>
    </div>

    <div id="note3" class="screen" style="background:#000; color:white;">
      <div class="nav-bar" style="background:#000; border:none; padding-bottom:0; justify-content: space-between;">
        <a href="#notes-app" class="back-btn" style="color:var(--yellow); font-size: 17px;">‹ Notes</a>
        <div style="display:flex; gap: 15px; color:var(--yellow); font-size:24px;">
          <span style="font-size: 18px; margin-top:2px;">↑</span>
          <span style="font-weight:bold; margin-top:-5px;">⋯</span>
        </div>
      </div>
      <div style="padding: 20px 15px;">
        <h1 style="margin: 0 0 10px 0; font-size: 26px;">Vhagar's Schedule</h1>
        <p style="font-size: 17px; line-height: 1.5; color: #fff;">
          <strong>Monday:</strong> Crickets (dusted with calcium)<br>
          <strong>Wednesday:</strong> Mealworms<br>
          <strong>Friday:</strong> Greens (she hates kale, get collard instead)<br><br>
          <em>*Reminder: Check her heat lamp bulb, it's flickering again.</em>
        </p>
      </div>
    </div>

    <div id="note4" class="screen" style="background:#000; color:white;">
      <div class="nav-bar" style="background:#000; border:none; padding-bottom:0; justify-content: space-between;">
        <a href="#notes-app" class="back-btn" style="color:var(--yellow); font-size: 17px;">‹ Notes</a>
        <div style="display:flex; gap: 15px; color:var(--yellow); font-size:24px;">
          <span style="font-size: 18px; margin-top:2px;">↑</span>
          <span style="font-weight:bold; margin-top:-5px;">⋯</span>
        </div>
      </div>
      <div style="padding: 20px 15px;">
        <h1 style="margin: 0 0 10px 0; font-size: 26px;">Heli Parts</h1>
        <p style="font-size: 17px; line-height: 1.5; color: #fff;">
          Order new rotor blades for the Syma.<br><br>
          The battery keeps dying after 5 mins of flight. Look into upgrading the motor or getting a higher capacity LiPo battery online.
        </p>
      </div>
    </div>

    <div id="note5" class="screen" style="background:#000; color:white;">
      <div class="nav-bar" style="background:#000; border:none; padding-bottom:0; justify-content: space-between;">
        <a href="#notes-app" class="back-btn" style="color:var(--yellow); font-size: 17px;">‹ Notes</a>
        <div style="display:flex; gap: 15px; color:var(--yellow); font-size:24px;">
          <span style="font-size: 18px; margin-top:2px;">↑</span>
          <span style="font-weight:bold; margin-top:-5px;">⋯</span>
        </div>
      </div>
      <div style="padding: 20px 15px;">
        <h1 style="margin: 0 0 10px 0; font-size: 26px;">Gym Routine</h1>
        <p style="font-size: 17px; line-height: 1.6; color: #fff;">
          <strong>Chest & Triceps</strong><br><br>
          Bench Press: 4 x 12<br>
          Incline DB Press: 3 x 10<br>
          Cable Flyes: 3 x 15<br>
          Tricep Pushdowns: 4 x 15<br>
          Dips: 3 x failure
        </p>
      </div>
    </div>

    <div id="settings-app" class="screen" style="background:#000; color:white;">
      <div class="app-header" style="background:#000;">Settings</div>
      <div style="margin: 15px; border-radius: 10px; background: #1c1c1e; overflow: hidden;">
        <div class="list-item" style="border-color:#333;">
          <div style="background:#8e8e93; border-radius:5px; width:30px; height:30px; display:flex; justify-content:center; align-items:center; margin-right:15px;">⚙️</div>
          <div class="list-content"><div class="list-name">General</div></div>
        </div>
        <div class="list-item" style="border-color:#333;">
          <div style="background:#0a84ff; border-radius:5px; width:30px; height:30px; display:flex; justify-content:center; align-items:center; margin-right:15px;">📶</div>
          <div class="list-content"><div class="list-name">Wi-Fi (O2-UK)</div></div>
        </div>
        <div class="list-item" style="border-color:#333;">
          <div style="background:#30d158; border-radius:5px; width:30px; height:30px; display:flex; justify-content:center; align-items:center; margin-right:15px;">🔋</div>
          <div class="list-content"><div class="list-name">Battery (12%)</div></div>
        </div>
      </div>
    </div>

    <div id="camera-app" class="screen" style="background: #000; display:flex; flex-direction:column; justify-content:space-between; overflow: hidden;">
      <div style="height: 60px; background: #000; display:flex; justify-content:space-between; padding: 20px 20px 0;">
        <span style="color:white; font-size:24px;">⚡️</span>
        <span style="color:white; font-size:24px;">🔄</span>
      </div>
      <div style="flex:1; border-top: 1px solid #222; border-bottom: 1px solid #222; background: #111; display:flex; justify-content:center; align-items:center;">
        <span style="color:#444; font-size:14px;">[ Viewfinder / Camera Disabled ]</span>
      </div>
      <div style="height: 120px; background: #000; display:flex; justify-content:center; align-items:center;">
        <div style="width: 65px; height: 65px; border-radius: 50%; background: #fff; border: 4px solid #000; outline: 3px solid #fff; cursor: pointer;"></div>
      </div>
    </div>

    <div id="messages-app" class="screen">
      <div class="app-header">Messages</div>
      <a href="#chat1" class="list-item">
        <div class="avatar">👩🏻</div>
        <div class="list-content">
          <div class="list-top"><span class="list-name">Mum 💕</span><span class="list-time">Sat</span></div>
          <div class="list-preview">Just got a call from the Hospital...</div>
        </div>
      </a>
      <a href="#chat2" class="list-item">
        <div class="avatar">🏎️</div>
        <div class="list-content">
          <div class="list-top"><span class="list-name">Matthew🏎️💪🏻</span><span class="list-time">21:14</span></div>
          <div class="list-preview">tell that to the f***ass tube i just missed</div>
        </div>
      </a>
      <a href="#chat3" class="list-item">
        <div class="avatar">#</div>
        <div class="list-content">
          <div class="list-top"><span class="list-name">+44 123456789</span><span class="list-time">Mon</span></div>
          <div class="list-preview">You still owe me 600 quid</div>
        </div>
      </a>
      <a href="#chat4" class="list-item">
        <div class="avatar">⚠️</div>
        <div class="list-content">
          <div class="list-top"><span class="list-name">Spam ⚠️</span><span class="list-time">Thu</span></div>
          <div class="list-preview">Final notice: unpaid invoice detected</div>
        </div>
      </a>
    </div>

    <div id="chat1" class="screen">
      <div class="nav-bar">
        <a href="#messages-app" class="back-btn">‹ Messages</a>
        <div class="chat-title">Mum 💕</div>
      </div>
      <div class="chat-container">
        <div class="timestamp">Monday 14:42</div>
        <div class="message received">Hello Martin, it's Mum💕🌷 How have you been, Darling?</div>
        <div class="timestamp">Wednesday 17:21</div>
        <div class="message received">Martin are you alright? I'm worried about you! Please give me a quick call if you see this!💝💝</div>
        <div class="timestamp">Saturday 22:51</div>
        <div class="message received">Just got a call from the Hospital. Did you do another car fight??? Please tell me you're alright!!💞💞💞Pick up your phone!! I’m so worried Martin!😰</div>
      </div>
    </div>

    <div id="chat2" class="screen">
      <div class="nav-bar">
        <a href="#messages-app" class="back-btn">‹ Messages</a>
        <div class="chat-title">Matthew🏎️💪🏻</div>
      </div>
      <div class="chat-container">
        <div class="timestamp">Saturday 15:03</div>
        <div class="message received">Oi Martin, u up for another fight today??? I could organise one for 9pm at the car park behind the old lido🥷🫯</div>
        <div class="timestamp">Saturday 16:35</div>
        <div class="message sent">yeah count me in…</div>
        <div class="timestamp">Saturday 21:08</div>
        <div class="message received">
          Bro, u better hurry. He is getting MAD mad…<br>
          <img src="https://i.imgur.com/k4xOs4O_d.webp" alt="Car Park" onclick="document.getElementById('img1').classList.add('show')">
        </div>
        <div class="timestamp">Saturday 21:14</div>
        <div class="message sent">
          tell that to the f***ass tube i just missed<br>
          <img src="https://i.imgur.com/LSHDJfW.jpeg" alt="Missed Tube" onclick="document.getElementById('img2').classList.add('show')">
        </div>
      </div>
    </div>

    <div id="chat3" class="screen">
      <div class="nav-bar">
        <a href="#messages-app" class="back-btn">‹ Messages</a>
        <div class="chat-title">+44 123456789</div>
      </div>
      <div class="chat-container">
        <div class="timestamp">Monday 09:13</div>
        <div class="message received">Lefevre for fucks sake</div>
        <div class="message received">You still owe me 600 quid</div>
      </div>
    </div>

    <div id="chat4" class="screen">
      <div class="nav-bar">
        <a href="#messages-app" class="back-btn">‹ Messages</a>
        <div class="chat-title">Spam ⚠️</div>
      </div>
      <div class="chat-container">
        <div class="timestamp">Monday 04:13</div>
        <div class="message received">URGENT: Your bank account has been locked!</div>
        <div class="timestamp">Monday 18:39</div>
        <div class="message received">Click here to verify immediately!</div>
        <div class="timestamp">Tuesday 04:13</div>
        <div class="message received">You have won £5000!!! Claim now!!!</div>
        <div class="timestamp">Thursday 22:26</div>
        <div class="message received">Final notice: unpaid invoice detected</div>
      </div>
    </div>

    <div id="photos-app" class="screen">
      <div class="app-header" style="font-size: 24px;">Library</div>
      <div class="photo-grid">
        <img src="https://i.imgur.com/k4xOs4O_d.webp" onclick="document.getElementById('img1').classList.add('show')">
        <img src="https://i.imgur.com/LSHDJfW.jpeg" onclick="document.getElementById('img2').classList.add('show')">
      </div>
    </div>

    <div id="phone-app" class="screen">
      <div class="app-header" style="font-size: 24px;">Recents</div>
      <div class="list-item">
        <div class="list-content">
          <div class="list-top"><span class="list-name missed">Mum 💕</span><span class="list-time">Sat</span></div>
          <div class="call-type missed">Missed Call</div>
        </div>
      </div>
      <div class="list-item">
        <div class="list-content">
          <div class="list-top"><span class="list-name missed">Mum 💕</span><span class="list-time">Sat</span></div>
          <div class="call-type missed">Missed Call</div>
        </div>
      </div>
      <div class="list-item">
        <div class="list-content">
          <div class="list-top"><span class="list-name">Matthew🏎️💪🏻</span><span class="list-time">Sat</span></div>
          <div class="call-type">Outgoing Call</div>
        </div>
      </div>
      <div class="list-item">
        <div class="list-content">
          <div class="list-top"><span class="list-name missed">+44 123456789</span><span class="list-time">Mon</span></div>
          <div class="call-type missed">Missed Call</div>
        </div>
      </div>
    </div>

    <div id="img1" class="fullscreen" onclick="this.classList.remove('show')">
      <img src="https://i.imgur.com/k4xOs4O_d.webp" alt="Car Park">
    </div>
    <div id="img2" class="fullscreen" onclick="this.classList.remove('show')">
      <img src="https://i.imgur.com/LSHDJfW.jpeg" alt="Missed Tube">
    </div>

  </div>
</div>

<script>
  // Robust Home Button Logic
  const homeBtn = document.getElementById('homeBtn');
  let clickCount = 0;
  let clickTimer = null;

  homeBtn.addEventListener('click', (e) => {
    e.preventDefault();
    clickCount++;
    
    if (clickCount === 1) {
      // Wait to see if a second click happens
      clickTimer = setTimeout(() => {
        clickCount = 0; // Reset counter
        // Single Click -> Go Home
        window.location.hash = '#home';
      }, 250); 
    } else if (clickCount === 2) {
      // Double Click detected! Clear the timer so the single-click action doesn't fire
      clearTimeout(clickTimer);
      clickCount = 0; // Reset counter
      // Double Click -> Open Switcher
      window.location.hash = '#switcher';
    }
  });
</script>

</body>
</html>

