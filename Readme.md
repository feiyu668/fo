1. 创建虚拟环境
uv venv
2. 激活虚拟环境
.venv\Scripts\activate
3. 安装

 $env:HTTP_PROXY="http://127.0.0.1:10808"; $env:HTTPS_PROXY="http://127.0.0.1:10808"; uv pip install -r requirements.txt
4. 查询
python .\fofa.py