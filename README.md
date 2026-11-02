# Game IA – Atividade prática: Steering Behaviors (libGDX)

Implementação à mão (sem gdx-ai) dos comportamentos vistos em aula.

| Passo | Onde | Como ver |
|---|---|---|
| 1. Modelar o agente | `Agente.java` (posição, velocidade, maxVelocidade, maxForca, massa) | – |
| 2. Seek e arrive | `Agente.seek / arrive` | tecla **1**, clique move o alvo |
| 3. Wander + FSM | `Agente.wander / pursuit`, `Jogo.updateFsm` | tecla **2**, WASD move o jogador |
| 4. Bônus: bando | `Agente.flocking` (30 agentes) | tecla **3**, Q/A W/S E/D ajustam pesos |

`ESPAÇO` liga/desliga os vetores de depuração (velocidade verde, steering azul).

