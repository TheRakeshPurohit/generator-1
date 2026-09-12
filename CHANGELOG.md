# Changelog

## [10.0.0](https://github.com/TheRakeshPurohit/generator-1/compare/v9.1.0...v10.0.0) (2026-09-12)


### ⚠ BREAKING CHANGES

* do not eagerly create destinationRoot folder, create on demand at spawn ([#1852](https://github.com/TheRakeshPurohit/generator-1/issues/1852))
* update execa to v10 ([#1850](https://github.com/TheRakeshPurohit/generator-1/issues/1850))
* drop node 20 support and update dependencies ([#1849](https://github.com/TheRakeshPurohit/generator-1/issues/1849))
* `templatePath()` and `destinationPath()` throw when the resolved path is outside the source/destination root.
* drop github-username dependency ([#1638](https://github.com/TheRakeshPurohit/generator-1/issues/1638))
* update execa to v9 ([#1636](https://github.com/TheRakeshPurohit/generator-1/issues/1636))
* bump required node versions ([#1632](https://github.com/TheRakeshPurohit/generator-1/issues/1632))

### Features

* add allowPackageTemplates feature ([#1855](https://github.com/TheRakeshPurohit/generator-1/issues/1855)) ([a9d69dd](https://github.com/TheRakeshPurohit/generator-1/commit/a9d69dd2a7357ab26c491930166bc3b5f0183c35))
* add configTransform feature ([#1759](https://github.com/TheRakeshPurohit/generator-1/issues/1759)) ([a810814](https://github.com/TheRakeshPurohit/generator-1/commit/a8108148c845ebeb77c6a31cc0751da85700d381))
* add createSimpleGit ([#1771](https://github.com/TheRakeshPurohit/generator-1/issues/1771)) ([5426124](https://github.com/TheRakeshPurohit/generator-1/commit/54261245e5e7e9f53e27f0020abe52f432c5d938))
* add custom context to getContextData and implement setContextData ([#1642](https://github.com/TheRakeshPurohit/generator-1/issues/1642)) ([2c5516b](https://github.com/TheRakeshPurohit/generator-1/commit/2c5516bef1808d88962ef2b422153853f54878f2))
* add disableInGeneratorOptionsSupport feature ([#1701](https://github.com/TheRakeshPurohit/generator-1/issues/1701)) ([ea0950d](https://github.com/TheRakeshPurohit/generator-1/commit/ea0950de6028b3205dd6d9e3f298e1571661e9c8))
* add editorMetadata support to fs helpers ([#1843](https://github.com/TheRakeshPurohit/generator-1/issues/1843)) ([3696d42](https://github.com/TheRakeshPurohit/generator-1/commit/3696d42a381c828d94cd43980c6c1e5ed1651776))
* add generics to Storage ([#1649](https://github.com/TheRakeshPurohit/generator-1/issues/1649)) ([0546e16](https://github.com/TheRakeshPurohit/generator-1/commit/0546e16ceab6198aa400fe408e2644bbf1656545))
* add getContextData ([#1630](https://github.com/TheRakeshPurohit/generator-1/issues/1630)) ([74ff742](https://github.com/TheRakeshPurohit/generator-1/commit/74ff7424c79b9c7845f428c017e4158cfdb0050a))
* add StorageTransform type and update StorageOptions ([#1761](https://github.com/TheRakeshPurohit/generator-1/issues/1761)) ([1684d01](https://github.com/TheRakeshPurohit/generator-1/commit/1684d01283c24f6645489193d9bfdb4499efa9a6))
* create destination root on demand at createSimpleGit ([#1854](https://github.com/TheRakeshPurohit/generator-1/issues/1854)) ([c1c5425](https://github.com/TheRakeshPurohit/generator-1/commit/c1c54250361afe8fe1d6fce126a915340e88f31f))
* do not eagerly create destinationRoot folder, create on demand at spawn ([#1852](https://github.com/TheRakeshPurohit/generator-1/issues/1852)) ([0a14c27](https://github.com/TheRakeshPurohit/generator-1/commit/0a14c271a423c124078f7d71887c5967eaf1b766))
* don't modify original copyOptions and pass fromBasePath to render* methods ([#1581](https://github.com/TheRakeshPurohit/generator-1/issues/1581)) ([9e2195f](https://github.com/TheRakeshPurohit/generator-1/commit/9e2195fcf846ccb19052f121229056f1431f7c61))
* drop github-username dependency ([#1638](https://github.com/TheRakeshPurohit/generator-1/issues/1638)) ([d5947c0](https://github.com/TheRakeshPurohit/generator-1/commit/d5947c04d551a1ea27b7c1ce6fad6c7dd2914f42))
* drop node 20 support and update dependencies ([#1849](https://github.com/TheRakeshPurohit/generator-1/issues/1849)) ([3cff385](https://github.com/TheRakeshPurohit/generator-1/commit/3cff3857ab54d6f06fcce6b62d3de0e9216684b3))
* improve createStorage type ([#1650](https://github.com/TheRakeshPurohit/generator-1/issues/1650)) ([d7704b0](https://github.com/TheRakeshPurohit/generator-1/commit/d7704b08652a6b7974dcba9deadab1d0d3bc6850))
* move `@types/node` to peer dependencies and make it optional. ([#1607](https://github.com/TheRakeshPurohit/generator-1/issues/1607)) ([da5240f](https://github.com/TheRakeshPurohit/generator-1/commit/da5240f3f85cf5c4651dc9faba62707fc13bfcd1))
* optionally use meta.getPackageJson for rootGeneratorName and rootGeneratorVersion ([#1834](https://github.com/TheRakeshPurohit/generator-1/issues/1834)) ([ca58b19](https://github.com/TheRakeshPurohit/generator-1/commit/ca58b198a9c6e038646107a221722dd074dd2a42))
* replace setContextData  with improved getContextData api ([#1643](https://github.com/TheRakeshPurohit/generator-1/issues/1643)) ([96810f6](https://github.com/TheRakeshPurohit/generator-1/commit/96810f66578d4c9d1befa66d5f04e2713d865d0a))
* support 'select' question type and deprecate list type ([#1706](https://github.com/TheRakeshPurohit/generator-1/issues/1706)) ([5ec5b77](https://github.com/TheRakeshPurohit/generator-1/commit/5ec5b7745488376eba74f8fc5e6f50ecca430728))
* throw when `templatePath()`/`destinationPath()` resolve outsid… ([#1848](https://github.com/TheRakeshPurohit/generator-1/issues/1848)) ([fb8de1b](https://github.com/TheRakeshPurohit/generator-1/commit/fb8de1b238ae91a53fc32b2166ac08fe7009f79f))
* update execa to v10 ([#1850](https://github.com/TheRakeshPurohit/generator-1/issues/1850)) ([6f8320f](https://github.com/TheRakeshPurohit/generator-1/commit/6f8320fd3d9f224b79dcf772c12ed6f88ebd018a))


### Bug Fixes

* add return type to avoid complex type generation ([#1795](https://github.com/TheRakeshPurohit/generator-1/issues/1795)) ([ddb534c](https://github.com/TheRakeshPurohit/generator-1/commit/ddb534c0c2011223e428014439e5b445e4793e1c))
* add runtime compatibility for old fs apis ([#1752](https://github.com/TheRakeshPurohit/generator-1/issues/1752)) ([281a9cb](https://github.com/TheRakeshPurohit/generator-1/commit/281a9cb892c2454d350dc863236729c27747dbbc))
* add support to @yeoman/types v1.11.0 ([#1785](https://github.com/TheRakeshPurohit/generator-1/issues/1785)) ([af78c13](https://github.com/TheRakeshPurohit/generator-1/commit/af78c13df6ec3c2aa6b9fed889406e4d08535f2d))
* adjust types ([#1753](https://github.com/TheRakeshPurohit/generator-1/issues/1753)) ([b0cbb5b](https://github.com/TheRakeshPurohit/generator-1/commit/b0cbb5bce620d59deec186a2f4dee702de54f256))
* executeTask should fallback to priority's args ([#1610](https://github.com/TheRakeshPurohit/generator-1/issues/1610)) ([3d9a6da](https://github.com/TheRakeshPurohit/generator-1/commit/3d9a6da2b9da3d1d9e34944f9806a9923a1d932c))
* freeze features object to avoid bugs since it won't propagate to internal features object ([#1713](https://github.com/TheRakeshPurohit/generator-1/issues/1713)) ([711e610](https://github.com/TheRakeshPurohit/generator-1/commit/711e610c978776f06d711ab30db677fb2d77b30a))
* keep resolved as absolute path ([#1580](https://github.com/TheRakeshPurohit/generator-1/issues/1580)) ([97a3bd6](https://github.com/TheRakeshPurohit/generator-1/commit/97a3bd6eb34ffd4565d5d5f275a39580c5ac2f2d))
* loose mem-fs dependency ([#1841](https://github.com/TheRakeshPurohit/generator-1/issues/1841)) ([c3f1758](https://github.com/TheRakeshPurohit/generator-1/commit/c3f17589b692a09b9d7820aafd9fcd86584ebc93))
* move @types/debug to prod dependencies ([#1669](https://github.com/TheRakeshPurohit/generator-1/issues/1669)) ([78b3cbb](https://github.com/TheRakeshPurohit/generator-1/commit/78b3cbb5d6e55a5276c71184840619bfe9c25926))
* pass selected env variables to simple-git ([#1770](https://github.com/TheRakeshPurohit/generator-1/issues/1770)) ([5338470](https://github.com/TheRakeshPurohit/generator-1/commit/53384707c8d0388e613b1cb2f75390347eeb586a))
* readd options to queueTransformStream ([33cbbe5](https://github.com/TheRakeshPurohit/generator-1/commit/33cbbe587b0207f800ed2411c94fe6cebd58ee1f))
* rename override to replacement ([#1644](https://github.com/TheRakeshPurohit/generator-1/issues/1644)) ([cd464fa](https://github.com/TheRakeshPurohit/generator-1/commit/cd464fa648050a2227a037c407cc2a484dd973fb))
* replace Duplex with Transform ([#1577](https://github.com/TheRakeshPurohit/generator-1/issues/1577)) ([6b70b9f](https://github.com/TheRakeshPurohit/generator-1/commit/6b70b9f32c5b31885334b601de0d13f003efa994))
* resolve `moveDestination` source against the destination root ([#1846](https://github.com/TheRakeshPurohit/generator-1/issues/1846)) ([db42587](https://github.com/TheRakeshPurohit/generator-1/commit/db42587643d1a97c47b29cc30b5de8f5115ceee8))
* support delete in Storage proxy's ([#1838](https://github.com/TheRakeshPurohit/generator-1/issues/1838)) ([f0372d3](https://github.com/TheRakeshPurohit/generator-1/commit/f0372d3b421f17c5e718055256c3099b31236645))
* try to avoid could be instantiated with a different subtype of constraint issue ([#1798](https://github.com/TheRakeshPurohit/generator-1/issues/1798)) ([2a83721](https://github.com/TheRakeshPurohit/generator-1/commit/2a837218858bb5384d3873e5a585f9b5123b882a))
* types adjusts ([#1647](https://github.com/TheRakeshPurohit/generator-1/issues/1647)) ([b1a2016](https://github.com/TheRakeshPurohit/generator-1/commit/b1a2016a2920f265fa240ccfbba39f54cd41ab06))
* types adjusts ([#1668](https://github.com/TheRakeshPurohit/generator-1/issues/1668)) ([cd927a6](https://github.com/TheRakeshPurohit/generator-1/commit/cd927a6e2121cf1e3cc626eafa5ca95f8241dc7d))
* types adjusts ([#1760](https://github.com/TheRakeshPurohit/generator-1/issues/1760)) ([d02af1d](https://github.com/TheRakeshPurohit/generator-1/commit/d02af1d70706f173e5fd7801508d62285a860a77))
* types adjusts and bump dependencies ([#1665](https://github.com/TheRakeshPurohit/generator-1/issues/1665)) ([4574b24](https://github.com/TheRakeshPurohit/generator-1/commit/4574b249555fbedea18d9f4a966fda05c3bb4847))
* update proxy behavior to handle raw values and add related tests ([#1762](https://github.com/TheRakeshPurohit/generator-1/issues/1762)) ([0f4dc08](https://github.com/TheRakeshPurohit/generator-1/commit/0f4dc0854a3ec1a6e3ba59b49dcd4fbbf0f7fd85))


### Miscellaneous Chores

* bump required node versions ([#1632](https://github.com/TheRakeshPurohit/generator-1/issues/1632)) ([d07c715](https://github.com/TheRakeshPurohit/generator-1/commit/d07c715b9dbd88c27fd533237ba5d6450cea73b4))
* update execa to v9 ([#1636](https://github.com/TheRakeshPurohit/generator-1/issues/1636)) ([3d1c783](https://github.com/TheRakeshPurohit/generator-1/commit/3d1c783222f4f099c483018928910c2004cf2aff))

## [9.1.0](https://github.com/yeoman/generator/compare/v9.0.0...v9.1.0) (2026-09-12)

### Features

- add allowPackageTemplates feature ([#1855](https://github.com/yeoman/generator/issues/1855)) ([a9d69dd](https://github.com/yeoman/generator/commit/a9d69dd2a7357ab26c491930166bc3b5f0183c35))
- create destination root on demand at createSimpleGit ([#1854](https://github.com/yeoman/generator/issues/1854)) ([c1c5425](https://github.com/yeoman/generator/commit/c1c54250361afe8fe1d6fce126a915340e88f31f))

## [9.0.0](https://github.com/yeoman/generator/compare/v8.4.0...v9.0.0) (2026-09-11)

### ⚠ BREAKING CHANGES

- do not eagerly create destinationRoot folder, create on demand at spawn ([#1852](https://github.com/yeoman/generator/issues/1852))
- update execa to v10 ([#1850](https://github.com/yeoman/generator/issues/1850))
- drop node 20 support and update dependencies ([#1849](https://github.com/yeoman/generator/issues/1849))
- `templatePath()` and `destinationPath()` throw when the resolved path is outside the source/destination root.

### Features

- do not eagerly create destinationRoot folder, create on demand at spawn ([#1852](https://github.com/yeoman/generator/issues/1852)) ([0a14c27](https://github.com/yeoman/generator/commit/0a14c271a423c124078f7d71887c5967eaf1b766))
- drop node 20 support and update dependencies ([#1849](https://github.com/yeoman/generator/issues/1849)) ([3cff385](https://github.com/yeoman/generator/commit/3cff3857ab54d6f06fcce6b62d3de0e9216684b3))
- throw when `templatePath()`/`destinationPath()` resolve outsid… ([#1848](https://github.com/yeoman/generator/issues/1848)) ([fb8de1b](https://github.com/yeoman/generator/commit/fb8de1b238ae91a53fc32b2166ac08fe7009f79f))
- update execa to v10 ([#1850](https://github.com/yeoman/generator/issues/1850)) ([6f8320f](https://github.com/yeoman/generator/commit/6f8320fd3d9f224b79dcf772c12ed6f88ebd018a))

### Bug Fixes

- resolve `moveDestination` source against the destination root ([#1846](https://github.com/yeoman/generator/issues/1846)) ([db42587](https://github.com/yeoman/generator/commit/db42587643d1a97c47b29cc30b5de8f5115ceee8))

## [8.4.0](https://github.com/yeoman/generator/compare/v8.3.2...v8.4.0) (2026-09-07)

### Features

- add editorMetadata support to fs helpers ([#1843](https://github.com/yeoman/generator/issues/1843)) ([3696d42](https://github.com/yeoman/generator/commit/3696d42a381c828d94cd43980c6c1e5ed1651776))

## [8.3.2](https://github.com/yeoman/generator/compare/v8.3.1...v8.3.2) (2026-09-07)

### Bug Fixes

- loose mem-fs dependency ([#1841](https://github.com/yeoman/generator/issues/1841)) ([c3f1758](https://github.com/yeoman/generator/commit/c3f17589b692a09b9d7820aafd9fcd86584ebc93))

## [8.3.1](https://github.com/yeoman/generator/compare/v8.3.0...v8.3.1) (2026-09-05)

### Bug Fixes

- support delete in Storage proxy's ([#1838](https://github.com/yeoman/generator/issues/1838)) ([f0372d3](https://github.com/yeoman/generator/commit/f0372d3b421f17c5e718055256c3099b31236645))

## [8.3.0](https://github.com/yeoman/generator/compare/v8.2.2...v8.3.0) (2026-08-24)

### Features

- optionally use meta.getPackageJson for rootGeneratorName and rootGeneratorVersion ([#1834](https://github.com/yeoman/generator/issues/1834)) ([ca58b19](https://github.com/yeoman/generator/commit/ca58b198a9c6e038646107a221722dd074dd2a42))

## [8.2.2](https://github.com/yeoman/generator/compare/v8.2.1...v8.2.2) (2026-04-29)

### Bug Fixes

- try to avoid could be instantiated with a different subtype of constraint issue ([#1798](https://github.com/yeoman/generator/issues/1798)) ([2a83721](https://github.com/yeoman/generator/commit/2a837218858bb5384d3873e5a585f9b5123b882a))

## [8.2.1](https://github.com/yeoman/generator/compare/v8.2.0...v8.2.1) (2026-04-28)

### Bug Fixes

- add return type to avoid complex type generation ([#1795](https://github.com/yeoman/generator/issues/1795)) ([ddb534c](https://github.com/yeoman/generator/commit/ddb534c0c2011223e428014439e5b445e4793e1c))

## [8.2.0](https://github.com/yeoman/generator/compare/v8.1.2...v8.2.0) (2026-04-28)

### Features

- add createSimpleGit ([#1771](https://github.com/yeoman/generator/issues/1771)) ([5426124](https://github.com/yeoman/generator/commit/54261245e5e7e9f53e27f0020abe52f432c5d938))

### Bug Fixes

- add support to @yeoman/types v1.11.0 ([#1785](https://github.com/yeoman/generator/issues/1785)) ([af78c13](https://github.com/yeoman/generator/commit/af78c13df6ec3c2aa6b9fed889406e4d08535f2d))
- pass selected env variables to simple-git ([#1770](https://github.com/yeoman/generator/issues/1770)) ([5338470](https://github.com/yeoman/generator/commit/53384707c8d0388e613b1cb2f75390347eeb586a))
