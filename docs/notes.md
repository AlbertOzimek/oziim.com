npm install
# watches your files and uses livereload by default
npm start
# api document for the app
npm run docs

# dev build
npm run build.dev
# prod build
npm run build.prod


scp -r dist/prod/ root@oziim.com:/var/www/oziim.com/public_html
