![asa-list](https://user-images.githubusercontent.com/64005663/151940730-7aec2e05-c4f5-42af-ada3-b35c614826fd.png)

# Tinyman - Algorand Standard Assets List

We are collecting all the icons of projects built on Algorand in one place where everyone can easily access. In this public repository you can check and add the icons of Algorand Standard Assets. Also you can use dynamic link to use these icons on your projects. This repository is being developed with the contributions of ASA makers.

If you have any problems, you can [join Tinyman Discord](https://discord.com/invite/wvHnAdmEv6) and ask your questions about the project in #asa-list channel.

&nbsp;

## Adding your icon

-   First of all, the asset icons should be properly updated for the repository. The following rules must be followed for icons.
    -   The icon must have both **SVG** and **PNG** versions.
    -   Icon sizes should be square, **256x256px** for both SVG and PNG versions. Landscape, portrait icons will not be accepted. *(Icons sent other than 256x256px will not be accepted.)*
    -   Note that these icons will mostly be used in rounded areas. Elements located at the corners of the container may not be visible in some applications.
    -   SVG and PNG files should be consistent. All the elements (colors, size, elements’ position, text elements etc.) should look the same in both versions. **(Grayscale image-traced SVG files will not be accepted.)**
    -   The SVG version must be compatible with web-rendering. These icons will mostly be used in Algorand applications. For example, if the SVG file does not appear in GitHub preview, it means it is not compatible.
    -   The SVG version should mostly not contain images. Your icon should have a vector version. (Again, not grayscale image-traced...)
    -   It would be better if your icons have a background. Icons consisting of pure-black or pure-white elements can cause problems in light mode and dark mode applications.
-   Icon file names should be **`icon.png`** and **`icon.svg`**.
    -   File names are **case-sensitive**. Icon.png or ICON.png will not be accepted.
-   Icon files should be located inside of a folder in the repository. This folder's name should be **`unit_name-asset_id`**, e.g. *"USDC-31566704"* without adding any space.
    -   **Unit names are case sensitive.** Make sure you are typing the exact unit name, paying attention to case sensitivity.
-   If you think you paid attention to all these in your commit, create a pull request. Pull requests should be into `review` branch. When your PR is accepted, it will be merged with the main branch along with the other icons. Empty PRs and icons sent by adding comments will not be accepted.

If you think you have met all the criteria and your PR has not been accepted, you can [join the Tinyman Discord](https://discord.gg/wvHnAdmEv6) and ask your questions in #asa-list channel.

&nbsp;

## Using in your project

You can use all ASA icons here in your projects dynamically. Each time the main branch is updated, the icons will be moved to the server. The following URLs can be used to access a project's icon.

 - `https://asa-icons.s3.eu-central-1.amazonaws.com/` **`asset_id`** `/icon.png`
 - `https://asa-icons.s3.eu-central-1.amazonaws.com/` **`asset_id`** `/icon.svg`

For example, we want to access the icon of USDc.  USDc's asset ID is 31566704. It can be accessed via this URL.

https://asa-icons.s3.eu-central-1.amazonaws.com/31566704/icon.png
