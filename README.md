# PanelForm

Just a quick tool to generate a HTML from a YAML doc using github https://github.com/holoviz/panel.

## Input

(you can also use `[ ]` instead of `* `, which is not valid YAML; parser will replace):

```YAML
What is the capital of Djibouti?:
    - ( ) option 1
    - ( ) option 2
Check all that apply:
    - x option 1
    - x option 2
What's your name?: _______
```

becomes:



