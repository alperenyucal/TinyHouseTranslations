# Tiny House Simulator Translation Repository

This repository is designed to facilitate collaboration on translations for our project. It contains a centralized `translations.csv` file with support for multiple languages.

## Supported Languages

| Code    | Language       |
|---------|----------------|
| ar      | Arabic         |
| bg      | Bulgarian      |
| zh-CN   | Simplified Chinese (schinese) |
| zh-TW   | Traditional Chinese (tchinese) |
| cs      | Czech          |
| da      | Danish         |
| nl      | Dutch          |
| en      | English        |
| fl      | Finnish        |
| fr      | French         |
| de      | German         |
| el      | Greek          |
| hu      | Hungarian      |
| id      | Indonesian     |
| it      | Italian        |
| ja      | Japanese       |
| ko      | Korean         |
| no      | Norwegian      |
| pl      | Polish         |
| pt      | Portuguese     |
| pt-BR   | Brazilian Portuguese |
| ro      | Romanian       |
| ru      | Russian        |
| es      | Spanish        |
| es-419  | Latin American Spanish (latam) |
| sv      | Swedish        |
| th      | Thai           |
| tr      | Turkish        |
| uk      | Ukrainian      |
| vi      | Vietnamese     |

## File Structure

- `translations.csv`: Contains the text entries for all supported languages. Each row represents a key-value pair, where:
  - The first column (`key`) defines the unique identifier for a text entry.
  - The subsequent columns represent translations for each language.

### Example Structure of `translations.csv`

| key          | en         | ar        | zh-CN      | fr         |
|--------------|------------|-----------|------------|------------|
| hello_world  | Hello, World! | \u0623\u0647\u0644\u0627 \u0628\u0627\u0644\u0639\u0627\u0644\u0645 | \u4f60\u597d\u4e16\u754c | Bonjour, Monde! |
| goodbye      | Goodbye!   | \u0645\u0639 \u0627\u0644\u0633\u0644\u0627\u0645\u0629 | \u518d\u89c1 | Au revoir! |

### Notes:
- Strings must be UTF-8 encoded.
- Use consistent keys to avoid duplication and ensure all languages have corresponding translations.

## How to Contribute

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Open the `translations.csv` file and add or update translations.

3. Submit your changes by creating a pull request with a clear description of the updates.

## Guidelines
- Follow the key naming conventions (`snake_case` preferred).
- Ensure translations are contextually accurate.
- Validate your changes before submitting.

Thank you for contributing to our localization efforts!
