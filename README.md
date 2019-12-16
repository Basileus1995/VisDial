# VisDial

Term Project for the class ESE 546: Principles of Deep Learning that involved using both textual and spatial (image) data for building an AI tool that estimated and formulated responses to human queries (a remodel and improvised building block for AI-based chatbots).

We believe that the next generation of intelligent systems will need to posses this ability to hold a dialog about visual content for a variety of applications.The purpose of this project is to suggest deep neural networks that will be enable a chatbot/AI to hold dialog with humans in conversational language about visual content.

Using the baseline LFE model given with the visdial starter challenge, with this project we discerned the impact of using alternative embeddings for the LSTM unit(s). 

Due to Colab constraints, we could only use a heavily subsampled dataset (10K out of 123K in the original MS-COCO Dataset), so our results reflect the findings on the subset. 

References: 
https://github.com/jiasenlu/visDial.pytorch
https://github.com/batra-mlp-lab/visdial-challenge-starter-pytorch
