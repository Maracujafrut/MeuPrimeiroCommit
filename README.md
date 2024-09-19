# MeuPrimeiroCommit

Git Add - Move as alterações do diretório de trabalho para a área de staging. Assim, você tem a oportunidade de preparar um instantâneo antes de realizar o commit ao histórico oficial.

Git Branch - Esse comando é a ferramenta de administração de ramificações de uso geral. Permite criar ambientes de desenvolvimento isolados em um único repositório.

Git Checkout - Além de verificar commits antigos e revisões de arquivos antigos, o git checkout também é a forma de navegar pelas ramificações existentes. Combinado com os comandos básicos do Git, é a maneira de trabalhar em determinada linha de desenvolvimento.

Git Clean - Remove os arquivos não monitorados do diretório de trabalho. Esse é o correspondente lógico do git reset, que (em geral) só opera em arquivos monitorados.

Git Clone - Cria cópia de um Repositório do Git existente. A clonagem é o modo mais comum dos desenvolvedores obterem uma cópia de trabalho de um repositório central.

Git Commit - Faz um commit do instantâneo preparado no histórico do projeto. Combinado com git add, esse processo define o fluxo de trabalho básico para todos os usuários do Git.

Git Commit--Amend - Informação da marcação -- amend ao git commit permite corrigir o commit mais recente. Isso é muito útil quando você esquece de preparar um arquivo ou para omitir informações importantes da mensagem do commit.

Git Config - Uma maneira conveniente de definir opções de configuração para a instalação do Git. Em geral, sua utilização só é necessária de modo imediato após a instalação do Git em máquina de desenvolvimento nova.

Git Fetch - A busca faz o download a partir da ramificação de outro repositório, junto com todos os commits e arquivos associados. Mas, não tenta integrar nada em o repositório local. Assim, você tem a oportunidade de inspecionar as alterações antes de fazer o merge no projeto.

Git Init - Inicializa novo repositório do Git. Se você quiser colocar um projeto sob controle de revisão, este é o primeiro comando que você precisa aprender.

Git Log - Permite explorar as revisões anteriores de determinado projeto. Ele oferece várias opções de formatação para exibir o commit de instantâneos.

Git Merge - Uma maneira poderosa de integrar alterações de ramificações divergentes. Após bifurcar o histórico do projeto com o git branch, o git merge permite unificar o histórico de novo.

Git Pull - É a versão automatizada do git fetch. Faz o download de ramificação de um repositório remoto e faz a mesclagem imediata na ramificação atual. É o equivalente Git do svn update.

Git Push - É o oposto de buscar (com algumas ressalvas). Permite que você mova uma ramificação local para outro repositório, o que é um modo conveniente de publicar as contribuições. É semelhante ao svn commit, mas envia uma série de commits em vez de um único conjunto de alterações.

Git Rebase - Permite mover ramificações, o que ajuda a evitar commits de merge desnecessários. A história linear resultante é, em geral, muito mais fácil de entender e explorar.

Git Rebase-i - A marcação -i é usada para iniciar uma sessão de rebase interativa. Ela apresenta todos os benefícios de um rebase normal, porém, dá a oportunidade de adicionar, editar ou excluir commits durante o processo.

Git Reflog - O Git mantém o controle das atualizações na ponta das ramificações usando um mecanismo chamado reflog. Ele permite retornar aos conjuntos de alterações mesmo que não estejam referenciados por nenhuma ramificação ou marcação.

Git Remote - Uma ferramenta prática para administrar conexões remotas. Em vez de passar o URL completo para os comandos fetch, pull e push, ele permite usar um atalho mais significativo.

Git Reset - Desfaz as alterações nos arquivos no diretório de trabalho. A redefinição permite limpar ou remover por completo as alterações que não foram enviadas a um repositório público.

Git Revert - Desfaz o commit de um instantâneo. Ao identificar um commit com falha, uma maneira fácil e segura de realizar a sua remoção da base de código é por meio da reversão.

Git Status - Exibe o estado do diretório de trabalho e o instantâneo preparado. Utilize essa opção em conjunto com os comandos git add e o git commit para ver com precisão o que vai ser incluído no próximo instantâneo.