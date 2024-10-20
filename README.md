# Devoir-challenge-des-param-tres
Le but de ce devoir est de déterminer de manière pratique combien de paramètres une fonction peut accepter avant de provoquer une erreur ou un comportement inattendu . 
# Résultats Attendus
 Erreurs de Mémoire :
  À un certain point, lorsque tu essaies de passer trop de paramètres , tu pourrais obtenir une erreur liée à l'allocation de mémoire (bad_alloc).
 Limite Pratique :
  En pratique,cela dépendra toujours des limites spécifiques de ton environnement de compilation et de l'architecture .

# Documentation et Observation:








# Explication des Résultats
  Limitations Architecturales :
   Chaque machine a une capacité de mémoire et de traitement qui peut limiter le nombre de paramètres qu on peux passer à une fonction.
   Sur une machine avec moins de RAM ou avec une architecture 32 bits, on pourrait rencontrer des limites plus strictes par rapport à une machine 64 bits.
  Gestion de la Mémoire :
    Les systèmes d'exploitation gèrent la mémoire et, lorsque la mémoire disponible est épuisée, des erreurs d'allocation se produisent.
     L'utilisation d'un grand nombre de paramètres peut également augmenter la charge de la pile, ce qui peut entraîner des débordements si la limite est dépassée.
