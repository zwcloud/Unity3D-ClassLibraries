This project is created for any .NET Project referencing `UnityEngine.dll` and `UnityEditor.dll`.

# Why

It's useful when build a .NET Project on a remote build pipeline or CI/CD such as VSTS. Because only only the dlls are needed for such projects.

# Usage

1. Add this repo as a submodule in the root directoy of your main project repo.
2. In your main project, add reference to `<relative-path-to>/Unity3D-ClassLibraries\<UnityVersion>/UnityEngine.dll`
