# SlackPairBot

O SlackPairBot é um bot para o slack 
Que diferente dos outros bots
Ajuda o time a manter um ritmo saudável de pareamento


Features:
1. /pair-list: Lista pessoas que estão pareando
2. /pair-free: Lista pessoas que estão sem par
3. /pair-with @someone <JIRA card>: Informa que está pareando com @someone, em determinado cartão (opcional)
4. pairbot.com/status/<prefixoSlack>/#canal: Lista pessoas que estão pareando no momento, pessoas disponíveis para parear e estatísticas de pareamento (quantas vezes)

MVP: 1, 2, 3

Feature 3:
Given we have a slack channel with 2 people (Gil and Mauricio)
When Gil enters /pair-with @Mauricio
Then the SlackPairBot should ask Mauricio a yes or no question
