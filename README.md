MINICURSO JAVASCRIPT INTRODUÇÃO
#criar a biblioteca
npm init -y       
#criar a biblioteca express
npm install express





código que fiz hoje:
// Eu preciso do express
// Import express
const express = require("express")
const app = express();

// fazer o app "ouvir"
app.listen(3000,() => {
    console.log("http://localhost:3000")
})

//get - buscar // post - criar // put - atualizar // delete - remover//
