# OnTraining Floripa

App pessoal de treino e dieta para chegar à viagem de Floripa com o corpo mais definido.

## O que ele faz

- **Treino do dia**: segue a rotação Superior A → Inferior A → Intervalado + abdômen → Superior B → Inferior B → Cardio longo → Descanso, sempre a partir do último treino que você confirmou.
  - Se você pular um dia, o treino não avança.
  - Depois de 6 treinos seguidos, ele manda descansar.
  - Depois de 3 ou mais dias parado, ele pula o descanso e volta pelo Superior A.
  - Os exercícios alternam entre a variação A e B a cada vez que o treino é concluído.
  - Você anota a carga de cada exercício e o app mostra a da última vez.
- **Refeições do dia**: low carb, sem glúten e com gordura só de origem animal. Refeições confirmadas nos últimos 3 dias não se repetem. Botão "Trocar" sorteia outra opção. Em dia de descanso não tem pré-treino.
- **Peso**: registro diário com média de 7 dias e aviso se o peso travar ou cair rápido demais.
- **Contagem regressiva** até a data da viagem, com aviso de redução de volume na semana da viagem.

## Metas

| Item | Meta |
|---|---|
| Calorias | ~2.350 kcal |
| Proteína | 150–160 g |
| Gordura | 140–150 g (animal) |
| Carboidrato | 50–80 g |

## Como usar

- Abra o `index.html` no navegador do celular. Os registros ficam salvos no próprio navegador.
- Para publicar no GitHub Pages: Settings → Pages → Branch `main` / pasta raiz. O app fica em `https://emanuel1811.github.io/ontraning/`.

## Personalizar

Tudo fica no início do `<script>` do `index.html`:
- `TREINOS`: exercícios, séries e variações.
- `REFEICOES`: opções de cada refeição com kcal, proteína, gordura e carboidrato.
- `META`: metas diárias.
