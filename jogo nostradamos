import time
import os 
import random

# Função para limpar a tela (sistemas operacionais)
def limpar_tela():
    sistema = os.name
    if sistema == 'nt':  # Windows
        os.system('cls')
    else:  # Linux ou Mac
        os.system('clear')

# Função para mostrar inventário
def mostrar_inventario():
    time.sleep(2)
    ver_inv = input("Deseja ver seu inventário agora? (s/n): ").strip().lower()
    if ver_inv == "s":
        print("\n📁 INVENTÁRIO:")
        if inventario:
            for item in inventario:
                print(f"- {item}")
        else:
            print("- (vazio)")
    else:
        print("\nVocê respira fundo e continua seu caminho...")

# Inventário (declarado no início para ser global)
inventario = []

# Limpar tela inicial
limpar_tela()

# Introdução do jogo
print(r"""·····································································
:                                                                   :
:   _   _           _                 _                             :
:  | \ | | ___  ___| |_ _ __ __ _  __| | __ _ _ __ ___  _   _ ___   :
:  |  \| |/ _ \/ __| __| '__/ _` |/ _` |/ _` | '_ ` _ \| | | / __|  :
:  | |\  | (_) \__ \ |_| | | (_| | (_| | (_| | | | | | | |_| \__ \  :
:  |_| \_|\___/|___/\__|_|  \__,_|\__,_|\__,_|_| |_| |_|\__,_|___/  :
:                                                                   :
·····································································""")

time.sleep(2)

# Lista de nomes que não podem ser usados (easter egg)
nomes_proibidos = ["Emma", "Pip", "Dante", "Jenna"]

# Solicita o nome e formata com a primeira letra de cada palavra em maiúscula
while True:
    nome = input("\nDigite o nome do seu personagem: ").strip().lower().title()
    if nome in nomes_proibidos:
        print(f"\nEsse nome... {nome}? É...meio familiar demais. Melhor tentar novamente.")
        time.sleep(1.5)
    else:
        break

# Loop de confirmação para iniciar
while True:
    iniciar = input(f"\nDeseja iniciar a história de {nome}? (sim/não): ").strip().lower()
    if iniciar == "sim":
        break
    elif iniciar == "não" or iniciar == "nao":
        print("Tudo bem. Talvez em outra noite mais corajosa... Até logo.")
        exit()
    else:
        print("Por favor, digite 'sim' ou 'não'.")

limpar_tela()

time.sleep(2)
print(f"Você é {nome}, um(a) estudante(a) padrão do ensino médio. \n")
time.sleep(2)
print("Junto de seus colegas — Emma, Pip, Jenna e Dante — você decidiu matar aula na sala de informática.")
time.sleep(2)
print("Entre risadas e conversas aleatórias," \
" entre idas e voltas pro banheiro ou só pra zoar nos corredores, o tempo passou... e passou demais.")
time.sleep(2)
print("Vocês percebem que a escola está completamente silenciosa. Nenhum som, nenhuma alma viva.")
print("Não há vozes nos corredores, nenhum barulho nas outras salas. Nem sinal de professores, inspetores ou alunos.\n")
time.sleep(5)

print("Emma: 'Já está meio escuro... que horas são?'")
print("Pip: 'Meu celular tá sem sinal aqui. E a internet também caiu.'")
print("Jenna: 'A gente devia sair daqui. Agora.'")
print("Dante: 'Finalmente alguém com bom senso.'\n")
time.sleep(4)

print("Vocês começam a caminhar pelos corredores da escola.")
print("Ao passar perto a porta do laboratório de ciências, uma luz acesa chama a atenção de vocês.")
time.sleep(3)
print("A porta está entreaberta.")
time.sleep(3)
print("Curiosos — e com um pouco de receio — vocês decidem entrar para ver o que está acontecendo.\n")
time.sleep(5)

print("Dentro do laboratório, o cheiro é estranho. Há uma sensação pesada no ar.")
print("E então vocês veem.")
time.sleep(4)
print("No chão, entre cadeiras caídas e vidros quebrados, está o corpo de Felipe — um aluno de um ano acima de vocês.")
print("Ele está morto. Claramente a facadas.\n")
time.sleep(4)

print("Jenna: 'Meu Deus... isso não é real. Isso não pode estar acontecendo.'")
print("Emma começa a tremer, as lágrimas escorrendo sem ela perceber.")
print("Emma: é o Felipe?? não não pode ser ")
print("Pip recua, batendo em uma mesa sem querer e colocando a mão em sua boca, sentindo um provável enjoô.")
print("Dante: 'Alguém tem que chamar ajuda. Agora.'\n")
time.sleep(6)

print("E então vocês veem a mensagem, escrita na parede com sangue fresco:")
print('"Ele não deveria ter descoberto."\n')
time.sleep(4)
print("O horror se instala.")
print("Algo aconteceu aqui.")
time.sleep(6)

print("Vocês vasculham a sala, mesmo sendo a pior situação, encontram um caderno em cima da mesa.")
print("Está manchado levemente de sangue. Parece ter sido deixado ali largado às pressas.\n")
time.sleep(5)

print("""
          
       ═════════════════════════════════════
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  _______________________________   ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║  ________________________________  ║
│ o │ ║                                    ║  
       ════════════════════════════════════
""")

# Escolha: ler ou não o diário
while True:
    ler_diario = input("Deseja ler o caderno? (s/n): ").strip().lower()
    if ler_diario in ["s", "n"]:
        break
    else:
        print("Digite 's' para sim ou 'n' para não.")

