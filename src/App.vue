<script setup>
import Rules from './components/Rules.vue'
import Comment from './components/Comment.vue'
import Other from './components/Other.vue'
</script>

<template>
    <div class="github">
        <a target="_blank" href="https://github.com/haer0248/mc-club/" class="github-corner" aria-label="View source on GitHub"><svg width="80" height="80" viewBox="0 0 250 250" style="fill:#151513; color:#fff; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true">
                <path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path>
                <path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path>
                <path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path>
            </svg>
        </a>
    </div>

    <div class="overflow-hidden text-center bg-light mb-3" id="header">
        <div class="mx-auto my-5 p-3">
            <h1 class="display-5 fw-normal">麥塊 Minecraft Facebook 社團規定</h1>
            <p class="lead fw-normal">
                此頁面為說明社團必須注意的規定及發文、留言、回覆事項，<br>
                管理員及板主有權力移除、封鎖您於社團的資格，請詳讀以下社團規定。<br>
                找不到需要的資訊請點選旁邊管理團隊聯絡，在這之前請先詳細閱讀此網頁，可使用 Ctrl+F 搜尋部分資料。
            </p>
            <a class="btn btn-primary" href="https://www.facebook.com/groups/143360935862590" target="_blank">立即加入社團</a>
        </div>
    </div>

    <main role="main" class="container-md">

        <div class="row">
            <div class="col-md-8">

                <Rules />

                <hr>

                <Comment />

                <hr>

                <Other />

            </div>

            <aside class="col-md-4 blog-sidebar">

                <h4>關於社團</h4>
                <p class="mb-0">
                    本社團於 <strong>2013年7月2日</strong> 創立。<br>
                    我們非常歡迎熱愛 Minecraft 的玩家加入並與我們一起享受遊戲帶來的樂趣！
                </p>

                <hr>

                <h4>伺服器列表</h4>
                <p class="mb-0">
                    伺服器沒地方宣傳還是想更多要宣傳嗎？要不要來這邊嘗試看看呢！<br>
                    什麼？你是玩家，沒有關係的啦！這邊有很多很多伺服器可以給你選擇的唷！<br>
                    宣傳或是遊玩伺服器！<a href="https://www.mc-list.xyz/" target="_blank">https://www.mc-list.xyz/</a><br>
                    也順便把網站分享給你的親朋好友吧！
                </p>

                <hr>

                <h4>管理團隊（加入時間排序）</h4>
                <ul class="mb-0">
                    <li><a class="text-decoration-none" href="https://fb.com/100007346440267" target="_blank">趙挺豪</a></li>
                    <li><a class="text-decoration-none" href="https://fb.com/100006775360555" target="_blank">Worfy Moon</a></li>
                    <li><a class="text-decoration-none" href="https://fb.com/100005923505566" target="_blank">Ye LinSa</a></li>
                    <li><a class="text-decoration-none" href="https://fb.com/100009389487688" target="_blank">陳筠樺</a></li>
                    <li><a class="text-decoration-none" href="https://fb.com/100001262295236" target="_blank">陳信安</a></li>
                    <li><a class="text-decoration-none" href="https://fb.com/haer0248" target="_blank">Michael Lin</a></li>
                </ul>

                <hr>

                <h4>Minecraft 相關連結</h4>
                <ul>
                    <li>Minecraft 官方網站 <a href="https://minecraft.net/" target="_blank">https://minecraft.net/</a></li>
                    <li>Minecraft 伺服器檔案下載 <a href="https://mcversions.net/" target="_blank">https://mcversions.net/</a></li>
                    <li>Minecraft 巴哈姆特 <a href="https://goo.gl/aiBqSx" target="_blank">https://goo.gl/aiBqSx</a></li>
                    <li>SpigotMC <a href="https://spigotmc.org/" target="_blank">https://spigotmc.org/</a></li>
                </ul>
            </aside>
        </div>

    </main>

    <footer class="pt-5 my-5 text-muted border-top text-center">
        <b>我們非常歡迎您加入 麥塊 Minecraft 社團，遵守規則、不違規，您我共同維護社團！<br>若需要馬上處理請第一時間進行社團內檢舉。</b>
        <p>Copyright &copy; All Rights Reserved.</p>
    </footer>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC&display=swap');

html,
body {
    font-family: "Noto Sans TC", sans-serif !important;
}

a,
a:hover {
    text-decoration: none;
}

#header {
    background-image: url('/header.jpg');
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: cover;
}

#header div {
    backdrop-filter: blur(10px);
}

.github {
    position: sticky;
    z-index: 99;
    top: 0;
    right: 0;
}

.github-corner:hover .octo-arm {
    animation: octocat-wave 560ms ease-in-out;
}

@keyframes octocat-wave {

    0%,
    100% {
        transform: rotate(0)
    }

    20%,
    60% {
        transform: rotate(-25deg)
    }

    40%,
    80% {
        transform: rotate(10deg)
    }
}

@media (max-width:500px) {
    .github-corner:hover .octo-arm {
        animation: none
    }

    .github-corner .octo-arm {
        animation: octocat-wave 560ms ease-in-out
    }
}
</style>