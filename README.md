# jogo-pedra-papel-tesoura
import random
print('\033[1;32;40m--------------------\033[m')
print('\033[1;32;40mPedra Papel Tesoura\033[m')
print('\033[1;32;40m--------------------\033[m')
Pedra_Papel_Tesoura_jogador=int(input('Pronto para jogar!!! Escolhar um dos itens a seguir \n (1)Pedra (2)Papel (3)Tesoura: '))
Pedra_Papel_Tesoura = random.randint(1, 3)

print(f'    Maquina escolhe: \033[1;32m{Pedra_Papel_Tesoura}\033[m')

if Pedra_Papel_Tesoura==1 and Pedra_Papel_Tesoura_jogador ==1:
    print('Emater, bom jogor!!!')
elif Pedra_Papel_Tesoura==2 and Pedra_Papel_Tesoura_jogador ==2:
        print('Emater, bom jogor!!!')
elif Pedra_Papel_Tesoura==3 and Pedra_Papel_Tesoura_jogador ==3:
    print('Emater, bom jogor!!!')

elif Pedra_Papel_Tesoura==3 and  Pedra_Papel_Tesoura_jogador ==1:
    print('você ganhou: Pedra ganha da Tesoura')

elif Pedra_Papel_Tesoura==1 and  Pedra_Papel_Tesoura_jogador ==3:
    print('Game over: Pedra ganha da Tesoura')

elif Pedra_Papel_Tesoura==1 and  Pedra_Papel_Tesoura_jogador ==2:
    print('você ganhou: Papel ganha da Pedra')

elif Pedra_Papel_Tesoura==2 and  Pedra_Papel_Tesoura_jogador ==1:
    print('Game over: Papel ganha da Pedra')

elif Pedra_Papel_Tesoura==3 and  Pedra_Papel_Tesoura_jogador ==2:
        print('você ganhou: Tesoura ganha da Papel')

elif Pedra_Papel_Tesoura==2 and  Pedra_Papel_Tesoura_jogador ==3:
    print('Game over: Tesoura ganha da Papel') 
else:
    print('\033[1;31mTente novamente mas agora digite os números corretamente!!!\033[m')
