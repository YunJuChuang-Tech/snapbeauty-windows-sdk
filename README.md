# SnapBeauty Windows SDK

Native C SDK for x64 Visual C++ projects. Requires Windows 10 version 1809 or
later and a vendor OpenGL 2.1+ driver with framebuffer objects.

1. Download the `SnapBeauty.Windows.1.3.6.nupkg` attachment from the release.
2. Add the containing folder as a NuGet package source in Visual Studio.
3. Select the local source and install `SnapBeauty.Windows` version `1.3.6` into the x64 C++ project.

The package configures the public header and import library and copies
`snapbeauty.dll` and `Assets/` beside the executable at build time.
Request a separate Windows license bound to the application ID and the
certificate fingerprint of the signed host executable.
