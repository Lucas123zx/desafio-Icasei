# desafio-Icasei
Repositorio voltado a responder um desafio da Icasei.

Ferramentas utilizadas para esse desafio são:
  
  - [Img2go](https://www.img2go.com/pt/converter-video-para-gif)
  - [LightShot](https://app.prntscr.com/pt-br/download.html)
  - [Snipping Tool](https://apps.microsoft.com/detail/9mz95kl8mr0l?hl=en-mt&gl=MT)
  - [Devtools-Chrome]("https://developer.chrome.com/docs/devtools?hl=pt-br")

## Desafio 1: 

**Bug01**:  Botão "Ir para proxima seção" após clicado não redireciona o usuário a próxima seção.

Step by Step: 

1. Usuário esteja na url "https://teste-qa.icasei.com.br/" 
2. Clicar no icone ![alt text](/evidencias_testes/image.png)

#### Result: 

`usuário permanece na seção de apresentação de banners, após clicado no botão.`

#### Result Expect:

`usuário ser redirecionado a próxima seção inicial da página home.`


---

**Bug02**: Seção "Fique por dentro de todos os detalhes!" não possuem efeito de animação na imagem.

Step by Step:

1. Usuário esteja na url "https://teste-qa.icasei.com.br/"
2. Navegar até a seção "Fique por dentro de todos os detalhes!" na página
3. Obervar que imagem não exibe nenhum efeito de animação.

#### Result: 

` A imagem está estática, sem qualquer animação.`

![alt text](/evidencias_testes/bug2.gif)


#### Result Expect: 

` A imagem deve apresentar um efeito de animação conforme o design especificado.`

![alt text](/evidencias_testes/resultExpect2.gif)

---

**Bug03**: Página "diferenca-planos-icasei" Apresenta Texto diferente do Esperado.

Step by Step: 

1. Usuário esteja na url "https://teste-qa.icasei.com.br/planos"
2. Navegar até a seção "São mais de 150 recursos incríveis!"

#### Result:

`Sistema apresenta o texto "Planos Icasei"`

![alt text](/evidencias_testes/image-2.png)


#### Result Expect: 

![alt text](/evidencias_testes/image-1.png)

--- 

**Bug04**: A tela "Tailor Made Design" não está disponível no ambiente de QA.

Step by Step: 

1. Usuário esteja na url "https://teste-qa.icasei.com.br/planos"
2. Navegar até a seção "Tailor Made Design"

#### Result: 

`Ambiente de Qa não possui seção "Tailor Made Design"`

#### Result Expect: 

`É esperado apresenta essa seçào "Tailor Made Design"`

![alt text](/evidencias_testes/image-3.png)

---

**Bug05**: Botão que expande caracteristica de recusrso na seção "São mais de 150 recursos incríveis!" não possuem efeitos.

Step by Step: 

1. Usuário esteja na url "https://teste-qa.icasei.com.br/planos"
2. Navegar até a seção "São mais de 150 recursos incríveis!"
3. Obervar que imagem não exibe nenhum efeito de animação.


#### Result:

![alt text](/evidencias_testes/image-5.png)

#### Result Expect: 

![alt text](/evidencias_testes/image-4.png)

---

**Bug06**: Botão do baixar aplicativo na gogle play redirecionando a loja da apple store

Step by Step: 

1. Usuário esteja na url "https://teste-qa.icasei.com.br/" 
2. Navegar até a seção "Fique por dentro de todos os detalhes!"
3. Clicar no botão "Google Play"


#### Result: 

`Usuário redirecionado a apple store`

![alt text](/evidencias_testes/image-6.png)

#### Result Expect: 

`Usuário deverá ser redirecionado a google play store`

---

**Bug07**: Ao enviar depoitmento com sucesso, back-end recebe como respota erro 500

1. Usuário esteja na url "https://teste-qa.icasei.com.br/depoimentos"
2. Clicar no botão "Enviar depoimento"
3. Preencher depoitmento por completo com dados válidos
4. Clicar no check "Autorizo a exibição dos nomes, foto, data e local do evento além do depoimento enviado."
5. Clicar no botão "Enviar"

#### Result:
![alt text](/evidencias_testes/image-7.1.png)

![alt text](/evidencias_testes/image-7.2.png)


#### Result Expect

`Back-end deverá apresenta a respota 201 - Created`