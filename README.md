# swagger-ui on GitHub Pages

- <https://helphi.github.io/pages-swagger-ui/ui/index.html>
- <https://helphi.github.io/pages-swagger-ui/editor/index.html>

---

```sh
mkdir ui
cd ui
wget https://github.com/swagger-api/swagger-ui/archive/master.zip
unzip master.zip
mv swagger-ui-master/dist/* .
rm -rf swagger-ui-master master.zip *.map
cd ../
mkdir editor
cd editor
wget https://github.com/swagger-api/swagger-editor/archive/master.zip
unzip master.zip
mv swagger-editor-master/dist dist
mv swagger-editor-master/index.html .
rm -rf swagger-editor-master master.zip dist/*.map
```