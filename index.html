<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
    <title>mc玩家自制社区</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        *{margin:0;padding:0;box-sizing:border-box}
        body{font-family:-apple-system,sans-serif;background:#f0ece6;padding:16px;color:#2c2721;display:flex;justify-content:center}
        .container{max-width:1000px;width:100%}
        .header{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;margin-bottom:20px;padding-bottom:10px;border-bottom:2px solid #d5cdc0}
        .logo{font-size:22px;font-weight:700}
        .btn{padding:8px 20px;border-radius:30px;border:none;font-weight:600;font-size:14px;cursor:pointer}
        .btn-dark{background:#3d372e;color:#f5efe6}
        .btn-dark:hover{background:#2d2821}
        .btn-gray{background:#e3dbce;color:#3b3329}
        .btn:disabled{opacity:.5;cursor:not-allowed}
        .user-badge{display:flex;align-items:center;gap:8px;background:#e8e0d4;padding:4px 14px 4px 10px;border-radius:30px}
        .user-badge .name{font-weight:600;font-size:14px}
        .logout-btn{background:0 0;border:none;color:#6b5f4f;cursor:pointer}
        .card{background:#fefcf8;border-radius:20px;padding:18px;border:1px solid #e8e1d6;margin-bottom:18px}
        .card h2{font-size:17px;margin-bottom:14px}
        .row{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:10px}
        .row .field{flex:1;min-width:130px}
        .row .field label{display:block;font-size:12px;font-weight:600;color:#5a4f42;margin-bottom:3px}
        .row .field input,.row .field select,.row .field textarea{width:100%;padding:8px 14px;border-radius:24px;border:1.5px solid #e0d8cc;background:#faf8f4;font-size:14px;outline:0;font-family:inherit}
        .row .field textarea{min-height:50px;resize:vertical}
        .file-btn{display:inline-block;padding:6px 14px;border-radius:30px;background:#eae3d7;border:1px solid #d6ccbb;cursor:pointer;font-size:13px}
        .file-btn:hover{background:#ddd4c5}
        .file-preview{max-width:80px;max-height:70px;border-radius:10px;margin-top:4px;display:none}
        .file-name{font-size:12px;color:#7c7161;margin-top:3px}
        .pills{display:flex;flex-wrap:wrap;gap:5px 8px;margin-bottom:14px}
        .pill{padding:4px 14px;border-radius:30px;font-size:13px;font-weight:500;background:#e8e1d6;border:1px solid #d5ccbe;cursor:pointer}
        .pill.active{background:#3d372e;color:#f5efe6;border-color:#3d372e}
        .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:14px}
        .post{background:#f8f4ee;border-radius:18px;padding:14px;border:1px solid #e6ded2}
        .post .tag{font-size:11px;font-weight:600;background:#d8cfc0;padding:2px 10px;border-radius:20px;display:inline-block}
        .post .ver{font-size:10px;background:#cbc0b0;padding:1px 8px;border-radius:20px;margin-left:4px}
        .post h4{font-size:15px;margin:6px 0 4px}
        .post .desc{font-size:13px;color:#4d4338;margin:4px 0 6px}
        .post .img{max-width:100%;border-radius:12px;max-height:100px;object-fit:cover;margin:4px 0}
        .post .link{display:inline-block;background:#2b261f;color:#f0ebe2;padding:2px 12px;border-radius:30px;font-size:11px;text-decoration:none;margin:3px 0}
        .post .download{display:inline-block;background:#4a7a5c;color:#fff;padding:2px 12px;border-radius:30px;font-size:11px;text-decoration:none;margin:3px 0}
        .post .author{font-size:12px;color:#7c7161;margin-top:4px}
        .comments{margin-top:10px;border-top:1px solid #e0d7c8;padding-top:8px}
        .comments .input-area{display:flex;gap:6px;flex-wrap:wrap}
        .comments .input-area input{flex:1;padding:4px 12px;border-radius:30px;border:1.5px solid #e0d8cc;font-size:13px;outline:0;min-width:70px}
        .comments .input-area button{background:#3d372e;color:#fff;border:none;padding:4px 14px;border-radius:30px;font-weight:600;font-size:12px;cursor:pointer}
        .comment-item{font-size:12px;padding:3px 0;border-bottom:1px dashed #e5ddd0}
        .comment-item .cname{font-weight:600}
        .empty{text-align:center;padding:30px 16px;color:#6e6354}
        .empty i{font-size:36px;opacity:.2;margin-bottom:8px}
        .modal{position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,.4);backdrop-filter:blur(4px);display:none;align-items:center;justify-content:center;z-index:999;padding:16px}
        .modal-box{background:#fefcf8;max-width:380px;width:100%;padding:24px;border-radius:28px}
        .modal-box h2{margin-bottom:14px}
        .modal-box .field{margin-bottom:12px}
        .modal-box .field input{width:100%;padding:10px 16px;border-radius:30px;border:1.5px solid #e0d8cc;font-size:14px;outline:0}
        .modal-box .actions{display:flex;gap:8px;margin-top:16px}
        .modal-box .actions button{flex:1;padding:10px;border-radius:30px;border:none;font-weight:600;cursor:pointer}
        .switch{text-align:center;margin-top:10px;font-size:14px;color:#5f5445}
        .switch span{color:#3d372e;font-weight:600;cursor:pointer}
        .toast{position:fixed;bottom:30px;left:50%;transform:translateX(-50%);background:#2c2721;color:#f5efe6;padding:10px 24px;border-radius:30px;font-size:14px;z-index:1000;box-shadow:0 8px 24px rgba(0,0,0,.3);display:none;max-width:90%;text-align:center}
        .toast.show{display:block}
        @media(max-width:640px){.row .field{flex:1 1 100%}.grid{grid-template-columns:1fr}.header{flex-direction:column;align-items:flex-start;gap:8px}}
    </style>
</head>
<body>
<div class="container">
    <header class="header">
        <div class="logo">🧱 mc玩家自制社区</div>
        <div class="user-area" id="headerRight"></div>
    </header>

    <div class="card">
        <h2>📝 发布资源</h2>
        <div class="row">
            <div class="field">
                <label>分类</label>
                <select id="categorySelect">
                    <option value="投影">📐 投影</option>
                    <option value="指令">⚡ 指令</option>
                    <option value="建筑">🏛️ 建筑</option>
                    <option value="机制">⚙️ 机制</option>
                    <option value="光影">☀️ 光影</option>
                    <option value="其他">📁 其他</option>
                </select>
            </div>
            <div class="field">
                <label>版本</label>
                <select id="versionSelect">
                    <option value="全版本">全版本</option>
                    <option value="1.21+">1.21+</option>
                    <option value="1.21.4">1.21.4</option>
                    <option value="1.21.3">1.21.3</option>
                    <option value="1.21.2">1.21.2</option>
                    <option value="1.21.1">1.21.1</option>
                    <option value="1.21">1.21</option>
                    <option value="1.20.6">1.20.6</option>
                    <option value="1.20.5">1.20.5</option>
                    <option value="1.20.4">1.20.4</option>
                    <option value="1.20.3">1.20.3</option>
                    <option value="1.20.2">1.20.2</option>
                    <option value="1.20.1">1.20.1</option>
                    <option value="1.20">1.20</option>
                    <option value="1.19.4">1.19.4</option>
                    <option value="1.19.3">1.19.3</option>
                    <option value="1.19.2">1.19.2</option>
                    <option value="1.19.1">1.19.1</option>
                    <option value="1.19">1.19</option>
                    <option value="1.18.2">1.18.2</option>
                    <option value="1.18.1">1.18.1</option>
                    <option value="1.18">1.18</option>
                    <option value="1.17.1">1.17.1</option>
                    <option value="1.17">1.17</option>
                    <option value="1.16.5">1.16.5</option>
                </select>
            </div>
            <div class="field">
                <label>标题 *</label>
                <input type="text" id="titleInput" placeholder="资源名称">
            </div>
        </div>
        <div class="row">
            <div class="field" style="flex:2;">
                <label>描述</label>
                <textarea id="descInput" placeholder="简单介绍……"></textarea>
            </div>
        </div>
        <div class="row">
            <div class="field">
                <label>📷 截图</label>
                <span class="file-btn" id="imageUploadBtn">选择图片</span>
                <input type="file" id="imageInput" accept="image/*" style="display:none;">
                <img id="imagePreview" class="file-preview">
            </div>
            <div class="field">
                <label>🔗 网址</label>
                <input type="url" id="urlInput" placeholder="https://example.com">
            </div>
        </div>
        <div class="row">
            <div class="field">
                <label>📦 上传文件（供下载）</label>
                <span class="file-btn" id="fileUploadBtn">选择文件</span>
                <input type="file" id="fileInput" style="display:none;">
                <div class="file-name" id="fileNameDisplay">未选择文件</div>
            </div>
        </div>
        <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap;margin-top:4px;">
            <button class="btn btn-dark" id="publishBtn"><i class="fas fa-cloud-upload-alt"></i> 发布</button>
            <span style="font-size:13px;color:#857b6d;" id="publishHint">登录后发布</span>
            <span id="loadingTip" style="font-size:13px;color:#8f8476;display:none;">⏳ 发布中...</span>
        </div>
    </div>

    <div class="pills" id="categoryPills">
        <span class="pill active" data-cat="全部">全部</span>
        <span class="pill" data-cat="投影">投影</span>
        <span class="pill" data-cat="指令">指令</span>
        <span class="pill" data-cat="建筑">建筑</span>
        <span class="pill" data-cat="机制">机制</span>
        <span class="pill" data-cat="光影">光影</span>
        <span class="pill" data-cat="其他">其他</span>
    </div>

    <div class="card">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px;">
            <h3>📋 最新分享</h3>
            <span style="font-size:13px;color:#8f8476;" id="categoryHint">全部</span>
        </div>
        <div id="emptyState" class="empty">
            <i class="fas fa-cube"></i>
            <p><strong>暂无玩家上传</strong><br>登录后分享你的创造</p>
        </div>
        <div id="uploadList" class="grid" style="display:none;"></div>
    </div>
    <div style="text-align:center;color:#8f8476;font-size:12px;border-top:1px solid #e1d8cb;padding-top:14px;margin-top:10px;">数据存储在 GitHub Issues · 电脑/手机通用</div>
</div>

<div class="toast" id="toast"></div>

<div class="modal" id="authModal">
    <div class="modal-box">
        <h2 id="modalTitle">🔑 登录</h2>
        <div class="field">
            <input type="text" id="authUsername" placeholder="玩家名称">
        </div>
        <div class="field">
            <input type="password" id="authPassword" placeholder="密码">
        </div>
        <div class="actions">
            <button id="authPrimaryBtn" class="btn btn-dark">登录</button>
            <button id="authSecondaryBtn" class="btn btn-gray">注册</button>
        </div>
        <div class="switch" id="switchAction">
            <span id="switchText">还没有账号？ 注册</span>
        </div>
    </div>
</div>

<script>
    // ================================================================
    //  ⚙️ 配置（您只需要改这一个地方）
    // ================================================================
    const CONFIG = {
        GITHUB_USER: 'daitoue3581',
        GITHUB_REPO: 'mccmmunity',
        GITHUB_TOKEN: '请在这里粘贴您新生成的Token'  // ← 替换成新 Token
    };
    // ================================================================

    const $ = id => document.getElementById(id);
    const showToast = (msg, duration = 3000) => {
        const t = $('toast');
        t.textContent = msg;
        t.classList.add('show');
        clearTimeout(t._timer);
        t._timer = setTimeout(() => t.classList.remove('show'), duration);
    };

    let currentUser = null, allPosts = [], currentCategory = '全部';
    const API = `https://api.github.com/repos/${CONFIG.GITHUB_USER}/${CONFIG.GITHUB_REPO}`;

    function loadSession() { try { const d = localStorage.getItem('mc_user'); if (d) currentUser = JSON.parse(d); } catch (e) {} }
    function saveSession() { localStorage.setItem('mc_user', JSON.stringify(currentUser)); }
    function clearSession() { localStorage.removeItem('mc_user');
        currentUser = null; }

    async function ghRequest(endpoint, options = {}) {
        const headers = { 'Authorization': `token ${CONFIG.GITHUB_TOKEN}`, 'Accept': 'application/vnd.github.v3+json',
            'Content-Type': 'application/json' };
        const res = await fetch(API + endpoint, { ...options, headers });
        if (!res.ok) { const err = await res.text(); throw new Error(`GitHub API 错误 (${res.status}): ${err}`); }
        return res.json();
    }

    async function loadPosts() {
        try {
            const issues = await ghRequest('/issues?state=all&per_page=100');
            allPosts = issues.filter(i => i.labels && i.labels.length > 0).map(i => {
                const label = i.labels[0]?.name || '其他';
                let ver = '全版本',
                    desc = '',
                    url = '',
                    img = '',
                    fname = '',
                    fdata = '';
                (i.body || '').split('\n').forEach(line => {
                    if (line.startsWith('版本:')) ver = line.replace('版本:', '').trim();
                    if (line.startsWith('描述:')) desc = line.replace('描述:', '').trim();
                    if (line.startsWith('网址:')) url = line.replace('网址:', '').trim();
                    if (line.startsWith('图片:')) img = line.replace('图片:', '').trim();
                    if (line.startsWith('文件:')) { const p = line.replace('文件:', '').trim().split('|');
                        fname = p[0] || '';
                        fdata = p[1] || ''; }
                });
                return { id: i.number, title: i.title, category: label, version: ver, description: desc, url: url,
                    image_url: img || null, file_name: fname || null, file_data: fdata || null,
                author: i.user?.login || '匿名', created_at: i.created_at };
            });
            renderPosts();
        } catch (e) {
            console.error(e);
            showToast('加载失败: ' + e.message, 5000);
            $('emptyState').innerHTML = `<i class="fas fa-exclamation-triangle"></i><p>加载失败: ${e.message}</p>`;
            $('emptyState').style.display = 'block';
            $('uploadList').style.display = 'none';
        }
    }

    async function publishPost(data) {
        let body =
            `分类: ${data.category}\n版本: ${data.version}\n描述: ${data.desc || '无'}\n网址: ${data.url || '无'}\n`;
        if (data.image) body += `图片: ${data.image}\n`;
        if (data.fileData && data.fileName) body += `文件: ${data.fileName}|${data.fileData}\n`;
        body += `\n---\n发布于: ${new Date().toISOString()}`;
        return await ghRequest('/issues', { method: 'POST', body: JSON.stringify({ title: data.title || '无标题',
                body: body, labels: [data.category] }) });
    }

    async function addComment(issueNumber, content) {
        return await ghRequest(`/issues/${issueNumber}/comments`, { method: 'POST', body: JSON.stringify({ body: content }) });
    }

    async function loadComments(issueId) {
        try {
            const comments = await ghRequest(`/issues/${issueId}/comments`);
            const container = document.getElementById(`cmt_list_${issueId}`);
            if (!container) return;
            if (comments.length === 0) { container.innerHTML =
                    '<div style="font-size:12px;color:#8f8476;padding:4px 0;">暂无评论</div>'; return; }
            container.innerHTML = comments.map(c =>
                `<div class="comment-item"><span class="cname">${c.user?.login || '匿名'}</span> ${c.body}</div>`).join('');
        } catch (e) { console.error(e); }
    }

    window._addComment = async function(issueId) {
        if (!currentUser) { showToast('请先登录'); return; }
        const input = document.getElementById(`cmt_${issueId}`);
        const text = input.value.trim();
        if (!text) return;
        try { await addComment(issueId, text);
            input.value = '';
            loadComments(issueId);
            showToast('✅ 评论成功'); } catch (e) { showToast('❌ 评论失败: ' + e.message); }
    };

    function renderPosts() {
        const filtered = currentCategory === '全部' ? allPosts : allPosts.filter(p => p.category === currentCategory);
        const list = $('uploadList'),
            empty = $('emptyState');
        list.innerHTML = '';
        if (filtered.length === 0) {
            empty.style.display = 'block';
            list.style.display = 'none';
            empty.innerHTML = currentCategory === '全部' ?
                `<i class="fas fa-cube"></i><p><strong>暂无玩家上传</strong><br>登录后分享你的创造</p>` :
                `<i class="fas fa-search"></i><p><strong>没有"${currentCategory}"分类的内容</strong></p>`;
            return;
        }
        empty.style.display = 'none';
        list.style.display = 'grid';
        filtered.forEach(post => {
            const div = document.createElement('div');
            div.className = 'post';
            div.innerHTML = `
                <span class="tag">${post.category}</span>
                <span class="ver">${post.version}</span>
                <h4>${post.title}</h4>
                ${post.description ? `<div class="desc">${post.description}</div>` : ''}
                ${post.image_url ? `<img class="img" src="${post.image_url}" onerror="this.style.display='none'">` : ''}
                ${post.url ? `<a class="link" href="${post.url}" target="_blank">🔗 访问网址</a>` : ''}
                ${post.file_data && post.file_name ? `<a class="download" href="${post.file_data}" download="${post.file_name}">⬇ 下载 ${post.file_name}</a>` : ''}
                <div class="author">👤 ${post.author}</div>
                <div class="comments">
                    <div class="input-area">
                        <input type="text" placeholder="写评论..." id="cmt_${post.id}">
                        <button onclick="window._addComment(${post.id})">发送</button>
                    </div>
                    <div id="cmt_list_${post.id}"></div>
                </div>
            `;
            list.appendChild(div);
            loadComments(post.id);
        });
        $('categoryHint').textContent = currentCategory;
    }

    function renderHeader() {
        const right = $('headerRight');
        if (currentUser) {
            right.innerHTML =
                `<div class="user-badge"><span class="name">${currentUser.username}</span><button class="logout-btn" id="logoutBtn"><i class="fas fa-sign-out-alt"></i></button></div>`;
            document.getElementById('logoutBtn')?.addEventListener('click', () => { clearSession();
                renderHeader();
                updatePublishHint(); });
        } else {
            right.innerHTML = `<button class="btn btn-dark" id="loginOpenBtn">登录 / 注册</button>`;
            document.getElementById('loginOpenBtn')?.addEventListener('click', () => openModal(true));
        }
    }

    function updatePublishHint() {
        const hint = $('publishHint'),
            btn = $('publishBtn');
        if (currentUser) { hint.textContent = '✅ 已登录，可发布';
            btn.disabled = false; } else { hint.textContent = '🔒 登录后发布';
            btn.disabled = true; }
    }

    let isLoginMode = true;

    function openModal(loginMode = true) {
        isLoginMode = loginMode;
        $('authModal').style.display = 'flex';
        if (isLoginMode) {
            $('modalTitle').textContent = '🔑 登录';
            $('authPrimaryBtn').textContent = '登录';
            $('authSecondaryBtn').textContent = '注册';
            $('switchText').textContent = '还没有账号？ 注册';
        } else {
            $('modalTitle').textContent = '📝 注册';
            $('authPrimaryBtn').textContent = '注册';
            $('authSecondaryBtn').textContent = '登录';
            $('switchText').textContent = '已有账号？ 登录';
        }
        $('authUsername').value = '';
        $('authPassword').value = '';
    }

    function closeModal() { $('authModal').style.display = 'none'; }

    let userDB = [];

    function loadUserDB() { try { const d = localStorage.getItem('mc_user_db'); if (d) userDB = JSON.parse(d); } catch (e) {} }

    function saveUserDB() { localStorage.setItem('mc_user_db', JSON.stringify(userDB)); }

    function findUser(name) { return userDB.find(u => u.username === name); }

    $('authPrimaryBtn').addEventListener('click', function() {
        const username = $('authUsername').value.trim(),
            password = $('authPassword').value.trim();
        if (!username || !password) { showToast('请填写完整'); return; }
        if (isLoginMode) {
            const user = findUser(username);
            if (!user) { showToast('账号不存在'); return; }
            if (user.password !== password) { showToast('密码错误'); return; }
            currentUser = { username };
            saveSession();
            closeModal();
            renderHeader();
            updatePublishHint();
            showToast('✅ 登录成功');
        } else {
            if (findUser(username)) { showToast('账号已存在'); return; }
            if (username.length < 2) { showToast('名称至少2个字符'); return; }
            userDB.push({ username, password });
            saveUserDB();
            currentUser = { username };
            saveSession();
            closeModal();
            renderHeader();
            updatePublishHint();
            showToast('🎉 注册成功！已自动登录');
        }
    });

    $('authSecondaryBtn').addEventListener('click', () => { isLoginMode = !isLoginMode;
        openModal(isLoginMode); });
    $('switchAction').addEventListener('click', () => { isLoginMode = !isLoginMode;
        openModal(isLoginMode); });
    $('authModal').addEventListener('click', (e) => { if (e.target === $('authModal')) closeModal(); });

    $('imageUploadBtn').addEventListener('click', () => { if (!currentUser) { showToast('请先登录'); return; }
        $('imageInput').click(); });
    $('imageInput').addEventListener('change', (e) => {
        const file = e.target.files[0];
        if (file) {
            if (file.size > 2 * 1024 * 1024) { showToast('图片太大，请选小于2MB的'); return; }
            const reader = new FileReader();
            reader.onload = (ev) => { $('imagePreview').src = ev.target.result;
                $('imagePreview').style.display = 'block'; };
            reader.readAsDataURL(file);
        }
    });

    $('fileUploadBtn').addEventListener('click', () => { if (!currentUser) { showToast('请先登录'); return; }
        $('fileInput').click(); });
    $('fileInput').addEventListener('change', (e) => {
        const file = e.target.files[0];
        if (file) {
            if (file.size > 10 * 1024 * 1024) { showToast('文件太大，请选小于10MB的'); return; }
            $('fileNameDisplay').textContent = `${file.name} (${(file.size/1024).toFixed(1)} KB)`;
        }
    });

    $('publishBtn').addEventListener('click', async function() {
        if (!currentUser) { showToast('请先登录'); return; }
        const category = $('categorySelect').value,
            version = $('versionSelect').value,
            title = $('titleInput').value.trim(),
            desc = $('descInput').value.trim(),
            url = $('urlInput').value.trim();
        if (!title) { showToast('请填写标题'); return; }
        const image = $('imagePreview').style.display === 'block' ? $('imagePreview').src : null;
        let fileData = null,
            fileName = null;
        const file = $('fileInput').files[0];
        if (file) {
            try {
                const content = await new Promise((resolve, reject) => {
                    const reader = new FileReader();
                    reader.onload = (e) => resolve(e.target.result);
                    reader.onerror = reject;
                    reader.readAsDataURL(file);
                });
                fileData = content;
                fileName = file.name;
            } catch (e) { showToast('读取文件失败');
                return; }
        }
        const loadingTip = $('loadingTip'),
            btn = this;
        loadingTip.style.display = 'inline';
        btn.disabled = true;
        try {
            await publishPost({ category, version, title, desc, url, image, fileData, fileName });
            showToast('✅ 发布成功！');
            $('titleInput').value = '';
            $('descInput').value = '';
            $('urlInput').value = '';
            $('imagePreview').style.display = 'none';
            $('imagePreview').src = '';
            $('imageInput').value = '';
            $('fileInput').value = '';
            $('fileNameDisplay').textContent = '未选择文件';
            await loadPosts();
        } catch (e) { showToast('❌ 发布失败: ' + e.message, 5000); } finally { loadingTip.style.display = 'none';
            btn.disabled = false; }
    });

    document.querySelectorAll('.pill').forEach(pill => {
        pill.addEventListener('click', function() {
            document.querySelectorAll('.pill').forEach(p => p.classList.remove('active'));
            this.classList.add('active');
            currentCategory = this.dataset.cat;
            renderPosts();
        });
    });

    async function init() {
        loadUserDB();
        loadSession();
        renderHeader();
        updatePublishHint();
        await loadPosts();
        console.log('✅ mc玩家自制社区 已启动');
    }
    init();
</script>
</body>
</html>
