By default, Android Studio displays your project files in the **Android** view. This view does not reflect the actual file hierarchy on disk, but is organized by **modules** (a collection of source files and build settings that allow you to divide your project into discrete units of functionality) and file types to simplify navigation between key source files of your project, hiding certain files or directories that are not commonly used. Some of the structural changes compared to the structure on disk include the following:
- Shows all the project's build-related configuration files in a top-level Gradle Script group.
- Shows all manifest files for each module in a module-level group (when you have different manifest files for different product flavors and build types).
- Shows all alternative resource files in a single group, instead of in separate folders per resource qualifier. For example, all density versions of your launcher icon are visible side-by-side.
![](.guides/img/19fileTree2.png)

Within each Android app module, files are shown in the following groups:

- manifests
  - Contains the AndroidManifest.xml file.
- java
  - Contains the Java source code files, separated by package names, including JUnit test code.
- res
  - Contains all non-code resources, such as XML layouts, UI strings, and bitmap images, divided into corresponding sub-directories.


