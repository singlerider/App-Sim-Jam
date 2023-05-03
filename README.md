# App Sim Jam

## Goals

The idea is to empower your ability to create and ideate without the requirement of having a headset available. And if it is available, to get around the requirement of waiting for APK compile times. In this project, you have:

- A properly set-up end-user-ready development environment.
- Unity examples to get you started.

## Setup

- Either clone (requires `git lfs`) or download this project.
- Follow [these instructions](https://developer-docs.magicleap.cloud/docs/guides/unity/getting-started/install-the-tools) to get the ML Hub and Unity Hub installed and set up.
- With the Unity Hub, **the correct version is `2022.2.17f1`**. Double-check that you are installing the correct version.

### Downloading as a ZIP/tarball on MacOS

If you are downloading this project on MacOS as a ZIP (not by cloning), you will get issues regarding not being able to trust the developer. To get past this, in a terminal, run:

```shell
sudo spctl --master-disable
```

This will allow you to choose an option in your Security settings that will allow the project to be opened.

## Running the Project

When the project is loaded, a window for the Project Setup Tool will automatically pop up. This window will, if it is your first time using Unity, open a file explorer — you should select the relevant SDK directory (in this case, `v1.2.0`). After that is selected, click **apply**/**okay**. The Magic Leap Project Setup Tool will still be open. Make sure to click "Apply all" and it will fix your local copy of the project up.

### Getting the App Sim for Unity Running

Follow [these instructions](https://developer-docs.magicleap.cloud/docs/guides/unity/app-simulator/app-sim-unity-zif#running-application-simulator-for-unity) to understand how the App Sim for Unity works.

## Next Steps

Now that everything is working, it's time to follow [our documentation](https://developer-docs.magicleap.cloud/docs/guides/unity/unity-overview) to expand your new project to fit your vision.

## Reporting Errors

If, for whatever reason you experience issues running the Application Simulator(s), you should follow [these instructions](https://developer-docs.magicleap.cloud/docs/guides/developer-tools/ml-hub/error-reporting) to get logs.

Once you have the logs, please make a Topic post in [The Magic Leap 2 Developer Forums in the "App Simulator" Category](https://forum.magicleap.cloud/c/app-simulator/142). A .zip can be added to your post.