if ler_diario == "s":
    print("\nVocê o abre e começa a ler. É como um diário feito por Felipe.\n")
    time.sleep(2)
    print("Nas páginas, ele escreve sobre uma sensação constante de estar sendo observado por alguém.")
    print("Mas o que chama mais atenção: Ele fala da própria turma de vocês.")
    time.sleep(3)
    print('"Tem algo errado. Me sinto espiado, acompanhado por alguém, já falei com o diretor sobre a turma B."')
    print('"Eles foram liberados mais cedo hoje, então acho que estou seguro, mas o diretor não me leva a sério."')
    print('"Se algo acontecer comigo eu mesmo mato aquele velho."')
    print("'Mais tarde passar na biblioteca e pegar um livro sobre processos laboratoriais'")
    
    # Dar chance de guardar o diário
    while True:
        guardar = input("Deseja guardar o diário de Felipe na mochila? (s/n): ").strip().lower()
        if guardar == "s":
            inventario.append("Diário de Felipe")
            print("\nVocê guarda o diário. Pode ser importante mais tarde.")
            print(">>> Item adicionado ao inventário: Diário de Felipe <<<\n")
            break
        elif guardar == "n":
            print("\nVocê decide deixar o diário. Ele ficará para trás.")
            print(">>> O item foi perdido e não poderá ser recuperado. <<<\n")
            break
        else:
            print("Digite 's' para sim ou 'n' para não.")
    
else:
    colega = random.choice(["Emma", "Pip", "Jenna", "Dante"])
    print(f"\nEnquanto você hesita, {colega} pega o diário e começa a ler em voz baixa para o grupo.\n")
    time.sleep(3)
    print("Nas páginas, ele(s) leem sobre uma sensação constante de Felipe estar sendo observado por alguém.")
    print("Também falam da própria turma de vocês, e de que algo está errado.\n")
    time.sleep(3)
    print('"Tem algo errado. Me sinto espiado, acompanhado por alguém, já falei com o diretor sobre a turma B."')
    print('"Eles foram liberados mais cedo hoje, então acho que estou seguro, mas o diretor não me leva a sério."')
    print('"Se algo acontecer comigo eu mesmo mato aquele velho."')
    print('"Mais tarde, passar na biblioteca para pegar o livro dos processos do laboratório."\n')
    time.sleep(2)

    print(f"{colega} devolve o diário para você.")
    print("Você segura o diário em mãos por alguns segundos.")
    print("Se decidir não guardá-lo agora, ele será perdido para sempre.")

    while True:
        guardar_diario = input("Deseja guardar o diário de Felipe na mochila? (s/n): ").strip().lower()
        if guardar_diario == "s":
            inventario.append("Diário de Felipe")
            print("\nVocê guarda o diário. Pode ser importante mais tarde.")
            print(">>> Item adicionado ao inventário: Diário de Felipe <<<\n")
            break
        elif guardar_diario == "n":
            print("\nVocê decide deixar o diário. Ele ficará para trás.")
            print(">>> O item foi perdido e não poderá ser recuperado. <<<\n")
            break
        else:
            print("Digite 's' para sim ou 'n' para não.")

# Mostrar inventário no final da cena
mostrar_inventario()

time.sleep(2)

print("Os outros começam a discutir.")
print("Emma: 'Espera... s-se ele morreu hoje e o sangue ainda tá fresco. Isso aconteceu há pouco tempo. - diz isso trêmula'")
print("Pip: 'A gente não ficou o tempo todo junto na sala de informática...'")
print("Dante: 'Você tá dizendo que um de nós pode ter feito isso?'")
print("Jenna: 'Era só a nossa turma que foi liberada mais cedo hoje...'\n")
time.sleep(4)

print("O silêncio que se segue é pesado.")
print("Todos se encaram. A dúvida se instala.")
print("Será que o assassino está entre vocês?\n")
time.sleep(3)

time.sleep(2)
print("\nEmma: 'Não foi nenhum de nós! Eu fiquei na sala o tempo todo'")
time.sleep(2)
print("Pip: 'Eu também estava lá, mas não vi ninguém estranho, só sei que ninguém saiu com o Felipe'")
time.sleep(2)
print("Jenna: 'Vocês dois estão mentindo! Eu vi o Dante saindo da sala, ele não pode negar.'")
time.sleep(2)
print("Dante: 'Sério, Jenna? E você? Onde você estava? Não ficou o tempo todo na sala também!'")
time.sleep(2)

print("\nA discussão esquenta, e eles começam a se acusar nervosamente.\n")
time.sleep(2)

print(f"{nome}: 'Parem! Isso não vai resolver nada. Se continuarmos assim, não vamos descobrir quem fez isso.'")
time.sleep(2)
print(f"{nome}: 'Temos que pensar no que o Felipe escreveu no diário dele. Ele disse algo sobre a biblioteca...'")
time.sleep(5)

    # Agora o personagem reclamando, sem função
personagens = [ "Pip", "Emma", "Jenna"]
reclamante = random.choice(personagens)
print(f"\n{reclamante}: 'Gente, a gente achou UM CORPO. E vocês querem ir pra biblioteca? A gente devia correr pra secretaria! ou SIMPLESMENTE SAIR DA ESCOLA??'")
time.sleep(2)
print("Dante: 'Você é muito certinha, ninguém vai acreditar e vão colocar a culpa na gente, não podemos fugir, e nem sabemos se tem alguém lá na secretaria, cabeção'")
print(f"Jenna: 'Mas talvez, faça mais sentido, pelo amor de Deus, a gente não é Scooby Doo para investigar essa droga... {nome}, o que você acha?'")
print(f"{nome}: melhor seguir para a biblioteca, mesmo vocês não querendo investigar, a secretaria deve estar vazia, afinal")
print(f"Jenna: PERFEITO, mas se algum problema acontecer eu vou te culpar para sempre, {nome}, eu juro!!\n")
time.sleep(6)

