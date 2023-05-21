# Curso Digital: Git

## Estados do Arquivo
<table>
    <tr>
        <th scope="col">Untracked</th>
        <th scope="col">Unmodified</th>
        <th scope="col">Modified</th>
        <th scope="col">Staged</th>
    </tr>
    <tr>
        <td>add file</td>
    </tr>
    <tr>
        <td></td>
        <td>edit file</td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td>stage file</td>
    </tr>
     <tr>
        <td>remove file</td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td>commit</td>
    </tr>
</table>

## Comandos
    - git clone: clonar repositorio
    - git init: iniciar novo repositorio
    - git status
    - git add
    - git diff: vericar arquivos modificados
    - git diff --staged
    - git commit -m "mensagem": teste
    - git log
    - git restore
    - git restore --staged

## Repositórios Remotos
    - git remote add origin https://github.com/MahFLima/git-digital-course.git
    - git remote permite criar, ver e excluir conexões com outros repositórios
    - git push origin main: usado para enviar o conteúdo do repositório local para um repositório remoto.
    - git diff origin/main: verifica as atualizações de acordo com o repositorio remoto.
    - git pull: atualiza de acordo com o repositorio remoto automaticamente.
    - git fetch: baixa o conteúdo remoto e não altera o estado do repositório local.