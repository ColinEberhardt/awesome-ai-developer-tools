# Awesome AI Developer Tools

## What's different in this fork




A curated list of the more mature AI tools for enhancing developer productivity.

There are a growing number of tools that leverage AI to assist developers write code, refactor, debug and more. These fall into some broad categories, however, there is a lot of overlap, which blurs the boundaries. This *awesome list* isn't intended to exhaustively list every tool, there's already a [really good list for that purpose](https://github.com/jamesmurdza/awesome-ai-devtools). Rather, here we only cover the more mature tools, but importantly provide detail. This will hopefully be a more useful starting point for anyone wanting to compare and select a tool.

Contributions are welcome! Please see the [contribution guide](CONTRIBUTING.md) for details. This project is licensed under the [MIT License](LICENSE).

<!-- vscode-markdown-toc -->
* [Autocompletion tools](#Autocompletiontools)
	* [GitHub Copilot](#GitHubCopilot)
	* [Amazon Q](#AmazonQ)
	* [Sweep](#Sweep)
	* [Tabnine](#Tabnine)
	* [Cody](#Cody)
* [Integrated Development Environments (IDE)](#IntegratedDevelopmentEnvironmentsIDE)
	* [Replit Agent](#ReplitAgent)
	* [Cursor](#Cursor)
	* [Cline](#Cline)
	* [GoCodeo](#gocodeo)
	* [Windsurf](#Windsurf)
	* [Aider](#Aider)
* [Rapid prototyping](#Rapidprototyping)
	* [v0](#v0)
	* [Bolt](#Bolt)
	* [Lovable](#Lovable)
* [Agents](#Agents)
	* [OpenWork](#OpenWork)
	* [Devin](#Devin)
	* [Copilot Workspaces](#CopilotWorkspaces)
	* [GitHub Copilot Agent Mode](#GitHubCopilotAgentMode)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

![tools timeline](tools.png)

## <a name='Autocompletiontools'></a>Autocompletion tools

### <a name='GitHubCopilot'></a>GitHub Copilot

| Released   | Cost             | Open source | From   |
|------------|------------------|-------------|--------|
| Oct 2021   | $0-$21 user/mo   | No          | [GitHub](https://github.com/features/copilot) |

GitHub Copilot, introduced in October 2021, marked a significant advancement in AI-assisted software development. Developed by GitHub in partnership with OpenAI, it leverages the Codex model to provide developers with intelligent code suggestions, streamlining the coding process and boosting productivity.

 - **AI-Powered Code Completion** – Provides real-time code suggestions as you type, offering complete lines or entire functions. Supports multiple programming languages, including Python, JavaScript, Java, C++, and more. 
 - **Whole Function and Boilerplate Generation** – Generates entire functions, including complex logic, based on high-level descriptions.  
 - **Copilot Edits for multi-file support** – Iterate quickly on code changes across multiple files by using natural language.  
 - **Code Explanation and Learning** – Helps developers understand existing codebases by providing AI-generated explanations. Useful for debugging, onboarding new team members, and learning new frameworks. 
 - **Multi-Platform and IDE Support** – Works with Visual Studio Code, JetBrains IDEs, and Neovim.

### <a name='AmazonQ'></a>Amazon Q

| Released   | Cost             | Open source | From   |
|------------|------------------|-------------|--------|
| Nov 2023   | $0-$19 user/mo   | No          | [AWS](https://aws.amazon.com/q/) |

Amazon Q is a generative AI-powered assistant developed by Amazon Web Services (AWS) to enhance software development, data management, and cloud operations. Announced in November 2023 at AWS re:Invent.

- **AI-Powered Code Completions** – Provides real-time code suggestions, including entire lines or full functions, based on the context of the developer’s code and comments. 
- **Multi-Language Support** – Supports various programming languages such as Python, Java, JavaScript, C#, TypeScript, Rust, Go, and more, making it versatile for different development tasks. 
- **IDE Integration** – Works with Visual Studio Code (VS Code), JetBrains IDEs (IntelliJ IDEA, PyCharm, WebStorm), AWS Cloud9, and Jupyter Notebooks, ensuring a smooth workflow within existing development environments. 
- **Context-Aware Code Suggestions** – Analyzes project structure, dependencies, and libraries to generate more relevant and accurate code recommendations. 
- **AWS Service Integration** – Provides optimized code suggestions for AWS services, including Amazon S3, Lambda, DynamoDB, EC2, and others, making it highly useful for cloud-based application development. 
- **Customizability and Enterprise Support** – Offers enterprise features, including customized model training based on an organization's codebase, improving the relevance of AI-generated suggestions for teams. 
- **Reference Tracking and Legal Compliance** – Helps developers identify whether AI-generated code is similar to existing open-source code and provides links to the original source, ensuring compliance with licensing requirements.
- **Autonomous Agents for Complex Tasks** - Amazon Q Developer agents can autonomously perform tasks like implementing features, documenting code, testing, reviewing, and refactoring, thereby streamlining the software development lifecycle.

### <a name='Sweep'></a>Sweep

| Released   | Cost             | Open source | From   |
|------------|------------------|-------------|--------|
| Nov 2023   | $0-$25 user/mo   | No          | [Sweep](https://sweep.dev/) |

Sweep is an AI-powered coding assistant designed to streamline software development by automating tasks such as bug fixes and feature implementations, within the JetBrains IDE.

- **Automated Code Changes** – Sweep transforms bug reports and feature requests into actionable code modifications. By analyzing the codebase, it plans and generates pull requests with the necessary changes, reducing manual intervention.
- **Seamless GitHub Integration** – The platform integrates directly with GitHub repositories, allowing developers to assign issues to Sweep. It reads the codebase, formulates a plan, and submits pull requests, streamlining the development workflow.
- **JetBrains IDE Support** – Sweep offers compatibility with JetBrains IDEs, including IntelliJ, PyCharm, and Android Studio, bringing AI coding assistance directly into these development environments.
- **Multi-Language Support** – The assistant supports various programming languages, enabling it to assist in diverse development projects.
- **Continuous Learning** – Leveraging advanced language models, Sweep continually improves its understanding of codebases and development practices, enhancing the accuracy and relevance of its code suggestions over time.

### <a name='Tabnine'></a>Tabnine

| Released   | Cost             | Open source | From   |
|------------|------------------|-------------|--------|
| 2019   | $9-$39 user/mo   | No          | [Tabnine](https://www.tabnine.com/) |

Tabnine is an AI-powered code completion tool designed to assist developers by providing intelligent code suggestions and autocompletions. It enhances productivity by integrating seamlessly with various IDEs and supporting multiple programming languages. Its core functions and capabilities include:

- **AI-Driven Code Completion** – Provides context-aware autocompletions, suggesting entire lines or blocks of code based on the user’s coding patterns and project context.
- **Multi-Language Support** – Works with a wide range of programming languages, including Python, JavaScript, Java, C++, Go, and more, making it useful for diverse development environments.
- **Seamless IDE Integration** – Compatible with popular IDEs such as VS Code, JetBrains suite (IntelliJ, PyCharm, WebStorm), Vim, Sublime Text, and others, allowing developers to use it within their preferred environment.
- **Private and Secure AI Models** – Offers on-device AI models that ensure user code remains private. Developers can run Tabnine locally without sending code to external servers, improving security and compliance.
- **Custom AI Model Training** – Allows teams and enterprises to fine-tune AI models based on their specific codebases, making the suggestions more relevant to their projects.
- **Contextual Awareness** – Analyzes project structure, function definitions, and dependencies to generate more relevant code suggestions, improving efficiency in large codebases.
- **Team and Enterprise Features** – Provides centralized AI model management for organizations, ensuring consistent code quality across teams.
- **Pair Programming Assistance** – Acts as a virtual pair programmer, reducing cognitive load by generating boilerplate code, common patterns, and refactoring suggestions.

### <a name='Cody'></a>Cody

| Released   | Cost             | Open source | From   |
|------------|------------------|-------------|--------|
| 2023   | $0-$59 user/mo   | No          | [Sourcegraph](https://sourcegraph.com/) |

Sourcegraph, launched in 2013, is a code search and intelligence platform designed to help developers navigate and understand large codebases efficiently. In 2023 they added Cody, an AI-autocompletion service.

- **AI-Powered Code Autocompletion** – Provides real-time, intelligent code suggestions, completing entire lines or functions based on project context.
- **Multi-Language Support** – Works with various programming languages, including Python, JavaScript, Go, Java, C++, Rust, and more.
- **Context-Aware Code Assistance** – Unlike traditional code assistants, Cody has deep knowledge of an entire codebase, enabling it to provide relevant suggestions, identify dependencies, and navigate large projects.
- **IDE and Editor Integration** – Supports VS Code, JetBrains IDEs, Neovim, and Sourcegraph’s own web-based environment, ensuring smooth integration with developers' workflows.
- **Code Search and Understanding** – Allows developers to quickly search and navigate through large codebases, helping them understand unfamiliar code more efficiently.
- **Code Explanation and Documentation** – Can generate explanations for code snippets, making it easier to onboard new developers or understand complex legacy code.
- **Refactoring and Code Improvements** – Suggests optimizations, helps rewrite inefficient code, and improves maintainability through structured refactoring.
- **Repository-Wide AI Assistance** – Unlike AI models that focus only on open files, Cody analyzes the entire repository, making its suggestions more contextually relevant.
- **Chat-Based AI Assistance** – Developers can chat with Cody using natural language queries, asking it to find specific code, explain logic, or even generate new functions.
- **Security and Privacy** – Offers on-premises and self-hosted deployment options, ensuring code remains private and secure, particularly for enterprise teams.
- **Enterprise Features and Custom Models** – Provides enterprise-grade AI assistance tailored to company-specific repositories and coding practices.

## <a name='IntegratedDevelopmentEnvironmentsIDE'></a>Integrated Development Environments (IDE)

### <a name='ReplitAgent'></a>Replit Agent

| Released   | Cost             | Open source | From   |
|------------|------------------|-------------|--------|
| Sept 2024   | $0-$20 user/mo   | No          | [Replit](https://replit.com/ai) |

Replit is a cloud-based integrated development environment (IDE) that simplifies coding, collaboration, and application deployment directly from the browser. Founded in 2016, Replit introduced Replit Agent in 2024 to provide AI-powered assistance for developers.

- **AI Assistance** – Replit integrates AI tools, such as Replit Agent, to assist with code generation, debugging, and intelligent code completions, helping developers work more efficiently.
- **Multilingual Support** – The platform supports over 50 programming languages, including Python, JavaScript, C++, and Java, enabling developers to work in their preferred language.
- **Real-Time Collaboration** – Replit's collaborative features allow multiple users to code together in real-time, with tools like live coding sessions, shared environments, and built-in chat.
- **Instant Deployment** – Users can deploy applications directly from the Replit environment with minimal setup, supporting rapid testing and production releases.
- **Integrated Development Environment** – As a cloud-based IDE, Replit provides tools like code editors, debuggers, and version control systems, accessible from any device with internet access.
- **Community and Learning Resources** – Replit offers a community where users can share projects, seek help, and access educational resources, supporting learning and collaboration among developers.

### <a name='Cursor'></a>Cursor

| Released   | Cost             | Open source | From   |
|------------|------------------|-------------|--------|
| Oct 2023   | $0-$40 user/mo   | No          | [Anysphere](https://www.cursor.com/) |

Cursor is an AI-powered integrated development environment (IDE) developed by Anysphere Inc, designed to enhance developer productivity by integrating advanced artificial intelligence features directly into the coding environment. It is a fork of the widely used VSCode platform.

- **AI-Powered Code Generation** – Allows developers to write code using natural language instructions, enabling the generation or updating of entire classes or functions, streamlining the coding process.
- **Intelligent Autocompletion** – Predicts subsequent code edits, allowing users to navigate through changes efficiently and facilitating rapid development by anticipating the developer's needs.
- **Codebase Understanding** – Comprehends and provides insights into the entire codebase, allowing developers to query the codebase in natural language to retrieve information or refer to specific files and documentation, enhancing code comprehension and navigation.
- **Smart Rewrites** – Offers capabilities to update multiple lines of code simultaneously, which is particularly useful for refactoring and implementing bulk changes efficiently.
- **Extension Compatibility** – As a fork of Visual Studio Code, Cursor supports the integration of existing extensions, themes, and keybindings, ensuring that developers can maintain their preferred workflows without disruption.
- **Privacy and Security** – Offers privacy options, including a Privacy Mode where the user's code is never stored remotely, and is SOC 2 certified, ensuring adherence to industry-standard security practices.

### <a name='Cline'></a>Cline

| Released