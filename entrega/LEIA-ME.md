# MotoSimulador v28 — correção do sentido e do farol

[Baixar o projeto Unity v28](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v28.zip)

Extraia o ZIP em uma pasta nova e execute `ABRIR_JOGO.bat`. O pacote usa Unity 6000.3.27f2 e inclui a pista Blender, texturas e configuração da moto.

- Confere o sentido de aceleração no primeiro arranque e inverte o torque automaticamente se o modelo importado estiver com o eixo invertido.
- Restaura a pose completa calculada pelo WheelCollider para evitar desalinhamento visual da roda.
- Reforça o farol e configura o URP para renderizar luzes adicionais por pixel.
- Mantém o corte por marcha em 20, 40, 80, 110 e 160 km/h.

Os testes de núcleo e a verificação sintática C# passaram. A cena ainda precisa ser conferida no Play Mode da Unity local.
