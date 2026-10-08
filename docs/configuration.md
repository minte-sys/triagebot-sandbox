# Configuration

## The config file
Settings live in config.toml in the project folder. Copy config.example.toml to start.

## Empty or missing config file
If config.toml is empty or a section is missing, the app stops with KeyError naming
the missing section, for example KeyError: 'llm'. Copy config.example.toml again.

## Environment variables
API keys are read from a .env file, never from config.toml.
