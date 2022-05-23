# fastai-setup

    1. Install Anaconda
        1. https://docs.fast.ai/
            1. conda install -c fastchan fastai anaconda
    2. Update Nvidia Driver
        1. https://www.linuxcapable.com/how-to-install-and-upgrade-nvidia-drivers-on-ubuntu-20-04/
            1. ubuntu-drivers devices
            2. sudo ubuntu-drivers autoinstall
    3. Install fastbook library
        1. pip install -Uqq fastbook
    4. Ampere – Cuda capability sm_86
        1. https://discuss.pytorch.org/t/need-help-trouble-with-cuda-capability-sm-86/120235/20
        2. https://pytorch.org/get-started/locally/
            1. TORCH_CUDA_ARCH_LIST=“8.6” conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
    5. solve graphicviz gv issue
        1. https://forums.fast.ai/t/missing-graphviz-please-run-conda-install-fastbook/77260
            1. sudo apt install graphviz
