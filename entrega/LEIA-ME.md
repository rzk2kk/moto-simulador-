# MotoSimulador — contato das rodas v5

Baixe `MotoSimulador_Unity_6000.3.27f2_v5.zip`, extraia para uma pasta nova, abra `ABRIR_PROJETO.bat` e aguarde a Unity preparar a cena. Clique em Play.

Mantive a correção de equilíbrio e a câmera de primeira pessoa. As rodas agora usam mais subpassos de física até 72 km/h; isso remove a queda de amostragem que acontecia perto de 18 km/h. A velocidade vertical também não altera mais os cálculos de direção. O HUD mostra o contato de cada roda.

Os controles estão em `COMECE_AQUI.txt`. Se a moto deixar de acelerar, veja no HUD o RPM, a marcha e o contato da roda traseira. Os ajustes são provisórios e precisam de validação na Unity local; o Editor/PhysX não é executado nesta nuvem.

Se estiver testando a v4, extraia a v5 em uma pasta nova para criar a cena atualizada sem sobrescrever a anterior.
