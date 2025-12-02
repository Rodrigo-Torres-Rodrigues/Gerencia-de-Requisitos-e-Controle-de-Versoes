# Diagrama de Caso de Uso

Todos os "<< include >>" no diagrama de caso de uso são dependências. Sobre o caso de uso "Assitir Vídeos", não é necessário logar ou mesmo cadastrar para realizar a ação, por isso, não é necessário um << include >> para o caso de uso "Logar".

<div align="center">
<img src="https://github.com/user-attachments/assets/2a6d4bc2-f928-4f40-b36b-32d71f1427b1" width="80%" alt="Diagrama de Caso de Uso">

  Figura 1: Diagrama de Caso de Uso.
</div>

---

## Especificações Detalhadas dos Casos de Uso  

| **Nome do caso de uso**                                                  | **UC1 - Cadastrar**                                                                                                                |
| ------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| **Caso de uso geral**                                                    | Fluxo Principal                                                                                                                    |
| **Ator principal**                                                       | Usuário                                                                                                                            |
| **Atores secundários**                                                   | N/A                                                                                                                                |
| **Resumo**                                                               | Este caso de uso descreve as etapas necessárias para a criação do cadastro do usuário para utilizar todo o potencial da aplicação. |
| **Pré-Condições**                                                        | O usuário precisa adicionar seu email e senha.                                                                                     |
| **Pós-Condições**                                                        | O usuário agora está cadastrado e poderá fazer login.                                                                              |
| **Ações do Ator**                                                        | **Ações do Sistema**                                                                                                               |
| 1 – Clicar na opção "Cadastrar-se".                                      |                                                                                                                                    |
| 2 - Informar todos os dados necessários (Email, Senha, Nome de Usuário). |                                                                                                                                    |
|                                                                          | 3 - Verificar se o usuário com os mesmos dados já está cadastrado.                                                                 |
|                                                                          | 4 - Validar todas as informações no sistema.                                                                                       |
|                                                                          | 5 - Redirecionar o usuário a tela de login.                                                                                        |
| **Restrições/Validações**                                                | O usuário não pode ter duas contas com o mesmo email.                                                                              |

<div align="center">
  Tabela 1 - Especificação do caso de uso Cadastrar.
</div>

---

| **Nome do caso de uso**                               | **UC2 - Logar**                                                                      |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Caso de uso geral**                                 | Fluxo Principal                                                                      |
| **Ator principal**                                    | Usuário                                                                              |
| **Atores secundários**                                | N/A                                                                                  |
| **Resumo**                                            | Este caso de uso descreve as ações na qual o usuário deve realizar para fazer login. |
| **Pré-Condições**                                     | O usuário precisa estar cadastrado.                                                  |
| **Pós-Condições**                                     | O usuário agora pode interagir com funcionalidades que ele não poderia antes.        |
| **Ações do Ator**                                     | **Ações do Sistema**                                                                 |
| 1 – Clicar na opção "Logar"                           |                                                                                      |
| 2 - Inserir todos os dados requeridos (Email, senha). |                                                                                      |
|                                                       | 3 - Verificar se o email está cadastrado no sistema.                                 |
|                                                       | 4 - Validar as informações que o usuário inseriu com a do sistema.                   |
|                                                       | 5 - Redirecionar a parte inicial com o usuário logado em sua conta.                  |
| **Restrições/Validações**                             | O usuário não pode estar logado em duas contas ao mesmo tempo.                       |

<div align="center">
  Tabela 2 - Especificação do caso de uso Logar.
</div>

---

| **Nome do caso de uso**                  | **UC3 - Enviar Vídeos**                                                                                    |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Caso de uso geral**                    | Fluxo Principal                                                                                            |
| **Ator principal**                       | Usuário                                                                                                    |
| **Atores secundários**                   | N/A                                                                                                        |
| **Resumo**                               | Este caso de uso descreve as ações na qual o usuário deve realizar para enviar um vídeo para a plataforma. |
| **Pré-Condições**                        | O usuário precisa estar logado.                                                                            |
| **Pós-Condições**                        | O vídeo agora está **público** para qualquer pessoa ver.                                                   |
| **Ações do Ator**                        | **Ações do Sistema**                                                                                       |
| 1 – Clicar na opção "Enviar vídeos".     |                                                                                                            |
| 2 - Inserir título e descrição do vídeo. |                                                                                                            |
|                                          | 3 - Registrar as informações do vídeo e o vídeo em si no sistema.                                          |
|                                          | 4 - Alertar o usuário que o vídeo foi enviado a plataforma.                                                |
| **Restrições/Validações**                | O vídeo precisa ter um título.                                                                             |

<div align="center">
  Tabela 3 - Especificação do caso de uso Enviar Vídeos.
</div>

---

