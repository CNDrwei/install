## UV
需要建立一个软连接 ln -s $home/uv /usr/local/bin/uv
UV 配置
export UV_HOME=/usr/local/bin/uv
export PATH=$UV_HOME:$PATH
export UV_PYTHON_INSTALL_MIRROR="https://registry.npmmirror.com/-/binary/python-build-standalone/"
export UV_INDEX_URL="https://mirrors.tencent.com/pypi/simple"
eval "$(uv generate-shell-completion bash)"
export PATH="$HOME/.local/bin:$PATH"

