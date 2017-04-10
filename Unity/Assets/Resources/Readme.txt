There are two specific use cases where the Resources system can be helpful without impeding good development practices:

Resources is an excellent system for during rapid prototyping and experimentation because it is simple and easy to use. However, when a project moves into full production, it is strongly recommended to eliminate uses of the Resources folder.

The Resources folder is also useful in trivial cases, when all of the following conditions are met:

The content stored in the Resources folder is not memory-intense
The content is generally required throughout a project's lifetime
The content rarely requires patching
The content does not vary across platforms or devices.
Examples of this second case include a globally-used prefab hosting singleton MonoBehaviours or an Asset hosting third-party configuration data, such as a Facebook App ID.