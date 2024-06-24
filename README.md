# Usefulness of data flow diagrams and large language models for security threat validation: a registered report
This repository contains the data used to execute a pilot control experiment to measure the effectiveness of LLMs to validate security threats. The experiment was conducted with MSC students enrolled in a computer science program

### How to Cite us
The scientific article describing design, execution, and main results of this study is available here.
If this study is helping your research, consider to cite it is as follows, thanks!

@article{,

  title={},
  
  author={},
  
  journal={},
  
  volume={},
  
  pages={},
  
  year={},
  
  publisher={}
}

### General overview
Several steps were followed in it's execution. 
First we prepared all textual materials. This included choosing relevant but comparable scenarios. To this end, we presented a kubernetes and a GitHub scenario, randomly. To further make the student's background knowledge comparable , for the subjects relevant to this study (security and the domains of the selected scenarios), we developed training videos.
From the scenarios, we compiled 10 threats, each containing a unique threat ID, threat description, assumption, affected data flow diagram (DFD) components, and an associated STRIDE threat type. 5 of the threats were real and 5 were fabricated.


To measure which additional anaysiss materials are necessary t effectively and efficiently validate threats, we defined two intervention, prescence of a data flow diagram (of the scenarios) as part of the handout material, and tasked to assess the correctness of security threats with a Large Language Model


In addition, we defined for treatment groups;
  1) LLM + DFD (A) receives the scenario descriptions with an accompanying data flow diagram instance and tasked with assessing the applicability of threats using an LLM
  2) noLLM + DFD (B) receives the scenario descriptions with an accompanying data flow diagram instance and tasked with self-assessing the applicability of threats
  3) LLM + noDFD (C) receives the scenario description without an accompanying data flow diagram instance and tasked with assessing the applicability of threats using an LLM
  4) noLLM + noDFD (D) receives the scenario description without an accompanying data flow diagram instance and tasked with self-assessing the applicability of threats

### The Task
From the list of threats, the participants were required to identify/choose the actual threats (either with the help of an LLM or self-assess).


### Available material for replication
To aide in the replication, we have made available the following materials;
1. Scenario descriptions, with a sequence diagram and a data flow diagram
2. List of threats, one from the Kubernetes scenario and one from the GitHub scenario
3. Sample entry questionnaire
4. Sample experiment survey
5. python notebook (to be updated once we have replicated it with practitioners)

## How to cite us
To be updated




## Repository Structure
This is the root directory of the repository. The directory is structured as follows:

    template-replication-package
     .
     |--- data/                            Contains sample survey flow, both entry questionnaire and actual study. All identifiable information has been removed.
     |
     |--- documentation/                   Contains the scenario description for each experiement, and the list of threats adopted from each scenario.
     |
     |--- src/                             WIll contain the python files used to analyse and report the results 
    
    
     
                         
  



