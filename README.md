# Meta Prompting: Building the Snake Game

Meta prompting is a technique that involves crafting highly detailed and structured instructions, known as meta prompts, to guide AI models like GPT in generating specific outputs. These prompts outline objectives, requirements, and even example outputs, enabling AI to produce accurate and tailored results.

## What is Meta Prompting?
Meta prompting leverages GPT-like AI's ability to interpret and respond to detailed instructions. By breaking down tasks into smaller, well-defined components, meta prompts ensure that AI-generated outputs meet precise specifications. This approach is particularly effective in coding, content creation, and structured problem-solving.

## How I Used Meta Prompting to Develop the Snake Game

Using meta prompting, I created a detailed instruction set for GPT to generate the code for a classic Snake game. The process involved:

1. Crafting a comprehensive meta prompt.
2. Using the GPT model to generate code based on the prompt.
3. Testing and refining the output to ensure it met all requirements.

### Links
- **Meta Prompt GPT:** [Access the Meta Prompt GPT](https://chatgpt.com/g/g-2mqMPjvcZ-meta-prompt-lendario)
- **Generated Chat Session:** [View the Chat for Code Generation](https://chatgpt.com/share/67734728-199c-8001-9d0b-639621efed19)

### Meta Prompt XML
```xml
<prompt>
    <identity>Act like an experienced front-end web developer</identity>
    <objective>Create a simple Snake game using HTML, CSS, and JavaScript, all within a single index.html file.</objective>
    <specifications>
        <requirement>Use the &lt;canvas&gt; element for the game interface.</requirement>
        <requirement>Style the page using CSS for a clean and centered layout.</requirement>
        <requirement>Use JavaScript for all game logic, including:</requirement>
        <details>
            <logic>
                <item>Snake movement: up, down, left, and right using arrow keys.</item>
                <item>Collision detection: end game on collision with walls or snake body.</item>
                <item>Food generation and consumption to increase the snake's length.</item>
                <item>Display a scoring system on the page.</item>
            </logic>
        </details>
    </specifications>
    <requirements>
        <requirement>The game starts with a "Start Game" button press.</requirement>
        <requirement>Display a "Game Over" message and the final score upon collision.</requirement>
        <requirement>Ensure smooth snake movement with proper timing intervals.</requirement>
        <requirement>Include comments in the code to explain key functionalities.</requirement>
    </requirements>
    <structure>
        <html>
            <head>
                <requirement>Include appropriate metadata.</requirement>
                <requirement>Use a &lt;style&gt; tag for CSS.</requirement>
            </head>
            <body>
                <content>
                    <item>A &lt;canvas&gt; element for the game interface.</item>
                    <item>A container to display the score.</item>
                    <item>A "Start Game" button.</item>
                </content>
                <script>Include all JavaScript logic within a &lt;script&gt; tag at the end of the file.</script>
            </body>
        </html>
    </structure>
    <style>
        <requirement>Center the game canvas on the page.</requirement>
        <requirement>Use a simple color scheme: black background, green snake, red food.</requirement>
        <requirement>Use a sans-serif font for the score and messages.</requirement>
    </style>
    <exampleOutput>
        <feature>The snake moves on the canvas and consumes food to grow longer.</feature>
        <feature>Score increases as the snake consumes food.</feature>
        <feature>Collision triggers "Game Over" and displays the final score.</feature>
    </exampleOutput>
    <finalInstruction>Take a deep breath and work on this problem step-by-step.</finalInstruction>
</prompt>
```
