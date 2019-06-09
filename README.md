# Real World Reinforcement Learning Workshop

### ICML 2019
[ICML session page](https://icml.cc/ExpoConferences/2019/schedule?workshop_id=1)  
Sunday June 9, 2019  
2PM - 6:30PM  
Room 104  

## Abstract
Microsoft recently announced the Azure Cognitive Service, Personalizer, aimed at democratizing real world reinforcement learning for context personalization. Its goal is to make reinforcement learning accessible to everyone, not just machine learning experts. Personalizer is the result of a successful partnership between Microsoft Research and Azure Cognitive Services aimed at rapid technology transfer and innovation.

In this workshop you will learn the theory behind contextual bandits and how this applies to content personalization. We will walk you through setting up the service, writing your first application, and optimizing the policy using offline optimization.

## Schedule

<table>
  <tr>
    <td>2PM - 3PM</td>
    <td>Introduction to reinforcement learning and contextual bandits <a href="https://aka.ms/icml2019-rl-slides">(Slides)</a></td>
  </tr>
  <tr>
    <td>3PM - 3:30PM</td>
    <td>Overview of Azure Cognitive Services Personalizer <a href="https://aka.ms/icml2019-personalizer-slides">(Slides)</a></td>
  </tr>
  <tr>
    <td>3:30PM - 4PM</td>
    <td><span style="font-style:italic">Break</span></td>
  </tr>
  <tr>
    <td>4PM - 5:30PM</td>
    <td>Hands on: Setting up SDK and writing first application <a href="https://aka.ms/icml2019-demo-slides">(Slides)</a></td>
  </tr>
  <tr>
    <td>5:30PM - 6PM</td>
    <td>Hands on: Counterfactual evaluation and offline policy optimization</td>
  </tr>
  <tr>
    <td>6PM - 6:30PM</td>
    <td>Wrap-up and Q&amp;A</td>
  </tr>
</table>

## Workshop Instructions
1. [Create free Azure/Microsoft account](https://azure.microsoft.com/en-us/free/)
2. Provision free instance of Personalizer
    1. Go to [Azure Portal](https://portal.azure.com)
    2. Search for "Cogitive Services"
    3. On Cognitive Services page click "Add"
    4. Search for "Personalizer (Preview)" and click "Create"
3. Install Python Client
    1. [Download client wheel package](https://icmldemo.blob.core.windows.net/dependencies/azure_cognitiveservices_personalizer-0.2.0-py2.py3-none-any.whl?sp=r&st=2019-06-07T15:25:36Z&se=2019-06-16T23:25:36Z&spr=https&sv=2018-03-28&sig=ONuq1MVNAj0x5nl89pZjz3H6k3wrky21rii3ZNTtFyY%3D&sr=b)
    2. ```pip install azure_cognitiveservices_personalizer-0.2.0-py2.py3-none-any.whl```
3. Paste your endpoint into [line 34 of ./demo/demo.py](https://github.com/VowpalWabbit/icml2019/blob/master/demo/demo.py#L34)
4. Paste your key into [line 35 of ./demo/demo.py](https://github.com/VowpalWabbit/icml2019/blob/master/demo/demo.py#L35)
5. run `python ./demo/demo.py`

## Next steps
- [Personalizer](https://azure.microsoft.com/en-us/services/cognitive-services/personalizer/)
- [Personalizer docs](https://docs.microsoft.com/en-us/azure/cognitive-services/personalizer/)
- How can personalization be integrated into what you work on day to day?

## Presenters
- John Langford
- Rodrigo Kumpera
- Alexey Taymanov
- Cheng Tan
