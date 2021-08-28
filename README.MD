Meu primeiro contato com o Git.
Comandos do Git

Status Geral
git status

Trackear
git add -A

Comitar
git commit -m "mensagem"

Ver situação do Repositório
git log

Voltar para etapa desejada do desenvolvimento
git reset --hard hash
git reset --soft hash

Movimentar entre Branch
git branch <nome branch>

Mudar de Branch
git checkout <nome branch>

Ver diferenças em arquivo
git diff 

Ver quais arquivos têm diferenças
git diff --name-only

Ver diferenças em determinado arquivo
git diff --index.html

Voltar para o conteúdo anterior
git checkout HEAD --<nome arquivo>

Publicar no GitHub
git push -u origin master



usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]    
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]       
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

Reverter determinado commit sem perder código feito
git revert [--[no-]edit] [-n] [-m parent-number] [-s] [-S[<keyid>]] <commit>


mod para o push
           editei no GitHub