print("\nVocês se dirigem até a biblioteca em silêncio, o cheiro de papel antigo e poeira se misturando à tensão no ar.")
time.sleep(3)
print("Dante examina as estantes, os olhos atentos a qualquer coisa fora do lugar.")
time.sleep(3)
print("Emma encontra uma gaveta trancada.\n Emma: Essa gaveta está trancada, talvez tenha uma arma qualquer coisa — comenta com um tom preocupado.")
time.sleep(3)
print("Dante: Acho que eu consigo forçar isso aqui calma — Ele pega na mesa um clipe e uma reguá de metal.\n")
print("Pip: Ai, meu Deus... Só espero que isso realmente valha a pena.")
time.sleep(3)
print("Emma: Vamos com calma, gente. Se tem algo importante aí, pode mudar tudo.")
print("Com um clique suave, a gaveta cede, revelando uma carta amassada e com as bordas desgastadas pelo tempo,\nendereçada ao diretor e assinada por Felipe.")

print("""
        
    ╔════════════════════════════════════╗
    ║   Para Diretor:Paulo A. Campos     ║
    ║                                    ║
    ║    #######################         ║
    ║  ########  ## # #################  ║
    ║                                    ║
    ║             ass: felipe montes     ║
    ╚════════════════════════════════════╝

        
        """)


print("\nCARTA DE FELIPE AO DIRETOR:\n"
          "'Eu não aguento mais isso, Diretor. A perseguição é insuportável.\n"
          "Ninguém faz nada, nem os professores, e toda vez que tento falar, dizem que é coisa da minha cabeça, mas tenho certeza que é alguém da turma B.\n"
          "Se algo acontecer comigo, a culpa vai ser inteiramente sua. Eu pedi ajuda. Ass: Felipe Montes'")
time.sleep(2)
print("\nAnexo à carta, um bilhete do diretor:"
          "'Desculpe, Felipe. Sem provas, não posso agir, você está por sua conta.\n"
          "Mas você sempre pode ir até a guarita do segurança, você sabe, fica ao lado da secretaria.' Ass: Paulo A. Campos \n")
time.sleep(2)

print("O silêncio cai sobre o grupo, pesado, como se as palavras de Felipe tivessem criado uma sombra na sala.")
time.sleep(3)
print("Jenna sussurra, com a voz trêmula:")
time.sleep(2)
print("— Isso é sério... ele estava mesmo com medo. E sozinho.")
time.sleep(2)

print("Dante franze o cenho, olhando para o grupo:")
time.sleep(2)
print("— E o pior, ninguém fez nada. Como o diretor disse, sem provas, estão todos de braços cruzados.\n")
time.sleep(4)

print("Emma observa um bilhete anexado à carta, triste e parecendo com raiva desse diretor")
time.sleep(2)
print("Ela entrega as cartas para você")
print("Você segura as cartas nas mãos.")
print("Se decidir não guardá-lo agora, ele será perdido para sempre.")

while True:
        carta = input("Deseja guardar as cartas do Felipe na mochila? (s/n): ").strip().lower()
        if carta == "s":
            inventario.append("Carta ao diretor")
            print("\nVocê guarda. Pode ser importante.")
            print(">>> Item adicionado ao inventário: Carta ao diretor <<<\n")
            break
        elif guardar_diario == "n":
            print("\nVocê decide deixar as cartas. Ficaram nas gaveta esquecidos.")
            print(">>> O item foi perdido e não poderá ser recuperado. <<<\n")
            time.sleep(2)
            break
        else:
            print("Digite 's' para sim ou 'n' para não.")


print("Pip cruza os braços, olhando para os outros com insistência:")
time.sleep(2)
print("— Esperem, não acho que devemos ir direto para a guarita. E se alguém lá na secretaria souber de mais alguma coisa? Precisamos tentar falar com eles primeiro.")
time.sleep(3)

print("Dante revira os olhos, impaciente:")
time.sleep(2)
print("— A secretaria provavelmente não vai ajudar, Pip. Se queremos respostas, a guarita é o lugar. É onde o segurança está de plantão e talvez tenha visto algo.")
time.sleep(3)

print("Jenna concorda, olhando para Pip com um sorriso encorajador:")
time.sleep(2)
print("— Ele tem razão. Se a gente enrolar muito, podemos perder tempo. O que o Felipe pediu já está claro: ele tentou falar com o diretor e não deu em nada.")
time.sleep(3)
print(f"Pip: o que você acha {nome}?? você sempre realmente foi o mais sensato")


