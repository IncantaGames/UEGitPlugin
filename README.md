Unreal Engine Git Source Control Plugin
-----------------------------------------

UEGitPlugin is a fork of https://github.com/sinbad/UE4GitPlugin (which is a fork of the original https://github.com/SRombauts/UE4GitPlugin) simple Git Source Control Plugin for **Unreal Engine 4.25+ and 5.0+**.

⚠️ This effort currently a WIP with no current support.

An older version of SRombauts's original repo got integrated into the official UE codebase, but this repo provides a much more feature-rich implementation, thanks to the work of @SRombauts and @sinbad. @IncantaGames is taking this further by adding Git submodule support with easy repo creation for submodule via GitHub, GitLab, and Gitea APIs. Lastly, we're also making sure this plugin finally makes it's way to the Unreal Marketplace for easy usage.

To ensure you don't mistake this plugin with other Git source providers, you can find this in your Source Control provider list as **Git by Incanta**.

You need to install it into your Project **Plugins/** folder, and it will overwrite (replace) the default "Git (beta version)" Source Control Provider with the "Git LFS 2" plugin.
