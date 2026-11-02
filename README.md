# pytorch-learning

My path from neural-network fundamentals to vision-language models (VLMs), written by hand rather than copied.

Sources: 3Blue1Brown *Neural Networks*, OpenCV University *PyTorch Bootcamp*, Andrej Karpathy *Neural Networks: Zero to Hero*.

| # | Topic | Notebook |
|---|---|---|
| 01 | Tensors & autograd | [01_tensors_autograd.ipynb](01-tensors-autograd/01_tensors_autograd.ipynb) |
| 02 | MLP on Fashion-MNIST (training loop by hand) | _next_ |
| 03 | CNN & pretrained models | _planned_ |
| 04 | Transfer learning & fine-tuning | _planned_ |
| 05 | Segmentation, Faster R-CNN, Mask R-CNN | _planned_ |

Rule for this repo: the training loop (forward → loss → `backward()` → `step()`) is always written by hand, and every notebook changes at least one thing (learning rate, a layer, an activation) and records what happened.
