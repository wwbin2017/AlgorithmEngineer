
# 复制一个文件到多个文件夹
echo CPlusPlus/ DesignPatterns/ Linux/ Python/ Shell/ | xargs -n 1 cp -v ../README.md
