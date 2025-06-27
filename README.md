# O que é esse repositório?

Esse repositório faz parte do curso da Dio Java Europe. Nesse projeto, desenvolvi um protótipo de Ebook utilizando o Canva(Ferramenta Grátis e Acessível para mim).

O conteúdo, como pedido no curso, foi escrito por uma IA e diagramado e estilizado por mim. Espero que goste!

## Prompts Utilizados

1. Crie um título para um ebook sobre o tema: Desenvolvimento de Jogos Indie com Godot. O título deve ser atrativo e curto.
   ChatGPT said:

"Godot na Veia: Crie Seus Jogos Indie do Zero"

Outras variações curtas e atrativas que você pode considerar:

    "Indie com Godot"

    "Godot Indie: Do Sonho ao Jogo"

    "Crie Jogos com Godot"

    "Godot em Ação!"

    "Godot para Indies"

Se quiser posso sugerir também subtítulos complementares para enriquecer o material. Deseja?
You said:
Me dê um título com subtítulo engajante e imperativo
ChatGPT said:

Claro! Aqui vai uma sugestão com tom engajante e imperativo:

Título:
"Domine a Godot"

Subtítulo:
"Crie, Programe e Lance Seus Próprios Jogos Indie com Liberdade e Criatividade"

Se quiser outras variações no mesmo estilo, aqui vão mais duas opções:

Título:
"Crie Jogos com Godot Agora!"
Subtítulo:
"O Guia Definitivo para Desenvolvedores Indie que Querem Tirar Ideias do Papel"

Título:
"Godot em Suas Mãos"
Subtítulo:
"Aprenda a Desenvolver Jogos Indie do Zero e Publique Sua Própria Obra"

Quer um título mais técnico, mais descontraído ou voltado a um público específico (como iniciantes, artistas, programadores)? Posso ajustar.
You said:
Crie uma capa para o título 'Godot em Suas Mãos. Aprenda a Desenvolver Jogos Indie do Zero e Publique Sua Própria Obra'. Faça um boneco robô que lembre o do godot num estilo pixel art
ChatGPT said:
Generated image
Generated image
Generated image
You said:
Me retorne texto para o Capítulo 1, que fala sobre: O que é Godot?
ChatGPT said:

Claro! Aqui está uma sugestão de texto para o Capítulo 1: O que é Godot? com linguagem clara, engajante e voltada para quem está começando no desenvolvimento de jogos indie:
Capítulo 1: O que é Godot?

Se você está entrando agora no mundo do desenvolvimento de jogos, talvez já tenha ouvido falar da Godot Engine. Mas afinal, o que é Godot? E por que tantos desenvolvedores indie têm apostado nessa ferramenta?

A Godot é uma engine de desenvolvimento de jogos 2D e 3D de código aberto, gratuita e extremamente poderosa. Criada para ser acessível, leve e flexível, ela permite que desenvolvedores de todos os níveis – do iniciante ao experiente – transformem ideias em jogos jogáveis de forma rápida e intuitiva.
Por que a Godot se destaca?

    Código aberto e gratuito: Diferente de outras engines que exigem licenças caras ou porcentagens sobre lucros, a Godot é 100% livre. Você pode usá-la para criar jogos comerciais sem pagar nada ou se preocupar com royalties.

    Multiplataforma: Com a Godot, você pode desenvolver para Windows, Linux, macOS, Android, iOS, HTML5 e até mesmo consoles (com suporte adicional). Um jogo, várias plataformas.

    Foco em 2D e 3D: Ao contrário de outras engines que são “3D-first”, a Godot oferece um sistema 2D robusto e nativo. Isso faz dela uma escolha excelente para jogos indie, pixel art, plataforma, visual novels e muito mais.

    GDScript: Uma linguagem de script própria, parecida com Python, feita para facilitar a vida do desenvolvedor. Rápida de aprender e perfeita para prototipagem.

    Interface intuitiva: A interface da Godot é organizada, com um fluxo de trabalho baseado em “nós” (nodes), que torna o processo de construção do jogo visual e lógico ao mesmo tempo.

A filosofia da Godot

Mais do que apenas uma engine, a Godot carrega uma filosofia de acessibilidade, comunidade e liberdade criativa. Ela é mantida por uma comunidade ativa de desenvolvedores ao redor do mundo e está em constante evolução.

