# insomnia-expandtesting_API

API testing in [expandtesting](https://practice.expandtesting.com/notes/api/api-docs/). This project contains basic examples on how to use Insomnia to test API. All the necessary support documentation to develop this project is placed here.

# Pre-requirements:

| Requirement                     | Version        | Note                                                            |
| :------------------------------ |:---------------| :-------------------------------------------------------------- |
| Insomnia                        | 10.3.0         | -                                                               |
| Inso                            | 10.3.0         | -                                                               |
             
# Installation:

- See [Insomnia page](https://github.com/Kong/insomnia/releases/tag/core@10.3.0) and download Insomnia and Inso. Install Insomnia and choose an option to sign in. Place inso.exe file in C:\insomnia-expandtesting_API.

# Tests:

- In Insomnia, Hit :point_right::arrow_forward: **Run**, :white_check_mark: **Select All**, :point_right: **Run**, :point_right: **</>Run via CLI** and copy the generated command. It must be something like  ```inso run collection wrk_89cad6 -e env_2823ee --bail ```. In cmd, navigate do C:\insomnia-expandtesting_API and execute the generated command ```inso run collection wrk_89cad6 -e env_2823ee --bail --verbose``` to run the collection in headless mode.
- In Insomnia, Hit :point_right::arrow_forward: **Run**, :white_check_mark: **Select All** to execute the entire collection or select individual tests.

# Support:

- [expandtesting API documentation page](https://practice.expandtesting.com/notes/api/api-docs/)
- [expandtesting API demonstration page](https://www.youtube.com/watch?v=bQYvS6EEBZc)
- [API Development and Testing 101: Introduction to Insomnia](https://www.youtube.com/watch?v=30vI6Oq865s&t=1145s)
- [CLI Command Reference](https://docs.insomnia.rest/inso-cli/cli-command-reference)
- [Continuous Integration](https://docs.insomnia.rest/inso-cli/continuous-integration)
- [ChatGPT](https://chatgpt.com/)

# Tips:

- UI and API tests to send password reset link to user's email and API tests to verify a password reset token and reset a user's password must be tested manually as they rely on e-mail verification.


