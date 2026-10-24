# Changelog

All notable changes to the Varbase AI Agents recipe are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.6] - 2026-10-24
### Changed
- Update logo.png to the new Varbase logo ([#3632505](https://www.drupal.org/i/3632505)).

## [1.0.5] - 2026-10-11
### Changed
- Add the default `.gitlab` and `.github` issue and merge request templates. See [#3614565](https://www.drupal.org/i/3614565).
- Set the recipe version to `1.0.5`.

## [1.0.4] - 2025-11-17
### Changed
- Change the AI Agent Assistant to the AI Agents API introduced in Drupal AI 1.2.0, require `drupal/ai` and `drupal/ai_agents` `~1.2.0`, and show the AI Agent chatbot on `/admin/dashboard` only. See [#3558339](https://www.drupal.org/i/3558339).
- Set the recipe version to `1.0.4`.

## [1.0.3] - 2025-07-01
### Changed
- Require `drupal/ai` `~1.1.0`. See [#3532981](https://www.drupal.org/i/3532981).
- Say in `README.md` that the Varbase AI Default recipe must be applied first, and show both ways to apply this recipe: the Drupal recipe script or Drush. See [#3533381](https://www.drupal.org/i/3533381).
- Set the recipe version to `1.0.3`.

## [1.0.2] - 2025-01-31
### Changed
- Rename Varbase Agent to AI Agent (assistant `ai_agent_assistant`, block `ai_chatbot`), require `drupal/ai`, and credit the Drupal AI community in `README.md`. See [#3503292](https://www.drupal.org/i/3503292).
- Switch the default AI Agent from the AI Chatbot block to the AI DeepChat Chatbot block. See [#3503473](https://www.drupal.org/i/3503473).

## [1.0.1] - 2025-01-28
### Changed
- Require `league/commonmark` so the AI Chatbot module can format its messages. See [#3502844](https://www.drupal.org/i/3502844).

## [1.0.0] - 2025-01-26
### Added
- Initial release of the Varbase AI Agents recipe: installs AI, AI Assistant API, AI Chatbot and AI Agents, and places an AI chatbot block for an agent assistant in the Gin admin theme. See [#3502286](https://www.drupal.org/i/3502286).

[Unreleased]: https://git.drupalcode.org/project/varbase_ai_agents/-/compare/1.0.6...1.0.x
[1.0.6]: https://git.drupalcode.org/project/varbase_ai_agents/-/compare/1.0.5...1.0.6
[1.0.5]: https://git.drupalcode.org/project/varbase_ai_agents/-/compare/1.0.4...1.0.5
[1.0.4]: https://git.drupalcode.org/project/varbase_ai_agents/-/compare/1.0.3...1.0.4
[1.0.3]: https://git.drupalcode.org/project/varbase_ai_agents/-/compare/1.0.2...1.0.3
[1.0.2]: https://git.drupalcode.org/project/varbase_ai_agents/-/compare/1.0.1...1.0.2
[1.0.1]: https://git.drupalcode.org/project/varbase_ai_agents/-/compare/1.0.0...1.0.1
[1.0.0]: https://git.drupalcode.org/project/varbase_ai_agents/-/tags/1.0.0
