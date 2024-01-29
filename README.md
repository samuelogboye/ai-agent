# Educational Agent Workflow

This Python script demonstrates an innovative agent workflow using the CrewAI framework for generating educational content on a specific topic. The workflow involves three agents: Researcher, Writer, and Examiner. Each agent plays a distinct role in creating a comprehensive and engaging educational experience.

## Agents

### 1. Researcher

- **Role:** Researcher
- **Goal:** Generate innovative ideas for teaching someone new to the subject
- **Backstory:** An imaginative expert in the field, the Researcher thrives on creativity and innovation, aiming to redefine how complex topics are introduced to beginners.
- **Interaction:** The Researcher can interact with prompts to dynamically generate innovative ideas.

### 2. Writer

- **Role:** Writer
- **Goal:** Craft a dynamic and immersive piece of text to explain the chosen topic
- **Backstory:** A storyteller at heart, the Writer's task is to transform the innovative ideas generated by the Researcher into a captivating narrative that engages and educates.
- **Interaction:** The Writer can interact with prompts to dynamically create engaging and immersive content.

### 3. Examiner

- **Role:** Examiner
- **Goal:** Generate dynamic and adaptive test questions with varying difficulty levels
- **Backstory:** With a focus on personalized assessment, the Examiner's role is to create dynamic test questions that adapt to the learner’s progress, ensuring a tailored and effective evaluation.
- **Interaction:** The Examiner can interact with prompts to dynamically generate adaptive test questions.

## Tasks

1. **Research Task:**

   - Description: Generate innovative ideas for teaching someone new to the subject
   - Assigned Agent: Researcher

2. **Write Task:**

   - Description: Craft a dynamic and immersive piece of text to explain the chosen topic using innovative ideas
   - Assigned Agent: Writer

3. **Exam Task:**
   - Description: Generate dynamic and adaptive test questions with varying difficulty levels
   - Assigned Agent: Examiner

## Workflow

The educational agent workflow follows a sequential process:

1. The Researcher generates innovative ideas for teaching the subject.
2. The Writer transforms the innovative ideas into a dynamic and immersive piece of text.
3. The Examiner creates dynamic and adaptive test questions based on the written content.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Install required dependencies: `pip install -r requirements.txt`

### Usage

1. Set up the Ollama model by providing the appropriate API key or local model configuration.

```bash
ollama run  openhermes
```

2. Run the script: `python main.py`

## Contributing

Contributions are welcome! If you have ideas for improvements or encounter any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
