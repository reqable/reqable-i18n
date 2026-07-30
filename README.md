# Reqable i18n

The internationalization (i18n) translation repository for [Reqable](https://reqable.com). This project aims to improve Reqable's multi-language support through community collaboration.

## Supported Languages

| Language | Directory | Notes |
|----------|-----------|-------|
| English | `en/` | Base language (reference) |
| 简体中文 | `zh/` | Simplified Chinese |
| 繁體中文 | `zh_TW/` | Traditional Chinese |
| 日本語 | `ja/` | Japanese |
| 한국어 | `ko/` | Korean |
| Deutsch | `de/` | German |
| Español | `es/` | Spanish |
| Français | `fr/` | French |
| Русский | `ru/` | Russian |

## How to Contribute

We welcome community contributions! Follow these steps to submit a PR:

### 1. Fork the Repository

Click the Fork button at the top right to fork the repo to your GitHub account.

### 2. Clone the Repository

```bash
git clone https://github.com/{your-username}/reqable-i18n.git
cd reqable-i18n
```

### 3. Edit Translation Files

- Translation files are in **JSON format**, each consisting of key-value pairs
- **Do NOT modify keys**, only translate the values
- Use the `en/` directory as the **reference** for translation
- Make sure the JSON is syntactically valid (watch for commas, quotes, etc.)

Example (English):

```json
{
    "email": "Email",
    "username": "Username",
    "password": "Password"
}
```

Translated (Simplified Chinese):

```json
{
    "email": "邮箱",
    "username": "用户名",
    "password": "密码"
}
```

### 4. Before Submitting

- Ensure the JSON is valid (use a JSON validator if needed)
- Translations should be accurate, natural, and idiomatic
- Keep the **same key order** as the corresponding file in `en/`
- If unsure about a translation, check how other languages translated it

### 5. Submit a Pull Request

```bash
git add .
git commit -m "fix(i18n): improve translations for {language}"
git push origin main
```

Then open a Pull Request on GitHub and wait for review.

## Guidelines

- **Do NOT modify key names** — only translate the value part
- **Do NOT add or remove keys** — keep keys identical to the corresponding file in `en/`
- If a file is missing some keys, add them based on `en/` as reference
- If you are unsure about the context of certain strings, feel free to open an Issue
- **No machine translation** — translations should read naturally

## License

This is the public translation repository for [Reqable](https://reqable.com). Translations will be integrated into the Reqable application. By contributing, you agree to license your translations for use in Reqable.

## Contact

- Website: [https://reqable.com](https://reqable.com)
- For questions or feedback, please open a GitHub Issue
