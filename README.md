# FRESH_PICKER

# Quality and Storage Monitoring with Reminders _inteloneAPI

## Description
 Embrace the innovation in product assessment with FreshPicker, where technology enhances freshness. Our groundbreaking application redefines the way you interact with fruits and vegetables, providing instant quality evaluations and freshness insights right at your fingertips. With our intuitive scan-and-identify feature, discover the health of your product through a simple upload click. Dive into a repository of preservation techniques and delicious recipes curated by our AI, tailored to the specific needs of your fruits and vegetables.

## Demonstration of the Project video 


https://github.com/vishnu2909200/FRESH_PICKER/assets/100519914/aca809f5-2b05-423c-b30f-dd0ab5ce6a2e

full video link : 
       https://drive.google.com/file/d/156RaviJJDthiDN4X2yP06RkW05hM2ltK/view?usp=sharing


## Execution Command

1.file directory


    /streamlit webapp
          ├── app.py             <-- main script
          └── streamlit environment   #mandatory create streamlitenv  
          └── models
                 └── xgmodel_without1api_job.pk1
                 └──100GPT
                    └── added_tokens.json
                    └── config.json
                    └── generation_config.json
                    └── merges.txt
                    └── special_tokens_map.json
                    └── tokenizer.json
                    └── tokenizer_config.json
                    └── training_args.bin
                    └── vocab.json
                    └── model.safetensors  # that is a large file so i have shared my drive link.
                
                   
                    
          

2.Install required packages into streamlit environment

3.Using this command to run our webapp
            
            "streamlit run app.py"

**Dataset Drive link**

            https://drive.google.com/drive/folders/18YIJhz7DfPHTS9pOgLojFKHWAWoMa4FE?usp=sharing


 **Some trained models and Dataset are too large. So, here I have shared my drive link .You can refer and download it.**

            https://drive.google.com/drive/folders/1kR-l7_63u6LWxUhMsXbFY43ik3hv3Sgu?usp=sharing

----------------------------------------------------------------------------------------------------------------------------------
## Problem Statement :
In the realm of food consumption, consumers struggle with assessing the freshness
and quality of fruits and vegetables, leading to wastage and sustainability setbacks.The lack of
efficient monitoring methods hampers inventory management, complicating the issue
further.Thus, there’s a growing need for an innovative solution, integrating Intel oneAPI toolkit
that provides reliable freshness detection and quality evaluation for fruits and vegetables,
empowering consumers to make informed decisions and reduce waste.

## Solution:
Our solution is a revolutionary web application designed to streamline the process of
assessing fruits and vegetable quality and freshness. Leveraging technologies such as the Intel
oneAPI toolkit and advanced image recognition algorithms, our application aims to transform
how consumers interact with products. Key features include:
+ Automated evaluation of scanned fruits and vegetables quality and freshness using
advanced image recognition and AI.
+ Personalized recommendations on product quality, including ripeness, freshness, and
condition, are provided.
+ The option to upload images for analysis ensures accuracy and flexibility in assessing a
wide range of products.
+ Interactive chatbot provides curated recipes and storage guidance tailored to scanned
products.
+ Effortless inventory management allows users to receive proactive reminders when
items are nearing expiration, minimizing food waste.

## Intel oneAPI Integration:
1. Intel oneAPI Deep Neural Networks Library(one DNN)
   
    i) Intel Extension for TensorFlow
   
   ii) Intel Extension for Pytorch


# Demonstration of the Project

