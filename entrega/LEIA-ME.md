# MotoSimulador v43 — direção das outras motos

[Baixar o projeto Unity v43 (ZIP direto)](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v43.zip)

Esta versão aplica à Rota 300 Street e à Rota 1000 Adventure o alinhamento entre o WheelCollider, o guidão, o garfo e a roda dianteira. Na Street, as peças inferiores do garfo agora acompanham o pivô de suspensão que estava vazio. Na Adventure, a preparação cria os pivôs de direção e suspensão, liga as peças do garfo e do guidão e prende os discos dianteiros ao eixo da roda. As cenas são recriadas na primeira abertura para receber as alterações.

A arrancada das duas motos foi verificada com seus perfis provisórios de massa, câmbio e aderência. A v42 já corrigia a orientação física do asfalto e a arrancada da Start. As demais funções da garagem, da autoescola e da pilotagem permanecem no pacote.

Validação: 35 testes do núcleo aprovados, análise sintática de 30 arquivos C# sem erros, integridade do ZIP v43 e comparação de conteúdo com a v42. O Unity Editor não está disponível neste ambiente; ainda é necessário testar no jogo o contato das rodas, a aceleração e o movimento visual do conjunto dianteiro.
