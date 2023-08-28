# Flan-T5-Summarization
# My Dialogue Summarization Labs

Welcome to my repository for the Dialogue Summarization Labs. Here, I've created three labs that revolve around dialogue summarization using the FLAN-T5 model. Through these labs, I explore various aspects of prompt engineering, fine-tuning, and model enhancement to achieve improved dialogue summarization results. Let me provide you with a brief overview of each lab:

## Lab 1: Exploring Dialogue Summarization with FLAN-T5

In the first lab, I delved into the realm of dialogue summarization using the FLAN-T5 model. My main focus was to understand how the input text affects the output of the model. By experimenting with different prompts, I gained insights into prompt engineering and its impact on shaping the model's generative abilities. This lab involved comparing zero-shot, one-shot, and few-shot inferences, which marked the initial steps towards prompt engineering and highlighted how it can enhance the output quality of Large Language Models.

## Lab 2: Enhancing Dialogue Summarization Through Fine-Tuning

The second lab guided me through the process of fine-tuning an existing Large Language Model (LLM) from Hugging Face to achieve enhanced dialogue summarization. I worked with the FLAN-T5 model, a pre-trained model fine-tuned specifically for instruction-based tasks. This model showcased its summarization capabilities "out of the box". During this lab, I explored a comprehensive fine-tuning approach and evaluated the results using the ROUGE metric to quantify improvements. Additionally, I dabbled in Parameter Efficient Fine-Tuning (PEFT), where I observed how the benefits of PEFT outweighed minor reductions in performance metrics.

## Lab 3: Crafting Less Toxic Content with FLAN-T5 Using RLHF

Lab 3 was all about fine-tuning the FLAN-T5 model to generate content with reduced toxicity, utilizing Facebook's hate speech reward model. This reward model acted as a binary classifier, categorizing text as either "not hate" or "hate". I employed the Proximal Policy Optimization (PPO) algorithm along with Reinforcement Learning from Human Feedback (RLHF) for fine-tuning and detoxifying the model. By the end of this lab, I gained a deeper understanding of how reinforcement learning techniques, particularly RLHF, can be harnessed to steer model outputs towards desired directions.

Feel free to explore the directories for each lab to find detailed code implementations, step-by-step guides, and any additional resources. These labs were created to enhance my understanding of dialogue summarization, prompt engineering, fine-tuning strategies, and ethical considerations in language generation. I'm excited to continue learning and experimenting!

