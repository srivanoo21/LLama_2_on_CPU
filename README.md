# LLama_2_on_CPU

# How to run ?

### Step 1:

clone the repository

'''bash
git clone https://github.com/srivanoo21/LLama_2_on_CPU.git
'''

### Step 2:

Create a virtual environment

'''bash
conda create -n cpullama python==3.8 -y
'''

'''bash
conda activate cpullama
'''

'''bash
pip install -r -requirements.txt
'''

### Download the quantize model from the link provided in model folder & keep the model in the model directory:

'''ini
## Download the Llama 2 model:

llama-2-7b-chat.Q4_0.gguf.bin

## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGUF/resolve/main/llama-2-7b-chat.Q4_0.gguf?download=true
'''


