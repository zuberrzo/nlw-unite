# html
table - Tabela
thead - cabecalho
tr - linhas
th - participantes

#javascript

```js
// variaveis
const mensagem = `Oi tudo bem`
// tipos de dados
  //number
  //string


// funcao
alert(mensagem)

//array 
let participantes = [
  {
    nome: "Rodrigo Zuber",
    email: "zuberrzo@gmail.com",
    dataInscricao: new Date(2024, 2, 22, 19, 20),
    dataCheckIn: new Date(2024, 2, 25, 22, 00)
  },
]

//estrutura repeticao - example
  let output = ""
  
  for (let participante of participantes) {
    output = output + criarNovoParticipante(participante)
  }


```
