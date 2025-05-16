Voice-Controlled LLM-Drone

This project demonstrates a fully automated voice-controlled drone interface powered by Large Language Models (LLMs). By integrating advanced AI models, the drone is able to interpret and execute natural language voice commands through a streamlined processing pipeline.
Pipeline Overview

    Speech Recognition – OpenAI Whisper
    Converts spoken commands into raw text using Whisper’s robust speech-to-text capabilities.

    Text Refinement – Flan-T5 (Transformers)
    The transcribed text is refined using Google's Flan-T5 model to ensure clarity and precision in the drone command, which is critical for safe and accurate operation.

    Code Generation – GPT-4o
    The cleaned instruction is passed to GPT-4o, which generates a complete MAVSDK Python script based on the command.

    Drone Control (MAVSDK)
    The generated Python script is used to control the drone, enabling it to perform tasks such as directional movement, altitude adjustment, and other predefined actions.

Key Features

    End-to-end integration of speech, natural language understanding, and drone automation

    Practical use of transformer models and GPT for real-world robotics

    Modular and extensible pipeline with clearly defined stages

    Demonstrates how LLMs can be applied to human-robot interaction
