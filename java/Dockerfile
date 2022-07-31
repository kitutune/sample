FROM openjdk:17
RUN microdnf install findutils
# docker内に入った時の初期パスの指定
# WORKDIR /app
# # ローカル側のファイルをdocker内にコピーする
# COPY app .
# # 　コンテナの使用ポート指定
# EXPOSE 8080
# コンテナが勝手に終了してしまわないようにする設定
ENV CI=true