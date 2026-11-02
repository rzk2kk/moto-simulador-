# MotoSimulador — câmera, manetes e estabilidade v10

Baixe o ZIP v10, extraia numa pasta nova e use `ABRIR_JOGO.bat`. Segure o botão direito do mouse e arraste para mover a câmera; em terceira pessoa ela orbita a moto. O botão no HUD e a tecla `V` alternam entre primeira e terceira pessoa.

As faixas adesivas foram removidas. A moto mantém a pintura preto/amarelo. O manete esquerdo mexe com Shift (embreagem) e o direito com Espaço (freio dianteiro). Os ajustes de torque, suspensão e equilíbrio investigam a instabilidade perto de 20 km/h; o limite da pista segue em 50 km/h. Os 31 testes do núcleo passaram, mas a física, as posições visuais e os comandos precisam ser confirmados no Play da Unity.

Na primeira execução, `ABRIR_JOGO.bat` compila o jogo no computador e abre o executável; nas seguintes, abre diretamente.
