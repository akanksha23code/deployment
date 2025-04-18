change line 14,18 from angular.json
"builder": "@angular-devkit/build-angular:browser",
          
          "options": {
            "outputPath": "dist/integration",
            "index": "src/index.html",
            "main": "src/main.ts",

            and run below command:
            ng build --configuration production --base-href="https://akanksha23code.github.io/deployment/"

            then u get dist folder,copy the contents into new folder and then push to git repo-then
            in git repo -settings-pages-deploy
