# React環境構築

- node.js + reactの環境です。


## ReaDock

1. リポジトリをクローン

   ```
   git clone https://github.com/Sodai-circle/React.git react_app/readock
   ```

2. readockの階層で

   ```
   docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app ."
   ```

3. ```
   docker-compose up -d node
   ```

4. [ここに](http://localhost:3000)アクセスし、うまくいっているか確認


## 使い方

- 始めるとき readockの階層で
   ```bash
   docker-compose up -d node
   ```
- 終わるとき
   ```bash
   docker-compose down
   ```

   
