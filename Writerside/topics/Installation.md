# Installation

## Prerequisites

Before installing CocoBot, you need to have the following software installed on your computer:

- [Python 3.9 or later](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installation/)
- [ImageMagick](https://imagemagick.org/script/download.php)

You also need to have a **AssemblyAI API key**. You can get one by signing up on the [AssemblyAI website](https://www.assemblyai.com/). After signing up, you will receive an API key that you can use to access the AssemblyAI service.

## Install CocoBot

<tabs>
    <tab title="Windows">
        <ol>
            <li>Open a command prompt(<shortcut key="$OpenTerminal" force-layout="Windows"></shortcut>, type `cmd`, and press <shortcut>Enter</shortcut>).</li>
            <li>Run the following command to clone the CocoBot repository:
                <p><pre><code>git clone git@github.com:MrArnaudMichel/Coco-Bot.git</code></pre></p>
            </li>
            <li>
                Copy the `config.example.json` file to `config.json` and edit it to match your configuration and preferences.
                <p><pre><code>copy config.example.json config.json</code></pre></p>
            </li>
            <li>
                Create a virtual environment
                <p><pre><code>python -m venv venv</code></pre></p>
            </li>
            <li>
                Activate the virtual environment
                <p><pre><code>.\venv\Scripts\activate</code></pre></p>
            </li>
            <li>Run the following command to install the required Python packages:
                <p>
                <pre><code>pip install -r requirements.txt</code></pre>
                </p>
            </li>
        </ol>
        <deflist collapsible="true">
            <def title="All the commands" collapsible="true" default-state="collapsed">
                <code-block lang="bash">
                    git clone git@github.com:MrArnaudMichel/Coco-Bot.git
                    copy config.example.json config.json
                    python -m venv venv
                    .\venv\Scripts\activate
                    pip install -r requirements.txt
                </code-block>
                <p>
                    You can copy and paste all the commands at once. Use the <shortcut key="$CtrlShiftV" force-layout="Windows"></shortcut> keyboard shortcut to paste the commands in the command prompt.
                </p>
            </def>
        </deflist>
    </tab>
    <tab title="macOS">
        <ol>
            <li>Open a terminal <shortcut key="$OpenTerminal" force-layout="macOS"></shortcut>.</li>
            <li>Run the following command to clone the CocoBot repository:
                <p><pre><code>git clone git@github.com:MrArnaudMichel/Coco-Bot.git</code></pre></p>
            </li>
            <li>
                Copy the `config.example.json` file to `config.json` and edit it to match your configuration and preferences.
                <p><pre><code>cp config.example.json config.json</code></pre></p>
            </li>
            <li>
                Create a virtual environment
                <p><pre><code>python3 -m venv venv</code></pre></p>
            </li>
            <li>
                Activate the virtual environment
                <p><pre><code>source venv/bin/activate</code></pre></p>
            </li>
            <li>Run the following command to install the required Python packages:
                <p>
                <pre><code>pip install -r requirements.txt</code></pre>
                </p>
            </li>
        </ol>
        <deflist collapsible="true">
            <def title="All the commands" collapsible="true" default-state="collapsed">
                <code-block lang="bash">
                    git clone git@github.com:MrArnaudMichel/Coco-Bot.git
                    cp config.example.json config.json
                    python3 -m venv venv
                    source venv/bin/activate
                    pip install -r requirements.txt
                </code-block>
                <p>
                    You can copy and paste all the commands at once. Use the <shortcut key="$CtrlShiftV" force-layout="macOS"></shortcut> keyboard shortcut to paste the commands in the terminal.
                </p>
            </def>
        </deflist>
    </tab>
    <tab title="Linux">
        <ol>
            <li>Open a terminal <shortcut key="$OpenTerminal" force-layout="Linux"></shortcut>.</li>
            <li>Run the following command to clone the CocoBot repository:
                <p><pre><code>git clone git@github.com:MrArnaudMichel/Coco-Bot.git</code></pre></p>
            </li>
            <li>
                Copy the `config.example.json` file to `config.json` and edit it to match your configuration and preferences.
                <p><pre><code>cp config.example.json config.json</code></pre></p>
            </li>
            <li>
                Create a virtual environment
                <p><pre><code>python3 -m venv venv</code></pre></p>
            </li>
            <li>
                Activate the virtual environment
                <p><pre><code>source venv/bin/activate</code></pre></p>
            </li>
            <li>Run the following command to install the required Python packages:
                <p>
                <pre><code>pip install -r requirements.txt</code></pre>
                </p>
            </li>
        </ol>
        <deflist collapsible="true">
            <def title="All the commands" collapsible="true" default-state="collapsed">
                <code-block lang="bash">
                    git clone git@github.com:MrArnaudMichel/Coco-Bot.git
                    cp config.example.json config.json
                    python3 -m venv venv
                    source venv/bin/activate
                    pip install -r requirements.txt
                </code-block>
                <p>
                    You can copy and paste all the commands at once. Use the <shortcut key="$CtrlShiftV" force-layout="Linux"></shortcut> keyboard shortcut to paste the commands in the terminal.
                </p>
            </def>
        </deflist>
    </tab>
</tabs>
