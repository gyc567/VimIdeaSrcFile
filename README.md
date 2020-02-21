# VimIdeaSrcFile
Ｗｉｎ版本：

简单步骤：
1.安装ＩＤＥＡ　社区版本：https://www.jetbrains.com/idea/
2.在idea中的plugins选择安装：IdeaVim插件。
3.在当前管理员用户目前下新建文件：_ideavimrc
4.把当前工程中的文件：_ideavimrc所有内容复制到新建文件：_ideavimrc
5.重启Intellij


简单说明 ：

" 设置debug为 zd，在vim的normal模式下，直接按zd将执行debug
nnoremap zd :action Debug<CR>
" 设置run 为 zr，在vim的normal模式下，直接按zr将执行run
nnoremap zr :action Run<CR>

"显示当前文件路径,在vim的normal模式下，直接按<space>+fp将执行ShowFilePath
nnoremap <Leader>fp :action ShowFilePath<CR>