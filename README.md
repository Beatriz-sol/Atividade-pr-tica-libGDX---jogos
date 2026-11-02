# Game IA – Atividade prática: Steering Behaviors (libGDX)

Implementação à mão (sem gdx-ai) dos comportamentos vistos em aula.

| Passo | Onde | Como ver |
|---|---|---|
| 1. Modelar o agente | `Agente.java` (posição, velocidade, maxVelocidade, maxForca, massa) | – |
| 2. Seek e arrive | `Agente.seek / arrive` | tecla **1**, clique move o alvo |
| 3. Wander + FSM | `Agente.wander / pursuit`, `Jogo.updateFsm` | tecla **2**, WASD move o jogador |
| 4. Bônus: bando | `Agente.flocking` (30 agentes) | tecla **3**, Q/A W/S E/D ajustam pesos |

`ESPAÇO` liga/desliga os vetores de depuração (velocidade verde, steering azul).

## Executar
```
gradle run        # ou ./gradlew run se você gerar o wrapper
```
Requer JDK 11+.

## Vídeo (até 1 min) – roteiro
1. (0–15s) Tecla 1: clique em alguns pontos; mostre o seek oscilando e o arrive parando.
2. (15–35s) Tecla 2: deixe o guarda vagar, entre no cone de visão, mostre a troca para PROCURANDO e a captura.
3. (35–55s) Tecla 3: mostre o bando e altere os pesos (ex.: coesão alta x separação alta).
