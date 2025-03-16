# 使用官方 Python 3.11 Slim 版本作為基礎映像
FROM python:3.11-slim

# 設定工作目錄
WORKDIR /app

# 複製應用程式檔案到容器
COPY main.py /app/
COPY requirements.txt /app/

# 安裝 Flask 及其他相依套件
RUN pip install --no-cache-dir -r requirements.txt

# 指定容器啟動時執行的指令
CMD ["python", "main.py"]
