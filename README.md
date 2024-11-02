# OpenGisk

OpenGisk is a collaborative documentation project aimed at fostering transparency and awareness in the Android root ecosystem. The project specifically focuses on open-source alternatives for popular Android root modules and frameworks. 

These modules have historically been open-source and developed by respected developers in the community, including developers below to the LSPosed team and many others.

## Background

The Android root community has long benefited from the open-source contributions of talented developers. However, due to issues such as unauthorized modifications, and the use of certain modules in malicious ways (like game cheating applications), some developers have chosen to make their projects closed-source or only release highly obfuscated binaries. While we respect and understand these decisions, we also recognize the potential security risks associated with high-permission, closed-source software.

Modules with elevated privileges play a significant role in device security, as they can directly impact system integrity and user privacy. Therefore, our goal with OpenGisk is to document viable open-source alternatives, allowing the community to continue developing responsibly and securely while fostering transparency.

## Alternatives Table

Below is a list of popular closed-source Android root modules, along with their corresponding open-source alternatives.

**Please note**: Open-source alternatives are often entirely different projects or are based on earlier, open-source versions of the closed projects. This may result in software behavior or outcomes that differ significantly from the original closed-source versions.

| Closed-Source Module                                            | Open-Source Alternative                                       |
|-----------------------------------------------------------------|---------------------------------------------------------------|
| [ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext)             | [ReZygisk](https://github.com/PerformanC/ReZygisk)            |
| [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases) | [Zygisk-Assistant](https://github.com/snake-4/Zygisk-Assistant/issues) |
| [TrickyStore](https://github.com/5ec1cff/TrickyStore) | [TrickyStore master branch (outdated)](https://github.com/5ec1cff/TrickyStore/tree/master) |


## Security and Transparency

For open-source projects, we highly recommend only using software that is compiled and released through **GitHub Actions**. This approach helps ensure that the releases are directly built from the current source code without any modifications. If you have any concerns, you can review the project's CI files yourself to confirm the build process.

E.g., for **ReZygisk**, you can download the release from [GitHub Releases](https://github.com/PerformanC/ReZygisk/releases) and verify the build process by checking the [GitHub Actions workflow](https://github.com/PerformanC/ReZygisk/blob/main/.github/workflows/build.yml).

By following this practice, we aim to enhance transparency and security, reducing the risk of tampered releases in high-permission modules.

## Honoring Key Contributors

We deeply respect these developers for dedicating significant time and expertise to the Android community. Their work has brought unparalleled contributions to open-source projects. While we are saddened by their decision to close-source some of their work, we understand and appreciate the reasons behind it.

| Avatar | Name | GitHub Profile | Closed-Source Projects | Note |
|--------|------|----------------|------------------|------------------|
| ![LSPosed](https://avatars.githubusercontent.com/LSPosed?s=64) | **LSPosed Developers** | [GitHub](https://github.com/LSPosed) | [LSPosed](https://github.com/LSPosed/LSPosed) | LSPosed close-source update https://t.me/LSPosed/287 |
| ![yujincheng08](https://avatars.githubusercontent.com/yujincheng08?s=64) | **yujincheng08** | [GitHub](https://github.com/yujincheng08) | [LSPosed](https://github.com/LSPosed/LSPosed) <br> [Shamiko](https://github.com/LSPosed/LSPosed.github.io) |
| ![Dr-TSNG](https://avatars.githubusercontent.com/Dr-TSNG?s=64) | **Dr-TSNG** | [GitHub](https://github.com/Dr-TSNG) | [ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext) <br> [Shamiko](https://github.com/LSPosed/LSPosed.github.io) <br> [TwiFucker](https://github.com/Dr-TSNG/TwiFucker) |
| ![vvb2060](https://avatars.githubusercontent.com/vvb2060?s=64) | **vvb2060** | [GitHub](https://github.com/vvb2060) | [Magisk alpha](https://github.com/LSPosed/Magisk) |
| ![5ec1cff](https://avatars.githubusercontent.com/5ec1cff?s=64) | **5ec1cff** | [GitHub](https://github.com/5ec1cff) | [TrickyStore](https://github.com/5ec1cff/TrickyStore) | Due to the rampant misuse and the contributions received after open-sourcing being less than expected, this module will be closed-source starting from version 1.1.0.
| ![canyie](https://avatars.githubusercontent.com/canyie?s=64) | **canyie** | [GitHub](https://github.com/canyie) | [LSPosed](https://github.com/LSPosed/LSPosed) |
| ![aviraxp](https://avatars.githubusercontent.com/aviraxp?s=64) | **aviraxp** | [GitHub](https://github.com/aviraxp) | [Shamiko](https://github.com/LSPosed/LSPosed.github.io) |

These developers have made invaluable contributions to the community, and we thank them for their continued efforts to make Android customization safer and more powerful.

## Contributing

We welcome contributions from the community! If you know of additional open-source alternatives or have other ideas on how to improve this documentation, please feel free to open an issue or submit a pull request.

Let's work together to make the Android root ecosystem safer, more transparent, and inclusive for everyone.

## License

OpenGisk is open-sourced under the [MIT license](LICENSE).
