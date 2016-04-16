## Relação de todos os artigos já publicados em nosso [blog](https://blog.cienciahacker.ch)
**Ordem: Mais novo >> Mais velho**  

###[Encodando backdoor em arquivos .exe](https://blog.cienciahacker.ch/encodando-backdoor-em-arquivos-exe/) 
Mostraremos alguns dos muitos recursos do Msfvenom, ao qual podemos encodar uma backdoor em um arquivo executável (.exe). De uma forma simples, ele permite que se clone um programa executável anexando nossa backdoor, a qual o programa será executado normalmente rodando o malware em background.  

###[Explorando a vulnerabilidade SQLi via Post – Sqlmap](https://blog.cienciahacker.ch/explorando-falha-sqli-com-sqlmap-metodo-post/)
Como muito visto, a falha de SQLi é muito abordada sobre o modo de exploração via GET, que se explora através dos parâmetros na URL. Traremos hoje a exploração do SQLi através do método POST, utilizando a ferramenta Sqlmap. Na exploração via POST, a falha está associada ao formulário da requisição que é enviado pela aplicação em sua query, sendo possível explorar essa requisição de modo malicioso onde podemos consultar no banco de dados informações do alvo, como login/senhas de usuários, informações de perfis de clientes, entre outras.  

###[Criando wordlist com o Crunch](https://blog.cienciahacker.ch/criando-wordlist-com-o-crunch-2/)  
Quando citamos a palavra “bruteforce” (força bruta), é inevitável deixarmos de pensar em uma wordlist (lista de palavras). Wordlist’s são arquivos que possuem diversas combinações de palavras e/ou números e símbolos com finalidade de realizar um ataque de força bruta, visando identificar uma senha qualquer.

###[Análise de Redes Wireless – Suíte Aircrack-ng](https://blog.cienciahacker.ch/analise-de-redes-wireless-suite-aircrack-ng/)  
Em tempos onde praticamente qualquer estabelecimento comercial ou residencial possui sua própria rede wireless, não resta dúvida que se trata de um vasto território carente de importantes cuidados com configurações de segurança.

A seguir mostraremos uma dentre tantas formas de se burlar critérios de segurança, que se mal configurados fazem papel contrário ao que se propõem, abrindo brechas de acesso e vulnerabilidades em sua composição.


###[Armitage, ferramenta de gerenciamento de ataque cibernético](https://blog.cienciahacker.ch/armitage-ferramenta-de-gerenciamento-de-ataque-cibernetico/)  
O Armitage é uma ferramenta de gerenciamento de ataques cibernéticos em modo gráfico, foi desenvolvida por Raphael Mudge para tornar o processo de exploração e pós-exploração mais simples.

###[Explorando recursos de ataque do Meterpreter](https://blog.cienciahacker.ch/explorando-recursos-de-ataque-do-meterpreter/)
Adentrando ao mundo do Metasploit, o payload Meterpreter (Meta-intérprete) está disponível para a utilização de seus recursos.

Com a finalidade de fornecer diversas funcionalidades que seriam complicadas e/ou entediantes para implementação manual, seu funcionamento permite que os atacantes escrevam suas próprias extensões em forma de arquivos de objetos compartilhados (DLL), que podem ser  injetados e carregados em um processo em execução no computador de destino do atacante após a exploração.

###[Criando e encriptando backdoor com Msfvenom](https://blog.cienciahacker.ch/criando-e-encriptando-backdoor-com-msfvenom/)  
Com a nova atualização da ferramenta do Metasploit, mudaram alguns comandos e sintaxes para gerar backdoors. Deixaremos as novas sintaxes e dicas das novas funcionalidades e sintaxe do Msfvenom.

###[Evidenciando e identificando servidores SSL/TLS vulneráveis](https://blog.cienciahacker.ch/evidenciando-e-identificando-servidores-ssltls-vulneraveis/)  
Na análise de vulnerabilidade em infraestrutura, uma das verificações a serem feitas é na versão do serviço do SSL/TLS, caso esteja numa versão obsoleta, é possível explorar vulnerabilidades sobre alguns vetores de ataque como gênero (MITM Main The Middle). Com ferramentas como SSLScan, SSLyze e Nmap, podemos recolher informações da versão do serviço rodando e as cifras que …  

###[Introdução à binários ELF no Linux: Compreensão e Análise](https://blog.cienciahacker.ch/intro-a-binarios-elf-no-linux-compreensao-e-analise/)  
Executable and Linkable Format [ELF] Formato executável e de ligação Um profundo mergulho em arquivos ELF: resposta a incidentes de segurança, desenvolvimento e uma melhor compreensão Nós muitas vezes não percebemos as habilidades de outros pois as concebemos como normais. Uma dessas coisas é o uso de ferramentas comuns, como ps e ls. Mesmo que …  

###[Escalação de privilégio com PowerShell](https://blog.cienciahacker.ch/escalacao-de-privilegio-com-powershell/)  
Escalação de privilégio é uma tarefa que se prova ser difícil às vezes. No passado, se poderia confiar no Metasploit como um framework de exploração completo. Com o Metasploit, não só seria capaz de explorar uma vulnerabilidade mas também rapidamente elevar os privilégios com o comando ‘getsystem’. De qualquer maneira, com o cenário da cybersegurança constantemente em mudança, foi apenas uma questão de tempo antes que administradores de rede implementassem novos avanços tecnológicos que detectariam e preveniriam a maioria dos payloads do Metasploit. Com uma das ferramentas favoritas de pentesters agora sendo detectada, os profissionais de segurança precisavam encontrar uma solução alternativa.

