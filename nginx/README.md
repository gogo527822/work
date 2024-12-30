我在一台AWS新機器安裝docker

yum install docker 並啟動
編寫Dockerfile
創建sre.txt

build 檔案
docker build -t nginx .

然後執行
docker run -d -p 8080:80 nginx

測試是否成功

curl http://localhost:8080/sre.txt
# work
![nginx](https://github.com/user-attachments/assets/fee6d05d-bb34-487a-8aac-2b013c50711c)

