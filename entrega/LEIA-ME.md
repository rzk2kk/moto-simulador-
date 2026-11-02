# MotoSimulador — correção de condução e peças originais v24

A versão v24 mantém a ignição ligada até o comando de desligar, melhora a sincronização do som de aceleração e redução em qualquer marcha e restaura a chave do modelo original. Remove a placa e o pedal traseiro que haviam sido adicionados como peças provisórias.

Extraia o ZIP em uma pasta nova e execute `ABRIR_JOGO.bat`. Na primeira execução, a Unity gera o projeto e compila o executável.

Verificações automáticas: 32 testes de física do motor e análise sintática C# sem erros. A cena ainda precisa ser executada na Unity local para confirmar o comportamento final do `WheelCollider` e a aparência do modelo.
