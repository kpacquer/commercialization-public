---
author: joshbax-msft
title: Process Management Test
description: Process Management Test
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 8ce73d7e-e4d3-448b-b6d3-da62442f174e
---

# Process Management Test


This automated test serves as a functional test for the **CreateSection**, **CreateProcess**, **FreeLibrary**, **GetProcAddress**, **LoadLibrary**, **DisableThreadLibraryCalls**, **FreeLibraryAndExitThread**, **GetModuleFileName**, and **GetModuleHandle** functions.

## Test Details


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Associated requirement(s)</strong></p></td>
<td><p>Filter.Driver.AntiVirus.MiniFilterFilter.Driver.AntiVirus.RegistryAndProcessFilter.Driver.FileSystem.MiniFilterFilter.Driver.FileSystem.RegistryAndProcess</p>
<p>See the [filter hardware requirements](http://go.microsoft.com/fwlink/p/?linkid=254485).</p></td>
</tr>
<tr class="even">
<td><p><strong>Platforms</strong></p></td>
<td><p>Windows 8 (x64) Windows 8 (x86) Windows Server 2012 (x64) Windows 7 (x64) Windows 7 (x86) Windows Server 2008 R2 (x64)</p></td>
</tr>
<tr class="odd">
<td><p><strong>Run time</strong></p></td>
<td><p>~1 hour</p></td>
</tr>
</tbody>
</table>

 

## Running the test


For more information about requirements, see [File System Testing Prerequisites](file-system-testing-prerequisites.md).

## Troubleshooting


For troubleshooting information, see [Troubleshooting File System Testing](troubleshooting-file-system-testing.md).

All test cases return Pass or Fail. To review test details, review the test log from Windows Hardware Certification Kit (Windows HCK) Studio.

## <a href="" id="bkmk-moreinformation"></a>More information


### Command syntax

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Command option</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Test</strong></p></td>
<td><p>For detailed information, see the Full Description and Theory of Operation section.</p></td>
</tr>
<tr class="even">
<td><p><strong>-c [string]</strong></p></td>
<td><p>Starts the application and runs the test cases that are specified in the .profile file.</p></td>
</tr>
<tr class="odd">
<td><p><strong>-h [string]</strong></p></td>
<td><p>Specifies the Plug and Play (PnP) ID of the device to be tested.</p></td>
</tr>
<tr class="even">
<td><p><strong>wdk_test.pro</strong></p></td>
<td><p>Specifies the .profile file of test cases to be run.</p></td>
</tr>
</tbody>
</table>

 

**Note**  
For command-line help for this test binary, type **/h**.

 

### File list

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>File</th>
<th>Location</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Modm.exe</p></td>
<td><p><em>&lt;[testbinroot]&gt;</em>\nttest\multimediatest\AVCore\Audio\WDK\</p></td>
</tr>
<tr class="even">
<td><p>Ntlog.dll</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

 

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_hck\p_hck%5D:%20Process%20Management%20Test%20%20RELEASE:%20%284/27/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