###[Montando um laboratório para análise de malware](https://blog.cienciahacker.ch/montando-um-laboratorio-para-analise-de-malware/)  
Há duas maneiras iniciais para se montar um laboratório de análise. Máquinas Virtuais Máquinas Físicas Máquinas físicas? Sim! Você pode usar aquele seu laptop da Xuxa que não podia ver uma smoke na dust2 que o PC explodia ou você pode optar por usar máquinas virtuais, processo mais rápido, fácil porém há malwares que conseguem identificar …

###[Realizando varreduras e descoberta de vulnerabilidades com Arachni Web Scanner](https://blog.cienciahacker.ch/realizando-varreduras-e-descoberta-de-vulnerabilidades-com-arachni-web-scanner/) 
O Arachni é uma ferramenta de análise de vulnerabilidades em servidores e aplicações Web, ideal para análises White/Gray Box devido ao alto número de requisições e barulho no servidor alvo.
Ele é totalmente escrito em Ruby e possui uma plataforma para rodar em Shell e um painel Web, onde é possível realizar várias análises e gerar relatórios e gráficos administrativos sobre o alvo.

###[Empire – Criando backdoor através de arquivos maliciosos](https://blog.cienciahacker.ch/empire-criando-backdoor-atraves-de-arquivos-maliciosos/)  
O Empire é uma ferramenta open source que permite infectar o computador da vítima através de macros maliciosas, que são executadas automaticamente quando habilitadas nos arquivos como doc, xls, pdf, etc. Essa infecção permite ganhar o acesso remoto com a vítima, a qual na manutenção do ataque são explorados via comandos do power shell, facilitando o bypass sobre os antivírus.

###[Footprint – Levantando informações do alvo](https://blog.cienciahacker.ch/footprint-levantando-informacoes-do-alvo/)  
Hoje iremos abordar sobre a técnica de arrecadamento de informações, conhecida como Footprint. Ela consiste em levantar o máximo de informações possíveis para mapear a estratégia de ataque num alvo. Veremos como elaborar o passo a passo, os mecanismos e ferramentas utilizadas nesse processo para fazer uma coleta eficiente.  

###[O malware por trás dos atalhos](https://blog.cienciahacker.ch/o-malware-por-tras-dos-atalhos/)  
Um tipo de malware vem causando vários transtornos aos usuários. Trata-se de um vírus que infecta o pendrive, transformando todos os arquivos e documentos em atalhos. Encontrado com diversos nomes, nós iremos chamá-lo de COOL.vbs.

###[Decifrando senhas do Shadow com John The Ripper](https://blog.cienciahacker.ch/decifrando-senhas-do-shadow-com-john-the-ripper/)  
Hoje traremos um artigo especialmente para aqueles que gostam de participar de campeonatos de Capture the Flag (CTF). Para quem participou do Roadsec, viu um desafio relacionado a decifrar uma senha de um usuário do shadow. Por isso demonstraremos como você pode decifrar a hash e também como pegar as senhas dos respectivos serviços de um host.

###[Explorando e tratando a falha de Cross-site-scripting (XSS)](https://blog.cienciahacker.ch/explorando-e-tratando-a-falha-de-cross-site-scripting-xss/)  
Muito pouco falada e com alto nível crítico dentro das vulnerabilidades relatadas, o Cross-site-scripting (XSS) ocorre na aplicação web em que os parâmetros inseridos no servidor não são tratados devidamente, permitindo que o usuário mal intencionado insira códigos (como em HTML e JavaScript) que manipulam instruções, como as estruturas de documentos HTML, roubo de sessões no sistema/credenciais, redirecionamento para sites maliciosos, entre outras coisas.  

###[Entendendo a fundo os conceitos e práticas sobre Engenharia Social](https://blog.cienciahacker.ch/entendendo-a-fundo-os-conceitos-e-praticas-sobre-engenharia-social/)  
A engenharia social é conhecida como a técnica de persuadir e ludibriar pessoas com o fim de obtenção de informações privilegiadas cujas são muito utilizadas para extração de login/senhas, dados pessoais, credenciais, entre outras informações. Sendo explorada tanto em ambiente corporativo ou com vítimas aleatórias que aproveita-se de fraquezas emocionais podendo ser feita fisicamente ou mediante algum meio tecnológico. Abordaremos os tipos de ataques utilizados na engenharia social, os meios que se utiliza e como entrar a fundo nesse meio.  

###[Realizando ataque Man in the Middle com SSLStrip e Ettercap](https://blog.cienciahacker.ch/realizando-ataque-man-in-the-middle-com-sslstrip-e-ettercap/)  
Neste tutorial iremos abordar o tipo de ataque conhecido como Man in the Middle. Esse teste “envenena” a Tabela ARP da vítima, fazendo com que a máquina atacante – nossa máquina – se passe pelo roteador, fazendo com que consigamos interceptar o tráfego e ter acesso a dados sigilosos trocados entre os dois atores.

###[Auditando e criando relatório de análise de vulnerabilidades com Nessus](https://blog.cienciahacker.ch/auditando-e-criando-relatorio-de-analise-de-vulnerabilidades-com-nessus/)  
Nessus é uma das ferramentas mais recomendadas para fazer análise de vulnerabilidade, devido apresentar uma interface interativa e ter capacidade de gerar relatórios bem robustos. Traremos aqui como instala-lo, e como fazer uma análise de vulnerabilidade (scanning) sobre o alvo, mostrando alguns de seus recursos como a geração de relatório.   

###[Mini-Playlist](https://blog.cienciahacker.ch/mini-playlist/)  
Eu fiz essa pequena playlist só pra da uma animada nesse fim de semana. Caso queira sugerir mais músicas, comenta aí – eu vou adorar. OBS: Caso precise de um email, você pode conseguir um no Temp Mail  

###[No Tech Hacking](https://blog.cienciahacker.ch/no-tech-hacking/)  
O No Tech Hacking é um conceito definido pela utilização de técnicas de ataques que não usam apoio de aparatos tecnológicos, as quais geralmente são usados para testar a segurança física de um alvo. As técnicas que giram envolta dele são na base do uso da engenharia social, por necessitar boa parte delas da interação humana.  

