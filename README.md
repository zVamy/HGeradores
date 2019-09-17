settings:
    Sem-Espaço: '&6&lMINA PARTICULAR &7-> &eVocê está sem espaço para colocar uma mina'
    Sem-Permissão: '&6&lMINA PARTICULAR &7-> &eVocê não tem permissões suficientes.'
    Mina-Não-Encontrada: '&6&lMINA PARTICULAR &7-> &eEsta mina não foi encontrada.'
    Jogador-Offline: '&6&lMINA PARTICULAR &7-> &eO dono da mina, não está online.'
    Não-Quebrar-Minas-De-Outros: '&6&lMINA PARTICULAR &7-> &eVocê deve estar em uma mina sua.'
    Mina-Resetar: '&6&lMINA PARTICULAR &7-> &eSua mina foi resetada.'
    SemAcessoParaRetirar: '&6&lMINA PARTICULAR &7-> &eVocê não tem acesso a esta mina.'
    SemAcessoParaColocar: '&6&lMINA PARTICULAR &7-> &eVocê não tem acesso a isto..'
    ResetarMinaOutro: '&6&lMINA PARTICULAR &7-> &eA mina em que você estava acabou de resetar.'
    DarMina: '&6&lMINA PARTICULAR &7-> &eVocê deu uma mina particular para um jogador.'
    Reiniciar-Config: '&6&lMINA PARTICULAR &7-> &aConfiguração reiniciada.'
    Receber-Cash: '&6&lMINA PARTICULAR &7-> &eVocê recebeu &6&l+50K ✪ de cash'
minas:
  minap1:
      type: SKULL_ITEM
      SkullMeta:
        ID: b53f975e-2857-427b-bede-069a780467fb
        Value: eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYjRlNzVjMzExOWZiNGNmZjdjZWNjODA2NGNlZGM0ZjkxMzVmZTAwMTU3M2ZiNzAyZTczZTRhODE4ZDQ1MzlkZSJ9fX0=
      data: 3
      name: '&6&lMINA PARTICULAR'
      lore:
      - '&eMina particular de &a(Coins)'
      - ''
      - '&f&lINFO:'
      - '&7▲ &fMoedas: &eRecebe &2$&a300M a cada bloco'
      - '&7▲ &fCash: &cEsta mina não lhe dá cash'
    Tamnho:
      size: 8 
   Blocos-Lateral:
      Lados: BEDROCK
      Chao: BEDROCK
      Tempo-para-resetar: 100 #Coloque (1 ou 2) e adicione 2 zeros para ficar 1minuto ou 2 minutos.
      Minerios:
      - COAL_BLOCK
      - IRON_BLOCK
      - DIAMOND_BLOCK
   PercentagemCoal: 30
   PercentagemIron: 20
   PercentagemDiamond: 50
   executed-command: 'money give {player} 300000000'
   Chance: 100

  minap2:
      type: SKULL_ITEM
      SkullMeta:
        ID: b53f975e-2857-427b-bede-069a780467fb
        Value: eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYjRlNzVjMzExOWZiNGNmZjdjZWNjODA2NGNlZGM0ZjkxMzVmZTAwMTU3M2ZiNzAyZTczZTRhODE4ZDQ1MzlkZSJ9fX0=
      data: 3
      name: '&6&lMINA PARTICULAR'
      lore:
      - '&eMina particular de &6(Cash)'
      - ''
      - '&f&lINFO:'
      - '&7▲ &fMoedas: &eRecebe &2$&a300M &ea cada bloco'
      - '&7▲ &fCash: &eRecebe &650K &ea cada bloco'
    Tamnho:
      size: 8
   Blocos-Lateral:
      Lados: QUARTZO
      Chao: QUARTZO
      Tempo-para-resetar: 200 #Coloque (1 ou 2) e adicione 2 zeros para ficar 1minuto ou 2 minutos.
      Minerios:
      - LAPIS_BLOCK
      - GOLD_BLOCK
      - DIAMOND_BLOCK
   PercentagemLapis: 50
   PercentagemGold: 40
   PercentagemDiamond: 10
   executed-command: 'money give {player} 300000000'
   Chance: 100
   executed-command: 'points give {player} 50000'
   Chance: 100

 Main-Confirmar:
        Name: '&7Pretende retirar esta mina?'
        type: SKULL_ITEM
      SkullMeta:
        ID: f294da6c-1ad0-453f-bb77-8c5ad4a9639d
        Value: eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvOTQ1ZjQ3ZmViNGQ3NWNiMzMzOTE0YmZkYjk5OWE0ODljOWQwZTMyMGQ1NDhmMzEwNDE5YWQ3MzhkMWUyNGI5In19fQ==
        LORE: 
        - '&7◆ &eClique caso queira retirar sua mina'
        - ''
        CommandsConsole:
          - "minasparticulares {player} minap1 remove" #Caso queira adicionar algum comando, pode adicionar.
 Main-Cancelar:
        Name: '&7Pretende cancelar esta ação?'
        type: SKULL_ITEM
      SkullMeta:
        ID: f294da6c-11ad0-453zzf-bb77-8c5ad4a9639d
        Value: eyJ0ZXh0dXJlcyKSZI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvOTQ1ZjQ3ZmViNGQ3NWNiMzMzOTE0YmZkYjk5OWE0ODljOWQwZTMyMGQ1NDhmMzEwNDE5YWQ3MzhkMWUyNGI5In19fQ==
        LORE: 
        - '&7◆ &eClique para cancelar esta ação.'
        - ''
        CommandsConsole:
          - "close" #Caso queira adicionar algum comando, pode adicionar.

  MinasHologramas:
       minap1:
        Hologramas:
          Line1: "&6&lMINA PARTICULAR"
          Line2: "&fDono da mina: &6{player}"
          Line3: "&fRaridáde: &aInicial"
       minap2:
        Hologramas:
          Line1: "&6&lMINA PARTICULAR"
          Line2: "&fDono da mina: &6{player}"
          Line3: "&fRaridáde: &aInicial"


#Minios Mineradores - Configurável-

 MinionMineradorInicial:
        Name: '&6Minion &aInicial'
        type: SKULL_ITEM
      SkullMeta:
        ID: f294da6c-11ad0-4z3zzf-bb77-8c5ad4a9639d
        Value: eyJ0ZXh0dXJlcyKSZI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvOTQ1ZjQ3ZmViNGQ3NWNiMzMzOTE0YmZkYjk5OWE0ODljOWQwZTMyMGQ1NDhmMzEwNDE5YWQ3MzhkMWUyNGI5In19fQ==
        LORE: 
        - '&7◆ &eEspecialidade do Minion'
        - '&a+15% Mineração ultra rápida!'
        - '&a+30% Energia'
        - '&a+15% Bonus Drop - Minerando'
        CommandsConsole:
          - "hminion set block rightclick minioninicial" #Caso queira adicionar algum comando, pode adicionar.
          - "hminion set energ 30" #30 é percentagem no caso +30% energia
          - "hminion set bonusdrop 15" #15 é a percentagem no caso 15% de bonus drop - minerando
          - "hminion set MineSpeed 15 " #15 é a percentagem no caso 15% de rápidez minerando
