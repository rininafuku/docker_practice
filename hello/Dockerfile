#OSを指定
FROM ubuntu:21.10

#helloファイルをbinにコピー
COPY hello /usr/local/bin
# 実行権限を付与
RUN chmod +x /usr/local/bin/hello

# コンテナ起動時にコマンド実行
CMD [ "hello" ]