###[Fazendo varredura e levantando vulnerabilidades com Nikto](https://blog.cienciahacker.ch/fazendo-varredura-e-levantando-vulnerabilidades-com-nikto/)  
O Nikto é uma ferramenta em Perl desenvolvida por Chris Solo e David Lodge, a qual foi escrita para validação de vulnerabilidade suportando diversas plataformas, entre elas Windows, Linux e UNIX. Ao contrário de alguns scanners de segurança, o Nikto foi projetado para operar em um modo furtivo, mesmo assim ele causa um ruído como os demais scanners.  

###[Lista de Dorks – Joomla](https://blog.cienciahacker.ch/lista-de-dorks-joomla/)  
Lista de Dorks utilizadas para Joomla  

###[GnuPG](https://blog.cienciahacker.ch/gnupg/)  
Gnu Privacy Guard [0] (ou GnuPG, ou mais reduzido ainda, GPG) é uma implementação do protocolo de cifragem de mensagens OpenPGP.  

Em uma vídeo aula [1], disponibilizada no canal Ciência Hacker, foi mostrado o uso do GPG. Aqui vai um artigo para introduzir o conceito e utilização dele ao leitor.  

###[Lista de Dorks – Câmeras de Vídeo](https://blog.cienciahacker.ch/lista-de-dork-cameras-de-video/)  
Lista de Dorks utilizadas para Câmeras de Vídeo  

###[Lista de Dorks – XSS](https://blog.cienciahacker.ch/lista-de-dork-xss/)  
Lista de Dorks utilizadas para XSS  

###[Lista de Dorks – LFI](https://blog.cienciahacker.ch/lista-de-dork-lfi/)  
Lista de Dorks utilizadas para LFI  

###[Lista de Dorks – RFI](https://blog.cienciahacker.ch/lista-de-dork-rfi/)  
Lista de Dorks utilizadas para RFI  

###[Lista de Dorks – SQLi](https://blog.cienciahacker.ch/lista-de-dork-sqli/)  
Lista de Dorks utilizadas para SQLi  

###[Se Precavendo Contra Roubo de Celular](https://blog.cienciahacker.ch/se-precavendo-contra-roubo-de-celular/)  
Muitas de nossas informações estão em nossos smartphones, logo é bom ter planos para caso ele fuja de sua mão, seja por perda, furto ou roubo. Portanto, é bom pensarmos nisso e vamos lá!  

###[\[Apache\] Rodar scripts CGI](https://blog.cienciahacker.ch/apache-rodar-scripts-cgi/)  
Para utilizarmos algumas linguagens, como o Perl e o Python na web, precisamos configurar o CGI, que permite a junção entre os dois “lados da moeda”.  

###[Lockpicking – A arte de abrir fechaduras](https://blog.cienciahacker.ch/lockpicking-a-arte-de-abrir-fechaduras/)  
Muitos já viram em filmes hollywoodianos pessoas que abrem fechaduras de carros, casas, cofres e cadeados, e sim, é realmente possível fazer isso, essa técnica é chamada de Lockpicking. Iremos abordar neste artigo conceitos e detalhes dessa técnica, lembrando que o mal uso dela é considerado crime como o Artigo 24 prevê na lei.  

###[\[Linux\] Montando mídias e partições](https://blog.cienciahacker.ch/linux-montando-midias-e-particoes/)  
Muitos usuários pensam que montar uma mídia no Linux por meio de linha de comando é uma tarefa complexa que exige um bom conhecimento. Desmistificaremos isso neste post.  

###[\[Cálculo\] Conversão de bases numéricas – Binário x Decimal](https://blog.cienciahacker.ch/calculo-conversao-de-bases-numericas-binario-x-decimal/)
Hoje trataremos de um assunto muito importante em toda a Informática: a conversão de bases numéricas. Neste post, aprenderemos a converter uma unidade em binário para decimal e vice-versa.  

###[Passando por antivírus com shikata_ga_nai](https://blog.cienciahacker.ch/passando-por-antivirus-com-shikata_ga_nai/)  
Descarte a ideia de se sentir protegido apenas por ter um bom antivírus, após ver esta postagem você vai entender que qualquer antivírus pode ser burlado com certa facilidade.  

###[\[Parte 2\] “Confiança não se compra, se conquista”](https://blog.cienciahacker.ch/confianca-nao-se-compra-se-conquista-parte-2/)   
Dando continuação à [Parte 1] do artigo “Confiança não se compra, se conquista”, veremos Proteção Antirrastreamento (diferente do Não Me Rastreie), como criar Senha Mestra e entender um pouco sobre Conexões Seguras. Recomendados que você leia o primeiro artigo para entender alguns conceitos importantes e outras funcionalidades já demonstradas.

###[Como efetuar ataque de Brute Force com Hydra e como se proteger](https://blog.cienciahacker.ch/ataque-bruteforce-com-hydra-parte-1/)  
O método de ataque conhecido como bruteforce (ou “força bruta”) é um dos métodos de ataque mais usado e questionado em relação na sua eficiência nos dias de hoje, criando um certo preconceito nesse método. Abordaremos detalhes sobre o método de ataque, demonstrando o uso da ferramenta THC Hydra, que explicaremos como utilizar seus recursos e configurar seu ataque.

###[Beholder](https://blog.cienciahacker.ch/beholder/)  
O Beholder é uma ferramenta feita em python3 usando o django desenvolvida pelo Pasknel Ribeiro com o intuito de levantar informações em redes sociais. O funcionamento da ferramenta é bem simples, você escolhe um local do nosso planeta, só não vale a Antártida porque o Happy Feet derrubou a net de lá, e dentro de um raio de X metros você pega os posts do twitter, instagram, flickr e foursquare daquele local.

