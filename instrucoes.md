// instalar o Bootstrap 5
npm install bootstrap@5


// Layout Breakpoints
Breakpoint	      Class infix	         Dimensions

Extra  small	     None	               <576px
Small	              sm            	   ≥576px
Medium	              md	               ≥768px
Large	              lg	               ≥992px
Extra large	          xl	               ≥1200px
Extra extra large	  xxl	               ≥1400px


// Layout Grid
A grid possui 12 colunas


//tabelas
//cores de fundo
table-dark - cor escuro
table-primary - cor azul
table-secondary - cor clara cinza
table-danger - cor tom de vermelho
table-warning - cor de yom amarelo
table-light cor clara
-------------------------------------------
table table-striped - deixou a tabela com a linha com cor sim e cor não
table table-striped-columns - deixou a tabela com a coluna com cor sim e cor não
table-hover - quando passa o mouse faz uma 
table-active - destaca uma linha ou coluna
table-bordered - coloca borda em toda a tabela 
table-borderless - retira toda a borda da tabela
table-sm - compacta a tabela diminuindo o padding
table-group-divider - cria uma linha divisoria entre as linha da tabela
---------------------------------------------
align-middle - alinha o texto no meio das celulas da tabela
-------------------------------------------
caption-top - coloca o texto no topo da tabela
---------------------------------------------
table-responsive - colocar uma barra de rolagem somente na tabela
-------------------------------------------------

//Cores e opacidades de textos e planos de fundos

bg-primary -  Blackground azul
bg-body-secondary  -  Blackground cinza
bg-success  -  Blackground verde
bg-danger  -  Blackground vermelho
bg-warning  -  Blackground amarelo
bg-info  -  Blackground azul claro
bg-light -  Blackground branco
bg-dark -  Blackground preto
bg-white  -  Blackground branco
bg-transparent  - Blackground trasparente

bg-opacity-10  - Opacidade de 10%
bg-opacity-25  - Opacidade de 25%
bg-opacity-50  - Opacidade de 50%
bg-opacity-75  - Opacidade de 75%

bg-gradient  -  Cor gradiente de cima para baixo

text-bg-primary  - Faz uma adaptação da cor do texto de acordo com a cor do blackground
text-bg-secondary
text-bg-success
text-bg-danger
text-bg-warning
text-bg-info
text-bg-light
text-bg-dark  -  
text-bg-white
text-bg-transparent


// Ícones do Bootstrap

//Instalação do ícone do bootstrap
npm i bootstrap-icons

//Instalação do ícone do bootstrap por CDN
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">



//Margens Externas e Internas

No CSS as margens externas é representado pelo Margin e as margens internas é representado pelo Padding e sua variante.

//Margens Externas

ms - representa margem Esquerda
me - representa margem direita
mt - representa margem Superior
mb - representa margem Inferior
mx - representa margem Horizontal que seria a esquerda e direita.
my - representa margem Vertical que seria a superior e inferior.
mx-auto - representa margem Vertical de forma centralizada
my-auto - representa margem horizontal de forma centralizada

m-0 - representa sem margem
m-1 - representa a 0.25rem
m-2 - representa a 0.5rem
m-3 - representa a 1.0rem
m-4 - representa a 1.5rem
m-5 - representa a 3.0rem

//Margens Internas

ps - representa margem Esquerda
pe - representa margem direita
pt - representa margem Superior
pb - representa margem Inferior
px - representa margem Horizontal que seria a esquerda e direita.
py - representa margem Vertical que seria a superior e inferior.
px-auto - representa margem Vertical de forma centralizada
py-auto - representa margem horizontal de forma centralizada

p-0 - representa sem margem
p-1 - representa a 0.25rem
p-2 - representa a 0.5rem
p-3 - representa a 1.0rem
p-4 - representa a 1.5rem
p-5 - representa a 3.0rem



//Borda e Sombra

border - representa a sombra
rounded  -  representa ao arrdondamento
shadow - representa a sombra


//Formatação de Texto

text-nowrap  -  não quebra alinha do texto
text-break  -  quebra uma palavra no texto
text-lowercase  -  Coloca todas as palavras em minúscula
text-uppercase  -  Coloca todas as palavras em maiúscula
text-capitalize  -  Coloca todas as palavras coma as iniciais maiúculas

//Tamanho das Fontes

fs-1  - Representa o tamanho maior comparado com o tamanho de H1
fs-2
fs-3
fs-4
fs-5
fs-6  - Representa o tamanho menor comparado com o tamanho de H6

fw-bold - Texto com peso negrido
fw-semibold  - Texto com peso semi-negrido<
fw-normal - Texto com peso normal
fw-light - Texto com peso leve

fst-italic - Texto com estilo itálico 
fst-normal - Texto cpm estilo normal

lh-1 -  As linhas entre o texto fica menor
lh-sm  - As linhas entre o texto fica um pouco maior
lh-base - As linhas entre o texto fica na altura padrão
lh-lg - As linhas entre o texto fica com espaço duplo

font-monospace  - Fonte mono espaçada

text-decoration-none  -  Remove a sublinhado do texto
text-decoration-underline  -  Coloca o texto sublinhado
text-decoration-line-through - coloca um rsico em todo o texto
text-truncate  - Mostra somente a primeira linha do texto


//Configurações de Visibilidades

d-block  - Define como o display block
d-print-none  - não aparece quando imprimi
invisible  - Oculta uma div mais o espaço qu ela ocupa permanece
overflow-auto  - Cria uma barra vertical e horizontal se necessário
overflow-hidden - Oculta o conteúdo que esta transbordando da div
overflow-visible - Mostra todo o conteúdo da div
overflow-scroll - Cria uma barra de rloagem vertical e horizontal


//Configurações de Posicionamento

fixed-top -  fixa no topo
fixed-bottom  -  fixa na parte inferior
sticky-top - fixa quando chega no topo da pagina

vstack - Cria uma pilha vertical
hstack - Cria uma pilha horizontal


//Título Flutuante

form-floating - Permite o texto flutuar em qualquer input textual.


//Cards

card-body - criar uma caixa de contorno meio arrendondado


//Alertas, Badges e Listas

alert alert-primary -  Criar um alerta simples
lert-heading - Cria um título
alert-link - Cria um link
bi-info-circle - Cria um icone
alert-dismissible - Cria uma opção de fechar o alert
<button class="btn-close" data-bs-dismiss="alert"></button>

alert-dismissible fade show - fecha de uma forma mais suave



//Carrosséis de Slides

carousel slide - referece ao efeito de com será mudado os Slides das imagens
carousel slide carousel-fade - referece ao efeito de com será mudado os Slides das imagens
carousel-indicators - referece aos indicadores de imagem
data-bs-slide-to="" - referece a imagem que iraá representar
carousel-inner - referece ao grupo de imagem para o slide
data-bs-interval="3000" - referece ao tempo em que a imagem irá mudar "Nesse exemplo 3 segundos"
data-bs-touch - Desabilta a passagem do slide pela dispositivo móvel
carousel-dark - Os elementos do slide fica escuro



//Painéis desizantes

data-bs-scroll="true" - Permite rolar o conteúdo no fundo da pagina
data-bs-backdrop="false" - Remove o fundo escuro da pagina
data-bs-backdrop="static" - Só fecha o backdrop clicando no botão fechar
offcanvas-start - O OffCanvas abre na esquerda
offcanvas-top - O OffCanvas abre na parte superior
offcanvas-bottom - O OffCanvas abre na parte inferior
style="--bs-offcanvas-width:120px" - Configura a largura do OffCanvas
