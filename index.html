<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Notes - Google Docs</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    background: #f0f4f8;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  #app {
    width: 420px;
    height: 580px;
    background: #1a1a2e;
    border-radius: 16px;
    display: flex;
    flex-direction: column;
    overflow: hidden;
    box-shadow: 0 20px 60px rgba(0,0,0,0.4);
  }

  #titlebar {
    display: flex;
    align-items: center;
    gap: 8px;
    padding: 14px 16px 10px;
    border-bottom: 1px solid rgba(255,255,255,0.08);
    flex-shrink: 0;
  }

  .dot { width: 8px; height: 8px; border-radius: 50%; background: #7c3aed; flex-shrink: 0; }

  #titlebar span {
    font-size: 13px;
    font-weight: 600;
    color: rgba(255,255,255,0.85);
    flex: 1;
  }

  #close-btn {
    background: none;
    border: none;
    cursor: pointer;
    color: rgba(255,255,255,0.3);
    font-size: 18px;
    line-height: 1;
    padding: 0 2px;
    transition: color 0.2s;
  }
  #close-btn:hover { color: rgba(255,255,255,0.7); }

  #key-screen {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 16px;
    padding: 24px;
  }

  #key-screen .icon { font-size: 36px; }

  #key-screen h2 {
    font-size: 15px;
    font-weight: 600;
    color: rgba(255,255,255,0.9);
    text-align: center;
  }

  #key-screen p {
    font-size: 12px;
    color: rgba(255,255,255,0.35);
    text-align: center;
  }

  #key-input {
    width: 100%;
    background: rgba(255,255,255,0.07);
    border: 1px solid rgba(255,255,255,0.12);
    border-radius: 8px;
    padding: 10px 12px;
    font-size: 12px;
    font-family: monospace;
    color: white;
    outline: none;
  }
  #key-input:focus { border-color: #7c3aed; }
  #key-input::placeholder { color: rgba(255,255,255,0.25); }

  .pill-btn {
    background: rgba(124,58,237,0.7);
    border: none;
    border-radius: 999px;
    color: white;
    font-size: 13px;
    font-weight: 500;
    padding: 10px 28px;
    cursor: pointer;
    transition: background 0.2s;
  }
  .pill-btn:hover { background: rgba(124,58,237,0.9); }
  .pill-btn:disabled { opacity: 0.4; cursor: not-allowed; }

  #chat-screen {
    flex: 1;
    display: flex;
    flex-direction: column;
    overflow: hidden;
  }

  #messages {
    flex: 1;
    overflow-y: auto;
    padding: 14px;
    display: flex;
    flex-direction: column;
    gap: 12px;
    scroll-behavior: smooth;
  }

  #messages::-webkit-scrollbar { width: 4px; }
  #messages::-webkit-scrollbar-track { background: transparent; }
  #messages::-webkit-scrollbar-thumb { background: rgba(255,255,255,0.15); border-radius: 4px; }

  .empty-state {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 10px;
    opacity: 0.3;
    padding-top: 60px;
  }
  .empty-state .big-icon { font-size: 32px; }
  .empty-state p { font-size: 13px; color: white; }

  .msg {
    display: flex;
    max-width: 88%;
  }
  .msg.user { align-self: flex-end; }
  .msg.assistant { align-self: flex-start; }

  .bubble {
    padding: 9px 13px;
    border-radius: 13px;
    font-size: 13px;
    line-height: 1.5;
    white-space: pre-wrap;
    word-break: break-word;
    user-select: text;
  }

  .msg.user .bubble {
    background: rgba(124,58,237,0.65);
    color: white;
    border-bottom-right-radius: 4px;
  }

  .msg.assistant .bubble {
    background: rgba(255,255,255,0.08);
    color: rgba(255,255,255,0.88);
    border-bottom-left-radius: 4px;
  }

  .typing-dots {
    display: flex;
    gap: 4px;
    padding: 12px 14px;
    background: rgba(255,255,255,0.08);
    border-radius: 13px;
    border-bottom-left-radius: 4px;
    align-self: flex-start;
  }
  .typing-dots span {
    width: 6px; height: 6px;
    background: rgba(124,58,237,0.8);
    border-radius: 50%;
    animation: bounce 1.2s infinite;
  }
  .typing-dots span:nth-child(2) { animation-delay: 0.2s; }
  .typing-dots span:nth-child(3) { animation-delay: 0.4s; }

  @keyframes bounce {
    0%, 60%, 100% { transform: translateY(0); }
    30% { transform: translateY(-6px); }
  }

  #input-bar {
    display: flex;
    align-items: flex-end;
    gap: 10px;
    padding: 10px 14px;
    border-top: 1px solid rgba(255,255,255,0.08);
    flex-shrink: 0;
  }

  #msg-input {
    flex: 1;
    background: transparent;
    border: none;
    outline: none;
    color: white;
    font-size: 13px;
    font-family: inherit;
    resize: none;
    line-height: 1.5;
    max-height: 100px;
    overflow-y: auto;
  }
  #msg-input::placeholder { color: rgba(255,255,255,0.25); }

  #send-btn {
    background: none;
    border: none;
    cursor: pointer;
    padding: 4px;
    color: rgba(255,255,255,0.2);
    font-size: 22px;
    line-height: 1;
    transition: color 0.2s;
    flex-shrink: 0;
  }
  #send-btn.active { color: #7c3aed; }
  #send-btn:disabled { cursor: not-allowed; }

  #footer {
    display: flex;
    justify-content: space-between;
    padding: 6px 16px 12px;
    flex-shrink: 0;
  }
  #footer button {
    background: none;
    border: none;
    cursor: pointer;
    font-size: 11px;
    color: rgba(255,255,255,0.25);
    transition: color 0.2s;
  }
  #footer button:hover { color: rgba(255,255,255,0.5); }

  #hotkey-hint {
    position: fixed;
    bottom: 16px;
    right: 16px;
    background: rgba(0,0,0,0.6);
    color: rgba(255,255,255,0.5);
    font-size: 11px;
    padding: 6px 10px;
    border-radius: 8px;
    pointer-events: none;
  }

  #app.hidden { display: none; }
