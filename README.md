# RemoteBox

## Présentation
L'application RemoteBox est une application pratique et facile à utiliser, conçue pour être compatible avec la box orange (et d'autres dans le futur). Elle inclut des fonctions telles que la mise sous/hors tension, le contrôle du volume, la navigation entre les chaînes... L'application est développée en Swift et SwiftUI

## Fonctionnalités
- **Contrôle de l'alimentation** : Allumez ou éteignez rapidement votre box grâce à un bouton dédié.
- **Contrôle du volume** : Ajustez facilement le volume à la hausse ou à la baisse grâce aux boutons à l'écran.
- **Navigation entre les chaînes** : Changez de chaîne en toute simplicité à l'aide de boutons dédiés ou du pavé numérique.
- **Pavé de contrôle directionnel** : Naviguez dans les menus avec un pavé de contrôle à quatre directions et un bouton "Ok".
- **Retour haptique personnalisé** : Chaque pression de bouton inclut un retour haptique.
- **Toasts d'erreur** : Les utilisateurs sont notifiés par un message toast en cas de problème (par exemple, problème de connexion).

## Écrans
1. **Écran principal de la télécommande** : L'interface principale se compose de boutons pour l'alimentation, le volume, la navigation entre les chaînes, et un pavé numérique pour rendre l'interaction plus directe et intuitive.

## Structure du code
- **RemoteView** : La vue principale SwiftUI qui représente l'interface de la télécommande.
- **RemoteViewModel** : Gère l'état et la logique en arrière-plan, comme l'envoi de commandes à la box, ainsi que la gestion des messages de retour.
- **Style de shadow personnalisé** : Des ombres personnalisées ont été ajoutées pour améliorer l'apparence visuelle des boutons.

## Installation
1. Clonez le dépôt.
2. Ouvrez le projet dans Xcode.
3. Exécutez le projet sur un simulateur iOS ou un appareil physique.

## Personnalisation
- **Ajouter plus de commandes** : Vous pouvez facilement ajouter de nouvelles touches en mettant à jour l'énum `RemoteKey` et les vues correspondantes.

## Améliorations futures
- **Compatibilité avec d'autres box** : Étendre la compatibilité à d'autres appareils.
- **Contrôle vocal** : Ajouter la prise en charge des commandes vocales pour faciliter encore plus la navigation.

## Screen
<img src="https://github.com/user-attachments/assets/bf50afb2-cc6e-45bb-8639-b6cbeb140d43" alt="Simulator Screenshot - iPhone 16 Pro - 2024-10-05 at 17 35 28" width="50%">
