<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-apache-james-website" class="anchor" aria-hidden="true" tabindex="-1" href="#apache-james-website"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿帕奇詹姆斯网站</font></font></h1>
<div id="user-content-preamble" dir="auto">
<div dir="auto">
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库用于存储</font></font><a href="https://james.apache.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache James</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站的（某些）内容。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它还用于构建和发布网站。</font></font></p>
</div>
</div>
</div>
<div dir="auto">
<h2 id="user-content-how-to-build-the-website" tabindex="-1" dir="auto"><a id="user-content-how-to-build-the-website" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-build-the-website"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何建立网站</font></font></h2>
<div dir="auto">
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们使用</font></font><a href="https://antora.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Antora</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为管理和生成网站的工具。</font><font style="vertical-align: inherit;">我们使用</font></font><a href="https://gradle.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gradle</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为工具来驱动/自动化生成、聚合和发布网站的任务。</font></font></p>
</div>
<div dir="auto">
<h3 id="user-content-why-antora" tabindex="-1" dir="auto"><a id="user-content-why-antora" class="anchor" aria-hidden="true" tabindex="-1" href="#why-antora"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么选择安托拉？</font></font></h3>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Antora 使我们能够聚合多个版本的多个文档源，并将它们发布为单个网站。</font><font style="vertical-align: inherit;">每个 Apache James 组件的文档都与其代码一起保存并进行版本控制。</font></font></p>
</div>
</div>
<div dir="auto">
<h3 id="user-content-why-gradle" tabindex="-1" dir="auto"><a id="user-content-why-gradle" class="anchor" aria-hidden="true" tabindex="-1" href="#why-gradle"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么是摇篮？</font></font></h3>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gralde 允许我们自动执行发布网站时执行的任务。</font><font style="vertical-align: inherit;">我们编写用于构建和发布网站的 gradle 任务。</font><font style="vertical-align: inherit;">我们可以在本地和我们的 CI 基础设施内运行这些任务：</font></font><a href="https://builds.apache.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache Builds</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更具体地说，我们使用 Gradle 来：</font></font></p>
</div>
<div dir="auto">
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font><a href="https://github.com/node-gradle/gradle-node-plugin"><font style="vertical-align: inherit;">Gradle Node Plugin</font></a><font style="vertical-align: inherit;">下载并安装特定版本的</font></font><a href="https://nodejs.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NodeJS</font></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/node-gradle/gradle-node-plugin"><font style="vertical-align: inherit;"></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 Antora 的本地版本</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Gradle 任务调用 Antora 构建网站</font></font></p>
</li>
</ul>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过使用此特定流程，您只需要</font></font><code>git</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">,</font></font><code>Java</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和 shell 访问即可构建网站。</font><font style="vertical-align: inherit;">所有其他依赖项均由 Gradle 自动安装。</font><font style="vertical-align: inherit;">甚至 Gradle 也是使用 Gradle 包装器脚本下载和安装的。</font></font></p>
</div>
</div>
</div>
</div>
<div dir="auto">
<h2 id="user-content-how-to-build-the-website-1" tabindex="-1" dir="auto"><a id="user-content-how-to-build-the-website-1" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-build-the-website-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何建立网站</font></font></h2>
<div dir="auto">
<div dir="auto">
<div dir="auto">
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>    <span class="pl-c"><span class="pl-c">#</span> To build the website run</span>
    ./gradlew clean build
    <span class="pl-c"><span class="pl-c">#</span> The website is located here</span>
    <span class="pl-c1">cd</span> doc-sites/build/site</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="    # To build the website run
    ./gradlew clean build
    # The website is located here
    cd doc-sites/build/site" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</div>
</div>
</div>
</div>
<div dir="auto">
<h2 id="user-content-how-to-customize-the-theme-for-the-documentaion" tabindex="-1" dir="auto"><a id="user-content-how-to-customize-the-theme-for-the-documentaion" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-customize-the-theme-for-the-documentaion"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何自定义文档主题</font></font></h2>
<div dir="auto">
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该文档网站基于</font></font><a href="https://antora.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Antora</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">我们已将</font></font><a href="https://gitlab.com/antora/antora-ui-default/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">antora-ui-default</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目添加为 git 子树</font></font><code>antora-ui</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><code>./gradlew :antora-ui:build</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将收集</font></font><code>antora-ui/build/ui-bundle.zip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站所需的档案。</font><font style="vertical-align: inherit;">所有步骤都作为该项目中的 Gradle 任务自动执行。</font><font style="vertical-align: inherit;">您所要做的就是更改 css 和 html 文件，然后重建项目。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Antora-ui项目有预览模式：</font></font><code>/.gradlew gulpPreviewTheme</code></p>
</div>
<div dir="auto">
<div dir="auto">
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>    <span class="pl-c"><span class="pl-c">#</span> antora-ui-default was added like this. You should be able to pull some changes from upstream</span>
    git subtree add --prefix antora-ui https://gitlab.com/antora/antora-ui-default.git master --squash</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="    # antora-ui-default was added like this. You should be able to pull some changes from upstream
    git subtree add --prefix antora-ui https://gitlab.com/antora/antora-ui-default.git master --squash" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</div>
</div>
<div dir="auto">
<h3 id="user-content-related-links" tabindex="-1" dir="auto"><a id="user-content-related-links" class="anchor" aria-hidden="true" tabindex="-1" href="#related-links"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相关链接</font></font></h3>
<div dir="auto">
<ul dir="auto">
<li>
<p dir="auto"><a href="https://medium.com/@v/git-subtrees-a-tutorial-6ff568381844" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">git 子树教程</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><a href="https://docs.antora.org/antora/2.3/playbook/configure-ui/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Antora UI 按键</font></font></a></p>
</li>
</ul>
</div>
</div>
</div>
</div></article></div>
