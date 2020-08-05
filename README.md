# Permissões Linux
### Repositório para eu lembrar as permissões Linux

### Valor das permissões
r => 4 <br>
w => 2 <br>
x => 1 <br>

### Significado das permissões
r => read / ler <br>
w => write / escrever <br>
x => execute / executar <br>

#### Siglas para usar com chmod
a => all / todos <br>
u => user / usuario <br>
g => group / grupo <br>
o => others / outros <br>

### Infos adicionais
chmod => modifica permissões de arquivos/dir <br>
chown => modifica o dono e/ou grupo do arquivo/dir <br>

#### Ex1: Deixar as mesmas permissões para usuários, grupos e outros
#chmod a=rwx nome-arquivo

#### Ex2: Deixar RW para o grupo
#chmod g=rw nome-arquivo

#### Ex3: Incluir permissão de execução para o usuário em um arquivo
#chmod u+x nome-arquivo

#### Ex4: Remover TODAS as permissão de um arquivo
#chmod a-rwx
