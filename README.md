Branches e commits semânticos no Git
Relatório — Branches e commits semânticos no Git

Desenvolvimento da atividade
Durante a atividade, foi estudado o funcionamento das branches no Git e a importância de padronizar as mensagens de commit. A branch main representa a linha principal do projeto, enquanto as branches de desenvolvimento permitem trabalhar em funcionalidades e correções de maneira independente.
Foi proposta a criação de um repositório de testes com uma branch chamada feature/mensagem-inicial. Nela, foi desenvolvida uma página HTML simples e realizada uma atualização na documentação do projeto, utilizando os commits semânticos feat e docs.
Após as alterações, foi realizado o merge da branch de desenvolvimento com a branch main, integrando as modificações ao histórico principal.

Comandos utilizados

git init: inicializa o repositório.

git branch -M main: define o nome da branch principal.

git switch -c: cria e acessa uma nova branch.

git add: prepara arquivos para o commit.

git commit -m: registra alterações com uma mensagem.

git switch main: retorna à branch principal.

git merge: integra alterações de outra branch.

git log --oneline --graph --all: permite visualizar o histórico de commits e branches

Conclusão
A atividade demonstrou que o uso de branches permite desenvolver funcionalidades de forma organizada, reduzindo o risco de interferir diretamente na versão principal do projeto. Os commits semânticos tornam o histórico mais claro, facilitando a identificação de funcionalidades, correções e alterações na documentação.
Em projetos desenvolvidos em grupo, essas práticas contribuem para a colaboração, a revisão do código e a manutenção do projeto, tornando o trabalho da equipe mais organizado e eficiente.

