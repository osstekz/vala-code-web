---
title: Settings
---

There are a number of settings for the Dart and Flutter extensions that can be modified in VS Code's [User Settings or Workspace Settings](https://code.visualstudio.com/docs/getstarted/settings).

The settings described here are documented by their JSON keys, though most of them can also be edited in the settings UI in VS Code by clicking the **Vala-Code** section under **Extensions**.

* TOC
{:toc}

# Window Scoped Settings

Window scoped settings must be applied in your User Settings or at the workspace level and will apply for all projects open in a window (for example, `vala.sdkPath` is used to launch an analyzer that is used for the whole window).

## vala.code.allowAnalytics
**Default:** `true`.
<br />
Whether to send analytics such as startup timings, frequency of use of features and analysis server crashes.
