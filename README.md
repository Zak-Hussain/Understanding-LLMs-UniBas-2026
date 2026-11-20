## Understanding-LLMs-UniBas-2026

![cover image](cover_grace.jpeg)

This course provides a conceptual foundation for understanding how modern LLMs work and how to use them effectively in research.

By [Dirk Wulff](https://www.wu.ac.at/en/bads/team/dirk-wulff) and [Zak Hussain](https://www.linkedin.com/in/zakir-a-s-hussain/)

### Schedule

09:00 AM - 09:30 AM: Welcome & Intro  
09:30 AM - 10:30 AM: Talk: Intro to LLMs  
10:30 AM - 10:45 AM: Break  
10:45 AM - 11:45 AM: Talk: Intro to Transformers  
11:45 AM - 12:30 PM: Talk & Demo: Intro Hugging Face  
12:30 PM - 02:00 PM: Lunch  
02:00 PM - 03:00 PM: Talk: Intro to Text Generation and Prompting  
03:00 PM - 03:30 PM: Demo: Chat with HuggingChat  
03:30 PM - 03:45 PM: Break  
03:45 PM - 04:30 PM: Talk: LLMs in Science  
04:30 PM - 05:15 PM: Discussion  
05:45 PM - 06:00 PM: Wrap-up  


### Resources

[Hussain, Binz, Mata, & Wulff (2024). A tutorial on open-source large language models for behavioral science. *Behavior Research Methods*, 1-24.](https://doi.org/10.3758/s13428-024-02455-8)

```
@article{hussain2024tutorial,
  title={A tutorial on open-source large language models for behavioral science},
  author={Hussain, Zak and Binz, Marcel and Mata, Rui and Wulff, Dirk U},
  journal={Behavior Research Methods},
  pages={1--24},
  year={2024},
  publisher={Springer}
}
```

[Hugging face documentation](https://huggingface.co/docs)  

[Hugging face book](https://transformersbook.com/)  

[But what is a GPT (3Blue1Brown)](https://www.youtube.com/watch?v=wjZofJX0v4M&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=5)  


### Installation Instructions

#### Hugging Face and Meta Llama License

1. Create a hugging Face account (https://huggingface.co/join).
2. Navigate to [your Hugging Face profile settings](https://huggingface.co/settings/tokens) to generate an API token (+Create new token). Set the token type to 'Read' and give it a name (e.g., 'understanding-LLMs').

#### Google Colab and GitHub Repository

4. If you do not have a Google account, you will need to create one (this can be deleted after the workshop).
5. Navigate to Google Drive (https://drive.google.com/).
6. In the top-left, click New > More > Colaboratory. If you do not see Colaboratory, you may need to click "Connect more apps",

search for 'Colaboratory', and install it. Then click New > More > Colaboratory.
7. Copy the following code snipped into the first cell of the notebook. Run it (`shift + enter` or click ► button) to mount your Google Drive to the Colab environment.
A pop-up will ask you to connect; click through the steps to connect your Google Drive to Colab (you will have to do this
every time you open a new notebook).

```
from google.colab import drive
drive.mount("/content/drive")
```

8. Create a second cell in your notebook using the "+ Code" button that appears when you hover your cursor right under the first cell. Copy and run the following code snippet in the second cell of your notebook to clone the GitHub repository to your Google Drive :

```
%cd /content/drive/MyDrive
!git clone https://github.com/Zak-Hussain/Understanding-LLMs-UniBas-2026.git
```

9. Go back to your Google Drive and navigate to the folder "Understanding-LLMs-UniBas-2026". You can then click on `hf_intro.ipynb` and start working through the notebook.

### Evaluation

Please fill out the course evaluation [here](https://evasys.unibas.ch/evasys/online.php?p=4PNX6).  

### Assignment

Research with LLMs involves many choices: which model, which prompt, which hyperparameters, and so on. As we stressed in the course, basic heuristics only get you so far. The most reliable way to choose is to test the options **in the specific context where you plan to use them**. For example, if you are automating a literature review and can't decide between Model A and Model B, run both and compare their accuracy against a ground truth (or a proxy for it, such as human expert labels).

**Task:** Pick a research problem and compare at least two LLM-based approaches to it. You might vary the model, the prompt, the temperature, or something else.

**Deliverable:** A research report of at most 2 pages that covers:

1. **Problem:** what you are trying to do and why it matters.
2. **Methods:** the approaches you compared, your data, and how you measured performance.
3. **Results:** how the approaches performed (a table or figure is encouraged). Go beyond point estimates such as raw accuracy: report inferential statistics (e.g., confidence intervals, bootstrapped standard errors, or a significance test) so readers can judge whether the differences between approaches are reliable.
4. **Limitations:** what might weaken your conclusions.

**Please submit the assignment to Zak (zakir.a.s.hussain at gmail dot com) by December 11th, 2026** 



