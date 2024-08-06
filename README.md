# lithe_modules

**lithe_modules** is a repository for modules and middlewares created by the community for [Lithe](https://github.com/lithecore/framework). This space is open to any developer who wants to contribute new features, extensions, or improvements to Lithe.

## What is This Repository?

This repository serves as a central hub where you can find and contribute modules and middlewares for Lithe. The idea is to provide a collaborative platform for developers to share their creations and expand the capabilities of Lithe.

## Repository Structure

The repository is organized into folders, where each folder represents a specific module. Within each module folder, versions are organized into subfolders. Each version subfolder should contain related files.

## Contributing Modules and Middlewares

If you want to contribute a new module or middleware, follow these steps:

1. **Fork** the repository.
2. Create a new **branch** for your changes (`git checkout -b my-new-feature`).
3. Add your module to the appropriate folder. Be sure to include versions as subfolders within the module folder, with the appropriate files for each version.
4. Make your changes and **commit** (`git commit -am 'Add new module or middleware'`).
5. Push your changes to the repository (`git push origin my-new-feature`).
6. Open a **Pull Request** on GitHub.

## How Modules and Versions Should Be Organized

- **Folder Organization**: Each module should be in a folder with its name, and versions should be organized in subfolders within the module folder. Each version subfolder should contain related files.

  Example:
  ```
  /example-module
      /v1.0.0
          - file1.php
          - file2.php
          - README.md
          - composer.json
      /v1.1.0
          - file1.php
          - file2.php
          - README.md
          - composer.json
  ```

- **README.md**: Each version of a module should contain a `README.md` file that describes the specific version with detailed instructions for that version.

- **Updates**: To update a module to a new version, the new version should be added as a new subfolder within the existing module folder.

Make sure to follow these guidelines to ensure that contributions of modules and middlewares are organized and easy to maintain.

## Installing, Updating, and Uninstalling Modules

### Installation

To install a module, use the following command:

```bash
php line module:install <module-name> <version>
```

- `<module-name>`: The name of the module you want to install.
- `<version>`: The version of the module you want to install.

### Update

To update a module to the latest version, use the following command:

```bash
php line module:update <module-name>
```

This command will uninstall the current version of the module and install the latest version available.

### Uninstallation

To uninstall a module, use the following command:

```bash
php line module:uninstall <module-name>
```

- `<module-name>`: The name of the module you want to uninstall.

Be sure to use the appropriate commands to manage modules and middlewares according to your needs.

## Contribution Guidelines

- **Code Quality**: Ensure that your code is clean and well-documented.
- **Tests**: Include tests to ensure the functionality of the module or middleware.
- **Documentation**: Provide clear and detailed documentation about the usage and configuration of the specific version of the module or middleware.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions and support, please open an issue on [GitHub](https://github.com/lithecore/lithe_modules/issues).
