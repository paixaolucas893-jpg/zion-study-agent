# Zion Study Agent

> A multimodal AI learning assistant that transforms study materials into personalized learning experiences.

Zion Study Agent is an educational AI project developed under **Zion AI Lab** for the **Lablab x AMD AI Academy Challenge**.

The project explores how multimodal artificial intelligence, OCR, language models, and intelligent agents can help students understand academic materials, practice more effectively, and receive personalized feedback.

## The Problem

Students often work with information scattered across PDFs, lecture notes, exercise lists, screenshots, textbooks, and previous exams.

Traditional AI chat interfaces can answer individual questions, but they often lack continuity, structured learning progression, and awareness of a student's recurring difficulties.

Zion Study Agent aims to bridge this gap.

## The Solution

The goal is to build an intelligent study agent capable of receiving academic materials and transforming them into an interactive learning process.

The system is designed to:

- Analyze PDFs, notes, exercise sheets, and images.
- Extract text from photographed or scanned materials using OCR.
- Identify subjects, concepts, and exercises.
- Explain concepts step by step.
- Generate exercises based on the uploaded material.
- Evaluate student responses.
- Provide progressive hints instead of immediately revealing answers.
- Identify recurring difficulties.
- Adapt future exercises to the student's performance.
- Maintain learning context throughout a study session.

## Example Workflow

1. A student uploads an image of an exam or exercise list.
2. OCR and vision components extract and interpret the content.
3. Zion Study Agent identifies the relevant concepts.
4. The agent explains the subject when necessary.
5. The student solves an exercise.
6. The agent evaluates the response.
7. Instead of simply providing the answer, it can offer progressive hints.
8. The system records areas of difficulty.
9. New exercises can be generated according to the student's current level.

## Planned Architecture

```text
Student
   |
   v
Web Application
   |
   +-------------------+
   |                   |
   v                   v
Document Input      Image Input
PDF / Notes         Exams / Exercises
   |                   |
   +---------+---------+
             |
             v
      OCR / Vision Layer
             |
             v
      Content Processing
             |
             v
        AI Study Agent
      /       |        \
     /        |         \
Explanation  Practice   Feedback
     \        |         /
      \       |        /
       Student Context
             |
             v
      Adaptive Learning
```

## Technologies

The project is being designed around technologies relevant to the AMD AI Academy ecosystem.

Planned and experimental technologies include:

- AMD Developer Cloud
- AMD ROCm
- Hugging Face
- Llama models
- LangChain
- EasyOCR
- Multimodal AI models
- Generative / agent-based AI workflows
- REST APIs
- Modern web technologies

The final technology stack will reflect only components actually implemented and tested in the project.

## AMD AI Academy

One of the technical goals of Zion Study Agent is to explore AI workloads using **AMD-compatible infrastructure**.

Possible workloads include:

- OCR inference
- Document processing
- Vision-language inference
- Embedding generation
- Language model inference
- Educational agent workflows

The implementation will evolve throughout the AMD AI Academy Challenge as the infrastructure and mini-challenges are explored.

## Project Status

**Current stage: Early prototype / development**

Current focus:

- [ ] Define initial architecture
- [ ] Build web interface
- [ ] Implement document upload
- [ ] Implement image upload
- [ ] Add OCR pipeline
- [ ] Add academic-content extraction
- [ ] Implement study-agent workflow
- [ ] Add exercise generation
- [ ] Add answer evaluation
- [ ] Add progressive hints
- [ ] Add student learning context
- [ ] Experiment with AMD ROCm workloads
- [ ] Deploy functional prototype
- [ ] Record project demonstration

This checklist will be updated as features are actually implemented.

## Responsible AI and Development Transparency

Zion Study Agent is being developed individually as part of Zion AI Lab.

AI-assisted tools are used during parts of the development process, including:

- Research
- Brainstorming
- Architecture exploration
- Coding assistance
- Debugging
- Documentation
- Prototyping
- Testing

AI assistance is not presented as autonomous authorship of the project. Project direction, feature selection, integration decisions, validation, implementation choices, and final submission remain the responsibility of the developer.

Generated outputs are reviewed and tested before being incorporated into the project.

## Educational Philosophy

Zion Study Agent is intended to support learning rather than simply act as an answer generator.

The project prioritizes:

**Understand → Practice → Receive Feedback → Improve**

The long-term goal is for the agent to recognize when a student needs an explanation, a hint, another example, or a more challenging exercise.

## Privacy

Educational documents may contain personal or academic information.

The project therefore aims to follow principles such as:

- Data minimization
- Purpose limitation
- Transparent AI processing
- Avoiding unnecessary storage of uploaded material
- Secure handling of user information
- User control over stored learning data

Privacy and security mechanisms will be documented as they are implemented.

## Author

Developed by **Lucas Paixão**  
Zion AI Lab

Created for the **Lablab x AMD AI Academy Challenge**.

## Development Notice

This repository is under active development.

Features, architecture, models, and infrastructure described as planned or experimental should not be interpreted as already implemented. The README will be updated continuously to distinguish completed functionality from planned functionality.
