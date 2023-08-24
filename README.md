
<img
    src = 'CuraEngine.ico'
    width = 200
/>

# CuraEngine


*C++ console application for 3D printing GCode generation.*

<br>
<br>

This is a modified version of CuraEngine that is compatible with Cura 5.4.0 that has been compiled for Windows 10 x64.  

This version has 2 modifications:

1.  Addresses a bug in Cura 5.x+ where inner and outer walls are no longer printed consecutively.  This version groups all adjacent walls together reducing unnecessary travels, retractions and other artifacts.
2.  Changes the Outer Wall wipe behavior.  This version will taper off the flow as you approach the end of an extrusion path reducing the blob that is usually left at the Zseam.  This feature is similar to coasting but keeps some pressure on the nozzle to prevent under-extrusion on the next path.  The Outer wall wipe distance parameter will dictate how far from the end of the extrusion to start tapering flow. 

<img
    src = 'OuterWallWipe.png'
    width = 1000
/>
<br>
<br>


This is an experimental branch of CuraEngine with modified behavior, for the original version please visit the following repository: **[CuraEngine]**.

You can use CuraEngine separately, with Cura or integrate it into your own app.

<br>

<!----------------------------------------------------------------------------->

[Contributors]: https://github.com/Ultimaker/CuraEngine/graphs/contributors
[PullRequests]: https://github.com/Ultimaker/CuraEngine/pulls
[Internals]: https://github.com/Ultimaker/CuraEngine/wiki/Internals
[Install]: https://github.com/Ultimaker/CuraEngine/wiki/Building-CuraEngine-From-Source
[Closed]: https://github.com/Ultimaker/CuraEngine/issues?q=is%3Aissue+is%3Aclosed
[Issues]: https://github.com/Ultimaker/CuraEngine/issues
[Conan]: https://github.com/Ultimaker/CuraEngine/actions/workflows/conan-package.yml
[Test]: https://github.com/Ultimaker/CuraEngine/actions/workflows/unit-test.yml
[CuraEngine]: https://github.com/Ultimaker/CuraEngine

[License]: LICENSE
[#]: #


<!---------------------------------[ Badges ]---------------------------------->

[Badge Contributors]: https://img.shields.io/github/contributors/ultimaker/CuraEngine?style=for-the-badge&logoColor=white&labelColor=db5e8a&color=ab4a6c&logo=GitHub
[Badge PullRequests]: https://img.shields.io/github/issues-pr/ultimaker/CuraEngine?style=for-the-badge&logoColor=white&labelColor=bb9f3e&color=937d31&logo=GitExtensions
[Badge License]: https://img.shields.io/badge/License-AGPL3-336887.svg?style=for-the-badge&labelColor=458cb5&logoColor=white&logo=GNU
[Badge Closed]: https://img.shields.io/github/issues-closed/ultimaker/CuraEngine?style=for-the-badge&logoColor=white&labelColor=629944&color=446a30&logo=AddThis
[Badge Issues]: https://img.shields.io/github/issues/ultimaker/CuraEngine?style=for-the-badge&logoColor=white&labelColor=c34360&color=933349&logo=AdBlock
[Badge Conan]: https://img.shields.io/github/workflow/status/Ultimaker/CuraEngine/conan-package?style=for-the-badge&logoColor=white&labelColor=6185aa&color=4c6987&logo=Conan&label=Conan%20Package
[Badge Test]: https://img.shields.io/github/workflow/status/Ultimaker/CuraEngine/unit-test?style=for-the-badge&logoColor=white&labelColor=4a999d&color=346c6e&logo=Codacy&label=Unit%20Test
[Badge Size]: https://img.shields.io/github/repo-size/ultimaker/CuraEngine?style=for-the-badge&logoColor=white&labelColor=715a97&color=584674&logo=GoogleAnalytics


<!---------------------------------[ Buttons ]--------------------------------->