###[Organon (instalando ferramentas de segurança)](https://blog.cienciahacker.ch/organon-instalando-ferramentas-de-seguranca/)  
Organon é um ferramenta que tem como objetivo facilitar a instalação de ferramentas para pentest em distribuições GNU/Linux como Ubuntu, Debian, Arch linux entre outras. No momento apenas suporta distribuições que possuam os gerenciadores de pacotes APT e PACMAN, pois depende deles para instalar as dependências necessárias para o bom funcionamento das ferramentas que serão instaladas pelo usuário.  

###[Cangibrina – Dashboard Finder](https://blog.cienciahacker.ch/cangibrina-dashboard-finder/)  
Hoje trarei uma ferramenta desenvolvida por mim mesmo – UAU – cujo desenvolvimento inicial teve como motivação a aprendizagem da linguagem de programação Python. Portanto, fui adicionando ao longo do tempo vários recursos que achava interessante.  

###[Explorando vulnerabilidades no WordPress com Wpscan](https://blog.cienciahacker.ch/explorando-vulnerabilidades-no-wordpress-com-wpscan/)  
Muito utiliza-se CMS (como WordPress, Drupal e Joomla) atualmente, devido o fácil gerenciamento que ele permite fazer em websites, porém o que muitos não sabem é a quantidade de falhas contidas nesses serviços. Traremos hoje a ferramenta Wpscan que é utilizada para fazer varreduras em sites gerenciados por WordPress, buscando por falhas de segurança, nos outros artigos traremos ferramentas de scanners para outros tipos de CMS.  

###[\[Linux\] Como criptografar e descriptografar seus arquivos com Ccrypt](https://blog.cienciahacker.ch/linux-como-criptografar-e-descriptografar-seus-arquivos-com-ccrypt/)  
A criptografia é um dos meios que garante a segurança e proteção de nossos dados, deixando a informação ilegível a quem tenta obtê-la sem autorização. Além de garantir a integridade de seus arquivos, ela permite que o acesso seja feito apenas para quem tem a chave (senha) para descriptografa-la. Veremos sobre a ferramenta Ccrypt a qual usaremos no processo para criptografar/descriptografar nossos arquivos.  

###[Como criar um Sistema Operacional | Unix](https://blog.cienciahacker.ch/como-criar-um-sistema-operacional/)  
Esse é um livro digital sobre como escrever um sistema operacional em C/C++ a partir do zero.

###[O que é Ethical Hacking? Conhecendo a filosofia Hacker](https://blog.cienciahacker.ch/o-que-e-ethical-hacking-conhecendo-a-filosofia-hacker/)  
O “Ethical Hacking” (conhecido como ética hacker) é muito confundido em sua definição atual, criando uma bifurcação entre profissionais de segurança da informação e a comunidade hacking. Em sua real definição o ethical hacking trata de valores morais e filosóficos empregado dentro da comunidade hacker, não se limitando apenas em na ética humana, mas em valores trazidos ao longo da cultura e do desenvolvimento tecnológico. 

###[\[Parte 1\] “Confiança não se compra, se conquista”](https://blog.cienciahacker.ch/confianca-nao-se-compra-se-conquista-parte-1/)  
Muitas vezes nós (estudantes da área de Tecnologia) e principalmente “usuários finais”, não nos preocupamos com a navegação propriamente dita, não sabemos a origem do nosso navegador, a empresa por trás dele, seus projetos e desenvolvimento. Isso pode ser um erro na hora de escolher seu navegador favorito, pois existem vários recursos ‘escondidos’ em alguns sites que são capazes de usar sua webcam e seu microfone, rastrear sua localização, enviar dados da sua navegação, por exemplo. Em seguida vou apresentar algumas das ferramentas e funcionalidades específicas do Firefox para você que se preocupa com sua privacidade.
###[Android Hacking: Explorando redes WiFi com zANTI](https://blog.cienciahacker.ch/android-hacking-explorando-redes-wifi-com-zanti/)  
Todos nós estamos acostumados a usar ferramentas sofisticadas para pegar logins e senhas em redes WiFi que só poderiam ser usadas em computadores potentes e com sistemas feitos para isso. E se a partir de um simples celular você tivesse acesso a ferramentas tão poderosas quanto? Isso é possível. E vamos aprender a usar uma delas agora.

###[DoNotSpy10 – Ferramenta anti espionagem para Windows 10](https://blog.cienciahacker.ch/donotspy10-ferramenta-anti-espionagem-para-windows-10/)  
Com o lançamento do Windows 10, várias novas funcionalidades surgiram. Para manter o padrão ‘Microsoft de ser’, junto com essas novas funcionalidades, ela trouxe muitos serviços de diagnóstico para ajudarem na coleta de dados na hora de solucionar um problema. Obviamente alguns usuários ficaram preocupados com a privacidade e a segurança de seus dados, nessa linha de pensamento que surgiu o DoNotSpy10, a primeira ferramenta anti ‘espionagem’ para Windows 10.  

###[[Linux] Compilando o Kernel](https://blog.cienciahacker.ch/linux-compilando-o-kernel/)  
Hoje trataremos de um assunto polêmico discutido entre os usuários Linux: a compilação do Kernel.

Muitos usuários pensam que a compilação de um Kernel é algo “de outro mundo”. Provaremos o contrário neste post.

###[Anonimato e segurança por Proxy, guia para Windows 10](https://blog.cienciahacker.ch/windows-10-adicionando-proxies-garantindo-o-anonimato-basico/)  
O uso do proxy é altamente recomendado para pessoas que desejam ter uma maior segurança e querem evitar ataques de negação de serviço (DDos) e vários outros ataques realizados em cima de seu endereço IP. Isso sem precisar ter muito conhecimento em informática. Proxies não são recomendados para pessoas que desejam um alto nível de anonimato, eles funcionam de forma simples e não garantem anonimato absoluto e podem ser quebrados mais facilmente do que métodos mais sofisticados.

