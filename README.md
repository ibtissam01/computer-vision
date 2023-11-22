## Projet : Segmentation des lésions de sclérose en plaques (SEP) dans des images IRM cérébrales

Ce projet se concentre sur la segmentation des lésions de sclérose en plaques (SEP) dans des images IRM cérébrales. L'objectif est d'identifier et de segmenter les lésions de SEP présentes dans les images afin d'aider à la détection précoce et au suivi de la maladie. Le dataset utilisé est le dataset SEP disponible sur ScienceDirect.

### Description du Dataset SEP
Le dataset SEP contient des images IRM cérébrales de patients atteints de sclérose en plaques. Les images ont été acquises à l'aide de la technique d'imagerie par résonance magnétique (IRM) et fournissent des informations détaillées sur la structure du cerveau. Chaque image est associée à un masque de segmentation qui indique les régions correspondant aux lésions de SEP.

![image](https://github.com/ibtissam01/computer-vision/assets/89752387/7e0ae979-5436-4220-9b17-d23f6e80d5a0)


### Objectif du Projet
L'objectif principal de ce projet est de développer un algorithme de segmentation des lésions de SEP dans les images IRM cérébrales. En utilisant des techniques de prétraitement d'images et de segmentation, nous chercherons à identifier et à isoler les régions de lésions de SEP présentes dans les images. La segmentation précise des lésions de SEP peut fournir des informations cruciales pour le diagnostic, le suivi de la progression de la maladie et l'évaluation de l'efficacité des traitements.

### Méthodologie
Voici les étapes clés de la méthodologie utilisée dans ce projet :

1. Prétraitement des images IRM :
   - Normalisation des intensités pour égaliser l'éclairage et réduire les variations de contraste.
   - Réduction du bruit à l'aide de filtres adaptés aux images médicales.
   - Correction des artefacts d'acquisition ou de mouvement indésirables.
  
     ![Uploading image.png…]()


2. Segmentation des lésions de SEP :
   - Utilisation d'algorithmes de segmentation classiques tels que la segmentation par seuillage ou la segmentation par région de croissance.
   - Exploration d'approches plus avancées telles que la segmentation par apprentissage automatique (par exemple, réseaux de neurones convolutifs).

     ![image](https://github.com/ibtissam01/computer-vision/assets/89752387/59abd408-d78e-4e46-a3ca-6cf4b9f372d0)
     
     ![image](https://github.com/ibtissam01/computer-vision/assets/89752387/557cb566-7f02-4501-951f-c79615f7d8c6)



3. Évaluation et validation :
   - Mesure des performances de la segmentation en comparant les résultats de la segmentation avec les masques de segmentation de référence.
   - Évaluation quantitative à l'aide de mesures telles que la précision, le rappel et le coefficient de Dice.
     ![image](https://github.com/ibtissam01/computer-vision/assets/89752387/236271d6-df73-4085-8316-a124a8b0310c)


### Ressources supplémentaires
- Le dataset SEP utilisé dans ce projet peut être téléchargé à partir de [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2352396418300756).

### Conclusion
La segmentation des lésions de sclérose en plaques dans les images IRM cérébrales est une tâche complexe mais cruciale pour le diagnostic et le suivi de la maladie. Ce projet offre l'opportunité d'explorer et de développer des méthodes de prétraitement et de segmentation d'images médicales, en mettant l'accent sur l'identification précise des lésions de SEP. En réalisant ce projet, vous pourrez acquérir une expérience pratique en utilisant des techniques d'imagerie médicale et en développant des algorithmes de segmentation avancés.
