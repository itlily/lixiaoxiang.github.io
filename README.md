# 使用技术 
## html jade 
  - jade -w src/index.jade --out /
  p this is a link #[a(href="http://jade.terrynie.com")]
## css stylus
  - stylus -w src/index.styl -o css/index.css
## js typescript
  - tsc src/index.ts -w --outFile js/index.js
## postcss
  -  npm install postcss-cli autoprefixer
  -  postcss index.css -u autoprefixer --replace --watch --poll
  -   postcss css/index.css -u autoprefixer --replace
  -   .browserlistrc
## gulp
  - gulpfile.js
## watch
  - browser-sync start --server --files "*.html,css/*.css,js/*.js"
