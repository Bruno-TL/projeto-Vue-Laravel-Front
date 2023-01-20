# Projeto Vue e Laravel (apenas 1 semana de estudo { 20/01/2023 } )
Primeira parte de uma atividade que um Dev do trabalho passo para min.
Estou no nível de trainee atualmente.
-----
## Front end:
- Feito com Vue.js 2 (cdn), axio(cdn)

## Back end:
- Feito com Laravel

==========================================================================
# Objetivo da atividade

- Fazer um formulário que ao digitar e clicar no button, o e-mail digitado no input recebá uma frase:
# Hello world
==========================================================================
- Infelismente só funciona na minha máquina por causa do endpoint que está como o meu localhost geredo pelo o serve do Laravel.
- A interação entre o front e o Back não foi totalmente testada.
- A api foi testada no Insomnia.
## Api - POST
### O método funciona : 
- No front ao clicar no button de enviar o e-mail será enviado uma frase "Hello world" para o e-mail digitado no input.
- Método usado é o POST, passando o valor pelo o BODY/json na requisição feito pelo axios.
- Usando Mailgun para simular o recebindo do email gerado pelo o endpoint.

Back => https://github.com/Bruno-TL/projeto-Vue-Laravel-back ;
