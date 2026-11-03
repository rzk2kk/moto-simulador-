# MotoSimulador v32 — correção de preparação da garagem

[Baixar o projeto Unity v32](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v32.zip)

Extraia o ZIP em uma pasta nova e execute `ABRIR_JOGO.bat`. Na primeira execução, a Unity prepara a garagem e as cenas da Honda CG 160, CB 300 Twister e Africa Twin, e compila o jogo. Depois, ele abre direto na garagem. Escolha uma moto e use **TESTAR** para pilotar.

Corrige a falha de preparação causada pela ausência de pivôs visuais de manete na CB 300 e na Africa Twin; esses controles agora são opcionais. A geração da garagem também interrompe a compilação com erro claro se alguma cena não for criada.

A tela de carregamento tem barra vermelha dinâmica e dica. O fundo artístico original será integrado em uma atualização futura. O perfil físico da Africa Twin é provisório. As 33 verificações do núcleo e a análise sintática passaram; esta versão ainda precisa de teste no Unity Editor.
