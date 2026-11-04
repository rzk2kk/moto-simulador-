# MotoSimulador v33 — correção de luzes da Africa Twin

[Baixar o projeto Unity v33](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v33.zip)

Extraia o ZIP em uma pasta nova e execute `ABRIR_JOGO.bat`. Na primeira execução, a Unity prepara a garagem e as cenas da Honda CG 160, CB 300 Twister e Africa Twin, e compila o jogo. Depois, ele abre direto na garagem. Escolha uma moto e use **TESTAR** para pilotar.

Esta versão corrige a preparação da Africa Twin buscando farol e lanterna pelos nomes reais dos componentes do FBX (`headlight_l` e `taillight_l`). Também mantém os pivôs visuais de manete opcionais e verifica se as cenas foram geradas antes da compilação.

A tela de carregamento tem barra vermelha dinâmica e dica; o fundo artístico original será integrado depois. O perfil físico da Africa Twin é provisório. As 33 verificações do núcleo e a análise sintática passaram; esta versão ainda precisa de teste no Unity Editor.
