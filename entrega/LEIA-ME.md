# MotoSimulador — abrir como jogo v7

Baixe o ZIP v7 e extraia tudo para uma pasta. Dê dois cliques em `ABRIR_JOGO.bat`.

Na primeira vez, o arquivo usa a Unity 6000.3.27f2 instalada no computador para importar e compilar o projeto em segundo plano; isso pode levar alguns minutos. Depois ele abre `MotoSimulador.exe` diretamente, sem abrir o Editor.

O executável e o log de compilação ficam dentro de `MotoSimulador/Build`. Se a compilação falhar, veja `MotoSimulador/Build/primeira_compilacao.log`. Para editar ou abrir a cena na Unity, use `ABRIR_PROJETO.bat`.

A nuvem não tem o Unity Editor de Windows, então não consigo gerar nem testar um EXE pronto daqui. Os 30 testes do núcleo passaram, mas o build standalone ainda precisa rodar uma vez no PC.
