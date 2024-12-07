# Junit
L'architecture
La version 5 de JUnit est composée de trois sous-projets :

JUnit Platform : propose une API permettant aux outils de découvrir et exécuter des tests. Il définit une interface entre JUnit et les clients qui souhaitent exécuter les tests (IDE ou outils de build par exemple)
JUnit Jupiter : propose une API reposant sur des annotations pour écrire des tests unitaires JUnit 5 et un TestEngine pour les exécuter
JUnit Vintage : propose un TestEngine pour exécuter des tests JUnit 3 et 4 et ainsi assurer une compatibilité ascendante
L'objectif de cette architecture est de séparer les responsabilités des tests, d'exécution et d'extensions. Elle doit aussi permettre de faciliter l'intégration d'autres frameworks de tests dans JUnit.
