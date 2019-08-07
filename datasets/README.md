Download CIFAR-10 and CIFAR-100 to this folder by running the respective scripts.

Example:

```bash
bash datasets/cifar10.sh
```

SVHN will automatically be downloaded by `torchvision` when it's required.


It is also easy to use PBA on a custom dataset as well: simply define a new dataloader and everything else falls into place.
