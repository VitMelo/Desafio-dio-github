O Git é um sistema de controle de versão distribuído, usado para rastrear mudanças em arquivos de código-fonte ao longo do tempo. Ele permite que desenvolvedores trabalhem em equipe ou individualmente, mantendo um histórico organizado de tudo o que foi feito no projeto.

 O que o Git faz:

    Salva versões do seu código em diferentes momentos (commits).

    Permite voltar a versões anteriores se algo der errado.

    Facilita o trabalho em equipe, permitindo que cada pessoa tenha sua cópia do projeto e depois envie suas alterações para um repositório central (como o GitHub).

    Ajuda a resolver conflitos quando duas pessoas editam o mesmo arquivo.

    Organiza funcionalidades ou correções em ramificações (branches) separadas.

Exemplo simples:

Você começa um projeto e usa o Git para registrar:

    Primeira versão do código → commit

    Adiciona nova funcionalidade → commit

    Corrige um erro → commit

Se algo quebrar, você pode voltar para a versão anterior com segurança.

 Distribuído?

Sim! Porque cada pessoa tem uma cópia completa do repositório, com todo o histórico. Isso aumenta a segurança e independência no desenvolvimento.

Git ≠ GitHub

    Git: ferramenta local para controle de versões.

    GitHub: plataforma online que hospeda repositórios Git e facilita a colaboração.

O linux e o Windowns possum comandos diferentes nos terminais. Mas no git é possível utilizar as duas formas de comando. 

EX: DIR e LS - listar pastas 

básico para criar, controlar e colaborar em projetos com Git.

Configurar o Git (uma vez por máquina): 
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

Criar um repositório Git local:
git init

Clonar um repositório remoto (como do GitHub):
git clone https://github.com/usuario/repositorio.git

Verificar o status do repositório:
git status

Adicionar arquivos ao stage (preparar para commit):
git add nome_do_arquivo
ou adicionar tudo:
git add . *

Criar um commit (salvar uma versão com mensagem):
git commit -m "Mensagem explicando a alteração"

Enviar mudanças para o repositório remoto (como GitHub):
 git push origin nome_da_branch
Ex: git push origin main

 Trazer atualizações do repositório remoto para o seu:
git pull origin nome_da_branch
