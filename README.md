# Project 7 - WordPress Pen Testing

Time spent: 7 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pen Testing Report

### 1. (Required) Authenticated Stored Cross-Site Scripting (XSS) ID: CVE-2015-5622

- [ ] Summary: 
  - Vulnerability types:XSS
  - Tested in version:4.2
  - Fixed in version:4.2.3
- [ ] GIF Walkthrough: ![GIF 1](https://user-images.githubusercontent.com/111730072/200039607-7967c8c4-7d34-4c86-99d6-abe9540e142e.gif)

- [ ] Steps to recreate: The following code demonstrates the vulnerability. It should be entered in a page or posting using the HTML edit mode
- [ ] Affected source code:
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
  
### 2. (Required) Authenticated Cross-Site Scripting (XSS) via Media File Metadata ID: CVE-2017-6814

- [ ] Summary: 
  - Vulnerability types:XSS
  - Tested in version:4.2
  - Fixed in version: 4.2.13
- [ ] GIF Walkthrough: ![GIF 2](https://user-images.githubusercontent.com/111730072/200040030-b05d342f-3809-4624-99d0-abf56b525e2b.gif)

- [ ] Steps to recreate: Upload MP3 file to the Media Library (as Editor or Administrator) and Insert an Audio Playlist in a Post containing this MP3
- [ ] Affected source code:
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

### 3. (Required) Large File Upload Error XSS ID: CVE-2017-9061

- [ ] Summary: 
  - Vulnerability types:XSS
  - Tested in version:4.2
  - Fixed in version: 4.2.115
- [ ] GIF Walkthrough: ![GIF 3 ](https://user-images.githubusercontent.com/111730072/200040383-c923feb2-56ff-4707-a0d3-039816ffd5ec.gif)

- [ ] Steps to recreate: An attacker can inject a malicious script in to the filename which a victim tries to upload leading to XSS inside the administrators control panel
- [ ] Affected source code:
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

### 4. (Optional) Vulnerability Name or ID

- [ ] Summary: 
  - Vulnerability types:
  - Tested in version:
  - Fixed in version: 
- [ ] GIF Walkthrough: 
- [ ] Steps to recreate: 
- [ ] Affected source code:
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

### 5. (Optional) Vulnerability Name or ID

- [ ] Summary: 
  - Vulnerability types:
  - Tested in version:
  - Fixed in version: 
- [ ] GIF Walkthrough: 
- [ ] Steps to recreate: 
- [ ] Affected source code:
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with  ...
<!-- Recommended GIF Tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

no challenges for all work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
