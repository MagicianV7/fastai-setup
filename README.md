# fastai-setup

    1. Install Anaconda
        1. https://docs.fast.ai/
            1. Anaconda install
                1. conda install -c fastchan fastai anaconda
            2. Miniconda install
                1. conda install -c fastchan fastai
    2. Update Nvidia Driver 
        (Linux)
        1. https://www.linuxcapable.com/how-to-install-and-upgrade-nvidia-drivers-on-ubuntu-20-04/
            1. ubuntu-drivers devices
            2. sudo ubuntu-drivers autoinstall
    3. Install fastbook library
        1. pip install -Uqq fastbook
    4. Ampere – Cuda capability sm_86 
        (Linux)
        1. https://discuss.pytorch.org/t/need-help-trouble-with-cuda-capability-sm-86/120235/20
        2. https://pytorch.org/get-started/locally/
            1. TORCH_CUDA_ARCH_LIST=“8.6” conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
        (Windows)
        1. https://developer.nvidia.com/cuda-toolkit
            1. Download and instal cuda-toolkit
        2. https://pytorch.org/get-started/locally/
            1. conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
    5. solve graphicviz gv issue
        1. https://forums.fast.ai/t/missing-graphviz-please-run-conda-install-fastbook/77260
            1. sudo apt install graphviz
    6. Install nbdev for Jupyter notebook better documentation 
        1. pip install nbdev
    7. Install following if Jupyter notebook doesn't see your environment 
        1. conda install nb_conda_kernels
