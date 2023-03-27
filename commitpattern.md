<h1 align="center">
📄 Padrões de commits 
</h1>

De acordo com a documentação do **Conventional Commits**, Commits Semânticos são uma convenção simples para ser utilizada nas mensagens de commit. Essa convenção define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas.

Esses commits auxiliarão a entenderem de forma facilitada quais alterações foram realizadas no trecho de código que foi commitado.

Essa identificação ocorre por meio de uma palavra que identifica se aquele commit realizado se trata de uma alteração de código, atualização de pacotes, documentação, alteração de visual, teste...

## Tipo e Descrição

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` - Commits do tipo build são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `ci` - Commits do tipo ci indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

## ☑️ Recomendações

- Adicione um título consistente com o título do conteúdo;
- Recomenda-se que na primeira linha deve ter no máximo 4 palavras;
- Para descrever com detalhes, usar a descrição do commit;
- Um link precisa ser adicionado em sua forma mais autêntica, ou seja: sem encurtadores de link e links afiliados;

## 📃 Complementos de Commits

- **Rodapé:** Geralmente uma informação sobre o revisor e numero de card de trello ou jira 
  Exemplo: Reviewed-by: Elisandro Mello Refs #133
- **Corpo** : descrições mais precisas do que está contido no commit, apresentando impactos e os motivos pelos quais foram empregadas as alterações no código, como também instruções essenciais para intervenções futuras. 
  Exemplo: see the issue for details on typos fixed.
- **Descrições**:  uma descrição sucinta da mudança
  Exemplo: correct minor typos in code

## 📂 Padrões

<table>
  <thead>
    <tr>
      <th>Tipo de commit</th>
      <th>Palavra-chave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Acessibilidade</td>
      <td></td>
    </tr>
    <tr>
      <td>Adicionando um teste</td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Adicionando uma dependência</td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Alterações de revisão de código</td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Animações e transições</td>
      <td></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Comentários</td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Commit inicial</td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Configuração</td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td></td>
    </tr>
    <tr>
      <td>Estilização de interface</td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Lista de ideias (tasks)</td>
      <td></td>
    </tr>
    <tr>
      <td>Mover/Renomear</td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Package.json em JS</td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Refatoração</td>
        <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td></td>
    </tr>
    <tr>
      <td>Removendo uma dependência</td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Responsividade</td>
      <td></td>
    </tr>
    <tr>
      <td>Revertendo mudanças</td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td></td>
    </tr>
    <tr>
      <td>Tag de versão</td>
      <td></td>
    </tr>
    <tr>
      <td>Teste de aprovação</td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Testes</td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Texto</td>
      <td></td>
    </tr>
    <tr>
      <td>Tipagem</td>
      <td></td>
    </tr>
    <tr>
      <td>Tratamento de erros</td>
      <td></td>
    </tr>
  </tbody>
</table>

## 💻 Exemplos

<table>
  <thead>
    <tr>
      <th>Comando git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m "Commit inicial"</code>
      </td>
      <td>Commit inicial</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "docs: Atualizaçao do README"</code>
      </td>
      <td>docs: Atualizaçao do README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "fix: Loop infinito na linha 50"</code>
      </td>
      <td>fix: Loop infinito na linha 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "feat: Pagina de login"</code>
      </td>
      <td>feat: Pagina de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "ci: Modificaçao no Dockerfile"</code>
      </td>
      <td>ci: Modificaçao no Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "refactor: Passando para arrow functions"</code>
      </td>
      <td>refactor: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "perf: Melhoria no tempo de resposta"</code>
      </td>
      <td>perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "fix: Revertendo mudanças ineficientes"</code>
      </td>
      <td>fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "feat: Estilizaçao CSS do formulario"</code>
      </td>
      <td>feat: Estilizaçao CSS do formulario</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "test: Criando novo teste"</code>
      </td>
      <td>test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "docs: Comentários sobre a função LoremIpsum( )"</code>
      </td>
      <td>docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
  </tbody>
</table>

<div align="center">
  <br/>
  <br/>
  <br/>
</div>
