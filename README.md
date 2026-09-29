# OnTraining Floripa

App pessoal de treino e dieta para chegar à viagem de Floripa com o corpo mais definido.

## O que ele faz

- **Treino do dia**: segue a rotação Superior A → Inferior A → Intervalado + abdômen → Superior B → Inferior B → Cardio longo → Descanso, sempre a partir do último treino que você confirmou.
  - Se você pular um dia, o treino não avança.
  - Depois de 6 treinos seguidos, ele manda descansar.
  - Depois de 3 ou mais dias parado, ele pula o descanso e volta pelo Superior A.
  - Os exercícios alternam entre a variação A e B a cada vez que o treino é concluído.
  - Você anota a carga de cada exercício e o app mostra a da última vez.
  - Botão **Execução** em cada exercício: abre um popup com um bonequinho animado fazendo o movimento, o passo a passo, o erro mais comum e um link para vídeos no YouTube.
- **Refeições do dia**: 2 ou 3 por dia (você escolhe). Low carb, sem glúten e com gordura só de origem animal.
  - As porções são calculadas: a carne/ovos ajustam para bater a proteína e manteiga/queijo/bacon ajustam para fechar as calorias.
  - No modo 3, a refeição extra é um lanche, que vira pré-treino nos dias de treino.
  - Refeições confirmadas nos últimos 3 dias não se repetem. Botão "Trocar" sorteia outra opção.
- **Peso**: registro diário com média de 7 dias e aviso se o peso travar ou cair rápido demais.
- **Contagem regressiva** até a data da viagem, com aviso de redução de volume na semana da viagem.

## Metas

| Item | Meta |
|---|---|
| Calorias | ~2.350 kcal |
| Proteína | ~170 g |
| Gordura | ~150 g (animal) |
| Carboidrato | 50–80 g |

## Como usar

- Abra o `index.html` no navegador do celular. Os registros ficam salvos no próprio navegador.
- Para publicar no GitHub Pages: Settings → Pages → Branch `main` / pasta raiz. O app fica em `https://emanuel1811.github.io/ontraning/`.

## Personalizar

Tudo fica no início do `<script>` do `index.html`:
- `TREINOS`: exercícios, séries e variações.
- `ALIM`: tabela de alimentos (kcal e macros por grama ou unidade).
- `REF`: opções de refeição e o papel de cada alimento (proteína, gordura ou fixo).
- `PAD` e `DICAS`: animação e instruções de cada padrão de movimento.
- `META`: metas diárias.
