* Original notebook: [![Open In Colab][colab-badge]][colab-notebook1]
[colab-notebook1]: <https://colab.research.google.com/github/komorra/ACA/blob/main/komorra_ACA_Augmented_Classifier_Attack.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>

# ACA
Augmented Classifier Attack

What is ACA?
* Generative algorithm, that can generate images, with support of any image classifier
* It doesn't need image generators
* It optimizes input image space "directly", optimizing it using augmentation, to match given classifier output
* It can help researchers to optimize their image classifiers

It is highly recommended to run this Colab notebook with GPU backend

# Examples
## Example using OpenAI CLIP model
Each image was generated for optimizing input image for given prompt embedding vector

Prompt: Beautiful flowers

![Beautiful Flowers](beautiful_flowers.png)

Prompt: Dance party

![Dane party](dance_party.png)

Prompt: Portrait of Mario

![Portrait of Mario](portrait_of_mario.png)

Prompt: Singing person

![Singing person](singing_person.png)
