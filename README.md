# ImgClassification_using_CIFAR10_and_CIFAR100

## CIFAR-10

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. The classes are completely mutually exclusive. There are 50000 training images and 10000 test images.

The batches.meta file contains the label names of each class.

The dataset was originally divided in 5 training batches with 10000 images per batch. The original dataset can be found here: https://www.cs.toronto.edu/~kriz/cifar.html. This dataset contains all the training data and test data in the same CSV file so it is easier to load.

### Content
Here is the list of the 10 classes in the CIFAR-10:

#### Classes:
1) 0: airplane
2) 1: automobile
3) 2: bird
4) 3: cat
5) 4: deer
6) 5: dog
7) 6: frog
8) 7: horse
9) 8: ship
10) 9: truck

## CIFAR-100

The CIFAR-100 dataset consists of 60000 32x32 colour images in 100 classes, with 600 images per class. The 100 classes in the CIFAR-100 are grouped into 20 superclasses. Each image comes with a "fine" label (the class to which it belongs) and a "coarse" label (the superclass to which it belongs). There are 50000 training images and 10000 test images.
The meta file contains the label names of each class and superclass.

### Content
Here is the list of the 100 classes in the CIFAR-100:

#### Classes:
1-5) beaver, dolphin, otter, seal, whale <br>
6-10) aquarium fish, flatfish, ray, shark, trout <br>
11-15) orchids, poppies, roses, sunflowers, tulips <br>
16-20) bottles, bowls, cans, cups, plates <br>
21-25) apples, mushrooms, oranges, pears, sweet peppers <br>
26-30) clock, computer keyboard, lamp, telephone, television <br>
31-35) bed, chair, couch, table, wardrobe <br>
36-40) bee, beetle, butterfly, caterpillar, cockroach <br>
41-45) bear, leopard, lion, tiger, wolf <br>
46-50) bridge, castle, house, road, skyscraper <br>
51-55) cloud, forest, mountain, plain, sea <br>
56-60) camel, cattle, chimpanzee, elephant, kangaroo <br>
61-65) fox, porcupine, possum, raccoon, skunk <br>
66-70) crab, lobster, snail, spider, worm <br>
71-75) baby, boy, girl, man, woman <br>
76-80) crocodile, dinosaur, lizard, snake, turtle <br>
81-85) hamster, mouse, rabbit, shrew, squirrel <br>
86-90) maple, oak, palm, pine, willow <br>
91-95) bicycle, bus, motorcycle, pickup truck, train <br>
96-100) lawn-mower, rocket, streetcar, tank, tractor <br>

and the list of the 20 superclasses:
1) aquatic mammals (classes 1-5)
2) fish (classes 6-10)
3) flowers (classes 11-15)
4) food containers (classes 16-20)
5) fruit and vegetables (classes 21-25)
6) household electrical devices (classes 26-30)
7) household furniture (classes 31-35)
8) insects (classes 36-40)
9) large carnivores (classes 41-45)
10) large man-made outdoor things (classes 46-50)
11) large natural outdoor scenes (classes 51-55)
12) large omnivores and herbivores (classes 56-60)
13) medium-sized mammals (classes 61-65)
14) non-insect invertebrates (classes 66-70)
15) people (classes 71-75)
16) reptiles (classes 76-80)
17) small mammals (classes 81-85)
18) trees (classes 86-90)
19) vehicles 1 (classes 91-95)
20) vehicles 2 (classes 96-100)

#### These datasets are very commonly used in benchmarking different CNN models for classification
