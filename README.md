# PanelForm

Just a quick tool to generate a Netlify form from a YAML doc using Holoviz Panel https://github.com/holoviz/panel.

## Input

(you can also use `- [ ] ` instead of `- x `, but it's not valid YAML; parser will replace):

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

https://riziles.github.io/PanelForm/panel_form.html



