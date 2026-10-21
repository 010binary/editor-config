# Editor Config

Personal editor settings for **Visual Studio Code** and **Zed**.

This repository keeps commonly used editor preferences, formatting behavior, language tooling, terminal profiles, Git integrations, and AI-assisted development settings in one place.

## Files

- [`vscode-config.json`](./vscode-config.json) — Visual Studio Code user settings.
- [`zed-config.json`](./zed-config.json) — Zed editor settings.

## Highlights

### Visual Studio Code

The VS Code configuration includes:

- Format-on-save support with Prettier and language-specific formatters.
- Java, JavaScript, TypeScript, React, Go, Rust, C#, HTML, YAML, Docker Compose, and other language settings.
- Java runtime and build-tool configuration for Java 11, 17, and 21.
- Git and GitLens preferences.
- GitHub Copilot and Claude Code integration settings.
- Automatic saving, import updates, editor rulers, terminal profiles, and UI customizations.
- Material icons and product icons.

### Zed

The Zed configuration includes:

- VS Code-compatible keybindings.
- Copilot and other agent-server integrations.
- Java and TypeScript language-server settings.
- Remote SSH project configuration.
- Git, outline, project, and collaboration panel layout preferences.
- Autosave, minimap, themes, fonts, telemetry, and editor behavior settings.

## Usage

These files are intended to be copied into the corresponding editor settings location or used as a reference when configuring a new machine.

### Visual Studio Code

1. Open the Command Palette.
2. Run **Preferences: Open User Settings (JSON)**.
3. Merge the relevant settings from [`vscode-config.json`](./vscode-config.json) into your settings file.

### Zed

1. Open the Command Palette.
2. Run **zed: open settings**.
3. Merge the relevant settings from [`zed-config.json`](./zed-config.json) into your Zed settings file.

Refer to the [Zed configuration documentation](https://zed.dev/docs/configuring-zed) for the current settings format and available options.

## Machine-specific settings

Some values are specific to a particular machine or environment, including:

- Local Java, .NET, Dart, and Flutter installation paths.
- Terminal font and shell configuration.
- Remote SSH hostnames and project paths.
- Editor model and AI-provider preferences.

Review and update these values before applying the configurations to another computer. Do not copy settings that reference unavailable paths, hosts, models, or services.

## Privacy and security

Review AI, telemetry, remote SSH, and agent permissions before using these settings in a new environment. In particular, confirm that the configured data-collection preferences and tool permissions match your security requirements.

## License

No license has been specified for this repository.