###[Windows 10, saindo da versão Jack Sparrow](https://blog.cienciahacker.ch/windows-10-saindo-da-versao-jack-sparrow/)
Com a vinda do mais novo Windows 10 surgiu a dúvida, já existe ativador seguro para essa versão ? Sim, existe e nesse tutorial vamos descobrir como ativa-lo permanentemente. Com o lançamento do Windows 8, 8.1 e Windows 10  a Micro$oft se preocupou em tornar a vida de quem gosta de usar o Windows piratão mais difícil. Sem a devida ativação você não pode personalizar e fazer configurações mais complexas no sistema. Mas como ninguém para a pirataria já existem formas de ativa-los sem ter original. Para a ativação eu vou usar o Windows 10 pro build 10240.

###[Permissões de arquivos com chmod](https://blog.cienciahacker.ch/linux-permissoes-de-arquivos-com-chmod/)  
Algo muito discutido e até “amedrontador” para alguns usuários Linux é a questão de permissões de arquivos. Muitos usuários veem esse assunto como uma verdadeira “hidra”. Então, caro usuário, aproxime-se e elimine de vez esse pensamento de sua cabeça.  

###[Descompactando arquivos ZIP, RAR, TAR.GZ, BZ2, TAR.BZ2, TAR.XZ, TGZ e GZ no Linux](https://blog.cienciahacker.ch/descompactando-arquivos-zip-rar-tar-gz-bz2-tar-bz2-tar-xz-tgz-e-gz-no-linux/)  
Abra o terminal no Linux, e siga os seguintes comandos para realizar a descompactação.  

###[XFCE – Adicionar atalhos no menu](https://blog.cienciahacker.ch/xfce-adicionar-atalhos-no-menu/#more-1407)
O XFCE é uma interface gráfica preferida por muitos usuários devido à leveza. Porém, essa interface pode não ser tão prática em algumas distros em que o usuário precisa de um pequeno conhecimento para operá-la. Neste tutorial aprenderemos a criar atalhos para aplicações no menu do XFCE.  

###[LILO – Adicionar background](https://blog.cienciahacker.ch/lilo-adicionar-background/)  
O Linux Loader, ou simplesmente LILO, é o gerenciador de boot padrão de algumas distros, entre elas, o Slackware. Por fazer parte do mundo Linux, deve obedecer à seguinte regra: “Keep it simple, stupid“. Vamos aprender neste tutorial a adicionar uma imagem de fundo ao LILO.

###[Beef – Invadindo navegadores sem ser notado](https://blog.cienciahacker.ch/beef-invadindo-navegadores-sem-ser-notado/)  
Beef é uma ferramenta de código aberto usada na invasão de browsers, a qual realiza testes de penetração em navegadores de forma silenciosa e sem que a vítima baixe nada. Ela é bem comum em sistemas desenvolvidos para pentest como o Kali Linux, Parrot, Backbox entre outros. Isso não significa que todas as pessoas que usam esses sistemas saibam de sua existência e como ela funciona.

###[Ping Sweep (ICMP Sweep) [Fping | Nmap]](https://blog.cienciahacker.ch/ping-sweep-fping-nmap/)  
Para entender o ping sweep, é preciso, antes de tudo, entender alguns conceitos para que, ao decorrer da explicação, você não se depare com algum termo desconhecido. Tais conceitos a serem entendidos são os de ping e ICMP. Depois disso, você estará mais familiarizado com o assunto e será mais fácil compreender.

###[Freenet: o real anonimato na internet (Configuração + Uso)](https://blog.cienciahacker.ch/freenet-o-real-anonimato-na-internet-configuracao-uso/)  
Se você acha a rede Tor “segura”, você precisa conhecer a Freenet, uma rede realmente segura, o lugar perfeito para manter conversas, transferências de arquivos, e até grupos de conversa totalmente seguro de hackers e espiões. 

### [Criptografia Assimétrica e Gerenciando Chaves com GnuPG](https://blog.cienciahacker.ch/criptografia-assimetrica-e-gerenciando-chaves-com-gnupg/)  
Não é de hoje que prezamos por segurança ao compartilhar informações, desde a Roma antiga já tinham pensado em uma forma de manter suas mensagens seguras caso fossem interceptadas, dando assim origem ao que conhecemos hoje como a técnica de criptografia, Cifra de César.

### [Criando uma simples backdoor no htaccess](https://blog.cienciahacker.ch/criando-uma-simples-backdoor-no-htaccess/)  
O .htaccess é um arquivo especial para o Apache. Quando um usuário está navegando por alguma página de um website, para todo diretório que ele tentar acessar, o Apache procura primeiro pelo tal do arquivo .htaccess e se encontrar, verifica se existe alguma restrição ou configuração especial. Com htaccess é possível bloquear acessos a diretórios e acessos de apenas determinados IP’s.

### [Linux – Comandos básicos](https://blog.cienciahacker.ch/linux-comandos-basicos/)  
Aprenderemos neste tutorial alguns comandos básicos que serão de grande utilidade para iniciantes em Linux. Os comandos que serão apresentados aqui darão um “empurrão” e auxiliarão o usuário na obtenção de novos conhecimentos.  

### [Explorando falhas de Local File Download (LFD)](https://blog.cienciahacker.ch/explorando-falhas-de-local-file-download-lfd/)  
O LFD  (Local File Download) é uma vulnerabilidade de ocorre em aplicações Web PHP. Com essa vulnerabilidade, é possível obter (fazer o download) arquivos de configuração, usuários e senhas de banco de dados, entre outros dados. As quais podem comprometer não só o website, mas sim o servidor por completo.  

