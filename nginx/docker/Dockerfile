# ベースイメージとして公式のNginxイメージを使用
FROM nginx:latest

# Nginxの設定ファイルをコンテナ内にコピー
COPY ../nginx.conf /etc/nginx/nginx.conf

# ドキュメントルートをコンテナ内にコピー
COPY ../html /usr/share/nginx/html

# ポート80を公開
EXPOSE 80