</style>
</head>
<body>

<div id="app">
  <div id="titlebar">
    <div class="dot"></div>
    <span>Jeren's Stealth AI</span>
    <button id="close-btn" title="Hide (Ctrl+Shift+Space)">×</button>
  </div>

  <div id="key-screen" style="display:none;">
    <div class="icon">🔑</div>
    <h2>Enter your Anthropic API Key</h2>
    <p>Get one free at console.anthropic.com</p>
    <input type="password" id="key-input" placeholder="sk-ant-..." autocomplete="off" />
    <button class="pill-btn" id="save-key-btn" disabled>Save Key</button>
  </div>

  <div id="chat-screen" style="display:none;">
    <div id="messages">
      <div class="empty-state" id="empty-state">
        <div class="big-icon">💬</div>
        <p>Ask me anything</p>
      </div>
    </div>
    <div id="input-bar">
      <textarea id="msg-input" placeholder="Ask anything..." rows="1"></textarea>
      <button id="send-btn" disabled>↑</button>
    </div>
    <div id="footer">
      <button id="clear-btn">Clear</button>
      <button id="change-key-btn">API Key</button>
    </div>
  </div>
</div>

<div id="hotkey-hint">Ctrl+Shift+Space to toggle</div>

<script>
  const app = document.getElementById('app');
  const keyScreen = document.getElementById('key-screen');
  const chatScreen = document.getElementById('chat-screen');
  const keyInput = document.getElementById('key-input');
  const saveKeyBtn = document.getElementById('save-key-btn');
  const messagesEl = document.getElementById('messages');
  const emptyState = document.getElementById('empty-state');
  const msgInput = document.getElementById('msg-input');
  const sendBtn = document.getElementById('send-btn');
  const clearBtn = document.getElementById('clear-btn');
  const changeKeyBtn = document.getElementById('change-key-btn');
  const closeBtn = document.getElementById('close-btn');

  let apiKey = localStorage.getItem('jsa_key') || '';
  let messages = [];
  let loading = false;

  function init() {
    if (apiKey) {
      showChat();
    } else {
      showKeyScreen();
    }
  }

  function showKeyScreen() {
    keyScreen.style.display = 'flex';
    chatScreen.style.display = 'none';
    keyInput.focus();
  }

  function showChat() {
    keyScreen.style.display = 'none';
    chatScreen.style.display = 'flex';
    msgInput.focus();
  }

  keyInput.addEventListener('input', () => {
    saveKeyBtn.disabled = keyInput.value.trim().length < 10;
  });

  saveKeyBtn.addEventListener('click', () => {
    apiKey = keyInput.value.trim();
    localStorage.setItem('jsa_key', apiKey);
    showChat();
  });

  keyInput.addEventListener('keydown', e => {
    if (e.key === 'Enter' && !saveKeyBtn.disabled) saveKeyBtn.click();
  });

  msgInput.addEventListener('input', () => {
    sendBtn.disabled = msgInput.value.trim() === '' || loading;
    sendBtn.className = (!msgInput.value.trim() || loading) ? '' : 'active';
    msgInput.style.height = 'auto';
    msgInput.style.height = Math.min(msgInput.scrollHeight, 100) + 'px';
  });

  msgInput.addEventListener('keydown', e => {
    if (e.key === 'Enter' && !e.shiftKey) {
      e.preventDefault();
      if (!sendBtn.disabled) sendMessage();
    }
  });

  sendBtn.addEventListener('click', sendMessage);
  clearBtn.addEventListener('click', () => {
    messages = [];
    messagesEl.innerHTML = '';
    messagesEl.appendChild(emptyState);
    emptyState.style.display = 'flex';
  });
  changeKeyBtn.addEventListener('click', showKeyScreen);
  closeBtn.addEventListener('click', () => app.classList.toggle('hidden'));

  document.addEventListener('keydown', e => {
    if (e.ctrlKey && e.shiftKey && e.code === 'Space') {
      e.preventDefault();
      app.classList.toggle('hidden');
      if (!app.classList.contains('hidden')) msgInput.focus();
    }
  });

  function addMessage(role, text) {
    emptyState.style.display = 'none';
    const msg = document.createElement('div');
    msg.className = `msg ${role}`;
    const bubble = document.createElement('div');
    bubble.className = 'bubble';
    bubble.textContent = text;
    msg.appendChild(bubble);
    messagesEl.appendChild(msg);
    messagesEl.scrollTop = messagesEl.scrollHeight;
    return bubble;
  }

  function showTyping() {
    emptyState.style.display = 'none';
    const dots = document.createElement('div');
    dots.className = 'typing-dots';
    dots.id = 'typing';
    dots.innerHTML = '<span></span><span></span><span></span>';
    messagesEl.appendChild(dots);
    messagesEl.scrollTop = messagesEl.scrollHeight;
  }

  function removeTyping() {
    const dots = document.getElementById('typing');
    if (dots) dots.remove();
  }

  async function sendMessage() {
    const text = msgInput.value.trim();
    if (!text || loading) return;

    messages.push({ role: 'user', content: text });
    addMessage('user', text);
    msgInput.value = '';
    msgInput.style.height = 'auto';
    sendBtn.disabled = true;
    sendBtn.className = '';
    loading = true;
    showTyping();

    try {
      const res = await fetch('https://api.anthropic.com/v1/messages', {
        method: 'POST',
        headers: {
          'Content-Type': 'application/json',
          'x-api-key': apiKey,
          'anthropic-version': '2023-06-01',
          'anthropic-dangerous-allow-browser': 'true'
        },
        body: JSON.stringify({
          model: 'claude-sonnet-4-20250514',
          max_tokens: 1024,
          messages: messages
        })
      });

      const data = await res.json();
      removeTyping();

      if (data.content && data.content[0]) {
        const reply = data.content[0].text;
        messages.push({ role: 'assistant', content: reply });
        addMessage('assistant', reply);
      } else if (data.error) {
        addMessage('assistant', 'Error: ' + data.error.message);
      }
    } catch (err) {
      removeTyping();
      addMessage('assistant', 'Connection error. Check your internet and API key.');
    }

    loading = false;
    msgInput.focus();
  }

  init();
</script>
</body>
</html>
