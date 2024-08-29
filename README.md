# Fine-tuning a Stable Diffusion model of Land Grandfather in Black Myth WUKONG 

I fine-tune a stable diffusion model [CompVis/stable-diffusion-v1-4](https://huggingface.co/CompVis/stable-diffusion-v1-4) via [DreamBooth](https://arxiv.org/abs/2208.12242).

The concept I implant is the Land Grandfather(土地爷爷) in the game Black Myth WUKONG (黑神话悟空).
## Dataset
I make the training dataset via screenshots during the game. 
Here is my [dataset](https://huggingface.co/datasets/BoHu370/Land_grandfather).

![image](https://github.com/user-attachments/assets/7dc2bd39-ad85-4521-a818-880cf7d13231)

## Usage
You could just run `inference.ipynb` to get some generated samples.
The usage of my fine-tuned model could also refer to the [Huggingface model card](https://huggingface.co/BoHu370/lgd-old-man) on HuggingFace.


## Examples
Here are some generated samples using my fine-tuned model.

The trigger word of my model is `lgd`.

Prompt: a photo of lgd old man eating icecream.

![image](https://github.com/user-attachments/assets/5f566f95-75d7-4205-afae-ffa164d57435)

Prompt: a photo of lgd old man driving car.

![image](https://github.com/user-attachments/assets/04444c44-91a9-4d42-b474-0f7cf1ab2328)

Prompt: a photo of lgd old man driving a bicycle.

![image](https://github.com/user-attachments/assets/bf4c1e8b-2034-4334-be62-83b4cfe72f38)

Prompt: a photo of lgd old man playing computer game.

![image](https://github.com/user-attachments/assets/a33043be-59fa-40f8-ba16-2401fe1d9ada)