while True:
    escolha = input("Escolha seu próximo destino: 'secretaria' ou 'guarita': ").strip().lower()
    
    if escolha == "secretaria":
        print("\nVocês seguem até a secretaria. A porta range ao ser aberta, mas o lugar está completamente vazio.")
        time.sleep(2)
        print("Sobre o balcão, apenas um panfleto plastificado: um mapa da escola.")
        time.sleep(2)
        print("\n--- MAPA ESCOLAR ---")
        print("BEM-VINDO, NOVO ALUNO, À NOSTRADAMUS - Uma das melhores escolas da região!\n")
        print("[Mapa com as salas decoradas: Biblioteca, Laboratórios, Guarita, Secretaria, banheiros do primeiro andar, refeitório junto a despensa e informática.]\n")
        time.sleep(2)
        print("Jenna suspira, cruzando os braços: \"Então é isso? Vazio? Que ideia genial foi essa de vir pra secretaria...\"")
        time.sleep(2)
        print("Dante revira os olhos: \"Não adiantou nada, né? Só perdemos tempo. Melhor irmos para a guarita antes que fiquemos parados aqui.\"")
        time.sleep(2)
        print(f"{nome}: \"Concordo. Vamos logo para a guarita.\"")
        time.sleep(2)
        print("\nVocês se dirigem até a guarita, o clima ficando cada vez mais tenso.")
        time.sleep(2)
        break  # sai do loop para ir à guarita

    elif escolha == "guarita":
        print("\nVocês decidem ir direto para a guarita. Não há mais volta.")
        time.sleep(2)
        print("O clima fica pesado à medida que se aproximam da guarita.")
        time.sleep(2)
        break  # sai do loop para ir à guarita

    else:
        print("Escolha inválida. Por favor, digite 'secretaria' ou 'guarita'.\n")

# Evento da GUARITA
print("\nA guarita está com a porta entreaberta. Um cheiro metálico e forte se espalha assim que vocês se aproximam.")
time.sleep(4)
print("Dante segura a respiração e empurra a porta com cuidado.")
time.sleep(4)
print("Emma grita baixinho ao ver a cena lá dentro.")
time.sleep(3)
print("O corpo do segurança está caído ao lado da cadeira, uma poça de sangue escuro se espalhando sob ele.")
time.sleep(3)
print("Pip leva a mão à boca, cambaleando para trás. \"Aaaah, merda, merda... eu vou vomitar...\"")
time.sleep(2)
print("Jenna segura o ombro dela, tentando acalmá-la. \"Não olha, Pip. Olha pra mim. Respira, respira.\"")
time.sleep(2.5)
print(f"{nome}: \"Isso... isso é real. Ele está morto. Alguém matou ele que nem fizeram com o Felipe.\"\n")
time.sleep(3)
print("Emma fecha os olhos por um segundo. \"Dois corpos. Dois. Isso está virando um pesadelo.\"\n")
time.sleep(3)
print("Dante se aproxima dos monitores das câmeras, alguns estão quebrados ou congelados.")
time.sleep(3)
print("Dante: \"Merda. As câmeras dos corredores estão completamente ferradas... mas o resto ainda parece funcionar.\"\n")
time.sleep(2.5)
print("Emma: \"Procura por algo de hoje. Talvez horas atrás, antes da gente chegar.\"\n")
time.sleep(2.5)
print("Eles avançam a gravação das câmeras e de repente Jenna aponta: \"Ali! Tem alguém!\"")
time.sleep(6)

# Parte nova da cena nas câmeras
print("\nA gravação está instável, cheia de ruído, mas uma figura escura surge.")
time.sleep(3.5)
print("É apenas um borrão, uma sombra... mas se move rápido.")
time.sleep(4)
print("A câmera chia e distorce, mas dá para ver a silhueta seguindo pelo corredor que leva ao refeitório.")
time.sleep(4)
print("No chão... uma trilha de sangue fresco se arrasta naquele mesmo caminho.")
time.sleep(4.5)

print("\nEmma: \"Tem alguém lá. Isso não é um ladrão. Não é uma brincadeira.\"")
time.sleep(3)
print("Jenna: \"Aquilo era muito rápido...\"")
time.sleep(2.5)
print("Pip, ainda meio trêmula: \"Por que sempre é o refeitório? Eu disse que comida de escola era do mal.\"")
time.sleep(2)
print("Dante: \"Piada ruim, Pip.\"")
time.sleep(2)
print("Pip: \"Tô tentando não enlouquecer, idiota, ok?\"")
time.sleep(4)

print(f"{nome}: \"A gente precisa ir até lá. Descobrir o que está acontecendo.\"")
time.sleep(3)
print("Emma balança a cabeça, hesitante. \"E se... e se aquilo ainda estiver lá? E se for perigoso?\"")
time.sleep(3.5)
print("Dante fecha os punhos. \"Já tem dois mortos. Esperar não vai salvar ninguém.\"")
time.sleep(3)
print("Jenna: \"Mas a gente não pode ir feito idiota. Vamos juntos. Devagar. Cuidando dos cantos.\"\n")
time.sleep(3)

print("Todos se entreolham, em silêncio.")
time.sleep(2)
print("A decisão foi tomada.")
time.sleep(2.5)
print("Eles saem da guarita, seguindo a trilha de sangue... rumo ao refeitório.\n")
time.sleep(5)



print("\nVocês seguem a trilha de sangue, entrando devagar pelo corredor que leva ao refeitório.")
time.sleep(3)
print("\nO refeitório está estranho. As mesas enormes e vazias, as cadeiras alinhadas perfeitamente, como se ninguém tivesse estado ali por dias.")
time.sleep(4)

print("A porta da despensa está entreaberta, com uma luz fraca escapando por entre a fresta.")
time.sleep(3)
print(f"{nome} se aproxima devagar, seguindo a trilha que leva até a porta da despensa.\n")
time.sleep(3)

print("\nAo entrarem, encontram prateleiras cheias de comidas enlatadas e caixas empilhadas — tudo aparentemente normal.")
time.sleep(4)

