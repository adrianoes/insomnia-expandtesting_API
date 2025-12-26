# insomnia-expandtesting_api

API testing in [expandtesting](https://practice.expandtesting.com/notes/api/api-docs/). This project contains basic examples on how to use Insomnia to test API. All the necessary support documentation to develop this project is placed here.

# Pre-requirements:

| Requirement                     | Version        | Note                                                            |
| :------------------------------ |:---------------| :-------------------------------------------------------------- |
| Insomnia                        | 12.2.0         | -                                                               |
| Inso                            | 12.2.0         | -                                                               |
             
# Installation:

- See [Insomnia page](https://github.com/Kong/insomnia/releases/tag/core%4012.2.0) and download Insomnia.Core-12.2.0.exe
 and inso-windows-12.2.0.zip. Install Insomnia and choose an option to sign in. Place inso.exe file in C:\insomnia-expandtesting_api.

# Tests:

- In Insomnia, Hit :point_right::arrow_forward: **Run**, :white_check_mark: **Select All**, :point_right: **Run**, :point_right: **</>Run via CLI** and copy the generated command. It must be something like  ```inso run collection wrk_6fcde3 -e env_0c07c1 --bail```. In cmd, navigate do C:\insomnia-expandtesting_api and execute the generated command ```inso run collection wrk_6fcde3 -e env_0c07c1 --bail --verbose``` to run the collection in headless mode.
- In Insomnia, Hit :point_right::arrow_forward: **Run**, :white_check_mark: **Select All** to execute the entire collection or select individual http requests.

# Support:

- [expandtesting API documentation page](https://practice.expandtesting.com/notes/api/api-docs/)
- [expandtesting API demonstration page](https://www.youtube.com/watch?v=bQYvS6EEBZc)
- [API Development and Testing 101: Introduction to Insomnia](https://www.youtube.com/watch?v=30vI6Oq865s&t=1145s)
- [CLI Command Reference](https://docs.insomnia.rest/inso-cli/cli-command-reference)
- [Continuous Integration](https://docs.insomnia.rest/inso-cli/continuous-integration)
- [ChatGPT](https://chatgpt.com/)

# Tips:

- UI and API tests to send password reset link to user's email and API tests to verify a password reset token and reset a user's password must be tested manually as they rely on e-mail verification.
- Insomnia has a poor and outdated documentation. ChatGPT was used in order to figure how to get the Github actions workflow working.


