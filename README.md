# Canary-vs-Blue-Green-na-AWS

Canary vs Blue/Green na AWS: Versão LoL e Rock Clássico

Fala, invocadores! Quando o assunto é deploy na AWS, dois estilos muito usados são o Canary e o Blue/Green. Vou explicar rapidinho usando o que a gente ama: LoL e aquele rockzão clássico. 

Canary Deploy = Testar o Gank com um Campeão Solo
Imagina que você tá planejando um gank pesado no Baron, mas antes de mandar todo o time, você envia só seu campeão mais furtivo (tipo um Rengar ou Twitch) pra dar uma olhada se o inimigo tá lá e se o terreno tá seguro. Se ele sobreviver e tudo estiver suave, aí sim você chama o squad inteiro pra mandar ver no fight.

Na AWS, o Canary é isso: libera só uma pequena parte do tráfego pro novo código, vê se tá tudo ok, e depois libera pra geral. Assim, evita que a partida (ou app) trave pra todo mundo.

Blue/Green Deploy = Dois Times, Dois Campos, Jogo Sem Tilt
Agora pensa numa partida ranqueada onde você não pode errar nada. Você prepara dois times completos: um (Blue) tá jogando a partida normal, enquanto o outro (Green) tá no campo de treino, testando estratégias novas, builds e sinergias. Quando o time novo estiver pronto e afiado, troca os times rapidinho, sem que os fãs (usuários) percebam, e sem deixar o jogo cair.

Na AWS, o Blue/Green é isso: duas versões do app, uma ativa e outra pronta pra assumir. Se a nova versão tiver problema, é só voltar rapidão pra antiga - sem sofrimento.

Canary e Blue/Green são como jogar solo pra testar ou preparar o time inteiro antes da team fight. Cada um tem seu momento, e saber qual usar é meta pra garantir a vitória no deploy!

![image](https://github.com/user-attachments/assets/2792c1eb-52b2-4dc3-8cff-c07eaeb7c566)