print("Mas no chão, um conjunto de facas está espalhado sobre a mesa, algumas em seus lugares, exceto uma .")
time.sleep(4)

print("A trilha de sangue parece terminar por ali dentro da despensa")
time.sleep(3)

print(f"\n{nome}: \"Tem uma faca faltando... Alguém deve ter pegado.\"")
time.sleep(3)

print("Emma: \"Será que é melhor a gente pegar uma faca? Pode ser útil se o que estiver por aqui aparecer de novo.\"")
time.sleep(3)

print("Dante, franzindo a testa: \"Armas não são brinquedo. Se alguém se desesperar ou for surpreendido, pode acabar ferindo um de nós. Isso não me parece seguro.\"")
time.sleep(4)

print("Pip, nervosa: \"E ficar sem nada pra se proteger parece mais seguro? Já viu a trilha de sangue? e eu não vou ser pega de surpresa.\"")
time.sleep(4)

print("Emma: \"A faca pode ser a diferença entre sobreviver ou não. Não tô dizendo que devemos sair por aí atacando,\n mas... é melhor ter e não precisar do que precisar e não ter.\"")
time.sleep(4)

print("Dante cruza os braços, sério: \"Mas e se alguém encontrar a gente armado? Podem achar que somos uma ameaça. Ou pior, alguém pode usar isso como desculpa pra atacar.\"")
time.sleep(4)

print("Pip: \"Se for entre mim e esse 'alguém', prefiro estar preparada. Já vi coisa demais pra confiar que vai ficar tudo bem só porque estamos de mãos vazias.\"")
time.sleep(4)


    # Escolha do jogador
escolha_faca = input("\nQuer pegar uma faca? (sim/não): ").strip().lower()

if escolha_faca == "sim":
    inventario.append("Faca")  # Adiciona a faca ao inventário
    print(f"\n{nome} cuidadosamente pega uma faca da mesa, sentindo o frio do metal na mão.")
    time.sleep(3)
    print("Dante: \"Se der ruim, eu fui contra isso a vida toda.\"")
    time.sleep(3)
    print("Pip: \"Segurança em primeiro lugar, Dante, querido.\"")
    time.sleep(3)
    print("Emma: \"Só não vamos fazer besteira. Essa coisa pode ser mais rápida do que a gente imagina.\"")
    time.sleep(3)

    # ASCII art da faca
    print(r"""                                        ___
                                                        |_  |
                                                            | |
    __                      ____                            | |
    \ ````''''----....____.'\   ````''''--------------------| |--.               _____      .-.
    :.                      `-._                           | |   `''-----''''```     ``''|`: :|
    '::.                       `'--.._____________________| |                           | : :|
        '::..       ----....._______________________________| |                           | : :|
        `'-::...__________________________________________| |   .-''-..-'`-..-'`-..-''-.  : :|
            ```'''---------------------------------------| |--'                         `'-'
                                                            | |
                                                        _| |
                                                        |___|
    """)

else:
    print(f"\n{nome} decide não pegar a faca, tentando não se deixar levar pelo medo.")
    time.sleep(3)
    print("Emma: \"Acho que era melhor levar, mas não quero carregar isso para cima de mim.\"")
    time.sleep(3)
    print("Dante: \"Precisar, a gente corre, vai dar tudo certo.\"")
    time.sleep(3)
    print("Pip: \"Eu ainda acho que a faca seria útil, mas te respeito.\"")
    time.sleep(3)

# Desaparecimento da Jenna — ocorre em ambos os casos
print("\nDe repente, enquanto conversam, percebem algo.")
time.sleep(5)
print("\nUm de vocês está faltando, não?")
print("E você finalmente repara...")
time.sleep(5)
print(f"{nome}: \"Espere... onde a Jenna foi?\"")
time.sleep(2.5)
print("Emma: \"Ela estava aqui há um momento atrás, mas que...\"")
time.sleep(3)
print("Pip começa a olhar em volta, nervosa, chamando por Jenna enquanto o clima no ambiente fica tenso.")
time.sleep(4)
print(f"{nome} sente um frio na espinha enquanto olha para a porta da despensa semiaberta, imaginando onde Jenna poderia estar...")

print("\nEmma: \"A gente não pode simplesmente deixar ela aqui! Ela pode estar machucada.\"")
time.sleep(3)
print("Pip: \"Mas e se for uma armadilha? E se for aquela coisa de novo?\"")
time.sleep(3)
print("Dante: \"A gente tem que decidir agora. Procurar ou fugir.\"")
time.sleep(3)
print("\nVocê sente a tensão aumentar. Cada escolha agora pode ser a última.")
time.sleep(3)


escolha_final = input("\nO que vocês vão fazer?\n1 - Fugir\n2 - Procurar Jenna\nDigite 1 ou 2: ").strip()

