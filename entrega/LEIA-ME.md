# MotoSimulador v51 — correção da criação da garagem

[Baixar o projeto Unity v51 (ZIP direto)](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v51.zip)

O log da v50 mostrou que o FBX de um colega já continha um componente `Animation`. A criação da sala tentou adicionar outro e parou com `NullReferenceException`; por isso a garagem não foi gerada e o executável não pôde ser compilado. A v51 reutiliza o componente existente, evita clipes duplicados e inicia a animação quando o jogo roda. A cena é regenerada na primeira abertura.

Extraia este ZIP inteiro em uma **pasta nova** no Windows e abra `ABRIR_JOGO.bat`. O Unity 6000.3.27f2 é necessário para a primeira compilação. O conteúdo da v50, incluindo personagens, carreiras, XP e missões, está preservado.

Validação local: 40 testes do núcleo, 39 arquivos C# na checagem de sintaxe, currículo e integridade do ZIP passaram. O Editor Unity não está disponível neste ambiente; a compilação Windows precisa ser confirmada no seu computador.
