
Setup instructions for Anaconda users:

  1. Create a new environment with most of the necessary packages:

        conda create --name CycleGAN python=3.7 --file requirements_gpu.txt

      or, if you do not have a suitable NVidia GPU

        conda create --name CycleGAN python=3.7 --file requirements_nogpu.txt

  2. Activate environment:

        conda activate CycleGAN

      or

        source activate CycleGAN

  3. Install the keras-contrib package through pip:

        pip install git+https://www.github.com/keras-team/keras-contrib.git

  4. Code is ready to run! You can either run the Jupyter notebook (includes explanations, recommended) or run it directly from the terminal:

        jupyter notebook

      or

        python CycleGAN.py
