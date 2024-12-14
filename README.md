# Mod Template

This is a DLL mode template for Scrap Mechanic that automatically supports [Carbon Launcher](https://github.com/ScrappySM/CarbonLauncher), other launchers and manual injection.
It comes with all boilerplate you need, a highly permissive license, and a simple build system. Along with this is industry standard CI/CD practices allowing launchers to automatically download and install your mod.

## Usage

1. Press "Use this template" on the GitHub page to create a new repository with this template.
2. Clone the repository to your computer that you have just created.
3. Run `rename.bat` and type the desired name of your mod.
4. Open the project in Visual Studio or any IDE that support the MSBuild system.
5. Modify `manifest.json` with your mod details.
6. Make any modifications you like to `dllmain.cpp` and compile the project.
7. If it works, commit and push your changes to GitHub with a [tagged commit](https://git-scm.com/book/en/v2/Git-Basics-Tagging)!
8. Go to your releases, find the draft release and press edit then publish! If your repo is public mod launchers can automatically download and install your mod if you request it to be added to their repos!

> [!NOTE]
> Want to be put on the [Carbon Launcher](https://github.com/ScrappySM/CarbonLauncher) repo? Just ask in the [issues](https://github.com/ScrappySM/CarnonLauncher/issues)!
> We will be happy to add your mod to our repo as long as it follows the [rules](https://github.com/ScrappySM/CarbonLauncher/blob/main/docs/rules.md)!

## License

This project is licensed under The Unlicense - see the [LICENSE](LICENSE) file for details, meaning you can do whatever you want with this template! (yes, you can change the license)
