- Identity setup

```bash
# Set your global commit name and email
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Update values
git config set user.name "John"
git config set user.email "your.email@example.com"
```

- Inspecting Variables

```bash
# List all configurations with their origins and scopes
git config list

# Find a single global setting
git config --global get user.name
```