### [Inibindo a Espionagem Comercial com Detekt](https://blog.cienciahacker.ch/inibindo-a-espionagem-comercial-com-detekt/)  
Depois do escândalo do Snowden surgiram muitas organizações voltadas ao combate da espionagem cibernética, um exemplo foi o programa desenvolvido por quatro grupos internacionais de defesa dos direitos civis conhecidos como Anistia Internacional.  A ferramenta que desenvolveram, nomeado como Detekt, tem objetivo de identificar softwares maliciosos usados em espionagem comercial.  

### [Como “dibrar” a espionagem da Microsoft.](https://blog.cienciahacker.ch/como-dibrar-a-espionagem-da-microsoft/)  
Sempre que ligamos o Windows, um teste de conexão é feito automaticamente através do NCSI (Network Connectivity Status Indicator). O computador faz uma requisição de um arquivo de texto no servidor do NSCI em que o Windows pode identificar quando o computador está conectado em uma rede, quando precisa de senha para alguns tipos de rede sem fio e quanto está conectado à internet.  

### [Varrendo portas e serviços com Nmap ( Scanning + Firewall Bypass)](https://blog.cienciahacker.ch/escaneanado-portas-e-servicos-com-nmap/)  
O Nmap (“Network Mapper”) é uma ferramenta de código aberto para exploração de rede e auditoria de segurança. Ela tem como função escanear rapidamente redes amplas, embora também funcione muito bem contra hosts individuais. O Nmap utiliza pacotes IP em estado bruto (raw) de maneira inovadora para determinar quais hosts estão disponíveis na rede, quais serviços (nome da aplicação e versão) os hosts oferecem, quais sistemas operacionais (e versões de SO) eles estão executando, que tipos de filtro de pacotes/firewalls estão em uso, e dezenas de outras características.  

### [Atualizando o sistema e adicionando repositório no Kali Linux](https://blog.cienciahacker.ch/atualizar-repositorio-no-kali-linux/)  
Nesse tutorial abordaremos como atualizar o repositório no Kali Linux e qual sua utilização, destacando uma das maneiras de atualizar a sua distribuição. De uma forma resumida, os repositórios servem para atualizar as ferramentas/recursos do sistema sem que você não tenha que pesquisar pelo software que você deseja instalar ou atualizar, tendo a vantagem de garantir a integridade do programa sem que tenha risco de baixar com ele alguma cópia duvidosa que possa prejudicar seu computador.  

### [Criando e montando imagens ISO](https://blog.cienciahacker.ch/criando-e-montando-imagens-iso/)  
Este post abordará algumas dicas que nos auxiliarão na utilização de imagens ISO no Linux. Aqui aprenderemos a criar, montar e gravar uma imagem ISO utilizando apenas a linha de comando.  

### [Compilando um programa em C manualmente](https://blog.cienciahacker.ch/compilando-um-programa-em-c-manualmente/)  
Muitos são os programadores que estão acostumados com a utilização de uma IDE individual para determinado tipo de linguagem (o C, por exemplo, é um dos campeões). Porém, esta prática não é necessária, sendo que podemos compilar o programa utilizando apenas o próprio compilador correspondente a determinada linguagem. Neste tutorial aprenderemos a compilar um script utilizando o GCC.  

### [Configurando o editor de texto Vim](https://blog.cienciahacker.ch/configurando-o-editor-de-texto-vim/)  
O editor de texto Vim possui uma grande fama no mundo Linux. Conquistando cada vez mais usuários, ele auxilia incrivelmente o desenvolvimento. Além disso, incentiva a pesquisa e o aprendizado do sistema Operacional Linux. Neste tutorial, iremos aprender a configurar o Vim para se tornar um editor texto prático e prazeroso de se trabalhar.  

### [O que é Google Hacking? Técnicas + Conceitos](https://blog.cienciahacker.ch/google-hacking-conceito-e-tecnica/)  
O Google Hacking está cada dia mais conhecido através das técnicas que podemos utilizar para extrair informações através do buscador Google, tais como vulnerabilidades de serviços, aplicações ou até mesmo acesso de dispositivos eletrônico como webcams, câmeras de vigilância, impressoras remotas, servidores, informações de pessoas (RG, CPF, endereço,etc.). Acompanhe o tutorial abaixo que trará mais base de como são feita essas buscas e um vídeo para complementar o conhecimento.  

### [Senhas default de Roteadores (Lista 1)](https://blog.cienciahacker.ch/senhas-default-de-roteadores-lista-1/)  
Diaramente ocorre acessos indevidos a roteadores, devido a má configuração dele. Uma das formas de explorar falhas nele é utilizando senhas default que vem de configuração de fábrica, para tentar ter acesso a ele com privilégio segue uma lista de possíveis senhas e usuários para realização da infiltração.  

### [Esteganografia com Steghide (Linux)](https://blog.cienciahacker.ch/esteganografia-com-steghide-linux/)  
Existe diversas formas de comunicação segurança dentro do hacking, uma delas é a esteganografia. Ela permite que nós enviemos mensagens ocultas para outra pessoa com o fim de manter uma comunicação segura. No uso computacional, seria você esconder uma mensagem dentro de um anexo (seja uma imagem, musica, video) para enviar a um destinatário a qual usaremos a ferramenta Steghide que possibilita a utilização desse recurso.  

### [Ataque Bruteforce com Hydra #Parte 1](https://blog.cienciahacker.ch/ataque-bruteforce-com-hydra-parte-1/)  
Nosso tutorial de hoje iremos abordar sobre o ataque de força bruta (bruteforce) com a ferramenta Hydra. Para quem não conhece o ataque de bruteceforce consiste em tentativas sequencias de verificação sobre um alvo através de uma wordlist (banco de palavras).  Dando exemplo mais claro ele pega uma palavra desse banco de arquivo e verifica se a senha é compatível com o dado correspondente a ela, como no caso uma senha ou usuário.  

