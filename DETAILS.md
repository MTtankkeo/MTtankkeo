# How I Fell Into the World of Code

My coding journey began in middle school, when I first became fascinated with Java. I started experimenting with Minecraft scripting, plugins, and mods and I was instantly hooked.

There was something ridiculously exciting about writing code and watching my own world respond. I could create things, change the rules, and decide how everything worked.

Basically, I felt like a god. A god whose world could be defeated by an error message.

<img width="700" src="https://github.com/user-attachments/assets/8eaa99d4-3d2b-4a71-aa0f-66f5b8dfc279" />

## Under the Hood

Soon after, I started learning C, which helped me understand how computers work at a more fundamental level.

Memory leaks stopped being just something that happened. I began to understand *why* they happened: the memory was still there, still taking up space, and nobody was coming to clean it up.

Apparently, allocating memory is easy. Getting your little freeloaders to move out takes more responsibility.

Around this time, I also became increasingly interested in object-oriented programming—organizing code into objects, giving them responsibilities, and figuring out how they should work together.

<img width="600" src="https://github.com/user-attachments/assets/f01cba21-a6a3-4337-9298-7a3430b6d4dd" />

## And Then I Found Flutter

A year or two later, I started exploring web development. That curiosity naturally expanded into mobile apps.

Then I discovered Flutter.

I absolutely fell in love with it. At some point, it stopped feeling like “a framework I enjoy using” and started feeling more like “my favorite character.”

Was I learning a development tool, or joining a fandom? Yes.

<img width="700" src="https://github.com/user-attachments/assets/424709a5-b0d7-44dc-8f93-b1abdd697c0a" />

## The Side Quests Never End

From there, I explored Jetpack Compose. After buying a MacBook, I started learning Swift, which eventually led me to SwiftUI.

“One more thing to learn” had become a recurring theme.

Since then, I’ve continued developing and maintaining packages for both Flutter and Jetpack Compose. Building them is fun; keeping them healthy means coming back to fix bugs, improve things, and give them regular attention.

They’re basically pets, except they ask for dependency updates.

I also had the valuable experience of contributing to the official Flutter SDK. Getting to contribute to something I had enjoyed so much was especially meaningful.

What started with creating my own little Minecraft world had grown into helping build tools that other people could use to create theirs.

And yes, I’m still a Flutter fan.

<img width="700" src="https://github.com/user-attachments/assets/07b3acc0-eef2-4370-8f25-685e2084686a" />

## My Open Sources
I take great pride in building and maintaining tools that solve real problems for developers. Rather than just contributing to existing projects, I've focused on creating my own open source libraries across multiple ecosystems Flutter, Jetpack Compose, React, and Webpack.

From frontend UIs to build toolchains, I enjoy crafting flexible, reusable, and thoughtfully designed packages. My work reflects a balance between practical usability and architectural cleanliness.

Here’s a curated list of my open source projects:

## ![pub.dev](https://github.com/user-attachments/assets/0bb08b23-8478-415c-aacb-44877787dcf7) Dart (Flutter)
These packages are designed to extend Flutter’s core capabilities with powerful, easy-to-use components:

