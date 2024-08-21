<script setup>
import Rules from './components/Rules.vue'
import Comment from './components/Comment.vue'
import Other from './components/Other.vue'
</script>

<template>
    <div class="position-relative overflow-hidden text-center bg-light mb-3" id="header">
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

html, body {    
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
</style>