### [Explorando falha SQLi com Sqlmap](https://blog.cienciahacker.ch/explorando-falha-sqli-com-sqlmap/)  
A falha SQLi é muito mais comum que você pensa, sendo listada como principal vulnerabilidade na lista da OWASP anualmente, para explorar essa falha usaremos o Sqlmap. Primeiramente precisamos entender o conceito teórico da falha antes de introduzir a parte técnica do ataque, para quem não conhece a falha SQLi está relacionado a falha de programação no banco de dados onde o atacante pode enviar requisições maliciosas a ele retornando dados as quais não poderiam ser extraídos (informações no banco que só deveriam ser acessada por usuário com privilégios).  

### [Trocando senha de administrador no Windows 7 ou 8](https://blog.cienciahacker.ch/trocar-senhas-de-administrador-no-windows-7-ou-8/)  
Traremos uma das formas de trocar senhas de contas de usuários sendo administrador ou usuário comum, utilizaremos o Linux como ferramenta auxiliar nesse processo. Esse processo de troca de senhas pode ser necessário durante uma perícia forense, ou até mesmo num procedimento de pentest. Se você já tem acesso ao cmd como administrador, pule para o final do post. Você vai precisar de um LiveCD/DVD/USB com alguma distribuição linux.  

### [Invadindo Windows 7 e 8 (Conexão Reversa)](https://blog.cienciahacker.ch/invadindo-windows-7-e-8-conexao-reversa/)  
O tutorial de hoje nós trará uma base de como fazer uma invasão ao sistema operacional Windows seja o XP, 7 ou 8 que nós permitirá criar uma conexão reversa com a vítima. Nessa conexão podemos transferir arquivos para nossa máquina, enviar um keylogger, capturar audio ou webcam, entre outras coisas. Estaremos utilizando o Metasploit como ferramenta para atacar nosso alvo.  

### [Mantendo conexão com a vítima (Manutenção de Acesso)](https://blog.cienciahacker.ch/manutencao-de-acesso-mantendo-conexao-com-a-vitima/)  
Como já vimos diversas vezes o ataque que utiliza a conexão reversa vemos que temos acesso total a máquina, mas muitas vezes quando acontece uma queda de conexão devido a um desligamento do dispositivo (computador) ou a queda da internet. Hoje veremos sobre como fazer uma manutenção de acesso que irá permitir todas vez que a vítima reconecte conosco de acordo com as opções que iremos setar na máquina alvo.  

### [Invadindo Windows XP (Metasploit)](https://blog.cienciahacker.ch/invadindo-windows-xp-metasploit/)  
Hoje traremos um tutorial voltado a pentest em sistema operacional XP, mesmo estando descontinuado pela Microsoft ainda ele é muito utilizado por bancos, sistemas comerciais, entre outros serviços. Utilizaremos um exploit que explora a falha da porta smb (445) que permite uma conexão remota com a vítima. Ou seja ao conectarmos a ela teremos controle total sobre o sistema dela, a qual permite interceptar dados, enviar malwares, acessar dispositivos na rede, entre outras coisas. Estaremos utilizando o Kali Linux como exemplo mas necessita apenas baixar e instalar o Metasploit.  

### [Instalando e usando o Proxychains](https://blog.cienciahacker.ch/instalando-e-usando-o-proxychains/)  
Hoje estarei escrevendo como instalar e utilizar o proxychains, porém não entrarei em configurações do mesmo, estaremos utilizando a configuração padrão.  
O que é o Proxychains?  
Proxychains permite que você utilize SSH, TELNET, VNC, FTP, e outras aplicações através de um servidor proxy HTTP(HTTPS) e SOCKS(4/5).  

### [Bypass anti-vírus com msfencode](https://blog.cienciahacker.ch/bypass-anti-virus-com-msfencode/)  
Hoje trarei um um assunto que já abordamos em vídeos no youtube, trata-se de burlar o antivírus utilizando o msfencode. Estarei fazendo um artigo mais resumido pra quem não consegue, ou não gosta, de ver vídeos. Como de costume farei uma introdução a ferramenta, a metodologia dos testes e por fim a execução.  

### [Identificando tipos de Hash](https://blog.cienciahacker.ch/identificando-tipos-de-hash/)  
Durante um pentest deparamos em muitas vezes em situações em que encontramos hashs (senhas criptografadas) a qual necessitamos quebra-las. Mas antes de iniciar o processo para descriptografar uma hash, necessitamos antes identifica-la. Com o Hash-Identifier é possível identificar diversos tipos de hash.  

### [Realizando ataques em redes com T50](https://blog.cienciahacker.ch/realizando-ataques-em-redes-com-t50/)  
O T50 é uma forte ferramenta de ataque utilizado em redes que permite enviar milhares de pacotes por segundo, devido a sua flexibilidade de trabalhar com protocolos (HTTP, UDP, TCP, ARP, entre outros). Dependendo da maneira que você o utiliza pode derrubar servidores, roteadores e diversos tipos de conexões entre dispositivos conectado a rede.   

### [Como fazer Consultas Web – Whois (Windows)](https://blog.cienciahacker.ch/204/)  
Hoje vamos trazer um tutorial simples e muito pedido de como fazer consultas web usando o windows, essas consultas podem trazer informações preciosas sobre nosso alvo como a versão do servidor, e-mail da host, domínios alocados, entre outras informações.  

### [Criando wordlist com o Crunch](https://blog.cienciahacker.ch/criando-wordlist-com-o-crunch/)  
Para entender melhor o funcionamento deste tutorial, vamos ver o que é uma wordlist.  
Wordlist é um conjunto de caracteres ou palavras que ajudam na quebra de alguma criptografia. O Crunch já vem instalado por padrão no Kali Linux, mas se você usa outra distro, pode usar o seguinte comando:  