![WhatsApp Image 2024-04-05 at 11 34 38 PM](https://github.com/vishnu2909200/FRESH_PICKER/assets/100519914/de9f58ca-0a7d-4b2e-b9b7-ac869612a166)





            

## FreshPicker - Two Models
**1.Fruit and Vegetable quality prediction:**

This model represents a significant advancement in product evaluation,
leveraging Intel Extension for TensorFlow to redefine how we assess the freshness and
quality of fruits and vegetables. Notably, running this code in Google Colab exceeded 30
minutes, but leveraging Intel's GPU ensures completion in less than a minute. 

**2.Recipe Generator:**

This model represents a leap forward in culinary innovation,
harnessing the power of GPT and Intel Extension for PyTorch. This groundbreaking
model redefines culinary creativity by generating personalized recipes based on your
ingredients. Leveraging the cutting-edge capabilities of GPT and Intel's technology, our
model ensures seamless recipe generation. The process involves installing essential
dependencies, fine-tuning GPT with a custom dataset, and configuring the model for
recipe generation. 

## Usage of Intel Developer Cloud:

Utilizing the resources provided by Intel Developer Cloud has significantly
expedited our fruit quality prediction model's development and deployment processes.
Specifically, we harnessed the power of Intel's GPU through Intel Extension for
TensorFlow to accelerate critical components of our project: Fruits and Vegetables
Quality Prediction.

1.**Fruits and vegetables Quality Prediction Model Training:**
The Intel Developer Cloud's GPU capabilities, combined with Intel Extension for TensorFlow, played a crucial role in
reducing the training time of our Fruit Detection model. Leveraging Intel's
high-performance computing infrastructure, we achieved more efficient model training,
significantly cutting down the time required for optimization and experimentation.Notably,
a single epoch now takes only 2 seconds, a substantial improvement compared to other
environments, showcasing the remarkable speedup achieved with Intel's hardware
resources and optimized software stack.




2.**Recipe Generation Model:**
Leveraging Intel Extension for PyTorch, our recipe generator
model benefits from the accelerated development and deployment processes facilitated
by Intel Developer Cloud. By harnessing Intel's GPU capabilities, we've significantly
reduced training times, ensuring efficient model optimization and experimentation. This
collaborative approach has led to remarkable speedups, enhancing the overall
performance of our Recipe Generation model and streamlining the culinary creativity
process.


# Inference

### Accuracy

There is no difference in accuracy
>Comparison between Accuracy in Intel Developers Cloud using OneDNN and Google Colab

![ACCURACY -quality prediction model](https://github.com/vishnu2909200/FRESH_PICKER/assets/100519914/0135e156-aed6-40ca-94a7-9825051adefa)

### Training Time

1.For Quality prediction model, the training time is reduced to **73%** by leveraging Intel libraries


2.LLM based Chatbot(recipe bot)  which is trained using Intel library has been reduced **99%**

>Comparison between time took in Intel Developers Cloud using OneDNN and Google Colab

![intel](https://github.com/vishnu2909200/FRESH_PICKER/assets/100519914/648801b5-88f6-4199-965e-bdc33ed1a0e4)

## What it Does

Our innovative application redefines the way users interact with fruits and
vegetables, offering a comprehensive suite of features for freshness detection, storage
management, recipe generation, and more. Here's an overview of its key functionalities:

**1.Freshness Quality Detection:**
Users can effortlessly assess the quality of fruits and vegetables by simply scanning
them by uploading images. The application employs advanced image recognition
algorithms to analyze the scanned product and provide its freshness status.This
real-time assessment empowers users to make informed decisions and ensuring they
only consume the freshest ingredients.

**2.Smart Storage Management and Notification System:**
Upon storing fruits and vegetables in the application, users receive personalized storage
suggestions tailored to each item's specific requirements. The web app's intelligent
notification system sends timely alerts ,when stored product is approaching expiration
or showing signs of spoilage.

**3.Recipe Generation and Ingredient Management:**
Users have the option to generate recipes based on the ingredients they have on hand,
making meal planning and preparation a breeze. The application's recipe generator
analyzes user-provided ingredients and suggests delicious recipe options that utilize
those items.

**4.User-Friendly Interface and Seamless Integration:**
Our application boasts a user-friendly interface that prioritizes simplicity and ease of use, allowing users to
navigate effortlessly and access features with minimal effort.
