#REX sur l'utilité des AI plateformes dans l'octroi de l'intelligence aux chatbots : 

<p align="center">
<img src="https://github.com/Raniazy/ai_plateforms_fir_chatbots_api_wit_googlenl_luis_watson/blob/master/img/no.png">
</p>

Les Chatbots sont des programmes informatiques qui peuvent interagir avec des utilisateurs humains dans des conversations. Il faut qu'ils soient utiles et utilisables. Bien qu'ils se contentent de réaliser la tâche pour laquelle ils sont conçus, ils ne peuvent pas être considéré comme des chatbots intelligents. 
Cette aptitude peut leur être attribuée via des plate-formes d'intelligence artificielle. C'est l'intelligence qui rend une conversation complexe facile et sans effort.

Les chatbots d'AI résident dans l'environnement préféré des utilisateurs (applications de messagerie), conversent avec les utilisateurs en langage naturel et comprennent ce que les internautes veulent. C'est ce que la science-fiction nous a promis depuis des décennies. 

Les Machines Learning peuvent aider le chatbot à identifier l'intention du message et à extraire des entités nommées. Ils sont très puissants mais nécessitent beaucoup de données pour former le modèle d'apprentissage. L'évolution des plateformes de traitement du langage naturel a permis aux chatbots d'avoir un comportement plus humain. 

Selon mon humble expérience autour des bots et comment leurs procurer une nature proche à l'humaine, je présenterai quelques plate-formes de Traitement du Langage Naturel NLP. 

#Quelques technologies NLP qui rendront vos robots intelligents en langage
##Wit.ai 

Wit est une interface de langage naturel pour les applications capable de transformer les phrases en données structurées. C'est une combinaison de reconnaissance de patterns et de Machine Learning. Wit.ai a été achetée par Facebook en janvier 2015. 

Elle est simple à utiliser vu ses outils raffinés. Elle permet d'extraire des informations structurées depuis un message ainsi que le suivi des interactions entre les utilisateurs et le chatbot. 
<p align="center">
<img src="https://github.com/Raniazy/ai_plateforms_fir_chatbots_api_wit_googlenl_luis_watson/blob/master/img/wit.png">
</p>
L'API Wit permet aux appels HTTP GET de renvoyer le sens extrait d'une phrase donnée en fonction des exemples appris par l'application. L'API retourne des réponses formatées JSON.

##Api.ai

Api.ai est un outil de Langage naturel dédié à la conception des scénarii de conversation uniques, dégénération des actions correspondantes et analyse des interactions avec les utilisateurs.

Api.ai fournit une plateforme qui permet aux développeurs de concevoir et d'implémenter des interfaces de conversation qui peuvent être intégrées dans des applications externes comme des bots. 
Fonctionnellement, Api.ai inclut des activités telles que la reconnaissance vocale, l'exécution ainsi qu'un ensemble d'outils de gestion robuste. 
Api.ai fournit l'intégration avec plusieurs plates-formes de bot et est particulièrement populaire dans la communauté Slack.
<p align="center">
<img src="https://github.com/Raniazy/ai_plateforms_fir_chatbots_api_wit_googlenl_luis_watson/blob/master/img/api.png">
</p>

##Google Natural Language (NL)

L'API Google Cloud Natural Language révèle la structure et la signification du texte en offrant des modèles puissants d'apprentissage automatique dans une API REST facile à utiliser. Elle offre des fonctionnalités telles que la détection de l'entité d'intention, l'analyse du sentiment, la classification du contenu et les graphiques de relation.

On peut l'utiliser pour extraire des informations sur des personnes, des lieux, des événements et bien plus encore, mentionnés dans des documents textuels, des articles de nouvelles ou des articles de blog. On peut l'utiliser pour comprendre le sentiment des utilisateurs sur les réseaux sociaux concernant un produit ou analyser l'intention d'une conversations dans une application de messagerie. 

Voici un exemple d'analyse de la phrase : "Google, headquartered in Mountain View, unveiled the new Android phone at the Consumer Electronic Show. Sundar Pichai said in his keynote that users love their new Android phones."

En plus de l'analyse des entités contenues dans la phrase, en occurrence : PERSON, LOCATION, ORGANISATION ... On trouve l'analyse des Sentiments ainsi que la Syntaxe de la phrase.  
<p align="center">
<img src="https://github.com/Raniazy/ai_plateforms_fir_chatbots_api_wit_googlenl_luis_watson/blob/master/img/ggle.png">
</p>
##LUIS : Language Understanding Intelligence Service de Microsoft 

LUIS offre un moyen rapide et efficace d'ajouter le traitement du langage naturel aux applications. On peut utiliser des modèles préexistants, de classe mondiale, pré-construits de Bing et Cortana chaque fois qu'ils conviennent au besoin - et lorsque'on a besoin de modèles spécialisés, LUIS possède un processus de construction rapide.

LUIS s'appuie sur du Machine Learning et la NLP de Microsoft Research et Bing, y compris la plate-forme de Microsoft Research pour l'apprentissage de concepts interactifs (PICL). LUIS fait partie d'un projet de Microsoft Cognitive Services.

Il est en version bêta et libre d'utilisation.
<p align="center">
<img src="https://github.com/Raniazy/ai_plateforms_fir_chatbots_api_wit_googlenl_luis_watson/blob/master/img/luis.png">
</p>
##Watson Conversation Service 

Watson Conversation combine un certain nombre de techniques cognitives pour aider les développeurs à construire et à former des bots définissant les intentions et les entités et l'artisanat de dialogue pour simuler la conversation. Le système peut ensuite être raffiné avec des technologies supplémentaires pour rendre le système plus humain-like ou de lui donner une plus grande chance de retourner la bonne réponse. Watson Conversation Service est généralement utilisé en conjonction avec d'autres services Watson NLP tels que Alchemy Language ou Natural Language Classifier.
<p align="center">
<img src="https://github.com/Raniazy/ai_plateforms_fir_chatbots_api_wit_googlenl_luis_watson/blob/master/img/watson.png">
</p>

J'ai examiné à la fois wit.ai, Google NL et API.AI La console API.AI est plus facile a utiliser et semble produire des applications qui apprennent beaucoup plus vite que celle sur Wit.ai. Bien que cette dernière bug quand les scénarios se compliquent avec un apprentissage moins vite, ses stratégies sont fortes et l'interface est formidable.

Wit et LUIS n'ont pas une bonne option pour créer des synonymes pour les entités. Ce qui est un must si on a besoin d'une bonne interprétation du langage naturel et du dialogue. 
Le problème avec Api.ai est qu'elle essaie d'utiliser uniquement les structures de phrase existantes limitant la vraie croissance. Aussi remplir le contexte pour chaque intention n'est pas idéal.
La documentation de Google NL n'est pas vraiment propre mais le résultat est toujours convainquant. Le seul problème avec Google NL est qu'on n'a pas le droit de créer nos propres entités. On se contente avec ce qui existe. 

#sharing_is_caring
