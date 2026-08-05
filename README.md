# Description
Poc Use Claude Code with Openrouter. You can use free models to be used with Claude Code

# Steps

- **STEP01**: create project folder
```shell
$ mkdir claude-code-sample
$ cd mkdir claude-code-sample
``` 

- **STEP02**: create claude code configuration
```shell
$ mkdir .claude
$ nano .claude/settings.json
``` 

With this data:
```shell
{
  "env": {
    "OPENROUTER_API_KEY": "<YOUR_OPENROUTER_API_KEY>",
    "ANTHROPIC_BASE_URL": "https://openrouter.ai/api",
    "ANTHROPIC_AUTH_TOKEN": "<YOUR_OPENROUTER_API_KEY>",
    "ANTHROPIC_API_KEY": "",
    "ANTHROPIC_MODEL": "nvidia/nemotron-3-ultra-550b-a55b:free"
  }
}
```

- **STEP03**: open claude code
Inside your code base directory, execute claude code
```shell
$ claude
```

![Claude Code](images/claude_code.png)

To select free models from openrouter go to its page [Openrouter Models Portal](https://openrouter.ai/models) find a free one a get the model id to be used in claude code settings.json


![Openrouter portal](images/openrouter_portal.png)
