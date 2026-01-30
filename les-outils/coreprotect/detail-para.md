# Détail para

| types                                             | explication                                                                                 |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| <mark style="color:$danger;">`u:<user>`</mark>    | Choisir un user en particulier                                                              |
| <mark style="color:$danger;">`t:<time>`</mark>    | Choisir la durée que vous voulez voir en arrière                                            |
| <mark style="color:$danger;">`r:<radius>`</mark>  | Choisir un rayon autour de vous en X blocss <mark style="color:$danger;">**X ≤ 100**</mark> |
| <mark style="color:$danger;">`a:<action>`</mark>  | Choisir une action en particulier                                                           |
| <mark style="color:$danger;">`i:<include>`</mark> | Inclure un bloc/entités spécifique                                                          |
| <mark style="color:$danger;">`e:<exclude>`</mark> | Exclure un bloc/entités spécifique                                                          |

<mark style="color:$danger;">`u:<user>`</mark>

Vous pouvez choisir un OU plusieur user pour votre lookup:

ex: <mark style="color:$success;">**- u:mysteriou73 // u: mysteriou73, Nosiaa**</mark>

<mark style="color:$danger;">`t:<time>`</mark>

Vous pouvez choisir le durer du lookup en arrière:

ex: <mark style="color:$success;">**t:1(s pour seconde, m pour minute, h pour heure, d pour jour, w pour semaine)**</mark>

<mark style="color:$danger;">`r:<radius>`</mark>

Vous pouvez choisir le rayon d'observation de votre lookup ( à partir de vous)

ex: <mark style="color:$success;">**r:50 effectue un lookup dans un rayon de 50 blocs**</mark>

{% hint style="danger" %}
<mark style="color:$danger;">**r: ≤ 100**</mark>
{% endhint %}

<mark style="color:$danger;">`a:<action>`</mark>

Vous permet de choisir une action en particulier depuis la liste si dessous:

| Action       | Description   |
| ------------ | ------------- |
| a:block      |               |
| a:+block     | Block poser   |
| a:-block     | Block détruit |
| a:chat       |               |
| a:click      |               |
| a:command    |               |
| a:container  |               |
| a:+container |               |
| a:-container |               |
| a:inventory  |               |
| a:+inventory |               |
| a:-inventory |               |
| a:item       |               |
| a:+item      |               |
| a:-item      |               |
| a:kill       |               |
| a:session    |               |
| a:+session   |               |
| a:-session   |               |
| a:sign       |               |
| a:username   |               |
