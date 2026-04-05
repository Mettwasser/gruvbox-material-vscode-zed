# Gruvbox Material VSCode

Gruvbox Material almost 1:1 as from VSCode.

## Requirements

For it to properly work, you need to add the following to your `settings.json` in Zed:

```json
"global_lsp_settings": {
    "semantic_token_rules": [
        {
            "token_type": "decorator",
            "style": ["decorator", "attribute"],
        },
        {
            "token_type": "deriveHelper",
            "style": ["deriveHelper", "attribute"],
        },
        {
            "token_type": "variable",
            "token_modifiers": ["attribute"],
            "style": ["attribute"],
        },
    ],
},
```

## Authors

- Mettwasser
