# MotoSimulador v29 — correção de compilação URP

[Baixar o projeto Unity v29](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v29.zip)

Extraia o ZIP em uma pasta nova e execute `ABRIR_JOGO.bat`. O pacote usa Unity 6000.3.27f2 e inclui a pista Blender, texturas e configuração da moto.

- Remove a configuração de duas propriedades URP incompatíveis com Unity 6000.3.27f2, que causavam erro de compilação CS0200 e CS1061.
- Mantém a verificação automática do sentido de aceleração no primeiro arranque e a pose da roda calculada pelo WheelCollider.
- Mantém o farol reforçado e os cortes por marcha em 20, 40, 80, 110 e 160 km/h.

Os testes de núcleo e a verificação sintática C# passaram. A compilação no Editor local precisa ser confirmada ao abrir o pacote.
