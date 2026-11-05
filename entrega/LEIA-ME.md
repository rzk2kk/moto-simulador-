# MotoSimulador v44 — lobby, garagem e autoescola

[Baixar o projeto Unity v44 (ZIP direto)](https://raw.githubusercontent.com/rzk2kk/moto-simulador-/entrega-unity-6000-3/entrega/MotoSimulador_Unity_6000.3.27f2_v44.zip)

O lobby mostra a etapa atual da carreira. A garagem ganhou informações de visualização e controles para pausar ou girar manualmente a moto. A autoescola tem doze momentos: chegada, dez aulas e preparação para a prova. Cada questão é ensinada em sua aula; a prova agora tem dez situações, explica as respostas, exige oito acertos e não tem limite de tempo. O progresso das aulas é salvo.

A troca de idioma deixou de reproduzir voz. A história mostra legendas em português, inglês e espanhol e carrega automaticamente áudios offline do ElevenLabs quando disponíveis. **Os áudios não estão neste ZIP**, pois ainda não há chave da API nem uma voz selecionada. O projeto inclui `Tools/generate_elevenlabs_voice.py` para gerá-los depois sem incluir a chave no jogo.

Validação: 35 testes do núcleo, checagem sintática de 30 arquivos C#, conteúdo das dez aulas e questões em três idiomas, integridade do ZIP e execução do gerador em modo de verificação. O Unity Editor não está disponível neste ambiente; ainda é preciso abrir o projeto e conferir as telas e a pilotagem no jogo.
