<template>
    <!-- 关于页面 -->
    <div class="about" style="text-align: left">
        <p>😀 <b>Lillian 个人博客</b></p>
        <p>🎨分享技术文章，记录学习中遇到的问题，分享学习心得。</p>
        <p>🚀基于vitepress: <a href="https://vitepress.dev/zh/" target="_blank">VitePress | 由 Vite 和 Vue 驱动的静态站点生成器</a>
        </p>
        <p>⚒️ 使用主题：<a href="https://www.appbeebee.com/posts/2024/01/open-source-vitepress-blog-theme-appbeebee.html"
                target="_blank">APP比比-基于
                vitepress+vercel搭建的前端资源分享博客主题，适合搭建vitepress blog主题</a></p>
    </div>
</template>

<script lang="ts" setup>

</script>

<style scoped>
.about {
    background-color: var(--vp-c-bg-alt);
    border-radius: 8px;
    padding: 40px;
    font-size: 14px;
    text-align: center;

    .list {
        font-size: 12px;
        margin-top: 24px;
        display: flex;
        flex-direction: column;
        align-self: center;
        justify-content: center;

        .h4 {
            margin: 10px;
            font-size: 12px;
        }

        .ul {
            display: flex;
            flex-direction: column;
            padding: 0;
            margin: 0 auto;

            .li {
                display: flex;
                flex-direction: row;
                align-items: center;
                justify-content: center;

                .label {
                    margin-right: 8px;
                }
            }
        }
    }
}
</style>
