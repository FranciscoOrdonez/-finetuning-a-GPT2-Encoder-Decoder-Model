# -finetuning-a-GPT2-Encoder-Decoder-Model
 finetuning a GPT2 Encoder Decoder Model
 
 This is a script that fine tunes a pretrained GPT2 Encoder Decoder model to generate recipe ingredients from a recipe title. This model will then be passed to other units in pipeline. The current implementation uses PyTorch. 
 
 First, you will need to install the necessary libraries, including PyTorch and transformers.
 
 Next, you need to load the pre-trained GPT-2 model and tokenizer from the transformers library.
 
 Next, you need to load your recipe dataset and preprocess it into a format that can be used for fine-tuning the GPT-2 model. In this case, you will need to provide the recipe title as the input to the model, and the recipe ingredients as the output.
 
 After loading and preprocessing the data, you can fine-tune the GPT-2 model using the input-output pairs.
 
 Finally, you can use the fine-tuned GPT-2 model to generate recipe ingredients from a recipe title.
 
To check coding view  [here](coding)
 
 
 
