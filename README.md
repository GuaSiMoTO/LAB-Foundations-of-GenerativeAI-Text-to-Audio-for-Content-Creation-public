![](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)
# LAB-Foundations-of-GenerativeAI-Text-to-Audio-for-Content-Creation
## Introduction
In this lab, students will work with pre-trained text-to-audio models such as **Tacotron 2** and **WaveNet**, available through Hugging Face, to explore their applications in content creation. The goal is for students to understand how these models work and learn to apply them in real-world projects without needing to build models from scratch.

Students will:
1. Use pre-trained text-to-audio models.
2. Implement text-to-audio conversion tasks using these models.
3. Evaluate the models’ performance and their real-world applications.
4. Analyze how text-to-audio models are impacting creative industries.

## Initial Setup

### Requirements
Start by forking the provided GitHub repository to your account and then clone it locally. This will be your workspace for completing the lab exercises.

- [Learn how to fork this repo](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)
- Clone this repo into your code/labs folder.

```bash
git clone https://github.com/codeskills-ai/LAB-Foundations-of-GenerativeAI-Text-to-Audio-for-Content-Creation.git
cd LAB-Foundations-of-GenerativeAI-Text-to-Audio-for-Content-Creation
```

### Setup Instructions

Create a virtual environment and install the required packages:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Once your environment is ready, you're all set to dive into the exercises.

---

## Iteration 1: Exploring gTTS for Text-to-Speech Conversion

**Model**: **gTTS** (Google Text-to-Speech), a pre-trained model for text-to-speech conversion.

**Task**: Convert the text "Artificial intelligence is transforming content creation" into an audio file using gTTS.

**Analysis**: Play the generated audio file and evaluate the quality of the text-to-speech conversion, considering aspects like clarity and naturalness.

---

## Iteration 2: Professional Customization of gTTS in Enterprise Environments

**Task**: Create a function that allows users just by executing the .py file to play a text, and adapt the use of gTTS for professional contexts such as presentations, tutorials, podcasts or virtual assistants:

- **lang** (language)

- **slow** (speech rate)


**Practical Application:** Use gTTS for one of these cases:

- Narrate short tech news articles.

- Create voiceovers for corporate videos or internal training material.

- Automate virtual assistant messages and guided tutorials.

**Analysis:** Make a written comparison of how voice parameter customization improves the user experience and professional perception of the content.

---

## Iteration 3: Creating Multi-Language Content with gTTS

**Task**: Use gTTS to convert text into different languages and accents. Choose a paragraph in English and translate it into other languages such as Spanish, French, or German. Add an input field where users can type the text they want to convert into speech. This text will be passed to the gTTS model to generate audio output. Additionally, allow users to select different accents (such as 'com', 'co.uk', 'com.au', etc.) to hear how the pronunciation changes based on the selected accent for the same language.

**Objective**: Explore gTTS’s ability to generate multilingual content, which is useful for global companies or multilingual support.

**Analysis**: Discuss how this capability can be applied in real-world scenarios like international customer support, global marketing, or multilingual presentations.

---


## Iteration 4: Generating Background Music for Narration with MusicGen

**Model**: **MusicGen**, a model designed for music generation.

**Task**: Using MusicGen, generate a 5-second instrumental background music piece that is soft and relaxing to accompany the narration of an article or presentation.

**Context**: The generated music should be suitable for use as background music in multimedia content projects such as presentation videos, narrated articles, or podcasts. The goal is for the music to complement the narration harmoniously without distracting the listener, enhancing the overall professional quality.

**Analysis**: Discuss how the generated music can improve user experience in multimedia projects and how it can be adjusted for different contexts (e.g., news narration, podcasts, promotional videos).

---

## Iteration 5: Ethical and Professional Considerations in TTS

**Task**: Analyze the ethical challenges related to the use of text-to-speech technology in professional environments, such as voice replication, privacy, and copyright issues.

**Practical Application**: Research how companies like Google, Amazon, and Microsoft use TTS models in virtual assistants and consumer products.

---

## Bonus Exercise

In this exercise, you will fine-tune and combine text generation and speech synthesis models to create a virtual assistant. Follow these steps:

1. **Choose a Text-to-Text Model:** Select a text generation model of your choice (e.g., GPT-2, T5, or any other transformer-based model). Use this model to generate a text response based on user input.
   
2. **Convert Text to Speech:** Use the `gTTS` library to convert predefined text into speech. Understand how this text-to-speech model operates and how to save and play the generated audio.

3. **Integrate Both Tasks:** Combine the two tasks—first, generate a text response using GPT-2, and then convert this generated text into speech using `gTTS`.

4. **Personalize Your Virtual Assistant:** Extend the functionality of the assistant by allowing users to input custom prompts and receive voice responses, simulating a real-world virtual assistant.

---


## Additional Resources

- [TTS Documentation](https://pypi.org/project/TTS/)

## Submission

Once you have completed the lab, push your Jupyter notebook to your forked GitHub repository and create a pull request.

```bash
$ git add .
$ git commit -m "completed lab"
$ git push origin main
```

![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)