Escolher a Godot é mais do que escolher uma ferramenta: é se juntar a um movimento de criadores que acreditam que qualquer pessoa pode fazer jogos, mesmo sem grandes orçamentos ou equipes gigantescas.

Se quiser, posso complementar com curiosidades históricas, exemplos de jogos criados com Godot ou um pequeno tutorial prático ao fim do capítulo. Deseja incluir algum desses elementos?
You said:
Para o capítulo 2, gostaria de uma apresentação introdutória a linguagem de programação gdscript, falando sobre variáveis, funções e outras coisas básicas. Faça no máximo 4 tópicos
ChatGPT said:

Perfeito! Aqui está o Capítulo 2: Introdução ao GDScript, com uma abordagem direta e clara, ideal para quem está começando.
Capítulo 2: Introdução ao GDScript

A linguagem principal da Godot é o GDScript, uma linguagem de script própria, desenvolvida especialmente para facilitar o desenvolvimento de jogos dentro da engine. Inspirada em Python, ela é simples, legível e totalmente integrada ao fluxo de trabalho da Godot.

A seguir, você conhecerá os conceitos básicos para começar a programar seu primeiro jogo.

1. Variáveis: Armazenando Dados

Variáveis são como “caixinhas” onde você guarda informações que o jogo vai usar.

var nome = "Jogador"
var vida = 100
var velocidade = 200.0

Você pode declarar variáveis com ou sem um tipo específico:

var pontos: int = 0
var nome_jogo: String = "Aventura Pixelada"

2. Funções: Fazendo Seu Código Agir

Funções são blocos de código que executam ações. Na Godot, a função especial \_ready() é executada quando a cena está carregada.

func \_ready():
print("O jogo começou!")

Você também pode criar suas próprias funções:

func mostrar_pontuacao():
print("Pontuação atual:", pontos)

3. Condicionais e Laços: Controle do Fluxo

Com condicionais, você faz o código tomar decisões:

if vida <= 0:
print("Game Over")
elif vida < 50:
print("Cuidado! Vida baixa")
else:
print("Tudo certo")

E com laços, você repete ações:

for i in range(5):
print("Inimigo número", i)

4. Sinais e Interatividade

Um dos diferenciais da Godot é o sistema de sinais, que permite que objetos se comuniquem entre si.

Exemplo: detectar quando um botão é pressionado:

func \_on_Botao_pressed():
print("Botão pressionado!")

Você pode conectar sinais pela interface ou via código, facilitando a criação de interações e eventos no jogo.

Esses são os fundamentos essenciais para começar. A partir daqui, você já consegue criar interações, controlar personagens e montar sistemas básicos de jogo.

Quer que o próximo capítulo seja sobre movimentação de personagens ou criação da primeira cena?

gere uma conclusão com agradecimentos ao leitor por ler até o final
ChatGPT said:

Claro! Aqui está uma sugestão de conclusão com tom inspirador e agradecido para encerrar seu eBook:
Conclusão

Se você chegou até aqui, parabéns!

Esperamos que esta leitura tenha despertado em você o entusiasmo e a confiança para mergulhar de cabeça no universo do desenvolvimento de jogos indie com a Godot. Não importa se você está dando seus primeiros passos ou já tem alguma experiência: o mais importante é continuar criando, errando, aprendendo e evoluindo.

A Godot é uma ferramenta poderosa, mas o verdadeiro poder está nas suas mãos — na sua criatividade, na sua persistência e no seu desejo de transformar ideias em experiências interativas.
Obrigado por ler até o fim!

Este eBook foi feito com carinho para quem, assim como nós, acredita que fazer jogos é mais do que programar — é contar histórias, criar mundos e tocar pessoas.

Continue estudando, experimentando e publicando seus projetos. O mundo precisa da sua visão única.

Boas criações — e até o próximo jogo!

Se quiser, posso incluir essa conclusão no arquivo Markdown já gerado. Deseja que eu atualize o arquivo?

### link do pptx no Canva

> [Ebook](https://www.canva.com/design/DAGrgAWMvyI/4OXVQlnnfui8hL5s02EF-g/edit?utm_content=DAGrgAWMvyI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

### link do linkedin

> [Artigo](https://www.linkedin.com/in/breno-de-moraes/)
