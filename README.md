# gh-ext-demo
only use for GitHub copilot extension demo usage

# Reference:
- **Building Your First Extension** (GitHub Resources)

# Code Repository:
- **GitHub Repository**: [gh-ext-demo](https://github.com/payton-chou-ms/gh-ext-demo)

# SOP Summary:
1. **Launching Code from Codespaces**:
   - Use Codespaces to have a public endpoint for testing.
   - **Commands in Codespaces Terminal**:
     - Navigate to the project folder:
       ```bash
       cd /workspaces/gh-ext-demo/src/my-gh-ext-demo
       ```
     - Build and run the code:
       ```bash
       dotnet build
       dotnet run
       ```
     - Make the endpoint public.

2. **GitHub Configuration**:
   - Navigate to **Settings > Developer Settings** to create a GitHub App.
   - Ensure the callback URL is set up correctly.
   - Confirm that all required extensions are installed.

3. **Testing**:
   - Launch the project locally in **VS Code** to test the extension.