if escolha_final == "1":
    print("\nVocês decidem não arriscar. Jenna sumiu, e o medo fala mais alto.")
    time.sleep(3)
    print("Dante força a porta da escola, tentando abri-la enquanto Pip fica de olho nos corredores.")
    time.sleep(3)
    print("Um barulho ecoa ao longe. Algo se arrastando. Algo... grande e vem atrás de vocês")
    time.sleep(3)

    if "Faca" in inventario:
        usar_faca = input("Você quer usar a faca para cortar o fio que bloqueia a porta? (s/n): ").strip().lower()
        if usar_faca == 's':
            print("Você tenta usar a faca para cortar um fio elétrico que bloqueia a porta...")
            time.sleep(3)
            print("Mas algo dá errado. Muito errado.")
            time.sleep(3)
            print("\nVocê sente a corrente elétrica percorrer seu corpo em um segundo eterno.")
            time.sleep(3)
            print("\nGAME OVER")
            print(r"""
                  
                                            ╔══════════════════════════════════════════════════╗
                                            ║                                                  ║
                                            ║                                                  ║
                                            ║     Você achou que cortar um fio elétrico        ║
                                            ║     com uma faca de metal era uma boa ideia.     ║
                                            ║                                                  ║
                                            ║        A resposta veio em forma de choque.       ║
                                            ║      Seu corpo caiu duro, o cheiro de queimado.  ║
                                            ║                                                  ║
                                            ║        "Parabéns. Você morreu como viveu:        ║
                                            ║                    Sem pensar."                  ║
                                            ║                                                  ║
                                            ╚══════════════════════════════════════════════════╝
                  
            """)
        else:
            print("Você decide não usar a faca e tenta passar por cima do fio mesmo assim...")
            time.sleep(3)
            print("Você se machuca ao tropeçar e cair mal...")
            time.sleep(3)
            print("Seu joelho está sangrando. Você mancando e com dor, mas consegue sair pela porta aberta.")
            time.sleep(3)
            print("\nVocê está livre. Mas... a que custo?")
            print("O que aconteceu com a Jenna, com o felipe??")
            print("\nFINAL NEUTRO")
            time.sleep(3)
            print(r"""
                  
                                            ╔══════════════════════════════════════════════════╗
                                            ║                                                  ║
                                            ║                                                  ║
                                            ║      Vocês escaparam... mas algo ficou para      ║
                                            ║         trás. Cicatrizes. Jenna e Felipe.        ║
                                            ║          A lembrança daquela noite vive.         ║
                                            ║                                                  ║
                                            ║         "A liberdade tem um gosto estranho.      ║
                                            ║         Quase tão amargo quanto o medo."         ║
                                            ║                                                  ║
                                            ╚══════════════════════════════════════════════════╝
                                            
                  """)
    

elif escolha_final == "2":
    print("\nDepois de uma longa discussão, decidem procurar Jenna e vão correndo pelos corredores e decidem ir ao pátio.")
    time.sleep(3)
    print("O grupo vai para o pátio. O silêncio é perturbador.")
    time.sleep(3)
    print("\nNo centro, sob a luz fraca, Jenna está lá. Em pé. Parada sobre a luz da noite.\n Faz muito tempo que vocês estão presos aqui\n")
    time.sleep(3)
    print("Ela veste as roupas do assassino. Em sua mão, uma faca reluz ao luar.")
    time.sleep(4)

    # Diálogo tenso de Jenna explicando sua história
    print("\nJenna fala calmamente, com um tom que mistura tristeza e raiva:")
    time.sleep(4)
    print("\"Meu pai... era um homem cruel. Não o homem que vocês achavam que conheciam.\"")
    time.sleep(4)
    print("\"Ele passou a vida destruindo tudo ao seu redor. Felipe... ele nunca me perdoou, nunca me deu uma chance.\"")
    time.sleep(5)
    print("\"Ele dizia que eu era um erro, que eu deveria desaparecer. E eu... eu cansei.\"")
    print("'fui eu que acabei com o Felipe. Dei fim ao meu sofrimento e ele pagou pelo seu ego'")
    time.sleep(5)

    print("\nEmma explode em raiva:")
    time.sleep(3)
    print("\"VOCÊ MATOU O FELIPE?! EU AMAVA O FELIPE, SUA...\"")
    time.sleep(5)
    print("Emma olha para todos, cheia de fúria, tentando convencer vocês a não apoiarem Jenna.\n")
    
    print("Emma avança até vocês, os olhos ardendo em fúria.")
    time.sleep(4)
    print("— VOCÊS VÃO MESMO FICAR DO LADO DELA?! — ela grita, a voz rasgando o ar.")
    time.sleep(5)
    print("— Ela mentiu! Manipulou! Fez vocês duvidarem de tudo! Ela colocou TODO MUNDO em perigo, e agora tá aí, com essa cara de 'coitadinha'!\n")
    time.sleep(6)
    
    print("Emma se vira para Pip, depois para Dante, depois para você. Os olhos imploram, suplicam, queimam.")
    time.sleep(6)
    print("— Eu... eu confiei nela. Eu achei que éramos um time. A Jenna não é quem vocês lembram... Ela escolheu mentir.")
    time.sleep(6)
    print("— E se fosse com vocês? Se fosse VOCÊ quem tivesse perdido alguém por causa dela? — ela sussurra com raiva, lágrimas contidas.\n")

    time.sleep(5)
    print("Jenna continua em silêncio. O rosto dela está pálido, os olhos perdidos.")
    time.sleep(4)
    print("Sua expressão é um mosaico distorcido: tristeza por ter sido exposta, alívio por não precisar mais carregar tudo sozinha,")
    time.sleep(5)
    print("e uma culpa latejante por ter afastado as únicas pessoas que um dia se importaram com ela.")
    time.sleep(7)
    

    print("Jenna dá um passo hesitante à frente. A voz dela sai baixa, embargada.")
    time.sleep(5)
    print("— Você acha que eu não sei o que fiz? — ela murmura. — A cada noite, a culpa me come viva.")
    time.sleep(5)
    print("Ela encara Emma com olhos marejados, a mandíbula trêmula.")
    time.sleep(4)
    print("— Eu menti. Eu afastei vocês. Eu me escondi... porque era mais fácil do que admitir o que eu era. O que eu fiz.")
    time.sleep(6)

    print("Você, Pip e Dante trocam olhares. Jenna era sua amiga desde sempre, e ouvir sua história mexe com vocês.")
    time.sleep(5)

    # Escolha: apoiar Emma ou apoiar Jenna
    apoio = input("\nVocê fica ao lado de quem?\n1 - Emma\n2 - Jenna\nDigite 1 ou 2: ").strip()

