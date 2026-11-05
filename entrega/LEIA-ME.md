# MotoSimulador v49 — auditoria das motos e iluminação

[Baixar o projeto Unity v49 (ZIP direto)](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v49.zip)

A v49 nivela o contato dos pneus da Street na cena de pilotagem, melhora o movimento das peças baixas do garfo da Adventure e corrige os materiais e caminhos das suas texturas. As pistas ganharam sol quente, céu, nuvens, faixas visuais discretas de luz e sombras mais longas; a garagem recebeu luzes de destaque. A auditoria com medições e pendências está em `MotoSimulador/Documentation/AUDITORIA_MOTOS_v49.md` dentro do ZIP.

A v48 habilitou o módulo Animation do Unity, necessário para compilar as cenas da história e o piloto. Ela corrigiu o erro CS1069 de `AnimationClip` registrado no log da v47. Extraia este ZIP em uma pasta nova para que o Unity leia o manifesto atualizado.

A v47 acrescentou três espaços independentes de carreira após **NOVO JOGO**, com continuação, exclusão confirmada e salvamento automático. O progresso anterior é migrado para o primeiro espaço. Dinheiro, motos compradas, pintura, aulas, provas, distância e missões são salvos em cada carreira.

Há 15 missões de dificuldade crescente com recompensas únicas. Elas cobrem a autoescola, pilotagem, farol, setas, frenagem, segurança e compras. A opção **MISSÕES** mostra objetivos e progresso. O modo **TESTAR** permite pilotar motos bloqueadas, mas não rende créditos nem avança missões.

O pacote também inclui as melhorias recentes na autoescola, cenários 3D, piloto e áreas de teste. Abra `ABRIR_JOGO.bat` no Windows; o Unity 6000.3.27f2 é necessário para a primeira compilação. A descrição completa e as atribuições estão em `MotoSimulador/LEIA-ME.md` dentro do ZIP.

Validação local: 39 testes do núcleo passaram, 37 arquivos C# passaram na checagem de sintaxe e a integridade do ZIP foi verificada. O Unity Editor não estava disponível neste ambiente, então compilação, iluminação, física e executável ainda precisam de teste dentro do jogo.
