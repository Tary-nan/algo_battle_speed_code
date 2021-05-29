# algo_battle_speed_code

## Durée : 30 mn

### INTRODUCTION

Nettoyez les numéros de téléphone saisis par l'utilisateur afin qu'ils puissent recevoir des messages SMS.

Le plan de numérotation nord-américain (NANP) est un système de numérotation téléphonique utilisé par de nombreux pays d'Amérique du Nord comme les États-Unis, le Canada ou les Bermudes. Tous les pays PNNA-partagent le même code du pays: 1.

Les numéros NANP sont des numéros à dix chiffres composés d'un indicatif régional de plan de numérotation à trois chiffres, communément appelé indicatif régional , suivi d'un numéro local à sept chiffres. Les trois premiers chiffres du numéro local représentent le code d'échange , suivi du numéro unique à quatre chiffres qui est le numéro d'abonné .

**Le format est généralement représenté par**

(NXX)-NXX-XXXX
où Nest n'importe quel chiffre de 2 à 9 et Xest n'importe quel chiffre de 0 à 9.

Votre tâche consiste à nettoyer les numéros de téléphone au format différent en supprimant la ponctuation et le code de pays (1) s'il est présent.


Par exemple, les entrées
* +1 (613)-995-0253
* 613-995-0253
* 1 613 995 0253
* 613.995.0253

```
devraient tous produire la sortie
6139950253
```