if apoio == "1":
    print("\nVocê se posiciona ao lado de Emma. A tensão explode em violência.")
    time.sleep(4)
    print("Emma avança contra Jenna, gritando por justiça, vingança, e tudo que foi tirado dela.")
    time.sleep(4)
    print("Jenna recua, os olhos arregalados, mas sua mão já busca algo no casaco.")
    time.sleep(4)

    if "Faca" in inventario:
        usar_faca = input("\nVocê quer sacar a faca para ajudar Emma? (s/n): ").strip().lower()
        if usar_faca == 's':
            print("Você saca a faca. O frio do metal contrasta com o calor da tensão no ar.")
            time.sleep(3)
            print("O confronto começa como um trovão — gritos, golpes, sangue.")
            time.sleep(4)
            print("Jenna luta como um animal encurralado. Emma grita de dor quando leva um corte no ombro.")
            time.sleep(4)
            print("Você consegue ferir Jenna, mas ela gira o corpo e finca algo no peito de Pip.")
            time.sleep(5)
            print("Pip solta um grunhido sufocado e cai, os olhos fixos em você, vazios.")
            time.sleep(5)
            print("Dante ruge de raiva e se lança sobre Jenna, mas ela o derruba com brutalidade.")
            time.sleep(4)
            print("Emma aproveita a abertura e, com um grito primal, acerta Jenna com força.")
            time.sleep(4)
            print("Jenna cai, arfando, os olhos perdendo o brilho.")
            time.sleep(3)
            print("\nO silêncio que vem depois é pior que a batalha.")
            time.sleep(4)
            print("Pip jaz imóvel. Dante respira com dificuldade. Emma cai de joelhos, tremendo.")
            time.sleep(5)
            print("Você escuta sirenes ao longe. A polícia chega logo depois.")
            time.sleep(4)
            print("Vocês contam que Jenna surtou. Que foi legítima defesa.")
            time.sleep(4)
            print("\nEles acreditam. Mas ninguém pode apagar o que aconteceu.")
            time.sleep(3)
            print("\nFINAL AMARGO - ESCAPARAM, MAS PERDERAM MUITO")
            
            print(r"""
                                                    ╔══════════════════════════════════════════════════╗
                                                    ║                                                  ║
                                                    ║                                                  ║
                                                    ║     Jenna caiu. Mas o preço foi alto demais.     ║
                                                    ║   Pip... Dante... nada trará os dois de volta.   ║
                                                    ║   Emma respira com dificuldade, vitoriosa...     ║
                                                    ║        mas ninguém saiu inteiro disso.           ║
                                                    ║                                                  ║
                                                    ║     "Sobrevivemos. Mas parte de nós ficou lá."   ║
                                                    ║                                                  ║
                                                    ╚══════════════════════════════════════════════════╝
            """)


        else:
            print("Você decide não sacar a faca. Sua hesitação custa caro.")
            time.sleep(3)
            print("Jenna se move como um raio, derrubando Pip com um golpe certeiro.")
            time.sleep(4)
            print("Dante tenta reagir, mas ela o atinge brutalmente na cabeça.")
            time.sleep(4)
            print("Emma grita e avança, mas Jenna está impiedosa. Um último golpe. Silêncio.")
            time.sleep(4)
            print("Você assiste tudo congelado, até sentir a dor rasgar seu próprio corpo.\n Você vê, Jenna com um sorriso triste na sua direção e a vê enfiar a faca em seu próprio peito.")
            time.sleep(3)
            print("\nTudo escurece lentamente...")
            time.sleep(3)
            print("\nGAME OVER - FINAL TRÁGICO")
            
            print(r"""
                                                ╔══════════════════════════════════════════════════╗
                                                ║                                                  ║
                                                ║                                                  ║
                                                ║   O sangue cobre o chão. O silêncio domina.      ║
                                                ║     Emma... Pip... Dante... você... Jenna.       ║
                                                ║        Todos caíram. Nenhum ficou de pé.         ║
                                                ║                                                  ║
                                                ║  Ninguém saberá o que aconteceu aqui de verdade. ║
                                                ║  Só o vento sussurrará os nomes de vocês à noite.║
                                                ║                                                  ║
                                                ║        "O fim não escolheu lados. Só levou."     ║
                                                ║                                                  ║
                                                ╚══════════════════════════════════════════════════╝
            """)


    else:
        print("\nVocê está desarmado e não consegue ajudar efetivamente.")
        time.sleep(3)
        print("Jenna domina a situação com uma frieza assustadora e rápida.")
        time.sleep(3)
        print("Pip e Dante são feridos um após o outro. Emma cai por último, gritando seu nome.")
        time.sleep(4)
        print("\nVocê sente o impacto de algo... e vê a Jenna enfiando a faca em seu próprio peito e então o mundo fica escuro.")
        time.sleep(3)
        print("\nGAME OVER - FINAL TRÁGICO")
        print(r"""
                                                ╔══════════════════════════════════════════════════╗
                                                ║                                                  ║
                                                ║                                                  ║
                                                ║   O sangue cobre o chão. O silêncio domina.      ║
                                                ║     Emma... Pip... Dante... você... Jenna.       ║
                                                ║        Todos caíram. Nenhum ficou de pé.         ║
                                                ║                                                  ║
                                                ║  Ninguém saberá o que aconteceu aqui de verdade. ║
                                                ║  Só o vento sussurrará os nomes de vocês à noite.║
                                                ║                                                  ║
                                                ║        "O fim não escolheu lados. Só levou."     ║
                                                ║                                                  ║
                                                ╚══════════════════════════════════════════════════╝
            """)


