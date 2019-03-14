# IDT-Fork of conan-protobuf

IDT-fork of [conan-protobuf](https://github.com/bincrafters/conan-protobuf), with OSS fork [here](https://github.com/ilyakrasnovsky/conan-protobuf). The rationale is that the pre-uploaded binaries on bincrafters-public-conan for version 3.5.2 of this are only compatible with conan version > 1.8.0, but we are currently on 1.4.5. The right answer is obvious to upgrade our conan infrastructure, but that is pending this [JIRA issue](https://jira.corp.idtus.com:8443/browse/CR-761). 

## Building (CMD.exe)

* `$> C:\Program Files (x86)\Microsoft Visual Studio 12.0\VC\vcvarsall.bat`
* `$> conan create . bincrafters/stable --profile=/some/profile/containing/cmake_installer`

See this [procedure](http://gitty.corp.idtus.com/core.low/app-logger/snippets/112) for a similar problem with other Conan libraries. 