| **Nome do caso de uso**                                     | **UC4 - Assistir Vídeos**                                                                           |
| ----------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **Caso de uso geral**                                       | Fluxo Principal                                                                                     |
| **Ator principal**                                          | Usuário                                                                                             |
| **Atores secundários**                                      | N/A                                                                                                 |
| **Resumo**                                                  | Este caso de uso descreve as etapas que o usuário precisa fazer para assistir vídeos na plataforma. |
| **Pré-Condições**                                           | O usuário precisa ter uma conexão estável com a internet.                                           |
| **Pós-Condições**                                           | O vídeo está em estado de "assistido".                                                              |
| **Ações do Ator**                                           | **Ações do Sistema**                                                                                |
| 1 – Procurar algum vídeo específico enviado por um usuário. |                                                                                                     |
| 2 - Clicar no vídeo.                                        |                                                                                                     |
|                                                             | 3 - Acessar o vídeo no sistema e começar a exibi-lo para o usuário.                                 |
| 4 - Assistir todo o vídeo.                                  |                                                                                                     |
|                                                             | 5 - Registrar o vídeo no sistema como "assistido".                                                  |
| **Restrições/Validações**                                   | O usuário não pode assitir dois vídeos ao mesmo tempo.                                              |

<div align="center">
  Tabela 4 - Especificação do caso de uso Assistir Vídeos.
</div>

---

| **Nome do caso de uso**                               | **UC5 - Adicionar Vídeos a uma Playlist**                                                                     |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Caso de uso geral**                                 | Fluxo Principal                                                                                               |
| **Ator principal**                                    | Usuário                                                                                                       |
| **Atores secundários**                                | N/A                                                                                                           |
| **Resumo**                                            | Este caso de uso descreve as etapas que o usuário precisa fazer para adicionar qualquer vídeo a uma playlist. |
| **Pré-Condições**                                     | O usuário deve estar **logado** em sua conta.                                                                 |
| **Pós-Condições**                                     | O vídeo deve ser adicionado à playlist. O contador de quantos vídeos a playlist tem deve ser **atualizado**.  |
| **Ações do Ator**                                     | **Ações do Sistema**                                                                                          |
| 1 – Selecionar qualquer vídeo enviado por um usuário. |                                                                                                               |
| 2 - Clicar em "Adicionar a Playlist..."               |                                                                                                               |
| 3 - Selecionar uma playlist.                          |                                                                                                               |
|                                                       | 4 - Adicionar o id do vídeo selecionado a playlist selecionada no sistema.                                    |
|                                                       | 5 - Atualizar a playlist com o novo vídeo adicionado.                                                         |
|                                                       | 6 - Atualizar o contador de vídeos na playlist.                                                               |
| **Restrições/Validações**                             | O usuário não pode assitir dois vídeos ao mesmo tempo.                                                        |

<div align="center">
  Tabela 5 - Especificação do caso de uso Adicionar Vídeos a uma Playlist.
</div>

---

| **Nome do caso de uso**                               | **UC6 - Curtir Vídeos**                                                                            |
| ----------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Caso de uso geral**                                 | Fluxo Principal                                                                                    |
| **Ator principal**                                    | Usuário                                                                                            |
| **Atores secundários**                                | N/A                                                                                                |
| **Resumo**                                            | Este caso de uso descreve as etapas que o usuário precisa fazer para "curtir" um vídeo específico. |
| **Pré-Condições**                                     | O usuário não pode já ter dado uma curtida. O usuário precisa estar logado.                        |
| **Pós-Condições**                                     | O contador de curtidas deve **aumentar em + 1**.                                                   |
| **Ações do Ator**                                     | **Ações do Sistema**                                                                               |
| 1 – Selecionar qualquer vídeo enviado por um usuário. |                                                                                                    |
| 2 - Clicar no vídeo para assisti-lo.                  |                                                                                                    |
| 3 - Clicar na opção "Curtir".                         |                                                                                                    |
|                                                       | 4 - Registrar a "Curtida" no vídeo específico.                                                     |
|                                                       | 5 - Atualizar o contador de "Curtidas".                                                            |
|                                                       | 6 - Desabilitar ao usuário dar um nova "Curtida".                                                  |
| **Restrições/Validações**                             | O botão de curtida pode ter **dois estados**: curtido, não curtido.                                |

<div align="center">
  Tabela 6 - Especificação do caso de uso Curtir Vídeos.
</div>

# Diagrama de Sequência
<div align="center">
<img width="670" height="528" alt="Diagrama de sequência(Cadastrar)" src="https://github.com/user-attachments/assets/557187fd-ad33-45a3-a689-7f546a2b5f5d" />

Figura 2: Diagrama de Sequência (Cadastrar)

<img width="645" height="500" alt="Diagrama de Sequência(Logar)" src="https://github.com/user-attachments/assets/ebe43efc-5c7b-4b61-9a52-800c52a98def" />

Figura 3: Diagrama de Sequência (Logar)

<img width="660" height="541" alt="Diagrama de Sequência(Assistir Vídeos)" src="https://github.com/user-attachments/assets/bdcb619b-8620-407d-91a7-4038163d205b" />

Figura 4: Diagrama de Sequência (Assistir Vídeos)

---

# Diagrama de Atividades

<img width="661" height="543" alt="Login e Cadastro" src="https://github.com/user-attachments/assets/e949b443-38d9-40de-ac65-8abed19ec430" />

Figura 5: Diagrama de Atividade (Login e Cadastro)
