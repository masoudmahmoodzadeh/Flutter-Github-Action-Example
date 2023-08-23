# flutter Github Action Example

GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that automates build, test, and deployment pipelines. It also allows you to execute code in the repository when certain events occur, making it easy to extend and customize.

In this sample, you’ll learn how to deploy your Flutter app following CI/CD principles with GitHub Actions as a tool.

The GitHub Actions workflow uses .yml (“YAML Ain’t Markup Language”) files, which will be stored in the .github directory at the root of your project.

- Set up a new Flutter project using your favourite IDE or using the Flutter command-line tool
- Initialize Git in your new project on your machine and create a new repository associated with your GitHub account
- Create the config directory in the root of your flutter project .github and a new directory called workflows. The workflows here will contain all your CI/CD workflows as .yml files
