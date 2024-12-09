# Why group?

The extension pack in this repository will only add extensions that are strongly associated with specified programming languages,
so that users can disable the relevant extensions with one click when needed.

Although VS Code already provides tools like [profiles](https://code.visualstudio.com/docs/editor/profiles) to help users manage extensions,
imagine a scenario where I create two profiles for Rust and Python separately.
The Rust profile includes all the extensions I need for Rust development,
and the Python profile also contains the necessary extensions for developing Python applications.
However, if I need to use Rust to develop modules callable by Python,
then I have no choice but to create a new profile that includes all the extensions from both the Rust and Python profiles.

This situation is not uncommon; seeing more and more profiles is frustrating, and switching between different profiles increases cognitive load on users.
Given that [VSCode has no plans to develop categorized extension management](https://github.com/microsoft/vscode/issues/20599), using an extension pack seems like a good solution.
