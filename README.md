# sanber41-cypress
https://kasirdemo.belajarqa.com
tutorial
1. Buat Folder
2. buka vs code new terminal 
3. npm init isi author, deskripsi, test
4. npm install cypress --save-dev
5. buat cyress.config.js isi dengan code berikut
const { defineConfig } = require('cypress')

module.exports = defineConfig({

    e2e: {

        baseUrl : 'url yang diinginkan',

        specPattern : "cypress/support/e2e",

        supportFile : false,

    },

})
6. npx cypress run