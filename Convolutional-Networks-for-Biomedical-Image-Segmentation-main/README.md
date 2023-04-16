# Convolutional-Networks-for-Biomedical-Image-Segmentation
This is a specific type of CNN called a "U-Net", that is used for biomedical imaging data based off computer vision research

This program is based off a 2015 research paper that uses a U-Net neural network and training strategy for successful training of deep networks with limited annotated samples. The network uses data augmentation to efficiently use available samples, and consists of a contracting path and a symmetric expanding path for context capture and precise localization, respectively. The network outperforms prior methods for segmentation of neuronal structures and cell tracking in electron microscopic stacks and transmitted light microscopy images, respectively. The network is also fast, with segmentation of a 512x512 image taking less than a second on a recent GPU


![blog-2](https://user-images.githubusercontent.com/30676606/231501106-6f14dd46-c449-4905-bcaa-b1f6e68c8b1e.jpg)


![Example-of-U-Net-segmentation-vs-ground-truth-results-of-a-transverse-CT-image-of-the](https://user-images.githubusercontent.com/30676606/231501149-0efbb91b-bbf6-4676-8641-86687eca0065.png)



![u-net-architecture](https://user-images.githubusercontent.com/30676606/231501191-a479d04b-3201-40ed-bd7e-b3643a38b6f9.png)
