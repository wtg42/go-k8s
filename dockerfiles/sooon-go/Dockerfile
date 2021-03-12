FROM alpine
RUN mkdir /app
RUN cd /app
# 加入你的go應用程式
ADD main /app
ADD .env /app
WORKDIR /app
EXPOSE 3000
# 可以讀取環境變數 ENTRYPOINT 是 Image 運行時 Container 要運行的 Executable
# 而 CMD 是 ENTRYPOINT 預設的 Argument (參數), 執行時可以被命令行取代
ENTRYPOINT ./main