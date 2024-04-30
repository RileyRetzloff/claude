<h3>
**NOTE:** This is my personal fork of the <a href="https://github.com/florisdobber/claude-raycast.git">original</a> Claude Raycast extension by <a href="https://github.com/florisdobber">Floris Dobber</a>.
</h3>

<p align="center">
<img width=100 src="./assets/icon.png">
</p>

<h1 align="center">Claude by Anthropic</h1>

<h3 align="center">
Interact with Anthropic's Claude right from your command bar
</h3>

<p align="center">
<a href="https://github.com/raycast/extensions/tree/main/extensions/claude" title="Claude Raycast extension latest source code">Latest source code
</a>
</p>

![All Commands](metadata/all_commands.png)

# Features

## Ask anything

Straight from your command bar, ask anything you want answered.

![Ask anything](metadata/ask.png)

## Personalized for you

Customize the model to your liking.

![Custom models](metadata/custom_models.png)

## Continue talking

Continue talking, right from where you left off.

![Continue talking](metadata/continue.png)

## Save answers

Got the answer that you wanted? Great.

![Saved answers](metadata/saved_answers.png)

# Models available

## Claude 3

- `claude-3-haiku-20240307`
- `claude-3-sonnet-20240229`
- `claude-3-opus-20240229`

## Claude 2

- `claude-2.0`
- `claude-2.1`

# How to use

This package requires a valid API key from [Anthropic](https://docs.anthropic.com/claude/reference/getting-started-with-the-api).

![Initial set-up](metadata/set-up.png)

> All the preferences value will be stored locally using [Preferences API](https://developers.raycast.com/api-reference/preferences)

# Preferences

All preferences properties list that can be customize through `Raycast Settings > Extensions > Claude`

| Properties        | Label               | Value     | Required | Default | Description                                                                                                      |
| ----------------- | ------------------- | --------- | -------- | ------- | ---------------------------------------------------------------------------------------------------------------- |
| `apiKey`          | API Key             | `string`  | `true`   | `empty` | Your personal Anthropic API key                                                                                  |
| `isAutoLoadText`  | Auto-load           | `boolean` | `false`  | `false` | Load selected text from your frontmost application to the `question bar` or `full text input form` automatically |
| `isAutoFullInput` | Use Full Text Input | `boolean` | `false`  | `false` | Switch to `full text input form` from `question bar` automatically whenever you want to ask or type a question   |

---
