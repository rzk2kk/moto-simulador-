# MotoSimulador v48 — correção da compilação da animação

[Baixar o projeto Unity v48 (ZIP direto)](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v48.zip)

A v48 habilita o módulo Animation do Unity, necessário para compilar as cenas da história e o piloto. Ela corrige o erro CS1069 de `AnimationClip` registrado no log da v47. Extraia este ZIP em uma pasta nova para que o Unity leia o manifesto atualizado.

A v47 acrescentou três espaços independentes de carreira após **NOVO JOGO**, com continuação, exclusão confirmada e salvamento automático. O progresso anterior é migrado para o primeiro espaço. Dinheiro, motos compradas, pintura, aulas, provas, distância e missões são salvos em cada carreira.

Há 15 missões de dificuldade crescente com recompensas únicas. Elas cobrem a autoescola, pilotagem, farol, setas, frenagem, segurança e compras. A opção **MISSÕES** mostra objetivos e progresso. O modo **TESTAR** permite pilotar motos bloqueadas, mas não rende créditos nem avança missões.

O pacote também inclui as melhorias recentes na autoescola, cenários 3D, piloto e áreas de teste. Abra `ABRIR_JOGO.bat` no Windows; o Unity 6000.3.27f2 é necessário para a primeira compilação. A descrição completa e as atribuições estão em `MotoSimulador/LEIA-ME.md` dentro do ZIP.

Validação local: 39 testes do núcleo passaram; a integridade do ZIP e o isolamento dos espaços de carreira foram verificados. O Unity Editor não estava disponível neste ambiente, então telas, física e executável ainda precisam de teste dentro do jogo.
