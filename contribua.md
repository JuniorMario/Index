# Guia para contribuir com o Ciência Hacker

Antes de tudo, esteja ciente que ao contribuir você está concordando com nossa [Licença](https://github.com/cienciahacker/Index/blob/master/LICENSE) e com o [Código de Conduta](https://github.com/cienciahacker/Index/blob/master/CODE_OF_CONDUCT.md).

## Chegando no GitHub

Se você é novo por aqui, siga esses links antes de continuar! É de suma importância que primeiramente você entenda como tudo funciona. 

1. Aprenda o que é [Git](https://git-scm.com/book/pt-br/v1)

 >Caso tenha dificuldades de entender, inicie aprendendo o que é [Controle de Versão](http://tableless.com.br/introducao-das-premissas-dos-controles-de-versao/).  
 >Assim que sentir que aprendeu, faça esse [Tutorial Interativo](https://try.github.io/levels/1/challenges/) de como usar o Git.  
 >Para ficar bom de verdade, brinque com o [Learn Git Branching Demo](http://learngitbranching.js.org/?demo).   

2. Aprenda a fazer um [Pull Request](http://blog.da2k.com.br/2015/02/04/git-e-github-do-clone-ao-pull-request/).  
3. Aprenda a ~~programar~~ marcar em [Markdown](http://blog.da2k.com.br/2015/02/08/aprenda-markdown/)  

 >Esse artigo tem vários links, inclusive a documentação oficial, então leia atentamente!

## Contribuindo

Agora que você sabe como contribuir, vamos te guiar por alguns tópicos para satisfazer nossa vontade :)

Como esse é um guia que vai abordar todas as sessões do projeto, será organizado por sessões e separado por *orientações* e *formatação*.

### [Sessão Programação](https://github.com/cienciahacker/Index/blob/master/matrix/arquivos/programa%C3%A7%C3%A3o.md)

Como listado nesse [commit](https://github.com/cienciahacker/Index/commit/4724889cd185eb9d362ab183408d97070579cab7), reformamos a estrutura recentemente e a mesma está incompleta e precisando de formatação. Então pode acontecer da estrutura atual contradizer as orientações e a formatação, logo, siga *explicitamente* as orientações e formatação descrita abaixo e nos ajude.

#### Orientações

* Envie apenas cursos, livros, artigos e palestras.

* Serão aceitas **SOMENTE** contribuições com conteúdo livre e gratuito. Sério, vamos verificar tudinho :)

* Não coloque conteúdos hospedados em plataformas de upload (MEGA, GDrive, etc), as chances de não serem livres e gratuitos são altas.

* Sempre tente encontrar o *Autor*, mas caso não encontre, mantenha a estrutura atual.  

* Se for conteúdo traduzido, coloque o Autor que traduziu. 
 
* Priorize conteúdo na língua portuguesa, porém, será aceito conteúdo em espanhol e inglês.

* Links curtos são bem vindos, `http://example.com/dir` - retire a última barra em domínios raiz - é melhor que `http://example.com/dir/index.html`, porém, não serão aceitos links encurtados por sistemas (migre.me, goo.gl, bit.do, etc). 

* Por favor, façam commits com poucas alterações. Se precisar remover, modificar ou adicionar algo de uma só vez, faça isso em vários commits em vez de um, facilita a análise.

* Estamos satisfeitos por enquanto com a nova estrutura, então não à motivos para modifica-la, apenas contribua com o que já temos. Caso tenha um bom argumento para modificar a estrutura, abra uma [issue][issue].

#### Formatação

* Mantenha a tabela em ordem alfabética (a-z) de acordo com a coluna Nome, priorizando os conteúdos em português no topo.

* Se for *Artigo* ou *Palestra*, organize pela coluna Assunto, aglomerando assuntos semelhantes. 

* Use 1 espaço em branco após os headers: `# Título` e não `#Título`.

* Fora isso, não use espaços em branco desnecessários: `[Texto](https://link)` e não `[Texto] (https://link)`.

* Ao colocar o Autor, dê preferência aos seguintes perfis: `GitHub` > `Portifólio` > `Twitter` > `Facebook` > `Outro`.

* A sequência das subseções é: `Cursos` > `Livros` > `Artigos` > `Palestras`. 

* Subseções devem ser declaradas por header nível 3: `### Palestras`.

* Para completar as últimas 4 colunas da tabela você precisa entender que: 

**Lang** - Linguagem do conteúdo.  
 >:us: - Conteúdo em inglês. **Código:** `:us:`  
 >![][brazilian-flag] - Conteúdo em português. **Código:** `![][brazilian-flag]`   
 
**Download** - Se o conteúdo está disponível para download de forma "oficial".  
 >:x: - Não está disponível a opção de download "oficial".  **Código:** `:x:`  
 >:white_check_mark: - Disponível opção de download "oficial". **Códgo:** `:white_check_mark:`  

**Cadastro** - Se necessita cadastro para acessar o conteúdo.
 >:x: - Não é necessário fazer cadastro para acessar o conteúdo. **Código:** `:x:`  
 >:white_check_mark: - É necessário fazer cadastro para acessar o conteúdo. **Código:** `:white_check_mark:`  

**Suxido** - Tipo do conteúdo.
 >:book: - Para conteúdo está em total - ou sua maior parte - formato de texto. **Código:** `:book:`  
 >:camera: - Para conteúdo está em total - ou sua maior parte - formato de vídeo. **Código:** `:camera:`   

* Estrutura básica de toda estrutura: 
```markdown
## [Linguagem](Link da documentação)
### Cursos

Nome | Autor | Curso | Lang | Download | Cadastro | Sufixo 
:-- | :-- | :-- | :--: | :--: | :--: | :--:
Nome do Curso | [Autor](do Curso) | [Link](do Curso) | :us: | :x: | :white_check_mark: | :camera:

### Livros

Nome | Autor | Livro | Lang | Download | Cadastro | Sufixo 
:-- | :-- | :-- | :--: | :--: | :--: | :--:
Nome do Livro | [Autor](do Livro) | [Link](do Livro) | :us: | :x: | :white_check_mark: | :book:

### Artigos

Assunto | Título | Lang 
:-- | :-- | :--: 
Assunto mais genérico do que será abordado | [Título]( com link de acesso ao material) | :us:

### Palestras

Assunto | Título | Lang 
:-- | :-- | :--: 
Assunto mais genérico do que será abordado | [Título]( com link de acesso ao material) | :us:
```
Inicialmente é isso galera, informações de quebras de linhas e espaços em branco em outras partes não foram descritas pois não é pra vocês mexerem nelas!

Essa é a "primeira versão" desse guia e por enquanto irá conter apenas a Sessão de Programação para que vocês possam contribuir de forma adequada.
Posteriormente terá todas as Sessões aqui, mas por hora, acessem esse outro [guia de contribuição][guia] e qualquer dúvida mandem uma [issue][issue] ou mandem mensagem na [página][page].

Ahhh! Esse guia foi inspirado nesse [aqui](https://github.com/vhf/free-programming-books/blob/master/CONTRIBUTING.md); Espero que tenham gostado da leitura e façam parte da nossa comunidade :blush:

[brazilian-flag]: https://github.com/cienciahacker/Index/blob/master/matrix/arquivos/img/brazil_flag.png
[issue]: https://github.com/cienciahacker/Index/issues
[guia]: https://github.com/cienciahacker/Index/blob/master/cienciaHacker/arquivos/contribua.md
[page]: https://www.facebook.com/CienciaHacker
