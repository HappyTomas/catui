一款简洁的个人单栏主题。

演示站点
----
- [折影轻梦](https://i.chainwon.com/catui.html)

主题情怀
----

> 纤细温柔的猫耳少女啊，那么的精致，那么的微弱的少女，我想要用我的双手保护你啊。<br/>
> 在几年之后将会吹起撼动世界的狂风，我们的身体太过轻盈，因为那阵狂风，我们将会分开，但是心将永远不会分离。

其他说明
----

 - 该模板需要插件：TeStat的配合，下载地址<a target="_blank"
   href="https://github.com/jiangmuzi/TeStat">https://github.com/jiangmuzi/TeStat</a>
 - 此模板仅仅在HTTPS环境下测试，非HTTPS环境不明。
 - 此模板将会一直维护，绝不离弃。
 
更新日志
----
#### 2017-02-25 更新 1.1版本

 1. 新header
 3. 新增赞助信息（支付宝、QQ、微信）。
 4. 更多色彩的Cover
 5. 独立页面的赞助自定义模板
 6. 修复导航栏后台跳转错误
 7. 不再需要插件支持来统计浏览次数
 8. 更加像猫
 9. 上一篇及下一篇文章功能
 1. 萌萌哒的后台说明

#### 2017-02-17 更新 1.0版本

 1. HTML cat标签
 1. tags、搜索、多说、封面图、代码高亮、分享等
 1. 新增主题后台，可自定义头像及多说等……
 1. 后台新增最新版本检测
 1. 新增404页面
 1. 新增Cover新样式

多说表情
----

下载链接：<a href="https://i.chainwon.com/newpaopao.zip">https://i.chainwon.com/newpaopao.zip</a>
使用 <code>配套多说CSS</code> 后，将压缩包文件夹 <code>newpaopao</code> 解压到 <code>博客</code> 根目录即可。

配套多说CSS
-------

    /* @轻梦 https://i.chainwon.com/catui.html */
     #ds-thread #ds-reset a.ds-user-name[data-user-id='13895227']:after {
        content:"站长";
        margin-left: 6px;
        font-size: 12px;
        color: #fff;
        background: rgb(244, 164, 164);
        border-radius: 2px;
        padding: 0 3px;
        box-shadow: 0px 0px 8px rgb(244, 164, 164);
    }
    #ds-thread {
        width: 100%;
        border: none;
        margin: 0 auto;
        margin-top: 10px;
    }
    #ds-thread .ds-sync, #ds-thread .ds-powered-by, #ds-smilies-tooltip ul.ds-smilies-tabs {
        display: none!important;
    }
    #ds-thread #ds-reset .ds-replybox {
        height: 80px;
        padding-left: 80px;
        background: #fff;
        border-radius: 5px;
        overflow: hidden;
    }
    #ds-thread #ds-reset .ds-replybox .ds-avatar {
        position: absolute;
        width: 80px;
        height: 80px;
        margin: 0;
        overflow: hidden;
        background: #f7f7f7;
        border-radius: 2px 0 0 2px;
    }
    
    @media (max-width: 720px) {
        #ds-thread #ds-reset .ds-replybox .ds-avatar {
            width: 50px;
            height: 50px;
        }
        #ds-reset form {
            margin-left: 12px;
        }
    }
    #ds-thread #ds-reset .ds-replybox .ds-avatar img {
        width: 100%;
        height: 100%;
        border-radius: 0;
    }
    #ds-thread #ds-reset .ds-replybox .ds-avatar img:hover {
        width: 100%;
        height: 100%;
        border-radius: 0;
    }
    #ds-thread #ds-reset .ds-textarea-wrapper {
        position: relative;
        border: none;
        border-radius: 0 5px 0 0;
        background: #f5f5f5;
    }
    #ds-thread #ds-reset .ds-textarea-wrapper textarea {
        height: 30px!important;
        letter-spacing: 0;
        line-height: 1.5;
        font-size: 14px;
        color: #333;
    }
    #ds-thread #ds-reset .ds-post-button {
        position: absolute;
        top: -50px;
        transition: all .35s;
        width: 80px !important;
        padding: 0;
        color: #fff;
        background-color: rgb(244, 164, 164);
        border: 0;
        box-shadow: 0 2px 6px rgba(0,0,0,.2);
        outline: none;
        height: 80px;
    }
    #ds-thread #ds-reset .ds-post-button:hover {
       background: rgb(244, 164, 164) !important;
        box-shadow: 0 3px 15px rgb(244, 164, 164) !important;
    }
    #ds-thread #ds-reset .ds-post-toolbar {
        box-shadow: 0 0;
    }
    #ds-thread #ds-reset .ds-post-options {
        border: 0;
        background: #f5f5f5;
    }
    #ds-thread #ds-reset li.ds-tab a.ds-current {
        border: none;
        background-color: rgba(255, 255, 255, 0);
    }
    #ds-thread #ds-reset li.ds-post, #ds-thread #ds-reset .ds-post-self {
        border: none;
    }
    #ds-thread #ds-reset .ds-post-self {
        background: #f5f5f5;
        margin-bottom: 10px;
        border-radius: 5px;
    }
    #ds-thread #ds-reset .ds-comments, #ds-thread #ds-reset .ds-paginator {
        border-bottom: none;
    }
    #ds-thread #ds-reset .ds-comments, #ds-thread #ds-reset .ds-paginator {
        border: none;
        background-color: rgba(255, 255, 255, 0);
        border-radius: 99px;
    }
    #ds-notify {
        border: 0;
        box-shadow: 0 2px 2px 0 rgba(0, 0, 0, .14), 0 3px 1px -2px rgba(0, 0, 0, .2), 0 1px 5px 0 rgba(0, 0, 0, .12);
        z-index: 999;
        background: #fff;
        border-radius: 5px;
    }
    #ds-notify #ds-reset .ds-logo {
        margin-top: 5px;
    }
    #ds-thread #ds-reset .ds-paginator {
        margin-bottom: 10px!important;
    }
    #ds-thread #ds-reset .ds-paginator .ds-current {
        border: 0!important;
        border-radius: 50%!important;
        box-shadow: 1px 1px 5px #ddd;
        background: #fff!important;
    }
    #ds-thread #ds-reset .ds-paginator a {
        font-size: 12px;
        border: 0px solid transparent!important;
        border-radius: 50%!important;
        height: 35px;
        width: 35px;
        line-height: 35px;
        margin: 0 3px;
        padding: 0!important;
        display: inline-block;
    }
    #ds-thread #ds-reset .ds-paginator a:hover {
        background: #fff!important;
        color: #F64848!important;
    }
    #ds-thread #ds-reset .ds-post-toolbar, #ds-reset .ds-avatar {
        box-shadow: none;
    }
    #ds-wrapper #ds-reset .ds-dialog-inner {
        box-shadow: 0px 10px 10px 0 rgba(0, 0, 0, .14), 0 3px 1px -2px rgba(0, 0, 0, .2), 1px 3px 7px 0 rgba(0, 0, 0, .12), 0px 0px 20px 5px rgba(0, 0, 0, .12);
        border: 0px;
        background: #fff;
        border-radius: 5px;
        top: 140px;
    }
    #ds-wrapper #ds-reset .ds-dialog-footer {
        display: none;
    }
    #ds-wrapper #ds-reset .ds-dialog-inner button, #ds-wrapper #ds-reset .ds-dialog-inner input {
        width: 100%;
    }
    #ds-thread #ds-reset #ds-bubble {
        border: none;
        box-shadow: 0 2px 2px 0 rgba(0, 0, 0, .14), 0 3px 1px -2px rgba(0, 0, 0, .2), 0 1px 5px 0 rgba(0, 0, 0, .12);
        background-color: rgba(255, 255, 255, .9);
        border-radius: 5px;
    }
    #ds-thread #ds-reset .ds-account-control ul {
        border: 0;
        box-shadow: 0 2px 2px 0 rgba(0, 0, 0, .14), 0 3px 1px -2px rgba(0, 0, 0, .2), 0 1px 5px 0 rgba(0, 0, 0, .12);
        z-index: 999;
        background: #fff;
    }
    #ds-reset .ds-avatar {
        background: none;
    }
    #ds-reset .ds-avatar img {
        border: 2px solid #fff;
        -webkit-border-radius: 50%;
        border-radius: 50%;
    }
    img.biaoqing, #ds-thread #ds-reset .ds-comment-body img.biaoqing {
        display: inline;
        margin: 0;
        width: auto;
        max-width: 6.25rem;
    }
    img.newpaopao, #ds-thread #ds-reset .ds-comment-body img.newpaopao {
        margin-bottom: -0.25rem;
        min-height: 1.875rem;
        height: 1em;
    }
    img.alu, #ds-thread #ds-reset .ds-comment-body img.alu {
        margin-bottom: -0.3125rem;
        min-height: 2.0625rem;
        height: 1em;
    }
    #ds-smilies-tooltip {
        box-shadow: .125rem .6875rem 1.375rem rgba(0,0,0,0.27);
        border: none;
        border-radius: 5px;
        overflow: hidden;
        max-width: calc(100% - 70px);
    }
    #ds-smilies-tooltip .ds-smilies-container li {
        margin: 6px;
    }
    #ds-smilies-tooltip .ds-smilies-container {
        margin-left: 0!important;
    }
    #ds-thread #ds-reset .ds-toolbar {
        padding: 0;
    }
