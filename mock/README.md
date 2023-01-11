# Como usar

1. Abra uma nova aba no terminal
2. Execute o seguinte comando: 
    ```
    yarn run json-server -w -p 3333 ./mock/database.json
    ```
    ou
    ```
    npm run json-server -w -p 3333 ./mock/database.json
    ```

3. pode ser que não funcione então vai no arquivo package.json na parte do script coloque 
 ```
  "mock": "json-server -w -p 3333 ./mock/database.json",
  ```
  4. e depois da npm run mock