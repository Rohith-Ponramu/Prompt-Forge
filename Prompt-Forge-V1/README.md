# Introduction

Prompt Forge V1 is a prompt engineering framework designed to transform vague, incomplete, unstructured, or conflicting user requests into precise, structured, and reusable prompts.

It acts as a Prompt Conversion Engine and Prompt Architect, analyzing your requirements, identifying missing information, selecting appropriate prompting frameworks, and refining your instructions into execution-ready prompts compatible with different AI models and platforms.

### How to Use

Wrap your original request inside the `<up>` and `</up>` tags when submitting it in your Prompt Forge V1 ChatGPT Project.

Prompt Forge V1 will either ask targeted clarification questions when essential information is missing or generate a refined prompt that you can copy and use with your preferred AI model.

**The goal:** Turn ordinary instructions into clear, effective prompts that improve task execution, reduce ambiguity, and produce more consistent AI outputs.

## Getting Started

Prompt Forge V1 runs through ChatGPT Projects. Follow the steps below to set it up and start using it.

### Prerequisites

- A ChatGPT account with access to Projects.
- The Prompt Forge V1 system prompt from this repository.

### Installation & Setup

#### Step 1: Open ChatGPT

Visit [ChatGPT](https://chatgpt.com/) and sign in to your account.

#### Step 2: Create a New Project

1. In the ChatGPT sidebar, click **New project**.
2. Enter `Prompt Forge V1` as the project name.
3. Select an icon and color if desired.

#### Step 3: Configure Project Instructions

1. Open your newly created project.
2. Click the three-dot menu (`...`) in the top-right corner.
3. Select **Project settings**.
4. Locate the **Project instructions** field.

#### Step 4: Install the Prompt Forge System Prompt

1. Open the system prompt file provided in this repository.
2. Copy the entire prompt.
3. Paste it into the Project instructions field.
4. Save your changes.

**Important:** Copy the complete system prompt without removing or modifying any instructions.

#### Step 5: Start Using Prompt Forge V1

Open a new chat inside your Prompt Forge V1 project.

Enter your request between the `<up>` and `</up>` tags:

```text
<up>
Your original prompt goes here.
</up>
```

Prompt Forge V1 will analyze your request and transform it into a structured, precise, and reusable prompt.

### Example

**Input:**

```text
<up>
I want to learn Python and get a remote job.
</up>
```

**Expected behavior:**

Prompt Forge V1 identifies the task, determines the relevant expertise and missing requirements, and either asks targeted clarification questions or generates a refined, ready-to-use prompt.

### Usage Guidelines

- Always wrap your original request in `<up>` and `</up>` tags.
- Provide relevant context, constraints, and examples when available.
- Answer clarification questions when prompted to improve the final result.
- Copy the generated refined prompt into your preferred AI model to execute the task.

For detailed information about the system, prompting frameworks, and design principles, explore the documentation in this repository.

---

**Official reference:** [Projects in ChatGPT — OpenAI Help Center](https://help.openai.com/en/articles/10169521-projects-in-chatgpt)
