# Multimodal-Question-Answering-System-for-Elderly-Care-and-Companionship

## Introduction
With the increasing number of the elderly in the society, the care and medical treatment of the elderly have become an important concern of the society, and the assessment and training of the cognitive function of the elderly have become a major difficulty and pain point in the aspect of old-age care and medical care. This system is based on the detailed cognitive function evaluation criteria (simple mental state checklist) to understand and evaluate the cognitive function of the elderly through the form of question and answer, and feedback the results to the medical staff to provide a basis for them to make accurate diagnosis and formulate effective treatment plans. At the same time, based on the multi-modal database ScienceQA and FairyTaleQA, the system provides cognitive function training modules for the elderly. By answering the questions raised by the system and conducting multiple rounds of dialogue with the system, the cognitive function of the elderly can be effectively trained and the disease of cognitive impairment can be prevented. In addition, considering the emotional needs of the elderly, the system designed the emotional dialogue module. This module can accompany the elderly to have a conversation, provide leisure entertainment and recreation, and help the elderly to relieve emotional stress and loneliness. In addition, this module can provide health advice and reminders according to the elderly's self-reported diet, exercise, medication, etc., to help the elderly maintain healthy and good living habits.In particular, in the section of cognitive assessment, we designed kernel attention based multi-modal transformer.

### kernel attention based multi-modal transformer(KAMM)
![KAMM](https://github.com/hajkeoadf/Multimodal-Question-Answering-System-for-Elderly-Care-and-Companionship/blob/main/images/KAMM.jpg)
Based on a transformer architecture, KAMM maps images and text into feature Spaces for feature fusion in this dimension. Also, KAMM uses the nuclear attention mechanism. Compared with the self-attention mechanism, it greatly reduces the number of parameters, which is suitable for the situation of small amount of data in medical scenarios, and can effectively improve the robustness of the model.

## Setup
> pip install -r requirements.txt

## Dataset & API
- [ScienceQA](https://github.com/lupantech/ScienceQA)
- [FairytaleQA](https://github.com/WorkInTheDark/FairytaleQA_QAG_System)
- [ERNIE](https://github.com/PaddlePaddle/ERNIE)

## Demo
![demoShow](https://github.com/hajkeoadf/Multimodal-Question-Answering-System-for-Elderly-Care-and-Companionship/blob/main/images/demoShow.png)
For more details, please click [demo](https://github.com/hajkeoadf/Multimodal-Question-Answering-System-for-Elderly-Care-and-Companionship/blob/main/demo.mp4) to check.
