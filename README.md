# React環境構築

- node.js + reactの環境です。

- dockerを使ったreactの環境構築なのでreadockと名付けています。

  

## ReaDock

1. リポジトリをクローン

   ```
   git clone https://gitlab.com/welcome-to-sodai/react.git rails_app/readock
   ```

2. readockの階層で

   ```
   docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app react_app"
   ```

3. ```
   docker-compose up -d node
   ```

4. [ここに](http://localhost)アクセスし、うまくいっているか確認

