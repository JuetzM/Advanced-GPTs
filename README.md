<div align="center">
  <h1>Advanced Workflow GPTs <i>by Nerority</i></h1>
  <h3><i>Showcase of my Custom GPTs, featuring advanced workflows and operational logic.</i></h3>
  <img src="https://skillicons.dev/icons?i=react,vite,ts" alt="Icons" />
  <br/>
  <a href="https://nerority.com"><kbd>🟢 Website</kbd></a>
  <a href="https://www.linkedin.com/in/devin-pellegrino-gt/"><kbd>🔵 LinkedIn </kbd></a>
</div>

</br>

> **I will be preparing public versions of all GPTs for the store release next week for free. This page will see constant updates over the weekend and links will be live here by Monday (1/08/24).**

> **Status: 8/10 GPTs Ready for Deployment. Finalized GPTs have been greatly augmented and refined for public use.**

---

![Nerority](https://github.com/nerority/Advanced-GPTs/assets/80237923/e99891a8-9645-4e9b-a22c-7fca73177882)

Hi my name is Devin. I specialize in engineering advanced generative AI workflows that leverage meta-functionality control. I have been mastering prompt engineering as a hobby for a long time now, and am able to design GPT's to do pretty much anything.

- Did you know you can perfectly control >5 minutes of AI tool chaining with >30 different tool calls in the same response, with 100% accuracy? 
- Or that you can have ChatGPT generate >10 DallE-3 Images in a single response, with perfect control?
- How about about having ChatGPT search a document with RAG, plan a tailored search strategy for that document in the python tool, execute a loop of sequentual in-depth RAG searches that synthesize their results in the python tool, plan broswer tool search queuries to align the distilled knowledge with real-time information, execute searches with the browser tool, synthesize the results in the python tool, compile all findings into a coherant report, and then present the user with the report, all in the same single response? 

Yes, that has been possible to do with ChatGPT alone. The tool timeout threshold of 60 seconds, resets with each new tool call, allowing highly complex responses if you know how.

Want me to build your dream GPT? Get in touch.

**Contact**: devinpellegrino@gmail.com

**Site**: [nerority.com](https://www.nerority.com)

<div align="center">
<h1>The Lineup</h1>
</div>

#### Quick Nav
1. [Automated Infinite Visual Progression ✔️](#automated-infinite-visual-progression-with-fine-grain-control)
2. [Automated Career Profile Builder and Resume Tailor ✔️](#automated-career-profile-builder-resume-optimizer-and-target-position-tailoring)
3. [Automated High-Quality Document Analysis ✔️](#automated-high-quality-document-analysis)
4. [Automated DALL-E Prompt Variation Testing ✔️](#automated-dall-e-prompt-variation-testing)
5. [Advanced Meta-Prompt Engineer ✔️](#advanced-meta-prompt-engineer)
6. [Automated Prompt Refinement ✔️](#automated-prompt-refinement)
7. [Business Contract Analyzer ✔️](#business-contract-analyzer)
8. [Advanced Competitive Analysis AI ✔️](#advanced-competitive-analysis-ai)
9. [Automated Knowledge Distillation 💫](#automated-knowledge-distillation)
10. [Botanical Growth Cycle Visualizer 💫](#botanical-growth-cycle-visualizer)


---

## Automated Infinite Visual Progression with Fine-Grain Control

**Status**: Finalized for Release 💯

### Description

This GPT is an exciting innovation in the world of AI-driven visual creativity. Originally born as a slight meme, it has evolved into a robust tool that allows users to embark on an endless journey of visual progression. This GPT facilitates the generation of a series of images, each evolving based on user-defined parameters, such as dimension, direction, and progression rate.

### Usage Instructions

Utilize this GPT to explore the realms of endless visual possibilities. Start by defining the base image and the desired progression parameters. The GPT will generate a series of images, each iterating on the previous one according to your specifications. This tool is perfect for artists, designers, or anyone looking to explore a dynamic visual narrative.

### User Commands

**Input Commands**

- `!executeIP [base image description, dimension, direction, starting point, rate]`: Initiates the image progression.
- `!demo`: Demonstrates the tool using an example progression.
- `!commands`: Displays a detailed command menu for user guidance.

**Control Commands**

- `!addDimension [dimension, direction, starting point, progression rate]`: Adds a new dimension to the progression.
- `!removeDimension [dimension]`: Removes an existing dimension.
- `!invertDirection [dimension]`: Inverts the progression direction in a specified dimension.
- `!adjustRate [dimension, new rate]`: Modifies the progression rate.
- `!updateBase [new base context]`: Updates the base image for subsequent progressions.
- `N`: Proceeds to the next set of five progressions.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant DallE as DALL-E

    User->>ChatGPT: Inputs Commands (e.g., !executeIP)
    ChatGPT->>DallE: Initial Image Generation
    DallE-->>ChatGPT: Initial Image
    loop Progressive Visualization Loops
        ChatGPT->>DallE: Progress Image in Specified Dimensions
        DallE-->>ChatGPT: Progressed Image
    end
    ChatGPT-->>ChatGPT: Compile Progression Status
    ChatGPT->>User: Displays Current Progression Status Menu
    ChatGPT->>User: Presents User Command Menu
    User->>ChatGPT: Inputs Next Commands
    Note over ChatGPT: Resource Management and Continuation Setup
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/c4502ac9-e05f-48af-b724-050d7fbdac8c" alt="First" width="30%" height="3000">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/0a8c0673-8018-497c-8c58-e35402c39c95" alt="Second" width="30%" height="3000">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/fcca86b4-183f-408d-85cf-830290422196" alt="Second" width="30%" height="3000">
</p>

---

## Automated Career Profile Builder, Resume Optimizer, and Target Position Tailoring

**Status**: Finalized for Release 💯

### Description

In today's highly competitive job market, standing out is more crucial than ever. This GPT, a masterpiece of my creation, tackles this challenge head-on. It's an advanced AI-driven tool that automates the intricate process of building a detailed career profile, optimizing resumes, and tailoring them for specific job roles. Leveraging the latest in AI, it analyzes market trends and job requirements, ensuring that your resume not only shines but also aligns perfectly with current market demands.

I know full well how frustrating applying for jobs can be for the average person in the current day. With the level of expected tailoring and ATS systems to deal with, it can be a full-time job and more on its own. This was intended from the start to shake things up once and for all.

Make me proud 😎

### Usage Instructions

This tool is a godsend for job seekers and professionals looking to give their careers a boost. Simply provide your career-related documents, and watch as the AI transforms them into a polished, market-aligned profile and a tailored resume. It's particularly adept at distilling complex career histories into compelling narratives that resonate with recruiters.

After the first phase is complete, you should enter `C` and allow the workflow to finish the 2nd phase. After the final resume is saved, you can use the next steps for automated quality tailoring for any position. Simply feed the description in and the comprehensive context is pre-framed for high-quality tailoring.

### User Commands

- `!start` - Initiates the advanced workflow using your uploaded career documents.
- `!demo` - Demonstrates the tool's capabilities using synthesized data.
- `C` - Resumes the workflow from the last saved checkpoint, a handy feature considering the depth of analysis involved.
- `G` - Generates the refined resume with elegant markdown formatting.
- `!tailor [job description]` - Performs tailored resume optimization based on a job description you provide. Feed the tool a job description, and it will craft a resume that speaks directly to that role's needs.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant PythonTool as Python Tool
    participant RAG as RAG Search
    participant Browser as Browser Tool

    User->>ChatGPT: Uploads Career Documents
    ChatGPT->>RAG: Initial Comprehensive Profile Analysis
    RAG-->>PythonTool: Extracted Career Information
    PythonTool->>PythonTool: Profile Knowledge Distillation
    PythonTool-->>ChatGPT: High-Level Profile
    ChatGPT->>RAG: Detailed Experience Analysis
    RAG-->>PythonTool: Search Results
    PythonTool->>PythonTool: Detailed Experience Mapping
    PythonTool-->>ChatGPT: Updated Profile
    ChatGPT->>RAG: Comprehensive Skills Analysis
    RAG-->>PythonTool: Search Results
    PythonTool->>PythonTool: Detailed Skill Mapping
    PythonTool->>PythonTool: Final Profile Synthesis, Save File
    PythonTool-->>ChatGPT: Save Link
    ChatGPT->>User: Present Link and Commands
    note over User, ChatGPT: Pause for User Review

    User->>ChatGPT: Resumes with 'C'
    ChatGPT->>Browser: Job Market Research
    Browser-->>PythonTool: Job Listings and Requirements
    PythonTool->>PythonTool: Market Trend Synthesis
    PythonTool-->>ChatGPT: Tailoring Strategy
    ChatGPT->>PythonTool: Resume Crafting
    PythonTool->>PythonTool: Save and Format Resume
    PythonTool-->>ChatGPT: Save File
    ChatGPT->>User: Presents Optimized Resume

    note over User, ChatGPT: Resume Tailoring
    note over User, ChatGPT: Use this step as a Repeatable Input
    User->>ChatGPT: Start Tailoring with "!tailor [job desc]"
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/af8554ef-091f-41e3-9abc-2a1659c37efb" width="45%" height="600">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/cb06ee1e-7b9c-4caf-899a-99700ffbb96e" width="45%" height="600">
</p>

---

## Automated High-Quality Document Analysis

**Status**: Finalized for Release 💯

### Description

In the realm of information overload, the ability to swiftly and accurately dissect complex documents is more vital than ever. This GPT transcends the current barriers of RAG-based document analysis. This tool is not just a mere summarizer; it's an in-depth analyzer, capable of understanding and articulating the nuances of extensive documents by exploiting a complex tool chain. Designed for those who grapple with the daunting task of digesting lengthy reports, legal documents, or scholarly articles, this AI assistant ensures that no critical information slips through the cracks.

### Intended Usage

**Required Input**: User-Uploaded Document

This GPT is engineered for scenarios requiring a deep dive into complex documents. Whether it's a lawyer analyzing legal texts, an academic researcher sifting through dense papers, or a business professional evaluating comprehensive reports, this tool stands as an indispensable ally. It excels in providing a clear, concise, and accurate summary of even the most intricate documents, transforming hours of reading into minutes of insightful comprehension.

This GPT works best for documents with coherent structure, and will dive into each section of importance for a granular and comprehensive understanding. Due to the complexity of this workflow, it can take multiple full responses to finish for complex documents. For more efficient or strategic workflows there are GPTs later in this portfolio tailored for that purpose.

### User Commands

- `!start` - Initiates the advanced analysis workflow based on the uploaded document.
- `C` - Continues the workflow from the last saved checkpoint, a crucial feature for handling extensive documents.
- `R` - Restarts the analysis with a new document.
- `E` - Ends the current analysis session, providing a comprehensive summary of the findings.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant RAG as RAG Search
    participant PythonTool as Python Tool

    User->>ChatGPT: Uploads Document
    ChatGPT->>RAG: Initial Holistic Document Analysis
    RAG-->>PythonTool: Extracted Core Concepts
    PythonTool->>PythonTool: Develops TOC and Analysis Strategy
    PythonTool-->>ChatGPT: Outlines Document Structure
    loop Detailed Section Analysis
        ChatGPT->>RAG: Delve into Specific Sections
        RAG-->>PythonTool: Detailed Insights
        PythonTool->>PythonTool: Synthesize Insights
    end
    PythonTool-->>ChatGPT: Compile and Synthesize Comprehensive Report
    ChatGPT->>User: Present Final Report and Analysis
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/02e2d031-48ac-4b3f-b56a-fb2bf14443c3" width="45%" height="800">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/cbb597cd-2ce9-4104-b1db-ece0f00421c9" width="45%" height="800">
</p>

---

### Automated DALL-E Prompt Variation Testing

**Status**: Finalized for Release 💯

### Description

In the realm of creative AI applications, this GPT shines as an essential tool. It's engineered to unlock the full potential of DALL-E's image generation prowess through systematic prompt variation testing. This GPT automates the process of ideation and prompt refinement, enabling users to explore an expansive array of visual possibilities swiftly and efficiently. This should be an asset for artists, designers, and anyone looking to push the boundaries of AI-assisted visual creation.

### Usage Instructions

To harness this tool's capabilities, users simply need to input a base idea or image concept. The GPT then intelligently generates multiple DALL-E prompts, each designed to explore different facets or interpretations of the initial idea. The result is a collection of diverse images, providing a visual brainstorming session that can inspire further creative exploration or be used to refine the concept to its most effective visual representation.

### User Commands

- `!start [description]`: Kickstarts the workflow with a user-defined description of the desired image.
- `!demo`: Runs a demonstration using AI-synthesized data, showcasing the tool's capabilities.
- `1-5`: Selects the preferred image from the generated batch, facilitating focused refinement or further exploration based on the chosen prompt.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant PythonTool as Python Tool
    participant DallE as DALL-E

    User->>ChatGPT: Initiates with !start [description]
    ChatGPT->>PythonTool: Generates 5 Unique Prompts
    loop Image Generation Loop
        PythonTool->>DallE: Requests Image Generation for Each Prompt
        DallE-->>ChatGPT: Returns Generated Images
    end
    ChatGPT->>User: Presents Images and User Command Options
    loop User Feedback Interaction
        User->>ChatGPT: Selects Preferred Image or Inputs Other Commands
        ChatGPT->>PythonTool: Refines or Expands on Selected Prompt
    end
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/10fc87a1-35b4-44c2-b710-9e7b2a8068d4" width="48%" height="1500">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/609795f2-12fb-4f49-83ef-5afce79b0fe1" width="48%" height="1500">
</p>

---

## Advanced Meta-Prompt Engineer

**Status**: Finalized for Release 💯

### Description

This GPT is a cutting-edge prompt engineering tool designed for the advanced synthesis and refinement of meta-prompts. Meta-prompts are complex prompts that serve as high-level instructions for AI models, guiding them towards achieving specific goals or tasks. This tool excels in transforming vague or abstract ideas into clear, actionable, and optimized meta-prompts, enhancing the efficiency and effectiveness of AI interactions. After completion of the synthesis workflow, users can easily initiate an experimentation and testing loop where different versions are tested, or initiate a refinement workflow based on their feedback. 

This GPT exists as the culmination of my prompt engineering expertise with the GPT line, and is designed to produce extremely precise "system prompts" based on any given prompt or idea. You will not find a better prompt engineering workflow around that actually works to produce better prompts. I will probably regret putting this one out. The large majority of users will not understand the point of this workflow or think this is a meme, yet the ones who know how to leverage this type of tool will appreciate the effort that went into making this. Remember, prompt engineering isn't worth learning 🤭🤭

### Usage Instructions

To utilize this GPT, users can start with a basic idea or a prompt they wish to explore. The tool then employs a series of steps to expand, refine, and optimize the initial input into a detailed and actionable meta-prompt. Users can experiment with variations, refine based on feedback, or use a demonstration mode to understand the GPT's capabilities.

### Important Notes

> *This GPT is intended for the SYNTHESIS and REFINEMENT of Complex System Prompts, and thus is geared more for designers and developers compared to everyday users... For the refinement of everyday "task prompts", the next GPT is tailored specifically for that purpose.*

*GPT can perfectly understand and execute JSON prompts, often times resulting in improved results compared to markdown syntax for complex tasks. JSON is easily convertable to Markdown which is the offical syntax for GPT prompts and what it is fine-tuned for. Markdown is the correct and proper syntax to use for 95% of prompts as a result. However, maintaining prompts in JSON allows you to easily make changes and adjustments to the logic in a coherant way. I'll add steps for markdown conversion in the next pass for those who prefer*

### User Commands

- `!start [prompt to refine]` - Initiates the workflow to transform and refine the user's initial prompt into a sophisticated meta-prompt.
- `!experiment` - Engages the tool in a creative loop, generating a variety of prompt variations to explore different possibilities and perspectives.
- `!refine [feedback]` - Uses user-provided feedback to further refine and enhance the meta-prompt, ensuring alignment with the user's intentions and goals.
- `!demo` - Demonstrates the tool's capabilities using AI-generated data, providing insights into its potential applications and effectiveness.
- `C` - Continues the workflow from the last checkpoint, useful in case of interruptions or for extended processing.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant PythonTool as Python Tool

	Note over User, ChatGPT: !start [prompt]
    User->>ChatGPT: Provides Initial Prompt

	Note over User, PythonTool: Refinement Workflow #E0FFFF
    ChatGPT->>PythonTool: Understanding Analysis
    PythonTool->>PythonTool: Adaptive Contextualization
    PythonTool->>PythonTool: Chain of Thought (CoT) Expansion
    PythonTool->>PythonTool: Universal Personalization
    PythonTool->>PythonTool: Optimization
    PythonTool->>PythonTool: Synthesize Final Prompt
    PythonTool-->>ChatGPT: Final Refined Prompt
    ChatGPT->>User: Present Final Refined Prompt

    Note over User, PythonTool: Post-Actions
    loop User Interaction
        User->>ChatGPT: Issues Command
        note over User, ChatGPT: !experiment
        alt Prompt Variation Experimentation
            ChatGPT-->>ChatGPT: Proceed with Experimentation Loop
            loop Experimentation & Enhancement
                ChatGPT->>PythonTool: Experiment with Prompt Variants
                PythonTool-->>ChatGPT: Feedback and Learning
            end
            ChatGPT->>User: Present results
        note over User, ChatGPT: !refine [feedback]
        else Refine Workflow
        ChatGPT-->>ChatGPT: Performs Refinement Workflow
        end
    end
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/25eecba7-9f07-4178-8bce-38f8a2617358" width="45%" height="800">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/b71c976d-b8e0-4d7e-9f9e-29becc0d2d0a" width="45%" height="800">
</p>

---

## Automated Prompt Refinement

**Status**: Finalized for Release 💯

### Description

This GPT is designed to elevate the clarity and effectiveness of user (task) prompts for AI interactions. This tool transforms vague or broad initial inputs into precisely structured and optimized prompts. It's particularly adept at handling complex tasks, ensuring that the resulting prompts are highly coherent and tailored for GPT-4's capabilities.

### Usage Instructions

Users begin by inputting an initial, perhaps unpolished, prompt. The GPT then employs a series of steps involving detailed analysis, enhancement, categorization, and optimization. This multistage process distills the essence of the user's request, refining it into a clear, actionable prompt. The tool is ideal for users who wish to transform their ideas into well-defined instructions for AI applications, ensuring maximum comprehension and effectiveness.

### User Commands

- `!start [prompt for refinement]`: Initiates the refinement process based on the user's input. This command sets off the workflow, transforming the user's initial prompt into a more structured form.
- `!refine [feedback]`: Allows users to provide feedback on the refined prompt, initiating a secondary refinement process. This iterative approach ensures that the final prompt aligns perfectly with the user's intent.
- `!demo`: Demonstrates the tool's capabilities using AI-synthesized examples.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant PythonTool as Python Tool

    User->>ChatGPT: Initiates the workflow with !start
    ChatGPT->>PythonTool: Submits the initial prompt for transformation
    PythonTool->>PythonTool: Analyzes the prompt
    PythonTool->>PythonTool: Enhances the prompt's clarity and focus
    PythonTool->>PythonTool: Optimizes the prompt for GPT-4
    PythonTool->>PythonTool: Categorizes the prompt for contextual relevance
    PythonTool-->>ChatGPT: Synthesizes the refined prompt
    ChatGPT->>User: Presents the refined prompt to the user
    loop User Feedback and Iteration
        User->>ChatGPT: Provides feedback or additional commands
        alt Refinement based on Feedback
            ChatGPT->>PythonTool: Applies user feedback for further refinement
        else Demonstration or Restart
            ChatGPT->>User: Executes demonstration or restarts the process
        end
    end

```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/3faf4c7e-fe9d-419b-aa32-1c012013a556" width="45%" height="1300">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/4799f739-ba0b-48c5-8396-f8c09c0b256f" width="45%" height="1300">
</p>

---

## Business Contract Analyzer

**Status**: Finalized for Release 💯

### Description

The Business Contract Analyzer is a sophisticated tool designed to provide a comprehensive analysis of legal contracts. Strategically leveraging RAG Search for in-depth content extraction and the Python tool for planning and data synthesis, it offers a granular review of contractual documents. This tool is especially beneficial for legal professionals and businesses who require a thorough understanding and interpretation of contract terms, conditions, and implications.

### Usage Instructions

To utilize the Business Contract Analyzer, users should upload the legal document they wish to analyze. The tool then proceeds on a multi-faceted analysis process, dissecting the contract's content to provide insights on key clauses, potential legal implications, and areas of concern or interest. The advanced start can be used to refine the analysis based on user preferences.

### User Commands

- `!start` - Initiates the analysis process based on the user-uploaded contract.
- `!advStart [specific interests]` - Launches an in-depth analysis focusing on areas specified by the user, such as particular clauses, legal risks, or obligations.
- `!demo` - Demonstrates the tool's capabilities using synthesized data for a better understanding of its functionality.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant RAG as RAG Search
    participant PythonTool as Python Tool

    User->>ChatGPT: Uploads Contract Document
    ChatGPT->>RAG: Conducts Initial Full Document Analysis
    RAG-->>PythonTool: Extracts Key Contractual Elements
    PythonTool->>PythonTool: Develops a Strategy for Deep Analysis
    PythonTool-->>ChatGPT: Outlines Detailed Search Strategy
    loop Detailed Analysis Loop
        ChatGPT->>RAG: Executes Targeted Deep Searches Based on Strategy
        RAG-->>PythonTool: Provides In-depth Search Results
        PythonTool->>PythonTool: Synthesizes and Interprets Findings
    end
    PythonTool->>PythonTool: Compiles Comprehensive Analysis Report
    PythonTool-->>ChatGPT: Finalizes and Formats Report
    ChatGPT->>User: Presents Detailed Contract Analysis
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/611bbc2b-b5cc-4cf5-be02-10f89563b052" width="40%" height="100%">
</p>

---

## Advanced Competitive Analysis AI

**Status**: Finalized for Release 💯

### Description

In today's fast-paced business world, staying ahead in the competitive landscape is key to success. This GPT is a tool designed to provide in-depth, real-time analysis of competitive dynamics within various industries. This workflow combines the analytical prowess of ChatGPT, the data processing capabilities of Python, and the extensive information access of the Browser tool to deliver a comprehensive view of competitors' strategies, market trends, and potential opportunities for strategic positioning.

### Usage Instructions

To utilize this GPT, users can input specific parameters such as the industry of interest, key competitors, and specific areas they want to focus on. The AI then employs a strategic search and synthesis process, adapting its depth and focus based on the user-defined scope. This allows users to tailor the analysis to their unique needs, whether they seek a broad industry overview or a deep dive into specific competitive strategies.

### User Commands

- `!start [industry, competitors, specific areas of interest]` - Initiates the analysis process based on user-defined parameters. At least one field is required, with additional fields optional to refine the scope.
- `!refine [feedback]` - Enables users to refine the analysis based on specific feedback
- `!demo` - Demonstrates the workflow with synthesized data.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant PythonTool as Python Tool
    participant Browser

    User->>ChatGPT: Provide Industry, Key Competitors, Areas of Interest
    ChatGPT->>PythonTool: Planning Phase
    PythonTool-->>ChatGPT: Analysis Plan
    loop Data Collection and Analysis Loop
        ChatGPT->>Browser: Search Competitors and Market Trends
        Browser-->>PythonTool: Gathered Data
        PythonTool->>PythonTool: Process and Analyze Data
    end
    PythonTool->>PythonTool: Identify Patterns and Strategic Insights
    PythonTool->>PythonTool: Generate Report and Recommendations
    PythonTool-->>ChatGPT: Compiled Report
    ChatGPT->>User: Present Final Report
    loop User Feedback Loop
        User->>ChatGPT: Provide Feedback
        ChatGPT->>PythonTool: Refinement Workflow
    end
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/460d77e0-2599-4d3e-91d9-77f9893d81e9" width="60%" height="100%">
</p>

---

## Automated Knowledge Distillation

**Status**: Initial Testing Done, Pending Refinement for Public Release 💫

### Description

This GPT represents a significant leap in efficiently handling complex, information-dense documents. Designed for those who need to quickly grasp the essence of lengthy materials, it serves as a powerful assistant in distilling key knowledge from extensive texts. Whether you're navigating academic research, sifting through business reports, or delving into technical papers, this tool condenses volumes of information into clear, concise summaries, saving valuable time and effort.

### Usage Instructions

**Required Input**: User-Uploaded Document

To harness the full potential of this GPT, simply upload the document you need to analyze. The tool then engages in a sophisticated process to extract the most pertinent information, synthesizing it into an easily digestible summary. This functionality is particularly useful for those who need to assimilate large amounts of data rapidly, whether for study, professional analysis, or personal interest.

### User Commands

- `!start`: Initiates the analysis process using the user-uploaded document.
- `!refine [keywords]`: Focuses the distillation process on specific topics or key terms provided by the user.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant RAG as RAG Search
    participant PythonTool as Python Tool

    User->>ChatGPT: Uploads Document
    ChatGPT->>RAG: Conducts Initial Document Search
    RAG-->>PythonTool: Transfers Document Understanding
    PythonTool->>PythonTool: Engages in Strategic Planning
    PythonTool-->>ChatGPT: Outlines Document Analysis Strategy
    loop RAG Search Loop for Key Concepts
        ChatGPT->>RAG: Performs Focused Searches
        RAG-->>PythonTool: Delivers Search Results
        PythonTool->>PythonTool: Synthesizes Key Information
    end
    PythonTool->>PythonTool: Compiles a Comprehensive Knowledge Summary
    PythonTool-->>ChatGPT: Presents the Synthesized Summary
    ChatGPT->>User: Displays Knowledge Summary
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/9dc5eb38-f8a4-434e-865c-88f938b8a352" width="40%" height="1500">
</p>

---

## Botanical Growth Cycle Visualizer

**Status**: Initial Testing Done, Pending Refinement for Public Release 💫

### Description

The Botanical Growth Cycle Visualizer is a unique, specialized educational tool built for high-quality visualizations of the growth cycle of various plant species. It's designed for both educational purposes and plant enthusiasts who wish to understand and observe the intricate stages of plant growth in a visually engaging manner. This tool is particularly useful for botanists, educators, and anyone with a keen interest in botany.

### Usage Instructions

To leverage this GPT, users simply need to specify the plant species they're interested in. The AI will then take over, synthesizing data and generating a series of images that depict the various stages of the plant's growth cycle, from seed germination to maturity. It's an interactive, user-friendly tool that brings the fascinating process of plant growth to life.

### User Commands

- `!start [plant species]` - This command initiates the workflow, triggering the AI to begin visualizing the growth cycle of the specified plant species.
- `!demo` - A demonstration mode, showcasing the tool's capabilities with a pre-selected plant species.

### Workflow

```mermaid
sequenceDiagram
    participant User
    participant ChatGPT
    participant PythonTool as Python Tool
    participant DallE as DALL-E

    User->>ChatGPT: User Input
    ChatGPT->>PythonTool: Data Synthesis and Planning
    loop Image Generation Loop
        PythonTool->>DallE: Request Image Generation
        DallE-->>PythonTool: Return Generated Image
    end
    PythonTool->>ChatGPT: Compiled Images
    ChatGPT->>User: Recap and Exploration
```

<p align="center">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/e63917ed-a231-48bf-853a-5a0d0fe209d5" width="40%" height="1500">
  <img src="https://github.com/nerority/Advanced-GPTs/assets/80237923/228a4129-846c-4031-833c-ca443e9b29c3" width="40%" height="1500">
</p>

---
