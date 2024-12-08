# githubAction
Features

📊 Integration with CI/CD pipelines (e.g., GitHub Actions).
📄 Page Object Model (POM) architecture for organized and reusable code.
🚀 Cypress for fast and reliable end-to-end testing.
✅ Tests written in TypeScript for better type safety and maintainability.

Prerequisites
Before starting, ensure you have the following installed:

Node.js (v16 or higher recommended)
Project Structure
plaintext

.github/
└── workflows/
    └── cypress-tests.yml         # GitHub Action for CI/CD integration
cypress/
├── fixtures/                     # Test data (e.g., JSON files)
├── integration/                  # Test specs (*.spec.ts files)
├── support/                      # Support files (e.g., commands.js)
├── screenshots/                  # Automatically saved screenshots (on failure)
├── videos/                       # Automatically saved test videos (on failure)
├── tsconfig.json                 # TypeScript configuration for Cypress
package.json                      # Project dependencies
Setup Instructions
Clone the Repository

git clone <https://github.com/nadiahashe>
Install Dependencies

Run Tests Locally

To open the Cypress test runner:
npx cypress open
To run all tests in headless mode:
npx cypress run

To manually trigger the GitHub Actions workflow:
https://github.com/nadiahashe/githubAction/actions/runs/12218333053

Push your changes to a branch.
Go to the Actions tab on your GitHub repository.
Writing Tests
Create a new spec file in cypress/integration/:

Install dependencies.
Run Cypress tests.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
If you have questions or feedback, please contact Nadia Hashemi.