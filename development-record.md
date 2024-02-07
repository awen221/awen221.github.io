# Github Pages開發紀錄
## 建立專案
1.  執行下列命令建立新angular專案，加入routing，設定style為css：
    ```
    ng new awen221.github.io --routing --style css
    ```
1.  在Github上建立同名repository並push此專案
1.  安裝angular-cli-ghpages
    ```
    npm i -g angular-cli-ghpages
    ```
1.  至Github此repository頁面
    
    ![Alt text](/development-record.resource/pages%20setting.png)

## 發佈專案
1.  ng build建置
1.  執行下列命令會自動發佈到遠端ph-pages分支上
    ```
    npx ngh --dir=dist/awen221.github.io
    ```

