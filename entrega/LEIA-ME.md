# MotoSimulador v27 — corte por marcha e ajustes físicos

[Baixar o projeto Unity v27](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v27.zip)

Extraia o ZIP em uma pasta nova e execute `ABRIR_JOGO.bat`. O pacote inclui a pista Blender, texturas e configuração para Unity 6000.3.27f2. A primeira abertura prepara e compila o jogo.

- Corte de giro por marcha: 20, 40, 80, 110 e 160 km/h; limite total de 160 km/h.
- Direção dianteira corrigida para girar no eixo vertical; farol direcionado à pista.
- Rodas visuais acompanham o RPM e param com a moto.
- Colisores no terreno, asfalto, acostamentos, faixa de equilíbrio, cones, portais, balizadores e placas; cones podem tombar ao serem atingidos.
- Velocímetro acompanha a escala da marcha selecionada.

Os testes de núcleo e a verificação sintática C# passaram. A cena ainda precisa ser conferida no Play Mode da Unity local.