| Name | Published At | Description |
| ---- | ------------ | ----------- |
| [flutter_touch_ripple](https://pub.dev/packages/flutter_touch_ripple) | 2023 _(Second half)_ | Customizable touch ripple effects
| [flutter_touch_scale](https://pub.dev/packages/flutter_touch_scale) | 2025-06-09 | Customizable touch scale effect for Flutter
| [flutter_appbar](https://pub.dev/packages/flutter_appbar) | 2025 | Modular AppBar components
| [flutter_refresh_indicator](https://pub.dev/packages/flutter_refresh_indicator) | 2025 | Elegant pull-to-refresh behavior
| [flutter_chartx](https://pub.dev/packages/flutter_chartx) | 2025 | Lightweight, extensible chart library
| [flutter_rebuildable](https://pub.dev/packages/flutter_rebuildable) | 2025 | Fine-grained rebuild control widget
| [flutter_sized_list_view](https://pub.dev/packages/flutter_sized_list_view) | 2025 | About pre-layout calculation
| [flutter_infinite_scroll_pagination](https://pub.dev/packages/flutter_infinite_scroll_pagination) | 2025-06-03 | A very simple and convenient next-generation alternative to [infinite_scroll_pagination](https://pub.dev/packages/infinite_scroll_pagination).
| [flutter_cached_transition](https://pub.dev/packages/flutter_cached_transition) | 2025-06-29 | Provides customizable widgets that preserve widget state while applying transition animations. |
| [flutter_scroll_bottom_sheet](https://pub.dev/packages/flutter_scroll_bottom_sheet) | 2025-07-29 | A bottom sheet widget that syncs smoothly with scroll events for a seamless UX. |
| [hero_container](https://pub.dev/packages/hero_container) | 2025-08-19 | Smooth animated transitions between widgets using snapshot-based animations. Inspired by OpenContainer with enhanced performance for complex layouts. |
| [keystore_signature](https://pub.dev/packages/keystore_signature) | 2025-10-15 | A Flutter plugin to retrieve Android app signature hash keys and convert them into SHA/MD5 hashes in Hex or Base64 format. |
| [git_config](https://pub.dev/packages/git_config) | 2025-10-17 | A Dart CLI to fetch config files from a remote Git repository into the project. |
| [prepare](https://pub.dev/packages/prepare) | 2025-10-26 | A Dart library that helps manage and configure Dart code generators. |
| [datagen](https://pub.dev/packages/datagen) | 2025-10-26 | A Dart CLI tool for analyzer-based, extremely fast and clean data class code generation. |
| [resourcegen](https://pub.dev/packages/resourcegen) | 2025-10-28 | A Dart CLI tool for generating code for static resources using a prepare-based workflow. |
| [mvvm_service](https://pub.dev/packages/mvvm_service) | 2025-10-29 | A Flutter-native service layer that embraces Flutter dynamic widget lifecycle instead of static provider graphs. |
| [pubspec_version_tool](https://pub.dev/packages/pubspec_version_tool) | 2025-11-30 | A Dart CLI to manage and update the version in pubspec.yaml |

## ![npm](https://github.com/user-attachments/assets/c6e85c28-46ee-4afe-b528-44adfae681e4) NPM (JavaScript / React)
Covering animation, layout systems, utility functions, and build tool enhancements:

| Name | Published At | Description |
| ---- | ------------ | ----------- |
| [animatable-js](https://www.npmjs.com/package/animatable-js), [animatable-jsx](https://www.npmjs.com/package/animatable-jsx) | 2024 | Declarative animation utility for JS/React
| [web-touch-ripple](https://www.npmjs.com/package/web-touch-ripple) | 2024 | Material-style ripple for Web Components
| [web-overlay-layout](https://www.npmjs.com/package/web-overlay-layout) | 2024 _(Second half)_ | Layered layout system for complex UIs
| [css-mangle-webpack-plugin](https://www.npmjs.com/package/css-mangle-webpack-plugin) | 2024 _(Second half)_ | CSS class minification plugin for Webpack
| [html-inline-webpack-plugin](https://www.npmjs.com/package/html-inline-webpack-plugin) | 2024 _(Second half)_ | Inline critical HTML and JS into templates
| [image-encode-loader](https://www.npmjs.com/package/image-encode-loader) | 2024 _(Second half)_ | Webpack loader for encoding images as others formats
| [@web-package/utility](https://www.npmjs.com/package/@web-package/utility) | 2024 _(Second half)_ | Lightweight JS utilities for web apps
| [@web-package/react-widgets](https://www.npmjs.com/package/@web-package/react-widgets) | 2025 | UI components with focus on DX
| [@web-package/react-widgets-router](https://www.npmjs.com/package/@web-package/react-widgets-router) | 2025 | Router-aware widget composition for React

## ![maven](https://github.com/user-attachments/assets/df1d64e0-2864-4ea3-97d8-dbc34f7df8ee) Maven Central (Jetpack Compose)
Focusing on UI consistency and design reusability in Android development:

| Name | Published At | Description |
| ---- | ------------ | ----------- |
| [compose_appbar](https://central.sonatype.com/artifact/dev.ttangkong/compose_appbar) | 2025 | Modular and animated AppBar components for Compose

## 🎯 Why I Do This
Open source isn’t just a side project it's my way of sharing the tools I wish existed, and making development more enjoyable for others. Whether it's improving developer experience, abstracting repetitive logic, or enhancing UI interactivity, I create packages with **real-world use cases and long-term maintainability in mind**!






