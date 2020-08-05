# Permissões Linux
## Repositório para eu lembrar as permissões Linux

### Valor das permissões
r => 4
w => 2
x => 1

### Significado das permissões
r => read / ler
w => write / escrever
x => execute / executar

#### Siglas para usar com chmod
a => all / todos
u => user / usuario
g => group / grupo
o => others / outros

### Infos adicionais
chmod => modifica permissões de arquivos/dir
chown => modifica o dono e/ou grupo do arquivo/dir

#### Ex1: Deixar as mesmas permissões para usuários, grupos e outros
#chmod a=rwx nome-arquivo

#### Ex2: Deixar RW para o grupo
#chmod g=rw nome-arquivo

#### Ex3: Incluir permissão de execução para o usuário em um arquivo
#chmod u+x nome-arquivo

#### Ex4: Remover TODAS as permissão de um arquivo
#chmod a-rwx