elif apoio == "2":
        print("Dante respira fundo. O olhar fixo em Jenna, mas suave.")
        time.sleep(4)
        print("-Eu te conheço desde a terceira série, Jenna. Você me salvou de um grupo de valentões com uma pedra e um grito.")
        time.sleep(6)
        print("-Eu não esqueci. E eu sei que você carrega coisas que a gente nem imagina\n")
        time.sleep(5)

        print("Pip, ainda olhando o chão, finalmente fala:")
        time.sleep(4)
        print("— Você foi minha primeira amiga. Quando ninguém queria falar comigo, você sentou do meu lado e... só ficou.")
        time.sleep(6)
        print("Ela olha para Emma, depois para Jenna.")
        time.sleep(3)
        print("Você sente o peso da decisão esmagando o peito.")
        time.sleep(3)
        print("O silêncio que se instala é denso como fumaça.")
        time.sleep(4)
        print("\nVocê decide apoiar Jenna. O grupo se une a ela, como uma só força contra Emma.")
        time.sleep(4)
        print("Emma se sente traída, e a luta começa.")
        time.sleep(4)


        if "Faca" in inventario:
            usar_faca = input("\nVocê quer usar a faca para lutar junto com Jenna? (s/n): ").strip().lower()
            if usar_faca == 's':
                print("\nCom a faca firme na mão, seu coração dispara. O ar ao redor fica pesado, sufocante.")
                time.sleep(3)
                print("Emma avança, olhos brilhando de ódio, sua respiração pesada ecoa como um aviso de tempestade.")
                time.sleep(4)
                print("Vocês se lançam no ataque, cada golpe é uma luta pela sobrevivência, sangue lateja, a dor pulsa.")
                time.sleep(5)
                print("\nEmma tenta resistir com toda força, mas aos poucos sua fúria se esvai — ela cai, derrotada, caindo no silêncio.")
                time.sleep(5)
                print("\nOfegantes, machucados, vocês se encaram — cúmplices naquele instante sombrio e irreversível.")
                time.sleep(4)
                print("Sabem que a polícia nunca vai ouvir sua versão, que a verdade aqui não tem espaço.")
                time.sleep(4)
                print("\nCom vozes baixas e firmes, combinam uma mentira mortal: Emma perdeu o controle, foi em legítima defesa.")
                time.sleep(5)
                print("\nEnquanto saem juntos da escola, Jenna segura as mãos de seus amigos — uma promessa silenciosa e um laço que não será quebrado.")
                time.sleep(4)
                print("\nVOCÊS ESCAPARAM.")
                print("\nFINAL SOMBRIAMENTE FELIZ - UNIDOS PElA ESCURIDÃO")

                print (r"""
                                                ╔══════════════════════════════════════════════════╗
                                                ║               UNIDOS PElA ESCURIDÃO              ║
                                                ║                                                  ║
                                                ║     Emma caiu. A verdade foi enterrada com ela.  ║
                                                ║        Vocês saem da escola, mãos unidas,        ║
                                                ║       cúmplices de algo que ninguém entenderia.  ║
                                                ║                                                  ║
                                                ║      "Na escuridão, encontramos abrigo.          ║
                                                ║       E juntos... escolhemos mentir."            ║
                                                ║                                                  ║
                                                ╚══════════════════════════════════════════════════╝

""")


            else:
                print("Você decide não usar a faca, e a luta é desesperada e sangrenta.")
                time.sleep(3)
                print("Emma ataca com força, e o grupo sofre baixas graves.")
                time.sleep(4)
                print("\nMas no fim os quatro sempre vencem, vocês veem Emma cair e a escola ficar silenciosa.")
                time.sleep(3)
                print("\n FINAL TRÁGICO")
                
        else:
            print("\nSem a faca, a luta é uma guerra desigual, desesperada e cruel.")
            time.sleep(3)
            print("Emma avança feroz, cada golpe seu parece rasgar não só a carne, mas a esperança.")
            time.sleep(3)
            print("O grupo cai aos poucos, entre gritos abafados e dor insuportável.")
            time.sleep(2)
            print("Pip não resistiu — seu corpo permanece imóvel, um silêncio doloroso entre a violência.")
            time.sleep(4)
            print(f"\nNo fim, exaustos e sangrando, Dante, {nome} e Jenna veem Emma desabar, a escola envolta em um silêncio mortal.")
            time.sleep(4)
            print(r"""
                                                    ╔══════════════════════════════════════════════════╗
                                                    ║                                                  ║
                                                    ║                                                  ║
                                                    ║   A dor e a perda marcam para sempre este dia.   ║
                                                    ║                                                  ║
                                                    ║     O silêncio da escola ecoa mais alto que      ║ 
                                                    ║              qualquer grito de luta.             ║
                                                    ║                                                  ║
                                                    ║      Pip se foi... E a esperança também.         ║
                                                    ║                                                  ║
                                                    ╚══════════════════════════════════════════════════╝
                  """)
 

else:
        print("\nEscolha inválida. O jogo termina aqui.")