### [Diferenças entre ataque DoS e DDoS](https://blog.cienciahacker.ch/136/)  
Vemos muitas pessoas que estão começando a estudar métodos hacking cometerem um erro bobo. Muitos sabem que alguns hackers são conhecidos por aplicar ataques DDoS em servidores e acabarem derrubando o site, impedindo que usuários entrem no site atacado.  

### [Hardening em rede wireless](https://blog.cienciahacker.ch/hardening-em-rede-wireless/)  
Bom galera, hoje iremos falar sobre hardening em rede wireless. Irei apresentar algumas ações que acho interessante para tornar sua rede wireless mais segura. Não irei demonstrar como realizar as mudanças na prática porque cada roteador tem uma configuração então isso faria o post limitado a um determinado modelo de roteadores. Irei fazer uma enumeração das mudanças que irei abordar  

### [Camuflando o Mac Address no Linux](https://blog.cienciahacker.ch/camuflando-o-mac-address-no-linux/)  
Para quem não acha que é importante camuflar seu IP durante um ataque, não se pode esquecer do Mac Address também. Ele é responsável pelo endereço de sua placa de rede, podendo também ser também rastreado. Com alguma comandos sem utilização de ferramentas podemos realizar esse processo.  

### [Identificando Usuario na sua rede (Windows)](https://blog.cienciahacker.ch/identificando-ips-na-sua-rede-pelo-windows/)  
Esse tutorial irá falar de como descobrir os usuários conectado a sua rede (roteador), através do IPs vemos o nome do usuário, endereço da placa de rede, entre outras informações. Estaremos utilizando a ferramenta Wnetwatcher que facilitará esse processo sem entrar nas configurações de seu roteador.  

### [Introdução ao Nmap Scripting Engine (NSE)](https://blog.cienciahacker.ch/introducao-ao-nse/)  
Todos nós conhecemos ou já ouvimos falar da ferramenta Nmap, que teve como propósito inicial a varredura de portas e mapeamento de redes, mas que com o tempo, suas utilidades foram se diversificando nos dando uma quantidade maior de informações sobre o alvo por ser uma ferramenta de código aberto. Assim, com a ajuda da comunidade, a ferramenta evoluiu. Com isso, o Nmap hoje pode ser usado também como ferramenta de teste de invasão cujo o auxiliar é o Nmap Scripting Engine, ou NSE.   

### [Metasploitable – Hacker Lab](https://blog.cienciahacker.ch/metasploitable-hacker-lab/)  
Você já deve ter ouvido falar sobre o Metasploit, um poderoso Framework com várias funcionalidades e muito útil para um pentester. Existe uma ferramenta que pode te ajudar a brincar um pouco com o metasploit (ou até o Nmap). Vou dar uma dica aqueles que tem um medo assíduo de fazer testes de penetração em redes desconhecidas no qual podem ser pegos por fazer muito barulho ou por caírem em algum tipo de honeypot, ou mesmo aqueles que são White Hat e não querem ferir a privacidade alheia.  

### Introdução a Segurança da Informação
Mini-série sobre assuntos que nos introduzirão à segurança da informação no qual irá te ajudar a ter uma certa noção quando se tratar desse assunto, serão apresentados assuntos técnicos assim como dicas corporativas que te farão ficar cientes da realidade do ambiente em empresas/organizações e saber como evitar problemas ou brechas que possam trazer qualquer tipo de dano na empresa. Esse artigo não tem a finalidade de mostrar técnicas avançadas para auditoria, mas sim introduzir ao assunto que tem também um monte de teoria do que só prática. Mas a teoria é fundamental para quando estiver mais avançado saber compreender os princípios do assunto.  

* [Introdução a Segurança da Informação – Parte 0](https://blog.cienciahacker.ch/intro-a-si-pt-0/)  
* [Introdução a Segurança da Informação – Parte 1](https://blog.cienciahacker.ch/intro-a-si-pt-1/)  
* [Introdução a Segurança da Informação – Parte 2](https://blog.cienciahacker.ch/intro-a-si-pt-2/)  
* [Introdução a Segurança da Informação – Parte 3](https://blog.cienciahacker.ch/intro-a-si-pt-3/)  
* [Introdução a Segurança da Informação – Parte 4](https://blog.cienciahacker.ch/intro-a-si-pt-4/)  
* [Introdução a Segurança da Informação – Parte 5](https://blog.cienciahacker.ch/intro-a-si-pt-5/)  
* [Introdução a Segurança da Informação – Parte 6](https://blog.cienciahacker.ch/intro-a-si-pt-6/)  
* [Introdução a Segurança da Informação – Parte 7](https://blog.cienciahacker.ch/intro-a-si-pt-7/)  
* [Introdução a Segurança da Informação – Parte 8](https://blog.cienciahacker.ch/intro-a-si-pt-8/)  

### [Derrubando servidores com Slowloris](https://blog.cienciahacker.ch/atacando-servidores-com-slowloris/)  
O Slowloris é uma poderosa ferramenta utilizada como ataque de negação de serviço, podendo derrubar ou deixar lento a conexão de um servidor devido a taxa de conexão emitida a um alvo.   

### [Resumo das Leis Cibernéticas – Lei Carolina Dieckmann 12.737](https://blog.cienciahacker.ch/resumo-das-leis-ciberneticas-carolina-dieckmann-lei-12-737/)  
Olá pessoal, hoje iremos falar de uma forma resumida sobre as leis que envolve o cibercrime, muitos já ouviram falar da Lei Carolina Diekcmann (conhecida pela Lei 12.737), mas não sabem ao certo o que ela é ou que representa dentro do contexto hacking. Traremos de uma forma clara o que é considerado cibercrime perante a essa lei, citando suas punições e as principais práticas na atualidade.  
