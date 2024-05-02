# Exploration de Keras Tuner sur l'ensemble de données MNIST

Ce dépôt contient des notebooks Jupyter développés sur Google Colab pour explorer l'efficacité de Keras Tuner dans l'optimisation de l'architecture des réseaux neuronaux (NAS) et l'ajustement des hyperparamètres pour maximiser la précision de validation sur l'ensemble de données MNIST.

## Aperçu

L'ensemble de données MNIST est un ensemble de données de référence classique dans le domaine de l'apprentissage automatique, composé d'images en niveaux de gris de 28x28 pixels de chiffres manuscrits (0-9). Dans ce projet, nous visons à utiliser Keras Tuner, une bibliothèque d'ajustement d'hyperparamètres pour Keras, pour optimiser à la fois l'architecture des réseaux neuronaux et leurs hyperparamètres afin d'obtenir la précision de validation la plus élevée sur l'ensemble de données MNIST.

## Contenu

- `MNIST_NN_hyperparameter_tuning_with_keras_tuner.ipynb`: Ce notebook montre comment utiliser Keras Tuner pour effectuer l'ajustement d'hyperparamètres afin d'optimiser les architectures de réseaux neuronaux (sans couches de convolution) sur l'ensemble de données MNIST.
- `MNIST_CNN_hyperparameter_tuning_with_keras_tuner.ipynb`: Ce notebook montre comment utiliser Keras Tuner pour effectuer l'ajustement d'hyperparamètres afin d'optimiser les architectures de réseaux neuronaux convolutifs sur l'ensemble de données MNIST.

## Pour commencer

Pour exécuter ces notebooks, vous pouvez soit cloner ce référentiel et les exécuter localement dans votre environnement Jupyter, soit les ouvrir directement dans Google Colab.

### Prérequis

- Python 3.8
- Jupyter Notebook ou Google Colab
- Keras Tuner (`pip install keras-tuner`)

## Utilisation

1. Clonez le référentiel :

    ```
    git clone https://github.com/your-username/mnist-keras-tuner.git
    ```

2. Accédez au répertoire du référentiel :

    ```
    cd mnist-keras-tuner
    ```

3. Ouvrez le notebook souhaité dans votre environnement Jupyter ou Google Colab et exécutez les cellules séquentiellement.

## Résultats

À la fin de ces notebooks, vous devriez avoir des idées sur la manière dont Keras Tuner peut être utilisé de manière efficace pour l'ajustement d'hyperparamètres et la recherche d'architecture neuronale (NAS) pour optimiser les performances du réseau neuronal sur l'ensemble de données MNIST.

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Remerciements

- L'ensemble de données MNIST : http://yann.lecun.com/exdb/mnist/
- Keras Tuner : https://keras-team.github.io/keras-tuner/
