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
    <td>Introduction to reinforcement learning and contextual bandits</td>
  </tr>
  <tr>
    <td>3PM - 4PM</td>
    <td>Overview of Azure Cognitive Services Personalizer</td>
  </tr>
  <tr>
    <td>4PM - 4:30PM</td>
    <td><span style="font-style:italic">Break</span></td>
  </tr>
  <tr>
    <td>4:30PM - 5:30PM</td>
    <td>Hands on: Setting up SDK and writing first application</td>
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

## Preparation
- [Create free Azure/Microsoft account](https://azure.microsoft.com/en-us/free/)
- [Install Visual Studio 2019](https://visualstudio.microsoft.com/downloads/)
- Provision free instance of Personalizer

## Workshop instructions
- [Download client wheel package](https://icmldemo.blob.core.windows.net/dependencies/azure_cognitiveservices_personalizer-0.2.0-py2.py3-none-any.whl?sp=r&st=2019-06-07T15:25:36Z&se=2019-06-16T23:25:36Z&spr=https&sv=2018-03-28&sig=ONuq1MVNAj0x5nl89pZjz3H6k3wrky21rii3ZNTtFyY%3D&sr=b)
- ```pip install azure_cognitiveservices_personalizer-0.2.0-py2.py3-none-any.whl```
- ```python demo.py```

## Next steps
- [Personalizer](https://azure.microsoft.com/en-us/services/cognitive-services/personalizer/)
- [Personalizer docs](https://docs.microsoft.com/en-us/azure/cognitive-services/personalizer/)
- How can personalization be integrated into what you work on day to day?

## Presenters
- John Langford
- Rodrigo Kumpera
