# Regra de Negócio (RN)

| **Identificador** | **Descrição** | **Escopo** | **Prioridade** |
|-------------------|---------------|------------|----------------|
| **RN01** | O usuário deve ter uma conta Google válida para acessar e interagir com o YouTube.| Geral | Essencial |
| **RN02** | Somente o dono do canal pode enviar, editar ou excluir seus vídeos. | Específico | Essencial |
| **RN03** | Os vídeos enviados devem respeitar as políticas de conteúdo e direitos autorais. | Geral | Essencial |
| **RN04** | O criador pode definir a visibilidade do vídeo (público, privado ou não listado). | Específico | Importante |
| **RN05** | Apenas vídeos públicos aparecem em resultados de busca e recomendações. | Específico | Importante |
| **RN06** | O registro das visualizações, curtidas e comentários deve ser feito de forma automática. | Geral | Desejável |
| **RN07** | Canais que violarem repetidamente as políticas podem ser suspensos. | Geral | Essencial |
| **RN08** | A monetização só é permitida para canais que cumprem as diretrizes do Programa de Parcerias. | Específico | Importante |
| **RN09** | Usuários podem denunciar conteúdos inapropriados para análise da equipe de moderação. | Geral | Importante |
| **RN10** | O usuário deve aceitar os termos de uso e a política de privacidade para utilizar o sistema. | Geral | Essencial |



# Requisitos Funcionais (RF)

| ID | Descrição | Pré-Condição | Pós-Condição | Invariante | Testável | Verificável | Escopo | Prioridade |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **RF01** | O sistema deve permitir ao usuário **cadastrar** a sua conta. | O usuário precisa adicionar seu email e senha. | O usuário agora está cadastrado e poderá fazer login. | O usuário não pode cadastrar duas contas com mesmo email. | Sim | Sim | Geral | Essencial |
| **RF02** | O sistema deve permitir o acesso do usuário por meio de **login**. | O usuário precisa estar cadastrado. | O usuário agora pode interagir com funcionalidades que ele não poderia antes. | O usuário não pode estar logado em duas coisas ao mesmo tempo | Sim | Sim | Geral | Essencial |
| **RF03** | O sistema deve permitir o envio de vídeos por usuários. | O usuário precisa estar logado. | O vídeo agora está público/privado na plataforma. | O vídeo precisa ter um título. | Sim | Sim | Geral | Essencial |
| **RF04** | O sistema deve permitir que os usuários assistam qualquer vídeo público publicado por outros usuários. | O usuário precisa ter uma conexão estável com a internet. | O vídeo agora está em estado de "assitido". | O usuário não pode assitir dois vídeos ao mesmo tempo. | Sim | Sim | Geral | Essencial |
| **RF05** | O sistema deve permitir que o usuário adicione um vídeo em uma **playlist**. | O usuário deve estar **logado** em sua conta antes de adicionar. | O vídeo deve ser adicionado à playlist. O contador de quantos vídeos a playlist tem deve ser **atualizado**. | A playlist deve sempre ter **um ou mais vídeos**. | Sim | Sim | Geral | Importante |
| **RF06** | O sistema deve permitir que o usuário dê **curtidas** em vídeos. | O usuário não pode já ter dado uma curtida. O usuário precisa estar **cadastrado**. | O contador de curtidas deve **aumentar em + 1**. | O botão de curtida pode ter **dois estados**: curtido, não curtido. | Sim | Sim | Geral | Essencial |