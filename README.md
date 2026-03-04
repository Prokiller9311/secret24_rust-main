<?xml version="1.0" encoding="utf-8"?>
<Project ToolsVersion="4.0" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
  <ItemGroup>
    <Filter Include="Source Files">
      <UniqueIdentifier>{4FC737F1-C7A5-4376-A066-2A32D752A2FF}</UniqueIdentifier>
      <Extensions>cpp;c;cc;cxx;c++;cppm;ixx;def;odl;idl;hpj;bat;asm;asmx</Extensions>
    </Filter>
    <Filter Include="Header Files">
      <UniqueIdentifier>{93995380-89BD-4b04-88EB-625FBE52EBFB}</UniqueIdentifier>
      <Extensions>h;hh;hpp;hxx;h++;hm;inl;inc;ipp;xsd</Extensions>
    </Filter>
    <Filter Include="Header Files\utils">
      <UniqueIdentifier>{844e9c29-76ef-4dfa-be0b-2aafc7ad1f0e}</UniqueIdentifier>
    </Filter>
    <Filter Include="Header Files\features">
      <UniqueIdentifier>{5ef89ec2-c694-4470-b1d2-2a7dc93605b3}</UniqueIdentifier>
    </Filter>
    <Filter Include="Header Files\game">
      <UniqueIdentifier>{99384470-5e29-42eb-9d29-be0063c3694a}</UniqueIdentifier>
    </Filter>
    <Filter Include="Source Files\features">
      <UniqueIdentifier>{5a2ce6d9-2570-485c-911c-f26308ab9c95}</UniqueIdentifier>
    </Filter>
    <Filter Include="Source Files\utils">
      <UniqueIdentifier>{ee1b8dc2-c8d6-44d9-86fe-31e0d5d15f9f}</UniqueIdentifier>
    </Filter>
    <Filter Include="Source Files\game">
      <UniqueIdentifier>{863337e4-8c56-40db-9871-7a732b3a20e3}</UniqueIdentifier>
    </Filter>
    <Filter Include="Header Files\hooks">
      <UniqueIdentifier>{7a6fdb0d-b06e-4e39-aa73-54d2502186ee}</UniqueIdentifier>
    </Filter>
    <Filter Include="Header Files\hooks\baseplayer">
      <UniqueIdentifier>{e2df53a4-6369-4c26-8e4d-4b410ca6611e}</UniqueIdentifier>
    </Filter>
    <Filter Include="Header Files\hooks\performanceui">
      <UniqueIdentifier>{b543191b-9993-4a82-a126-4054c5afe2c8}</UniqueIdentifier>
    </Filter>
    <Filter Include="Header Files\hooks\ddraw">
      <UniqueIdentifier>{8b134599-ae05-4296-a1b4-40582b2e696d}</UniqueIdentifier>
    </Filter>
    <Filter Include="Source Files\Resource Files">
      <UniqueIdentifier>{67DA6AB6-F800-4c08-8B7A-83BB121AAD01}</UniqueIdentifier>
      <Extensions>rc;ico;cur;bmp;dlg;rc2;rct;bin;rgs;gif;jpg;jpeg;jpe;resx;tiff;tif;png;wav;mfcribbon-ms</Extensions>
    </Filter>
  </ItemGroup>
  <ItemGroup>
    <ClCompile Include="source_main.cpp">
      <Filter>Source Files</Filter>
    </ClCompile>
    <ClCompile Include="core\game\offsets.cpp">
      <Filter>Source Files\utils</Filter>
    </ClCompile>
    <ClCompile Include="core\utilities\math.cpp">
      <Filter>Source Files\utils</Filter>
    </ClCompile>
    <ClCompile Include="core\utilities\memory.cpp">
      <Filter>Source Files\utils</Filter>
    </ClCompile>
    <ClCompile Include="core\game\il2cpp.cpp">
      <Filter>Source Files\utils</Filter>
    </ClCompile>
    <ClCompile Include="core\game\sdk.cpp">
      <Filter>Source Files\game</Filter>
    </ClCompile>
    <ClCompile Include="core\features\visuals\esp.cpp">
      <Filter>Source Files\features</Filter>
    </ClCompile>
    <ClCompile Include="core\features\aimbot\aimbot.cpp">
      <Filter>Source Files\features</Filter>
    </ClCompile>
    <ClCompile Include="core\features\aimbot\aimbot_data.cpp">
      <Filter>Source Files</Filter>
    </ClCompile>
    <ClCompile Include="core\features\visuals\world_esp.cpp">
      <Filter>Source Files</Filter>
    </ClCompile>
    <ClCompile Include="core\features\menu\gui_hook.cpp">
      <Filter>Source Files</Filter>
    </ClCompile>
    <ClCompile Include="core\features\menu\framework\gui_framework.cpp">
      <Filter>Source Files</Filter>
    </ClCompile>
    <ClCompile Include="core\features\menu\cfg.cpp">
      <Filter>Source Files</Filter>
    </ClCompile>
    <ClCompile Include="core\features\menu\menu_tabs.cpp">
      <Filter>Source Files</Filter>
    </ClCompile>
    <ClCompile Include="core\game\render\render.cpp">
      <Filter>Source Files</Filter>
    </ClCompile>
  </ItemGroup>
  <ItemGroup>
    <ClInclude Include="core\includes\includes.hpp">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\game\sdk.hpp">
      <Filter>Header Files\game</Filter>
    </ClInclude>
    <ClInclude Include="core\game\offsets.hpp">
      <Filter>Header Files\game</Filter>
    </ClInclude>
    <ClInclude Include="core\game\hooks.hpp">
      <Filter>Header Files\game</Filter>
    </ClInclude>
    <ClInclude Include="core\utilities\xor.hpp">
      <Filter>Header Files\utils</Filter>
    </ClInclude>
    <ClInclude Include="core\game\il2cpp.hpp">
      <Filter>Header Files\utils</Filter>
    </ClInclude>
    <ClInclude Include="core\utilities\lazy_importer.hpp">
      <Filter>Header Files\utils</Filter>
    </ClInclude>
    <ClInclude Include="core\utilities\math.hpp">
      <Filter>Header Files\utils</Filter>
    </ClInclude>
    <ClInclude Include="core\utilities\memory.hpp">
      <Filter>Header Files\utils</Filter>
    </ClInclude>
    <ClInclude Include="core\utilities\returnspoofer.hpp">
      <Filter>Header Files\utils</Filter>
    </ClInclude>
    <ClInclude Include="core\features\menu\framework\gui_framework.h">
      <Filter>Header Files\utils</Filter>
    </ClInclude>
    <ClInclude Include="core\includes\hinclude.h">
      <Filter>Header Files\hooks</Filter>
    </ClInclude>
    <ClInclude Include="core\hooks\player_related.h">
      <Filter>Header Files\hooks\baseplayer</Filter>
    </ClInclude>
    <ClInclude Include="core\features\visuals\esp.h">
      <Filter>Header Files\features</Filter>
    </ClInclude>
    <ClInclude Include="core\features\aimbot\aimbot.h">
      <Filter>Header Files\features</Filter>
    </ClInclude>
    <ClInclude Include="core\hooks\weapon_related.h">
      <Filter>Header Files\hooks\baseplayer</Filter>
    </ClInclude>
    <ClInclude Include="core\features\visuals\world_esp.hpp">
      <Filter>Header Files\hooks\baseplayer</Filter>
    </ClInclude>
    <ClInclude Include="core\features\options.h">
      <Filter>Header Files\features</Filter>
    </ClInclude>
    <ClInclude Include="core\includes\fnv1a.hpp">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\vector\vector2.hpp">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\vector\vector3.hpp">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\vector\vector4.hpp">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\vector\color.hpp">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\game\enums.hpp">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\features\menu\gui_hook.h">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\features\menu\cfg.h">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\features\menu\menu_tabs.h">
      <Filter>Header Files</Filter>
    </ClInclude>
    <ClInclude Include="core\game\render\render.h">
      <Filter>Header Files</Filter>
    </ClInclude>
  </ItemGroup>
</Project>
<?xml version="1.0" encoding="utf-8"?>
<Project ToolsVersion="Current" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
  <PropertyGroup>
    <ShowAllFiles>true</ShowAllFiles>
  </PropertyGroup>
</Project>

Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio Version 17
VisualStudioVersion = 17.3.32929.385
MinimumVisualStudioVersion = 10.0.40219.1
Project("{8BC9CEB8-8B4A-11D0-8D11-00A0C91BC942}") = "secret_sdk24", "secret_base24.vcxproj", "{0678EC97-C0F5-4F7A-A230-561A65F33499}"
EndProject
Global
	GlobalSection(SolutionConfigurationPlatforms) = preSolution
		debug|x64 = debug|x64
		debug|x86 = debug|x86
		stable|x64 = stable|x64
		stable|x86 = stable|x86
	EndGlobalSection
	GlobalSection(ProjectConfigurationPlatforms) = postSolution
		{0678EC97-C0F5-4F7A-A230-561A65F33499}.debug|x64.ActiveCfg = Debug|x64
		{0678EC97-C0F5-4F7A-A230-561A65F33499}.debug|x64.Build.0 = Debug|x64
		{0678EC97-C0F5-4F7A-A230-561A65F33499}.debug|x86.ActiveCfg = Debug|x64
		{0678EC97-C0F5-4F7A-A230-561A65F33499}.stable|x64.ActiveCfg = Release|x64
		{0678EC97-C0F5-4F7A-A230-561A65F33499}.stable|x64.Build.0 = Release|x64
		{0678EC97-C0F5-4F7A-A230-561A65F33499}.stable|x86.ActiveCfg = Release|Win32
		{0678EC97-C0F5-4F7A-A230-561A65F33499}.stable|x86.Build.0 = Release|Win32
	EndGlobalSection
	GlobalSection(SolutionProperties) = preSolution
		HideSolutionNode = FALSE
	EndGlobalSection
	GlobalSection(ExtensibilityGlobals) = postSolution
		SolutionGuid = {BA4B5B24-92AA-458D-A465-8713A1535B4C}
	EndGlobalSection
EndGlobal

#include <Windows.h>
#include "core/includes/includes.hpp"
#include "core/game/hooks.hpp"
#include "core/game/offsets.hpp"
#include "core/game/sdk.hpp"

unsigned long main( void* ) {

    il2mgr::init( ); // would look pretty dope if i'd space it out
    {
        hooks::init( );
    }
    return 0;
}

bool DllMain( void* arg1, unsigned long reason, void* r ) {
    if( reason != 1 )
        return false;

    const auto handle = CreateThread( nullptr, 0, &main, nullptr, 0, nullptr );
    if( handle ) // make sure handle has a valid pointer.
        CloseHandle( handle );

    return true;
}
#pragma once
/*
The MIT License ( MIT )

PASTA PASTA PASTA PASTA PASTA PASTA PASTA PASTA PASTA PASTA PASTA PASTA

Copyright ( c ) 2018 Ivor Wanders

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files ( the "Software" ), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
*/
#ifndef COMPILE_TIME_CRC_H
#define COMPILE_TIME_CRC_H

#include <cstdint>
#include <type_traits>

// Based on code from Python's crcmod module. Polynomial "crc-32".
// polynomial: 0x104C11DB7, bit reverse algorithm: 
//  crcmod.Crc( 0x104C11DB7, initCrc=0, xorOut=0xFFFFFFFF )

namespace crcdetail
{
	static constexpr const uint32_t table[256] =
	{
		0x00000000U, 0x77073096U, 0xEE0E612CU, 0x990951BAU, 0x076DC419U,
		0x706AF48FU, 0xE963A535U, 0x9E6495A3U, 0x0EDB8832U, 0x79DCB8A4U,
		0xE0D5E91EU, 0x97D2D988U, 0x09B64C2BU, 0x7EB17CBDU, 0xE7B82D07U,
		0x90BF1D91U, 0x1DB71064U, 0x6AB020F2U, 0xF3B97148U, 0x84BE41DEU,
		0x1ADAD47DU, 0x6DDDE4EBU, 0xF4D4B551U, 0x83D385C7U, 0x136C9856U,
		0x646BA8C0U, 0xFD62F97AU, 0x8A65C9ECU, 0x14015C4FU, 0x63066CD9U,
		0xFA0F3D63U, 0x8D080DF5U, 0x3B6E20C8U, 0x4C69105EU, 0xD56041E4U,
		0xA2677172U, 0x3C03E4D1U, 0x4B04D447U, 0xD20D85FDU, 0xA50AB56BU,
		0x35B5A8FAU, 0x42B2986CU, 0xDBBBC9D6U, 0xACBCF940U, 0x32D86CE3U,
		0x45DF5C75U, 0xDCD60DCFU, 0xABD13D59U, 0x26D930ACU, 0x51DE003AU,
		0xC8D75180U, 0xBFD06116U, 0x21B4F4B5U, 0x56B3C423U, 0xCFBA9599U,
		0xB8BDA50FU, 0x2802B89EU, 0x5F058808U, 0xC60CD9B2U, 0xB10BE924U,
		0x2F6F7C87U, 0x58684C11U, 0xC1611DABU, 0xB6662D3DU, 0x76DC4190U,
		0x01DB7106U, 0x98D220BCU, 0xEFD5102AU, 0x71B18589U, 0x06B6B51FU,
		0x9FBFE4A5U, 0xE8B8D433U, 0x7807C9A2U, 0x0F00F934U, 0x9609A88EU,
		0xE10E9818U, 0x7F6A0DBBU, 0x086D3D2DU, 0x91646C97U, 0xE6635C01U,
		0x6B6B51F4U, 0x1C6C6162U, 0x856530D8U, 0xF262004EU, 0x6C0695EDU,
		0x1B01A57BU, 0x8208F4C1U, 0xF50FC457U, 0x65B0D9C6U, 0x12B7E950U,
		0x8BBEB8EAU, 0xFCB9887CU, 0x62DD1DDFU, 0x15DA2D49U, 0x8CD37CF3U,
		0xFBD44C65U, 0x4DB26158U, 0x3AB551CEU, 0xA3BC0074U, 0xD4BB30E2U,
		0x4ADFA541U, 0x3DD895D7U, 0xA4D1C46DU, 0xD3D6F4FBU, 0x4369E96AU,
		0x346ED9FCU, 0xAD678846U, 0xDA60B8D0U, 0x44042D73U, 0x33031DE5U,
		0xAA0A4C5FU, 0xDD0D7CC9U, 0x5005713CU, 0x270241AAU, 0xBE0B1010U,
		0xC90C2086U, 0x5768B525U, 0x206F85B3U, 0xB966D409U, 0xCE61E49FU,
		0x5EDEF90EU, 0x29D9C998U, 0xB0D09822U, 0xC7D7A8B4U, 0x59B33D17U,
		0x2EB40D81U, 0xB7BD5C3BU, 0xC0BA6CADU, 0xEDB88320U, 0x9ABFB3B6U,
		0x03B6E20CU, 0x74B1D29AU, 0xEAD54739U, 0x9DD277AFU, 0x04DB2615U,
		0x73DC1683U, 0xE3630B12U, 0x94643B84U, 0x0D6D6A3EU, 0x7A6A5AA8U,
		0xE40ECF0BU, 0x9309FF9DU, 0x0A00AE27U, 0x7D079EB1U, 0xF00F9344U,
		0x8708A3D2U, 0x1E01F268U, 0x6906C2FEU, 0xF762575DU, 0x806567CBU,
		0x196C3671U, 0x6E6B06E7U, 0xFED41B76U, 0x89D32BE0U, 0x10DA7A5AU,
		0x67DD4ACCU, 0xF9B9DF6FU, 0x8EBEEFF9U, 0x17B7BE43U, 0x60B08ED5U,
		0xD6D6A3E8U, 0xA1D1937EU, 0x38D8C2C4U, 0x4FDFF252U, 0xD1BB67F1U,
		0xA6BC5767U, 0x3FB506DDU, 0x48B2364BU, 0xD80D2BDAU, 0xAF0A1B4CU,
		0x36034AF6U, 0x41047A60U, 0xDF60EFC3U, 0xA867DF55U, 0x316E8EEFU,
		0x4669BE79U, 0xCB61B38CU, 0xBC66831AU, 0x256FD2A0U, 0x5268E236U,
		0xCC0C7795U, 0xBB0B4703U, 0x220216B9U, 0x5505262FU, 0xC5BA3BBEU,
		0xB2BD0B28U, 0x2BB45A92U, 0x5CB36A04U, 0xC2D7FFA7U, 0xB5D0CF31U,
		0x2CD99E8BU, 0x5BDEAE1DU, 0x9B64C2B0U, 0xEC63F226U, 0x756AA39CU,
		0x026D930AU, 0x9C0906A9U, 0xEB0E363FU, 0x72076785U, 0x05005713U,
		0x95BF4A82U, 0xE2B87A14U, 0x7BB12BAEU, 0x0CB61B38U, 0x92D28E9BU,
		0xE5D5BE0DU, 0x7CDCEFB7U, 0x0BDBDF21U, 0x86D3D2D4U, 0xF1D4E242U,
		0x68DDB3F8U, 0x1FDA836EU, 0x81BE16CDU, 0xF6B9265BU, 0x6FB077E1U,
		0x18B74777U, 0x88085AE6U, 0xFF0F6A70U, 0x66063BCAU, 0x11010B5CU,
		0x8F659EFFU, 0xF862AE69U, 0x616BFFD3U, 0x166CCF45U, 0xA00AE278U,
		0xD70DD2EEU, 0x4E048354U, 0x3903B3C2U, 0xA7672661U, 0xD06016F7U,
		0x4969474DU, 0x3E6E77DBU, 0xAED16A4AU, 0xD9D65ADCU, 0x40DF0B66U,
		0x37D83BF0U, 0xA9BCAE53U, 0xDEBB9EC5U, 0x47B2CF7FU, 0x30B5FFE9U,
		0xBDBDF21CU, 0xCABAC28AU, 0x53B39330U, 0x24B4A3A6U, 0xBAD03605U,
		0xCDD70693U, 0x54DE5729U, 0x23D967BFU, 0xB3667A2EU, 0xC4614AB8U,
		0x5D681B02U, 0x2A6F2B94U, 0xB40BBE37U, 0xC30C8EA1U, 0x5A05DF1BU,
		0x2D02EF8DU
	};

	constexpr uint32_t compute( const char* data, uint32_t len, uint32_t crc = 0 ) {
		crc = crc ^ 0xFFFFFFFFU;
		for( uint32_t i = 0; i < len; i++ ) {
			crc = table[( *data ^ crc ) & 0xFF] ^ ( crc >> 8 );
			data++;
		}
		crc = crc ^ 0xFFFFFFFFU;
		return crc;
	}

	constexpr uint32_t compute( const wchar_t* data, uint32_t len, uint32_t crc = 0 ) {
		crc = crc ^ 0xFFFFFFFFU;
		for( uint32_t i = 0; i < len; i++ ) {
			crc = table[( *data ^ crc ) & 0xFF] ^ ( crc >> 8 );
			data++;
		}
		crc = crc ^ 0xFFFFFFFFU;
		return crc;
	}
}  // namespace crcdetail

// Macro to be used, guarantees hash is computed at compile time.
#define STATIC_CRC32( A )                                                           \
    std::integral_constant<uint32_t, crcdetail::compute( A, sizeof( A )-1 )>::value

#define RUNTIME_CRC32( B ) crcdetail::compute( B, strlen( B ) )
#define RUNTIME_CRC32_W( B ) crcdetail::compute( B, wcslen( B ) )

#endif  // COMPILE_TIME_CRC_H
<?xml version="1.0" encoding="utf-8"?>
<Project DefaultTargets="Build" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
  <ItemGroup Label="ProjectConfigurations">
    <ProjectConfiguration Include="Debug|x64">
      <Configuration>Debug</Configuration>
      <Platform>x64</Platform>
    </ProjectConfiguration>
    <ProjectConfiguration Include="Release|x64">
      <Configuration>Release</Configuration>
      <Platform>x64</Platform>
    </ProjectConfiguration>
  </ItemGroup>
  <PropertyGroup Label="Globals">
    <VCProjectVersion>16.0</VCProjectVersion>
    <Keyword>Win32Proj</Keyword>
    <ProjectGuid>{0678ec97-c0f5-4f7a-a230-561a65f33499}</ProjectGuid>
    <RootNamespace>rust base</RootNamespace>
    <WindowsTargetPlatformVersion>10.0</WindowsTargetPlatformVersion>
    <ProjectName>secret_sdk24</ProjectName>
  </PropertyGroup>
  <Import Project="$(VCTargetsPath)\Microsoft.Cpp.Default.props" />
  <PropertyGroup Condition="'$(Configuration)|$(Platform)'=='Debug|x64'" Label="Configuration">
    <ConfigurationType>DynamicLibrary</ConfigurationType>
    <UseDebugLibraries>true</UseDebugLibraries>
    <PlatformToolset>v145</PlatformToolset>
    <CharacterSet>MultiByte</CharacterSet>
    <UseOfMfc>false</UseOfMfc>
  </PropertyGroup>
  <PropertyGroup Condition="'$(Configuration)|$(Platform)'=='Release|x64'" Label="Configuration">
    <ConfigurationType>DynamicLibrary</ConfigurationType>
    <UseDebugLibraries>true</UseDebugLibraries>
    <PlatformToolset>v145</PlatformToolset>
    <WholeProgramOptimization>true</WholeProgramOptimization>
    <CharacterSet>MultiByte</CharacterSet>
    <UseOfMfc>false</UseOfMfc>
  </PropertyGroup>
  <Import Project="$(VCTargetsPath)\Microsoft.Cpp.props" />
  <ImportGroup Label="ExtensionSettings">
    <Import Project="$(VCTargetsPath)\BuildCustomizations\masm.props" />
  </ImportGroup>
  <ImportGroup Label="Shared">
  </ImportGroup>
  <ImportGroup Label="PropertySheets" Condition="'$(Configuration)|$(Platform)'=='Debug|x64'">
    <Import Project="$(UserRootDir)\Microsoft.Cpp.$(Platform).user.props" Condition="exists('$(UserRootDir)\Microsoft.Cpp.$(Platform).user.props')" Label="LocalAppDataPlatform" />
  </ImportGroup>
  <ImportGroup Label="PropertySheets" Condition="'$(Configuration)|$(Platform)'=='Release|x64'">
    <Import Project="$(UserRootDir)\Microsoft.Cpp.$(Platform).user.props" Condition="exists('$(UserRootDir)\Microsoft.Cpp.$(Platform).user.props')" Label="LocalAppDataPlatform" />
  </ImportGroup>
  <PropertyGroup Label="UserMacros" />
  <PropertyGroup Condition="'$(Configuration)|$(Platform)'=='Release|x64'">
    <TargetName>$(ProjectName)</TargetName>
    <IntDir>$(SolutionDir)\trash</IntDir>
    <IncludePath>C:\Users\Shadow\Desktop\Bypasses\injector;$(IncludePath)</IncludePath>
    <LibraryPath>C:\Users\Shadow\Desktop\Bypasses\injector\x64\Release;$(LibraryPath)</LibraryPath>
    <OutDir>$(SolutionDir)\binaries\$(Configuration)\</OutDir>
  </PropertyGroup>
  <PropertyGroup Condition="'$(Configuration)|$(Platform)'=='Debug|x64'">
    <TargetExt>.dll</TargetExt>
  </PropertyGroup>
  <ItemDefinitionGroup Condition="'$(Configuration)|$(Platform)'=='Debug|x64'">
    <ClCompile>
      <WarningLevel>Level3</WarningLevel>
      <SDLCheck>true</SDLCheck>
      <PreprocessorDefinitions>_DEBUG;_CONSOLE;%(PreprocessorDefinitions)</PreprocessorDefinitions>
      <ConformanceMode>true</ConformanceMode>
      <LanguageStandard>stdcpp20</LanguageStandard>
      <LanguageStandard_C>stdc17</LanguageStandard_C>
      <DebugInformationFormat>ProgramDatabase</DebugInformationFormat>
    </ClCompile>
    <Link>
      <SubSystem>Console</SubSystem>
      <GenerateDebugInformation>true</GenerateDebugInformation>
      <AssemblyDebug>true</AssemblyDebug>
    </Link>
  </ItemDefinitionGroup>
  <ItemDefinitionGroup Condition="'$(Configuration)|$(Platform)'=='Release|x64'">
    <ClCompile>
      <WarningLevel>Level3</WarningLevel>
      <FunctionLevelLinking>true</FunctionLevelLinking>
      <IntrinsicFunctions>true</IntrinsicFunctions>
      <SDLCheck>true</SDLCheck>
      <PreprocessorDefinitions>NDEBUG;_CONSOLE;%(PreprocessorDefinitions)</PreprocessorDefinitions>
      <ConformanceMode>true</ConformanceMode>
      <LanguageStandard>stdcpp20</LanguageStandard>
      <LanguageStandard_C>stdc17</LanguageStandard_C>
      <Optimization>MinSpace</Optimization>
      <RuntimeLibrary>MultiThreaded</RuntimeLibrary>
      <DebugInformationFormat>None</DebugInformationFormat>
      <BasicRuntimeChecks>Default</BasicRuntimeChecks>
      <InlineFunctionExpansion>OnlyExplicitInline</InlineFunctionExpansion>
      <WholeProgramOptimization>true</WholeProgramOptimization>
      <FavorSizeOrSpeed>Speed</FavorSizeOrSpeed>
    </ClCompile>
    <Link>
      <SubSystem>Console</SubSystem>
      <EnableCOMDATFolding>true</EnableCOMDATFolding>
      <OptimizeReferences>true</OptimizeReferences>
      <GenerateDebugInformation>false</GenerateDebugInformation>
    </Link>
  </ItemDefinitionGroup>
  <ItemGroup>
    <ClCompile Include="core\features\aimbot\aimbot.cpp" />
    <ClCompile Include="core\features\aimbot\aimbot_data.cpp" />
    <ClCompile Include="core\features\menu\cfg.cpp" />
    <ClCompile Include="core\features\menu\framework\gui_framework.cpp" />
    <ClCompile Include="core\features\menu\gui_hook.cpp" />
    <ClCompile Include="core\features\menu\menu_tabs.cpp" />
    <ClCompile Include="core\features\visuals\esp.cpp" />
    <ClCompile Include="core\features\visuals\world_esp.cpp" />
    <ClCompile Include="core\game\render\render.cpp" />
    <ClCompile Include="core\game\sdk.cpp" />
    <ClCompile Include="core\game\il2cpp.cpp" />
    <ClCompile Include="core\game\offsets.cpp" />
    <ClCompile Include="source_main.cpp" />
    <ClCompile Include="core\utilities\math.cpp" />
    <ClCompile Include="core\utilities\memory.cpp" />
  </ItemGroup>
  <ItemGroup>
    <ClInclude Include="core\features\aimbot\aimbot.h" />
    <ClInclude Include="core\features\menu\cfg.h" />
    <ClInclude Include="core\features\menu\gui_hook.h" />
    <ClInclude Include="core\features\menu\menu_tabs.h" />
    <ClInclude Include="core\game\render\render.h" />
    <ClInclude Include="core\hooks\weapon_related.h" />
    <ClInclude Include="core\hooks\player_related.h" />
    <ClInclude Include="core\features\visuals\esp.h" />
    <ClInclude Include="core\includes\fnv1a.hpp" />
    <ClInclude Include="core\game\enums.hpp" />
    <ClInclude Include="core\game\sdk.hpp" />
    <ClInclude Include="core\game\hooks.hpp" />
    <ClInclude Include="core\game\il2cpp.hpp" />
    <ClInclude Include="core\game\offsets.hpp" />
    <ClInclude Include="core\features\menu\framework\gui_framework.h" />
    <ClInclude Include="core\includes\hinclude.h" />
    <ClInclude Include="core\includes\includes.hpp" />
    <ClInclude Include="core\features\options.h" />
    <ClInclude Include="core\vector\color.hpp" />
    <ClInclude Include="core\vector\vector2.hpp" />
    <ClInclude Include="core\vector\vector3.hpp" />#pragma once
#include "../../includes/includes.hpp"
#include "../../game/sdk.hpp"

class c_aimbot {
public:
	std::array< bone_list, 19 > scanning_bones = {
		head, spine1, spine2, spine3, spine4, pelvis, penis, neck,
		l_breast, r_breast, r_eye, l_eye, r_hip, r_knee,
		l_knee, l_hip, l_upperarm, r_upperarm, l_hip
	};

	void get_best_player( );
	void get_best_bone( );
	std::string get_key_from_combo( int key );
	void smooth_angles( vec2_t& angles, vec2_t local_view_angles );

	struct proj_weapon_mod
	{
		bool enabled{ };
		float scalar{ }, offset{ };
	};

	void update_weapon_information( );

	void start_movement_simulation( vec3_t& aim_pos, const vec3_t& from );

	// context..
	void process( );

	/*\ crucial data region /*/
	int aim_key;

	int aimbot_bone{ };
	vec2_t aim_angle{ };
	vec3_t shoot_position{ }, psilent_aim_angle{ };
	core::base_player* target{ };
	core::base_entity* best_helicopter{ };

	float bullet_speed{ FLT_MAX },
		bullet_gravity{ FLT_MAX },
		drag{ FLT_MAX }, closest_distance{ FLT_MAX };

	bool is_in_aim = false;
};

extern c_aimbot g_aimbot;
#include "aimbot.h"
#include "../options.h"
#include "../visuals/esp.h"

void c_aimbot::get_best_player( ) {
    target = NULL; // k to the y to the s
    closest_distance = FLT_MAX;

    for( int i = 0; i < g_cheat.player_list.size( ); i++ ) {
        core::base_player* player = g_cheat.player_list.at( i ).first;
		if( !player )
			continue;

        core::player_model* model = player->get_model( );
		if( !model )
			continue;

        float dist_to = g_cheat.local_pos.distance( model->get_position( ) );
        if( dist_to > options::aimbot::max_target_distance )
            continue;

		if( ( player->is_sleeping( ) 
            && !options::aimbot::aim_sleepers )
            || player->get_life_state( ) /* let's ignore dead players */
            || player == g_cheat.local
            || ( model->is_npc( ) 
            && !options::aimbot::aim_npc
            || ( player->is_knocked( )
            && !options::aimbot::aim_knocked ) ) )
            continue;

        vec3_t bone_position = player->get_bone_position( aimbot_bone );
        vec2_t bone_w2s = g_sdk.world_to_screen( bone_position );

        if( bone_w2s.is_zero( )
            || ( options::aimbot::aim_check
            && !player->is_visible( bone_position ) ) )
            continue;

        float length = g_cheat.screen_center.distance( bone_w2s );

        if( length < closest_distance
            && length < options::aimbot::fov_amount ) {
            closest_distance = length;
			target = player;

			for( auto& targets : g_esp.m_friends )
			{
				if( !targets )
					continue;

				core::player_model* model = targets->get_model( );
				if( !model )
					continue;

				if( target 
					&& target == targets ) {
					target = NULL;
					closest_distance = FLT_MAX;
				}
			}
        }
    }
}

void c_aimbot::get_best_bone( ) {
    if( !options::aimbot::aim_nearest_bone ) {
		switch( options::aimbot::aim_bone ) {
			case 0:
			{
				aimbot_bone = bone_list::head;
				break;
			}
			case 1:
			{
				aimbot_bone = bone_list::neck;
				break;
			}
			case 2:
			{
				aimbot_bone = bone_list::pelvis;
				break;
			}
			case 3:
			{
				aimbot_bone = bone_list::penis;
				break;
			}
		}
	}
    else {
        float closest = FLT_MAX;
        aimbot_bone = -1; // reset this too

        for( int i = 0; i < scanning_bones.size( ); i++ ) {
            vec3_t pos3d = target->get_bone_position( scanning_bones[ i ] );

            vec2_t pos = g_sdk.world_to_screen( pos3d );
            if( pos.is_zero( ) )
                continue;

            float length = g_cheat.screen_center.distance( pos );

            if( length < closest
                && length < options::aimbot::fov_amount ) {
                closest = length;
                aimbot_bone = scanning_bones[ i ];
            }
        }
    }
}

void c_aimbot::smooth_angles( vec2_t& angles, vec2_t local_view_angles ) {
	float smoothness = options::aimbot::smoothness_amount;
    if( smoothness ) {
		float smooth; // 0 is regular yaw, and 1 is pitch. 2 is being used for constant smooth.

	    vec2_t delta = ( angles - local_view_angles ).normalize( );

		float smoothing_value = 5.5f * ( smoothness / 100.f );
	    smooth = powf( 0.81f + smoothing_value, 0.4f );
	    smooth = min( 0.98f, smooth );

	    vec2_t new_delta = vec2_t( );

	    float coeff = ( 1.0f - smooth ) / delta.length( ) * 4.f;

	    // fast end
	    coeff = powf( coeff, 2.f ) * 80.f / smoothness;

	    coeff = min( 1.f, coeff );
	    new_delta = delta * coeff;

		angles = ( local_view_angles + new_delta );
    }
}

std::string c_aimbot::get_key_from_combo( int key ) {
	switch( key ) {
		case ( int )key_code::Mouse0:
		{
			return "lmouse";//lmouse button
			break;
		}
		case ( int )key_code::Mouse1:
		{
			return "rmouse";//rmouse button
			break;
		}
		case ( int )key_code::Mouse2:
		{
			return "middle mouse";//middle mouse button
			break;
		}
		case ( int )key_code::Mouse3:
		{
			return "x1 mbutton";//x1 mouse button
			break;
		}
		case ( int )key_code::Mouse4:
		{
			return "x2 mbutton";//x2 mouse button
			break;
		}
		case ( int )key_code::LeftControl:
		{
			return "lalt";//control break processing
			break;
		}
		case ( int )key_code::Backspace:
		{
			return "backspace";//backspace
			break;
		}
		case ( int )key_code::Tab:
		{
			return "tab";//tab
			break;
		}
		case ( int )key_code::Clear:
		{
			return "clear";//clear
			break;
		}
		case ( int )key_code::KeypadEnter:
		{
			return "enter";//enter
			break;
		}
		case ( int )key_code::LeftShift:
		{
			return "lshift";//shift
			break;
		}
		case ( int )key_code::RightControl:
		{
			return "rcontrol";//ctrl
			break;
		}
		case ( int )key_code::LeftAlt:
		{
			return "lalt";//alt
			break;
		}
		case ( int )key_code::CapsLock:
		{
			return "caps-lock";//caps lock
			break;
		}
		case ( int )key_code::Escape:
		{
			return "esc";//esc
			break;
		}
		case ( int )key_code::Space:
		{
			return "space";//space
			break;
		}
		case ( int )key_code::A:
		{
			return "a";//a
			break;
		}
		case ( int )key_code::B:
		{
			return "b";//b
			break;
		}
		case ( int )key_code::C:
		{
			return "c";//c
			break;
		}
		case ( int )key_code::D:
		{
			return "d";//d
			break;
		}
		case ( int )key_code::E:
		{
			return "e";//e
			break;
		}
		case ( int )key_code::F:
		{
			return "f";//f
			break;
		}
		case ( int )key_code::G:
		{
			return "g";//g
			break;
		}
		case ( int )key_code::H:
		{
			return "h";//h
			break;
		}
		case ( int )key_code::I:
		{
			return "i";//i
			break;
		}
		case ( int )key_code::J:
		{
			return "j";//j
			break;
		}
		case ( int )key_code::K:
		{
			return "k";//k
			break;
		}
		case ( int )key_code::L:
		{
			return "l";//L
			break;
		}
		case ( int )key_code::M:
		{
			return "m";//m
			break;
		}
		case ( int )key_code::N:
		{
			return "n";//n
			break;
		}
		case ( int )key_code::O:
		{
			return "o";//o
			break;
		}
		case ( int )key_code::P:
		{
			return "p";//p
			break;
		}
		case ( int )key_code::Q:
		{
			return "q";//q
			break;
		}
		case ( int )key_code::R:
		{
			return "r";//r
			break;
		}
		case ( int )key_code::S:
		{
			return "s";//s
			break;
		}
		case ( int )key_code::T:
		{
			return "t";//t
			break;
		}
		case ( int )key_code::U:
		{
			return "u";//u
			break;
		}
		case ( int )key_code::V:
		{
			return "v";//v
			break;
		}
		case ( int )key_code::W:
		{
			return "w";//w
			break;
		}
		case ( int )key_code::X:
		{
			return "x";//x
			break;
		}
		case ( int )key_code::Y:
		{
			return "y";//y
			break;
		}
		case ( int )key_code::Z:
		{
			return "z";//z
			break;
		}
		case ( int )key_code::F1: {
			return "f1";
			break;
		}
		case ( int )key_code::F2: {
			return "f2";
			break;
		}
		case ( int )key_code::F3: {
			return "f3";
			break;
		}
		case ( int )key_code::F4: {
			return "f4";
			break;
		}
		case ( int )key_code::F5: {
			return "f5";
			break;
		}
		case ( int )key_code::F6: {
			return "f6";
			break;
		}
		case ( int )key_code::F7: {
			return "f7";
			break;
		}
		case ( int )key_code::F8: {
			return "f8";
			break;
		}
		case ( int )key_code::F9: {
			return "f9";
			break;
		}
		case ( int )key_code::F10: {
			return "f10";
			break;
		}
		case ( int )key_code::F11: {
			return "f11";
			break;
		}
		default: {
			return "none";
			break;
		}
	}
	return "none";
}
#include "aimbot.h"
#include "../options.h"
#include "../../includes/includes.hpp"
#include "../visuals/esp.h"
#include "../../game/offsets.hpp"
#include "../../utilities/memory.hpp"

core::player_input* m_input{ };

// create global definition for aimbot class.
c_aimbot g_aimbot;

void c_aimbot::update_weapon_information( )
{
	core::base_player* local = g_cheat.local;
	if( !local )
		return;

    core::item* held_item = local->get_held_item( );
    if( !held_item )
		return;
		
	core::weapon_information bullet_info = held_item->get_weapon_information( );

    float bullet_velocity_scale = held_item->get_projectile_velocity_scale( );

    bullet_speed = bullet_info.bullet_speed;
    if( bullet_velocity_scale )
        bullet_speed *= bullet_velocity_scale;

    bullet_gravity = bullet_info.bullet_gravity;
    drag = bullet_info.drag;

    //g_render.draw_text( vec4_t( 100, 100, 35, 35 ), to_string( bullet_speed ), color_t( 255, 255, 255 ) );
    //g_render.draw_text( vec4_t( 100, 200, 35, 35 ), to_string( drag ), color_t( 255, 0, 255 ) );
    //g_render.draw_text( vec4_t( 100, 300, 35, 35 ), to_string( bullet_gravity ), color_t( 255, 0, 0 ) );
}

void c_aimbot::start_movement_simulation( vec3_t& aim_point, const vec3_t& from )
{
    shoot_position.clear( ); // clear this the fuck outta here.

    if( options::aimbot::should_simulate_movement ) {
        float distance = from.distance( aim_point );           

	    constexpr float time_step = 0.015625f;
	    float travelled{ }, y_speed{ }, travel_time{ };

	    for( float to_travel = 0.f; to_travel < distance; )
	    {
		    float speed_modifier = ( 1.f - ( time_step * drag ) );
		    bullet_speed *= speed_modifier;

		    if( bullet_speed <= 0.f 
                || bullet_speed >= 10000.f
                || travelled >= 10000.f 
                || travelled < 0.f )
			    break;

		    if( travel_time > 8.f )
			    break;

		    y_speed += ( ( ( 9.81f * bullet_gravity ) * time_step ) * speed_modifier );

		    to_travel += ( bullet_speed * time_step );
		    travelled += ( y_speed * time_step );
            travel_time += time_step;
	    }

        vec3_t velocity = target->get_model( )->get_velocity( ) * 0.75f;
	    if( velocity.y > 0.f )
		    velocity.y /= 3.25f;

	    aim_point.y += travelled;
	    aim_point += ( velocity * travel_time );
    }

	shoot_position = aim_point;
}

void c_aimbot::process( ) {
    if( options::aimbot::aim_type < 1 )
        return;

	// get our things to run aimbot..
    get_best_player( );

	core::base_player* local = g_cheat.local;

    if( !target
        || !local
        || g_cheat.cam_pos.is_zero( ) )
        return;

	core::item* held_item = local->get_held_item( );
	if( !held_item )
		return;

    if( held_item->is_melee( ) 
        || !held_item->is_gun( ) 
        || held_item->is_heal( ) )
        return;

    update_weapon_information( );

    m_input = local->get_input( );
    if( !m_input )
        return;

    vec2_t view_angles = m_input->get_view_angles( );
    if( view_angles.is_zero( ) )
        return shoot_position.clear( );

	/* we have shit ready, get our best bone to shoot at :p */
    get_best_bone( );

    vec3_t bone_position = target->get_bone_position( aimbot_bone );
    if( bone_position.is_zero( ) )
        return;

    /* update our weapon information before using any crucial data.. */
	start_movement_simulation( bone_position, g_cheat.cam_pos ); /* handle player prediction simulation */

    if( shoot_position.is_zero( ) ) // :P
        return;

	aim_angle = ( view_angles + ( g_math.unity_calculate_angle( g_cheat.cam_pos, shoot_position ) ) );

    if( !held_item->is_melee( ) 
        && held_item->is_gun( ) ) {
        aim_angle -= ( view_angles - m_input->get_recoil_angles( ) );
    }

    vec3_t silent_angle = vec3_t( shoot_position - g_cheat.cam_pos ); // now our aimbot also compensates for da recoilzz
    vec4_t quat_angle = vec4_t::quat_look_rot( silent_angle, vec3_t( 0, 1, 0 ) );
        
    if( options::aimbot::smooth_type > 0 )
        smooth_angles( aim_angle, view_angles );

    // normalize aimbot angles.
    aim_angle.normalize( );
    silent_angle.normalize( );

    is_in_aim = g_sdk.get_key( aim_key );
    if( !is_in_aim )
        return; // fuck it.

	core::player_eyes* eyes = local->get_eyes( );

    switch( options::aimbot::aim_type ) {
    case 1:
		if( eyes )
			eyes->set_body_rotation( quat_angle );
		else
			goto MEMORY_AIM;
        break;
    case 2:
		MEMORY_AIM:
        m_input->set_view_angles( aim_angle );
        break;
    }
}
#include "gui_hook.h"
#include "../../includes/hinclude.h"
#include "../visuals/esp.h"
#include "../../game/offsets.hpp"
#include "../options.h"
#include "../aimbot/aimbot.h"
#include "framework/gui_framework.h"
#include <filesystem>
#include <shlobj.h>
#include "menu_tabs.h"

void entity_loop( )
{
	std::vector< std::pair< core::base_player*, entity_type > > player_list;
	
	event_type event_type = g_sdk.get_event_type( g_sdk.get_current( ) );

	auto clear_list = [ & ]( bool get_client_entities = false ) -> void
	{
		if( get_client_entities )
			g_cheat.client_entities = il2mgr::value( xs( "BaseNetworkable" ), xs( "clientEntities" ), false );

		/* fix for re-joining servers xd */
		player_list.clear( );
		g_cheat.player_list.clear( );
		g_cheat.local_pos.clear( );
		g_cheat.cam_pos.clear( );
	};

	if( !g_cheat.client_entities )
		return clear_list( true );

	uintptr_t entity_realm = *reinterpret_cast< uintptr_t* >( g_cheat.client_entities + 0x10 );
	if( !entity_realm )
		return clear_list( true );

	uintptr_t buffer_list = *reinterpret_cast< uintptr_t* >( entity_realm + 0x28 );
	if( !buffer_list )
		return clear_list( );

	uintptr_t object_list = *reinterpret_cast< uintptr_t* >( buffer_list + 0x18 );
	if( !object_list )
		return clear_list( );

	int object_list_size = *reinterpret_cast< int* >( buffer_list + 0x10 );

	if( !g_cheat.local )
		clear_list( );

	for( int i = 0; i < object_list_size; i++ )
	{
		core::base_entity* current_object = *reinterpret_cast< core::base_entity** >( object_list + ( 0x20 + ( i * sizeof( uint64_t ) ) ) );
		if( !current_object )
			continue;

		uintptr_t base_object = *reinterpret_cast< uintptr_t* >( ( uintptr_t )current_object + 0x10 );
		if( !base_object )
			continue;

		uintptr_t object = *reinterpret_cast< uintptr_t* >( base_object + 0x30 );
		if( !object )
			continue;

		uintptr_t object_class = *reinterpret_cast< uintptr_t* >( object + 0x30 );
		if( !object_class )
			continue;

		uintptr_t entity = *reinterpret_cast< uintptr_t* >( object_class + 0x18 );
		if( !entity )
			continue;

		std::string class_name = current_object->get_class_name( );

		core::base_player* player = *reinterpret_cast< core::base_player** >( entity + 0x28 );
		if( player ) {
			if( i == 0 )
			{
				g_cheat.local = player;

				if( g_cheat.local->get_life_state( ) )
					continue;

				core::player_model* model = g_cheat.local->get_model( );
				if( model )
					g_cheat.local_pos = model->get_position( );

				continue;
			}

			const uint16_t tag = *reinterpret_cast< uint16_t* >( object + 0x54 );
			if( tag == 6 )
			{
				static entity_type type = entity_type::player;

				if( ( class_name.length ( ) > 9
					&& ( class_name[ 9 ] == 'N' )
					|| ( class_name[ 0 ] == 'S' && class_name[ 1 ] == 'c' ) ) 
					|| ( class_name[ 0 ] == 'H' && class_name[ 1 ] == 'T' ) 
					|| ( class_name[ 0 ] == 'N' && class_name[ 3 ] == 'S' )
					|| ( class_name[ 0 ] == 'V' && class_name[ 7 ] == 'V' ) ) // Scientist
					type = scientist;
				else if( ( class_name[ 0 ] == 'T' && class_name[ 6 ] == 'D' ) ) // TunnelDweller
					type = tunnel_dweller;
				else 
					type = entity_type::player;

				player_list.emplace_back( std::make_pair( player, type ) );
			}
		}

		core::base_entity* base_entity = *reinterpret_cast< core::base_entity** >( base_object + 0x28 );
		if( !base_entity )
			continue;

		core::transform* transform = base_entity->get_transform( );
		if( !transform )
			continue;

		vec3_t position = transform->get_position( );
		if( position.is_zero( ) )
			continue;

		float distance = g_cheat.local_pos.distance( position );

		uintptr_t object_name_ptr = *reinterpret_cast< uintptr_t* >( object + 0x60 );
		if( !object_name_ptr )
			continue;

		std::string obj_name = g_sdk.read_ascii( object_name_ptr, 128 );

		vec2_t screen_pos = g_sdk.world_to_screen( position );
		if( screen_pos.is_zero( ) )
			continue;

		vec4_t render_position = vec4_t( screen_pos.x, screen_pos.y, 150, 55 );

		core::base_combat_entity* combat_entity = reinterpret_cast< core::base_combat_entity* >( current_object );

		g_world.render( render_position, class_name, obj_name, distance, combat_entity, event_type, base_entity );
	}

	g_cheat.player_list = player_list;
}

namespace perf_ui {
	void ongui_hook( )
	{
		g_cheat.mouse_pos = g_sdk.get_mouse_pos( );
		g_cheat.screen_size = vec2_t( g_sdk.get_screen_width( ), g_sdk.get_screen_height( ) ); // k to the y to the s
		if( !g_cheat.screen_size.is_zero( ) )
			g_cheat.screen_center = g_cheat.screen_size / 2;

		uintptr_t current_event = g_sdk.get_current( );
		if( !current_event )
			return;

		event_type event_type = g_sdk.get_event_type( current_event );
		if( event_type != event_type::re_paint )
			return;

		g_cheat.draw_skin = g_sdk.get_draw_skin( );
		if( !g_cheat.draw_label )
			g_cheat.draw_label = *reinterpret_cast< uintptr_t* >( g_cheat.draw_skin + 0x38 );
		else {
			g_sdk.set_draw_font_size( g_cheat.draw_label, 12 );
			g_sdk.set_draw_alignment( g_cheat.draw_label, 0x0 );
			g_sdk.set_draw_color( color_t( 255, 255, 255, 255 ) );
		}

		if( !g_cheat.circuit_chams_bundle )
			g_cheat.circuit_chams_bundle = g_sdk.load_bundle_file( "C:\\secrethack24\\circuit_chams_bundle.vmt" );

		if( !g_cheat.chams_bundle )
			g_cheat.chams_bundle = g_sdk.load_bundle_file( "C:\\secrethack24\\chams_bundle.vmt" );

		if( !g_cheat.wireframe_chams_bundle )
			g_cheat.wireframe_chams_bundle = g_sdk.load_bundle_file( "C:\\secrethack24\\wire_chams.vmt" );

		if( !g_cheat.asset_bundle )
			g_cheat.asset_bundle = g_sdk.load_bundle_file( "C:\\secrethack24\\chams.vmt" );

		if( !g_cheat.font_bundle )
			g_cheat.font_bundle = g_sdk.load_bundle_file( "C:\\secrethack24\\font_bundle.bndl" );
		else {
			static uintptr_t object = il2mgr::type_object( "UnityEngine", "Font" );

			static uintptr_t font_name = g_sdk.load_asset( g_cheat.font_bundle, "ubuntu-medium.ttf", object );
			if( font_name )
				*reinterpret_cast< uintptr_t* >( g_cheat.draw_skin + 0x18 ) = font_name;
		}

		g_cheat.pulsation.rainbow( 5.f );
		g_cheat.rainbow = color_t( g_cheat.pulsation.r, 127 + g_cheat.pulsation.g * 0.25f, g_cheat.pulsation.g );

		if( options::rainbow_accent )
			options::accent_color = g_cheat.rainbow;

		// draw our menu.
		g_menu.draw_menu( );

		// set-up shader before draw.
		g_render.set_up_draw_shader( );

		std::string config_direction = std::filesystem::current_path( ).string( );

		static std::vector< std::string > cfg_files;

		cfg_files.clear( );
		for( const auto& entry : std::filesystem::directory_iterator( config_direction ) )
		{
			if( entry.is_regular_file( ) 
				&& entry.path( ).extension( ) == ".cfg" )
				cfg_files.push_back( entry.path( ).filename( ).string( ) );
		}

		if( options::cfg_index >= 0 ) {
			std::string file_name = cfg_files.at( options::cfg_index );

			if( options::load_cfg
				&& options::cfg_index < cfg_files.size( ) )
			{
				g_cfg.load_cfg( file_name );
			}

			if( options::save_cfg
				&& options::cfg_index < cfg_files.size( ) )
			{
				g_cfg.save_cfg( file_name );
			}
		}

		if( options::aimbot::exploits::misc::no_flash )
			g_game.set_flash_duration( 0.f );
		else
			g_game.set_flash_duration( 2.5f );

		entity_loop( );

		// esp font flags.
		{
			switch( options::font_flags )
			{
			case 1:
				g_esp.font_flags = font_flags_t::dropshadow;
				break;
			case 2:
				g_esp.font_flags = font_flags_t::outline;
				break;
			default:
				g_esp.font_flags = font_flags_t::none;
				break;
			}
		}

		auto render_water_mark =[ & ]( ) -> void // tf is that lambda:P
		{
			std::string total_text = xs( "secret-hack24: RUST" );

			g_render.outline_box( vec2_t( 2, 3 ), vec2_t( 110, 20 ), color_t( 48, 48, 48 ) );
			g_render.draw_filled_rect( vec4_t( 2, 3, 110, 20 ), color_t( 10, 10, 10 ) );
			g_render.draw_filled_rect( vec4_t( 2, 3, 2, 20 ), options::accent_color.alpha( 255.f, true ) );
			g_render.draw_text( vec4_t( 7, 4, 150, 20 ), total_text, color_t( 225, 225, 225 ), false, 11, g_esp.font_flags );
		};

		if( options::visuals::show_watermark )
			render_water_mark( );

		if( options::visuals::world::mie_changer )
			g_game.set_mie( options::visuals::world::mie_amount );
		if( options::visuals::world::rayleigh_changer )
			g_game.set_rayleigh( options::visuals::world::rayleigh_amount );
		if( options::visuals::world::modify_rain )
			g_game.set_rain( options::visuals::world::rain_amount );

		if( options::aimbot::draw_fov )
		{
			g_render.draw_circle( g_cheat.screen_center, options::aimbot::fov_amount, 
				options::aimbot::fov_circle_color );
		}

		if( options::aimbot::draw_crosshair ) {
			g_render.draw_line( vec2_t( g_cheat.screen_center.x - 7.f, g_cheat.screen_center.y ), 
				vec2_t( g_cheat.screen_center.x - 2.f, g_cheat.screen_center.y ), color_t( g_cheat.pulsation.r, g_cheat.pulsation.g, 255 ) ); // left middle

			g_render.draw_line( vec2_t( g_cheat.screen_center.x + 6.f, g_cheat.screen_center.y ),
				vec2_t( g_cheat.screen_center.x + 1.f, g_cheat.screen_center.y ), color_t( g_cheat.pulsation.r, ( 0.5f + g_cheat.pulsation.g * 0.25f ), g_cheat.pulsation.g ) ); // right middle

			g_render.draw_line( vec2_t( g_cheat.screen_center.x, g_cheat.screen_center.y - 7.f ),
				vec2_t( g_cheat.screen_center.x, g_cheat.screen_center.y - 2.f ), color_t( g_cheat.pulsation.b, 255, g_cheat.pulsation.b ) ); // middle down

			g_render.draw_line( vec2_t( g_cheat.screen_center.x, g_cheat.screen_center.y + 6.f ),
				vec2_t( g_cheat.screen_center.x, g_cheat.screen_center.y + 1.f ), color_t( g_cheat.pulsation.r, g_cheat.pulsation.g, g_cheat.pulsation.b ) ); // middle up
		}

		g_esp.change_sky_ambient_color( );
		core::base_player* local_player = g_cheat.local;

		if( local_player )
		{			
			// reset this.
			g_esp.not_in_fly_action = true;

			bool manipulation_activated = g_sdk.get_key( options::aimbot::manipulation_key ) && options::aimbot::manipulation;

			if( manipulation_activated ) {
				local_player->set_clientTickInterval( 1.f );

				g_esp.find_manipulate_angle( );
				if( !g_esp.manipulation_angle.is_zero( ) ) {
					core::player_eyes* eyes = local_player->get_eyes( );
					if( eyes ) {
						if( g_sdk.get_key( key_code::F )
							&& local_player->get_clientTickInterval( ) > 0.75f )
							eyes->set_view_offset( g_esp.manipulation_angle );
					}
				}
			}
			else {
				g_esp.manipulation_angle.clear( );
			}

			g_esp.render_saved_positions( );

			if( options::aimbot::exploits::movement::modify_clothing_speed )
				local_player->set_clothing_speed_reduce( -options::aimbot::exploits::movement::clothing_speed );

			if( options::aimbot::exploits::combat::unlock_aim_on_jugger )
				local_player->set_clothing_blocks_aiming( false );

			// spacing handle lol.
			{
				if( options::visuals::show_health_text 
					&& g_esp.esp_spacing[ 1 ] < 13 )
					g_esp.esp_spacing[ 1 ] += 13;
				else if( !options::visuals::show_health_text )
					g_esp.esp_spacing[ 1 ] = 0;
			}

			if( options::visuals::draw_radar )
			{
				float width = 200, height = 200;

				// check if we have menu open.
				if( g_framework.in_alpha ) {
					vec3_t cursor = g_cheat.mouse_pos;

					if( g_sdk.get_key( key_code::Mouse0 ) 
						&& g_framework.is_hovering( g_esp.radar_position, vec2_t( width, 25 ) ) )
					{
						cursor.y = g_cheat.screen_size.y - cursor.y;

						g_esp.radar_position.x = cursor.x - width / 2.f;
						g_esp.radar_position.y = cursor.y - 10.f;
					}
				}

				g_render.draw_filled_rect( vec4_t( g_esp.radar_position.x, g_esp.radar_position.y, width, height ), color_t( 0, 0, 0, 255 ) );
				g_render.outline_box( vec2_t( g_esp.radar_position.x, g_esp.radar_position.y ), vec2_t( width, height ), color_t( 48, 48, 48, 255 ) );
			}

			if( options::visuals::rgb_chams )
				options::visuals::chams_color = options::visuals::chams_visible = g_cheat.rainbow;

			for( int i = 0; i < g_cheat.player_list.size( ); i++ )
			{
				std::pair< core::base_player*, entity_type > player = g_cheat.player_list.at( i ); // wow that's so ugly
				if( !player.first )
					continue;

				g_esp.context_instance( player.first, player.second );
			}

			g_aimbot.process( );

			if( g_aimbot.target ) {
				if( options::visuals::show_hotbar )
				{
					g_esp.draw_hotbar( g_aimbot.target ); 
				}
				if( options::visuals::show_clothes )
				{
					g_esp.draw_clothes( g_aimbot.target );
				}
			}

			if( g_sdk.get_key( options::add_friend_key )
				&& options::friend_system )
				g_esp.m_friends.push_back( g_aimbot.target );

			core::player_walk_movement* movement = local_player->get_movement( );
			core::player_eyes* eyes = local_player->get_eyes( );

			float speed = options::aimbot::exploits::movement::fly_speed / 100.f;

			bool has_triggered_stopper[ 2 ]{ false };
			has_triggered_stopper[ 0 ] = g_esp.current_vertical_fly >= g_esp.max_vertical_fly;
			has_triggered_stopper[ 1 ] = g_esp.current_horizontal_fly >= g_esp.max_horizontal_fly;

			if( eyes 
				&& movement ) {
				if( options::aimbot::exploits::movement::increase_height ) {
					if( g_sdk.get_key( options::aimbot::exploits::movement::increase_height_key ) )
						movement->set_capsule_height( options::aimbot::exploits::movement::height_amount );
					else
						movement->set_capsule_height( 1.8f );
				}

				if( options::aimbot::exploits::combat::head_teleportation
					&& g_sdk.get_key( options::aimbot::exploits::combat::teleport_key ) ) {
					core::base_player* target = g_aimbot.target;
					if( target ) {
						core::player_model* model = target->get_model( );
						if( model ) {
							vec3_t target_pos = model->get_position( );
							if( !target_pos.is_zero( )
								&& target_pos.distance( g_cheat.local_pos ) < 5.f )
								movement->teleport_to( vec3_t( target_pos.x, target_pos.y + 1.f, target_pos.z ) );
						}
					}
				}

				vec3_t movement_direction = vec3_t( );

				// get movement direction..
				{
					vec4_t rotation = eyes->get_body_rotation( );
					if( !rotation.is_zero( ) ) {
						const vec3_t vecright = vec3_t( 1.f, 0.f, 0.f );
						const vec3_t vecforward = vec3_t( 0.f, 0.f, 1.f );
						const vec3_t vecup = vec3_t( 0.f, 1.f, 0.f );

						if( g_sdk.get_key( key_code::W ) )
							movement_direction += g_math.quatmult( &vecforward, &rotation );
						if( g_sdk.get_key( key_code::S ) )
							movement_direction -= g_math.quatmult( &vecforward, &rotation );
						if( g_sdk.get_key( key_code::A ) )
							movement_direction -= g_math.quatmult( &vecright, &rotation );
						if( g_sdk.get_key( key_code::D ) )
							movement_direction += g_math.quatmult( &vecright, &rotation );
						if( g_sdk.get_key( key_code::Space ) )
							movement_direction.y += 1.f;
						if( g_sdk.get_key( key_code::LeftShift ) )
							movement_direction.y -= 1.f;
					}
				}

				if( options::aimbot::exploits::movement::always_sprint ) {
					movement->set_is_running( 1.f );
					g_game.set_is_sprinting( true );
				}

				if( options::aimbot::exploits::movement::fly_hack ) {
					bool is_moving = g_sdk.get_key( key_code::W ) || g_sdk.get_key( key_code::A ) ||
						g_sdk.get_key( key_code::S ) || g_sdk.get_key( key_code::D ) || g_sdk.get_key( key_code::Space );

					if( g_sdk.get_key( options::aimbot::exploits::movement::fly_key ) ) {
						g_esp.not_in_fly_action = false;

						movement->set_flying( true );
						movement->set_capsule_center( -1000.f );

						if( !movement_direction.is_zero( ) )
							movement->set_targetmovement( movement_direction * speed );
					}
					else {
						movement->set_capsule_center( 0.9f );
						movement->set_flying( false );
						g_esp.not_in_fly_action = true;
					}
				}

				if( options::aimbot::exploits::movement::stopper_fly
					&& ( has_triggered_stopper[ 0 ] || has_triggered_stopper[ 1 ] )
					&& !g_sdk.get_key( options::aimbot::exploits::movement::ignore_key ) )
				{
					vec3_t current = g_cheat.local_pos;

					vec3_t previous_position = current;

					core::player_ticks* last_sent_tick = local_player->get_lastSentTick( );

					if( last_sent_tick ) {
						// no fall damage when teleporting.
						movement->set_was_falling( true );
						movement->set_previous_velocity( vec3_t( ) );

						vec3_t old = last_sent_tick->get_position( );

						float height = ( current.y < old.y ? current.y : old.y ) - 0.75f;

						if( has_triggered_stopper[ 0 ] )
							previous_position = vec3_t( previous_position.x,
								height, previous_position.z );
						else if( has_triggered_stopper[ 1 ] )
							previous_position = vec3_t( old.x, height, old.z );

						movement->set_targetmovement( vec3_t( ) );

						if( !previous_position.is_zero( ) )
							movement->teleport_to( previous_position );// teleport to our previous position.
					}
				}
			}

			camera* camera = g_cheat.camera_ptr;
			if( camera ) {
				if( options::visuals::world::aspect_changer )
					camera->set_aspect_ratio( options::visuals::world::aspect_value );
			}

			g_esp.apply_fly_violation( );

			g_esp.show_reload_bar( ); // render reload bar BEFORE desync bar, so spacing works fine:p
			g_esp.show_desync_bar( );

			g_esp.draw_bullet_tracers( );

			//g_sdk.set_admin_ambient_mp( options::visuals::world::rayleigh_value );
			//g_sdk.set_admin_ref_mp( options::visuals::world::rayleigh_value );

			if( local_player->has_flag( player_flags::is_connected ) ) {
				if( options::visuals::local_trails )
					g_esp.draw_local_trails( );
				// ----------------------------- //
				if( options::visuals::show_last_sent_tick )
					g_esp.draw_last_sent_tick( );
			}

			int indicator_spacing = 0;

			if( options::visuals::indicators ) {
				if( options::visuals::fly_hack_indicator )
					g_esp.fly_hack_bar( );

				float current_lag = local_player->get_clientTickInterval( );

				if( g_aimbot.target )
				{
					std::string text = xs( "aimbot[t" );
					if( g_aimbot.is_in_aim )
						text += "|b]";
					else
						text += "]";

					g_render.draw_text( vec4_t( g_cheat.screen_center.x - 50, g_cheat.screen_center.y + ( 15 + 
						( g_esp.indicators_spacing[ 0 ] + g_esp.indicators_spacing[ 1 ] ) ), 150, 20 ),
						text, color_t( g_cheat.pulsation.r, 125, g_cheat.pulsation.b - 125.f ), true, 10, g_esp.font_flags );

					indicator_spacing += 10;
				}

				if( current_lag > 0.1f )
				{
					std::string text = xs( "lag" );
					text += xs( "(" );
					text += g_math.remove_trailing_zeros( current_lag );
					text += xs( "s)" );

					g_render.draw_text( vec4_t( g_cheat.screen_center.x - 50, g_cheat.screen_center.y + ( 15 + indicator_spacing 
						+ ( g_esp.indicators_spacing[ 0 ] + g_esp.indicators_spacing[ 1 ] ) ), 150, 20 ),
						text, g_cheat.rainbow, true, 10, g_esp.font_flags );

					indicator_spacing += 10;
				}

				if( !g_esp.not_in_fly_action )
				{
					std::string text = std::string( );
					bool unsafe[ 3 ]{ false };
					unsafe[ 1 ] = ( g_esp.current_vertical_fly - g_esp.max_vertical_fly ) > 2.f;
					unsafe[ 2 ] = ( g_esp.current_horizontal_fly - g_esp.max_horizontal_fly ) > 2.f;

					if( ( unsafe[ 1 ] ) )
						text += "*";
					text += xs( "noclipping" );
					if( ( unsafe[ 2 ] ) )
						text += "*";

					color_t color = color_t( g_cheat.pulsation.r - 127, g_cheat.pulsation.g * 0.25f, g_cheat.pulsation.g * 0.25f );
					if( unsafe[ 1 ] || unsafe[ 2 ] )
						color = color_t( g_cheat.pulsation.r * g_cheat.pulsation.g * 0.1f, 127, 0 );

					g_render.draw_text( vec4_t( g_cheat.screen_center.x - 50, g_cheat.screen_center.y + ( 15 + indicator_spacing 
						+ ( g_esp.indicators_spacing[ 0 ] + g_esp.indicators_spacing[ 1 ] ) ), 150, 20 ),
						text, color, true, 10, g_esp.font_flags );

					indicator_spacing += 10;
				}

				if( !g_esp.manipulation_angle.is_zero( ) )
				{
					std::string text = std::string( );
					text += xs( "manipulator" );
					if( current_lag > 0.5f )
						text += xs( "[r]" );
					else
						text += xs( "[c]" );

					color_t color = color_t( 255 / current_lag, 255 * current_lag, 255 - ( 125 * current_lag ) );

					g_render.draw_text( vec4_t( g_cheat.screen_center.x - 50, g_cheat.screen_center.y + ( 15 + indicator_spacing 
						+ ( g_esp.indicators_spacing[ 0 ] + g_esp.indicators_spacing[ 1 ] ) ), 150, 20 ),
						text, color, true, 10, g_esp.font_flags );
				}
			}

			g_game.set_underwater_blur( !options::visuals::world::clear_underwater );

			if( options::aimbot::exploits::misc::zoom_fov
				&& g_sdk.get_key( options::aimbot::exploits::misc::zoom_key ) )
				g_game.set_graphics_fov( options::aimbot::exploits::misc::zoom_fov_amount );
			else if( options::aimbot::exploits::misc::fov_changer )
				g_game.set_graphics_fov( options::aimbot::exploits::misc::fov_amount );
			else
				g_game.set_graphics_fov( 90.f );

			core::base_mountable* mountable = local_player->get_mountable( );

			if( mountable )
			{
				if( options::aimbot::exploits::combat::can_attack_in_vehicles )
					mountable->set_can_wield_item( true );

				if( options::aimbot::exploits::combat::unlock_view_angles )
					mountable->set_ignore_vehicle_parent( true );
			}

			g_sdk.ignore_layer_collision( layer::PlayerMovement, layer::Tree, options::aimbot::exploits::movement::walk_through_trees );
			g_sdk.ignore_layer_collision( layer::PlayerMovement, layer::AI, options::aimbot::exploits::movement::walk_through_players );
		}

		return; // yeah
	}

	void performance_ui_update_hook( void* instance )
	{
		if( first_loaded )
		{
			static uintptr_t game_object = il2mgr::methods::object_new( il2mgr::init_class( xs( "GameObject" ), xs( "UnityEngine" ) ) );
			g_sdk.create( game_object, xs( "" ) );

			static uintptr_t dev_controls = il2mgr::type_object( xs( "" ), xs( "DevControls" ) );
			g_sdk.add_component( game_object, dev_controls );
			g_sdk.dont_destroy_on_load( game_object );

			first_loaded = false;
		}

		static auto update_performance_ui = reinterpret_cast< void( * )( void* ) >( hook_address[ 5 ] );
		spoof_ret( update_performance_ui, instance );
	}
}
#pragma once
#include "cfg.h"

namespace perf_ui
{
	void ongui_hook( );

	inline static bool first_loaded = true;
	void performance_ui_update_hook( void* instance );
}
#include "menu_tabs.h"
#include "framework/gui_framework.h"
#include "../options.h"
#include "../aimbot/aimbot.h"

// create global definition of menu class.
c_menu g_menu;

void c_menu::draw_menu_tab( ) {
	g_framework.create_check_box( xs( "rainbow accent" ), &options::rainbow_accent, 1 );
	g_framework.color_picker( xs( "menu accent color" ), &options::accent_color, 1 );

	g_framework.create_label( xs( "quick config" ), 1 );
	g_framework.create_combo_box( cfg_vector, &options::cfg_index, 1 );
	g_framework.create_check_box( xs( "load" ), &options::load_cfg, 1 );
	g_framework.create_check_box( xs( "save" ), &options::save_cfg, 1 );

	g_framework.create_label( xs( "esp font flags" ), 1 );
	g_framework.create_combo_box( font_flags, &options::font_flags, 1 );
				
	g_framework.create_label( xs( "local indicators" ), 2 );
	g_framework.create_check_box( xs( "indicators" ), &options::visuals::indicators, 2 );
	if( options::visuals::indicators )
		g_framework.create_check_box( xs( "fly hack indicator" ), &options::visuals::fly_hack_indicator, 2 );

	g_framework.create_check_box( xs( "draw hit bullet tracers" ), &options::visuals::draw_tracers, 2 );
	g_framework.color_picker( xs( "hit tracers color" ), &options::visuals::tracers_color, 2 );
	g_framework.create_check_box( xs( "draw local trails" ), &options::visuals::local_trails, 2 );
	g_framework.color_picker( xs( "trails color" ), &options::visuals::trails_color, 2 );
	g_framework.create_check_box( xs( "draw desync bar" ), &options::visuals::show_desync_bar, 2 );
	g_framework.color_picker( xs( "desync bar color" ), &options::visuals::desync_bar_color, 2 );
	g_framework.create_check_box( xs( "draw reload bar" ), &options::visuals::show_reload_bar, 2 );
	g_framework.color_picker( xs( "reload bar color" ), &options::visuals::reload_bar_color, 2 );

	g_framework.create_label( xs( "location manager" ), 2 );
	g_framework.create_hotkey( xs( "remove last position" ), &options::visuals::remove_positions_key, 2 );
	g_framework.create_hotkey( xs( "save pos key" ), &options::visuals::save_pos_key, 2 );
	g_framework.create_check_box( xs( "is home position" ), &options::visuals::is_home_pos, 2 );
	g_framework.color_picker( xs( "position color" ), &options::visuals::pos_color, 2 );
}

void c_menu::draw_aimbot_tab( ) {
	g_framework.create_combo_box( aim_mode, &options::aimbot::aim_type, 1 );

	g_framework.create_check_box( xs( "manipulator" ), &options::aimbot::manipulation, 1 );
	g_framework.create_hotkey( xs( "manipulator key" ), &options::aimbot::manipulation_key, 1 );
	//g_framework.create_check_box( xs( "auto reload" ), &options::aimbot::auto_reload, 1 );
	g_framework.create_check_box( xs( "simulate player movement" ), &options::aimbot::should_simulate_movement, 1 );

	g_framework.create_check_box( xs( "aim at nearest bone" ), &options::aimbot::aim_nearest_bone, 1 );
	if( !options::aimbot::aim_nearest_bone )
		g_framework.create_combo_box( bones, &options::aimbot::aim_bone, 1 );

	g_framework.create_hotkey( xs( "aim key" ), &g_aimbot.aim_key, 1 );
				
	g_framework.create_check_box( xs( "draw field of view circle" ), &options::aimbot::draw_fov, 1 );
	g_framework.color_picker( xs( "fov circle color" ), &options::aimbot::fov_circle_color, 1 );

	g_framework.slider_int( xs( "field of view" ), &options::aimbot::fov_amount, 0, 1000, 1 );

	g_framework.create_label( xs( "smooth type" ), 1 );
	g_framework.create_combo_box( smooth_type, &options::aimbot::smooth_type, 1 );
	g_framework.slider_float( xs( "smoothness amount" ), &options::aimbot::smoothness_amount, 0.0f, 10.f, 1 );

	g_framework.create_check_box( xs( "draw line to target" ), &options::aimbot::draw_target, 1 );
	g_framework.color_picker( xs( "line color" ), &options::aimbot::target_line_color, 1 );

	g_framework.create_check_box( xs( "aim at knocked" ), &options::aimbot::aim_knocked, 1 );
	g_framework.create_check_box( xs( "aim at sleepers" ), &options::aimbot::aim_sleepers, 1 );
	g_framework.create_check_box( xs( "aim at npc" ), &options::aimbot::aim_npc, 1 );
	g_framework.create_check_box( xs( "aim at helicopter" ), &options::aimbot::aim_helicopter, 1 );
	g_framework.create_check_box( xs( "only aim at visible" ), &options::aimbot::aim_check, 1 );

	g_framework.create_check_box( xs( "draw crosshair" ), &options::aimbot::draw_crosshair, 1 );
	g_framework.create_check_box( xs( "killaura" ), &options::aimbot::kill_aura, 1 );

	g_framework.slider_int( xs( "target max distance" ), &options::aimbot::max_target_distance, 0, options::visuals::max_player_distance, 2 );
}

void c_menu::draw_visuals_tab( ) {
	g_framework.create_check_box( xs( "master-switch" ), &options::visuals::draw_visuals, 1 );
	g_framework.create_combo_box( color_list, &options::color_tab, 1 );
	if( options::visuals::draw_visuals ) {
		g_framework.create_check_box( xs( "name" ), &options::visuals::show_name, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "name color" ), &options::visuals::name_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "name color" ), &options::visuals::vis_name_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "name color" ), &options::visuals::npc_name_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "name color" ), &options::visuals::npc_vis_name_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "radar" ), &options::visuals::draw_radar, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "radar color" ), &options::visuals::radar_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "radar color" ), &options::visuals::vis_radar_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "radar color" ), &options::visuals::npc_radar_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "radar color" ), &options::visuals::npc_vis_radar_color, 1 );
			break;
		}

		g_framework.create_combo_box( box_esp_mode, &options::visuals::box_type, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "box color" ), &options::visuals::box_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "box color" ), &options::visuals::vis_box_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "box color" ), &options::visuals::npc_box_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "box color" ), &options::visuals::npc_vis_box_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "health" ), &options::visuals::show_health, 1 );
		if( options::visuals::show_health ) {
			g_framework.slider_int( xs( "health thickness" ), &options::visuals::health_thickness, 1, 3, 1 );
			g_framework.create_check_box( xs( "custom health color" ), &options::visuals::modify_health_color, 1 );
			if( options::visuals::modify_health_color ) {
				switch( options::color_tab ) {
				case invisible:
					g_framework.color_picker( xs( "health color" ), &options::visuals::custom_health_color, 1 );
					break;
				case visible:
					g_framework.color_picker( xs( "health color" ), &options::visuals::vis_custom_health_color, 1 );
					break;
				case npc_invisible:
					g_framework.color_picker( xs( "health color" ), &options::visuals::npc_custom_health_color, 1 );
					break;
				case npc_visible:
					g_framework.color_picker( xs( "health color" ), &options::visuals::npc_vis_custom_health_color, 1 );
					break;
				}
			}
		}
		g_framework.create_check_box( xs( "health text" ), &options::visuals::show_health_text, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "health text color" ), &options::visuals::health_text_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "health text color" ), &options::visuals::vis_health_text_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "health text color" ), &options::visuals::npc_health_text_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "health text color" ), &options::visuals::npc_vis_health_text_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "skeleton" ), &options::visuals::draw_bones, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "skeleton color" ), &options::visuals::skeleton_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "skeleton color" ), &options::visuals::vis_skeleton_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "skeleton color" ), &options::visuals::npc_skeleton_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "skeleton color" ), &options::visuals::npc_vis_skeleton_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "weapon" ), &options::visuals::show_weapon, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "weapon color" ), &options::visuals::weapon_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "weapon color" ), &options::visuals::vis_weapon_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "weapon color" ), &options::visuals::npc_weapon_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "weapon color" ), &options::visuals::npc_vis_weapon_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "distance" ), &options::visuals::show_distance, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "distance color" ), &options::visuals::distance_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "distance color" ), &options::visuals::vis_distance_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "distance color" ), &options::visuals::npc_distance_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "distance color" ), &options::visuals::npc_vis_distance_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "snap-lines" ), &options::visuals::show_lines, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "lines color" ), &options::visuals::snap_lines_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "lines color" ), &options::visuals::vis_snap_lines_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "lines color" ), &options::visuals::npc_snap_lines_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "lines color" ), &options::visuals::npc_vis_snap_lines_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "show view direction" ), &options::visuals::show_view_direction, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "view direction color" ), &options::visuals::view_direction_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "view direction color" ), &options::visuals::vis_view_direction_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "view direction color" ), &options::visuals::npc_view_direction_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "view direction color" ), &options::visuals::npc_vis_view_direction_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "offscreen arrows" ), &options::visuals::offscreen_arrows, 1 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "oof color" ), &options::visuals::oof_color, 1 );
			break;
		case visible:
			g_framework.color_picker( xs( "oof color" ), &options::visuals::vis_oof_color, 1 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "oof color" ), &options::visuals::npc_oof_color, 1 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "oof color" ), &options::visuals::npc_vis_oof_color, 1 );
			break;
		}

		g_framework.create_check_box( xs( "chams" ), &options::visuals::chams, 1 );
		if( options::visuals::chams )
			g_framework.create_check_box( xs( "rgb chams" ), &options::visuals::rgb_chams, 1 );

		g_framework.create_combo_box( chams_vector, &options::visuals::chams_type, 1 );
					
		g_framework.create_label( xs( "states" ), 2 );
		g_framework.create_check_box( xs( "show sleepers" ), &options::visuals::can_show_sleepers, 2 );
		g_framework.create_check_box( xs( "show knocked" ), &options::visuals::can_show_knocked, 2 );
		g_framework.create_check_box( xs( "show npc" ), &options::visuals::can_show_npc, 2 );
		if( options::visuals::offscreen_arrows ) {
			g_framework.create_check_box( xs( "show sleepers oof" ), &options::visuals::can_show_sleepers_oof, 2 );
			g_framework.create_check_box( xs( "show knocked oof" ), &options::visuals::can_show_knocked_oof, 2 );
			g_framework.create_check_box( xs( "show npc oof" ), &options::visuals::can_show_npc_oof, 2 );
		}

		g_framework.create_label( xs( "flags" ), 2 );
		g_framework.create_check_box( xs( "in duck" ), &options::visuals::show_ducking_flag, 2 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "ducking color" ), &options::visuals::ducking_color, 2 );
			break;
		case visible:
			g_framework.color_picker( xs( "ducking color" ), &options::visuals::vis_ducking_color, 2 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "ducking color" ), &options::visuals::npc_ducking_color, 2 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "ducking color" ), &options::visuals::npc_vis_ducking_color, 2 );
			break;
		}

		g_framework.create_check_box( xs( "is knocked" ), &options::visuals::show_knocked_flag, 2 );
		switch( options::color_tab ) {
		case invisible:
			g_framework.color_picker( xs( "knocked color" ), &options::visuals::knocked_color, 2 );
			break;
		case visible:
			g_framework.color_picker( xs( "knocked color" ), &options::visuals::vis_knocked_color, 2 );
			break;
		case npc_invisible:
			g_framework.color_picker( xs( "knocked color" ), &options::visuals::npc_knocked_color, 2 );
			break;
		case npc_visible:
			g_framework.color_picker( xs( "knocked color" ), &options::visuals::npc_vis_knocked_color, 2 );
			break;
		}

		g_framework.create_label( xs( "information" ), 2 );
		g_framework.create_check_box( xs( "show hot-bar" ), &options::visuals::show_hotbar, 2 );
		g_framework.create_check_box( xs( "show clothes" ), &options::visuals::show_clothes, 2 );

		g_framework.slider_int( xs( "player max distance" ), &options::visuals::max_player_distance, 0, max_distance, 2 );

		if( !options::visuals::rgb_chams ) {
			if( options::visuals::chams_type != 3 ) {
				bool one_color = options::visuals::chams_type == 6 || options::visuals::chams_type == 5;
				if( options::color_tab == invisible
					|| one_color )
					g_framework.color_picker( xs( "chams color" ), &options::visuals::chams_color, 1 );
				else
					g_framework.color_picker( xs( "chams color" ), &options::visuals::chams_visible, 1 );
			}
		}
	}
}

void c_menu::draw_worlds_tab( ) {
	g_framework.create_check_box( xs( "master-switch" ), &options::visuals::world::master_switch, 1 );

	if( options::visuals::world::master_switch ) {
		g_framework.create_check_box( xs( "show distance" ), &options::visuals::world::show_distance, 1 );
		g_framework.create_check_box( xs( "show health" ), &options::visuals::world::show_health, 1 );
		g_framework.create_check_box( xs( "show amount of items" ), &options::visuals::world::show_item_amount, 1 );

		g_framework.create_check_box( xs( "prefab name debug" ), &options::visuals::prefab_name_debug, 1 );
		g_framework.create_check_box( xs( "class name debug" ), &options::visuals::class_name_debug, 1 );

		// tab selection.
		g_framework.create_combo_box( tab_choice, &options::tab_selection, 1 );
		if( options::tab_selection == 0 ) {
			// first tab additionals.
			g_framework.create_combo_box( tab_list, &options::first_tab, 1 );

			if( options::first_tab == 1 ) {
				g_framework.create_label( xs( "additional" ), 1, true );
				g_framework.create_check_box( xs( "show grenades" ), &options::visuals::world::show_grenades, 1 );
				g_framework.create_check_box( xs( "player corpse" ), &options::visuals::world::show_corpse, 1 );
				g_framework.create_check_box( xs( "backpack" ), &options::visuals::world::show_backpack, 1 );

				g_framework.create_label( xs( "loot containers" ), 1, true );
				g_framework.create_check_box( xs( "mine crate" ), &options::visuals::world::show_mine_crate, 1 );
				g_framework.create_check_box( xs( "small loot crate" ), &options::visuals::world::show_small_crate, 1 );
				g_framework.create_check_box( xs( "tool box" ), &options::visuals::world::show_tool_box, 1 );
				g_framework.create_check_box( xs( "underwater crate" ), &options::visuals::world::show_underwater_crate, 1 );
				g_framework.create_check_box( xs( "elite crate" ), &options::visuals::world::show_elite_crate, 1 );
				g_framework.create_check_box( xs( "military crate" ), &options::visuals::world::show_military_crate, 1 );
				g_framework.create_check_box( xs( "food crate" ), &options::visuals::world::show_food_crate, 1 );
				g_framework.create_check_box( xs( "medical crate" ), &options::visuals::world::show_medical_crate, 1 );
				g_framework.create_check_box( xs( "normal crate" ), &options::visuals::world::show_normal_crate, 1 );
				g_framework.create_check_box( xs( "helicopter crate" ), &options::visuals::world::show_helicopter_crate, 1 );
				g_framework.create_check_box( xs( "bradley crate" ), &options::visuals::world::show_bradley_crate, 1 );
				g_framework.create_check_box( xs( "supply drop crate" ), &options::visuals::world::show_supply_drops, 1 );
				g_framework.create_check_box( xs( "supply signals" ), &options::visuals::world::show_supply_signals, 1 );
				g_framework.create_check_box( xs( "hackable locked crate" ), &options::visuals::world::show_hackable_locked_crate, 1 );
				g_framework.create_check_box( xs( "stashes" ), &options::visuals::world::show_stashes, 1 );

				g_framework.create_label( xs( "traps" ), 1, true );
				g_framework.create_check_box( xs( "landmine" ), &options::visuals::world::show_landmines, 1 );
				g_framework.create_check_box( xs( "npc turrets" ), &options::visuals::world::show_npc_turrets, 1 );
				g_framework.create_check_box( xs( "auto-turrets" ), &options::visuals::world::show_auto_turrets, 1 );
				g_framework.create_check_box( xs( "shotgun trap" ), &options::visuals::world::show_shotgun_traps, 1 );
				g_framework.create_check_box( xs( "tesla coil" ), &options::visuals::world::show_tesla_coil, 1 );
				g_framework.create_check_box( xs( "flame turret" ), &options::visuals::world::show_flame_turrets, 1 );
				g_framework.create_check_box( xs( "sam-site" ), &options::visuals::world::show_sam_site, 1 );
				g_framework.create_check_box( xs( "land spikes" ), &options::visuals::world::show_land_spikes, 1 );
				g_framework.create_check_box( xs( "bear trap" ), &options::visuals::world::show_bear_trap, 1 );
			}
			else {
				g_framework.create_label( xs( "items" ), 1, true );
				g_framework.create_check_box( xs( "weapons" ), &options::visuals::world::show_weapons, 1 );
				g_framework.create_check_box( xs( "melee weapons" ), &options::visuals::world::show_melee_weapons, 1 );
				g_framework.create_check_box( xs( "heal" ), &options::visuals::world::show_heal, 1 );
				g_framework.create_check_box( xs( "everything" ), &options::visuals::world::show_everything, 1 );
				g_framework.create_check_box( xs( "drone" ), &options::visuals::world::show_drone, 1 );
				g_framework.create_check_box( xs( "recycler" ), &options::visuals::world::show_recycler, 1 );
				g_framework.create_check_box( xs( "show nails and arrows" ), &options::visuals::world::show_ammo_nails_arrows, 1 );

				g_framework.create_label( xs( "ore collectibles" ), 1, true );
				g_framework.create_check_box( xs( "sulfur collectible" ), &options::visuals::world::show_sulfur_collectibles, 1 );
				g_framework.create_check_box( xs( "metal collectible" ), &options::visuals::world::show_metal_collectibles, 1 );
				g_framework.create_check_box( xs( "wood collectible" ), &options::visuals::world::show_wood_collectibles, 1 );
				g_framework.create_check_box( xs( "stone collectible" ), &options::visuals::world::show_stone_collectibles, 1 );

				g_framework.create_label( xs( "ores" ), 1, true );
				g_framework.create_check_box( xs( "sulfur ore" ), &options::visuals::world::show_sulfur_ore, 1 );
				g_framework.create_check_box( xs( "metal ore" ), &options::visuals::world::show_metal_ore, 1 );
				g_framework.create_check_box( xs( "stone ore" ), &options::visuals::world::show_stone_ore, 1 );

				g_framework.create_label( xs( "barrels" ), 1, true );
				g_framework.create_check_box( xs( "oil barrel" ), &options::visuals::world::show_oil_barrel, 1 );
				g_framework.create_check_box( xs( "regular barrels" ), &options::visuals::world::show_regular_barrels, 1 );
				g_framework.create_check_box( xs( "diesel barrels" ), &options::visuals::world::show_diesel_fuel, 1 );					

				g_framework.create_label( xs( "storages" ), 1, true );
				g_framework.create_check_box( xs( "tool cupboard" ), &options::visuals::world::show_tool_cupboard, 1 );
				g_framework.create_check_box( xs( "box storages" ), &options::visuals::world::show_box_storages, 1 );
				g_framework.create_check_box( xs( "vending machines" ), &options::visuals::world::show_vending_machine, 1 );
			}

			g_framework.create_label( xs( "food" ), 2, true );
			g_framework.create_check_box( xs( "hemp" ), &options::visuals::world::show_hemp, 2 );
			g_framework.create_check_box( xs( "mushroom" ), &options::visuals::world::show_mushroom, 2 );
			g_framework.create_check_box( xs( "pumpkin" ), &options::visuals::world::show_pumpkin, 2 );
			g_framework.create_check_box( xs( "corn" ), &options::visuals::world::show_corns, 2 );
			g_framework.create_check_box( xs( "berry" ), &options::visuals::world::show_berrys, 2 );
			g_framework.create_check_box( xs( "potato" ), &options::visuals::world::show_potatos, 2 );

			g_framework.create_label( xs( "animals" ), 2, true );
			g_framework.create_check_box( xs( "chicken" ), &options::visuals::world::show_chickens, 2 );
			g_framework.create_check_box( xs( "boars" ), &options::visuals::world::show_boars, 2 );
			g_framework.create_check_box( xs( "wolves" ), &options::visuals::world::show_wolves, 2 );
			g_framework.create_check_box( xs( "deer" ), &options::visuals::world::show_deers, 2 );
			g_framework.create_check_box( xs( "polar bear" ), &options::visuals::world::show_polar_bears, 2 );
			g_framework.create_check_box( xs( "bear" ), &options::visuals::world::show_bears, 2 );
			g_framework.create_check_box( xs( "sharks" ), &options::visuals::world::show_sharks, 2 );
			g_framework.create_check_box( xs( "horses" ), &options::visuals::world::show_horses, 2 );

			g_framework.create_label( xs( "vehicles" ), 2, true );
			g_framework.create_check_box( xs( "mini-copter" ), &options::visuals::world::show_minicopter, 2 );
			g_framework.create_check_box( xs( "scrap helicopter" ), &options::visuals::world::show_scrap_helicopter, 2 );
			g_framework.create_check_box( xs( "rhib" ), &options::visuals::world::show_rhib, 2 );
			g_framework.create_check_box( xs( "kayak" ), &options::visuals::world::show_kayak, 2 );
			g_framework.create_check_box( xs( "small motorboat" ), &options::visuals::world::show_small_motorboat, 2 );
			g_framework.create_check_box( xs( "solo submarine" ), &options::visuals::world::show_solo_submarine, 2 );
			g_framework.create_check_box( xs( "duo submarine" ), &options::visuals::world::show_duo_submarine, 2 );
			g_framework.create_check_box( xs( "bradley tank" ), &options::visuals::world::show_bradley_apc, 2 );

			g_framework.create_label( xs( "helicopters" ), 2, true );
			g_framework.create_check_box( xs( "attack helicopter" ), &options::visuals::world::show_attack_helicopter, 2 );
			g_framework.create_check_box( xs( "chinook helicopter" ), &options::visuals::world::show_chinook_helicopter, 2 );
			g_framework.create_check_box( xs( "patrol helicopter" ), &options::visuals::world::show_patrol_helicopter, 2 );

			g_framework.create_label( xs( "cars" ), 2, true );
			g_framework.create_check_box( xs( "modular car" ), &options::visuals::world::show_modular_car, 2 );
			g_framework.create_check_box( xs( "2 module car" ), &options::visuals::world::show_two_modules_car, 2 );
		}
		else if( options::tab_selection == 1 ) {
			// first tab additionals.
			g_framework.create_combo_box( tab_list, &options::first_tab, 1 );

			if( options::first_tab == 1 ) {
				g_framework.color_picker( xs( "player corpse" ), &options::visuals::world::color_corpse, 1 );
				g_framework.color_picker( xs( "backpack" ), &options::visuals::world::color_backpack, 1 );
				
				g_framework.create_label( xs( "loot containers" ), 1, true );

				g_framework.color_picker( xs( "mine crate" ), &options::visuals::world::color_mine_crate, 1 );
				g_framework.color_picker( xs( "small loot crate" ), &options::visuals::world::color_small_crate, 1 );
				g_framework.color_picker( xs( "tool box" ), &options::visuals::world::color_tool_box, 1 );
				g_framework.color_picker( xs( "underwater crate" ), &options::visuals::world::color_underwater_crate, 1 );
				g_framework.color_picker( xs( "elite crate" ), &options::visuals::world::color_elite_crate, 1 );
				g_framework.color_picker( xs( "military crate" ), &options::visuals::world::color_military_crate, 1 );
				g_framework.color_picker( xs( "food crate" ), &options::visuals::world::color_food_crate, 1 );
				g_framework.color_picker( xs( "medical crate" ), &options::visuals::world::color_medical_crate, 1 );
				g_framework.color_picker( xs( "normal crate" ), &options::visuals::world::color_normal_crate, 1 );
				g_framework.color_picker( xs( "helicopter crate" ), &options::visuals::world::color_helicopter_crate, 1 );
				g_framework.color_picker( xs( "bradley crate" ), &options::visuals::world::color_bradley_crate, 1 );
				g_framework.color_picker( xs( "supply drop crate" ), &options::visuals::world::color_supply_drops, 1 );
				g_framework.color_picker( xs( "supply signals" ), &options::visuals::world::color_supply_signals, 1 );
				g_framework.color_picker( xs( "hackable locked crate" ), &options::visuals::world::color_hackable_locked_crate, 1 );

				g_framework.create_label( xs( "traps" ), 1, true );
				g_framework.color_picker( xs( "landmine" ), &options::visuals::world::color_landmines, 1 );
				g_framework.color_picker( xs( "npc turrets" ), &options::visuals::world::color_npc_turrets, 1 );
				g_framework.color_picker( xs( "auto-turrets" ), &options::visuals::world::color_auto_turrets, 1 );
				g_framework.color_picker( xs( "shotgun trap" ), &options::visuals::world::color_shotgun_traps, 1 );
				g_framework.color_picker( xs( "tesla coil" ), &options::visuals::world::color_tesla_coil, 1 );
				g_framework.color_picker( xs( "flame turret" ), &options::visuals::world::color_flame_turrets, 1 );
				g_framework.color_picker( xs( "sam-site" ), &options::visuals::world::color_sam_site, 1 );
				g_framework.color_picker( xs( "land spikes" ), &options::visuals::world::color_land_spikes, 1 );
				g_framework.color_picker( xs( "bear trap" ), &options::visuals::world::color_bear_trap, 1 );
			}
			else {
				g_framework.create_label( xs( "items" ), 1, true );
				g_framework.color_picker( xs( "weapons" ), &options::visuals::world::color_weapons, 1 );
				g_framework.color_picker( xs( "melee weapons" ), &options::visuals::world::color_melee_weapons, 1 );
				g_framework.color_picker( xs( "heal" ), &options::visuals::world::color_heal, 1 );
				g_framework.color_picker( xs( "everything" ), &options::visuals::world::color_everything, 1 );
				g_framework.color_picker( xs( "drone" ), &options::visuals::world::color_drone, 1 );
				g_framework.color_picker( xs( "recycler" ), &options::visuals::world::color_recycler, 1 );

				g_framework.create_label( xs( "ore collectibles" ), 1, true );
				g_framework.color_picker( xs( "sulfur collectible" ), &options::visuals::world::color_sulfur_collectibles, 1 );
				g_framework.color_picker( xs( "metal collectible" ), &options::visuals::world::color_metal_collectibles, 1 );
				g_framework.color_picker( xs( "wood collectible" ), &options::visuals::world::color_wood_collectibles, 1 );
				g_framework.color_picker( xs( "stone collectible" ), &options::visuals::world::color_stone_collectibles, 1 );

				g_framework.create_label( xs( "ores" ), 1, true );
				g_framework.color_picker( xs( "sulfur ore" ), &options::visuals::world::color_sulfur_ore, 1 );
				g_framework.color_picker( xs( "metal ore" ), &options::visuals::world::color_metal_ore, 1 );
				g_framework.color_picker( xs( "stone ore" ), &options::visuals::world::color_stone_ore, 1 );

				g_framework.create_label( xs( "barrels" ), 1, true );
				g_framework.color_picker( xs( "oil barrel" ), &options::visuals::world::color_oil_barrel, 1 );
				g_framework.color_picker( xs( "regular barrels" ), &options::visuals::world::color_regular_barrels, 1 );
				g_framework.color_picker( xs( "diesel barrels" ), &options::visuals::world::color_diesel_fuel, 1 );					

				g_framework.create_label( xs( "storages" ), 1, true );
				g_framework.color_picker( xs( "tool cupboard" ), &options::visuals::world::color_tool_cupboard, 1 );
				g_framework.color_picker( xs( "box storages" ), &options::visuals::world::color_box_storages, 1 );
				g_framework.color_picker( xs( "vending machines" ), &options::visuals::world::color_vending_machine, 1 );
			}

			g_framework.create_label( xs( "food" ), 2, true );
			g_framework.color_picker( xs( "hemp" ), &options::visuals::world::color_hemp, 2 );
			g_framework.color_picker( xs( "mushroom" ), &options::visuals::world::color_mushroom, 2 );
			g_framework.color_picker( xs( "pumpkin" ), &options::visuals::world::color_pumpkin, 2 );
			g_framework.color_picker( xs( "corn" ), &options::visuals::world::color_corns, 2 );
			g_framework.color_picker( xs( "berry" ), &options::visuals::world::color_berrys, 2 );
			g_framework.color_picker( xs( "potato" ), &options::visuals::world::color_potatos, 2 );

			g_framework.create_label( xs( "animals" ), 2, true );
			g_framework.color_picker( xs( "chicken" ), &options::visuals::world::color_chickens, 2 );
			g_framework.color_picker( xs( "boars" ), &options::visuals::world::color_boars, 2 );
			g_framework.color_picker( xs( "wolves" ), &options::visuals::world::color_wolves, 2 );
			g_framework.color_picker( xs( "deer" ), &options::visuals::world::color_deers, 2 );
			g_framework.color_picker( xs( "polar bear" ), &options::visuals::world::color_polar_bears, 2 );
			g_framework.color_picker( xs( "bear" ), &options::visuals::world::color_bears, 2 );
			g_framework.color_picker( xs( "sharks" ), &options::visuals::world::color_sharks, 2 );
			g_framework.color_picker( xs( "horses" ), &options::visuals::world::color_horses, 2 );

			g_framework.create_label( xs( "vehicles" ), 2, true );
			g_framework.color_picker( xs( "mini-copter" ), &options::visuals::world::color_minicopter, 2 );
			g_framework.color_picker( xs( "scrap helicopter" ), &options::visuals::world::color_scrap_helicopter, 2 );
			g_framework.color_picker( xs( "rhib" ), &options::visuals::world::color_rhib, 2 );
			g_framework.color_picker( xs( "kayak" ), &options::visuals::world::color_kayak, 2 );
			g_framework.color_picker( xs( "small motorboat" ), &options::visuals::world::color_small_motorboat, 2 );
			g_framework.color_picker( xs( "solo submarine" ), &options::visuals::world::color_solo_submarine, 2 );
			g_framework.color_picker( xs( "duo submarine" ), &options::visuals::world::color_duo_submarine, 2 );
			g_framework.color_picker( xs( "bradley tank" ), &options::visuals::world::color_bradley_apc, 2 );

			g_framework.create_label( xs( "helicopters" ), 2, true );
			g_framework.color_picker( xs( "attack helicopter" ), &options::visuals::world::color_attack_helicopter, 2 );
			g_framework.color_picker( xs( "chinook helicopter" ), &options::visuals::world::color_chinook_helicopter, 2 );
			g_framework.color_picker( xs( "patrol helicopter" ), &options::visuals::world::color_patrol_helicopter, 2 );

			g_framework.create_label( xs( "cars" ), 2, true );
			g_framework.color_picker( xs( "modular car" ), &options::visuals::world::color_modular_car, 2 );
			g_framework.color_picker( xs( "2 module car" ), &options::visuals::world::color_two_modules_car, 2 );
		}
		else {
			g_framework.slider_int( xs( "helicopter max distance" ), &options::visuals::world::max_helicopter_distance, 0, max_distance, 1 );
			g_framework.slider_int( xs( "ores max distance" ), &options::visuals::world::max_ores_distance, 0, max_distance, 1 );
			g_framework.slider_int( xs( "corpse max distance" ), &options::visuals::world::max_corpse_distance, 0, max_distance, 1 );
			g_framework.slider_int( xs( "ore collectibles max distance" ), &options::visuals::world::max_ore_collectibles_distance, 0, max_distance, 1 );
			g_framework.slider_int( xs( "loot containers max distance" ), &options::visuals::world::max_container_distance, 0, max_distance, 1 );
			g_framework.slider_int( xs( "food collectibles max distance" ), &options::visuals::world::max_food_collectibles_distance, 0, max_distance, 1 );
			g_framework.slider_int( xs( "respawn points max distance" ), &options::visuals::world::max_respawn_points_distance, 0, max_distance, 1 );
			g_framework.slider_int( xs( "barrels max distance" ), &options::visuals::world::max_barrels_distance, 0, max_distance, 1 );
			g_framework.slider_int( xs( "cars max distance" ), &options::visuals::world::max_cars_distance, 0, max_distance, 1 );

			g_framework.slider_int( xs( "items max distance" ), &options::visuals::world::max_item_distance, 0, max_distance, 2 );
			g_framework.slider_int( xs( "grenades max distance" ), &options::visuals::world::max_grenade_distance, 0, max_distance, 2 );
			g_framework.slider_int( xs( "animal max distance" ), &options::visuals::world::max_animal_distance, 0, max_distance, 2 );
			g_framework.slider_int( xs( "traps max distance" ), &options::visuals::world::max_trap_distance, 0, max_distance, 2 );
			g_framework.slider_int( xs( "stashes max distance" ), &options::visuals::world::max_stash_distance, 0, max_distance, 2 );
			g_framework.slider_int( xs( "storages max distance" ), &options::visuals::world::max_storage_distance, 0, max_distance, 2 );
			g_framework.slider_int( xs( "vehicle max distance" ), &options::visuals::world::max_vehicle_distance, 0, max_distance, 2 );
			g_framework.slider_int( xs( "raid max distance" ), &options::visuals::world::max_raid_distance, 0, max_distance, 2 );
		}
	}
}
	
void c_menu::draw_combat_tab( ) {
	g_framework.create_check_box( xs( "aim during cycle" ), &options::aimbot::exploits::combat::aim_bolt_cycle, 1 );
	g_framework.create_check_box( xs( "can aim on jugger clothes" ), &options::aimbot::exploits::combat::unlock_aim_on_jugger, 1 );
	g_framework.create_check_box( xs( "burst weapons" ), &options::aimbot::exploits::combat::burst_weapons, 1 );
	g_framework.create_check_box( xs( "automatic weapons" ), &options::aimbot::exploits::combat::automatic_weapons, 1 );
	g_framework.create_check_box( xs( "semi-automatic weapons" ), &options::aimbot::exploits::combat::semi_automatic_weapons, 1 );
	//g_framework.create_check_box( xs( "reduce shotgun spread" ), &options::aimbot::exploits::combat::no_shot_gun_spread, 1 );
	g_framework.create_check_box( xs( "reduce spread" ), &options::aimbot::exploits::combat::no_spread, 1 );
	g_framework.slider_float( xs( "spread amount" ), &options::aimbot::exploits::combat::reduce_spread, 0.0f, 100.f, 1 );
	g_framework.create_check_box( xs( "remove sway" ), &options::aimbot::exploits::combat::no_sway, 1 );
	g_framework.create_check_box( xs( "modify eoka chance" ), &options::aimbot::exploits::combat::modify_eoka_chance, 1 );
	g_framework.slider_float( xs( "eoka chance" ), &options::aimbot::exploits::combat::eoka_chance, 0.0f, 100.f, 1 );
	g_framework.create_check_box( xs( "reduce recoil" ), &options::aimbot::exploits::combat::no_recoil, 1 );
	g_framework.slider_float( xs( "recoil amount" ), &options::aimbot::exploits::combat::reduce_recoil, 0.0f, 100.f, 1 );
	g_framework.create_check_box( xs( "extended melee" ), &options::aimbot::exploits::combat::extended_melee, 1 );
	g_framework.slider_float( xs( "attack radius" ), &options::aimbot::exploits::combat::attack_radius, 0.0f, 2.5f, 1 );
	//g_framework.create_check_box( xs( "big bullets" ), &options::aimbot::exploits::combat::big_bullets, 1 );
	//g_framework.slider_float( xs( "bullet size" ), &options::aimbot::exploits::combat::bullet_size, 0.0f, 250.f, 1 );
	g_framework.create_check_box( xs( "quick bullets" ), &options::aimbot::exploits::combat::quick_bullets, 1 );
	g_framework.slider_int( xs( "bullet speed" ), &options::aimbot::exploits::combat::bullet_speed, 50, 145, 1 );
	g_framework.create_check_box( xs( "spoof hit distance" ), &options::aimbot::exploits::combat::spoof_hit_distance, 1 );
	g_framework.slider_float( xs( "bullet distance" ), &options::aimbot::exploits::combat::bullet_distance, 1.0f, 1000.f, 1 );
	//g_framework.create_check_box( xs( "pierce" ), &options::aimbot::exploits::combat::pierce, 1 );
	g_framework.create_check_box( xs( "attack in air" ), &options::aimbot::exploits::combat::modify_can_attack, 1 );
	g_framework.create_check_box( xs( "attack in vehicles" ), &options::aimbot::exploits::combat::can_attack_in_vehicles, 1 );
	g_framework.create_check_box( xs( "unlock viewangles" ), &options::aimbot::exploits::combat::unlock_view_angles, 1 );
	g_framework.create_check_box( xs( "fake fire" ), &options::aimbot::exploits::misc::fake_fire, 1 );
	g_framework.create_check_box( xs( "fake fire always on" ), &options::aimbot::exploits::misc::fake_fire_on, 1 );	
	g_framework.slider_float( xs( "fire delay" ), &options::aimbot::exploits::misc::delay_fake_fire, 0.0f, 1000.f, 1 );				

	g_framework.create_check_box( xs( "teleport to player head" ), &options::aimbot::exploits::combat::head_teleportation, 2 );

	if( options::aimbot::exploits::combat::head_teleportation )
		g_framework.create_hotkey( xs( "teleport key" ), &options::aimbot::exploits::combat::teleport_key, 2 );

	if( !options::aimbot::exploits::misc::fake_fire_on )
		g_framework.create_hotkey( xs( "fake fire key" ), &options::aimbot::exploits::misc::fake_fire_key, 2 );
}

void c_menu::draw_time_tab( ) {
	g_framework.create_check_box( xs( "rapid-fire" ), &options::aimbot::exploits::time::rapid_fire, 1 );
	g_framework.slider_float( xs( "fire speed" ), &options::aimbot::exploits::time::rapid_fire_speed, 0.0f, 20.f, 1 );
	g_framework.create_check_box( xs( "instant revive" ), &options::aimbot::exploits::time::instant_revive, 1 );
	g_framework.create_check_box( xs( "always revive target" ), &options::aimbot::exploits::time::always_revive_target, 1 );
	g_framework.create_check_box( xs( "instant charge compound" ), &options::aimbot::exploits::time::instant_charge_compound, 1 );

	g_framework.create_label( xs( "additional" ), 2, true );
	g_framework.create_check_box( xs( "fake-lag" ), &options::aimbot::exploits::time::fake_lag, 2 );
	g_framework.create_check_box( xs( "fake-lag always on" ), &options::aimbot::exploits::time::fake_lag_on, 2 );
	g_framework.slider_float( xs( "fake-lag amount" ), &options::aimbot::exploits::time::fake_lag_amount, 0.0f, 2.f, 2 );
	if( !options::aimbot::exploits::time::fake_lag_on )
		g_framework.create_hotkey( xs( "fake-lag key" ), &options::aimbot::exploits::time::fake_lag_key, 2 );

	g_framework.create_check_box( xs( "fast heal" ), &options::aimbot::exploits::time::fast_heal, 2 );
	g_framework.create_check_box( xs( "fast switch" ), &options::aimbot::exploits::time::fast_switch, 2 );
	g_framework.create_check_box( xs( "fast loot" ), &options::aimbot::exploits::time::fast_loot, 2 );

	g_framework.create_check_box( xs( "fast bow" ), &options::aimbot::exploits::time::fast_bow, 2 );

	if( !options::aimbot::exploits::time::always_revive_target )
		g_framework.create_hotkey( xs( "revive key" ), &options::aimbot::exploits::time::revive_key, 1 );
}

void c_menu::draw_movement_tab( ) {
	g_framework.create_check_box( xs( "walk through trees" ), &options::aimbot::exploits::movement::walk_through_trees, 1 );
	g_framework.create_check_box( xs( "walk through ai" ), &options::aimbot::exploits::movement::walk_through_players, 1 );

	g_framework.create_check_box( xs( "modify clothing speed" ), &options::aimbot::exploits::movement::modify_clothing_speed, 1 );
	g_framework.slider_float( xs( "clothing speed" ), &options::aimbot::exploits::movement::clothing_speed, 0.f, 2.5f, 1 );			

	g_framework.create_check_box( xs( "always sprint" ), &options::aimbot::exploits::movement::always_sprint, 1 );
				
	g_framework.create_check_box( xs( "speed hack" ), &options::aimbot::exploits::movement::omni_sprint, 1 );
	g_framework.slider_float( xs( "[s] speed" ), &options::aimbot::exploits::movement::omni_sprint_speed, 100.0f, 300.f, 1 );
	g_framework.create_check_box( xs( "infinite jump" ), &options::aimbot::exploits::movement::infinite_jump, 1 );
	g_framework.create_check_box( xs( "silent walk(shift)" ), &options::aimbot::exploits::movement::silent_walk, 1 );
	g_framework.create_check_box( xs( "climb assistance" ), &options::aimbot::exploits::movement::climb_assist, 1 );
	g_framework.create_check_box( xs( "no slow down on melee" ), &options::aimbot::exploits::movement::disable_slow_down_melee, 1 );
	g_framework.create_check_box( xs( "high jump" ), &options::aimbot::exploits::movement::high_jump, 1 );
	g_framework.slider_float( xs( "jump height" ), &options::aimbot::exploits::movement::jump_height, 100.0f, 275.f, 1 );
	g_framework.create_check_box( xs( "fly-hack" ), &options::aimbot::exploits::movement::fly_hack, 1 );
	g_framework.slider_int( xs( "fly speed" ), &options::aimbot::exploits::movement::fly_speed, 0.0f, 1000.f, 1 );
	g_framework.create_check_box( xs( "anti fly violation" ), &options::aimbot::exploits::movement::stopper_fly, 1 );

	g_framework.create_hotkey( xs( "fly key" ), &options::aimbot::exploits::movement::fly_key, 1 );

	g_framework.create_hotkey( xs( "ignore stopper key" ), &options::aimbot::exploits::movement::ignore_key, 1 );

	g_framework.create_check_box( xs( "increase height" ), &options::aimbot::exploits::movement::increase_height, 2 );
	g_framework.slider_float( xs( "height amount" ), &options::aimbot::exploits::movement::height_amount, 1.8f, 7.5f, 2 );
	g_framework.create_hotkey( xs( "height key" ), &options::aimbot::exploits::movement::increase_height_key, 2 );

	if( options::aimbot::exploits::movement::omni_sprint )
		g_framework.create_hotkey( xs( "speed-hack bind" ), &options::aimbot::exploits::movement::omni_sprint_key, 2 );
}

void c_menu::draw_misc_tab( ) {
	g_framework.create_check_box( xs( "enable friend system" ), &options::friend_system, 1 );
	g_framework.create_hotkey( xs( "add friend key" ), &options::add_friend_key, 1 );

	g_framework.create_label( xs( "disablers" ), 1 );
	g_framework.create_check_box( xs( "disarm landmines" ), &options::aimbot::exploits::misc::disarm_landmines, 1 );
	g_framework.create_check_box( xs( "disable recycler" ), &options::aimbot::exploits::misc::stop_recycler, 1 );

	g_framework.create_check_box( xs( "interactive debug" ), &options::aimbot::exploits::misc::interactive_debug, 2 );
	g_framework.create_check_box( xs( "gesture spam" ), &options::aimbot::exploits::misc::gesture_spam, 2 );
	g_framework.create_combo_box( default_gestures, &options::aimbot::exploits::misc::gesture_type, 2 );

	g_framework.create_check_box( xs( "debug camera" ), &options::aimbot::exploits::misc::debug_camera, 1 );
	g_framework.create_hotkey( xs( "debug camera key" ), &options::aimbot::exploits::misc::debug_camera_key, 1 );

	g_framework.create_check_box( xs( "disable land damage" ), &options::aimbot::exploits::misc::disable_land_damage, 1 );
	g_framework.create_check_box( xs( "always hit weak spot" ), &options::aimbot::exploits::misc::always_hit_weak_spot, 1 );

	g_framework.create_check_box( xs( "change fov" ), &options::aimbot::exploits::misc::fov_changer, 1 );
	g_framework.slider_int( xs( "fov amount" ), &options::aimbot::exploits::misc::fov_amount, 0.0f, 150, 1 );
	g_framework.create_check_box( xs( "zoom" ), &options::aimbot::exploits::misc::zoom_fov, 1 );
	g_framework.slider_int( xs( "zoom fov amount" ), &options::aimbot::exploits::misc::zoom_fov_amount, 0.0f, 40.f, 1 );
		
	g_framework.create_check_box( xs( "keep wounded alive" ), &options::aimbot::exploits::misc::keep_wounded_alive, 1 );
				
	g_framework.create_check_box( xs( "use max view" ), &options::aimbot::exploits::misc::use_max_view, 1 );

	g_framework.create_check_box( xs( "view offset height" ), &options::aimbot::exploits::misc::long_neck, 1 );
	g_framework.slider_float( xs( "height" ), &options::aimbot::exploits::misc::long_neck_height, 0.f, 1.50f, 1 );
	g_framework.create_check_box( xs( "view offset right" ), &options::aimbot::exploits::misc::long_neck_right, 1 );
	g_framework.slider_float( xs( "right" ), &options::aimbot::exploits::misc::long_neck_right_amount, 0.f, 1.50f, 1 );
	g_framework.create_check_box( xs( "view offset left" ), &options::aimbot::exploits::misc::long_neck_left, 1 );
	g_framework.slider_float( xs( "left" ), &options::aimbot::exploits::misc::long_neck_left_amount, 0.f, 1.50f, 1 );

	g_framework.create_check_box( xs( "spin-bot" ), &options::aimbot::exploits::misc::spin_bot, 1 );

	g_framework.create_check_box( xs( "suicide" ), &options::aimbot::exploits::misc::suicide, 1 );

	g_framework.create_check_box( xs( "fake admin" ), &options::aimbot::exploits::misc::fake_admin, 1 );			

	g_framework.create_label( xs( "view" ), 2 );
	g_framework.create_check_box( xs( "no view lower" ), &options::aimbot::exploits::misc::no_lower, 2 );
	g_framework.create_check_box( xs( "no view bob" ), &options::aimbot::exploits::misc::no_viewmodel_bob, 2 );
	g_framework.create_check_box( xs( "no flash" ), &options::aimbot::exploits::misc::no_flash, 2 );

	g_framework.create_check_box( xs( "remove water blur" ), &options::visuals::world::clear_underwater, 2 );

	g_framework.create_check_box( xs( "watermark" ), &options::visuals::show_watermark, 2 );				
				
	g_framework.create_label( xs( "bind related" ), 2 );
	g_framework.create_hotkey( xs( "height key" ), &options::aimbot::exploits::misc::view_height, 2 );
	g_framework.create_hotkey( xs( "right key" ), &options::aimbot::exploits::misc::view_right, 2 );
	g_framework.create_hotkey( xs( "left key" ), &options::aimbot::exploits::misc::view_left, 2 );
	g_framework.create_hotkey( xs( "zoom key" ), &options::aimbot::exploits::misc::zoom_key, 2 );

	g_framework.create_hotkey( xs( "suicide key" ), &options::aimbot::exploits::misc::suicide_key, 2 );
}

void c_menu::draw_modulations_tab( ) {
	g_framework.create_check_box( xs( "modify rain" ), &options::visuals::world::modify_rain, 1 );
	g_framework.slider_float( xs( "rain amount" ), &options::visuals::world::rain_amount, 0.f, 5.f, 1 );

	//g_framework.create_check_box( xs( "night stars" ), &options::visuals::world::night_stars, 1 );
	g_framework.create_check_box( xs( "change aspect ratio" ), &options::visuals::world::aspect_changer, 1 );
	g_framework.slider_float( xs( "aspect ratio" ), &options::visuals::world::aspect_value, 0.1f, 1.92f, 1 );
				
	g_framework.create_check_box( xs( "change time duration" ), &options::aimbot::exploits::time::time_modifier, 1 );
	g_framework.slider_float( xs( "time" ), &options::aimbot::exploits::time::time_speed, 0.0f, 24.f, 1 );

	g_framework.create_check_box( xs( "mie changer" ), &options::visuals::world::mie_changer, 1 );
	if( options::visuals::world::mie_changer )
		g_framework.slider_float( xs( "mie amount" ), &options::visuals::world::mie_amount, 1.0f, 100.f, 1 );	

	g_framework.create_check_box( xs( "rayleigh changer" ), &options::visuals::world::rayleigh_changer, 1 );
	if( options::visuals::world::rayleigh_changer )
		g_framework.slider_float( xs( "rayleigh amount" ), &options::visuals::world::rayleigh_amount, 1.0f, 100.f, 1 );

	g_framework.create_check_box( xs( "stars brightness" ), &options::visuals::world::stars, 1 );
	if( options::visuals::world::stars )
		g_framework.slider_float( xs( "stars amount" ), &options::visuals::world::brightness_stars_amount, 1.0f, 5000.f, 1 );
				
	g_framework.create_check_box( xs( "stars size" ), &options::visuals::world::stars_size, 1 );
	if( options::visuals::world::stars_size )
		g_framework.slider_float( xs( "stars amount size" ), &options::visuals::world::size_stars_amount, 1.0f, 50.f, 1 );

	g_framework.create_check_box( xs( "change ambient" ), &options::visuals::world::ambient, 1 );
	if( options::visuals::world::ambient ) { 
		g_framework.slider_float( xs( "ambient value" ), &options::visuals::world::ambient_value, 1.0f, 15.f, 1 );
		g_framework.slider_float( xs( "light value" ), &options::visuals::world::light_value, 1.0f, 15.f, 1 );
	}

	g_framework.create_check_box( xs( "change world color" ), &options::visuals::world::change_world_color, 1 );
	g_framework.color_picker( xs( "sky color" ), &options::visuals::world::sky_color, 1 );
	g_framework.color_picker( xs( "ambient color" ), &options::visuals::world::ambient_color, 1 );
}

void c_menu::draw_automations_tab( ) {
	g_framework.create_check_box( xs( "auto pickup items" ), &options::aimbot::exploits::misc::auto_pickup_items, 1 );
	if( options::aimbot::exploits::misc::auto_pickup_items )
		g_framework.create_check_box( xs( "pickup everything" ), &options::aimbot::exploits::misc::pickup_everything, 1 );
	g_framework.create_hotkey( xs( "pickup key" ), &options::aimbot::exploits::misc::pickup_key, 1 );
	g_framework.slider_float( xs( "item distance" ), &options::aimbot::exploits::misc::max_item_distance, 0.f, 15.f, 1 );
	g_framework.create_check_box( xs( "always pickup items" ), &options::aimbot::exploits::misc::always_pickup, 1 );

	g_framework.create_check_box( xs( "auto pickup collectibles" ), &options::aimbot::exploits::misc::auto_pickup, 1 );
	g_framework.slider_float( xs( "collectible distance" ), &options::aimbot::exploits::misc::max_collectible_distance, 0.f, 15.f, 1 );

	g_framework.create_check_box( xs( "always set code" ), &options::aimbot::exploits::misc::always_codelock, 1 );
	g_framework.create_check_box( xs( "auto code lock" ), &options::aimbot::exploits::misc::auto_codelock, 1 );
	g_framework.slider_int( xs( "code" ), &options::aimbot::exploits::misc::code_lock_code, 1000, 9999, 1 );
	g_framework.slider_float( xs( "lock distance" ), &options::aimbot::exploits::misc::max_lock_distance, 0.f, 15.f, 1 );
	g_framework.create_hotkey( xs( "code key" ), &options::aimbot::exploits::misc::codelock_key, 1 );

	g_framework.create_check_box( xs( "always grade" ), &options::aimbot::exploits::misc::always_grade, 1 );
	g_framework.create_check_box( xs( "auto grade" ), &options::aimbot::exploits::misc::auto_grade, 1 );
	g_framework.slider_float( xs( "grade distance" ), &options::aimbot::exploits::misc::max_grade_distance, 0.f, 100.f, 1 );
	g_framework.create_combo_box( grade_tier_list, &options::aimbot::exploits::misc::grade_tier, 1 );
	g_framework.create_hotkey( xs( "grade key" ), &options::aimbot::exploits::misc::grade_key, 1 );

	g_framework.create_check_box( xs( "auto untie crates" ), &options::aimbot::exploits::misc::auto_untie_crates, 1 );

	g_framework.create_label( xs( "farm" ), 2 );
	g_framework.create_check_box( xs( "auto farm barrels" ), &options::aimbot::exploits::misc::auto_farm_barrels, 2 );
	g_framework.create_check_box( xs( "auto farm ores" ), &options::aimbot::exploits::misc::auto_farm_ores, 2 );
	g_framework.create_check_box( xs( "auto farm trees" ), &options::aimbot::exploits::misc::auto_farm_trees, 2 );
	g_framework.create_check_box( xs( "farm hotspot" ), &options::aimbot::exploits::misc::auto_farm_only_hotspot, 2 );
}

/* draw menu */
void c_menu::draw_menu( ) {
	if( g_framework.get_ins( ) )
		g_framework.open = !g_framework.open;

	if( g_framework.open
		&& g_framework.alpha < 255.f )
		g_framework.alpha = std::lerp( g_framework.alpha, 255.f, 0.35f );
	else if( !g_framework.open
		&& g_framework.alpha > 0.f )
		g_framework.alpha = std::lerp( g_framework.alpha, 0.f, 0.35f );

	g_framework.in_alpha = g_framework.alpha > 5.f;
	options::accent_color.a = g_framework.alpha;

	if( !g_framework.in_alpha ) {
		g_framework.pressed_key = false;
		g_framework.active_hotkey = g_framework.active_picker = -1;
		return;
	}

	g_framework.begin( );
	g_framework.create_tab( xs( "aimbot" ), 0, 1 );
	g_framework.create_tab( xs( "players" ), 1, 2 );
	g_framework.create_tab( xs( "world" ), 2, 3 );
	g_framework.create_tab( xs( "weapon mods" ), 3, 4 );
	g_framework.create_tab( xs( "time" ), 4, 5 );
	g_framework.create_tab( xs( "movement" ), 5, 6 );
	g_framework.create_tab( xs( "misc" ), 6, 7 );
	g_framework.create_tab( xs( "modulations" ), 7, 8 );
	g_framework.create_tab( xs( "automations" ), 8, 9 );
	g_framework.create_tab( xs( "main" ), 9, 10 );

	// vis check in aim
	// omni-sprint

	switch( g_framework.selected_tab ) {
	case 0:
		draw_aimbot_tab( );
	break;
	case 1:
		draw_visuals_tab( );
	break;
	case 2:
		draw_worlds_tab( );
	break;
	case 3:
		draw_combat_tab( );
	break;
	case 4:
		draw_time_tab( );
	break;
	case 5:
		draw_movement_tab( );
	break;
	case 6:
		draw_misc_tab( );
	break;
	case 7:
		draw_modulations_tab( );
	break;
	case 8:
		draw_automations_tab( );
	break;
	case 9:
		draw_menu_tab( );
	break;
	}

	g_framework.end( );
}

#pragma once
#include "../../includes/includes.hpp"

class c_menu {
public:
	int max_distance = 5000;

	enum color_tab_t {
		visible = 0,
		invisible = 1,
		npc_visible = 2,
		npc_invisible = 3
	};

	std::vector< std::string > bones = { xs( "head" ), xs( "neck" ), xs( "pelvis" ), xs( "dick" ) };

	std::vector< std::string > box_esp_color_tone = { xs( "green" ), xs( "turquoise" ), xs( "blue" ), xs( "purple" ) };

	std::vector< std::string > box_esp_mode = { xs( "off" ), xs( "normal" ), xs( "corner" ), xs( "3d box" ) };

	std::vector< std::string > aim_mode = { xs( "off" ), xs( "silent" ), xs( "memory" ) };

	std::vector< std::string > smooth_type = { xs( "off" ), xs( "constant" ), xs( "regular" ) };

	std::vector< std::string > chams_vector = { xs( "flat" ), xs( "hologram" ), xs( "invisible" ), xs( "galaxy" ), xs( "transparent" ), xs( "wireframe" ), xs( "circuit" ) };

	std::vector< std::string > cfg_vector = { xs( "rage" ), xs( "blatant" ), xs( "legit" ), xs( "secret" ), xs( "ziebel" ), xs( "alpha" ) };

	std::vector< std::string > color_list = { xs( "visible" ), xs( "invisible" ), xs( "npc visible" ), xs( "npc invisible" ) };

	std::vector< std::string > tab_list = { xs( "first" ), xs( "second" ) };

	std::vector< std::string > grade_tier_list = { xs( "none" ), xs( "wood" ), xs( "stone" ), xs( "metal" ), xs( "hqm" ) };

	std::vector< std::string > font_flags = { xs( "none" ), xs( "dropshadow" ), xs( "outline" ) };

	std::vector< std::string > tab_choice = { xs( "choice" ), xs( "colors" ), xs( "sliders" ) };

	std::vector< std::string > key_vector =
	{
		xs( "left mouse button" ), xs( "right mouse button" ),
		xs( "middle mouse button" ), xs( "x1 mouse button" ),
		xs( "x2 mouse button" ), xs( "control-break processing" ),
		xs( "backspace" ), xs( "tab" ), xs( "clear" ), xs( "enter" ),
		xs( "shift" ), xs( "ctrl" ), xs( "alt" ), xs( "caps lock" ),
		xs( "esc" ), xs( "space" ), xs( "a" ), xs( "b" ), xs( "c" ), xs( "d" ), xs( "e" ),
		xs( "f" ), xs( "g" ), xs( "h" ), xs( "i" ), xs( "j" ), xs( "k" ), xs( "l" ), xs( "m" ), xs( "n" ),
		xs( "o" ), xs( "p" ), xs( "q" ), xs( "r" ), xs( "s" ), xs( "t" ), xs( "u" ),
		xs( "v" ), xs( "w" ), xs( "x" ), xs( "y" ), xs( "z" ), xs( "f1" ), xs( "f2" ),
		xs( "f3" ), xs( "f4" ), xs( "f5" ), xs( "f6" ), xs( "f7" ), xs( "f8" ), xs( "f9" ),
		xs( "f10" ), xs( "f11" )
	};

	std::vector< std::string > default_gestures =
	{
		xs( "clap" ), xs( "friendly" ), xs( "thumbsdown" ),
		xs( "thumbsup" ), xs( "ok" ), xs( "point" ), xs( "shrug" ), xs( "victory" ),
		xs( "wave" ), xs( "cabbage patch" ), xs( "twist" )
	};

	/* draw menu tab */
	void draw_menu_tab( );

	/* draw aimbot tab */
	void draw_aimbot_tab( );

	/* draw visuals tab */
	void draw_visuals_tab( );

	/* draw world tab */
	void draw_worlds_tab( );
	
	/* draw combat tab */
	void draw_combat_tab( );

	/* draw time tab */
	void draw_time_tab( );

	/* draw movement tab */
	void draw_movement_tab( );

	/* draw misc tab */
	void draw_misc_tab( );

	/* draw modulations tab */
	void draw_modulations_tab( );

	/* draw automations tab */
	void draw_automations_tab( );

	/* draw menu */
	void draw_menu( );
};

extern c_menu g_menu;
#pragma once
#include "cfg.h"
#include "../../includes/hinclude.h"
#include "../options.h"
#include "../aimbot/aimbot.h"
#include "../visuals/esp.h"

// create global definition of cfg class.
c_cfg_sys g_cfg;

void c_cfg_sys::save_cfg( const std::string& filename ) {
	std::ofstream cfg_file( filename );
	if( !cfg_file.is_open( ) ) {
		std::cout << xs( "can't open file with name: " ) << filename << std::endl;
		return;
	}

	cfg_file << xs( "add_friend_key " ) << options::add_friend_key << std::endl;

	cfg_file << xs( "aim_check " ) << options::aimbot::aim_check << std::endl;
	cfg_file << xs( "smoothness " ) << options::aimbot::smoothness << std::endl;
	cfg_file << xs( "auto_fire " ) << options::aimbot::auto_fire << std::endl;
	cfg_file << xs( "should_simulate_movement " ) << options::aimbot::should_simulate_movement << std::endl;
	cfg_file << xs( "draw_fov " ) << options::aimbot::draw_fov << std::endl;
	cfg_file << xs( "draw_crosshair " ) << options::aimbot::draw_crosshair << std::endl;
	cfg_file << xs( "draw_target " ) << options::aimbot::draw_target << std::endl;
	cfg_file << xs( "aim_npc " ) << options::aimbot::aim_npc << std::endl;

	cfg_file << xs( "auto_pickup " ) << options::aimbot::exploits::misc::auto_pickup << std::endl;
	cfg_file << xs( "auto_grade " ) << options::aimbot::exploits::misc::auto_grade << std::endl;
	cfg_file << xs( "grade_tier " ) << options::aimbot::exploits::misc::grade_tier << std::endl;
	cfg_file << xs( "auto_pickup_items " ) << options::aimbot::exploits::misc::auto_pickup_items << std::endl;
	cfg_file << xs( "pickup_everything " ) << options::aimbot::exploits::misc::pickup_everything << std::endl;

	cfg_file << xs( "auto_farm_only_hotspot " ) << options::aimbot::exploits::misc::auto_farm_only_hotspot << std::endl;
	cfg_file << xs( "auto_farm_ores " ) << options::aimbot::exploits::misc::auto_farm_ores << std::endl;
	cfg_file << xs( "auto_farm_trees " ) << options::aimbot::exploits::misc::auto_farm_trees << std::endl;
	cfg_file << xs( "auto_farm_barrels " ) << options::aimbot::exploits::misc::auto_farm_barrels << std::endl;

	cfg_file << xs( "max_grade_distance " ) << options::aimbot::exploits::misc::max_grade_distance << std::endl;
	cfg_file << xs( "max_item_distance " ) << options::aimbot::exploits::misc::max_item_distance << std::endl;
	cfg_file << xs( "max_collectible_distance " ) << options::aimbot::exploits::misc::max_collectible_distance << std::endl;

	cfg_file << xs( "manipulation_key " ) << options::aimbot::manipulation_key << std::endl;

	cfg_file << xs( "aim_helicopter " ) << options::aimbot::aim_helicopter << std::endl;
	cfg_file << xs( "manipulation " ) << options::aimbot::manipulation << std::endl;
	cfg_file << xs( "kill_aura " ) << options::aimbot::kill_aura << std::endl;
	cfg_file << xs( "auto_reload " ) << options::aimbot::auto_reload << std::endl;
	cfg_file << xs( "aim_nearest_bone " ) << options::aimbot::aim_nearest_bone << std::endl;

	cfg_file << xs( "aim_type " ) << options::aimbot::aim_type << std::endl;

	cfg_file << xs( "aim_bone " ) << options::aimbot::aim_bone << std::endl;
	cfg_file << xs( "manipulation_key " ) << options::aimbot::manipulation_key << std::endl;
	cfg_file << xs( "smooth_type " ) << options::aimbot::smooth_type << std::endl;
	cfg_file << xs( "max_target_distance " ) << options::aimbot::max_target_distance << std::endl;
	cfg_file << xs( "fov_amount " ) << options::aimbot::fov_amount << std::endl;

	cfg_file << xs( "always_grade " ) << options::aimbot::exploits::misc::always_grade << std::endl;
	cfg_file << xs( "always_codelock " ) << options::aimbot::exploits::misc::always_codelock << std::endl;
	cfg_file << xs( "always_pickup " ) << options::aimbot::exploits::misc::always_pickup << std::endl;

	cfg_file << xs( "codelock_key " ) << options::aimbot::exploits::misc::codelock_key << std::endl;
	cfg_file << xs( "grade_key " ) << options::aimbot::exploits::misc::grade_key << std::endl;
	cfg_file << xs( "pickup_key " ) << options::aimbot::exploits::misc::pickup_key << std::endl;
	cfg_file << xs( "auto_codelock " ) << options::aimbot::exploits::misc::auto_codelock << std::endl;
	cfg_file << xs( "code_lock_code " ) << options::aimbot::exploits::misc::code_lock_code << std::endl;
	cfg_file << xs( "max_lock_distance " ) << options::aimbot::exploits::misc::max_lock_distance << std::endl;

	cfg_file << xs( "no_viewmodel_bob " ) << options::aimbot::exploits::misc::no_viewmodel_bob << std::endl;
	cfg_file << xs( "no_lower " ) << options::aimbot::exploits::misc::no_lower << std::endl;

	cfg_file << xs( "smoothness_amount " ) << options::aimbot::smoothness_amount << std::endl;

	cfg_file << xs( "infinite_jump " ) << options::aimbot::exploits::movement::infinite_jump << std::endl;
	cfg_file << xs( "stopper_fly " ) << options::aimbot::exploits::movement::stopper_fly << std::endl;
	cfg_file << xs( "climb_assist " ) << options::aimbot::exploits::movement::climb_assist << std::endl;
	cfg_file << xs( "fly_hack " ) << options::aimbot::exploits::movement::fly_hack << std::endl;
	cfg_file << xs( "omni_sprint " ) << options::aimbot::exploits::movement::omni_sprint << std::endl;
	cfg_file << xs( "silent_walk " ) << options::aimbot::exploits::movement::silent_walk << std::endl;
	cfg_file << xs( "always_sprint " ) << options::aimbot::exploits::movement::always_sprint << std::endl;
	cfg_file << xs( "high_jump " ) << options::aimbot::exploits::movement::high_jump << std::endl;

	cfg_file << xs( "walk_through_players " ) << options::aimbot::exploits::movement::walk_through_players << std::endl;
	cfg_file << xs( "disable_slow_down_melee " ) << options::aimbot::exploits::movement::disable_slow_down_melee << std::endl;
	cfg_file << xs( "modify_clothing_speed " ) << options::aimbot::exploits::movement::modify_clothing_speed << std::endl;
	cfg_file << xs( "increase_height " ) << options::aimbot::exploits::movement::increase_height << std::endl;

	cfg_file << xs( "fly_key " ) << options::aimbot::exploits::movement::fly_key << std::endl;
	cfg_file << xs( "ignore_key " ) << options::aimbot::exploits::movement::ignore_key << std::endl;
	cfg_file << xs( "omni_sprint_key " ) << options::aimbot::exploits::movement::omni_sprint_key << std::endl;
	cfg_file << xs( "silent_walk_key " ) << options::aimbot::exploits::movement::silent_walk_key << std::endl;
	cfg_file << xs( "increase_height_key " ) << options::aimbot::exploits::movement::increase_height_key << std::endl;
	cfg_file << xs( "fly_speed " ) << options::aimbot::exploits::movement::fly_speed << std::endl;
	cfg_file << xs( "jump_height " ) << options::aimbot::exploits::movement::jump_height << std::endl;
	cfg_file << xs( "omni_sprint_speed " ) << options::aimbot::exploits::movement::omni_sprint_speed << std::endl;
	cfg_file << xs( "height_amount " ) << options::aimbot::exploits::movement::height_amount << std::endl;

	cfg_file << xs( "show_ducking_flag " ) << options::visuals::show_ducking_flag << std::endl;
	cfg_file << xs( "ducking_color[0] " ) << options::visuals::ducking_color.r << std::endl;
	cfg_file << xs( "ducking_color[1] " ) << options::visuals::ducking_color.g << std::endl;
	cfg_file << xs( "ducking_color[2] " ) << options::visuals::ducking_color.b << std::endl;

	cfg_file << xs( "show_knocked_flag " ) << options::visuals::show_knocked_flag << std::endl;
	cfg_file << xs( "knocked_color[0] " ) << options::visuals::knocked_color.r << std::endl;
	cfg_file << xs( "knocked_color[1] " ) << options::visuals::knocked_color.g << std::endl;
	cfg_file << xs( "knocked_color[2] " ) << options::visuals::knocked_color.b << std::endl;

	cfg_file << xs( "sky_color[0] " ) << options::visuals::world::sky_color.r << std::endl;
	cfg_file << xs( "sky_color[1] " ) << options::visuals::world::sky_color.g << std::endl;
	cfg_file << xs( "sky_color[2] " ) << options::visuals::world::sky_color.b << std::endl;

	cfg_file << xs( "ambient_color[0] " ) << options::visuals::world::ambient_color.r << std::endl;
	cfg_file << xs( "ambient_color[1] " ) << options::visuals::world::ambient_color.g << std::endl;
	cfg_file << xs( "ambient_color[2] " ) << options::visuals::world::ambient_color.b << std::endl;

	cfg_file << xs( "automatic_weapons " ) << options::aimbot::exploits::combat::automatic_weapons << std::endl;
	cfg_file << xs( "semi_automatic_weapons " ) << options::aimbot::exploits::combat::semi_automatic_weapons << std::endl;
	cfg_file << xs( "burst_weapons " ) << options::aimbot::exploits::combat::burst_weapons << std::endl;
	cfg_file << xs( "unlock_aim_on_jugger " ) << options::aimbot::exploits::combat::unlock_aim_on_jugger << std::endl;
	cfg_file << xs( "aim_bolt_cycle " ) << options::aimbot::exploits::combat::aim_bolt_cycle << std::endl;
	cfg_file << xs( "extended_melee " ) << options::aimbot::exploits::combat::extended_melee << std::endl;
	cfg_file << xs( "no_spread " ) << options::aimbot::exploits::combat::no_spread << std::endl;
	cfg_file << xs( "no_sway " ) << options::aimbot::exploits::combat::no_sway << std::endl;
	cfg_file << xs( "modify_eoka_chance " ) << options::aimbot::exploits::combat::modify_eoka_chance << std::endl;
	cfg_file << xs( "no_recoil " ) << options::aimbot::exploits::combat::no_recoil << std::endl;
	cfg_file << xs( "modify_can_attack " ) << options::aimbot::exploits::combat::modify_can_attack << std::endl;
	cfg_file << xs( "can_attack_in_vehicles " ) << options::aimbot::exploits::combat::can_attack_in_vehicles << std::endl;
	cfg_file << xs( "unlock_view_angles " ) << options::aimbot::exploits::combat::unlock_view_angles << std::endl;
	cfg_file << xs( "big_bullets " ) << options::aimbot::exploits::combat::big_bullets << std::endl;
	cfg_file << xs( "quick_bullets " ) << options::aimbot::exploits::combat::quick_bullets << std::endl;

	cfg_file << xs( "pierce " ) << options::aimbot::exploits::combat::pierce << std::endl;
	cfg_file << xs( "spoof_hit_distance " ) << options::aimbot::exploits::combat::spoof_hit_distance << std::endl;
	cfg_file << xs( "no_shot_gun_spread " ) << options::aimbot::exploits::combat::no_shot_gun_spread << std::endl;
	cfg_file << xs( "head_teleportation " ) << options::aimbot::exploits::combat::head_teleportation << std::endl;

	cfg_file << xs( "reduce_recoil " ) << options::aimbot::exploits::combat::reduce_recoil << std::endl;
	cfg_file << xs( "reduce_spread " ) << options::aimbot::exploits::combat::reduce_spread << std::endl;
	cfg_file << xs( "bullet_distance " ) << options::aimbot::exploits::combat::bullet_distance << std::endl;
	cfg_file << xs( "eoka_chance " ) << options::aimbot::exploits::combat::eoka_chance << std::endl;
	cfg_file << xs( "attack_radius " ) << options::aimbot::exploits::combat::attack_radius << std::endl;
	cfg_file << xs( "bullet_size " ) << options::aimbot::exploits::combat::bullet_size << std::endl;
	cfg_file << xs( "teleport_key " ) << options::aimbot::exploits::combat::teleport_key << std::endl;
	cfg_file << xs( "bullet_speed " ) << options::aimbot::exploits::combat::bullet_speed << std::endl;

	cfg_file << xs( "show_diesel_fuel " ) << options::visuals::world::show_diesel_fuel << std::endl;

	cfg_file << xs( "fast_loot " ) << options::aimbot::exploits::time::fast_loot << std::endl;
	cfg_file << xs( "fast_heal " ) << options::aimbot::exploits::time::fast_heal << std::endl;
	cfg_file << xs( "fast_switch " ) << options::aimbot::exploits::time::fast_switch << std::endl;
	cfg_file << xs( "time_modifier " ) << options::aimbot::exploits::time::time_modifier << std::endl;
	cfg_file << xs( "rapid_fire " ) << options::aimbot::exploits::time::rapid_fire << std::endl;
	cfg_file << xs( "fake_lag " ) << options::aimbot::exploits::time::fake_lag << std::endl;
	cfg_file << xs( "instant_charge_compound " ) << options::aimbot::exploits::time::instant_charge_compound << std::endl;
	cfg_file << xs( "fake_lag_on " ) << options::aimbot::exploits::time::fake_lag_on << std::endl;
	cfg_file << xs( "fake_lag_amount " ) << options::aimbot::exploits::time::fake_lag_amount << std::endl;


	cfg_file << xs( "revive_key " ) << options::aimbot::exploits::time::revive_key << std::endl;
	cfg_file << xs( "fake_lag_key " ) << options::aimbot::exploits::time::fake_lag_key << std::endl;
	cfg_file << xs( "instant_revive " ) << options::aimbot::exploits::time::instant_revive << std::endl;
	cfg_file << xs( "fast_bow " ) << options::aimbot::exploits::time::fast_bow << std::endl;
	cfg_file << xs( "always_revive_target " ) << options::aimbot::exploits::time::always_revive_target << std::endl;
	cfg_file << xs( "rapid_fire_speed " ) << options::aimbot::exploits::time::rapid_fire_speed << std::endl;
	cfg_file << xs( "time_speed " ) << options::aimbot::exploits::time::time_speed << std::endl;

	cfg_file << xs( "keep_wounded_alive " ) << options::aimbot::exploits::misc::keep_wounded_alive << std::endl;
	cfg_file << xs( "always_hit_weak_spot " ) << options::aimbot::exploits::misc::always_hit_weak_spot << std::endl;
	cfg_file << xs( "long_neck " ) << options::aimbot::exploits::misc::long_neck << std::endl;
	cfg_file << xs( "long_neck_right " ) << options::aimbot::exploits::misc::long_neck_right << std::endl;
	cfg_file << xs( "long_neck_left " ) << options::aimbot::exploits::misc::long_neck_left << std::endl;
	cfg_file << xs( "disable_land_damage " ) << options::aimbot::exploits::misc::disable_land_damage << std::endl;
	cfg_file << xs( "fov_changer " ) << options::aimbot::exploits::misc::fov_changer << std::endl;
	cfg_file << xs( "zoom_fov " ) << options::aimbot::exploits::misc::zoom_fov << std::endl;

	cfg_file << xs( "radar_position[0] " ) << g_esp.radar_position.x << std::endl;
	cfg_file << xs( "radar_position[1] " ) << g_esp.radar_position.y << std::endl;

	cfg_file << xs( "hotbar_position[0] " ) << g_esp.hotbar_position.x << std::endl;
	cfg_file << xs( "hotbar_position[1] " ) << g_esp.hotbar_position.y << std::endl;

	cfg_file << xs( "clothes_position[0] " ) << g_esp.clothes_position.x << std::endl;
	cfg_file << xs( "clothes_position[1] " ) << g_esp.clothes_position.y << std::endl;

	cfg_file << xs( "suicide " ) << options::aimbot::exploits::misc::suicide << std::endl;
	cfg_file << xs( "fake_fire " ) << options::aimbot::exploits::misc::fake_fire << std::endl;
	cfg_file << xs( "fake_admin " ) << options::aimbot::exploits::misc::fake_admin << std::endl;
	cfg_file << xs( "fake_fire_on " ) << options::aimbot::exploits::misc::fake_fire_on << std::endl;
	cfg_file << xs( "debug_camera " ) << options::aimbot::exploits::misc::debug_camera << std::endl;
	cfg_file << xs( "spin_bot " ) << options::aimbot::exploits::misc::spin_bot << std::endl;
	cfg_file << xs( "gesture_spam " ) << options::aimbot::exploits::misc::gesture_spam << std::endl;
	cfg_file << xs( "interactive_debug " ) << options::aimbot::exploits::misc::interactive_debug << std::endl;
	cfg_file << xs( "disarm_landmines " ) << options::aimbot::exploits::misc::disarm_landmines << std::endl;
	cfg_file << xs( "stop_recycler " ) << options::aimbot::exploits::misc::stop_recycler << std::endl;
	cfg_file << xs( "long_neck_height " ) << options::aimbot::exploits::misc::long_neck_height << std::endl;
	cfg_file << xs( "long_neck_right_amount " ) << options::aimbot::exploits::misc::long_neck_right_amount << std::endl;
	cfg_file << xs( "delay_fake_fire " ) << options::aimbot::exploits::misc::delay_fake_fire << std::endl;
	cfg_file << xs( "long_neck_left_amount " ) << options::aimbot::exploits::misc::long_neck_left_amount << std::endl;
	cfg_file << xs( "zoom_fov_amount " ) << options::aimbot::exploits::misc::zoom_fov_amount << std::endl;
	cfg_file << xs( "no_flash " ) << options::aimbot::exploits::misc::no_flash << std::endl;
	
	cfg_file << xs( "fov_amount " ) << options::aimbot::exploits::misc::fov_amount << std::endl;
	cfg_file << xs( "view_left " ) << options::aimbot::exploits::misc::view_left << std::endl;
	cfg_file << xs( "view_right " ) << options::aimbot::exploits::misc::view_right << std::endl;
	cfg_file << xs( "view_height " ) << options::aimbot::exploits::misc::view_height << std::endl;
	cfg_file << xs( "zoom_key " ) << options::aimbot::exploits::misc::zoom_key << std::endl;
	cfg_file << xs( "fake_fire_key " ) << options::aimbot::exploits::misc::fake_fire_key << std::endl;
	cfg_file << xs( "gesture_type " ) << options::aimbot::exploits::misc::gesture_type << std::endl;
	cfg_file << xs( "debug_camera_key " ) << options::aimbot::exploits::misc::debug_camera_key << std::endl;
	cfg_file << xs( "suicide_key " ) << options::aimbot::exploits::misc::suicide_key << std::endl;
	cfg_file << xs( "gesture_type " ) << options::aimbot::exploits::misc::gesture_type << std::endl;

	cfg_file << xs( "auto_untie_crates " ) << options::aimbot::exploits::misc::auto_untie_crates << std::endl;

	cfg_file << xs( "master_switch ") << options::visuals::world::master_switch << std::endl;

	cfg_file << xs( "draw_visuals " ) << options::visuals::draw_visuals << std::endl;
	cfg_file << xs( "indicators " ) << options::visuals::indicators << std::endl;
	cfg_file << xs( "fly_hack_indicator " ) << options::visuals::fly_hack_indicator << std::endl;
	cfg_file << xs( "draw_tracers " ) << options::visuals::draw_tracers << std::endl;
	cfg_file << xs( "offscreen_arrows " ) << options::visuals::offscreen_arrows << std::endl;
	cfg_file << xs( "draw_radar " ) << options::visuals::draw_radar << std::endl;
	cfg_file << xs( "show_name " ) << options::visuals::show_name << std::endl;
	cfg_file << xs( "show_weapon " ) << options::visuals::show_weapon << std::endl;
	cfg_file << xs( "show_health " ) << options::visuals::show_health << std::endl;
	cfg_file << xs( "show_health_text " ) << options::visuals::show_health_text << std::endl;
	cfg_file << xs( "show_distance " ) << options::visuals::show_distance << std::endl;
	cfg_file << xs( "show_hotbar " ) << options::visuals::show_hotbar << std::endl;
	cfg_file << xs( "show_clothes " ) << options::visuals::show_clothes << std::endl;
	cfg_file << xs( "show_lines " ) << options::visuals::show_lines << std::endl;
	cfg_file << xs( "show_view_direction " ) << options::visuals::show_view_direction << std::endl;
	cfg_file << xs( "can_show_sleepers " ) << options::visuals::can_show_sleepers << std::endl;
	cfg_file << xs( "can_show_knocked " ) << options::visuals::can_show_knocked << std::endl;
	cfg_file << xs( "can_show_npc " ) << options::visuals::can_show_npc << std::endl;
	cfg_file << xs( "chams " ) << options::visuals::chams << std::endl;
	cfg_file << xs( "rgb_chams " ) << options::visuals::rgb_chams << std::endl;
	cfg_file << xs( "draw_bones " ) << options::visuals::draw_bones << std::endl;
	cfg_file << xs( "show_watermark " ) << options::visuals::show_watermark << std::endl;
	cfg_file << xs( "local_trails " ) << options::visuals::local_trails << std::endl;
	cfg_file << xs( "show_last_sent_tick " ) << options::visuals::show_last_sent_tick << std::endl;
	cfg_file << xs( "show_desync_bar " ) << options::visuals::show_desync_bar << std::endl;
	cfg_file << xs( "show_reload_bar " ) << options::visuals::show_reload_bar << std::endl;
	cfg_file << xs( "can_show_sleepers_oof " ) << options::visuals::can_show_sleepers_oof << std::endl;
	cfg_file << xs( "can_show_knocked_oof " ) << options::visuals::can_show_knocked_oof << std::endl;
	cfg_file << xs( "can_show_npc_oof " ) << options::visuals::can_show_npc_oof << std::endl;
	cfg_file << xs( "max_player_distance " ) << options::visuals::max_player_distance << std::endl;
	cfg_file << xs( "box_type " ) << options::visuals::box_type << std::endl;
	cfg_file << xs( "offscreen_distance " ) << options::visuals::offscreen_distance << std::endl;

	cfg_file << xs( "show_stashes " ) << options::visuals::world::show_stashes << std::endl;

	cfg_file << xs( "rainbow_accent " ) << options::rainbow_accent << std::endl;

	cfg_file << xs( "show_corpse " ) << options::visuals::world::show_corpse << std::endl;
	cfg_file << xs( "show_backpack " ) << options::visuals::world::show_backpack << std::endl;
	cfg_file << xs( "todsky " ) << options::visuals::world::todsky << std::endl;
	cfg_file << xs( "show_grenades " ) << options::visuals::world::show_grenades << std::endl;
	cfg_file << xs( "night_stars " ) << options::visuals::world::night_stars << std::endl;
	cfg_file << xs( "clear_underwater " ) << options::visuals::world::clear_underwater << std::endl;
	cfg_file << xs( "change_world_color " ) << options::visuals::world::change_world_color << std::endl;

	cfg_file << xs( "todsky " ) << options::visuals::world::todsky << std::endl;
	cfg_file << xs( "show_grenades " ) << options::visuals::world::show_grenades << std::endl;
	cfg_file << xs( "night_stars " ) << options::visuals::world::night_stars << std::endl;
	cfg_file << xs( "clear_underwater " ) << options::visuals::world::clear_underwater << std::endl;
	cfg_file << xs( "change_world_color " ) << options::visuals::world::change_world_color << std::endl;

	cfg_file << xs( "show_heal " ) << options::visuals::world::show_heal << std::endl;
	cfg_file << xs( "show_weapons " ) << options::visuals::world::show_weapons << std::endl;
	cfg_file << xs( "show_melee_weapons " ) << options::visuals::world::show_melee_weapons << std::endl;
	cfg_file << xs( "show_everything " ) << options::visuals::world::show_everything << std::endl;

	cfg_file << xs( "show_item_amount " ) << options::visuals::world::show_item_amount << std::endl;
	cfg_file << xs( "stars_size " ) << options::visuals::world::stars_size << std::endl;
	cfg_file << xs( "stars " ) << options::visuals::world::stars << std::endl;
	cfg_file << xs( "ambient " ) << options::visuals::world::ambient << std::endl;
	cfg_file << xs( "mie_changer " ) << options::visuals::world::mie_changer << std::endl;

	cfg_file << xs( "rayleigh_changer " ) << options::visuals::world::rayleigh_changer << std::endl;
	cfg_file << xs( "brightness_changer " ) << options::visuals::world::brightness_changer << std::endl;
	cfg_file << xs( "aspect_changer " ) << options::visuals::world::aspect_changer << std::endl;
	cfg_file << xs( "show_sulfur_ore " ) << options::visuals::world::show_sulfur_ore << std::endl;
	cfg_file << xs( "show_metal_ore " ) << options::visuals::world::show_metal_ore << std::endl;
	cfg_file << xs( "show_stone_ore " ) << options::visuals::world::show_stone_ore << std::endl;
	cfg_file << xs( "show_box_storages " ) << options::visuals::world::show_box_storages << std::endl;
	cfg_file << xs( "show_tool_cupboard " ) << options::visuals::world::show_tool_cupboard << std::endl;
	cfg_file << xs( "aspect_changer " ) << options::visuals::world::aspect_changer << std::endl;
	cfg_file << xs( "show_sulfur_ore " ) << options::visuals::world::show_sulfur_ore << std::endl;
	cfg_file << xs( "show_metal_ore " ) << options::visuals::world::show_metal_ore << std::endl;
	cfg_file << xs( "show_stone_ore " ) << options::visuals::world::show_stone_ore << std::endl;
	cfg_file << xs( "show_vending_machine " ) << options::visuals::world::show_vending_machine << std::endl;
	cfg_file << xs( "show_drone " ) << options::visuals::world::show_drone << std::endl;
	cfg_file << xs( "show_recycler " ) << options::visuals::world::show_recycler << std::endl;
	cfg_file << xs( "show_tool_cupboard " ) << options::visuals::world::show_tool_cupboard << std::endl;
	cfg_file << xs( "show_oil_barrel " ) << options::visuals::world::show_oil_barrel << std::endl;
	cfg_file << xs( "show_regular_barrels " ) << options::visuals::world::show_regular_barrels << std::endl;
	cfg_file << xs( "show_underwater_crate " ) << options::visuals::world::show_underwater_crate << std::endl;
	cfg_file << xs( "show_elite_crate " ) << options::visuals::world::show_elite_crate << std::endl;
	cfg_file << xs( "show_military_crate " ) << options::visuals::world::show_military_crate << std::endl;
	cfg_file << xs( "show_bradley_crate " ) << options::visuals::world::show_bradley_crate << std::endl;

	cfg_file << xs( "show_helicopter_crate " ) << options::visuals::world::show_helicopter_crate << std::endl;
	cfg_file << xs( "show_hackable_locked_crate " ) << options::visuals::world::show_hackable_locked_crate << std::endl;
	cfg_file << xs( "show_normal_crate " ) << options::visuals::world::show_normal_crate << std::endl;
	cfg_file << xs( "show_chickens " ) << options::visuals::world::show_chickens << std::endl;
	cfg_file << xs( "show_small_crate " ) << options::visuals::world::show_small_crate << std::endl;
	cfg_file << xs( "show_mine_crate " ) << options::visuals::world::show_mine_crate << std::endl;
	cfg_file << xs( "show_tool_box " ) << options::visuals::world::show_tool_box << std::endl;
	cfg_file << xs( "show_tool_cupboard " ) << options::visuals::world::show_tool_cupboard << std::endl;
	cfg_file << xs( "show_boars " ) << options::visuals::world::show_boars << std::endl;
	cfg_file << xs( "show_wolves " ) << options::visuals::world::show_wolves << std::endl;
	cfg_file << xs( "show_horses " ) << options::visuals::world::show_horses << std::endl;

	cfg_file << xs( "show_sharks " ) << options::visuals::world::show_sharks << std::endl;
	cfg_file << xs( "show_deers " ) << options::visuals::world::show_deers << std::endl;
	cfg_file << xs( "show_polar_bears " ) << options::visuals::world::show_polar_bears << std::endl;

	cfg_file << xs( "show_bears " ) << options::visuals::world::show_bears << std::endl;
	cfg_file << xs( "show_sulfur_collectibles " ) << options::visuals::world::show_sulfur_collectibles << std::endl;
	cfg_file << xs( "show_metal_collectibles " ) << options::visuals::world::show_metal_collectibles << std::endl;
	cfg_file << xs( "show_wood_collectibles " ) << options::visuals::world::show_wood_collectibles << std::endl;
	cfg_file << xs( "show_stone_collectibles " ) << options::visuals::world::show_military_crate << std::endl;

	cfg_file << xs( "show_supply_signals " ) << options::visuals::world::show_supply_signals << std::endl;
	cfg_file << xs( "show_supply_drops " ) << options::visuals::world::show_supply_drops << std::endl;
	cfg_file << xs( "show_ammo_nails_arrows " ) << options::visuals::world::show_ammo_nails_arrows << std::endl;

	cfg_file << xs( "show_food_crate " ) << options::visuals::world::show_food_crate << std::endl;
	cfg_file << xs( "show_medical_crate " ) << options::visuals::world::show_medical_crate << std::endl;

	cfg_file << xs( "show_duo_submarine " ) << options::visuals::world::show_duo_submarine << std::endl;
	cfg_file << xs( "show_solo_submarine " ) << options::visuals::world::show_solo_submarine << std::endl;
	cfg_file << xs( "show_small_motorboat " ) << options::visuals::world::show_small_motorboat << std::endl;

	cfg_file << xs( "show_kayak " ) << options::visuals::world::show_kayak << std::endl;

	cfg_file << xs( "show_bradley_apc " ) << options::visuals::world::show_bradley_apc << std::endl;
	cfg_file << xs( "show_rhib " ) << options::visuals::world::show_rhib << std::endl;
	cfg_file << xs( "show_scrap_helicopter " ) << options::visuals::world::show_scrap_helicopter << std::endl;
	cfg_file << xs( "show_minicopter " ) << options::visuals::world::show_minicopter << std::endl;
	cfg_file << xs( "show_two_modules_car " ) << options::visuals::world::show_two_modules_car << std::endl;
	cfg_file << xs( "show_modular_car " ) << options::visuals::world::show_modular_car << std::endl;

	cfg_file << xs( "show_potatos " ) << options::visuals::world::show_potatos << std::endl;
	cfg_file << xs( "show_corns " ) << options::visuals::world::show_corns << std::endl;
	cfg_file << xs( "show_berrys " ) << options::visuals::world::show_berrys << std::endl;
	cfg_file << xs( "show_pumpkin " ) << options::visuals::world::show_pumpkin << std::endl;
	cfg_file << xs( "show_mushroom " ) << options::visuals::world::show_mushroom << std::endl;
	cfg_file << xs( "show_hemp " ) << options::visuals::world::show_hemp << std::endl;

	cfg_file << xs( "show_potatos " ) << options::visuals::world::show_potatos << std::endl;
	cfg_file << xs( "show_corns " ) << options::visuals::world::show_corns << std::endl;
	cfg_file << xs( "show_berrys " ) << options::visuals::world::show_berrys << std::endl;
	cfg_file << xs( "show_pumpkin " ) << options::visuals::world::show_pumpkin << std::endl;
	cfg_file << xs( "show_mushroom " ) << options::visuals::world::show_mushroom << std::endl;
	cfg_file << xs( "show_hemp " ) << options::visuals::world::show_hemp << std::endl;

	cfg_file << xs( "show_potatos " ) << options::visuals::world::show_potatos << std::endl;
	cfg_file << xs( "show_corns " ) << options::visuals::world::show_corns << std::endl;
	cfg_file << xs( "show_berrys " ) << options::visuals::world::show_berrys << std::endl;
	cfg_file << xs( "show_pumpkin " ) << options::visuals::world::show_pumpkin << std::endl;
	cfg_file << xs( "show_mushroom " ) << options::visuals::world::show_mushroom << std::endl;
	cfg_file << xs( "show_hemp " ) << options::visuals::world::show_hemp << std::endl;

	cfg_file << xs( "show_landmines " ) << options::visuals::world::show_landmines << std::endl;
	cfg_file << xs( "show_npc_turrets " ) << options::visuals::world::show_npc_turrets << std::endl;
	cfg_file << xs( "show_auto_turrets " ) << options::visuals::world::show_auto_turrets << std::endl;
	cfg_file << xs( "show_shotgun_traps " ) << options::visuals::world::show_shotgun_traps << std::endl;
	cfg_file << xs( "show_tesla_coil " ) << options::visuals::world::show_tesla_coil << std::endl;

	cfg_file << xs( "show_flame_turrets " ) << options::visuals::world::show_flame_turrets << std::endl;
	cfg_file << xs( "show_sam_site " ) << options::visuals::world::show_sam_site << std::endl;
	cfg_file << xs( "show_bear_trap " ) << options::visuals::world::show_bear_trap << std::endl;

	cfg_file << xs( "size_stars_amount " ) << options::visuals::world::size_stars_amount << std::endl;
	cfg_file << xs( "brightness_stars_amount " ) << options::visuals::world::brightness_stars_amount << std::endl;
	cfg_file << xs( "ambient_value " ) << options::visuals::world::ambient_value << std::endl;
	cfg_file << xs( "aspect_value " ) << options::visuals::world::aspect_value << std::endl;
	cfg_file << xs( "light_value " ) << options::visuals::world::light_value << std::endl;
	cfg_file << xs( "rayleigh_amount " ) << options::visuals::world::rayleigh_amount << std::endl;
	cfg_file << xs( "brightness_amount " ) << options::visuals::world::brightness_amount << std::endl;
	cfg_file << xs( "mie_amount " ) << options::visuals::world::mie_amount << std::endl;

	// distance
	cfg_file << xs( "max_cars_distance " ) << options::visuals::world::max_cars_distance << std::endl;
	cfg_file << xs( "max_barrels_distance " ) << options::visuals::world::max_barrels_distance << std::endl;
	cfg_file << xs( "max_ores_distance " ) << options::visuals::world::max_ores_distance << std::endl;
	cfg_file << xs( "max_grenade_distance " ) << options::visuals::world::max_grenade_distance << std::endl;
	cfg_file << xs( "max_food_collectibles_distance " ) << options::visuals::world::max_food_collectibles_distance << std::endl;
	cfg_file << xs( "max_container_distance " ) << options::visuals::world::max_container_distance << std::endl;
	cfg_file << xs( "max_corpse_distance " ) << options::visuals::world::max_corpse_distance << std::endl;
	cfg_file << xs( "max_vehicle_distance " ) << options::visuals::world::max_vehicle_distance << std::endl;
	cfg_file << xs( "max_ore_collectibles_distance " ) << options::visuals::world::max_ore_collectibles_distance << std::endl;
	cfg_file << xs( "max_respawn_points_distance " ) << options::visuals::world::max_respawn_points_distance << std::endl;
	cfg_file << xs( "max_helicopter_distance " ) << options::visuals::world::max_helicopter_distance << std::endl;

	cfg_file << xs( "color_heal[0] " ) << options::visuals::world::color_heal.r << std::endl;
	cfg_file << xs( "color_heal[1] " ) << options::visuals::world::color_heal.g << std::endl;
	cfg_file << xs( "color_heal[2] " ) << options::visuals::world::color_heal.b << std::endl;

	cfg_file << xs( "color_weapons[0] " ) << options::visuals::world::color_weapons.r << std::endl;
	cfg_file << xs( "color_weapons[1] " ) << options::visuals::world::color_weapons.g << std::endl;
	cfg_file << xs( "color_weapons[2] " ) << options::visuals::world::color_weapons.b << std::endl;

	cfg_file << xs( "color_corpse[0] " ) << options::visuals::world::color_corpse.r << std::endl;
	cfg_file << xs( "color_corpse[1] " ) << options::visuals::world::color_corpse.g << std::endl;
	cfg_file << xs( "color_corpse[2] " ) << options::visuals::world::color_corpse.b << std::endl;

	cfg_file << xs( "color_backpack[0] " ) << options::visuals::world::color_backpack.r << std::endl;
	cfg_file << xs( "color_backpack[1] " ) << options::visuals::world::color_backpack.g << std::endl;
	cfg_file << xs( "color_backpack[2] " ) << options::visuals::world::color_backpack.b << std::endl;

	cfg_file << xs( "color_melee_weapons[0] " ) << options::visuals::world::color_melee_weapons.r << std::endl;
	cfg_file << xs( "color_melee_weapons[1] " ) << options::visuals::world::color_melee_weapons.g << std::endl;
	cfg_file << xs( "color_melee_weapons[2] " ) << options::visuals::world::color_melee_weapons.b << std::endl;

	cfg_file << xs( "color_everything[0] " ) << options::visuals::world::color_everything.r << std::endl;
	cfg_file << xs( "color_everything[1] " ) << options::visuals::world::color_everything.g << std::endl;
	cfg_file << xs( "color_everything[2] " ) << options::visuals::world::color_everything.b << std::endl;

	cfg_file << xs( "color_stashes[0] " ) << options::visuals::world::color_stashes.r << std::endl;
	cfg_file << xs( "color_stashes[1] " ) << options::visuals::world::color_stashes.g << std::endl;
	cfg_file << xs( "color_stashes[2] " ) << options::visuals::world::color_stashes.b << std::endl;
	
	cfg_file << xs( "color_animals[0] " ) << options::visuals::world::color_animals.r << std::endl;
	cfg_file << xs( "color_animals[1] " ) << options::visuals::world::color_animals.g << std::endl;
	cfg_file << xs( "color_animals[2] " ) << options::visuals::world::color_animals.b << std::endl;

	cfg_file << xs( "color_traps[0] " ) << options::visuals::world::color_traps.r << std::endl;
	cfg_file << xs( "color_traps[1] " ) << options::visuals::world::color_traps.g << std::endl;
	cfg_file << xs( "color_traps[2] " ) << options::visuals::world::color_traps.b << std::endl;

	cfg_file << xs( "color_storages[0] " ) << options::visuals::world::color_storages.r << std::endl;
	cfg_file << xs( "color_storages[1] " ) << options::visuals::world::color_storages.g << std::endl;
	cfg_file << xs( "color_storages[2] " ) << options::visuals::world::color_storages.b << std::endl;

	cfg_file << xs( "color_vehicles[0] " ) << options::visuals::world::color_vehicles.r << std::endl;
	cfg_file << xs( "color_vehicles[1] " ) << options::visuals::world::color_vehicles.g << std::endl;
	cfg_file << xs( "color_vehicles[2] " ) << options::visuals::world::color_vehicles.b << std::endl;

	cfg_file << xs( "color_raid[0] " ) << options::visuals::world::color_raid.r << std::endl;
	cfg_file << xs( "color_raid[1] " ) << options::visuals::world::color_raid.g << std::endl;
	cfg_file << xs( "color_raid[2] " ) << options::visuals::world::color_raid.b << std::endl;

	cfg_file << xs( "color_item[0] " ) << options::visuals::world::color_item.r << std::endl;
	cfg_file << xs( "color_item[1] " ) << options::visuals::world::color_item.g << std::endl;
	cfg_file << xs( "color_item[2] " ) << options::visuals::world::color_item.b << std::endl;

	cfg_file << xs( "color_respawn_points[0] " ) << options::visuals::world::color_respawn_points.r << std::endl;
	cfg_file << xs( "color_respawn_points[1] " ) << options::visuals::world::color_respawn_points.g << std::endl;
	cfg_file << xs( "color_respawn_points[2] " ) << options::visuals::world::color_respawn_points.b << std::endl;

	cfg_file << xs( "color_chickens[0] " ) << options::visuals::world::color_chickens.r << std::endl;
	cfg_file << xs( "color_chickens[1] " ) << options::visuals::world::color_chickens.g << std::endl;
	cfg_file << xs( "color_chickens[2] " ) << options::visuals::world::color_chickens.b << std::endl;

	cfg_file << xs( "color_helicopter[0] " ) << options::visuals::world::color_helicopter.r << std::endl;
	cfg_file << xs( "color_helicopter[1] " ) << options::visuals::world::color_helicopter.g << std::endl;
	cfg_file << xs( "color_helicopter[2] " ) << options::visuals::world::color_helicopter.b << std::endl;

	cfg_file << xs( "color_ores[0] " ) << options::visuals::world::color_ores.r << std::endl;
	cfg_file << xs( "color_ores[1] " ) << options::visuals::world::color_ores.g << std::endl;
	cfg_file << xs( "color_ores[2] " ) << options::visuals::world::color_ores.b << std::endl;

	cfg_file << xs( "color_sulfur_ore[0] " ) << options::visuals::world::color_sulfur_ore.r << std::endl;
	cfg_file << xs( "color_sulfur_ore[1] " ) << options::visuals::world::color_sulfur_ore.g << std::endl;
	cfg_file << xs( "color_sulfur_ore[2] " ) << options::visuals::world::color_sulfur_ore.b << std::endl;

	cfg_file << xs( "color_metal_ore[0] " ) << options::visuals::world::color_metal_ore.r << std::endl;
	cfg_file << xs( "color_metal_ore[1] " ) << options::visuals::world::color_metal_ore.g << std::endl;
	cfg_file << xs( "color_metal_ore[2] " ) << options::visuals::world::color_metal_ore.b << std::endl;

	cfg_file << xs( "color_stone_ore[0] " ) << options::visuals::world::color_stone_ore.r << std::endl;
	cfg_file << xs( "color_stone_ore[1] " ) << options::visuals::world::color_stone_ore.g << std::endl;
	cfg_file << xs( "color_stone_ore[2] " ) << options::visuals::world::color_stone_ore.b << std::endl;

	cfg_file << xs( "color_tool_cupboard[0] " ) << options::visuals::world::color_tool_cupboard.r << std::endl;
	cfg_file << xs( "color_tool_cupboard[1] " ) << options::visuals::world::color_tool_cupboard.g << std::endl;
	cfg_file << xs( "color_tool_cupboard[2] " ) << options::visuals::world::color_tool_cupboard.b << std::endl;

	cfg_file << xs( "color_box_storages[0] " ) << options::visuals::world::color_box_storages.r << std::endl;
	cfg_file << xs( "color_box_storages[1] " ) << options::visuals::world::color_box_storages.g << std::endl;
	cfg_file << xs( "color_box_storages[2] " ) << options::visuals::world::color_box_storages.b << std::endl;

	cfg_file << xs( "color_ammo_nails_arrows[0] " ) << options::visuals::world::color_ammo_nails_arrows.r << std::endl;
	cfg_file << xs( "color_ammo_nails_arrows[1] " ) << options::visuals::world::color_ammo_nails_arrows.g << std::endl;
	cfg_file << xs( "color_ammo_nails_arrows[2] " ) << options::visuals::world::color_ammo_nails_arrows.b << std::endl;

	cfg_file << xs( "color_supply_signals[0] " ) << options::visuals::world::color_supply_signals.r << std::endl;
	cfg_file << xs( "color_supply_signals[1] " ) << options::visuals::world::color_supply_signals.g << std::endl;
	cfg_file << xs( "color_supply_signals[2] " ) << options::visuals::world::color_supply_signals.b << std::endl;

	cfg_file << xs( "color_supply_drops[0] " ) << options::visuals::world::color_supply_drops.r << std::endl;
	cfg_file << xs( "color_supply_drops[1] " ) << options::visuals::world::color_supply_drops.g << std::endl;
	cfg_file << xs( "color_supply_drops[2] " ) << options::visuals::world::color_supply_drops.b << std::endl;

	cfg_file << xs( "color_hemp[0] " ) << options::visuals::world::color_hemp.r << std::endl;
	cfg_file << xs( "color_hemp[1] " ) << options::visuals::world::color_hemp.g << std::endl;
	cfg_file << xs( "color_hemp[2] " ) << options::visuals::world::color_hemp.b << std::endl;

	cfg_file << xs( "color_mushroom[0] " ) << options::visuals::world::color_mushroom.r << std::endl;
	cfg_file << xs( "color_mushroom[1] " ) << options::visuals::world::color_mushroom.g << std::endl;
	cfg_file << xs( "color_mushroom[2] " ) << options::visuals::world::color_mushroom.b << std::endl;

	cfg_file << xs( "color_pumpkin[0] " ) << options::visuals::world::color_pumpkin.r << std::endl;
	cfg_file << xs( "color_pumpkin[1] " ) << options::visuals::world::color_pumpkin.g << std::endl;
	cfg_file << xs( "color_pumpkin[2] " ) << options::visuals::world::color_pumpkin.b << std::endl;

	cfg_file << xs( "color_berrys[0] " ) << options::visuals::world::color_berrys.r << std::endl;
	cfg_file << xs( "color_berrys[1] " ) << options::visuals::world::color_berrys.g << std::endl;
	cfg_file << xs( "color_berrys[2] " ) << options::visuals::world::color_berrys.b << std::endl;

	cfg_file << xs( "color_corns[0] " ) << options::visuals::world::color_corns.r << std::endl;
	cfg_file << xs( "color_corns[1] " ) << options::visuals::world::color_corns.g << std::endl;
	cfg_file << xs( "color_corns[2] " ) << options::visuals::world::color_corns.b << std::endl;

	cfg_file << xs( "color_potatos[0] " ) << options::visuals::world::color_potatos.r << std::endl;
	cfg_file << xs( "color_potatos[1] " ) << options::visuals::world::color_potatos.g << std::endl;
	cfg_file << xs( "color_potatos[2] " ) << options::visuals::world::color_potatos.b << std::endl;

	cfg_file << xs( "color_modular_car[0] " ) << options::visuals::world::color_modular_car.r << std::endl;
	cfg_file << xs( "color_modular_car[1] " ) << options::visuals::world::color_modular_car.g << std::endl;
	cfg_file << xs( "color_modular_car[2] " ) << options::visuals::world::color_modular_car.b << std::endl;

	cfg_file << xs( "color_two_modules_car[0] " ) << options::visuals::world::color_two_modules_car.r << std::endl;
	cfg_file << xs( "color_two_modules_car[1] " ) << options::visuals::world::color_two_modules_car.g << std::endl;
	cfg_file << xs( "color_two_modules_car[2] " ) << options::visuals::world::color_two_modules_car.b << std::endl;

	cfg_file << xs( "color_minicopter[0] " ) << options::visuals::world::color_minicopter.r << std::endl;
	cfg_file << xs( "color_minicopter[1] " ) << options::visuals::world::color_minicopter.g << std::endl;
	cfg_file << xs( "color_minicopter[2] " ) << options::visuals::world::color_minicopter.b << std::endl;

	cfg_file << xs( "color_scrap_helicopter[0] " ) << options::visuals::world::color_scrap_helicopter.r << std::endl;
	cfg_file << xs( "color_scrap_helicopter[1] " ) << options::visuals::world::color_scrap_helicopter.g << std::endl;
	cfg_file << xs( "color_scrap_helicopter[2] " ) << options::visuals::world::color_scrap_helicopter.b << std::endl;

	cfg_file << xs( "color_rhib[0] " ) << options::visuals::world::color_rhib.r << std::endl;
	cfg_file << xs( "color_rhib[1] " ) << options::visuals::world::color_rhib.g << std::endl;
	cfg_file << xs( "color_rhib[2] " ) << options::visuals::world::color_rhib.b << std::endl;

	cfg_file << xs( "color_bradley_apc[0] " ) << options::visuals::world::color_bradley_apc.r << std::endl;
	cfg_file << xs( "color_bradley_apc[1] " ) << options::visuals::world::color_bradley_apc.g << std::endl;
	cfg_file << xs( "color_bradley_apc[2] " ) << options::visuals::world::color_bradley_apc.b << std::endl;

	cfg_file << xs( "color_kayak[0] " ) << options::visuals::world::color_kayak.r << std::endl;
	cfg_file << xs( "color_kayak[1] " ) << options::visuals::world::color_kayak.g << std::endl;
	cfg_file << xs( "color_kayak[2] " ) << options::visuals::world::color_kayak.b << std::endl;

	cfg_file << xs( "color_small_motorboat[0] " ) << options::visuals::world::color_small_motorboat.r << std::endl;
	cfg_file << xs( "color_small_motorboat[1] " ) << options::visuals::world::color_small_motorboat.g << std::endl;
	cfg_file << xs( "color_small_motorboat[2] " ) << options::visuals::world::color_small_motorboat.b << std::endl;

	cfg_file << xs( "color_solo_submarine[0] " ) << options::visuals::world::color_solo_submarine.r << std::endl;
	cfg_file << xs( "color_solo_submarine[1] " ) << options::visuals::world::color_solo_submarine.g << std::endl;
	cfg_file << xs( "color_solo_submarine[2] " ) << options::visuals::world::color_solo_submarine.b << std::endl;

	cfg_file << xs( "color_duo_submarine[0] " ) << options::visuals::world::color_duo_submarine.r << std::endl;
	cfg_file << xs( "color_duo_submarine[1] " ) << options::visuals::world::color_duo_submarine.g << std::endl;
	cfg_file << xs( "color_duo_submarine[2] " ) << options::visuals::world::color_duo_submarine.b << std::endl;

	cfg_file << xs( "color_landmines[0] " ) << options::visuals::world::color_landmines.r << std::endl;
	cfg_file << xs( "color_landmines[1] " ) << options::visuals::world::color_landmines.g << std::endl;
	cfg_file << xs( "color_landmines[2] " ) << options::visuals::world::color_landmines.b << std::endl;

	cfg_file << xs( "color_npc_turrets[0] " ) << options::visuals::world::color_npc_turrets.r << std::endl;
	cfg_file << xs( "color_npc_turrets[1] " ) << options::visuals::world::color_npc_turrets.g << std::endl;
	cfg_file << xs( "color_npc_turrets[2] " ) << options::visuals::world::color_npc_turrets.b << std::endl;

	cfg_file << xs( "color_auto_turrets[0] " ) << options::visuals::world::color_auto_turrets.r << std::endl;
	cfg_file << xs( "color_auto_turrets[1] " ) << options::visuals::world::color_auto_turrets.g << std::endl;
	cfg_file << xs( "color_auto_turrets[2] " ) << options::visuals::world::color_auto_turrets.b << std::endl;

	cfg_file << xs( "color_shotgun_traps[0] " ) << options::visuals::world::color_shotgun_traps.r << std::endl;
	cfg_file << xs( "color_shotgun_traps[1] " ) << options::visuals::world::color_shotgun_traps.g << std::endl;
	cfg_file << xs( "color_shotgun_traps[2] " ) << options::visuals::world::color_shotgun_traps.b << std::endl;

	cfg_file << xs( "color_tesla_coil[0] " ) << options::visuals::world::color_tesla_coil.r << std::endl;
	cfg_file << xs( "color_tesla_coil[1] " ) << options::visuals::world::color_tesla_coil.g << std::endl;
	cfg_file << xs( "color_tesla_coil[2] " ) << options::visuals::world::color_tesla_coil.b << std::endl;

	cfg_file << xs( "color_flame_turrets[0] " ) << options::visuals::world::color_flame_turrets.r << std::endl;
	cfg_file << xs( "color_flame_turrets[1] " ) << options::visuals::world::color_flame_turrets.g << std::endl;
	cfg_file << xs( "color_flame_turrets[2] " ) << options::visuals::world::color_flame_turrets.b << std::endl;

	cfg_file << xs( "color_sam_site[0] " ) << options::visuals::world::color_sam_site.r << std::endl;
	cfg_file << xs( "color_sam_site[1] " ) << options::visuals::world::color_sam_site.g << std::endl;
	cfg_file << xs( "color_sam_site[2] " ) << options::visuals::world::color_sam_site.b << std::endl;

	cfg_file << xs( "color_land_spikes[0] " ) << options::visuals::world::color_land_spikes.r << std::endl;
	cfg_file << xs( "color_land_spikes[1] " ) << options::visuals::world::color_land_spikes.g << std::endl;
	cfg_file << xs( "color_land_spikes[2] " ) << options::visuals::world::color_land_spikes.b << std::endl;

	cfg_file << xs( "color_bear_trap[0] " ) << options::visuals::world::color_bear_trap.r << std::endl;
	cfg_file << xs( "color_bear_trap[1] " ) << options::visuals::world::color_bear_trap.g << std::endl;
	cfg_file << xs( "color_bear_trap[2] " ) << options::visuals::world::color_bear_trap.b << std::endl;

	cfg_file << xs( "color_oil_barrel[0] " ) << options::visuals::world::color_oil_barrel.r << std::endl;
	cfg_file << xs( "color_oil_barrel[1] " ) << options::visuals::world::color_oil_barrel.g << std::endl;
	cfg_file << xs( "color_oil_barrel[2] " ) << options::visuals::world::color_oil_barrel.b << std::endl;

	cfg_file << xs( "color_regular_barrels[0] " ) << options::visuals::world::color_regular_barrels.r << std::endl;
	cfg_file << xs( "color_regular_barrels[1] " ) << options::visuals::world::color_regular_barrels.g << std::endl;
	cfg_file << xs( "color_regular_barrels[2] " ) << options::visuals::world::color_regular_barrels.b << std::endl;

	cfg_file << xs( "color_underwater_crate[0] " ) << options::visuals::world::color_underwater_crate.r << std::endl;
	cfg_file << xs( "color_underwater_crate[1] " ) << options::visuals::world::color_underwater_crate.g << std::endl;
	cfg_file << xs( "color_underwater_crate[2] " ) << options::visuals::world::color_underwater_crate.b << std::endl;

	cfg_file << xs( "color_elite_crate[0] " ) << options::visuals::world::color_elite_crate.r << std::endl;
	cfg_file << xs( "color_elite_crate[1] " ) << options::visuals::world::color_elite_crate.g << std::endl;
	cfg_file << xs( "color_elite_crate[2] " ) << options::visuals::world::color_elite_crate.b << std::endl;

	cfg_file << xs( "color_military_crate[0] " ) << options::visuals::world::color_military_crate.r << std::endl;
	cfg_file << xs( "color_military_crate[1] " ) << options::visuals::world::color_military_crate.g << std::endl;
	cfg_file << xs( "color_military_crate[2] " ) << options::visuals::world::color_military_crate.b << std::endl;
	
	cfg_file << xs( "color_bradley_crate[0] " ) << options::visuals::world::color_bradley_crate.r << std::endl;
	cfg_file << xs( "color_bradley_crate[1] " ) << options::visuals::world::color_bradley_crate.g << std::endl;
	cfg_file << xs( "color_bradley_crate[2] " ) << options::visuals::world::color_bradley_crate.b << std::endl;

	cfg_file << xs( "color_food_crate[0] " ) << options::visuals::world::color_food_crate.r << std::endl;
	cfg_file << xs( "color_food_crate[1] " ) << options::visuals::world::color_food_crate.g << std::endl;
	cfg_file << xs( "color_food_crate[2] " ) << options::visuals::world::color_food_crate.b << std::endl;
	
	cfg_file << xs( "color_medical_crate[0] " ) << options::visuals::world::color_medical_crate.r << std::endl;
	cfg_file << xs( "color_medical_crate[1] " ) << options::visuals::world::color_medical_crate.g << std::endl;
	cfg_file << xs( "color_medical_crate[2] " ) << options::visuals::world::color_medical_crate.b << std::endl;

	cfg_file << xs( "color_diesel_fuel[0] " ) << options::visuals::world::color_diesel_fuel.r << std::endl;
	cfg_file << xs( "color_diesel_fuel[1] " ) << options::visuals::world::color_diesel_fuel.g << std::endl;
	cfg_file << xs( "color_diesel_fuel[2] " ) << options::visuals::world::color_diesel_fuel.b << std::endl;

	cfg_file << xs( "color_helicopter_crate[0] " ) << options::visuals::world::color_helicopter_crate.r << std::endl;
	cfg_file << xs( "color_helicopter_crate[1] " ) << options::visuals::world::color_helicopter_crate.g << std::endl;
	cfg_file << xs( "color_helicopter_crate[2] " ) << options::visuals::world::color_helicopter_crate.b << std::endl;

	cfg_file << xs( "color_hackable_locked_crate[0] " ) << options::visuals::world::color_hackable_locked_crate.r << std::endl;
	cfg_file << xs( "color_hackable_locked_crate[1] " ) << options::visuals::world::color_hackable_locked_crate.g << std::endl;
	cfg_file << xs( "color_hackable_locked_crate[2] " ) << options::visuals::world::color_hackable_locked_crate.b << std::endl;

	cfg_file << xs( "color_normal_crate[0] " ) << options::visuals::world::color_normal_crate.r << std::endl;
	cfg_file << xs( "color_normal_crate[1] " ) << options::visuals::world::color_normal_crate.g << std::endl;
	cfg_file << xs( "color_normal_crate[2] " ) << options::visuals::world::color_normal_crate.b << std::endl;

	cfg_file << xs( "color_small_crate[0] " ) << options::visuals::world::color_small_crate.r << std::endl;
	cfg_file << xs( "color_small_crate[1] " ) << options::visuals::world::color_small_crate.g << std::endl;
	cfg_file << xs( "color_small_crate[2] " ) << options::visuals::world::color_small_crate.b << std::endl;

	cfg_file << xs( "color_mine_crate[0] " ) << options::visuals::world::color_mine_crate.r << std::endl;
	cfg_file << xs( "color_mine_crate[1] " ) << options::visuals::world::color_mine_crate.g << std::endl;
	cfg_file << xs( "color_mine_crate[2] " ) << options::visuals::world::color_mine_crate.b << std::endl;

	cfg_file << xs( "color_tool_box[0] " ) << options::visuals::world::color_tool_box.r << std::endl;
	cfg_file << xs( "color_tool_box[1] " ) << options::visuals::world::color_tool_box.g << std::endl;
	cfg_file << xs( "color_tool_box[2] " ) << options::visuals::world::color_tool_box.b << std::endl;

	cfg_file << xs( "color_boars[0] " ) << options::visuals::world::color_boars.r << std::endl;
	cfg_file << xs( "color_boars[1] " ) << options::visuals::world::color_boars.g << std::endl;
	cfg_file << xs( "color_boars[2] " ) << options::visuals::world::color_boars.b << std::endl;

	cfg_file << xs( "color_wolves[0] " ) << options::visuals::world::color_wolves.r << std::endl;
	cfg_file << xs( "color_wolves[1] " ) << options::visuals::world::color_wolves.g << std::endl;
	cfg_file << xs( "color_wolves[2] " ) << options::visuals::world::color_wolves.b << std::endl;

	cfg_file << xs( "color_horses[0] " ) << options::visuals::world::color_horses.r << std::endl;
	cfg_file << xs( "color_horses[1] " ) << options::visuals::world::color_horses.g << std::endl;
	cfg_file << xs( "color_horses[2] " ) << options::visuals::world::color_horses.b << std::endl;

	cfg_file << xs( "color_sharks[0] " ) << options::visuals::world::color_sharks.r << std::endl;
	cfg_file << xs( "color_sharks[1] " ) << options::visuals::world::color_sharks.g << std::endl;
	cfg_file << xs( "color_sharks[2] " ) << options::visuals::world::color_sharks.b << std::endl;

	cfg_file << xs( "color_deers[0] " ) << options::visuals::world::color_deers.r << std::endl;
	cfg_file << xs( "color_deers[1] " ) << options::visuals::world::color_deers.g << std::endl;
	cfg_file << xs( "color_deers[2] " ) << options::visuals::world::color_deers.b << std::endl;

	cfg_file << xs( "color_polar_bears[0] " ) << options::visuals::world::color_polar_bears.r << std::endl;
	cfg_file << xs( "color_polar_bears[1] " ) << options::visuals::world::color_polar_bears.g << std::endl;
	cfg_file << xs( "color_polar_bears[2] " ) << options::visuals::world::color_polar_bears.b << std::endl;

	cfg_file << xs( "color_bears[0] " ) << options::visuals::world::color_bears.r << std::endl;
	cfg_file << xs( "color_bears[1] " ) << options::visuals::world::color_bears.g << std::endl;
	cfg_file << xs( "color_bears[2] " ) << options::visuals::world::color_bears.b << std::endl;

	cfg_file << xs( "color_sulfur_collectibles[0] " ) << options::visuals::world::color_sulfur_collectibles.r << std::endl;
	cfg_file << xs( "color_sulfur_collectibles[1] " ) << options::visuals::world::color_sulfur_collectibles.g << std::endl;
	cfg_file << xs( "color_sulfur_collectibles[2] " ) << options::visuals::world::color_sulfur_collectibles.b << std::endl;

	cfg_file << xs( "color_drone[0]" ) << options::visuals::world::color_drone.r << std::endl;
	cfg_file << xs( "color_drone[1]" ) << options::visuals::world::color_drone.g << std::endl;
	cfg_file << xs( "color_drone[2]" ) << options::visuals::world::color_drone.b << std::endl;

	cfg_file << xs( "color_recycler[0]" ) << options::visuals::world::color_recycler.r << std::endl;
	cfg_file << xs( "color_recycler[1]" ) << options::visuals::world::color_recycler.g << std::endl;
	cfg_file << xs( "color_recycler[2]" ) << options::visuals::world::color_recycler.b << std::endl;

	cfg_file << xs( "color_metal_collectibles[0]" ) << options::visuals::world::color_metal_collectibles.r << std::endl;
	cfg_file << xs( "color_metal_collectibles[1]" ) << options::visuals::world::color_metal_collectibles.g << std::endl;
	cfg_file << xs( "color_metal_collectibles[2]" ) << options::visuals::world::color_metal_collectibles.b << std::endl;

	cfg_file << xs( "color_wood_collectibles[0]" ) << options::visuals::world::color_wood_collectibles.r << std::endl;
	cfg_file << xs( "color_wood_collectibles[1]" ) << options::visuals::world::color_wood_collectibles.g << std::endl;
	cfg_file << xs( "color_wood_collectibles[2]" ) << options::visuals::world::color_wood_collectibles.b << std::endl;

	cfg_file << xs( "color_stone_collectibles[0]" ) << options::visuals::world::color_stone_collectibles.r << std::endl;
	cfg_file << xs( "color_stone_collectibles[1]" ) << options::visuals::world::color_stone_collectibles.g << std::endl;
	cfg_file << xs( "color_stone_collectibles[2]" ) << options::visuals::world::color_stone_collectibles.b << std::endl;

	cfg_file << xs( "color_vending_machine[0]" ) << options::visuals::world::color_vending_machine.r << std::endl;
	cfg_file << xs( "color_vending_machine[1]" ) << options::visuals::world::color_vending_machine.g << std::endl;
	cfg_file << xs( "color_vending_machine[2]" ) << options::visuals::world::color_vending_machine.b << std::endl;

	cfg_file << xs( "chams_color[0] " ) << options::visuals::chams_color.r << std::endl;
	cfg_file << xs( "chams_color[1] " ) << options::visuals::chams_color.g << std::endl;
	cfg_file << xs( "chams_color[2] " ) << options::visuals::chams_color.b << std::endl;

	cfg_file << xs( "font_flags " ) << options::font_flags << std::endl;

	cfg_file << xs( "health_thickness " ) << options::visuals::health_thickness << std::endl;

	cfg_file << xs( "chams_visible[0] " ) << options::visuals::chams_visible.r << std::endl;
	cfg_file << xs( "chams_visible[1] " ) << options::visuals::chams_visible.g << std::endl;
	cfg_file << xs( "chams_visible[2] " ) << options::visuals::chams_visible.b << std::endl;

	cfg_file << xs( "target_line_color[0] " ) << options::aimbot::target_line_color.r << std::endl;
	cfg_file << xs( "target_line_color[1] " ) << options::aimbot::target_line_color.g << std::endl;
	cfg_file << xs( "target_line_color[2] " ) << options::aimbot::target_line_color.b << std::endl;

	cfg_file << xs( "fov_circle_color[0] " ) << options::aimbot::fov_circle_color.r << std::endl;
	cfg_file << xs( "fov_circle_color[1] " ) << options::aimbot::fov_circle_color.g << std::endl;
	cfg_file << xs( "fov_circle_color[2] " ) << options::aimbot::fov_circle_color.b << std::endl;

	cfg_file << xs( "npc_vis_name_color[0] " ) << options::visuals::npc_vis_name_color.r << std::endl;
	cfg_file << xs( "npc_vis_name_color[1] " ) << options::visuals::npc_vis_name_color.g << std::endl;
	cfg_file << xs( "npc_vis_name_color[2] " ) << options::visuals::npc_vis_name_color.b << std::endl;

	cfg_file << xs( "npc_vis_skeleton_color[0] " ) << options::visuals::npc_vis_skeleton_color.r << std::endl;
	cfg_file << xs( "npc_vis_skeleton_color[1] " ) << options::visuals::npc_vis_skeleton_color.g << std::endl;
	cfg_file << xs( "npc_vis_skeleton_color[2] " ) << options::visuals::npc_vis_skeleton_color.b << std::endl;

	cfg_file << xs( "npc_vis_box_color[0] " ) << options::visuals::npc_vis_box_color.r << std::endl;
	cfg_file << xs( "npc_vis_box_color[1] " ) << options::visuals::npc_vis_box_color.g << std::endl;
	cfg_file << xs( "npc_vis_box_color[2] " ) << options::visuals::npc_vis_box_color.b << std::endl;

	cfg_file << xs( "npc_vis_radar_color[0] " ) << options::visuals::npc_vis_radar_color.r << std::endl;
	cfg_file << xs( "npc_vis_radar_color[1] " ) << options::visuals::npc_vis_radar_color.g << std::endl;
	cfg_file << xs( "npc_vis_radar_color[2] " ) << options::visuals::npc_vis_radar_color.b << std::endl;

	cfg_file << xs( "npc_vis_oof_color[0] " ) << options::visuals::npc_vis_oof_color.r << std::endl;
	cfg_file << xs( "npc_vis_oof_color[1] " ) << options::visuals::npc_vis_oof_color.g << std::endl;
	cfg_file << xs( "npc_vis_oof_color[2] " ) << options::visuals::npc_vis_oof_color.b << std::endl;

	cfg_file << xs( "npc_vis_ducking_color[0] " ) << options::visuals::npc_vis_ducking_color.r << std::endl;
	cfg_file << xs( "npc_vis_ducking_color[1] " ) << options::visuals::npc_vis_ducking_color.g << std::endl;
	cfg_file << xs( "npc_vis_ducking_color[2] " ) << options::visuals::npc_vis_ducking_color.b << std::endl;

	cfg_file << xs( "npc_vis_knocked_color[0] " ) << options::visuals::npc_vis_knocked_color.r << std::endl;
	cfg_file << xs( "npc_vis_knocked_color[1] " ) << options::visuals::npc_vis_knocked_color.g << std::endl;
	cfg_file << xs( "npc_vis_knocked_color[2] " ) << options::visuals::npc_vis_knocked_color.b << std::endl;

	cfg_file << xs( "npc_vis_snap_lines_color[0] " ) << options::visuals::npc_vis_snap_lines_color.r << std::endl;
	cfg_file << xs( "npc_vis_snap_lines_color[1] " ) << options::visuals::npc_vis_snap_lines_color.g << std::endl;
	cfg_file << xs( "npc_vis_snap_lines_color[2] " ) << options::visuals::npc_vis_snap_lines_color.b << std::endl;

	cfg_file << xs( "npc_vis_view_direction_color[0] " ) << options::visuals::npc_vis_view_direction_color.r << std::endl;
	cfg_file << xs( "npc_vis_view_direction_color[1] " ) << options::visuals::npc_vis_view_direction_color.g << std::endl;
	cfg_file << xs( "npc_vis_view_direction_color[2] " ) << options::visuals::npc_vis_view_direction_color.b << std::endl;

	cfg_file << xs( "npc_name_color[0] " ) << options::visuals::npc_name_color.r << std::endl;
	cfg_file << xs( "npc_name_color[1] " ) << options::visuals::npc_name_color.g << std::endl;
	cfg_file << xs( "npc_name_color[2] " ) << options::visuals::npc_name_color.b << std::endl;

	cfg_file << xs( "npc_skeleton_color[0] " ) << options::visuals::npc_skeleton_color.r << std::endl;
	cfg_file << xs( "npc_skeleton_color[1] " ) << options::visuals::npc_skeleton_color.g << std::endl;
	cfg_file << xs( "npc_skeleton_color[2] " ) << options::visuals::npc_skeleton_color.b << std::endl;

	cfg_file << xs( "npc_box_color[0] " ) << options::visuals::npc_box_color.r << std::endl;
	cfg_file << xs( "npc_box_color[1] " ) << options::visuals::npc_box_color.g << std::endl;
	cfg_file << xs( "npc_box_color[2] " ) << options::visuals::npc_box_color.b << std::endl;

	cfg_file << xs( "npc_radar_color[0] " ) << options::visuals::npc_radar_color.r << std::endl;
	cfg_file << xs( "npc_radar_color[1] " ) << options::visuals::npc_radar_color.g << std::endl;
	cfg_file << xs( "npc_radar_color[2] " ) << options::visuals::npc_radar_color.b << std::endl;

	cfg_file << xs( "npc_oof_color[0] " ) << options::visuals::npc_oof_color.r << std::endl;
	cfg_file << xs( "npc_oof_color[1] " ) << options::visuals::npc_oof_color.g << std::endl;
	cfg_file << xs( "npc_oof_color[2] " ) << options::visuals::npc_oof_color.b << std::endl;

	cfg_file << xs( "npc_ducking_color[0] " ) << options::visuals::npc_ducking_color.r << std::endl;
	cfg_file << xs( "npc_ducking_color[1] " ) << options::visuals::npc_ducking_color.g << std::endl;
	cfg_file << xs( "npc_ducking_color[2] " ) << options::visuals::npc_ducking_color.b << std::endl;

	cfg_file << xs( "npc_knocked_color[0] " ) << options::visuals::npc_knocked_color.r << std::endl;
	cfg_file << xs( "npc_knocked_color[1] " ) << options::visuals::npc_knocked_color.g << std::endl;
	cfg_file << xs( "npc_knocked_color[2] " ) << options::visuals::npc_knocked_color.b << std::endl;

	cfg_file << xs( "npc_snap_lines_color[0] " ) << options::visuals::npc_snap_lines_color.r << std::endl;
	cfg_file << xs( "npc_snap_lines_color[1] " ) << options::visuals::npc_snap_lines_color.g << std::endl;
	cfg_file << xs( "npc_snap_lines_color[2] " ) << options::visuals::npc_snap_lines_color.b << std::endl;

	cfg_file << xs( "npc_view_direction_color[0] " ) << options::visuals::npc_view_direction_color.r << std::endl;
	cfg_file << xs( "npc_view_direction_color[1] " ) << options::visuals::npc_view_direction_color.g << std::endl;
	cfg_file << xs( "npc_view_direction_color[2] " ) << options::visuals::npc_view_direction_color.b << std::endl;

	cfg_file << xs( "vis_name_color[0] " ) << options::visuals::vis_name_color.r << std::endl;
	cfg_file << xs( "vis_name_color[1] " ) << options::visuals::vis_name_color.g << std::endl;
	cfg_file << xs( "vis_name_color[2] " ) << options::visuals::vis_name_color.b << std::endl;

	cfg_file << xs( "vis_skeleton_color[0] " ) << options::visuals::vis_skeleton_color.r << std::endl;
	cfg_file << xs( "vis_skeleton_color[1] " ) << options::visuals::vis_skeleton_color.g << std::endl;
	cfg_file << xs( "vis_skeleton_color[2] " ) << options::visuals::vis_skeleton_color.b << std::endl;

	cfg_file << xs( "vis_box_color[0] " ) << options::visuals::vis_box_color.r << std::endl;
	cfg_file << xs( "vis_box_color[1] " ) << options::visuals::vis_box_color.g << std::endl;
	cfg_file << xs( "vis_box_color[2] " ) << options::visuals::vis_box_color.b << std::endl;

	cfg_file << xs( "vis_radar_color[0] " ) << options::visuals::vis_radar_color.r << std::endl;
	cfg_file << xs( "vis_radar_color[1] " ) << options::visuals::vis_radar_color.g << std::endl;
	cfg_file << xs( "vis_radar_color[2] " ) << options::visuals::vis_radar_color.b << std::endl;

	cfg_file << xs( "vis_oof_color[0] " ) << options::visuals::vis_oof_color.r << std::endl;
	cfg_file << xs( "vis_oof_color[1] " ) << options::visuals::vis_oof_color.g << std::endl;
	cfg_file << xs( "vis_oof_color[2] " ) << options::visuals::vis_oof_color.b << std::endl;

	cfg_file << xs( "vis_distance_color[0] " ) << options::visuals::vis_distance_color.r << std::endl;
	cfg_file << xs( "vis_distance_color[1] " ) << options::visuals::vis_distance_color.g << std::endl;
	cfg_file << xs( "vis_distance_color[2] " ) << options::visuals::vis_distance_color.b << std::endl;

	cfg_file << xs( "vis_weapon_color[0] " ) << options::visuals::vis_weapon_color.r << std::endl;
	cfg_file << xs( "vis_weapon_color[1] " ) << options::visuals::vis_weapon_color.g << std::endl;
	cfg_file << xs( "vis_weapon_color[2] " ) << options::visuals::vis_weapon_color.b << std::endl;

	cfg_file << xs( "vis_ducking_color[0] " ) << options::visuals::vis_ducking_color.r << std::endl;
	cfg_file << xs( "vis_ducking_color[1] " ) << options::visuals::vis_ducking_color.g << std::endl;
	cfg_file << xs( "vis_ducking_color[2] " ) << options::visuals::vis_ducking_color.b << std::endl;

	cfg_file << xs( "vis_knocked_color[0] " ) << options::visuals::vis_knocked_color.r << std::endl;
	cfg_file << xs( "vis_knocked_color[1] " ) << options::visuals::vis_knocked_color.g << std::endl;
	cfg_file << xs( "vis_knocked_color[2] " ) << options::visuals::vis_knocked_color.b << std::endl;

	cfg_file << xs( "vis_snap_lines_color[0] " ) << options::visuals::vis_snap_lines_color.r << std::endl;
	cfg_file << xs( "vis_snap_lines_color[1] " ) << options::visuals::vis_snap_lines_color.g << std::endl;
	cfg_file << xs( "vis_snap_lines_color[2] " ) << options::visuals::vis_snap_lines_color.b << std::endl;

	cfg_file << xs( "vis_view_direction_color[0] " ) << options::visuals::vis_view_direction_color.r << std::endl;
	cfg_file << xs( "vis_view_direction_color[1] " ) << options::visuals::vis_view_direction_color.g << std::endl;
	cfg_file << xs( "vis_view_direction_color[2] " ) << options::visuals::vis_view_direction_color.b << std::endl;

	cfg_file << xs( "name_color[0] " ) << options::visuals::name_color.r << std::endl;
	cfg_file << xs( "name_color[1] " ) << options::visuals::name_color.g << std::endl;
	cfg_file << xs( "name_color[2] " ) << options::visuals::name_color.b << std::endl;

	cfg_file << xs( "tracers_color[0] " ) << options::visuals::tracers_color.r << std::endl;
	cfg_file << xs( "tracers_color[1] " ) << options::visuals::tracers_color.g << std::endl;
	cfg_file << xs( "tracers_color[2] " ) << options::visuals::tracers_color.b << std::endl;

	cfg_file << xs( "desync_bar_color[0] " ) << options::visuals::desync_bar_color.r << std::endl;
	cfg_file << xs( "desync_bar_color[1] " ) << options::visuals::desync_bar_color.g << std::endl;
	cfg_file << xs( "desync_bar_color[2] " ) << options::visuals::desync_bar_color.b << std::endl;

	cfg_file << xs( "reload_bar_color[0] " ) << options::visuals::reload_bar_color.r << std::endl;
	cfg_file << xs( "reload_bar_color[1] " ) << options::visuals::reload_bar_color.g << std::endl;
	cfg_file << xs( "reload_bar_color[2] " ) << options::visuals::reload_bar_color.b << std::endl;

	cfg_file << xs( "trails_color[0] " ) << options::visuals::trails_color.r << std::endl;
	cfg_file << xs( "trails_color[1] " ) << options::visuals::trails_color.g << std::endl;
	cfg_file << xs( "trails_color[2] " ) << options::visuals::trails_color.b << std::endl;

	cfg_file << xs( "reload_bar_color[0] " ) << options::visuals::reload_bar_color.r << std::endl;
	cfg_file << xs( "reload_bar_color[1] " ) << options::visuals::reload_bar_color.g << std::endl;
	cfg_file << xs( "reload_bar_color[2] " ) << options::visuals::reload_bar_color.b << std::endl;

	cfg_file << xs( "skeleton_color[0] " ) << options::visuals::skeleton_color.r << std::endl;
	cfg_file << xs( "skeleton_color[1] " ) << options::visuals::skeleton_color.g << std::endl;
	cfg_file << xs( "skeleton_color[2] " ) << options::visuals::skeleton_color.b << std::endl;

	cfg_file << xs( "box_color[0] " ) << options::visuals::box_color.r << std::endl;
	cfg_file << xs( "box_color[1] " ) << options::visuals::box_color.g << std::endl;
	cfg_file << xs( "box_color[2] " ) << options::visuals::box_color.b << std::endl;

	cfg_file << xs( "radar_color[0] " ) << options::visuals::radar_color.r << std::endl;
	cfg_file << xs( "radar_color[1] " ) << options::visuals::radar_color.g << std::endl;
	cfg_file << xs( "radar_color[2] " ) << options::visuals::radar_color.b << std::endl;

	cfg_file << xs( "oof_color[0] " ) << options::visuals::oof_color.r << std::endl;
	cfg_file << xs( "oof_color[1] " ) << options::visuals::oof_color.g << std::endl;
	cfg_file << xs( "oof_color[2] " ) << options::visuals::oof_color.b << std::endl;

	cfg_file << xs( "snap_lines_color[0] " ) << options::visuals::snap_lines_color.r << std::endl;
	cfg_file << xs( "snap_lines_color[1] " ) << options::visuals::snap_lines_color.g << std::endl;
	cfg_file << xs( "snap_lines_color[2] " ) << options::visuals::snap_lines_color.b << std::endl;

	cfg_file << xs( "view_direction_color[0] " ) << options::visuals::view_direction_color.r << std::endl;
	cfg_file << xs( "view_direction_color[1] " ) << options::visuals::view_direction_color.g << std::endl;
	cfg_file << xs( "view_direction_color[2] " ) << options::visuals::view_direction_color.b << std::endl;

	cfg_file << xs( "accent_color[0] " ) << options::accent_color.r << std::endl;
	cfg_file << xs( "accent_color[1] " ) << options::accent_color.g << std::endl;
	cfg_file << xs( "accent_color[2] " ) << options::accent_color.b << std::endl;

	cfg_file << xs( "distance_color[0] " ) << options::visuals::distance_color.r << std::endl;
	cfg_file << xs( "distance_color[1] " ) << options::visuals::distance_color.g << std::endl;
	cfg_file << xs( "distance_color[2] " ) << options::visuals::distance_color.b << std::endl;

	cfg_file << xs( "weapon_color[0] " ) << options::visuals::weapon_color.r << std::endl;
	cfg_file << xs( "weapon_color[1] " ) << options::visuals::weapon_color.g << std::endl;
	cfg_file << xs( "weapon_color[2] " ) << options::visuals::weapon_color.b << std::endl;

	cfg_file << xs( "health_text_color[0] " ) << options::visuals::health_text_color.r << std::endl;
	cfg_file << xs( "health_text_color[1] " ) << options::visuals::health_text_color.g << std::endl;
	cfg_file << xs( "health_text_color[2] " ) << options::visuals::health_text_color.b << std::endl;

	cfg_file << xs( "custom_health_color[0] " ) << options::visuals::custom_health_color.r << std::endl;
	cfg_file << xs( "custom_health_color[1] " ) << options::visuals::custom_health_color.g << std::endl;
	cfg_file << xs( "custom_health_color[2] " ) << options::visuals::custom_health_color.b << std::endl;

	cfg_file << xs( "modify_health_color " ) << options::visuals::modify_health_color << std::endl;

	cfg_file << xs( "modify_rain " ) << options::visuals::world::modify_rain << std::endl;
	cfg_file << xs( "rain_amount " ) << options::visuals::world::rain_amount << std::endl;

	cfg_file << xs( "aim_key " ) << g_aimbot.aim_key << std::endl;

	cfg_file.close( );
	std::cout << xs( "saved file with name: " ) << filename << std::endl;
	options::save_cfg = false;
}

void c_cfg_sys::load_cfg( const std::string& filename ) {
	std::ifstream cfg_file( filename );
	if( !cfg_file.is_open( ) ) {
		std::cout << xs( "can't open file with name: " ) << filename << std::endl;
		return;
	}

	std::string line;
	while ( std::getline( cfg_file, line ) ) {
		std::istringstream string_str( line );
		std::string feature_name;	
		if( string_str >> feature_name ) {
			if( feature_name == xs( "rainbow_accent" ) ) string_str >> options::rainbow_accent;

			if( feature_name == xs( "aim_check" ) ) string_str >> options::aimbot::aim_check;
			if( feature_name == xs( "smoothness" ) ) string_str >> options::aimbot::smoothness;
			if( feature_name == xs( "auto_fire" ) ) string_str >> options::aimbot::auto_fire;
			if( feature_name == xs( "should_simulate_movement" ) ) string_str >> options::aimbot::should_simulate_movement;
			if( feature_name == xs( "draw_fov" ) ) string_str >> options::aimbot::draw_fov;
			if( feature_name == xs( "draw_crosshair" ) ) string_str >> options::aimbot::draw_crosshair;
			if( feature_name == xs( "draw_target" ) ) string_str >> options::aimbot::draw_target;
			if( feature_name == xs( "aim_npc" ) ) string_str >> options::aimbot::aim_npc;

			if( feature_name == xs( "target_line_color[0]" ) ) string_str >> options::aimbot::target_line_color.r;
			if( feature_name == xs( "target_line_color[1]" ) ) string_str >> options::aimbot::target_line_color.g;
			if( feature_name == xs( "target_line_color[2]" ) ) string_str >> options::aimbot::target_line_color.b;

			if( feature_name == xs( "fov_circle_color[0]" ) ) string_str >> options::aimbot::fov_circle_color.r;
			if( feature_name == xs( "fov_circle_color[1]" ) ) string_str >> options::aimbot::fov_circle_color.g;
			if( feature_name == xs( "fov_circle_color[2]" ) ) string_str >> options::aimbot::fov_circle_color.b;

			if( feature_name == xs( "vis_name_color[0]" ) ) string_str >> options::visuals::vis_name_color.r;
			if( feature_name == xs( "vis_name_color[1]" ) ) string_str >> options::visuals::vis_name_color.g;
			if( feature_name == xs( "vis_name_color[2]" ) ) string_str >> options::visuals::vis_name_color.b;

			if( feature_name == xs( "vis_skeleton_color[0]" ) ) string_str >> options::visuals::vis_skeleton_color.r;
			if( feature_name == xs( "vis_skeleton_color[1]" ) ) string_str >> options::visuals::vis_skeleton_color.g;
			if( feature_name == xs( "vis_skeleton_color[2]" ) ) string_str >> options::visuals::vis_skeleton_color.b;

			if( feature_name == xs( "vis_box_color[0]" ) ) string_str >> options::visuals::vis_box_color.r;
			if( feature_name == xs( "vis_box_color[1]" ) ) string_str >> options::visuals::vis_box_color.g;
			if( feature_name == xs( "vis_box_color[2]" ) ) string_str >> options::visuals::vis_box_color.b;

			if( feature_name == xs( "vis_radar_color[0]" ) ) string_str >> options::visuals::vis_radar_color.r;
			if( feature_name == xs( "vis_radar_color[1]" ) ) string_str >> options::visuals::vis_radar_color.g;
			if( feature_name == xs( "vis_radar_color[2]" ) ) string_str >> options::visuals::vis_radar_color.b;

			if( feature_name == xs( "vis_oof_color[0]" ) ) string_str >> options::visuals::vis_oof_color.r;
			if( feature_name == xs( "vis_oof_color[1]" ) ) string_str >> options::visuals::vis_oof_color.g;
			if( feature_name == xs( "vis_oof_color[2]" ) ) string_str >> options::visuals::vis_oof_color.b;

			if( feature_name == xs( "vis_ducking_color[0]" ) ) string_str >> options::visuals::vis_ducking_color.r;
			if( feature_name == xs( "vis_ducking_color[1]" ) ) string_str >> options::visuals::vis_ducking_color.g;
			if( feature_name == xs( "vis_ducking_color[2]" ) ) string_str >> options::visuals::vis_ducking_color.b;

			if( feature_name == xs( "vis_knocked_color[0]" ) ) string_str >> options::visuals::vis_knocked_color.r;
			if( feature_name == xs( "vis_knocked_color[1]" ) ) string_str >> options::visuals::vis_knocked_color.g;
			if( feature_name == xs( "vis_knocked_color[2]" ) ) string_str >> options::visuals::vis_knocked_color.b;

			if( feature_name == xs( "vis_snap_lines_color[0]" ) ) string_str >> options::visuals::vis_snap_lines_color.r;
			if( feature_name == xs( "vis_snap_lines_color[1]" ) ) string_str >> options::visuals::vis_snap_lines_color.g;
			if( feature_name == xs( "vis_snap_lines_color[2]" ) ) string_str >> options::visuals::vis_snap_lines_color.b;

			if( feature_name == xs( "vis_view_direction_color[0]" ) ) string_str >> options::visuals::vis_view_direction_color.r;
			if( feature_name == xs( "vis_view_direction_color[1]" ) ) string_str >> options::visuals::vis_view_direction_color.g;
			if( feature_name == xs( "vis_view_direction_color[2]" ) ) string_str >> options::visuals::vis_view_direction_color.b;

			if( feature_name == xs( "npc_vis_name_color[0]" ) ) string_str >> options::visuals::npc_vis_name_color.r;
			if( feature_name == xs( "npc_vis_name_color[1]" ) ) string_str >> options::visuals::npc_vis_name_color.g;
			if( feature_name == xs( "npc_vis_name_color[2]" ) ) string_str >> options::visuals::npc_vis_name_color.b;

			if( feature_name == xs( "npc_vis_skeleton_color[0]" ) ) string_str >> options::visuals::npc_vis_skeleton_color.r;
			if( feature_name == xs( "npc_vis_skeleton_color[1]" ) ) string_str >> options::visuals::npc_vis_skeleton_color.g;
			if( feature_name == xs( "npc_vis_skeleton_color[2]" ) ) string_str >> options::visuals::npc_vis_skeleton_color.b;

			if( feature_name == xs( "npc_vis_box_color[0]" ) ) string_str >> options::visuals::npc_vis_box_color.r;
			if( feature_name == xs( "npc_vis_box_color[1]" ) ) string_str >> options::visuals::npc_vis_box_color.g;
			if( feature_name == xs( "npc_vis_box_color[2]" ) ) string_str >> options::visuals::npc_vis_box_color.b;

			if( feature_name == xs( "npc_vis_radar_color[0]" ) ) string_str >> options::visuals::npc_vis_radar_color.r;
			if( feature_name == xs( "npc_vis_radar_color[1]" ) ) string_str >> options::visuals::npc_vis_radar_color.g;
			if( feature_name == xs( "npc_vis_radar_color[2]" ) ) string_str >> options::visuals::npc_vis_radar_color.b;

			if( feature_name == xs( "npc_vis_oof_color[0]" ) ) string_str >> options::visuals::npc_vis_oof_color.r;
			if( feature_name == xs( "npc_vis_oof_color[1]" ) ) string_str >> options::visuals::npc_vis_oof_color.g;
			if( feature_name == xs( "npc_vis_oof_color[2]" ) ) string_str >> options::visuals::npc_vis_oof_color.b;

			if( feature_name == xs( "npc_vis_ducking_color[0]" ) ) string_str >> options::visuals::npc_vis_ducking_color.r;
			if( feature_name == xs( "npc_vis_ducking_color[1]" ) ) string_str >> options::visuals::npc_vis_ducking_color.g;
			if( feature_name == xs( "npc_vis_ducking_color[2]" ) ) string_str >> options::visuals::npc_vis_ducking_color.b;

			if( feature_name == xs( "npc_vis_knocked_color[0]" ) ) string_str >> options::visuals::npc_vis_knocked_color.r;
			if( feature_name == xs( "npc_vis_knocked_color[1]" ) ) string_str >> options::visuals::npc_vis_knocked_color.g;
			if( feature_name == xs( "npc_vis_knocked_color[2]" ) ) string_str >> options::visuals::npc_vis_knocked_color.b;

			if( feature_name == xs( "npc_vis_snap_lines_color[0]" ) ) string_str >> options::visuals::npc_vis_snap_lines_color.r;
			if( feature_name == xs( "npc_vis_snap_lines_color[1]" ) ) string_str >> options::visuals::npc_vis_snap_lines_color.g;
			if( feature_name == xs( "npc_vis_snap_lines_color[2]" ) ) string_str >> options::visuals::npc_vis_snap_lines_color.b;

			if( feature_name == xs( "npc_vis_view_direction_color[0]" ) ) string_str >> options::visuals::npc_vis_view_direction_color.r;
			if( feature_name == xs( "npc_vis_view_direction_color[1]" ) ) string_str >> options::visuals::npc_vis_view_direction_color.g;
			if( feature_name == xs( "npc_vis_view_direction_color[2]" ) ) string_str >> options::visuals::npc_vis_view_direction_color.b;

			if( feature_name == xs( "npc_name_color[0]" ) ) string_str >> options::visuals::npc_name_color.r;
			if( feature_name == xs( "npc_name_color[1]" ) ) string_str >> options::visuals::npc_name_color.g;
			if( feature_name == xs( "npc_name_color[2]" ) ) string_str >> options::visuals::npc_name_color.b;

			if( feature_name == xs( "npc_skeleton_color[0]" ) ) string_str >> options::visuals::npc_skeleton_color.r;
			if( feature_name == xs( "npc_skeleton_color[1]" ) ) string_str >> options::visuals::npc_skeleton_color.g;
			if( feature_name == xs( "npc_skeleton_color[2]" ) ) string_str >> options::visuals::npc_skeleton_color.b;

			if( feature_name == xs( "npc_box_color[0]" ) ) string_str >> options::visuals::npc_box_color.r;
			if( feature_name == xs( "npc_box_color[1]" ) ) string_str >> options::visuals::npc_box_color.g;
			if( feature_name == xs( "npc_box_color[2]" ) ) string_str >> options::visuals::npc_box_color.b;

			if( feature_name == xs( "npc_radar_color[0]" ) ) string_str >> options::visuals::npc_radar_color.r;
			if( feature_name == xs( "npc_radar_color[1]" ) ) string_str >> options::visuals::npc_radar_color.g;
			if( feature_name == xs( "npc_radar_color[2]" ) ) string_str >> options::visuals::npc_radar_color.b;

			if( feature_name == xs( "npc_oof_color[0]" ) ) string_str >> options::visuals::npc_oof_color.r;
			if( feature_name == xs( "npc_oof_color[1]" ) ) string_str >> options::visuals::npc_oof_color.g;
			if( feature_name == xs( "npc_oof_color[2]" ) ) string_str >> options::visuals::npc_oof_color.b;

			if( feature_name == xs( "npc_ducking_color[0]" ) ) string_str >> options::visuals::npc_ducking_color.r;
			if( feature_name == xs( "npc_ducking_color[1]" ) ) string_str >> options::visuals::npc_ducking_color.g;
			if( feature_name == xs( "npc_ducking_color[2]" ) ) string_str >> options::visuals::npc_ducking_color.b;

			if( feature_name == xs( "npc_knocked_color[0]" ) ) string_str >> options::visuals::npc_knocked_color.r;
			if( feature_name == xs( "npc_knocked_color[1]" ) ) string_str >> options::visuals::npc_knocked_color.g;
			if( feature_name == xs( "npc_knocked_color[2]" ) ) string_str >> options::visuals::npc_knocked_color.b;

			if( feature_name == xs( "npc_snap_lines_color[0]" ) ) string_str >> options::visuals::npc_snap_lines_color.r;
			if( feature_name == xs( "npc_snap_lines_color[1]" ) ) string_str >> options::visuals::npc_snap_lines_color.g;
			if( feature_name == xs( "npc_snap_lines_color[2]" ) ) string_str >> options::visuals::npc_snap_lines_color.b;

			if( feature_name == xs( "npc_view_direction_color[0]" ) ) string_str >> options::visuals::npc_view_direction_color.r;
			if( feature_name == xs( "npc_view_direction_color[1]" ) ) string_str >> options::visuals::npc_view_direction_color.g;
			if( feature_name == xs( "npc_view_direction_color[2]" ) ) string_str >> options::visuals::npc_view_direction_color.b;

			if( feature_name == xs( "name_color[0]" ) ) string_str >> options::visuals::name_color.r;
			if( feature_name == xs( "name_color[1]" ) ) string_str >> options::visuals::name_color.g;
			if( feature_name == xs( "name_color[2]" ) ) string_str >> options::visuals::name_color.b;

			if( feature_name == xs( "tracers_color[0]" ) ) string_str >> options::visuals::tracers_color.r;
			if( feature_name == xs( "tracers_color[1]" ) ) string_str >> options::visuals::tracers_color.g;
			if( feature_name == xs( "tracers_color[2]" ) ) string_str >> options::visuals::tracers_color.b;

			if( feature_name == xs( "desync_bar_color[0]" ) ) string_str >> options::visuals::desync_bar_color.r;
			if( feature_name == xs( "desync_bar_color[1]" ) ) string_str >> options::visuals::desync_bar_color.g;
			if( feature_name == xs( "desync_bar_color[2]" ) ) string_str >> options::visuals::desync_bar_color.b;

			if( feature_name == xs( "reload_bar_color[0]" ) ) string_str >> options::visuals::reload_bar_color.r;
			if( feature_name == xs( "reload_bar_color[1]" ) ) string_str >> options::visuals::reload_bar_color.g;
			if( feature_name == xs( "reload_bar_color[2]" ) ) string_str >> options::visuals::reload_bar_color.b;

			if( feature_name == xs( "trails_color[0]" ) ) string_str >> options::visuals::trails_color.r;
			if( feature_name == xs( "trails_color[1]" ) ) string_str >> options::visuals::trails_color.g;
			if( feature_name == xs( "trails_color[2]" ) ) string_str >> options::visuals::trails_color.b;

			if( feature_name == xs( "reload_bar_color[0]" ) ) string_str >> options::visuals::reload_bar_color.r;
			if( feature_name == xs( "reload_bar_color[1]" ) ) string_str >> options::visuals::reload_bar_color.g;
			if( feature_name == xs( "reload_bar_color[2]" ) ) string_str >> options::visuals::reload_bar_color.b;

			if( feature_name == xs( "skeleton_color[0]" ) ) string_str >> options::visuals::skeleton_color.r;
			if( feature_name == xs( "skeleton_color[1]" ) ) string_str >> options::visuals::skeleton_color.g;
			if( feature_name == xs( "skeleton_color[2]" ) ) string_str >> options::visuals::skeleton_color.b;

			if( feature_name == xs( "box_color[0]" ) ) string_str >> options::visuals::box_color.r;
			if( feature_name == xs( "box_color[1]" ) ) string_str >> options::visuals::box_color.g;
			if( feature_name == xs( "box_color[2]" ) ) string_str >> options::visuals::box_color.b;

			if( feature_name == xs( "radar_color[0]" ) ) string_str >> options::visuals::radar_color.r;
			if( feature_name == xs( "radar_color[1]" ) ) string_str >> options::visuals::radar_color.g;
			if( feature_name == xs( "radar_color[2]" ) ) string_str >> options::visuals::radar_color.b;

			if( feature_name == xs( "oof_color[0]" ) ) string_str >> options::visuals::oof_color.r;
			if( feature_name == xs( "oof_color[1]" ) ) string_str >> options::visuals::oof_color.g;
			if( feature_name == xs( "oof_color[2]" ) ) string_str >> options::visuals::oof_color.b;

			if( feature_name == xs( "show_ducking_flag" ) ) string_str >> options::visuals::show_ducking_flag;
			if( feature_name == xs( "ducking_color[0]" ) ) string_str >> options::visuals::ducking_color.r;
			if( feature_name == xs( "ducking_color[1]" ) ) string_str >> options::visuals::ducking_color.g;
			if( feature_name == xs( "ducking_color[2]" ) ) string_str >> options::visuals::ducking_color.b;

			if( feature_name == xs( "show_knocked_flag" ) ) string_str >> options::visuals::show_knocked_flag;
			if( feature_name == xs( "knocked_color[0]" ) ) string_str >> options::visuals::knocked_color.r;
			if( feature_name == xs( "knocked_color[1]" ) ) string_str >> options::visuals::knocked_color.g;
			if( feature_name == xs( "knocked_color[2]" ) ) string_str >> options::visuals::knocked_color.b;

			if( feature_name == xs( "snap_lines_color[0]" ) ) string_str >> options::visuals::snap_lines_color.r;
			if( feature_name == xs( "snap_lines_color[1]" ) ) string_str >> options::visuals::snap_lines_color.g;
			if( feature_name == xs( "snap_lines_color[2]" ) ) string_str >> options::visuals::snap_lines_color.b;

			if( feature_name == xs( "view_direction_color[0]" ) ) string_str >> options::visuals::view_direction_color.r;
			if( feature_name == xs( "view_direction_color[1]" ) ) string_str >> options::visuals::view_direction_color.g;
			if( feature_name == xs( "view_direction_color[2]" ) ) string_str >> options::visuals::view_direction_color.b;

			if( feature_name == xs( "accent_color[0]" ) ) string_str >> options::accent_color.r;
			if( feature_name == xs( "accent_color[1]" ) ) string_str >> options::accent_color.g;
			if( feature_name == xs( "accent_color[2]" ) ) string_str >> options::accent_color.b;

			if( feature_name == xs( "aim_helicopter" ) ) string_str >> options::aimbot::aim_helicopter;
			if( feature_name == xs( "manipulation" ) ) string_str >> options::aimbot::manipulation;
			if( feature_name == xs( "kill_aura" ) ) string_str >> options::aimbot::kill_aura;
			if( feature_name == xs( "auto_reload" ) ) string_str >> options::aimbot::auto_reload;
			if( feature_name == xs( "aim_nearest_bone" ) ) string_str >> options::aimbot::aim_nearest_bone;

			if( feature_name == xs( "aim_bone" ) ) string_str >> options::aimbot::aim_bone;
			if( feature_name == xs( "manipulation_key" ) ) string_str >> options::aimbot::manipulation_key;
			if( feature_name == xs( "smooth_type" ) ) string_str >> options::aimbot::smooth_type;
			if( feature_name == xs( "max_target_distance" ) ) string_str >> options::aimbot::max_target_distance;
			if( feature_name == xs( "fov_amount" ) ) string_str >> options::aimbot::fov_amount;

			if( feature_name == xs( "smoothness_amount" ) ) string_str >> options::aimbot::smoothness_amount;

			if( feature_name == xs( "infinite_jump" ) ) string_str >> options::aimbot::exploits::movement::infinite_jump;
			if( feature_name == xs( "stopper_fly" ) ) string_str >> options::aimbot::exploits::movement::stopper_fly;
			if( feature_name == xs( "climb_assist" ) ) string_str >> options::aimbot::exploits::movement::climb_assist;
			if( feature_name == xs( "fly_hack" ) ) string_str >> options::aimbot::exploits::movement::fly_hack;
			if( feature_name == xs( "omni_sprint" ) ) string_str >> options::aimbot::exploits::movement::omni_sprint;
			if( feature_name == xs( "silent_walk" ) ) string_str >> options::aimbot::exploits::movement::silent_walk;
			if( feature_name == xs( "always_sprint" ) ) string_str >> options::aimbot::exploits::movement::always_sprint;
			if( feature_name == xs( "high_jump" ) ) string_str >> options::aimbot::exploits::movement::high_jump;

			if( feature_name == xs( "walk_through_players" ) ) string_str >> options::aimbot::exploits::movement::walk_through_players;
			if( feature_name == xs( "disable_slow_down_melee" ) ) string_str >> options::aimbot::exploits::movement::disable_slow_down_melee;
			if( feature_name == xs( "modify_clothing_speed" ) ) string_str >> options::aimbot::exploits::movement::modify_clothing_speed;
			if( feature_name == xs( "increase_height" ) ) string_str >> options::aimbot::exploits::movement::increase_height;

			if( feature_name == xs( "fly_key" ) ) string_str >> options::aimbot::exploits::movement::fly_key;
			if( feature_name == xs( "ignore_key" ) ) string_str >> options::aimbot::exploits::movement::ignore_key;
			if( feature_name == xs( "omni_sprint_key" ) ) string_str >> options::aimbot::exploits::movement::omni_sprint_key;
			if( feature_name == xs( "silent_walk_key" ) ) string_str >> options::aimbot::exploits::movement::silent_walk_key;
			if( feature_name == xs( "increase_height_key" ) ) string_str >> options::aimbot::exploits::movement::increase_height_key;
			if( feature_name == xs( "fly_speed" ) ) string_str >> options::aimbot::exploits::movement::fly_speed;
			if( feature_name == xs( "jump_height" ) ) string_str >> options::aimbot::exploits::movement::jump_height;
			if( feature_name == xs( "omni_sprint_speed" ) ) string_str >> options::aimbot::exploits::movement::omni_sprint_speed;
			if( feature_name == xs( "height_amount" ) ) string_str >> options::aimbot::exploits::movement::height_amount;

			if( feature_name == xs( "master_switch" ) ) string_str >> options::visuals::world::master_switch;

			if( feature_name == xs( "show_diesel_fuel" ) ) string_str >> options::visuals::world::show_diesel_fuel;

			if( feature_name == xs( "color_heal[0]" ) ) string_str >> options::visuals::world::color_heal.r;
			if( feature_name == xs( "color_heal[1]" ) ) string_str >> options::visuals::world::color_heal.g;
			if( feature_name == xs( "color_heal[2]" ) ) string_str >> options::visuals::world::color_heal.b;

			if( feature_name == xs( "color_weapons[0]" ) ) string_str >> options::visuals::world::color_weapons.r;
			if( feature_name == xs( "color_weapons[1]" ) ) string_str >> options::visuals::world::color_weapons.g;
			if( feature_name == xs( "color_weapons[2]" ) ) string_str >> options::visuals::world::color_weapons.b;

			if( feature_name == xs( "color_melee_weapons[0]" ) ) string_str >> options::visuals::world::color_melee_weapons.r;
			if( feature_name == xs( "color_melee_weapons[1]" ) ) string_str >> options::visuals::world::color_melee_weapons.g;
			if( feature_name == xs( "color_melee_weapons[2]" ) ) string_str >> options::visuals::world::color_melee_weapons.b;

			if( feature_name == xs( "color_everything[0]" ) ) string_str >> options::visuals::world::color_everything.r;
			if( feature_name == xs( "color_everything[1]" ) ) string_str >> options::visuals::world::color_everything.g;
			if( feature_name == xs( "color_everything[2]" ) ) string_str >> options::visuals::world::color_everything.b;

			if( feature_name == xs( "color_stashes[0]" ) ) string_str >> options::visuals::world::color_stashes.r;
			if( feature_name == xs( "color_stashes[1]" ) ) string_str >> options::visuals::world::color_stashes.g;
			if( feature_name == xs( "color_stashes[2]" ) ) string_str >> options::visuals::world::color_stashes.b;
	
			if( feature_name == xs( "color_animals[0]" ) ) string_str >> options::visuals::world::color_animals.r;
			if( feature_name == xs( "color_animals[1]" ) ) string_str >> options::visuals::world::color_animals.g;
			if( feature_name == xs( "color_animals[2]" ) ) string_str >> options::visuals::world::color_animals.b;

			if( feature_name == xs( "color_traps[0]" ) ) string_str >> options::visuals::world::color_traps.r;
			if( feature_name == xs( "color_traps[1]" ) ) string_str >> options::visuals::world::color_traps.g;
			if( feature_name == xs( "color_traps[2]" ) ) string_str >> options::visuals::world::color_traps.b;

			if( feature_name == xs( "color_storages[0]" ) ) string_str >> options::visuals::world::color_storages.r;
			if( feature_name == xs( "color_storages[1]" ) ) string_str >> options::visuals::world::color_storages.g;
			if( feature_name == xs( "color_storages[2]" ) ) string_str >> options::visuals::world::color_storages.b;

			if( feature_name == xs( "color_vehicles[0]" ) ) string_str >> options::visuals::world::color_vehicles.r;
			if( feature_name == xs( "color_vehicles[1]" ) ) string_str >> options::visuals::world::color_vehicles.g;
			if( feature_name == xs( "color_vehicles[2]" ) ) string_str >> options::visuals::world::color_vehicles.b;

			if( feature_name == xs( "color_raid[0]" ) ) string_str >> options::visuals::world::color_raid.r;
			if( feature_name == xs( "color_raid[1]" ) ) string_str >> options::visuals::world::color_raid.g;
			if( feature_name == xs( "color_raid[2]" ) ) string_str >> options::visuals::world::color_raid.b;

			if( feature_name == xs( "color_item[0]" ) ) string_str >> options::visuals::world::color_item.r;
			if( feature_name == xs( "color_item[1]" ) ) string_str >> options::visuals::world::color_item.g;
			if( feature_name == xs( "color_item[2]" ) ) string_str >> options::visuals::world::color_item.b;

			if( feature_name == xs( "color_respawn_points[0]" ) ) string_str >> options::visuals::world::color_respawn_points.r;
			if( feature_name == xs( "color_respawn_points[1]" ) ) string_str >> options::visuals::world::color_respawn_points.g;
			if( feature_name == xs( "color_respawn_points[2]" ) ) string_str >> options::visuals::world::color_respawn_points.b;

			if( feature_name == xs( "color_chickens[0]" ) ) string_str >> options::visuals::world::color_chickens.r;
			if( feature_name == xs( "color_chickens[1]" ) ) string_str >> options::visuals::world::color_chickens.g;
			if( feature_name == xs( "color_chickens[2]" ) ) string_str >> options::visuals::world::color_chickens.b;

			if( feature_name == xs( "color_helicopter[0]" ) ) string_str >> options::visuals::world::color_helicopter.r;
			if( feature_name == xs( "color_helicopter[1]" ) ) string_str >> options::visuals::world::color_helicopter.g;
			if( feature_name == xs( "color_helicopter[2]" ) ) string_str >> options::visuals::world::color_helicopter.b;

			if( feature_name == xs( "color_ores[0]" ) ) string_str >> options::visuals::world::color_ores.r;
			if( feature_name == xs( "color_ores[1]" ) ) string_str >> options::visuals::world::color_ores.g;
			if( feature_name == xs( "color_ores[2]" ) ) string_str >> options::visuals::world::color_ores.b;

			if( feature_name == xs( "color_sulfur_ore[0]" ) ) string_str >> options::visuals::world::color_sulfur_ore.r;
			if( feature_name == xs( "color_sulfur_ore[1]" ) ) string_str >> options::visuals::world::color_sulfur_ore.g;
			if( feature_name == xs( "color_sulfur_ore[2]" ) ) string_str >> options::visuals::world::color_sulfur_ore.b;

			if( feature_name == xs( "color_metal_ore[0]" ) ) string_str >> options::visuals::world::color_metal_ore.r;
			if( feature_name == xs( "color_metal_ore[1]" ) ) string_str >> options::visuals::world::color_metal_ore.g;
			if( feature_name == xs( "color_metal_ore[2]" ) ) string_str >> options::visuals::world::color_metal_ore.b;

			if( feature_name == xs( "color_stone_ore[0]" ) ) string_str >> options::visuals::world::color_stone_ore.r;
			if( feature_name == xs( "color_stone_ore[1]" ) ) string_str >> options::visuals::world::color_stone_ore.g;
			if( feature_name == xs( "color_stone_ore[2]" ) ) string_str >> options::visuals::world::color_stone_ore.b;

			if( feature_name == xs( "color_tool_cupboard[0]" ) ) string_str >> options::visuals::world::color_tool_cupboard.r;
			if( feature_name == xs( "color_tool_cupboard[1]" ) ) string_str >> options::visuals::world::color_tool_cupboard.g;
			if( feature_name == xs( "color_tool_cupboard[2]" ) ) string_str >> options::visuals::world::color_tool_cupboard.b;

			if( feature_name == xs( "color_box_storages[0]" ) ) string_str >> options::visuals::world::color_box_storages.r;
			if( feature_name == xs( "color_box_storages[1]" ) ) string_str >> options::visuals::world::color_box_storages.g;
			if( feature_name == xs( "color_box_storages[2]" ) ) string_str >> options::visuals::world::color_box_storages.b;

			if( feature_name == xs( "color_ammo_nails_arrows[0]" ) ) string_str >> options::visuals::world::color_ammo_nails_arrows.r;
			if( feature_name == xs( "color_ammo_nails_arrows[1]" ) ) string_str >> options::visuals::world::color_ammo_nails_arrows.g;
			if( feature_name == xs( "color_ammo_nails_arrows[2]" ) ) string_str >> options::visuals::world::color_ammo_nails_arrows.b;

			if( feature_name == xs( "color_supply_signals[0]" ) ) string_str >> options::visuals::world::color_supply_signals.r;
			if( feature_name == xs( "color_supply_signals[1]" ) ) string_str >> options::visuals::world::color_supply_signals.g;
			if( feature_name == xs( "color_supply_signals[2]" ) ) string_str >> options::visuals::world::color_supply_signals.b;

			if( feature_name == xs( "color_supply_drops[0]" ) ) string_str >> options::visuals::world::color_supply_drops.r;
			if( feature_name == xs( "color_supply_drops[1]" ) ) string_str >> options::visuals::world::color_supply_drops.g;
			if( feature_name == xs( "color_supply_drops[2]" ) ) string_str >> options::visuals::world::color_supply_drops.b;

			if( feature_name == xs( "color_hemp[0]" ) ) string_str >> options::visuals::world::color_hemp.r;
			if( feature_name == xs( "color_hemp[1]" ) ) string_str >> options::visuals::world::color_hemp.g;
			if( feature_name == xs( "color_hemp[2]" ) ) string_str >> options::visuals::world::color_hemp.b;

			if( feature_name == xs( "color_mushroom[0]" ) ) string_str >> options::visuals::world::color_mushroom.r;
			if( feature_name == xs( "color_mushroom[1]" ) ) string_str >> options::visuals::world::color_mushroom.g;
			if( feature_name == xs( "color_mushroom[2]" ) ) string_str >> options::visuals::world::color_mushroom.b;

			if( feature_name == xs( "color_pumpkin[0]" ) ) string_str >> options::visuals::world::color_pumpkin.r;
			if( feature_name == xs( "color_pumpkin[1]" ) ) string_str >> options::visuals::world::color_pumpkin.g;
			if( feature_name == xs( "color_pumpkin[2]" ) ) string_str >> options::visuals::world::color_pumpkin.b;

			if( feature_name == xs( "color_berrys[0]" ) ) string_str >> options::visuals::world::color_berrys.r;
			if( feature_name == xs( "color_berrys[1]" ) ) string_str >> options::visuals::world::color_berrys.g;
			if( feature_name == xs( "color_berrys[2]" ) ) string_str >> options::visuals::world::color_berrys.b;

			if( feature_name == xs( "color_corns[0]" ) ) string_str >> options::visuals::world::color_corns.r;
			if( feature_name == xs( "color_corns[1]" ) ) string_str >> options::visuals::world::color_corns.g;
			if( feature_name == xs( "color_corns[2]" ) ) string_str >> options::visuals::world::color_corns.b;

			if( feature_name == xs( "show_corpse" ) ) string_str >> options::visuals::world::show_corpse;
			if( feature_name == xs( "show_backpack" ) ) string_str >> options::visuals::world::show_backpack;

			if( feature_name == xs( "color_corpse[0]" ) ) string_str >> options::visuals::world::color_corpse.r;
			if( feature_name == xs( "color_corpse[1]" ) ) string_str >> options::visuals::world::color_corpse.g;
			if( feature_name == xs( "color_corpse[2]" ) ) string_str >> options::visuals::world::color_corpse.b;

			if( feature_name == xs( "color_backpack[0]" ) ) string_str >> options::visuals::world::color_backpack.r;
			if( feature_name == xs( "color_backpack[1]" ) ) string_str >> options::visuals::world::color_backpack.g;
			if( feature_name == xs( "color_backpack[2]" ) ) string_str >> options::visuals::world::color_backpack.b;

			if( feature_name == xs( "color_potatos[0]" ) ) string_str >> options::visuals::world::color_potatos.r;
			if( feature_name == xs( "color_potatos[1]" ) ) string_str >> options::visuals::world::color_potatos.g;
			if( feature_name == xs( "color_potatos[2]" ) ) string_str >> options::visuals::world::color_potatos.b;

			if( feature_name == xs( "color_modular_car[0]" ) ) string_str >> options::visuals::world::color_modular_car.r;
			if( feature_name == xs( "color_modular_car[1]" ) ) string_str >> options::visuals::world::color_modular_car.g;
			if( feature_name == xs( "color_modular_car[2]" ) ) string_str >> options::visuals::world::color_modular_car.b;

			if( feature_name == xs( "color_two_modules_car[0]" ) ) string_str >> options::visuals::world::color_two_modules_car.r;
			if( feature_name == xs( "color_two_modules_car[1]" ) ) string_str >> options::visuals::world::color_two_modules_car.g;
			if( feature_name == xs( "color_two_modules_car[2]" ) ) string_str >> options::visuals::world::color_two_modules_car.b;

			if( feature_name == xs( "color_minicopter[0]" ) ) string_str >> options::visuals::world::color_minicopter.r;
			if( feature_name == xs( "color_minicopter[1]" ) ) string_str >> options::visuals::world::color_minicopter.g;
			if( feature_name == xs( "color_minicopter[2]" ) ) string_str >> options::visuals::world::color_minicopter.b;

			if( feature_name == xs( "color_scrap_helicopter[0]" ) ) string_str >> options::visuals::world::color_scrap_helicopter.r;
			if( feature_name == xs( "color_scrap_helicopter[1]" ) ) string_str >> options::visuals::world::color_scrap_helicopter.g;
			if( feature_name == xs( "color_scrap_helicopter[2]" ) ) string_str >> options::visuals::world::color_scrap_helicopter.b;

			if( feature_name == xs( "color_rhib[0]" ) ) string_str >> options::visuals::world::color_rhib.r;
			if( feature_name == xs( "color_rhib[1]" ) ) string_str >> options::visuals::world::color_rhib.g;
			if( feature_name == xs( "color_rhib[2]" ) ) string_str >> options::visuals::world::color_rhib.b;

			if( feature_name == xs( "color_bradley_apc[0]" ) ) string_str >> options::visuals::world::color_bradley_apc.r;
			if( feature_name == xs( "color_bradley_apc[1]" ) ) string_str >> options::visuals::world::color_bradley_apc.g;
			if( feature_name == xs( "color_bradley_apc[2]" ) ) string_str >> options::visuals::world::color_bradley_apc.b;

			if( feature_name == xs( "color_kayak[0]" ) ) string_str >> options::visuals::world::color_kayak.r;
			if( feature_name == xs( "color_kayak[1]" ) ) string_str >> options::visuals::world::color_kayak.g;
			if( feature_name == xs( "color_kayak[2]" ) ) string_str >> options::visuals::world::color_kayak.b;

			if( feature_name == xs( "color_small_motorboat[0]" ) ) string_str >> options::visuals::world::color_small_motorboat.r;
			if( feature_name == xs( "color_small_motorboat[1]" ) ) string_str >> options::visuals::world::color_small_motorboat.g;
			if( feature_name == xs( "color_small_motorboat[2]" ) ) string_str >> options::visuals::world::color_small_motorboat.b;

			if( feature_name == xs( "color_solo_submarine[0]" ) ) string_str >> options::visuals::world::color_solo_submarine.r;
			if( feature_name == xs( "color_solo_submarine[1]" ) ) string_str >> options::visuals::world::color_solo_submarine.g;
			if( feature_name == xs( "color_solo_submarine[2]" ) ) string_str >> options::visuals::world::color_solo_submarine.b;

			if( feature_name == xs( "color_duo_submarine[0]" ) ) string_str >> options::visuals::world::color_duo_submarine.r;
			if( feature_name == xs( "color_duo_submarine[1]" ) ) string_str >> options::visuals::world::color_duo_submarine.g;
			if( feature_name == xs( "color_duo_submarine[2]" ) ) string_str >> options::visuals::world::color_duo_submarine.b;

			if( feature_name == xs( "color_landmines[0]" ) ) string_str >> options::visuals::world::color_landmines.r;
			if( feature_name == xs( "color_landmines[1]" ) ) string_str >> options::visuals::world::color_landmines.g;
			if( feature_name == xs( "color_landmines[2]" ) ) string_str >> options::visuals::world::color_landmines.b;

			if( feature_name == xs( "color_npc_turrets[0]" ) ) string_str >> options::visuals::world::color_npc_turrets.r;
			if( feature_name == xs( "color_npc_turrets[1]" ) ) string_str >> options::visuals::world::color_npc_turrets.g;
			if( feature_name == xs( "color_npc_turrets[2]" ) ) string_str >> options::visuals::world::color_npc_turrets.b;

			if( feature_name == xs( "color_auto_turrets[0]" ) ) string_str >> options::visuals::world::color_auto_turrets.r;
			if( feature_name == xs( "color_auto_turrets[1]" ) ) string_str >> options::visuals::world::color_auto_turrets.g;
			if( feature_name == xs( "color_auto_turrets[2]" ) ) string_str >> options::visuals::world::color_auto_turrets.b;

			if( feature_name == xs( "color_shotgun_traps[0]" ) ) string_str >> options::visuals::world::color_shotgun_traps.r;
			if( feature_name == xs( "color_shotgun_traps[1]" ) ) string_str >> options::visuals::world::color_shotgun_traps.g;
			if( feature_name == xs( "color_shotgun_traps[2]" ) ) string_str >> options::visuals::world::color_shotgun_traps.b;

			if( feature_name == xs( "color_tesla_coil[0]" ) ) string_str >> options::visuals::world::color_tesla_coil.r;
			if( feature_name == xs( "color_tesla_coil[1]" ) ) string_str >> options::visuals::world::color_tesla_coil.g;
			if( feature_name == xs( "color_tesla_coil[2]" ) ) string_str >> options::visuals::world::color_tesla_coil.b;

			if( feature_name == xs( "color_flame_turrets[0]" ) ) string_str >> options::visuals::world::color_flame_turrets.r;
			if( feature_name == xs( "color_flame_turrets[1]" ) ) string_str >> options::visuals::world::color_flame_turrets.g;
			if( feature_name == xs( "color_flame_turrets[2]" ) ) string_str >> options::visuals::world::color_flame_turrets.b;

			if( feature_name == xs( "color_sam_site[0]" ) ) string_str >> options::visuals::world::color_sam_site.r;
			if( feature_name == xs( "color_sam_site[1]" ) ) string_str >> options::visuals::world::color_sam_site.g;
			if( feature_name == xs( "color_sam_site[2]" ) ) string_str >> options::visuals::world::color_sam_site.b;

			if( feature_name == xs( "color_land_spikes[0]" ) ) string_str >> options::visuals::world::color_land_spikes.r;
			if( feature_name == xs( "color_land_spikes[1]" ) ) string_str >> options::visuals::world::color_land_spikes.g;
			if( feature_name == xs( "color_land_spikes[2]" ) ) string_str >> options::visuals::world::color_land_spikes.b;

			if( feature_name == xs( "color_bear_trap[0]" ) ) string_str >> options::visuals::world::color_bear_trap.r;
			if( feature_name == xs( "color_bear_trap[1]" ) ) string_str >> options::visuals::world::color_bear_trap.g;
			if( feature_name == xs( "color_bear_trap[2]" ) ) string_str >> options::visuals::world::color_bear_trap.b;

			if( feature_name == xs( "color_oil_barrel[0]" ) ) string_str >> options::visuals::world::color_oil_barrel.r;
			if( feature_name == xs( "color_oil_barrel[1]" ) ) string_str >> options::visuals::world::color_oil_barrel.g;
			if( feature_name == xs( "color_oil_barrel[2]" ) ) string_str >> options::visuals::world::color_oil_barrel.b;

			if( feature_name == xs( "color_regular_barrels[0]" ) ) string_str >> options::visuals::world::color_regular_barrels.r;
			if( feature_name == xs( "color_regular_barrels[1]" ) ) string_str >> options::visuals::world::color_regular_barrels.g;
			if( feature_name == xs( "color_regular_barrels[2]" ) ) string_str >> options::visuals::world::color_regular_barrels.b;

			if( feature_name == xs( "color_underwater_crate[0]" ) ) string_str >> options::visuals::world::color_underwater_crate.r;
			if( feature_name == xs( "color_underwater_crate[1]" ) ) string_str >> options::visuals::world::color_underwater_crate.g;
			if( feature_name == xs( "color_underwater_crate[2]" ) ) string_str >> options::visuals::world::color_underwater_crate.b;

			if( feature_name == xs( "color_elite_crate[0]" ) ) string_str >> options::visuals::world::color_elite_crate.r;
			if( feature_name == xs( "color_elite_crate[1]" ) ) string_str >> options::visuals::world::color_elite_crate.g;
			if( feature_name == xs( "color_elite_crate[2]" ) ) string_str >> options::visuals::world::color_elite_crate.b;

			if( feature_name == xs( "color_military_crate[0]" ) ) string_str >> options::visuals::world::color_military_crate.r;
			if( feature_name == xs( "color_military_crate[1]" ) ) string_str >> options::visuals::world::color_military_crate.g;
			if( feature_name == xs( "color_military_crate[2]" ) ) string_str >> options::visuals::world::color_military_crate.b;
	
			if( feature_name == xs( "color_bradley_crate[0]" ) ) string_str >> options::visuals::world::color_bradley_crate.r;
			if( feature_name == xs( "color_bradley_crate[1]" ) ) string_str >> options::visuals::world::color_bradley_crate.g;
			if( feature_name == xs( "color_bradley_crate[2]" ) ) string_str >> options::visuals::world::color_bradley_crate.b;

			if( feature_name == xs( "color_food_crate[0]" ) ) string_str >> options::visuals::world::color_food_crate.r;
			if( feature_name == xs( "color_food_crate[1]" ) ) string_str >> options::visuals::world::color_food_crate.g;
			if( feature_name == xs( "color_food_crate[2]" ) ) string_str >> options::visuals::world::color_food_crate.b;
	
			if( feature_name == xs( "color_medical_crate[0]" ) ) string_str >> options::visuals::world::color_medical_crate.r;
			if( feature_name == xs( "color_medical_crate[1]" ) ) string_str >> options::visuals::world::color_medical_crate.g;
			if( feature_name == xs( "color_medical_crate[2]" ) ) string_str >> options::visuals::world::color_medical_crate.b;

			if( feature_name == xs( "color_diesel_fuel[0]" ) ) string_str >> options::visuals::world::color_diesel_fuel.r;
			if( feature_name == xs( "color_diesel_fuel[1]" ) ) string_str >> options::visuals::world::color_diesel_fuel.g;
			if( feature_name == xs( "color_diesel_fuel[2]" ) ) string_str >> options::visuals::world::color_diesel_fuel.b;

			if( feature_name == xs( "color_helicopter_crate[0]" ) ) string_str >> options::visuals::world::color_helicopter_crate.r;
			if( feature_name == xs( "color_helicopter_crate[1]" ) ) string_str >> options::visuals::world::color_helicopter_crate.g;
			if( feature_name == xs( "color_helicopter_crate[2]" ) ) string_str >> options::visuals::world::color_helicopter_crate.b;

			if( feature_name == xs( "color_hackable_locked_crate[0]" ) ) string_str >> options::visuals::world::color_hackable_locked_crate.r;
			if( feature_name == xs( "color_hackable_locked_crate[1]" ) ) string_str >> options::visuals::world::color_hackable_locked_crate.g;
			if( feature_name == xs( "color_hackable_locked_crate[2]" ) ) string_str >> options::visuals::world::color_hackable_locked_crate.b;

			if( feature_name == xs( "color_normal_crate[0]" ) ) string_str >> options::visuals::world::color_normal_crate.r;
			if( feature_name == xs( "color_normal_crate[1]" ) ) string_str >> options::visuals::world::color_normal_crate.g;
			if( feature_name == xs( "color_normal_crate[2]" ) ) string_str >> options::visuals::world::color_normal_crate.b;

			if( feature_name == xs( "color_small_crate[0]" ) ) string_str >> options::visuals::world::color_small_crate.r;
			if( feature_name == xs( "color_small_crate[1]" ) ) string_str >> options::visuals::world::color_small_crate.g;
			if( feature_name == xs( "color_small_crate[2]" ) ) string_str >> options::visuals::world::color_small_crate.b;

			if( feature_name == xs( "color_mine_crate[0]" ) ) string_str >> options::visuals::world::color_mine_crate.r;
			if( feature_name == xs( "color_mine_crate[1]" ) ) string_str >> options::visuals::world::color_mine_crate.g;
			if( feature_name == xs( "color_mine_crate[2]" ) ) string_str >> options::visuals::world::color_mine_crate.b;

			if( feature_name == xs( "color_tool_box[0]" ) ) string_str >> options::visuals::world::color_tool_box.r;
			if( feature_name == xs( "color_tool_box[1]" ) ) string_str >> options::visuals::world::color_tool_box.g;
			if( feature_name == xs( "color_tool_box[2]" ) ) string_str >> options::visuals::world::color_tool_box.b;

			if( feature_name == xs( "color_boars[0]" ) ) string_str >> options::visuals::world::color_boars.r;
			if( feature_name == xs( "color_boars[1]" ) ) string_str >> options::visuals::world::color_boars.g;
			if( feature_name == xs( "color_boars[2]" ) ) string_str >> options::visuals::world::color_boars.b;

			if( feature_name == xs( "color_wolves[0]" ) ) string_str >> options::visuals::world::color_wolves.r;
			if( feature_name == xs( "color_wolves[1]" ) ) string_str >> options::visuals::world::color_wolves.g;
			if( feature_name == xs( "color_wolves[2]" ) ) string_str >> options::visuals::world::color_wolves.b;

			if( feature_name == xs( "color_horses[0]" ) ) string_str >> options::visuals::world::color_horses.r;
			if( feature_name == xs( "color_horses[1]" ) ) string_str >> options::visuals::world::color_horses.g;
			if( feature_name == xs( "color_horses[2]" ) ) string_str >> options::visuals::world::color_horses.b;

			if( feature_name == xs( "color_sharks[0]" ) ) string_str >> options::visuals::world::color_sharks.r;
			if( feature_name == xs( "color_sharks[1]" ) ) string_str >> options::visuals::world::color_sharks.g;
			if( feature_name == xs( "color_sharks[2]" ) ) string_str >> options::visuals::world::color_sharks.b;

			if( feature_name == xs( "color_deers[0]" ) ) string_str >> options::visuals::world::color_deers.r;
			if( feature_name == xs( "color_deers[1]" ) ) string_str >> options::visuals::world::color_deers.g;
			if( feature_name == xs( "color_deers[2]" ) ) string_str >> options::visuals::world::color_deers.b;

			if( feature_name == xs( "color_polar_bears[0]" ) ) string_str >> options::visuals::world::color_polar_bears.r;
			if( feature_name == xs( "color_polar_bears[1]" ) ) string_str >> options::visuals::world::color_polar_bears.g;
			if( feature_name == xs( "color_polar_bears[2]" ) ) string_str >> options::visuals::world::color_polar_bears.b;

			if( feature_name == xs( "color_bears[0]" ) ) string_str >> options::visuals::world::color_bears.r;
			if( feature_name == xs( "color_bears[1]" ) ) string_str >> options::visuals::world::color_bears.g;
			if( feature_name == xs( "color_bears[2]" ) ) string_str >> options::visuals::world::color_bears.b;

			if( feature_name == xs( "color_drone[0]" ) ) string_str >> options::visuals::world::color_drone.r;
			if( feature_name == xs( "color_drone[1]" ) ) string_str >> options::visuals::world::color_drone.g;
			if( feature_name == xs( "color_drone[2]" ) ) string_str >> options::visuals::world::color_drone.b;

			if( feature_name == xs( "color_recycler[0]" ) ) string_str >> options::visuals::world::color_recycler.r;
			if( feature_name == xs( "color_recycler[1]" ) ) string_str >> options::visuals::world::color_recycler.g;
			if( feature_name == xs( "color_recycler[2]" ) ) string_str >> options::visuals::world::color_recycler.b;

			if( feature_name == xs( "color_metal_collectibles[0]" ) ) string_str >> options::visuals::world::color_metal_collectibles.r;
			if( feature_name == xs( "color_metal_collectibles[1]" ) ) string_str >> options::visuals::world::color_metal_collectibles.g;
			if( feature_name == xs( "color_metal_collectibles[2]" ) ) string_str >> options::visuals::world::color_metal_collectibles.b;

			if( feature_name == xs( "color_wood_collectibles[0]" ) ) string_str >> options::visuals::world::color_wood_collectibles.r;
			if( feature_name == xs( "color_wood_collectibles[1]" ) ) string_str >> options::visuals::world::color_wood_collectibles.g;
			if( feature_name == xs( "color_wood_collectibles[2]" ) ) string_str >> options::visuals::world::color_wood_collectibles.b;

			if( feature_name == xs( "color_stone_collectibles[0]" ) ) string_str >> options::visuals::world::color_stone_collectibles.r;
			if( feature_name == xs( "color_stone_collectibles[1]" ) ) string_str >> options::visuals::world::color_stone_collectibles.g;
			if( feature_name == xs( "color_stone_collectibles[2]" ) ) string_str >> options::visuals::world::color_stone_collectibles.b;

			if( feature_name == xs( "color_vending_machine[0]" ) ) string_str >> options::visuals::world::color_vending_machine.r;
			if( feature_name == xs( "color_vending_machine[1]" ) ) string_str >> options::visuals::world::color_vending_machine.g;
			if( feature_name == xs( "color_vending_machine[2]" ) ) string_str >> options::visuals::world::color_vending_machine.b;

			if( feature_name == xs( "vis_distance_color[0]" ) ) string_str >> options::visuals::vis_distance_color.r;
			if( feature_name == xs( "vis_distance_color[1]" ) ) string_str >> options::visuals::vis_distance_color.g;
			if( feature_name == xs( "vis_distance_color[2]" ) ) string_str >> options::visuals::vis_distance_color.b;

			if( feature_name == xs( "vis_weapon_color[0]" ) ) string_str >> options::visuals::vis_weapon_color.r;
			if( feature_name == xs( "vis_weapon_color[1]" ) ) string_str >> options::visuals::vis_weapon_color.g;
			if( feature_name == xs( "vis_weapon_color[2]" ) ) string_str >> options::visuals::vis_weapon_color.b;

			if( feature_name == xs( "distance_color[0]" ) ) string_str >> options::visuals::distance_color.r;
			if( feature_name == xs( "distance_color[1]" ) ) string_str >> options::visuals::distance_color.g;
			if( feature_name == xs( "distance_color[2]" ) ) string_str >> options::visuals::distance_color.b;

			if( feature_name == xs( "weapon_color[0]" ) ) string_str >> options::visuals::weapon_color.r;
			if( feature_name == xs( "weapon_color[1]" ) ) string_str >> options::visuals::weapon_color.g;
			if( feature_name == xs( "weapon_color[2]" ) ) string_str >> options::visuals::weapon_color.b;

			if( feature_name == xs( "health_text_color[0]" ) ) string_str >> options::visuals::health_text_color.r;
			if( feature_name == xs( "health_text_color[1]" ) ) string_str >> options::visuals::health_text_color.g;
			if( feature_name == xs( "health_text_color[2]" ) ) string_str >> options::visuals::health_text_color.b;

			if( feature_name == xs( "custom_health_color[0]" ) ) string_str >> options::visuals::custom_health_color.r;
			if( feature_name == xs( "custom_health_color[1]" ) ) string_str >> options::visuals::custom_health_color.g;
			if( feature_name == xs( "custom_health_color[2]" ) ) string_str >> options::visuals::custom_health_color.b;

			if( feature_name == xs( "modify_health_color" ) ) string_str >> options::visuals::modify_health_color;

			if( feature_name == xs( "health_thickness" ) ) string_str >> options::visuals::health_thickness;

			if( feature_name == xs( "auto_pickup" ) ) string_str >> options::aimbot::exploits::misc::auto_pickup;
			if( feature_name == xs( "manipulation_key" ) ) string_str >> options::aimbot::manipulation_key;

			if( feature_name == xs( "auto_untie_crates" ) ) string_str >> options::aimbot::exploits::misc::auto_untie_crates;

			if( feature_name == xs( "automatic_weapons" ) ) string_str >> options::aimbot::exploits::combat::automatic_weapons;
			if( feature_name == xs( "semi_automatic_weapons" ) ) string_str >> options::aimbot::exploits::combat::semi_automatic_weapons;
			if( feature_name == xs( "burst_weapons" ) ) string_str >> options::aimbot::exploits::combat::burst_weapons;
			if( feature_name == xs( "unlock_aim_on_jugger" ) ) string_str >> options::aimbot::exploits::combat::unlock_aim_on_jugger;
			if( feature_name == xs( "aim_bolt_cycle" ) ) string_str >> options::aimbot::exploits::combat::aim_bolt_cycle;
			if( feature_name == xs( "extended_melee" ) ) string_str >> options::aimbot::exploits::combat::extended_melee;
			if( feature_name == xs( "no_spread" ) ) string_str >> options::aimbot::exploits::combat::no_spread;
			if( feature_name == xs( "no_sway" ) ) string_str >> options::aimbot::exploits::combat::no_sway;
			if( feature_name == xs( "modify_eoka_chance" ) ) string_str >> options::aimbot::exploits::combat::modify_eoka_chance;
			if( feature_name == xs( "no_recoil" ) ) string_str >> options::aimbot::exploits::combat::no_recoil;
			if( feature_name == xs( "modify_can_attack" ) ) string_str >> options::aimbot::exploits::combat::modify_can_attack;
			if( feature_name == xs( "can_attack_in_vehicles" ) ) string_str >> options::aimbot::exploits::combat::can_attack_in_vehicles;
			if( feature_name == xs( "unlock_view_angles" ) ) string_str >> options::aimbot::exploits::combat::unlock_view_angles;
			if( feature_name == xs( "big_bullets" ) ) string_str >> options::aimbot::exploits::combat::big_bullets;
			if( feature_name == xs( "quick_bullets" ) ) string_str >> options::aimbot::exploits::combat::quick_bullets;

			if( feature_name == xs( "aim_type" ) ) string_str >> options::aimbot::aim_type;

			if( feature_name == xs( "pierce" ) ) string_str >> options::aimbot::exploits::combat::pierce;
			if( feature_name == xs( "spoof_hit_distance" ) ) string_str >> options::aimbot::exploits::combat::spoof_hit_distance;
			if( feature_name == xs( "no_shot_gun_spread" ) ) string_str >> options::aimbot::exploits::combat::no_shot_gun_spread;
			if( feature_name == xs( "head_teleportation" ) ) string_str >> options::aimbot::exploits::combat::head_teleportation;

			if( feature_name == xs( "reduce_recoil" ) ) string_str >> options::aimbot::exploits::combat::reduce_recoil;
			if( feature_name == xs( "reduce_spread" ) ) string_str >> options::aimbot::exploits::combat::reduce_spread;
			if( feature_name == xs( "bullet_distance" ) ) string_str >> options::aimbot::exploits::combat::bullet_distance;
			if( feature_name == xs( "eoka_chance" ) ) string_str >> options::aimbot::exploits::combat::eoka_chance;
			if( feature_name == xs( "attack_radius" ) ) string_str >> options::aimbot::exploits::combat::attack_radius;
			if( feature_name == xs( "bullet_size" ) ) string_str >> options::aimbot::exploits::combat::bullet_size;
			if( feature_name == xs( "teleport_key" ) ) string_str >> options::aimbot::exploits::combat::teleport_key;
			if( feature_name == xs( "bullet_speed" ) ) string_str >> options::aimbot::exploits::combat::bullet_speed;

			if( feature_name == xs( "fast_loot" ) ) string_str >> options::aimbot::exploits::time::fast_loot;
			if( feature_name == xs( "fast_heal" ) ) string_str >> options::aimbot::exploits::time::fast_heal;
			if( feature_name == xs( "fast_switch" ) ) string_str >> options::aimbot::exploits::time::fast_switch;
			if( feature_name == xs( "time_modifier" ) ) string_str >> options::aimbot::exploits::time::time_modifier;
			if( feature_name == xs( "rapid_fire" ) ) string_str >> options::aimbot::exploits::time::rapid_fire;
			if( feature_name == xs( "fake_lag" ) ) string_str >> options::aimbot::exploits::time::fake_lag;
			if( feature_name == xs( "instant_charge_compound" ) ) string_str >> options::aimbot::exploits::time::instant_charge_compound;
			if( feature_name == xs( "fake_lag_on" ) ) string_str >> options::aimbot::exploits::time::fake_lag_on;
			if( feature_name == xs( "fake_lag_amount" ) ) string_str >> options::aimbot::exploits::time::fake_lag_amount;

			if( feature_name == xs( "radar_position[0]" ) ) string_str >> g_esp.radar_position.x;
			if( feature_name == xs( "radar_position[1]" ) ) string_str >> g_esp.radar_position.y;

			if( feature_name == xs( "hotbar_position[0]" ) ) string_str >> g_esp.hotbar_position.x;
			if( feature_name == xs( "hotbar_position[1]" ) ) string_str >> g_esp.hotbar_position.y;

			if( feature_name == xs( "clothes_position[0]" ) ) string_str >> g_esp.clothes_position.x;
			if( feature_name == xs( "clothes_position[1]" ) ) string_str >> g_esp.clothes_position.y;
			
			if( feature_name == xs( "revive_key" ) ) string_str >> options::aimbot::exploits::time::revive_key;
			if( feature_name == xs( "fake_lag_key" ) ) string_str >> options::aimbot::exploits::time::fake_lag_key;
			if( feature_name == xs( "instant_revive" ) ) string_str >> options::aimbot::exploits::time::instant_revive;
			if( feature_name == xs( "fast_bow" ) ) string_str >> options::aimbot::exploits::time::fast_bow;
			if( feature_name == xs( "always_revive_target" ) ) string_str >> options::aimbot::exploits::time::always_revive_target;
			if( feature_name == xs( "rapid_fire_speed" ) ) string_str >> options::aimbot::exploits::time::rapid_fire_speed;
			if( feature_name == xs( "time_speed" ) ) string_str >> options::aimbot::exploits::time::time_speed;

			if( feature_name == xs( "no_viewmodel_bob" ) ) string_str >> options::aimbot::exploits::misc::no_viewmodel_bob;
			if( feature_name == xs( "no_lower" ) ) string_str >> options::aimbot::exploits::misc::no_lower;
			if( feature_name == xs( "no_flash" ) ) string_str >> options::aimbot::exploits::misc::no_flash;

			if( feature_name == xs( "grade_key" ) ) string_str >> options::aimbot::exploits::misc::grade_key;
			if( feature_name == xs( "pickup_key" ) ) string_str >> options::aimbot::exploits::misc::pickup_key;
			if( feature_name == xs( "codelock_key" ) ) string_str >> options::aimbot::exploits::misc::codelock_key;
			if( feature_name == xs( "auto_codelock" ) ) string_str >> options::aimbot::exploits::misc::auto_codelock;
			if( feature_name == xs( "code_lock_code" ) ) string_str >> options::aimbot::exploits::misc::code_lock_code;
			if( feature_name == xs( "max_lock_distance" ) ) string_str >> options::aimbot::exploits::misc::max_lock_distance;

			if( feature_name == xs( "auto_farm_trees" ) ) string_str >> options::aimbot::exploits::misc::auto_farm_trees;
			if( feature_name == xs( "auto_farm_only_hotspot" ) ) string_str >> options::aimbot::exploits::misc::auto_farm_only_hotspot;
			if( feature_name == xs( "auto_farm_ores" ) ) string_str >> options::aimbot::exploits::misc::auto_farm_ores;
			if( feature_name == xs( "auto_farm_barrels" ) ) string_str >> options::aimbot::exploits::misc::auto_farm_barrels;

			if( feature_name == xs( "always_pickup" ) ) string_str >> options::aimbot::exploits::misc::always_pickup;
			if( feature_name == xs( "always_codelock" ) ) string_str >> options::aimbot::exploits::misc::always_codelock;
			if( feature_name == xs( "always_grade" ) ) string_str >> options::aimbot::exploits::misc::always_grade;

			if( feature_name == xs( "add_friend_key" ) ) string_str >> options::add_friend_key;

			if( feature_name == xs( "keep_wounded_alive" ) ) string_str >> options::aimbot::exploits::misc::keep_wounded_alive;
			if( feature_name == xs( "always_hit_weak_spot" ) ) string_str >> options::aimbot::exploits::misc::always_hit_weak_spot;
			if( feature_name == xs( "long_neck" ) ) string_str >> options::aimbot::exploits::misc::long_neck;
			if( feature_name == xs( "long_neck_right" ) ) string_str >> options::aimbot::exploits::misc::long_neck_right;
			if( feature_name == xs( "long_neck_left" ) ) string_str >> options::aimbot::exploits::misc::long_neck_left;
			if( feature_name == xs( "disable_land_damage" ) ) string_str >> options::aimbot::exploits::misc::disable_land_damage;
			if( feature_name == xs( "fov_changer" ) ) string_str >> options::aimbot::exploits::misc::fov_changer;
			if( feature_name == xs( "zoom_fov" ) ) string_str >> options::aimbot::exploits::misc::zoom_fov;

			if( feature_name == xs( "font_flags" ) ) string_str >> options::font_flags;
			if( feature_name == xs( "auto_pickup_items" ) ) string_str >> options::aimbot::exploits::misc::auto_pickup_items;

			if( feature_name == xs( "suicide" ) ) string_str >> options::aimbot::exploits::misc::suicide;
			if( feature_name == xs( "fake_fire" ) ) string_str >> options::aimbot::exploits::misc::fake_fire;
			if( feature_name == xs( "fake_admin" ) ) string_str >> options::aimbot::exploits::misc::fake_admin;
			if( feature_name == xs( "fake_fire_on" ) ) string_str >> options::aimbot::exploits::misc::fake_fire_on;
			if( feature_name == xs( "debug_camera" ) ) string_str >> options::aimbot::exploits::misc::debug_camera;
			if( feature_name == xs( "spin_bot" ) ) string_str >> options::aimbot::exploits::misc::spin_bot;
			if( feature_name == xs( "gesture_spam" ) ) string_str >> options::aimbot::exploits::misc::gesture_spam;
			if( feature_name == xs( "interactive_debug" ) ) string_str >> options::aimbot::exploits::misc::interactive_debug;
			if( feature_name == xs( "disarm_landmines" ) ) string_str >> options::aimbot::exploits::misc::disarm_landmines;
			if( feature_name == xs( "stop_recycler" ) ) string_str >> options::aimbot::exploits::misc::stop_recycler;
			if( feature_name == xs( "long_neck_height" ) ) string_str >> options::aimbot::exploits::misc::long_neck_height;
			if( feature_name == xs( "long_neck_right_amount" ) ) string_str >> options::aimbot::exploits::misc::long_neck_right_amount;
			if( feature_name == xs( "delay_fake_fire" ) ) string_str >> options::aimbot::exploits::misc::delay_fake_fire;
			if( feature_name == xs( "long_neck_left_amount" ) ) string_str >> options::aimbot::exploits::misc::long_neck_left_amount;
			if( feature_name == xs( "zoom_fov_amount" ) ) string_str >> options::aimbot::exploits::misc::zoom_fov_amount;

			if( feature_name == xs( "fov_amount" ) ) string_str >> options::aimbot::exploits::misc::fov_amount;
			if( feature_name == xs( "view_left" ) ) string_str >> options::aimbot::exploits::misc::view_left;
			if( feature_name == xs( "view_right" ) ) string_str >> options::aimbot::exploits::misc::view_right;
			if( feature_name == xs( "view_height" ) ) string_str >> options::aimbot::exploits::misc::view_height;
			if( feature_name == xs( "zoom_key" ) ) string_str >> options::aimbot::exploits::misc::zoom_key;
			if( feature_name == xs( "fake_fire_key" ) ) string_str >> options::aimbot::exploits::misc::fake_fire_key;
			if( feature_name == xs( "gesture_type" ) ) string_str >> options::aimbot::exploits::misc::gesture_type;
			if( feature_name == xs( "debug_camera_key" ) ) string_str >> options::aimbot::exploits::misc::debug_camera_key;
			if( feature_name == xs( "suicide_key" ) ) string_str >> options::aimbot::exploits::misc::suicide_key;

			if( feature_name == xs( "pickup_everything" ) ) string_str >> options::aimbot::exploits::misc::pickup_everything;

			if( feature_name == xs( "max_grade_distance" ) ) string_str >> options::aimbot::exploits::misc::max_grade_distance;
			if( feature_name == xs( "max_item_distance" ) ) string_str >> options::aimbot::exploits::misc::max_item_distance;
			if( feature_name == xs( "max_collectible_distance" ) ) string_str >> options::aimbot::exploits::misc::max_collectible_distance;

			if( feature_name == xs( "auto_grade" ) ) string_str >> options::aimbot::exploits::misc::auto_grade;
			if( feature_name == xs( "grade_tier" ) ) string_str >> options::aimbot::exploits::misc::grade_tier;

			if( feature_name == xs( "aim_key" ) ) string_str >> g_aimbot.aim_key;

			if( feature_name == xs( "draw_visuals" ) ) string_str >> options::visuals::draw_visuals;
			if( feature_name == xs( "indicators" ) ) string_str >> options::visuals::indicators;
			if( feature_name == xs( "fly_hack_indicator" ) ) string_str >> options::visuals::fly_hack_indicator;
			if( feature_name == xs( "draw_tracers" ) ) string_str >> options::visuals::draw_tracers;
			if( feature_name == xs( "offscreen_arrows" ) ) string_str >> options::visuals::offscreen_arrows;
			if( feature_name == xs( "draw_radar" ) ) string_str >> options::visuals::draw_radar;
			if( feature_name == xs( "show_name" ) ) string_str >> options::visuals::show_name;
			if( feature_name == xs( "show_weapon" ) ) string_str >> options::visuals::show_weapon;
			if( feature_name == xs( "show_health" ) ) string_str >> options::visuals::show_health;
			if( feature_name == xs( "show_health_text" ) ) string_str >> options::visuals::show_health_text;
			if( feature_name == xs( "show_distance" ) ) string_str >> options::visuals::show_distance;
			if( feature_name == xs( "show_hotbar" ) ) string_str >> options::visuals::show_hotbar;
			if( feature_name == xs( "show_clothes" ) ) string_str >> options::visuals::show_clothes;
			if( feature_name == xs( "show_lines" ) ) string_str >> options::visuals::show_lines;
			if( feature_name == xs( "show_view_direction" ) ) string_str >> options::visuals::show_view_direction;
			if( feature_name == xs( "can_show_sleepers" ) ) string_str >> options::visuals::can_show_sleepers;
			if( feature_name == xs( "can_show_knocked" ) ) string_str >> options::visuals::can_show_knocked;
			if( feature_name == xs( "can_show_npc" ) ) string_str >> options::visuals::can_show_npc;
			if( feature_name == xs( "chams" ) ) string_str >> options::visuals::chams;
			if( feature_name == xs( "rgb_chams" ) ) string_str >> options::visuals::rgb_chams;
			if( feature_name == xs( "draw_bones" ) ) string_str >> options::visuals::draw_bones;
			if( feature_name == xs( "show_watermark" ) ) string_str >> options::visuals::show_watermark;
			if( feature_name == xs( "local_trails" ) ) string_str >> options::visuals::local_trails;
			if( feature_name == xs( "show_last_sent_tick" ) ) string_str >> options::visuals::show_last_sent_tick;
			if( feature_name == xs( "show_desync_bar" ) ) string_str >> options::visuals::show_desync_bar;
			if( feature_name == xs( "show_reload_bar" ) ) string_str >> options::visuals::show_reload_bar;
			if( feature_name == xs( "can_show_sleepers_oof" ) ) string_str >> options::visuals::can_show_sleepers_oof;
			if( feature_name == xs( "can_show_knocked_oof" ) ) string_str >> options::visuals::can_show_knocked_oof;
			if( feature_name == xs( "can_show_npc_oof" ) ) string_str >> options::visuals::can_show_npc_oof;
			if( feature_name == xs( "max_player_distance" ) ) string_str >> options::visuals::max_player_distance;
			if( feature_name == xs( "box_type" ) ) string_str >> options::visuals::box_type;
			if( feature_name == xs( "offscreen_distance" ) ) string_str >> options::visuals::offscreen_distance;

			if( feature_name == xs( "modify_rain" ) ) string_str >> options::visuals::world::modify_rain;
			if( feature_name == xs( "rain_amount" ) ) string_str >> options::visuals::world::rain_amount;

			if( feature_name == xs( "chams_color[0]" ) ) string_str >> options::visuals::chams_color.r;
			if( feature_name == xs( "chams_color[1]" ) ) string_str >> options::visuals::chams_color.g;
			if( feature_name == xs( "chams_color[2]" ) ) string_str >> options::visuals::chams_color.b;

			if( feature_name == xs( "chams_visible[0]" ) ) string_str >> options::visuals::chams_visible.r;
			if( feature_name == xs( "chams_visible[1]" ) ) string_str >> options::visuals::chams_visible.g;
			if( feature_name == xs( "chams_visible[2]" ) ) string_str >> options::visuals::chams_visible.b;

			if( feature_name == xs( "sky_color[0]" ) ) string_str >> options::visuals::world::sky_color.r;
			if( feature_name == xs( "sky_color[1]" ) ) string_str >> options::visuals::world::sky_color.g;
			if( feature_name == xs( "sky_color[2]" ) ) string_str >> options::visuals::world::sky_color.b;

			if( feature_name == xs( "show_chinook_helicopter" ) ) string_str >> options::visuals::world::show_chinook_helicopter;
			if( feature_name == xs( "show_patrol_helicopter" ) ) string_str >> options::visuals::world::show_patrol_helicopter;
			if( feature_name == xs( "show_attack_helicopter" ) ) string_str >> options::visuals::world::show_attack_helicopter;

			if( feature_name == xs( "color_chinook_helicopter[0]" ) ) string_str >> options::visuals::world::color_chinook_helicopter.r;
			if( feature_name == xs( "color_chinook_helicopter[1]" ) ) string_str >> options::visuals::world::color_chinook_helicopter.g;
			if( feature_name == xs( "color_chinook_helicopter[2]" ) ) string_str >> options::visuals::world::color_chinook_helicopter.b;

			if( feature_name == xs( "color_patrol_helicopter[0]" ) ) string_str >> options::visuals::world::color_patrol_helicopter.r;
			if( feature_name == xs( "color_patrol_helicopter[1]" ) ) string_str >> options::visuals::world::color_patrol_helicopter.g;
			if( feature_name == xs( "color_patrol_helicopter[2]" ) ) string_str >> options::visuals::world::color_patrol_helicopter.b;

			if( feature_name == xs( "color_attack_helicopter[0]" ) ) string_str >> options::visuals::world::color_attack_helicopter.r;
			if( feature_name == xs( "color_attack_helicopter[1]" ) ) string_str >> options::visuals::world::color_attack_helicopter.g;
			if( feature_name == xs( "color_attack_helicopter[2]" ) ) string_str >> options::visuals::world::color_attack_helicopter.b;

			if( feature_name == xs( "ambient_color[0]" ) ) string_str >> options::visuals::world::ambient_color.r;
			if( feature_name == xs( "ambient_color[1]" ) ) string_str >> options::visuals::world::ambient_color.g;
			if( feature_name == xs( "ambient_color[2]" ) ) string_str >> options::visuals::world::ambient_color.b;

			if( feature_name == xs( "show_stashes" ) ) string_str >> options::visuals::world::show_stashes;
			if( feature_name == xs( "todsky" ) ) string_str >> options::visuals::world::todsky;
			if( feature_name == xs( "show_grenades" ) ) string_str >> options::visuals::world::show_grenades;
			if( feature_name == xs( "night_stars" ) ) string_str >> options::visuals::world::night_stars;
			if( feature_name == xs( "clear_underwater" ) ) string_str >> options::visuals::world::clear_underwater;
			if( feature_name == xs( "change_world_color" ) ) string_str >> options::visuals::world::change_world_color;

			if( feature_name == xs( "show_heal" ) ) string_str >> options::visuals::world::show_heal;
			if( feature_name == xs( "show_weapons" ) ) string_str >> options::visuals::world::show_weapons;
			if( feature_name == xs( "show_melee_weapons" ) ) string_str >> options::visuals::world::show_melee_weapons;
			if( feature_name == xs( "show_everything" ) ) string_str >> options::visuals::world::show_everything;

			if( feature_name == xs( "show_item_amount" ) ) string_str >> options::visuals::world::show_item_amount;
			if( feature_name == xs( "stars_size" ) ) string_str >> options::visuals::world::stars_size;
			if( feature_name == xs( "stars" ) ) string_str >> options::visuals::world::stars;
			if( feature_name == xs( "ambient" ) ) string_str >> options::visuals::world::ambient;
			if( feature_name == xs( "mie_changer" ) ) string_str >> options::visuals::world::mie_changer;

			if( feature_name == xs( "rayleigh_changer" ) ) string_str >> options::visuals::world::rayleigh_changer;
			if( feature_name == xs( "brightness_changer" ) ) string_str >> options::visuals::world::brightness_changer;
			if( feature_name == xs( "aspect_changer" ) ) string_str >> options::visuals::world::aspect_changer;
			if( feature_name == xs( "aspect_value" ) ) string_str >> options::visuals::world::aspect_value;
			if( feature_name == xs( "show_sulfur_ore" ) ) string_str >> options::visuals::world::show_sulfur_ore;
			if( feature_name == xs( "show_metal_ore" ) ) string_str >> options::visuals::world::show_metal_ore;
			if( feature_name == xs( "show_stone_ore" ) ) string_str >> options::visuals::world::show_stone_ore;
			if( feature_name == xs( "show_box_storages" ) ) string_str >> options::visuals::world::show_box_storages;
			if( feature_name == xs( "show_tool_cupboard" ) ) string_str >> options::visuals::world::show_tool_cupboard;
			if( feature_name == xs( "show_sulfur_ore" ) ) string_str >> options::visuals::world::show_sulfur_ore;
			if( feature_name == xs( "show_metal_ore" ) ) string_str >> options::visuals::world::show_metal_ore;
			if( feature_name == xs( "show_stone_ore" ) ) string_str >> options::visuals::world::show_stone_ore;
			if( feature_name == xs( "show_vending_machine" ) ) string_str >> options::visuals::world::show_vending_machine;
			if( feature_name == xs( "show_drone" ) ) string_str >> options::visuals::world::show_drone;
			if( feature_name == xs( "show_recycler" ) ) string_str >> options::visuals::world::show_recycler;

			if( feature_name == xs( "show_tool_cupboard" ) ) string_str >> options::visuals::world::show_tool_cupboard;
			if( feature_name == xs( "show_oil_barrel" ) ) string_str >> options::visuals::world::show_oil_barrel;
			if( feature_name == xs( "show_regular_barrels" ) ) string_str >> options::visuals::world::show_regular_barrels;
			if( feature_name == xs( "show_underwater_crate" ) ) string_str >> options::visuals::world::show_underwater_crate;
			if( feature_name == xs( "show_elite_crate" ) ) string_str >> options::visuals::world::show_elite_crate;
			if( feature_name == xs( "show_military_crate" ) ) string_str >> options::visuals::world::show_military_crate;
			if( feature_name == xs( "show_bradley_crate" ) ) string_str >> options::visuals::world::show_bradley_crate;

			if( feature_name == xs( "show_helicopter_crate" ) ) string_str >> options::visuals::world::show_helicopter_crate;
			if( feature_name == xs( "show_hackable_locked_crate" ) ) string_str >> options::visuals::world::show_hackable_locked_crate;
			if( feature_name == xs( "show_normal_crate" ) ) string_str >> options::visuals::world::show_normal_crate;
			if( feature_name == xs( "show_chickens" ) ) string_str >> options::visuals::world::show_chickens;
			if( feature_name == xs( "show_small_crate" ) ) string_str >> options::visuals::world::show_small_crate;
			if( feature_name == xs( "show_mine_crate" ) ) string_str >> options::visuals::world::show_mine_crate;
			if( feature_name == xs( "show_tool_box" ) ) string_str >> options::visuals::world::show_tool_box;
			if( feature_name == xs( "show_tool_cupboard" ) ) string_str >> options::visuals::world::show_tool_cupboard;
			if( feature_name == xs( "show_boars" ) ) string_str >> options::visuals::world::show_boars;
			if( feature_name == xs( "show_wolves" ) ) string_str >> options::visuals::world::show_wolves;
			if( feature_name == xs( "show_horses" ) ) string_str >> options::visuals::world::show_horses;

			if( feature_name == xs( "show_sharks" ) ) string_str >> options::visuals::world::show_sharks;
			if( feature_name == xs( "show_deers" ) ) string_str >> options::visuals::world::show_deers;
			if( feature_name == xs( "show_polar_bears" ) ) string_str >> options::visuals::world::show_polar_bears;

			if( feature_name == xs( "show_bears" ) ) string_str >> options::visuals::world::show_bears;
			if( feature_name == xs( "show_sulfur_collectibles" ) ) string_str >> options::visuals::world::show_sulfur_collectibles;
			if( feature_name == xs( "show_metal_collectibles" ) ) string_str >> options::visuals::world::show_metal_collectibles;
			if( feature_name == xs( "show_wood_collectibles" ) ) string_str >> options::visuals::world::show_wood_collectibles;
			if( feature_name == xs( "show_stone_collectibles" ) ) string_str >> options::visuals::world::show_military_crate;

			if( feature_name == xs( "show_supply_signals" ) ) string_str >> options::visuals::world::show_supply_signals;
			if( feature_name == xs( "show_supply_drops" ) ) string_str >> options::visuals::world::show_supply_drops;
			if( feature_name == xs( "show_ammo_nails_arrows" ) ) string_str >> options::visuals::world::show_ammo_nails_arrows;

			if( feature_name == xs( "show_food_crate" ) ) string_str >> options::visuals::world::show_food_crate;
			if( feature_name == xs( "show_medical_crate" ) ) string_str >> options::visuals::world::show_medical_crate;


			if( feature_name == xs( "show_duo_submarine" ) ) string_str >> options::visuals::world::show_duo_submarine;
			if( feature_name == xs( "show_solo_submarine" ) ) string_str >> options::visuals::world::show_solo_submarine;
			if( feature_name == xs( "show_small_motorboat" ) ) string_str >> options::visuals::world::show_small_motorboat;

			if( feature_name == xs( "show_kayak" ) ) string_str >> options::visuals::world::show_kayak;

			if( feature_name == xs( "show_bradley_apc" ) ) string_str >> options::visuals::world::show_bradley_apc;
			if( feature_name == xs( "show_rhib" ) ) string_str >> options::visuals::world::show_rhib;
			if( feature_name == xs( "show_scrap_helicopter" ) ) string_str >> options::visuals::world::show_scrap_helicopter;
			if( feature_name == xs( "show_minicopter" ) ) string_str >> options::visuals::world::show_minicopter;
			if( feature_name == xs( "show_two_modules_car" ) ) string_str >> options::visuals::world::show_two_modules_car;
			if( feature_name == xs( "show_modular_car" ) ) string_str >> options::visuals::world::show_modular_car;

			if( feature_name == xs( "show_potatos" ) ) string_str >> options::visuals::world::show_potatos;
			if( feature_name == xs( "show_corns" ) ) string_str >> options::visuals::world::show_corns;
			if( feature_name == xs( "show_berrys" ) ) string_str >> options::visuals::world::show_berrys;
			if( feature_name == xs( "show_pumpkin" ) ) string_str >> options::visuals::world::show_pumpkin;
			if( feature_name == xs( "show_mushroom" ) ) string_str >> options::visuals::world::show_mushroom;
			if( feature_name == xs( "show_hemp" ) ) string_str >> options::visuals::world::show_hemp;

			if( feature_name == xs( "show_potatos" ) ) string_str >> options::visuals::world::show_potatos;
			if( feature_name == xs( "show_corns" ) ) string_str >> options::visuals::world::show_corns;
			if( feature_name == xs( "show_berrys" ) ) string_str >> options::visuals::world::show_berrys;
			if( feature_name == xs( "show_pumpkin" ) ) string_str >> options::visuals::world::show_pumpkin;
			if( feature_name == xs( "show_mushroom" ) ) string_str >> options::visuals::world::show_mushroom;
			if( feature_name == xs( "show_hemp" ) ) string_str >> options::visuals::world::show_hemp;

			if( feature_name == xs( "show_potatos" ) ) string_str >> options::visuals::world::show_potatos;
			if( feature_name == xs( "show_corns" ) ) string_str >> options::visuals::world::show_corns;
			if( feature_name == xs( "show_berrys" ) ) string_str >> options::visuals::world::show_berrys;
			if( feature_name == xs( "show_pumpkin" ) ) string_str >> options::visuals::world::show_pumpkin;
			if( feature_name == xs( "show_mushroom" ) ) string_str >> options::visuals::world::show_mushroom;
			if( feature_name == xs( "show_hemp" ) ) string_str >> options::visuals::world::show_hemp;

			if( feature_name == xs( "show_landmines" ) ) string_str >> options::visuals::world::show_landmines;
			if( feature_name == xs( "show_npc_turrets" ) ) string_str >> options::visuals::world::show_npc_turrets;
			if( feature_name == xs( "show_auto_turrets" ) ) string_str >> options::visuals::world::show_auto_turrets;
			if( feature_name == xs( "show_shotgun_traps" ) ) string_str >> options::visuals::world::show_shotgun_traps;
			if( feature_name == xs( "show_tesla_coil" ) ) string_str >> options::visuals::world::show_tesla_coil;

			if( feature_name == xs( "show_flame_turrets" ) ) string_str >> options::visuals::world::show_flame_turrets;
			if( feature_name == xs( "show_sam_site" ) ) string_str >> options::visuals::world::show_sam_site;
			if( feature_name == xs( "show_bear_trap" ) ) string_str >> options::visuals::world::show_bear_trap;

			if( feature_name == xs( "size_stars_amount" ) ) string_str >> options::visuals::world::size_stars_amount;
			if( feature_name == xs( "brightness_stars_amount" ) ) string_str >> options::visuals::world::brightness_stars_amount;
			if( feature_name == xs( "ambient_value" ) ) string_str >> options::visuals::world::ambient_value;
			if( feature_name == xs( "aspect_value" ) ) string_str >> options::visuals::world::aspect_value;
			if( feature_name == xs( "light_value" ) ) string_str >> options::visuals::world::light_value;
			if( feature_name == xs( "rayleigh_amount" ) ) string_str >> options::visuals::world::rayleigh_amount;
			if( feature_name == xs( "brightness_amount" ) ) string_str >> options::visuals::world::brightness_amount;
			if( feature_name == xs( "mie_amount" ) ) string_str >> options::visuals::world::mie_amount;

			if( feature_name == xs( "size_stars_amount" ) ) string_str >> options::visuals::world::size_stars_amount;
			if( feature_name == xs( "brightness_stars_amount" ) ) string_str >> options::visuals::world::brightness_stars_amount;
			if( feature_name == xs( "ambient_value" ) ) string_str >> options::visuals::world::ambient_value;
			if( feature_name == xs( "light_value" ) ) string_str >> options::visuals::world::light_value;
			if( feature_name == xs( "rayleigh_amount" ) ) string_str >> options::visuals::world::rayleigh_amount;
			if( feature_name == xs( "brightness_amount" ) ) string_str >> options::visuals::world::brightness_amount;
			if( feature_name == xs( "mie_amount" ) ) string_str >> options::visuals::world::mie_amount;

			// distance
			if( feature_name == xs( "max_cars_distance" ) ) string_str >> options::visuals::world::max_cars_distance;
			if( feature_name == xs( "max_barrels_distance" ) ) string_str >> options::visuals::world::max_barrels_distance;
			if( feature_name == xs( "max_ores_distance" ) ) string_str >> options::visuals::world::max_ores_distance;
			if( feature_name == xs( "max_grenade_distance" ) ) string_str >> options::visuals::world::max_grenade_distance;
			if( feature_name == xs( "max_food_collectibles_distance" ) ) string_str >> options::visuals::world::max_food_collectibles_distance;
			if( feature_name == xs( "max_container_distance" ) ) string_str >> options::visuals::world::max_container_distance;
			if( feature_name == xs( "max_corpse_distance" ) ) string_str >> options::visuals::world::max_corpse_distance;
			if( feature_name == xs( "max_vehicle_distance" ) ) string_str >> options::visuals::world::max_vehicle_distance;
			if( feature_name == xs( "max_ore_collectibles_distance" ) ) string_str >> options::visuals::world::max_ore_collectibles_distance;
			if( feature_name == xs( "max_respawn_points_distance" ) ) string_str >> options::visuals::world::max_respawn_points_distance;
			if( feature_name == xs( "max_helicopter_distance" ) ) string_str >> options::visuals::world::max_helicopter_distance;
		}
	}
	cfg_file.close( );
	std::cout << xs( "loaded file with name: " ) << filename << std::endl;
	options::load_cfg = false;
}
#pragma once
#include <string>

class c_cfg_sys {
public:
	void save_cfg( const std::string& filename );
	void load_cfg( const std::string& filename );
};

extern c_cfg_sys g_cfg;
    <ClInclude Include="core\vector\vector4.hpp" />
    <ClInclude Include="core\features\visuals\world_esp.hpp" />
    <ClInclude Include="core\utilities\lazy_importer.hpp" />#pragma once
#include "../../../includes/includes.hpp"

// pre-declare.
enum class key_code;

class c_framework
{
public:
	vec2_t cursor1 = vec2_t( ), cursor2 = vec2_t( ),
		size = vec2_t( ), position = vec2_t( );

	bool in_alpha{ };
	float x{ }, y{ };
	int selected_tab = 0;
	bool lmb{ }, rmb{ }, open{ true };
	float alpha{ 255.f };

	color_t background_color = color_t( 25, 25, 25, alpha ), 
		outline_color = color_t( 15, 15, 15, alpha ), text_color = color_t( 225, 225, 225, alpha ), elements_outline_color = color_t( 48, 48, 48, alpha );

	int max_width = 250;

	int active_picker = -1, active_hotkey = -1;
	int elements_count;
	bool pressed_key = false;

	void create_hotkey( std::string name, int* key, int child );
	void color_pixel( vec2_t pos, vec2_t size, color_t* original, color_t color );
	void color_picker( std::string name, color_t* color, int child );

	bool get_lmb( );

	vec2_t get_cursor( int child );

	bool get_rmb( );

	bool get_ins( );

	bool is_hovering( vec2_t position, vec2_t size );

	void create_tab( std::string name, int index, int offset );

	void create_label( std::string text, int child, bool centered = false );

	void create_combo_box( std::vector< std::string > list, int* selected, int child );

	void create_check_box( std::string name, bool* value, int child );

	void slider_float( std::string name, float* value, float min, float max, int child );
	void slider_int( std::string name, int* value, int min, int max, int child );

	void begin( );

	void end( );
};

extern c_framework g_framework;
#include "gui_framework.h"
#include "../../../game/sdk.hpp"
#include "../../options.h"
#include "../../aimbot/aimbot.h"

// create global definition of framework class.
c_framework g_framework;

bool c_framework::get_lmb( )
{
	static int delay = 0;

	if( g_sdk.get_key_down( key_code::Mouse0 ) 
		&& delay < 1 )
	{
		delay = 10;
		return true;
	}

	delay--;

	return false;
}

vec2_t c_framework::get_cursor( int child ) {
	switch( child ) {
	case 1:
		return cursor1;
		break;
	case 2:
		return cursor2;
		break;
	default:
		return cursor1;
		break;
	}

	// as default return cursor1
	return cursor1;
}

bool c_framework::get_rmb( )
{
	static int delay = 0;

	if( g_sdk.get_key_down( key_code::Mouse1 )
		&& delay < 1 )
	{
		delay = 10;
		return true;
	}

	delay--;

	return false;
}

bool c_framework::get_ins( )
{
	static int delay = 0;

	if( g_sdk.get_key_down( key_code::Insert )
		&& delay < 1 )
	{
		delay = 10;
		return true;
	}

	delay--;

	return false;
}

bool c_framework::is_hovering( vec2_t position, vec2_t size )
{
	vec3_t cursor = g_cheat.mouse_pos;
	cursor.y = ( g_cheat.screen_size.y - cursor.y );

	return ( cursor.x > position.x 
		&& cursor.x < ( position.x + size.x )
		&& cursor.y > position.y 
		&& cursor.y < ( position.y + size.y ) );
}

void c_framework::create_tab( std::string name, int index, int offset )
{
	auto hovering = is_hovering( vec2_t( position.x + 12, position.y + 33 + ( 45 * index ) ), vec2_t( 100, 35 ) );

	g_render.draw_filled_rect( vec4_t( position.x + 12, position.y + 33 + ( 45 * index ), 100, 35 ),
		selected_tab == index || hovering ? color_t( 25, 25, 25, alpha ) : color_t( 20, 20, 20, alpha ) );

	g_render.outline_box( vec2_t( position.x + 11, position.y + 32 + ( 45 * index ) ), vec2_t( 101, 36 ),
		elements_outline_color.alpha( alpha, true ) );

	g_render.draw_filled_rect( vec4_t( position.x + 11, position.y + 32 + ( 45 * index ), 2, 37 ),
		selected_tab == index ? options::accent_color.alpha( alpha, true ) :
		hovering ? color_t( 132, 142, 156, alpha ) : color_t( 25, 25, 25, alpha ) );

	if( hovering 
		&& lmb )
		selected_tab = index;

	g_render.draw_text( vec4_t( position.x + 12, position.y + 33 + ( 45 * index ), 100, 35 ), name, text_color.alpha( alpha, true ), true, 11, dropshadow );
}

void c_framework::create_label( std::string text, int child, bool centered )
{
	vec2_t cursor = get_cursor( child );

	g_render.draw_text( vec4_t( cursor.x, cursor.y - 2, 150, 20 ), text, text_color.alpha( alpha, true ), centered, 12, dropshadow );

	switch( child )
	{
	case 1:
		cursor1.y += 22;
		break;
	case 2:
		cursor2.y += 22;
		break;
	default:
		break;
	}
}
	
void c_framework::create_combo_box( std::vector< std::string > list, int* selected, int child )
{
	vec2_t cursor = get_cursor( child );

	const bool left_hovered = is_hovering( vec2_t( cursor.x, cursor.y - 3 ), vec2_t( 14, 20 ) );
	const bool right_hovered = is_hovering( vec2_t( cursor.x + 141, cursor.y - 2 ), vec2_t( 14, 20 ) );

	g_render.draw_text( vec4_t( cursor.x, cursor.y - 3, 150, 20 ), xs( "<" ),
		left_hovered ? color_t( 255, 245, 245 ) : text_color.alpha( alpha, true ), false, 11, dropshadow );

	g_render.draw_text( vec4_t( cursor.x, cursor.y - 2, 150, 20 ), list[ *selected ],
		text_color.alpha( alpha, true ), true, 11, dropshadow );

	g_render.draw_text( vec4_t( cursor.x + 141, cursor.y - 2, 150, 20 ), xs( ">" ),
		right_hovered ? color_t( 249, 255, 245 ) : text_color.alpha( alpha, true ), false, 11, dropshadow );

	int list_size = list.size( ) - 1;

	if( *selected < 1 
		&& left_hovered
		&& lmb )
	{	
		*selected = list_size;
	}
	else if( *selected > 0 
		&& left_hovered
		&& lmb )
	{	
		--* selected;
	}
	else if( *selected >= list_size
		&& right_hovered 
		&& lmb )
	{
		*selected = 0;
	}
	else if( *selected < list_size
		&& right_hovered 
		&& lmb )
	{
		++* selected;
	}
	else if( left_hovered
		&& rmb )
	{
		*selected = 0;
	}

	switch( child )
	{
	case 1:
		cursor1.y += 22;
		break;
	case 2:
		cursor2.y += 22;
		break;
	default:
		break;
	}
}

void c_framework::create_check_box( std::string name, bool* value, int child )
{
	vec2_t cursor = get_cursor( child );
			
	const bool hovered = is_hovering( vec2_t( cursor.x - 3, cursor.y - 2 ), vec2_t( 80, 16 ) );

	g_render.draw_filled_rect( vec4_t( cursor.x, cursor.y, 14, 14 ), color_t( 20, 20, 20, alpha ) );
	g_render.outline_box( vec2_t( cursor.x, cursor.y ), vec2_t( 14, 14 ), elements_outline_color.alpha( alpha, true ) );

	if( *value
		|| hovered )
		g_render.draw_filled_rect( vec4_t( cursor.x + 3, cursor.y + 3, 9, 9 ), *value ? options::accent_color.alpha( alpha, true ) : color_t( 132, 142, 156, alpha ) );

	g_render.draw_text( vec4_t( cursor.x + 19, cursor.y - 2, 150, 20 ), name, text_color.alpha( alpha, true ), false, 11 );

	if( hovered 
		&& lmb )
		*value = !*value;

	switch( child )
	{
	case 1:
		cursor1.y += 22;
		break;
	case 2:
		cursor2.y += 22;
		break;
	default:
		break;
	}
}

void c_framework::slider_float( std::string name, float* value, float min, float max, int child )
{
	vec2_t cursor = get_cursor( child );

	const float mouse_x = g_sdk.get_mouse_pos( ).x;

	const bool hovered = is_hovering( vec2_t( cursor.x - 1, cursor.y + 17 ), vec2_t( max_width + 2, 10 ) );

	g_render.draw_filled_rect( vec4_t( cursor.x, cursor.y + 15, max_width, 4 ), background_color.alpha( alpha, true ) );
	g_render.outline_box( vec2_t( cursor.x, cursor.y + 15 ), vec2_t( max_width, 4 ), elements_outline_color.alpha( alpha, true ) );

	float to_set = ( ( mouse_x - cursor.x ) / max_width * max );

	*value = std::clamp( *value, min, max );

	if( hovered 
		&& g_sdk.get_key( key_code::Mouse0 ) )
		*value = to_set;

	if( *value > 0.f ) {
		g_render.draw_filled_rect( vec4_t( cursor.x + 2, cursor.y + 17, ( ( ( hovered ? to_set : *value ) * max_width ) / max ) - 2, 2 ),
			hovered ? color_t( 132, 142, 156 ).alpha( alpha, true ) : options::accent_color.alpha( alpha, true ) );
	}

	std::string normal_value = g_math.remove_trailing_zeros( hovered ? to_set : *value );

	g_render.draw_text( vec4_t( cursor.x, cursor.y - 4, 150, 20 ), name, text_color.alpha( alpha, true ), false, 11, dropshadow );
	g_render.draw_text( vec4_t( cursor.x + max_width - 15, cursor.y - 4, 150, 20 ), 
		normal_value.c_str( ),
		text_color.alpha( alpha, true ), false, 11, dropshadow );
		
	switch( child )
	{
	case 1:
		cursor1.y += 23;
		break;
	case 2:
		cursor2.y += 23;
		break;
	default:
		break;
	}
}

void c_framework::slider_int( std::string name, int* value, int min, int max, int child )
{
	vec2_t cursor = get_cursor( child );

	const float mouse_x = g_sdk.get_mouse_pos( ).x;

	const bool hovered = is_hovering( vec2_t( cursor.x - 1, cursor.y + 17 ), vec2_t( max_width + 2, 10 ) );

	g_render.draw_filled_rect( vec4_t( cursor.x, cursor.y + 15, max_width, 4 ), background_color.alpha( alpha, true ) );
	g_render.outline_box( vec2_t( cursor.x, cursor.y + 15 ), vec2_t( max_width, 4 ), elements_outline_color.alpha( alpha, true ) );

	int to_set = static_cast< int >( ( mouse_x - cursor.x ) / max_width * max );

	static int delay = 0;
	if( delay > 1 )
		--delay;

	*value = std::clamp( *value, min, max );

	if( hovered 
		&& g_sdk.get_key( key_code::Mouse0 ) )
		*value = to_set;

	if( *value > 0 ) {
		g_render.draw_filled_rect( vec4_t( cursor.x + 2, cursor.y + 17, ( ( ( hovered ? to_set : *value ) * max_width ) / max ) - 2, 2 ),
			hovered ? color_t( 132, 142, 156, alpha ) : options::accent_color.alpha( alpha, true ) );
	}

	std::string normal_value = std::to_string( hovered ? to_set : *value );

	g_render.draw_text( vec4_t( cursor.x, cursor.y - 4, 150, 20 ), name, text_color.alpha( alpha, true ), false, 11, dropshadow );
	g_render.draw_text( vec4_t( cursor.x + max_width - 15, cursor.y - 4, 150, 20 ), 
		normal_value.c_str( ),
		text_color.alpha( alpha, true ), false, 11, dropshadow );
		
	switch( child )
	{
	case 1:
		cursor1.y += 23;
		break;
	case 2:
		cursor2.y += 23;
		break;
	default:
		break;
	}
}

void c_framework::create_hotkey( std::string name, int* key, int child )
{
	elements_count++;

	vec2_t size = vec2_t( 50.f, 23.f );

	vec2_t cursor = get_cursor( child );

	vec2_t pos = cursor;

	const bool hovered = is_hovering( pos, size );
	const bool pressed_lmb = lmb;

	std::string text = name + ": " + "[" + g_aimbot.get_key_from_combo( *key ) + "]";

	if( active_hotkey == elements_count )
	{
		text = name + ": " + "[~]";

		if( !g_sdk.get_key( key_code::Mouse0	) )
			pressed_key = false;

		if( !pressed_key )
		{
			for( int code = 0; code < ( int )key_code::Mouse6; code++ ) {
				if( g_sdk.get_key( code ) ) { 
					*key = code;
					active_hotkey = -1;
				}
			}
		}
	}
	else
	{
		if( pressed_lmb ) {
			if( hovered )
			{
				pressed_key = true;
				active_hotkey = elements_count;
			}
		}
	}
	g_render.draw_text( vec4_t( pos.x + 3.f, pos.y, 150, 20 ), text, text_color.alpha( alpha, true ), false, 11 );

	switch( child )
	{
	case 1:
		cursor1.y += 23;
		break;
	case 2:
		cursor2.y += 23;
		break;
	default:
		break;
	}
}

void c_framework::color_pixel( vec2_t pos, vec2_t size, color_t* original, color_t color )
{		
	g_render.draw_filled_rect( pos, size, color );

	const bool hovered = is_hovering( pos, size );

	if( original->r == color.r && original->g == color.g && original->b == color.b )
		g_render.outline_box( pos, size, color_t( 0.f, 0.f, 0.f, alpha ) );

	if( hovered ) {
		g_render.outline_box( pos, size, color_t( 45, 45, 45, alpha ) );

		if( g_sdk.get_key( key_code::Mouse0 ) )
			*original = color;
	}
}

void c_framework::color_picker( std::string name, color_t* color, int child )
{
	++elements_count;

	// set this to full alpha.
	color->a = 255.f;

	vec2_t size = vec2_t( 11, 11 );

	vec2_t cursor = get_cursor( child );

	vec2_t pos = cursor;

	const bool hovered = is_hovering( pos, size );
		
	g_render.draw_filled_rect( vec4_t( pos.x, pos.y, 14, 14 ), hovered ? color_t( 40, 40, 40, alpha ) : background_color.alpha( alpha, true ) );

	color_t render_color = *color;
	g_render.draw_filled_rect( vec4_t( pos.x + 3, pos.y + 3, 9, 9 ), render_color.alpha( alpha, true ) );

	g_render.outline_box( vec2_t( pos.x, pos.y ), vec2_t( 14, 14 ), hovered ? color_t( 25, 25, 25, alpha ) : elements_outline_color.alpha( alpha, true ) );

	g_render.draw_text( vec4_t( pos.x + size.x + 8.f, pos.y - 2.f, 150, 20 ), name, text_color.alpha( alpha, true ), false, 11 );

	if( active_picker == elements_count )
	{
		vec2_t color_size = vec2_t( 125, 125 );

		bool hover_picker = is_hovering( pos, vec2_t( color_size.x, color_size.y - 60 ) );

		vec2_t pixel_size = vec2_t( color_size.x / 12, color_size.y / 12 );
		pos.x += 90;

		g_render.draw_filled_rect( vec4_t( pos.x + pixel_size.x, pos.y + pixel_size.y, pixel_size.x * 9, pixel_size.y * 9 ), color_t( 40, 40, 40, alpha ) );

		g_render.outline_box( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y ), vec2_t( pixel_size.x * 9, pixel_size.y * 9 ), elements_outline_color.alpha( alpha, true ) );

		//0
		{
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y ), pixel_size, color, color_t( 174, 235, 253, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 136, 225, 251, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 108, 213, 250, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 89, 175, 213, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 76, 151, 177, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 60, 118, 140, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 43, 85, 100, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 32, 62, 74, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 255, 255, 255, alpha ) );
		}
		//1
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y ), pixel_size, color, color_t( 175, 205, 252, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 132, 179, 252, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 90, 152, 250, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 55, 120, 250, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 49, 105, 209, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 38, 83, 165, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 28, 61, 120, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 20, 43, 86, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 1, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 247, 247, 247, alpha ) );
		}
		//2
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y ), pixel_size, color, color_t( 153, 139, 250, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 101, 79, 249, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 64, 50, 230, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 54, 38, 175, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 39, 31, 144, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 32, 25, 116, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 21, 18, 82, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 16, 13, 61, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 2, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 228, 228, 228, alpha ) );
		}
		//3
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y ), pixel_size, color, color_t( 194, 144, 251, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 165, 87, 249, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 142, 57, 239, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 116, 45, 184, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 92, 37, 154, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 73, 29, 121, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 53, 21, 88, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 37, 15, 63, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 3, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 203, 203, 203, alpha ) );
		}
		//4
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y ), pixel_size, color, color_t( 224, 162, 197, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 210, 112, 166, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 199, 62, 135, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 159, 49, 105, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 132, 41, 89, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 104, 32, 71, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 75, 24, 51, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 54, 14, 36, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 4, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 175, 175, 175, alpha ) );
		}
		//5
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y ), pixel_size, color, color_t( 235, 175, 176, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 227, 133, 135, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 219, 87, 88, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 215, 50, 36, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 187, 25, 7, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 149, 20, 6, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 107, 14, 4, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 77, 9, 3, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 5, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 144, 144, 144, alpha ) );
		}
		//6
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y ), pixel_size, color, color_t( 241, 187, 171, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 234, 151, 126, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 229, 115, 76, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 227, 82, 24, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 190, 61, 15, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 150, 48, 12, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 107, 34, 8, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 79, 25, 6, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 6, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 113, 113, 113, alpha ) );
		}
		//7
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y ), pixel_size, color, color_t( 245, 207, 169, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 240, 183, 122, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 236, 159, 74, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 234, 146, 37, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 193, 111, 28, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 152, 89, 22, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 110, 64, 16, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 80, 47, 12, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 7, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 82, 82, 82, alpha ) );
		}
		//8
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y ), pixel_size, color, color_t( 247, 218, 170, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 244, 200, 124, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 241, 182, 77, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 239, 174, 44, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 196, 137, 34, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 154, 108, 27, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 111, 77, 19, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 80, 56, 14, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 8, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 54, 54, 54, alpha ) );
		}
		//9
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y ), pixel_size, color, color_t( 254, 243, 187, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 253, 237, 153, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 253, 231, 117, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 254, 232, 85, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 242, 212, 53, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 192, 169, 42, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 138, 120, 30, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 101, 87, 22, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 9, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 29, 29, 29, alpha ) );
		}
		//10
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y ), pixel_size, color, color_t( 247, 243, 185, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 243, 239, 148, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 239, 232, 111, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 235, 229, 76, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 208, 200, 55, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 164, 157, 43, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 118, 114, 31, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 86, 82, 21, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 10, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 9, 9, 9, alpha ) );
		}
		//11
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y ), pixel_size, color, color_t( 218, 232, 182, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 198, 221, 143, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 181, 210, 103, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 154, 186, 76, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 130, 155, 64, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 102, 121, 50, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 74, 88, 36, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 54, 64, 26, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 11, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 0, 0, 0, alpha ) );
		}
		//12
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y ), pixel_size, color, color_t( 225, 255, 125, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 170, 161, 255, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 161, 255, 252, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 127, 252, 73, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 255, 84, 54, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 255, 138, 54, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 255, 54, 54, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 54, 87, 255, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 12, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 0, 255, 187, alpha ) );
		}
		//12
		{
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y ), pixel_size, color, color_t( 255, 0, 255, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y * 2 ), pixel_size, color, color_t( 255, 255, 0, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y * 3 ), pixel_size, color, color_t( 0, 255, 255, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y * 4 ), pixel_size, color, color_t( 0, 255, 0, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y * 5 ), pixel_size, color, color_t( 255, 0, 125, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y * 6 ), pixel_size, color, color_t( 125, 0, 255, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y * 7 ), pixel_size, color, color_t( 125, 125, 255, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y * 8 ), pixel_size, color, color_t( 255, 125, 125, alpha ) );
			color_pixel( vec2_t( pos.x + pixel_size.x * 13, pos.y + pixel_size.y * 9 ), pixel_size, color, color_t( 255, 255, 125, alpha ) );
		}

		if( !hover_picker 
			&& lmb )
			active_picker = -1;	
	}
	else
	{
		if( hovered 
			&& lmb )
			active_picker = elements_count;
	}

	switch( child )
	{
	case 1:
		cursor1.y += 21;
		break;
	case 2:
		cursor2.y += 21;
		break;
	default:
		break;
	}
}

void c_framework::begin( )
{
	vec3_t cursor = g_cheat.mouse_pos;

	if( g_sdk.get_key( key_code::Mouse0 ) 
		&& is_hovering( position, vec2_t( size.x, 25 ) ) )
	{
		cursor.y = g_cheat.screen_size.y - cursor.y;

		x = cursor.x - size.x / 2.f;
		y = cursor.y - 10.f;
	}

	elements_count = 0;

	// background
	g_render.draw_filled_rect( vec4_t( position.x, position.y + 28, size.x + 180, size.y ), outline_color.alpha( alpha, true ) );
	g_render.outline_box( vec2_t( position.x, position.y + 28 ), vec2_t( size.x + 180, size.y ), options::accent_color.alpha( alpha, true ) );

	// separator line
	g_render.draw_filled_rect( vec4_t( position.x + 125, position.y + 29, 2, size.y - 2 ), color_t( 20, 20, 20, alpha ) );
	g_render.outline_box( vec2_t( position.x + 125, position.y + 29 ), vec2_t( 2, size.y - 2 ), color_t( 50, 50, 50, alpha ) );

	// first sub-tab.
	g_render.draw_filled_rect( vec4_t( position.x + 135, position.y + 35, 300, size.y - 13 ), color_t( 15, 15, 15, alpha ) );
	g_render.outline_box( vec2_t( position.x + 135, position.y + 34 ), vec2_t( 300, size.y - 14 ), elements_outline_color.alpha( alpha, true ) );

	// second sub-tab.
	g_render.draw_filled_rect( vec4_t( position.x + 440, position.y + 35, 300, size.y - 13 ), color_t( 15, 15, 15, alpha ) );
	g_render.outline_box( vec2_t( position.x + 440, position.y + 34 ), vec2_t( 300, size.y - 14 ), elements_outline_color.alpha( alpha, true ) );
}

void c_framework::end( )
{
	static bool has_initializated = false;

	size = vec2_t( 575, 855 );
	if( !has_initializated ) {
		if( !g_cheat.screen_size.is_zero( ) ) {
			x = g_cheat.screen_size.x / 2.f - size.x;
			y = g_cheat.screen_size.y / 2.f;
		}
		has_initializated = true;
	}
	position = vec2_t( x, y );

	lmb = get_lmb( );#pragma once
#include "../../includes/includes.hpp"
#include "../../game/sdk.hpp"
#include "world_esp.hpp"

class c_esp
{
public:
	vec3_t manipulation_angle{ }, eye_manipulation_angle{ };
	core::bounds_t bbox{ };
	bool not_in_fly_action{ true };

	float maximum_eye_height{ }, melee_max_dist{ };

	font_flags_t font_flags{ };

	float indicators_spacing[ 2 ];
	float esp_spacing[ 6 ]; // uses 0 for weapon, then goes health, distance, show team id, knocked flag, ducking flag;

	color_t name_color{ 255, 255, 255 }, box_color{ 255, 255, 255 },
		skeleton_color{ 255, 255, 255 }, radar_color{ },
		oof_color{ 255, 255, 255 }, snap_lines_color{ 255, 255, 255 }, distance_color{ 255, 255, 255 }, weapon_color{ 255, 255, 255 },
		view_direction_color{ 255, 255, 255 }, knocked_color{ 0, 255, 0 }, ducking_color{ 255, 0, 0 },
		custom_health_color{ 255, 255, 255 }, health_text_color{ 255, 255, 255 };

	/* fly-hack violation related */
	float distance_vertical = 0.f, distance_horizontal = 0.f;
	float pause_time = 0.f;
	float current_horizontal_fly = 0.f, max_horizontal_fly = 0.f;
	float current_vertical_fly = 0.f, max_vertical_fly = 0.f;

	// for clothing / hotbars.
	bool  should_use_spacing{ };

	struct shot_record_t
	{
		float m_time{ };
		vec3_t m_start{ }, m_end{ };
		core::base_player* entity{ };
	};

	struct saved_position
	{
		bool is_home{ };
		vec3_t m_location{ };
		color_t color{ };
	};

	std::vector< saved_position > m_positions;

	std::vector< shot_record_t > m_shots;
	std::vector< core::base_player* > m_friends;

	void render_saved_positions( );
	void change_sky_ambient_color( );

	void draw_bullet_tracers( );

	void invoke_chams( core::base_player* );
	void draw_snap_lines( core::base_player* );
	void draw_health_text( core::base_player* );
	void draw_weapon( core::base_player* );
	void reset_fly_hack( );
	void draw_distance( core::base_player* );

	vec2_t radar_position = vec2_t( 20, 20 );
	vec2_t hotbar_position = vec2_t( 20, 20 );
	vec2_t clothes_position = vec2_t( 20, 20 );

	vec2_t info_bar_size = vec2_t( 175, 190 );

	void find_manipulate_angle( );
	
    void draw_knocked_flag( core::base_player* player );
    void draw_ducking_flag( core::base_player* player );

	void draw_name( core::base_player*, entity_type );
	void draw_box( core::base_player* );
    void draw_health( core::base_player* );
	void draw_hotbar( core::base_player* target );
	void draw_clothes( core::base_player* target );
	void draw_bones( core::base_player* );
	void draw_radar( core::base_player* );
	void draw_local_trails( );
	void draw_last_sent_tick( );

	void draw_out_of_fov_arrows( core::base_player* );
	void draw_view_direction( core::base_player* );

	void context_instance( core::base_player*, entity_type );

	void apply_fly_violation( );

	void fly_hack_bar( );
	void show_reload_bar( );
	void show_desync_bar( );

	core::base_entity* get_closest_object_of_class( std::string class_to_find, float max_dist = 250.f );
	void do_melee_attack( vec3_t pos, core::base_entity* entity, bool is_player = false );
};

extern c_esp g_esp;
#include "world_esp.hpp"
#include "esp.h"
#include "../options.h"
#include "../../includes/fnv1a.hpp"
#include "../../utilities/memory.hpp"
#include "../../game/offsets.hpp"

// create global definition for world class.
c_world_esp g_world;

void c_world_esp::render( vec4_t render_position, std::string class_name,
	std::string obj_name, int distance, core::base_combat_entity* combat_entity,
	event_type event, core::base_entity* base_entity )
{
	if( !options::visuals::world::master_switch 
		|| event != event_type::re_paint
		|| distance >= 5000 )
		return;

	std::string dist_str = std::to_string( static_cast< int >( distance ) );
	std::string text = std::string( );
	color_t color = color_t( 0, 0, 0, 0 );

	float closest_distance = FLT_MAX;
		
	core::base_player* local = g_cheat.local;
	if( !local )
		return;

	static float last_sent_tick = local->lastSentTickTime( );

	//g_render.draw_text( render_position, obj_name, color_t( 255, 255, 255 ) );
	if( options::visuals::prefab_name_debug ) {
		render_position.y += 15;
		g_render.draw_text( render_position, obj_name, color_t( 255, 255, 255 ), false, 10, g_esp.font_flags );
		render_position.y -= 15;
	}

	if( options::visuals::class_name_debug ) {
		render_position.y += options::visuals::prefab_name_debug ? 30 : 15;

		g_render.draw_text( vec4_t( render_position.x, render_position.y + 40, render_position.z, render_position.w ), 
			class_name, color_t( 255 ,255, 255 ), false, 10, g_esp.font_flags );

		render_position.y -= options::visuals::prefab_name_debug ? 30 : 15;
	}

	if( distance < options::visuals::world::max_grenade_distance
		&& options::visuals::world::show_grenades ) {
		if( strstr( obj_name.c_str( ), xs( "grenade.f1.deployed.prefab" ) ) )
		{
			color = color_t( 177, 232, 95 );
			text = xs( "f1 grenade" );
		}
		if( strstr( obj_name.c_str( ), xs( "grenade.flashbang.deployed.prefab" ) ) )
		{
			color = color_t( 165, 183, 201 );
			text = xs( "flashbang" );
		}
		if( strstr( obj_name.c_str( ), xs( "grenade.molotov.deployed.prefab" ) ) )
		{
			color = color_t( 199, 138, 74 );
			text = xs( "molotov" );
		}
		if( strstr( obj_name.c_str( ), xs( "grenade.beancan.deployed.prefab" ) ) )
		{
			color = color_t( 220, 220, 220 );
			text = xs( "bean can" );
		}
	}
	if( distance < options::visuals::world::max_corpse_distance ) {
		bool npc_corpse = class_name == xs( "NPCPlayerCorpse" );
		if( ( class_name == xs( "PlayerCorpse" ) || npc_corpse )
			&& options::visuals::world::show_corpse )
		{
			color = options::visuals::world::color_corpse;
			text = npc_corpse ? xs( "npc corpse" ) : xs( "player corpse" );
		}
		if( strstr( obj_name.c_str( ), xs( "item_drop_backpack.prefab" ) )
			&& options::visuals::world::show_backpack )
		{
			color = options::visuals::world::color_backpack;
			text = xs( "backpack" );
		}
	}
	if( distance < options::visuals::world::max_ores_distance
		&& class_name == xs( "OreResourceEntity" ) ) {
		if( ( strstr( obj_name.c_str( ), xs( "metal-ore.prefab" ) )
			|| strstr( obj_name.c_str( ), xs( "ore_metal.prefab" ) ) )
			&& options::visuals::world::show_metal_ore ) {
			color = options::visuals::world::color_metal_ore;
			text = xs( "metal ore" );
		}
		else if( ( strstr( obj_name.c_str( ), xs( "sulfur-ore.prefab" ) )
			|| strstr( obj_name.c_str( ), xs( "ore_sulfur.prefab" ) ) )
			&& options::visuals::world::show_sulfur_ore ) {
			color = options::visuals::world::color_sulfur_ore;
			text = xs( "sulfur ore" );
		}
		else if( ( strstr( obj_name.c_str( ), xs( "stone-ore.prefab" ) )
			|| strstr( obj_name.c_str( ), xs( "ore_stone.prefab" ) ) )
			&& options::visuals::world::show_stone_ore ) {
			color = options::visuals::world::color_stone_ore;
			text = xs( "stone ore" );
		}
	}
	if( distance < options::visuals::world::max_item_distance ) {
		core::item* item = base_entity->get_world_item( );
		if( item ) {
			if( class_name == xs( "DroppedItem" ) )
			{
				int item_amt = item->get_amount( );
				std::string item_amount = std::to_string( item_amt );

				text = g_sdk.ws2s( item->get_weapon_name( ) );
				if( options::visuals::world::show_item_amount 
					&& item_amt > 1 )
					text += ( " x" ) + item_amount;

				if( text.find( "arrow" ) != std::string::npos 
					|| text.find( "nails" ) != std::string::npos ) {
					color = color_t( 143, 165, 199 );
					if( !options::visuals::world::show_ammo_nails_arrows )
						return;
				}
				else if( item->is_gun( ) ) {
					color = color_t( 145, 187, 255 );
					if( !options::visuals::world::show_weapons )
						return;
				}
				else if( item->is_melee( ) ) {
					color = color_t( 145, 156, 255 );
					if( !options::visuals::world::show_melee_weapons )
						return;
				}
				else if( item->is_heal( )
					&& !options::visuals::world::show_heal ) {
					color = color_t( 188, 255, 112 );
					return;
				}
				else if( !options::visuals::world::show_everything ) {
					color = color_t( 230, 247, 255 );
					return;
				}
				else if( text.find( "scrap" ) != std::string::npos )
					color = color_t( 222, 113, 60 );
				else if( text.find( "ammo" ) != std::string::npos ) {
					if( text.find( "incendiary" ) != std::string::npos )
						color = color_t( 255, 169, 112 );
					else if( text.find( "hv" ) != std::string::npos )
						color = color_t( 112, 169, 255 ); 
					else if( text.find( "explosive" ) != std::string::npos )
						color = color_t( 255, 119, 28 );
					else 
						color = color_t( 159, 167, 196 );
				}
				else if( text.find( "blue" ) != std::string::npos )
					color = color_t( 173, 199, 255 );
				else if( text.find( "white" ) != std::string::npos )
					color = color_t( 255, 255, 255 );
				else if( text.find( "green" ) != std::string::npos )
					color = color_t( 199, 255, 173 );
				else if( text.find( "red" ) != std::string::npos )
					color = color_t( 255, 110, 139 );
				else if( text.find( "purple" ) != std::string::npos )
					color = color_t( 156, 110, 255 );
				else if( text.find( "yellow" ) != std::string::npos )
					color = color_t( 217, 197, 95 );
				else
					color = color_t( 217, 237, 255 );
			}
		}
		if( class_name == xs( "Drone" )
			&& options::visuals::world::show_drone )
		{
			color = options::visuals::world::color_drone;
			text = xs( "drone" );
		}
		if( class_name == xs( "Recycler" ) )
		{  
			if( base_entity 
				&& options::aimbot::exploits::misc::stop_recycler
				&& distance < 5.f 
				&& ( local->lastSentTickTime( ) - last_sent_tick ) > 2.5 ) {
				base_entity->server_rpc( "SVSwitch" );
				last_sent_tick = local->lastSentTickTime( );
			}

			if( options::visuals::world::show_recycler ) {
				color = options::visuals::world::color_recycler;
				text = xs( "recycler" );
			}
		}
	}
	if( distance < options::visuals::world::max_respawn_points_distance )
	{
		if( class_name == xs( "SleepingBag" ) )
		{
			color = color_t( 175, 175, 175 );
			text = xs( "sleeping bag" );
		}
		if( strstr( obj_name.c_str( ), "bed_deployed.prefab" ) )
		{
			color = color_t( 225, 225, 225 );
			text = xs( "bed" );
		}
	}
	if( distance < options::visuals::world::max_raid_distance )
	{
		if( strstr( obj_name.c_str( ), "c4_explosion.prefab" ) ) {
			text = xs( "c4" );
			color = color_t( 255, 0, 0 );
		}
		else if( strstr( obj_name.c_str( ), xs( "satchel-charge-explosion.prefab" ) ) ) {
			text = xs( "satchel" );
			color = color_t( 242, 164, 63 );
		}
		else if( strstr( obj_name.c_str( ), xs( "beancan_grenade_explosion.prefab" ) ) ) {
			text = xs( "bean can grenade" );
			color = color_t( 255, 114, 59 );
		}
		else if( strstr( obj_name.c_str( ), xs( "rocket_explosion.prefab" ) ) ) {
			text = xs( "rocket" );
			color = color_t( 255, 114, 59 );
		}
	}
	if( distance < options::visuals::world::max_container_distance )
	{
		if( class_name == xs( "HackableLockedCrate" )
			&& options::visuals::world::show_hackable_locked_crate )
		{
			text = xs( "hackable crate" );
			color = options::visuals::world::color_hackable_locked_crate;
		}
		else if( class_name == xs( "LootContainer" ) )
		{
			if( strstr( obj_name.c_str( ), xs( "crate_elite.prefab" ) )
				&& options::visuals::world::show_elite_crate )
			{
				text = xs( "elite crate" );
				color = options::visuals::world::color_elite_crate;
			}
			else if( strstr( obj_name.c_str( ), xs( "crate_basic.prefab" ) )
				&& options::visuals::world::show_small_crate )
			{
				text = xs( "small crate" );
				color = options::visuals::world::color_small_crate;
			}
			else if( strstr( obj_name.c_str( ), xs( "crate_normal_2.prefab" ) )
				&& options::visuals::world::show_normal_crate )
			{
				text = xs( "crate" );
				color = options::visuals::world::color_normal_crate;
			}
			else if( strstr( obj_name.c_str( ), xs( "crate_underwater_advanced.prefab" ) )
				&& options::visuals::world::show_underwater_crate )
			{
				text = xs( "advanced underwater crate" );
				color = color_t( 3, 136, 252 );

				if( options::aimbot::exploits::misc::auto_untie_crates
					&& distance < 5.f )
					base_entity->server_rpc( xs( "RPC_FreeCrate" ) ); 
			}
			else if( strstr( obj_name.c_str( ), xs( "crate_underwater_basic.prefab" ) )
				&& options::visuals::world::show_underwater_crate )
			{
				text = xs( "underwater crate" );
				color = color_t( 113, 159, 199 );

				if( options::aimbot::exploits::misc::auto_untie_crates
					&& distance < 5.f )
					base_entity->server_rpc( xs( "RPC_FreeCrate" ) ); 
			}
			else if( strstr( obj_name.c_str( ), xs( "crate_tools.prefab" ) )
				&& options::visuals::world::show_tool_box )
			{
				text = xs( "toolbox" );
				color = options::visuals::world::color_tool_box;
			}
			else if( strstr( obj_name.c_str( ), xs( "crate_normal.prefab" ) )
				&& options::visuals::world::show_military_crate )
			{
				text = xs( "military crate" );
				color = options::visuals::world::color_military_crate;
			}
			else if( ( strstr( obj_name.c_str( ), xs( "minecart.prefab" ) ) )
				&& options::visuals::world::show_mine_crate )
			{
				text = xs( "mine crate" );
				color = options::visuals::world::color_mine_crate;
			}
			else if( ( strstr( obj_name.c_str( ), xs( "crate_foodbox.prefab" ) ) 
				|| strstr( obj_name.c_str( ), xs( "crate_normal_2_food.prefab" ) ) )
				&& options::visuals::world::show_food_crate )
			{
				text = xs( "food crate" );
				color = options::visuals::world::color_food_crate;
			}
			//else if( strstr( obj_name.c_str( ), xs( "crate_bradley.prefab" ) ) )
			//{
			//	text = xs( "bradley crate" );
			//	color = color_t( 206, 255, 150 ) ;
			//}
			//else if( strstr( obj_name.c_str( ), xs( "codelockedhackablecrate.prefab" ) ) )
			//{
			//	text = xs( "hackable crate" );
			//	color = color_t( 206, 255, 150 ) ;
			//}
			//else if( strstr( obj_name.c_str( ), xs( "codelockedhackablecrate_oilrig.prefab" ) ) )
			//{
			//	text = xs( "hackable oil-rig crate" );
			//	color = color_t( 206, 255, 150 ) ;
			//}
			else if( strstr( obj_name.c_str( ), xs( "crate_normal_2_medic.prefab" ) )
				&& options::visuals::world::show_medical_crate )
			{
				text = xs( "medic crate" );
				color = options::visuals::world::color_medical_crate;
			}
			//else if( strstr( obj_name.c_str( ), xs( "codelockedhackablecrate.prefab" ) ) )
			//{
			//	text = xs( "hackable crate" );
			//	color = color_t( 206, 255, 150 ) ;
			//}
			//else if( strstr( obj_name.c_str( ), xs( "codelockedhackablecrate_oilrig.prefab" ) ) )
			//{
			//	text = xs( "hackable oil-rig crate" );
			//	color = color_t( 206, 255, 150 ) ;
			//}
		}
		else if( class_name == xs( "SupplyDrop" )
			&& options::visuals::world::show_supply_drops )
		{
			color = options::visuals::world::color_supply_drops;
			text = xs( "supply drop" );
		}
		else if( class_name == xs( "SupplySignal" )
			&& options::visuals::world::show_supply_signals )
		{
			color = options::visuals::world::color_supply_signals;
			text = xs( "supply signal" );
		}
		else if( ( strstr( obj_name.c_str( ), xs( "bradley_crate" ) ) && strstr( obj_name.c_str( ), xs( ".prefab" ) ) )
			&& options::visuals::world::show_bradley_crate )
		{
			text = xs( "bradley crate" );
			color = options::visuals::world::color_bradley_crate;
		}
		else if( strstr( obj_name.c_str( ), xs( "heli_crate.prefab" ) )
			&& options::visuals::world::show_helicopter_crate )
		{
			text = xs( "helicopter crate" );
			color = options::visuals::world::color_helicopter_crate;
		}
		//else if( class_name == xs( "MobileMapMarker" )
			//&& class_name != xs( "HackableLockedCrate" ) )
		//{
			//text = xs( "marker" );
					
			//g_render.draw_text( render_position, text, color_t( 255, 255, 255 ), false, 10, font_flags_t::dropshadow );
		//}
	}
	if( distance < options::visuals::world::max_food_collectibles_distance )
	{
		if( strstr( obj_name.c_str( ), xs( "hemp/hemp" ) )
			&& options::visuals::world::show_hemp ) {
			text = xs( "hemp" );
			color = options::visuals::world::color_hemp;
		}
		else if( strstr( obj_name.c_str( ), xs( "mushroom-cluster-6.prefab" ) )
			&& options::visuals::world::show_mushroom ) {
			text = xs( "mushroom" );
			color = options::visuals::world::color_mushroom;
		}
		else if( strstr( obj_name.c_str( ), xs( "pumpkin-collectable.prefab" ) )
			&& options::visuals::world::show_pumpkin ) {
			text = xs( "pumpkin" );
			color = options::visuals::world::color_pumpkin;
		}
		else if( strstr( obj_name.c_str( ), xs( "corn-collectable.prefab" ) )
			&& options::visuals::world::show_corns ) {
			text = xs( "corn" );
			color = options::visuals::world::color_corns;
		}
		else if( strstr( obj_name.c_str( ), xs( "berry-" ) )
			&& options::visuals::world::show_berrys ) {
			text = xs( "berry" );
			color = color_t( 143, 128, 217 );
			if( strstr( obj_name.c_str( ), xs( "white" ) ) )
				color = color_t( 209, 209, 209 );
			if( strstr( obj_name.c_str( ), xs( "yellow" ) ) )
				color = color_t( 235, 196, 89 );
			if( strstr( obj_name.c_str( ), xs( "blue" ) ) )
				color = color_t( 115, 171, 255 );
			if( strstr( obj_name.c_str( ), xs( "red" ) ) )
				color = color_t( 255, 46, 99 );
			if( strstr( obj_name.c_str( ), xs( "black" ) ) )
				color = color_t( 150, 150, 150 );
			if( strstr( obj_name.c_str( ), xs( "green" ) ) )
				color = color_t( 117, 255, 117 );
		}
		else if( strstr( obj_name.c_str( ), xs( "potato-collectable.prefab" ) )
			&& options::visuals::world::show_potatos ) {
			text = xs( "potato" );
			color = options::visuals::world::color_potatos;
		}
	}

	if( distance < options::visuals::world::max_ore_collectibles_distance )
	{
		if( strstr( obj_name.c_str( ), xs( "metal-collectable.prefab" ) )
			&& options::visuals::world::show_metal_collectibles ) {
			text = xs( "metal collectible" );
			color = options::visuals::world::color_metal_collectibles;
		}
		else if( strstr( obj_name.c_str( ), xs( "wood-collectable.prefab" ) ) 
			&& options::visuals::world::show_wood_collectibles ) {
			text = xs( "wood collectible" );
			color = options::visuals::world::color_wood_collectibles;
		}
		else if( strstr( obj_name.c_str( ), xs( "stone-collectable.prefab" ) )
			&& options::visuals::world::show_stone_collectibles ) {
			text = xs( "stone collectible" );
			color = options::visuals::world::color_stone_collectibles;
		}
		else if( strstr( obj_name.c_str( ), xs( "sulfur-collectable.prefab" ) )
			&& options::visuals::world::show_sulfur_collectibles ) {
			text = xs( "sulfur collectible" );
			color = options::visuals::world::color_sulfur_collectibles;
		}
	}

	//std::string stash_state = std::string( );
	//core::stash_container* stash_container = reinterpret_cast< core::stash_container* >( combat_entity );

	//if( stash_container ) {
	//	float buried_offset = stash_container->get_burried_offset( );
	//	if( buried_offset == 2048 )
	//		stash_state = " | buried";
	//	else if( buried_offset == 8 )
	//		stash_state = " | being looted";
	//	else
	//		stash_state = " | not buried";

	//	stash_state += std::to_string( buried_offset );

	//	if( distance < options::visuals::world::max_stash_distance 
	//		&& options::visuals::world::show_stashes ) {
	//		if( class_name == xs( "StashContainer" ) )
	//		{
	//			text = xs( "stash" ) + stash_state;
	//			
	//			g_render.draw_text( render_position, text, color_t( 255, 255, 255 ), false, 10, font_flags_t::dropshadow );
	//		}
	//	}
	//}

	if( distance < options::visuals::world::max_barrels_distance )
	{
		bool is_barrel = false;

		if( class_name == xs( "LootContainer" ) )
		{
			if( ( strstr( obj_name.c_str( ), xs( "loot-barrel-1.prefab" ) )
				|| strstr( obj_name.c_str( ), xs( "loot-barrel-2.prefab" ) )
				|| ( strstr( obj_name.c_str( ), xs( "loot_barrel_1.prefab" ) )
				|| strstr( obj_name.c_str( ), xs( "loot_barrel_2.prefab" ) ) ) ) )
			{
				if( options::visuals::world::show_regular_barrels ) {
					text = xs( "barrel" );
					if( strstr( obj_name.c_str( ), xs( "loot-barrel-1.prefab" ) )
						|| strstr( obj_name.c_str( ), xs( "loot_barrel_1.prefab" ) ) )
						color = color_t( 135, 177, 222 );
					else
						color = color_t( 227, 193, 113 );
				}
				is_barrel = true;
			}
			else if( strstr( obj_name.c_str( ), xs( "oil_barrel.prefab" ) ) )
			{
				if( options::visuals::world::show_oil_barrel ) {
					text = xs( "oil barrel" );
					color = options::visuals::world::color_oil_barrel;
				}
				is_barrel = true;
			}
		}
		else if( ( strstr( obj_name.c_str( ), xs( "diesel" ) ) && strstr( obj_name.c_str( ), xs( ".prefab" ) ) ) )
		{
			if( options::visuals::world::show_diesel_fuel ) {
				text = xs( "diesel fuel" );
				color = options::visuals::world::color_diesel_fuel;
			}
			is_barrel = true;
		}

		if( options::aimbot::exploits::misc::auto_farm_barrels ) {
			if( is_barrel ) {
				core::transform* transform = base_entity->get_transform( );
				if( transform
					&& distance < g_esp.melee_max_dist )
					g_esp.do_melee_attack( transform->get_position( ), base_entity, false );
			}
		}
	}
	if( distance < options::visuals::world::max_cars_distance )
	{
		if( !strstr( obj_name.c_str( ), xs( "lift" ) ) ) {
			if( strstr( obj_name.c_str( ), xs( "modularcar" ) )
				&& options::visuals::world::show_modular_car )
			{
				text = xs( "modular car" );
				color = options::visuals::world::color_modular_car;
			}
			else if( strstr( obj_name.c_str( ), xs( "2module_camper" ) )
				&& options::visuals::world::show_two_modules_car )
			{
				text = xs( "two module car" );
				color = options::visuals::world::color_two_modules_car;
			}
		}
	}
	if( distance < options::visuals::world::max_storage_distance )
	{
		//std::string upkeep_time = std::to_string( static_cast< int >( base_entity->get_protected_minutes( ) / 60 ) );

		if( class_name == xs( "BuildingPrivlidge" )
			&& options::visuals::world::show_tool_cupboard )
		{
			color = options::visuals::world::color_tool_cupboard;
			text = xs( "tool cupboard" );
		}
		if( class_name == xs( "VendingMachine" )
			&& options::visuals::world::show_vending_machine )
		{
			color = options::visuals::world::color_vending_machine;
			text = xs( "vending machine" );
		}
		if( class_name == xs( "BoxStorage" )
			&& options::visuals::world::show_box_storages )
		{
			color = options::visuals::world::color_box_storages;
			text = xs( "box storage" );
		}
	}

	if( distance < options::visuals::world::max_stash_distance 
		&& options::visuals::world::show_stashes ) {
		if( class_name == xs( "StashContainer" ) )
		{
			color = options::visuals::world::color_stashes;
			text = xs( "stash" );
		}
	}
	if( distance < options::visuals::world::max_animal_distance ) {
		if( class_name == xs( "Boar" )
			&& options::visuals::world::show_boars )
		{
			text = xs( "boar" );
			color = options::visuals::world::color_boars;
		}
		if( class_name == xs( "Chicken" )
			&& options::visuals::world::show_chickens )
		{	
			color = options::visuals::world::color_chickens;
			text = xs( "chicken" );
		}
		if( class_name == xs( "Stag" ) 
			&& options::visuals::world::show_deers )
		{
			color = options::visuals::world::color_deers;
			text = xs( "deer" );
		}
		if( class_name == xs( "Wolf" )
			&& options::visuals::world::show_wolves )
		{
			color = options::visuals::world::color_wolves;
			text = xs( "wolf" );
		}
		if( class_name == xs( "Bear" )
			&& options::visuals::world::show_bears )
		{
			color = options::visuals::world::color_bears;
			text = xs( "bear" );
		}
		if( class_name == xs( "Polarbear" )
			&& options::visuals::world::show_polar_bears )
		{
			color = options::visuals::world::color_polar_bears;
			text = xs( "polar bear" );
		}
		if( class_name == xs( "RidableHorse" )
			&& options::visuals::world::show_horses )
		{
			color = options::visuals::world::color_horses;
			text = xs( "horse" );
		}
		if( strstr( obj_name.c_str( ), xs( "simpleshark.prefab" ) )
			&& options::visuals::world::show_sharks )
		{
			color = options::visuals::world::color_sharks;
			text = xs( "shark" );
		}
	}
	if( distance < options::visuals::world::max_vehicle_distance )
	{
		if( strstr( obj_name.c_str( ), xs( "submarineduo.entity.prefab" ) )
			&& options::visuals::world::show_duo_submarine )
		{
			color = options::visuals::world::color_duo_submarine;
			text = xs( "duo submarine" );
		}
		if( strstr( obj_name.c_str( ), xs( "submarinesolo.entity.prefab" ) )
			&& options::visuals::world::show_solo_submarine )
		{
			color = options::visuals::world::color_solo_submarine;
			text = xs( "solo submarine" );
		}
		if( class_name == xs( "MotorRowboat" )
			&& options::visuals::world::show_small_motorboat )
		{
			color = options::visuals::world::color_small_motorboat;
			text = xs( "motor boat" );
		}
		if( strstr( obj_name.c_str( ), xs( "kayak.prefab" ) )
			&& options::visuals::world::show_kayak )
		{
			color = options::visuals::world::color_kayak;
			text = xs( "kayak" );
		}
		if( class_name == xs( "RHIB" )
			&& options::visuals::world::show_rhib )
		{
			color = options::visuals::world::color_rhib;
			text = xs( "rhib" );
		}
		if( strstr( obj_name.c_str( ), xs( "bradleyapc.prefab" ) )
			&& options::visuals::world::show_bradley_apc )
		{
			color = options::visuals::world::color_bradley_apc;
			text = xs( "bradley apc" );
		}
		if( class_name == xs( "MiniCopter" )
			&& options::visuals::world::show_minicopter )
		{
			color = options::visuals::world::color_rhib;
			text = xs( "minicopter" );
		}
		if( class_name == xs( "ScrapTransportHelicopter" )
			&& options::visuals::world::show_scrap_helicopter )
		{
			color = options::visuals::world::color_scrap_helicopter;
			text = xs( "scrap helicopter" );
		}
	}
	if( distance < options::visuals::world::max_helicopter_distance ) {

		if( class_name == xs( "PatrolHelicopter" )
			&& options::visuals::world::show_patrol_helicopter )
		{
			color = options::visuals::world::color_patrol_helicopter;
			text = xs( "patrol helicopter" );
		}
		if( strstr( obj_name.c_str( ), xs( "attackhelicopter.entity.prefab" ) )
			&& options::visuals::world::show_attack_helicopter )
		{
			color = options::visuals::world::color_attack_helicopter;
			text = xs( "attack helicopter" );
		}
		if( strstr( obj_name.c_str( ), xs( "ch47.entity.prefab" ) )
			&& options::visuals::world::show_chinook_helicopter )
		{
			color = options::visuals::world::color_chinook_helicopter;
			text = xs( "chinook helicopter" );
		}
	}
	if( distance < options::visuals::world::max_trap_distance )
	{
		if( class_name == xs( "Landmine" ) 
			&& options::visuals::world::show_landmines )
		{
			color = options::visuals::world::color_landmines;
			text = xs( "landmine" );

			core::base_player* local = g_cheat.local;

			if( local ) {
				if( base_entity 
					&& options::aimbot::exploits::misc::disarm_landmines
					&& distance < 5.f 
					&& ( local->lastSentTickTime( ) - last_sent_tick ) > 0.05 ) {
					base_entity->server_rpc( "RPC_Disarm" );
					last_sent_tick = local->lastSentTickTime( );
				}
			}
		}
		if( class_name == xs( "NPCAutoTurret" )
			&& options::visuals::world::show_npc_turrets )
		{
			color = options::visuals::world::color_npc_turrets;
			text = xs( "npc turret" );
		}
		if( strstr( obj_name.c_str( ), xs( "spikes.floor.prefab" ) )
			&& options::visuals::world::show_land_spikes )
		{
			color = options::visuals::world::color_land_spikes;
			text = xs( "floor spikes" );
		}
		if( class_name == xs( "FlameTurret" )
			&& options::visuals::world::show_flame_turrets )
		{
			color = options::visuals::world::color_flame_turrets;
			text = xs( "flame turret" );
		}
		if( class_name == xs( "TeslaCoil" )
			&& options::visuals::world::show_tesla_coil )
		{
			color = options::visuals::world::color_tesla_coil;
			text = xs( "tesla coil" );
		}
		if( class_name == xs( "AutoTurret" )
			&& options::visuals::world::show_auto_turrets )
		{
			color = options::visuals::world::color_auto_turrets;
			text = xs( "turret" );
		}
		if( class_name == xs( "GunTrap" )
			&& options::visuals::world::show_shotgun_traps )
		{
			color = options::visuals::world::color_shotgun_traps;
			text = xs( "shotgun trap" );
		}
		if( class_name == xs( "SamSite" )
			&& options::visuals::world::show_sam_site )
		{
			color = options::visuals::world::color_sam_site;
			text = xs( "sam-site" );
		}
		if( class_name == xs( "BearTrap" )
			&& options::visuals::world::show_bear_trap )
		{
			color = options::visuals::world::color_bear_trap;
			text = xs( "bear trap" );
		}
	}

	if( !text.empty( )
		&& color.a > 0 ) {
		std::transform( text.begin( ), text.end( ), text.begin( ), ::tolower );

		bool show_distance = options::visuals::world::show_distance;
		bool show_health = options::visuals::world::show_health 
			&& combat_entity
			&& combat_entity->get_health( ) > 0;

		if( show_distance || show_health )
			text += xs( "[" );

		if( show_distance )
			text += dist_str + xs( "m" );
		
		if( show_health ) {
			std::string health_str = std::to_string( int( combat_entity->get_health( ) ) ) + xs( "hp" );

			text += show_distance ? xs( "|" ) + health_str : health_str;
		}

		if( show_distance || show_health )
			text += xs( "]" );

		g_render.draw_text( render_position, text, color, false, 10, g_esp.font_flags );
	}
}
#pragma once
#include "../../includes/includes.hpp"
#include "../../game/sdk.hpp"

class c_world_esp 
{
public:
	void render( vec4_t, std::string,
		std::string, int, core::base_combat_entity*,
		event_type, core::base_entity* );
};
extern c_world_esp g_world;
#include "esp.h"
#include <cmath>
#include "../aimbot/aimbot.h"

#include <Windows.h>
#include "../options.h"

#include "../../utilities/memory.hpp"
#include "../menu/framework/gui_framework.h"

// create global definition for esp class.
c_esp g_esp;

void draw_3d_box( vec3_t bottom, vec3_t head_pos, float wide, color_t col )
{
    vec3_t bottom_one = vec3_t( bottom.x + wide, bottom.y + wide, bottom.z );
    vec2_t bottom_one_pos = g_sdk.world_to_screen( bottom_one );

    vec3_t bottom_two = vec3_t( bottom.x - wide, bottom.y - wide, bottom.z );
    vec2_t bottom_two_pos = g_sdk.world_to_screen( bottom_two );

    vec3_t bottom_three = vec3_t( bottom.x + wide, bottom.y - wide, bottom.z );
    vec2_t bottom_three_pos = g_sdk.world_to_screen( bottom_three );

    vec3_t bottom_four = vec3_t( bottom.x - wide, bottom.y + wide, bottom.z );
    vec2_t bottom_four_pos = g_sdk.world_to_screen( bottom_four );

    vec3_t top_one = vec3_t( bottom.x + wide, bottom.y + wide, head_pos.z + 15 );
    vec2_t top_one_pos = g_sdk.world_to_screen( top_one );

    vec3_t top_two = vec3_t( bottom.x - wide, bottom.y - wide, head_pos.z + 15 );
    vec2_t top_two_pos = g_sdk.world_to_screen( top_two );

    vec3_t top_three = vec3_t( bottom.x + wide, bottom.y - wide, head_pos.z + 15 );
    vec2_t top_three_pos = g_sdk.world_to_screen( top_three );

    vec3_t top_four = vec3_t( bottom.x - wide, bottom.y + wide, head_pos.z + 15 );
    vec2_t top_four_pos = g_sdk.world_to_screen( top_four );

    g_render.draw_line( bottom_one_pos, bottom_three_pos, col );
    g_render.draw_line( bottom_three_pos, bottom_two_pos, col );
    g_render.draw_line( bottom_two_pos, bottom_four_pos, col );
    g_render.draw_line( bottom_four_pos, bottom_one_pos, col );

    g_render.draw_line( top_one_pos, top_three_pos, col );
    g_render.draw_line( top_three_pos, top_two_pos, col );
    g_render.draw_line( top_two_pos, top_four_pos, col );
    g_render.draw_line( top_four_pos, top_one_pos, col );

    g_render.draw_line( bottom_one_pos, top_one_pos, col );
    g_render.draw_line( bottom_two_pos, top_two_pos, col );
    g_render.draw_line( bottom_three_pos, top_three_pos, col );
    g_render.draw_line( bottom_four_pos, top_four_pos, col );
}

void c_esp::context_instance( core::base_player* player, entity_type type )
{
    core::player_model* model = player->get_model( );
    core::base_player* local = g_cheat.local;
    if( !local
        || player == local )
        return;

    bool npc = model->is_npc( );

	if( ( !options::visuals::draw_visuals
        || ( !options::visuals::can_show_sleepers 
		&& player->is_sleeping( ) ) 
		|| ( !options::visuals::can_show_knocked
		&& player->is_knocked( ) )
		|| ( !options::visuals::can_show_npc && npc )
		|| player->get_life_state( ) ) ) {
		return;
	}

    bool visible = player->is_visible( player->get_bone_position( head ) );

    if( npc ) {
        if( visible ) {
            name_color = options::visuals::npc_vis_name_color;
            box_color = options::visuals::npc_vis_box_color;

            skeleton_color = options::visuals::npc_vis_skeleton_color;
            radar_color = options::visuals::npc_vis_radar_color;
            oof_color = options::visuals::npc_vis_oof_color;
            snap_lines_color = options::visuals::npc_vis_snap_lines_color;
            distance_color = options::visuals::npc_vis_distance_color;
            weapon_color = options::visuals::npc_vis_weapon_color;
            view_direction_color = options::visuals::npc_vis_view_direction_color;
            knocked_color = options::visuals::npc_vis_knocked_color;
            ducking_color = options::visuals::npc_vis_ducking_color;
            custom_health_color = options::visuals::npc_vis_custom_health_color;
            health_text_color = options::visuals::npc_vis_health_text_color;
        }
        else {
            name_color = options::visuals::npc_name_color;
            box_color = options::visuals::npc_box_color;

            skeleton_color = options::visuals::npc_skeleton_color;
            radar_color = options::visuals::npc_radar_color;
            oof_color = options::visuals::npc_oof_color;
            snap_lines_color = options::visuals::npc_snap_lines_color;
            distance_color = options::visuals::npc_distance_color;
            weapon_color = options::visuals::npc_weapon_color;
            view_direction_color = options::visuals::npc_view_direction_color;
            knocked_color = options::visuals::npc_knocked_color;
            ducking_color = options::visuals::npc_ducking_color;
            custom_health_color = options::visuals::npc_custom_health_color;
            health_text_color = options::visuals::npc_health_text_color;
        }
    }
    else {
        if( visible ) {
            name_color = options::visuals::vis_name_color;
            box_color = options::visuals::vis_box_color;

            skeleton_color = options::visuals::vis_skeleton_color;
            radar_color = options::visuals::vis_radar_color;
            oof_color = options::visuals::vis_oof_color;
            snap_lines_color = options::visuals::vis_snap_lines_color;
            distance_color = options::visuals::vis_distance_color;
            weapon_color = options::visuals::vis_weapon_color;
            view_direction_color = options::visuals::vis_view_direction_color;
            knocked_color = options::visuals::vis_knocked_color;
            ducking_color = options::visuals::vis_ducking_color;
            custom_health_color = options::visuals::vis_custom_health_color;
            health_text_color = options::visuals::vis_health_text_color;
        }
        else {
            name_color = options::visuals::name_color;
            box_color = options::visuals::box_color;

            skeleton_color = options::visuals::skeleton_color;
            radar_color = options::visuals::radar_color;
            oof_color = options::visuals::oof_color;
            snap_lines_color = options::visuals::snap_lines_color;
            distance_color = options::visuals::distance_color;
            weapon_color = options::visuals::weapon_color;
            view_direction_color = options::visuals::view_direction_color;
            knocked_color = options::visuals::knocked_color;
            ducking_color = options::visuals::ducking_color;
            custom_health_color = options::visuals::custom_health_color;
            health_text_color = options::visuals::health_text_color;
        }
    }

	float dist_to = g_cheat.local_pos.distance( model->get_position( ) );
	if( dist_to > options::visuals::max_player_distance )
		return;

    bbox = core::get_bounds( player, 5.f );

    if( !bbox.on_screen ) {
        if( options::visuals::offscreen_arrows ) {
            draw_out_of_fov_arrows( player );
        }
    }
	else {
        if( options::visuals::show_name ) {
			draw_name( player, type );
		}
        if( options::visuals::box_type > 0 ) { 
			draw_box( player ); 
		}
        if( options::visuals::show_health )
		{
			draw_health( player );
		}
        if( options::visuals::draw_bones )
		{
			draw_bones( player );
		}
        if( options::visuals::show_lines 
            || options::aimbot::draw_target )
		{
			draw_snap_lines( player );
		}
        draw_view_direction( player );
        if( options::visuals::show_health_text )
        {
            draw_health_text( player );
        }
		draw_weapon( player ); // custom shit
		if( options::visuals::show_distance ) {
			draw_distance( player );
		}
        if( options::visuals::show_ducking_flag )
        {
            draw_ducking_flag( player );
        }
        if( options::visuals::show_knocked_flag )
        {
            draw_knocked_flag( player );
        }
        if( options::visuals::chams )
		{
			invoke_chams( player );
		}
	}

    if( options::visuals::draw_radar ) {
        draw_radar( player );
    }
}

void c_esp::draw_bullet_tracers( )
{
    if( !options::visuals::draw_tracers )
        return m_shots.clear( );

	if( m_shots.empty( ) )
		return;

    int font_size = 12;

    // keep this limited to 5 instances.
    while( m_shots.size( ) > 5 )
        m_shots.pop_back( );

    color_t color = options::visuals::tracers_color;

	for( size_t i = 0; i < m_shots.size( ); i++ )
	{
		auto& tr = m_shots[ i ];

        static float alpha = 0.f;

		float delta = g_sdk.get_time( ) - tr.m_time;
		if( ( delta > 1.0f
            || std::abs( delta ) > 3.f ) ) {

            alpha = std::lerp( alpha, 0.f, 0.025f );

            if( alpha < 0.1f )
			    m_shots.erase( m_shots.begin( ) + i );
        }
        else if( alpha < 1.f )
            alpha = std::lerp( alpha, 1.f, 0.025f );

        // measure alpha.
        color.a *= alpha;

        core::base_player* player = tr.entity;
        if( !player )
            continue;

        g_render.ddraw_line( tr.m_start, tr.m_end, color, 3.5f, false );
	}
}

vec2_t rotate_point( vec2_t to_rotate, vec2_t center, float angle )
{
    angle *= ( M_PI / 180.f );

    float ang_cos = cos( angle );
    float ang_sin = sin( angle );

    vec2_t to_return = vec2_t( );

    to_return.x = ( ( ang_cos * ( to_rotate.x - center.x ) - ang_sin * ( to_rotate.y - center.y ) ) + center.x );
    to_return.y = ( ( ang_sin * ( to_rotate.x - center.x ) + ang_cos * ( to_rotate.y - center.y ) ) + center.y );

    return to_return;
}

void c_esp::draw_local_trails( ) {
    core::base_player* local = g_cheat.local;
    if( !local )
        return;

    core::player_ticks* last_sent_tick = local->get_lastSentTick( );
    if( !last_sent_tick )
        return;

    g_render.ddraw_line( last_sent_tick->get_position( ), g_cheat.local_pos, options::visuals::trails_color, 2.5f, true, true );
}

void c_esp::draw_last_sent_tick( ) {
    core::base_player* local = g_cheat.local;
    if( !local )
        return;

    core::player_ticks* last_sent_tick = local->get_lastSentTick( );
    if( !last_sent_tick )
        return;

    g_render.ddraw_sphere( last_sent_tick->get_position( ), g_cheat.local_pos, color_t( 255, 0, 0 ), 2.5f, false );
}

void c_esp::draw_radar( core::base_player* player )
{
    vec2_t size = vec2_t( 4, 4 );
    float width = 200, height = 200;

    vec2_t screen_position = vec2_t( ), rotated_point = vec2_t( );
    vec2_t center = vec2_t( radar_position.x + ( width / 2 ), radar_position.y + 100 );
    vec2_t center_position = vec2_t( center.x, center.y );
        
    core::player_model* model = player->get_model( );
    if( !model )
        return;

    core::base_player* local = g_cheat.local;
    if( !local )
        return;

    core::player_input* input = local->get_input( );
    if( !input )
        return;

    vec3_t pos = model->get_position( );
    if( pos.is_zero( ) )
        return;

    vec2_t view_angles = input->get_view_angles( );
    if( view_angles.is_zero( ) )
        return;

    screen_position = vec2_t( ( -( g_cheat.local_pos.x - pos.x ) + center.x ),
        ( g_cheat.local_pos.z - pos.z ) + center.y );

    rotated_point = rotate_point( screen_position, center_position, ( 360.0f - view_angles.y ) );

    if( ( rotated_point.x < radar_position.x
        || rotated_point.y < radar_position.y
        || rotated_point.x > radar_position.x + ( width - size.x )
        || rotated_point.y > radar_position.y + ( height - size.y ) ) )
        return;

    g_render.draw_filled_rect( vec2_t( rotated_point.x, rotated_point.y ), vec2_t( 4, 4 ), radar_color );
    g_render.outline_box( vec2_t( rotated_point.x, rotated_point.y ), vec2_t( 4, 4 ), color_t( 10, 10, 10, 175 ) );

    g_render.draw_filled_rect( vec4_t( center.x, center.y, 4, 4 ), options::accent_color.alpha( 255, true ) );
    g_render.outline_box( vec2_t( center.x, center.y ), vec2_t( 4, 4 ), color_t( 10, 10, 10, 175 ) );
}

void c_esp::render_saved_positions( )
{
    core::base_player* local = g_cheat.local;
    if( !local )
        return;

    core::player_model* model = local->get_model( );
    if( !model )
        return;

    vec3_t local_pos = model->get_position( );
    if( local_pos.is_zero( ) )
        return;

    // make position higher than us.
    local_pos.y += 2;

    static int delay = 0;

    if( g_sdk.get_key_down( ( key_code )options::visuals::save_pos_key )
        && delay < 10 ) {
        delay = 10;
        m_positions.push_back( { options::visuals::is_home_pos, local_pos, options::visuals::pos_color } );
    }

    // remove delay by 1.
    --delay;

    if( g_sdk.get_key( options::visuals::remove_positions_key )
        && !m_positions.empty( ) )
        m_positions.pop_back( );

    for( int i = 0; i < m_positions.size( ); i++ ) {
        auto& pos = m_positions.at( i );
        if( pos.m_location.is_zero( ) )
            continue;

        vec2_t world_pos = g_sdk.world_to_screen( pos.m_location );
        if( world_pos.is_zero( ) )
            continue;

        std::string text = std::string( );

        if( pos.is_home )
            text = xs( "home pos" );
        else
            text = xs( "saved position" );

        text += xs( "[" ) + std::to_string( i );
        text += xs( "|" ) + std::to_string( int( g_cheat.local_pos.distance( pos.m_location ) ) ) + xs( "m" );
        text += xs( "]" );

        g_render.draw_text( vec4_t( world_pos.x, world_pos.y, 150, 20 ), text, pos.color, false, 12, font_flags );
    }
}

void c_esp::change_sky_ambient_color( ) {
    static uintptr_t sky = il2mgr::init_class( "TOD_Sky" );
    if( !sky )
        return;

	uintptr_t night = memory::read_chain< uintptr_t >( sky, { 0xB8, 0x0, 0x10, 0x20, 0x58 } );
	uintptr_t day = memory::read_chain< uintptr_t >( sky, { 0xB8, 0x0, 0x10, 0x20, 0x50 } );
	uintptr_t stars = memory::read_chain< uintptr_t >( sky, { 0xB8, 0x0, 0x10, 0x20, 0x70 } );
				
	if( stars ) {
		if( options::visuals::world::stars )
			*reinterpret_cast< int* >( stars + 0x14 ) = options::visuals::world::brightness_stars_amount;
		if( options::visuals::world::stars_size )
			*reinterpret_cast< int* >( stars + 0x10 ) = options::visuals::world::size_stars_amount;
	}

	if( options::aimbot::exploits::time::time_modifier )
        g_game.set_admin_time( options::aimbot::exploits::time::time_speed );

	if( night
		&& day 
		&& options::visuals::world::ambient ) {

		*reinterpret_cast< float* >( night + 0x48 ) = options::visuals::world::light_value;
		*reinterpret_cast< float* >( night + 0x50 ) = options::visuals::world::ambient_value;
		*reinterpret_cast< float* >( day + 0x48 ) = options::visuals::world::light_value;
		*reinterpret_cast< float* >( day + 0x50 ) = options::visuals::world::ambient_value;
	}

    color_t ambient = options::visuals::world::ambient_color;
    color_t sky_clr = options::visuals::world::sky_color;

    // modify alpha so it's not so bright as it is.

    if( options::visuals::world::change_world_color ) {
        uintptr_t components = *reinterpret_cast< uintptr_t* >( sky + 0xA8 );
        if( !components )
            return;

        uintptr_t scattering = *reinterpret_cast< uintptr_t* >( components + 0x1A0 );
        if( !scattering )
            return;

        uintptr_t sky_color = *reinterpret_cast< uintptr_t* >( day + 0x28 );
        if( !sky_color )
            return;

        uintptr_t ambient_color = *reinterpret_cast< uintptr_t* >( day + 0x40 );
        if( !ambient_color )
            return;

        uintptr_t sky_gradient = *reinterpret_cast< uintptr_t* >( sky_color + 0x10 );
        if( !sky_gradient )
            return;

        uintptr_t ambient_gradient = *reinterpret_cast< uintptr_t* >( ambient_color + 0x10 );
        if( !ambient_gradient )
            return;

        *reinterpret_cast< color_t* >( sky_gradient ) = color_t( sky_clr.r, sky_clr.g, sky_clr.b, 255.f );

        *reinterpret_cast< color_t* >( ambient_gradient ) = color_t( ambient.r, ambient.g, ambient.b, 255.f );
    }
}

void c_esp::find_manipulate_angle( ) {
    core::base_player* target = g_aimbot.target;
    if( !target ) {
        manipulation_angle.clear( );
        return;
    }

    core::base_player* local = g_cheat.local;
    if( !local ) {
        manipulation_angle.clear( );
        return;
    }

    core::transform* transform = local->get_transform( );
    if( !transform ) {
        manipulation_angle.clear( );
        return;
    }

    core::player_eyes* eyes = local->get_eyes( );
    if( !eyes ) {
        manipulation_angle.clear( );
        return;
    }

    vec3_t re_p = transform->get_position( ) + transform->up( ) * ( core::player_eyes::get_eyeOffset( ).y + eyes->get_viewoffset( ).y );

    vec3_t choice = vec3_t( );

    vec3_t z = target->get_bone_position( head );

    if( target->is_visible( z ) ) {
        manipulation_angle.clear( );
        return;
    }

	float max_v_multiplier = 6.2f;
	float v_maximum_eye_height = maximum_eye_height / max_v_multiplier;

    vec3_t right = eyes->get_bodyright( );
    vec3_t forward = eyes->get_movementforward( );

    std::array< vec3_t, 60 > arr = {
        vec3_t( right.x * maximum_eye_height, 0.f, right.z * maximum_eye_height ), // big right

        vec3_t( right.x * ( maximum_eye_height / 2 ), 0.65f, right.z * ( maximum_eye_height / 2 ) ), // small right up

        vec3_t( right.x * ( maximum_eye_height / 2 ), -0.65f, right.z * 2.f ), // small right down

        vec3_t( -( right.x * ( maximum_eye_height / 2 ) ), 0.65f, -( right.z * ( maximum_eye_height / 2 ) ) ), // small left up

        vec3_t( -( right.x * maximum_eye_height ), 1.5f, -( right.z * maximum_eye_height ) ), // big left up

        vec3_t( -( right.x * ( maximum_eye_height / 2 ) ), -0.65f, -( right.z * ( maximum_eye_height / 2 ) ) ), // small left down

        vec3_t( -( forward.x * maximum_eye_height ), 0.f, -( forward.z * maximum_eye_height ) ), // big backward

        vec3_t( forward.x * ( maximum_eye_height / 2 ), 0.65f, forward.z * ( maximum_eye_height / 2 ) ),// small forward up

        vec3_t( forward.x * ( maximum_eye_height / 2 ), -0.65f, forward.z * ( maximum_eye_height / 2 ) ),// small forward down

        vec3_t( -( forward.x * ( maximum_eye_height / 2 ) ), 0.f, -( forward.z * ( maximum_eye_height / 2 ) ) ),// small reverse

        vec3_t( -( forward.x * ( maximum_eye_height / 2 ) ), 0.65f, -( forward.z * ( maximum_eye_height / 2 ) ) ),// small reverse up

        vec3_t( -( forward.x * ( maximum_eye_height / 2 ) ), -0.65f, -( forward.z * ( maximum_eye_height / 2 ) ) ),// small reverse down

        vec3_t( right.x * maximum_eye_height, 1.5f, right.z * ( maximum_eye_height ) ) * 0.9f, // big diag-up-right

        vec3_t( -right.x * ( maximum_eye_height ), 1.5f, -right.z * ( maximum_eye_height ) ) * 0.9f, // big diag-up-left

        vec3_t( right.x * maximum_eye_height, -1.5f, right.z * ( maximum_eye_height ) ) * 0.9f, // big diag-down-right

        vec3_t( -right.x * ( maximum_eye_height ), -1.5f, -right.z * ( maximum_eye_height ) ) * 0.9f, // big diag-up-left

        vec3_t( ( right.x / 2 ) * maximum_eye_height, 1.5f, ( right.z / 2 ) * ( maximum_eye_height ) ), // big diag-up-right

        vec3_t( -( right.x / 2 ) * ( maximum_eye_height ), 1.5f, -( right.z / 2 ) * ( maximum_eye_height ) ), // big diag-up-left

        vec3_t( ( right.x / 2 ) * maximum_eye_height, -1.5f, ( right.z / 2 ) * ( maximum_eye_height ) ), // big diag-down-right

        vec3_t( -( right.x / 2 ) * ( maximum_eye_height ), -1.5f, -( right.z / 2 ) * ( maximum_eye_height ) ), // big diag-up-left

        vec3_t( ( forward.x / 2 ) * ( maximum_eye_height / 2 ), 1.5f, ( forward.z / 2 ) * ( maximum_eye_height / 2 ) ), // big diag-up-forward

        vec3_t( -( ( forward.x / 2 ) * ( maximum_eye_height / 2 ) ), 1.5f, -( ( forward.z / 2 ) * maximum_eye_height / 2 ) ), // big diag-up-backward

        vec3_t( 0.f, ( v_maximum_eye_height / 5 ), 0.f ), // small up

		vec3_t( 0.f, v_maximum_eye_height, 0.f ), // big up

		vec3_t( 0.f, -0.75f, 0.f ), // small down

		vec3_t( 0.f, -1.5f, 0.f ), // big down

        vec3_t( 1.5f, -v_maximum_eye_height, 0.f ), // big right-down

        vec3_t( -1.5f, v_maximum_eye_height, 0.f ), // big right-down

        vec3_t( 1.5f, v_maximum_eye_height, 0.f ), // big right-down

        vec3_t( maximum_eye_height, -v_maximum_eye_height, 0.f ), // big right-down

		vec3_t( right.x * ( maximum_eye_height / 2 ), 0.f, right.z * ( maximum_eye_height / 2 ) ), // small right

		vec3_t( right.x * ( maximum_eye_height / 2 ), 0.75f, right.z * ( maximum_eye_height / 2 ) ), // small right up

		vec3_t( right.x * maximum_eye_height, 1.5f, right.z * maximum_eye_height ), // big right up

		vec3_t( right.x * ( maximum_eye_height / 2 ), -0.75f, right.z * 2.f ), // small right down

		vec3_t( right.x * maximum_eye_height, -1.5f, right.z * maximum_eye_height ), // big right down

		vec3_t( -( right.x * ( maximum_eye_height / 2 ) ), 0.f, -( right.z * ( maximum_eye_height / 2 ) ) ), // small left

		vec3_t( -( right.x * maximum_eye_height ), 0.f, -( right.z * maximum_eye_height ) ), // big left

		vec3_t( -( right.x * ( maximum_eye_height / 2 ) ), 0.75f, -( right.z * ( maximum_eye_height / 2 ) ) ), // small left up

		vec3_t( -( right.x * ( maximum_eye_height / 2 ) ), -0.75f, -( right.z * ( maximum_eye_height / 2 ) ) ), // small left down

		vec3_t( -( right.x * maximum_eye_height ), -1.5f, -( right.z * maximum_eye_height ) ), // big left down 

		vec3_t( forward.x * maximum_eye_height, 0.f, forward.z * maximum_eye_height ), // big forward

		vec3_t( forward.x * ( maximum_eye_height / 2 ), 0.75f, forward.z * ( maximum_eye_height / 2 ) ),// small forward up

		vec3_t( forward.x * maximum_eye_height, 1.5f, forward.z * maximum_eye_height ), // big forward up

		vec3_t( forward.x * ( maximum_eye_height / 2 ), -0.75f, forward.z * ( maximum_eye_height / 2 ) ),// small forward down

		vec3_t( forward.x * maximum_eye_height, -1.5f, forward.z * maximum_eye_height ), // big forward down

		vec3_t( -( forward.x * ( maximum_eye_height / 2 ) ), 0.75f, -( forward.z * ( maximum_eye_height / 2 ) ) ),// small reverse up

		vec3_t( -( forward.x * 4.f ), 1.5f, -( forward.z * 4.f ) ), // big reverse up

		vec3_t( -( forward.x * ( maximum_eye_height / 2 ) ), -0.75f, -( forward.z * ( maximum_eye_height / 2 ) ) ),// small reverse down

		vec3_t( -( forward.x * maximum_eye_height ), -1.5f, -( forward.z * maximum_eye_height ) ), // big reverse down

		vec3_t( right.x * maximum_eye_height, v_maximum_eye_height, right.z * ( maximum_eye_height ) ) * 0.9f, // big diag-up-right

		vec3_t( -right.x * ( maximum_eye_height ), ( v_maximum_eye_height ), -right.z * ( maximum_eye_height ) ) * 0.9f, // big diag-up-left

		vec3_t( right.x * maximum_eye_height, -v_maximum_eye_height, right.z * ( maximum_eye_height ) ) * 0.9f, // big diag-down-right

		vec3_t( -right.x * ( maximum_eye_height ), ( -v_maximum_eye_height ), -right.z * ( maximum_eye_height ) ) * 0.9f, // big diag-up-left

		vec3_t( ( right.x / 2 ) * maximum_eye_height, v_maximum_eye_height, ( right.z / 2 ) * ( maximum_eye_height ) ), // big diag-up-right

		vec3_t( -( right.x / 2 ) * ( maximum_eye_height ), ( v_maximum_eye_height ), -( right.z / 2 ) * ( maximum_eye_height ) ), // big diag-up-left

		vec3_t( ( right.x / 2 ) * maximum_eye_height, -v_maximum_eye_height, ( right.z / 2 ) * ( maximum_eye_height ) ), // big diag-down-right

		vec3_t( -( right.x / 2 ) * ( maximum_eye_height ), ( -v_maximum_eye_height ), -( right.z / 2 ) * ( maximum_eye_height ) ), // big diag-up-left

		vec3_t( ( forward.x / 2 ) * ( maximum_eye_height / 2 ), ( v_maximum_eye_height / 1 ), ( forward.z / 2 ) * ( maximum_eye_height / 2 ) ), // big diag-up-forward

		vec3_t( -( ( forward.x / 2 ) * ( maximum_eye_height / 2 ) ), ( v_maximum_eye_height / 1 ), -( ( forward.z / 2 ) * maximum_eye_height / 2 ) ), // big diag-up-backward
    };

    for( vec3_t s : arr ) {
        vec3_t point = re_p + s;

        if( !g_sdk.is_visible( point, re_p ) )
            continue;

		g_render.ddraw_arrow( re_p, eyes->get_position( ), 0.3f, color_t( 255, 255, 255 ), 0.01f);

        if( !g_sdk.is_visible( target->get_bone_position( head ), point ) )
            continue;

        eye_manipulation_angle = point;
        choice = s;
        break;
    }
    if( choice.is_zero( ) ) {
        manipulation_angle.clear( );
        return;
    }

    manipulation_angle = choice;
}

void c_esp::invoke_chams( core::base_player* player )
{
    static uintptr_t shader = { };
    static uintptr_t type_obj = il2mgr::type_object( "UnityEngine", "Shader" );
    switch( options::visuals::chams_type ) {
    case 0:
        shader = g_sdk.load_asset( g_cheat.asset_bundle, "chams.shader", type_obj );
        break;
    case 1:
        shader = g_sdk.load_asset( g_cheat.chams_bundle, "hologramshader.shader", type_obj );
        break;
    case 2:
        shader = g_sdk.load_asset( g_cheat.chams_bundle, "invisible.shader", type_obj );
        break;
    case 3:
        shader = g_sdk.load_asset( g_cheat.chams_bundle, "assets\\sinevfx\\galaxymaterials\\resources\\shaders\\galaxymaterial.shader", type_obj );
        break;
    case 4:
        shader = g_sdk.load_asset( g_cheat.chams_bundle, "chams.shader", type_obj );
        break;
    case 5:
        shader = g_sdk.load_asset( g_cheat.wireframe_chams_bundle, "assets\\bundledassets\\wireframetransparentculled.shader", type_obj );
        break;
    case 6:
        shader = g_sdk.load_asset( g_cheat.circuit_chams_bundle, "nebnel.shader", type_obj );
        break;
    }
    if( !shader )
        return;

    core::player_model* model = player->get_model( );
    if( !model )
        return;

    uintptr_t multi_mesh = model->get_multimesh( );
    if( !multi_mesh )
        return;

    laddy_list< uintptr_t >* renderers = g_sdk.get2renderers( multi_mesh );
    if( !renderers )
        return;

    for( int i = 0; i < renderers->get_size( ); i++ )
    {
        uintptr_t renderer = renderers->get_value( i );
        if( !renderer )
            return;

        const uintptr_t material = g_sdk.get_material( renderer );
        if( !material )
            return;

        if( g_sdk.get_shader( material ) != shader )
            g_sdk.set_shader( material, shader );

        if( options::visuals::chams_type == 5 ) {
            g_sdk.set_color( material, "_WireColor", 
                color_t( options::visuals::chams_color.r * 255.f, options::visuals::chams_color.g * 255.f, options::visuals::chams_color.b * 255.f ) );

            g_sdk.set_color( material, "_BaseColor", 
                color_t( options::visuals::chams_color.r * 255.f, options::visuals::chams_color.g * 255.f, options::visuals::chams_color.b * 255.f ) );

            g_sdk.set_material_int( material, "_WireThickness", 
                1 );
        }

        if( options::visuals::chams_type == 6 ) {
            g_sdk.set_color( material, "_Color", 
                color_t( options::visuals::chams_color.r * 255.f, options::visuals::chams_color.g * 255.f, options::visuals::chams_color.b * 255.f ) );
        }
        if( options::visuals::chams_type == 1 || options::visuals::chams_type == 3 ) {
            g_sdk.set_color( material, "_InvisCol", 
                options::visuals::chams_color );

            g_sdk.set_color( material, "_VisCol", 
                options::visuals::chams_visible );
        }
        if( options::visuals::chams_type == 0
            || options::visuals::chams_type == 4 ) {
            g_sdk.set_color( material, "_ColorBehind", 
                options::visuals::chams_color );

            g_sdk.set_color( material, "_ColorVisible", 
                options::visuals::chams_visible );
        }
    }

    //uintptr_t skin_set = *reinterpret_cast< uintptr_t* >( ( uintptr_t )model + 0x140 );
    //if( !skin_set ) {
    //    skin_set = *reinterpret_cast< uintptr_t* >( ( uintptr_t )model + 0x148 );
    //    return;
    //}
            
    //uintptr_t skins = *reinterpret_cast< uintptr_t* >( skin_set + 0x18 );
    //if( !skins )
    //    return;

    //static uintptr_t sky = il2mgr::init_class( "TOD_Sky" );
    //if( !sky )
    //    return;

    //uintptr_t components = *reinterpret_cast< uintptr_t* >( sky + 0xA8 );
    //if( !components )
    //    return;

    //uintptr_t scattering = *reinterpret_cast< uintptr_t* >( components + 0x154 );
    //if( !scattering )
    //    return;

    //int size = *reinterpret_cast< int* >( skins + 0x18 );

    //for ( int idx = 0; idx < size; idx++ )
    //{
    //    uintptr_t skin_set = *reinterpret_cast< uintptr_t* >( skins + 0x20 + ( idx * sizeof( uint64_t ) ) );
    //    if( !skin_set )
    //        continue;

    //    *reinterpret_cast< uintptr_t* >( skin_set + 0x68 ) = scattering; // SkinSet HeadMaterial
    //    *reinterpret_cast< uintptr_t* >( skin_set + 0x70 ) = scattering; // SkinSet BodyMaterial
    //    *reinterpret_cast< uintptr_t* >( skin_set + 0x78 ) = scattering; // SkinSet EyeMaterial
    //}
}

void c_esp::draw_health( core::base_player* player )
{
    float health = min( 100.f, static_cast< float >( player->get_health( ) ) );

    float box_height = bbox.bottom - bbox.top;

    // calculate hp bar color.
    const float calculate_col = ( std::clamp< float >( health, 25, 75 ) - 25.f ) / 50.f;

    color_t color = color_t( 120.f + ( 135.f * ( 1.f - calculate_col ) ), 50.f + ( 175.f * calculate_col ), 80 );
    if( options::visuals::modify_health_color )
        color = custom_health_color/*.multiply( color_t( 255, 15, 15 ), ( health / 100.f ) )*/;

    // get hp bar height.
	int fill = static_cast< int >( std::round( health * box_height / 100.f ) );

    int thickness = options::visuals::health_thickness;

    g_render.draw_filled_rect( vec4_t( bbox.left - ( 5 + thickness ), bbox.top - 1, thickness + 2, box_height + 3 ), color_t( 0, 0, 0, 150 ) );
	g_render.draw_filled_rect( vec4_t( bbox.left - ( 4 + thickness ), bbox.top + box_height - fill, thickness, fill + 1 ), color );
}

void c_esp::draw_hotbar( core::base_player* target )
{
    if( !target
        || target->get_life_state( ) )
        return;

    // check if we have menu open.
	if( g_framework.in_alpha ) {
		vec3_t cursor = g_cheat.mouse_pos;

		if( g_sdk.get_key( key_code::Mouse0 ) 
			&& g_framework.is_hovering( hotbar_position, vec2_t( info_bar_size.x, 25 ) ) )
		{
			cursor.y = g_cheat.screen_size.y - cursor.y;

			hotbar_position.x = cursor.x - info_bar_size.x / 2.f;
			hotbar_position.y = cursor.y - 10.f;
		}
	}

    float info_y = 0;

    std::string name = std::string( );

    core::player_model* model = target->get_model( );
    if( !model )
        return;

    std::vector< core::item* > belt = target->get_hotbar_items( );

    if( belt.empty( ) )
        return;

    name = model->is_npc( ) ? xs( "npc" ) : g_sdk.ws2s( target->get_username( ) ).substr( 0, 14 );

    std::string text = name + xs( "'s hotbar" );

    g_render.draw_filled_rect( hotbar_position, info_bar_size, g_framework.outline_color );
    g_render.outline_box( hotbar_position, info_bar_size, options::accent_color.alpha( 255, true ) );

    g_render.draw_text( vec4_t( hotbar_position.x + 11, hotbar_position.y, 150, 30 ), text, color_t( 255, 255, 255 ), true, 11, font_flags );

    color_t color = color_t( 220, 220, 220 );

    core::item* held_item = target->get_held_item( );

    for( size_t i = 0; i < belt.size( ); i++ )
    {
        core::item* item = belt.at( i );
        if( !item )
            continue;

        int item_amount = item->get_amount( );
	    if( item_amount > 1000 )
            item_amount = 1000;

        std::string weapon_name = g_sdk.ws2s( item->get_weapon_name( ) );
        if( weapon_name.empty( ) )
            continue;

        if( held_item 
            && item == held_item )
            color = color_t( 255, 255, 255 );

        std::string text = weapon_name;
        if( item_amount > 1 )
            text += xs( " x" ) + std::to_string( item_amount );

        std::transform( text.begin( ), text.end( ), text.begin( ), ::tolower );

        g_render.draw_text( vec4_t( hotbar_position.x + 11, ( hotbar_position.y + 25 ) + info_y, 150, 40 ), text, color, true, 11, font_flags );
        info_y += 13;
    }

    info_y = 0; // whaat...
}

void c_esp::draw_clothes( core::base_player* target )
{
    if( !target
        || target->get_life_state( ) )
        return;

    float info_y = 0;

    // check if we have menu open.
	if( g_framework.in_alpha ) {
		vec3_t cursor = g_cheat.mouse_pos;

		if( g_sdk.get_key( key_code::Mouse0 ) 
			&& g_framework.is_hovering( clothes_position, vec2_t( info_bar_size.x, 25 ) ) )
		{
			cursor.y = g_cheat.screen_size.y - cursor.y;

			clothes_position.x = cursor.x - info_bar_size.x / 2.f;
			clothes_position.y = cursor.y - 10.f;
		}
	}

    std::string name = std::string( );

    core::player_model* model = target->get_model( );
    if( !model )
        return;

    std::vector< core::item* > wear = target->get_wear_items( );
    if( wear.empty( ) )
        return;

    name = model->is_npc( ) ? xs( "npc" ) : g_sdk.ws2s( target->get_username( ) ).substr( 0, 14 );

    std::string text = name + xs( "'s clothes" );

    g_render.draw_filled_rect( clothes_position, info_bar_size, g_framework.outline_color );
    g_render.outline_box( clothes_position, info_bar_size, options::accent_color.alpha( 255, true ) );

    g_render.draw_text( vec4_t( clothes_position.x + 11, clothes_position.y, 150, 30 ), text, color_t( 255, 255, 255 ), true, 11, font_flags );

    color_t color = color_t( 255, 255, 255 );

    for( size_t i = 0; i < wear.size( ); i++ )
    {
        core::item* item = wear.at( i );
        if( !item )
            continue;

        int item_amount = item->get_amount( );
	    if( item_amount > 1000 )
            item_amount = 1000;

        std::string item_name = g_sdk.ws2s( item->get_weapon_name( ) );
        if( item_name.empty( ) )
            continue;

        std::string text = item_name;
        if( item_amount > 1 )
            text += xs( " x" ) + std::to_string( item_amount );

        std::transform( text.begin( ), text.end( ), text.begin( ), ::tolower );

        g_render.draw_text( vec4_t( clothes_position.x + 11, ( clothes_position.y + 25 ) + info_y, 150, 40 ), text, color, true, 11, font_flags );
        info_y += 13;
    }

    info_y = 0; // whaat...
}

void c_esp::draw_box( core::base_player* player ) {
    float box_width = bbox.right - bbox.left;
    float box_height = bbox.bottom - bbox.top;
                         
    color_t dropshadow_color = color_t( 0, 0, 0, 150 );

    float box_left_x = bbox.left - 1;
    float box_right_x = bbox.right - 1;

    auto draw_corner_box = [ & ] {
        /* dropshadow */

        // horizontal line ----

        //// left
        //g_render.horizontal_line( vec2_t( box_left_x - 1.f, bbox.top - 1.f ), box_width / 4 + 1, dropshadow_color );

        //// right
        //g_render.horizontal_line( vec2_t( box_right_x + 1.f, bbox.top - 1.f ), -( box_width / 4 + 1 ), dropshadow_color );

        //// vertical line |

        //// left
        //g_render.vertical_line( vec2_t( box_left_x - 1.f, bbox.top ), box_height / 4, dropshadow_color );

        //// right
        //g_render.vertical_line( vec2_t( box_right_x + 1.f, bbox.top - 1.f ), box_height / 4 + 1, dropshadow_color );

        ///* bottom */

        //// horizontal line ----

        //// left
        //g_render.horizontal_line( vec2_t( box_left_x - 1.f, bbox.bottom + 1.f ), box_width / 4 + 1, dropshadow_color );

        //// right
        //g_render.horizontal_line( vec2_t( box_right_x + 2.f, bbox.bottom + 1.f ), -( box_width / 4 + 2 ), dropshadow_color );

        //// vertical line |

        //// left
        //g_render.vertical_line( vec2_t( box_left_x - 1.f, bbox.bottom + 1.f ), -( box_height / 4 + 1 ), dropshadow_color );

        //// right
        //g_render.vertical_line( vec2_t( box_right_x + 1.f, bbox.bottom + 1.f ), -( box_height / 4 + 1 ), dropshadow_color );

        // main part

        // horizontal line ----
        // left
        g_render.horizontal_line( vec2_t( box_left_x, bbox.top ), box_width / 4, box_color );

        // right
        g_render.horizontal_line( vec2_t( box_right_x, bbox.top ), -( box_width / 4 ), box_color );

        // vertical line |
        // left
        g_render.vertical_line( vec2_t( box_left_x, bbox.top ), box_height / 4, box_color );

        // right
        g_render.vertical_line( vec2_t( box_right_x, bbox.top ), box_height / 4, box_color );

        // lower part

        /* bottom */

        // horizontal line ----
        // left
        g_render.horizontal_line( vec2_t( box_left_x, bbox.bottom ), box_width / 4, box_color );

        // right
        g_render.horizontal_line( vec2_t( box_right_x, bbox.bottom ), -( box_width / 4 ), box_color );

        // vertical line |
        // left
        g_render.vertical_line( vec2_t( box_left_x, bbox.bottom ), -( box_height / 4 ), box_color );

        // right
        g_render.vertical_line( vec2_t( box_right_x, bbox.bottom + 1.f ), -( box_height / 4 + 1 ), box_color );
    };

    if( options::visuals::box_type == 1 ) {
        g_render.outline_box( 
            vec2_t( bbox.left - 2, bbox.top - 1 ),
            vec2_t( box_width + 2, box_height + 2 ),
            color_t( 0, 0, 0, 150 ) );

        g_render.outline_box( 
            vec2_t( bbox.left - 1, bbox.top ),
            vec2_t( box_width, box_height ),
            box_color );
    }
    else if( options::visuals::box_type == 2 ) {
        draw_corner_box( );
    }
    else {
        draw_3d_box( player->get_bone_position( pelvis ), player->get_bone_position( head ), 2.f, options::visuals::box_color );
    }
}

void c_esp::draw_snap_lines( core::base_player* player ) {
    vec3_t bone_pos = player->get_bone_position( g_aimbot.aimbot_bone );
    vec2_t pos = g_sdk.world_to_screen( bone_pos );
    if( pos.is_zero( ) )
        return;

    core::player_model* model = player->get_model( );
    if( !model )
        return;

    if( player == g_aimbot.target 
        && options::aimbot::draw_target ) {
        g_render.draw_line( vec2_t( g_cheat.screen_size.x / 2, g_cheat.screen_size.y / 2 ), pos, options::aimbot::target_line_color );
    }
    else if( options::visuals::show_lines ) {
        g_render.draw_line( vec2_t( g_cheat.screen_size.x / 2, g_cheat.screen_size.y ), vec2_t( bbox.left + ( ( bbox.right - bbox.left ) / 2 ), bbox.bottom ), options::visuals::snap_lines_color );
    }
}

void c_esp::draw_view_direction( core::base_player* player )
{
    if( !options::visuals::show_view_direction )
        return;

    core::player_model* model = player->get_model( );
    if( !model )
        return;

    core::base_player* local = g_cheat.local;
    if( !local )
        return;

    core::player_eyes* eyes = player->get_eyes( );
    if( !eyes )
        return;

    vec3_t head_pos = player->get_bone_position( head );
    vec2_t head = g_sdk.world_to_screen( head_pos );

    vec2_t forward = g_sdk.world_to_screen( head_pos + ( eyes->get_bodyforward( ) * 2.f ) );

    if( head.is_zero( )
        || forward.is_zero( ) )
        return;

    g_render.draw_line( vec2_t( head.x, head.y ), vec2_t( forward.x, forward.y ), snap_lines_color );
}

void c_esp::draw_out_of_fov_arrows( core::base_player* player )
{
    core::base_player* local = g_cheat.local;
    if( !local )
        return;

    core::player_model* model = player->get_model( );
    if( !model )
        return;

    core::player_eyes* eyes = local->get_eyes( );
    if( !eyes )
        return;

    vec2_t center = g_cheat.screen_center;

    vec3_t local_pos = g_cheat.local_pos;
    vec3_t player_pos = model->get_position( );
    if( local_pos.is_zero( ) 
        || player_pos.is_zero( ) )
        return;

    vec3_t euler_angles = g_math.to_euler_angles( eyes->get_rotation( ) );

    const vec2_t position = vec2_t( local_pos.x - player_pos.x, local_pos.z - player_pos.z ).normalize( );

    float angle = atan2( position.x, position.y ) * 57.29578f - 180.f - euler_angles.y;

    vec2_t pos_0 = g_math.cos_tan_horizontal( angle, 10.f, center.x, center.y, 140 );
    vec2_t pos_1 = g_math.cos_tan_horizontal( angle + 2.f, 10.f, center.x, center.y, 130 );
    vec2_t pos_2 = g_math.cos_tan_horizontal( angle - 2.f, 10.f, center.x, center.y, 130 );

    g_render.gl_triangle( vec2_t( pos_0.x + 1, pos_0.y + 1 ), vec2_t( pos_1.x + 1, pos_1.y + 1 ), vec2_t( pos_2.x + 1, pos_2.y + 1 ), color_t( 0, 0, 0, 150 ) );
    g_render.gl_triangle( vec2_t( pos_0.x, pos_0.y ), vec2_t( pos_1.x, pos_1.y ), vec2_t( pos_2.x, pos_2.y ), oof_color );
}

void c_esp::draw_knocked_flag( core::base_player* player ) {
    if( !player->is_knocked( ) )
        return;

    g_render.draw_text( vec4_t( bbox.center, bbox.top - 25.f - ( esp_spacing[ 3 ] + esp_spacing[ 4 ] ), bbox.half, 30 ),
        xs( "^knocked^" ), knocked_color,
        true, 11, font_flags );
}

void c_esp::draw_ducking_flag( core::base_player* player ) {
    std::string name = std::string( );

    core::model_state* model_state = player->get_modelstate( );
    if( !model_state ) {
        esp_spacing[ 4 ] = 0;
        return;
    }

    if( !model_state->get_ducked( ) 
        || player->is_sleeping( )
        || player->is_knocked( ) ) {
        esp_spacing[ 4 ] = 0;
        return;
    }

    g_render.draw_text( vec4_t( bbox.center, bbox.top - 25.f - esp_spacing[ 3 ], bbox.half, 30 ), 
        xs( "*ducking*" ), ducking_color,
        true, 11, font_flags );

    if( esp_spacing[ 4 ] < 12 )
        esp_spacing[ 4 ] = 12;
}

void c_esp::draw_name( core::base_player* player, entity_type type ) {
    std::string name = std::string( );

    core::player_model* model = player->get_model( );
    if( !model )
        return;

    if( type == scientist )
        name  = xs( "scientist" );
    else if( type == tunnel_dweller )
        name  = xs( "tunnel dweller" );
    else if( model->is_npc( ) )
        name = xs( "npc" );
    else
        name = g_sdk.ws2s( player->get_username( ) );

    std::string new_name = std::string( );

    new_name = name;

    /* added to friend list. */
	for( auto& targets : m_friends )
	{
        if( player == targets )
            new_name = xs( "[f]" ) + name;
    }

    new_name.substr( 0, 18 ); // limit to 18 chars.

    g_render.draw_text( vec4_t( bbox.center, bbox.top - 25.f, bbox.half, 30 ), 
        new_name, name_color,
        true, 11, font_flags );

    if( esp_spacing[ 3 ] < 12 )
        esp_spacing[ 3 ] = 12;
}

void c_esp::draw_health_text( core::base_player* player ) {
    std::string hp_str = std::to_string( static_cast< int >( player->get_health( ) ) ) + "hp";

    g_render.draw_text( vec4_t( bbox.center, bbox.bottom, bbox.half, 30 ), 
        hp_str, health_text_color,
        true, 11, font_flags );
}   

void c_esp::draw_distance( core::base_player* player ) {
	std::string dist_str = std::to_string( static_cast< int >( g_cheat.local_pos.distance( player->get_model( )->get_position( ) ) ) ) + "m";

    g_render.draw_text( vec4_t( bbox.center, bbox.bottom + ( esp_spacing[ 0 ] + esp_spacing[ 1 ] ), bbox.half, 30 ), 
        dist_str, distance_color,
        true, 11, font_flags );

    if( esp_spacing[ 2 ] < 12 )
        esp_spacing[ 2 ] = 12;
}    

void c_esp::draw_bones( core::base_player* player )
{
    vec3_t head_pos = player->get_bone_position( head );
	vec3_t spine4_pos = player->get_bone_position( spine4 );
	vec3_t l_clavicle_pos = player->get_bone_position( l_clavicle );
	vec3_t l_upperarm_pos = player->get_bone_position( l_upperarm );
	vec3_t l_forearm_pos = player->get_bone_position( l_forearm );
	vec3_t l_hand_pos = player->get_bone_position( l_hand );
	vec3_t r_clavicle_pos = player->get_bone_position( r_clavicle );
	vec3_t r_upperarm_pos = player->get_bone_position( r_upperarm );
	vec3_t r_forearm_pos = player->get_bone_position( r_forearm );
	vec3_t r_hand_pos = player->get_bone_position( r_hand );
	vec3_t pelvis_pos = player->get_bone_position( pelvis );
	vec3_t l_hip_pos = player->get_bone_position( l_hip );
	vec3_t l_knee_pos = player->get_bone_position( l_knee );
	vec3_t l_ankle_scale_pos = player->get_bone_position( l_ankle_scale );
	vec3_t l_foot_pos = player->get_bone_position( l_foot );
	vec3_t r_hip_pos = player->get_bone_position( r_hip );
	vec3_t r_knee_pos = player->get_bone_position( r_knee );
	vec3_t r_ankle_scale_pos = player->get_bone_position( r_ankle_scale );
	vec3_t r_foot_pos = player->get_bone_position( r_foot );

	vec2_t head = g_sdk.world_to_screen( head_pos );
    vec2_t spine = g_sdk.world_to_screen( spine4_pos ); 
    vec2_t l_clavicle = g_sdk.world_to_screen( l_clavicle_pos );
    vec2_t l_upperarm = g_sdk.world_to_screen( l_upperarm_pos );
    vec2_t l_forearm = g_sdk.world_to_screen( l_forearm_pos );
    vec2_t l_hand = g_sdk.world_to_screen( l_hand_pos );
    vec2_t r_clavicle = g_sdk.world_to_screen( r_clavicle_pos );
    vec2_t r_upperarm = g_sdk.world_to_screen( r_upperarm_pos );
    vec2_t r_forearm = g_sdk.world_to_screen( r_forearm_pos ); 
    vec2_t r_hand = g_sdk.world_to_screen( r_hand_pos ); 
    vec2_t pelvis = g_sdk.world_to_screen( pelvis_pos );
    vec2_t l_hip = g_sdk.world_to_screen( l_hip_pos );
    vec2_t l_knee = g_sdk.world_to_screen( l_knee_pos );
    vec2_t l_ankle_scale = g_sdk.world_to_screen( l_ankle_scale_pos );
    vec2_t l_foot = g_sdk.world_to_screen( l_foot_pos ); 
    vec2_t r_hip = g_sdk.world_to_screen( r_hip_pos );
    vec2_t r_knee = g_sdk.world_to_screen( r_knee_pos );
    vec2_t r_ankle_scale = g_sdk.world_to_screen( r_ankle_scale_pos ); 
    vec2_t r_foot = g_sdk.world_to_screen( r_foot_pos );

	if( head.is_zero( )
        || spine.is_zero( )
        || l_clavicle.is_zero( )
        || l_upperarm.is_zero( )
        || l_forearm.is_zero( )
        || l_hand.is_zero( )
        || r_clavicle.is_zero( )
        || r_upperarm.is_zero( )
        || r_forearm.is_zero( )
        || r_hand.is_zero( )
        || pelvis.is_zero( )
		|| l_hip.is_zero( )
        || l_knee.is_zero( )
        || l_ankle_scale.is_zero( )
        || l_foot.is_zero( )
        || r_hip.is_zero( )
        || r_knee.is_zero( )
        || r_ankle_scale.is_zero( )
        || r_foot.is_zero( ) )
        return;

    core::player_model* model = player->get_model( );
    if( !model )
        return;

    vec3_t vis = model->get_position( );

    g_render.draw_line( vec2_t( head.x, head.y ), vec2_t( spine.x, spine.y ), skeleton_color );
    g_render.draw_line( vec2_t( spine.x, spine.y ), vec2_t( l_upperarm.x, l_upperarm.y ), skeleton_color );
    g_render.draw_line( vec2_t( l_upperarm.x, l_upperarm.y ), vec2_t( l_forearm.x, l_forearm.y ), skeleton_color );
    g_render.draw_line( vec2_t( l_forearm.x, l_forearm.y ), vec2_t( l_hand.x, l_hand.y ), skeleton_color );
    g_render.draw_line( vec2_t( spine.x, spine.y ), vec2_t( r_upperarm.x, r_upperarm.y ), skeleton_color );
    g_render.draw_line( vec2_t( r_upperarm.x, r_upperarm.y ), vec2_t( r_forearm.x, r_forearm.y ), skeleton_color );
    g_render.draw_line( vec2_t( r_forearm.x, r_forearm.y ), vec2_t( r_hand.x, r_hand.y ), skeleton_color );
    g_render.draw_line( vec2_t( spine.x, spine.y ), vec2_t( pelvis.x, pelvis.y ), skeleton_color );
    g_render.draw_line( vec2_t( pelvis.x, pelvis.y ), vec2_t( l_hip.x, l_hip.y ), skeleton_color );
    g_render.draw_line( vec2_t( l_hip.x, l_hip.y ), vec2_t( l_knee.x, l_knee.y ), skeleton_color );
    g_render.draw_line( vec2_t( l_knee.x, l_knee.y ), vec2_t( l_foot.x, l_foot.y ), skeleton_color );
    g_render.draw_line( vec2_t( pelvis.x, pelvis.y ), vec2_t( r_hip.x, r_hip.y ), skeleton_color );
    g_render.draw_line( vec2_t( r_hip.x, r_hip.y ), vec2_t( r_knee.x, r_knee.y ), skeleton_color );
    g_render.draw_line( vec2_t( r_knee.x, r_knee.y ), vec2_t( r_foot.x, r_foot.y ), skeleton_color );
}

void c_esp::draw_weapon( core::base_player* player ) {
    if( !player->get_held_item( ) ) {
        esp_spacing[ 0 ] = 0;
        return;
    }

    std::string weapon_name = g_sdk.ws2s( player->get_held_item( )->get_weapon_name( ) );

    std::transform( weapon_name.begin( ), weapon_name.end( ), weapon_name.begin( ), ::tolower );

    if( options::visuals::show_weapon ) {
        g_render.draw_text( vec4_t( bbox.center, bbox.bottom + esp_spacing[ 1 ], bbox.half, 30 ),
            weapon_name, weapon_color,
            true, 11, font_flags );

        if( esp_spacing[ 0 ] < 12 )
            esp_spacing[ 0 ] = 12;
    }
    else if( !options::visuals::show_weapon
        || weapon_name.empty( ) )
        esp_spacing[ 0 ] = 0;
}

void c_esp::reset_fly_hack( ) {
    distance_vertical = distance_horizontal =
    pause_time = current_horizontal_fly = 0.f;
    current_vertical_fly = 0.f;
}

void c_esp::apply_fly_violation( ) {
    core::base_player* local = g_cheat.local;
    if( !local
        || local 
        && ( local->get_life_state( ) || local->get_on_ladder( ) ) )
        return reset_fly_hack( );

    core::player_ticks* last_sent_tick = local->get_lastSentTick( );
    if( !last_sent_tick )
        return reset_fly_hack( );

    float radius = local->get_radius( );
    if( !radius )
        return reset_fly_hack( );

    float height = local->get_height( false );
    if( !height )
        return reset_fly_hack( );

    float jump_height = local->get_jumpheight( );
    if( !jump_height )
        return reset_fly_hack( );

    vec3_t last_position = last_sent_tick->get_position( );
    if( last_position.is_zero( ) )
        return reset_fly_hack( );

    vec3_t position = g_cheat.local_pos;
    if( position.is_zero( ) )
        return reset_fly_hack( );

    bool has_silent_walk = options::aimbot::exploits::movement::silent_walk && g_sdk.get_key( key_code::LeftShift );

    vec3_t new_position = ( last_position + position ) * 0.5f;
    vec3_t start = new_position + vec3_t( 0.f, radius - 2.f, 0.f );
    vec3_t end = new_position + vec3_t( 0.f, height - radius, 0.f );

    if( g_game.water_level_test( new_position - vec3_t( 0.f, 2.f, 0.f ), true, false, local ) )
        return reset_fly_hack( );

    float lower_radius = radius - 0.05f;

    bool in_air = !g_sdk.physics_checkcapsule( start, end, lower_radius, 1503731969, QueryTriggerInteraction::Ignore );
    if( local->get_modelstate( )->has_flag( on_ladder ) 
        && !has_silent_walk ) {
        distance_horizontal = 0.f;
        distance_vertical = 0.f;
        in_air = false;
    }

    if( in_air ) {
        vec3_t position_difference = position - last_position;
        float position_height = abs( position_difference.y );
        float position_length = position_difference.unity_length( );
        if( position_difference.y >= 0.f )
            distance_vertical += position_difference.y;

        if( position_height < position_length )
            distance_horizontal += position_length;
    }
    else {
        distance_horizontal = 0.f;
        distance_vertical = 0.f;
    }

    pause_time = max( 0.f, pause_time - g_sdk.get_time( ), 0.0f );

    double time_since_violation = max( ( pause_time > 0.0 ) ? 10 : 1.5, 0.0, 0.0 );

	float new_jump_time = jump_height + time_since_violation;
	max_vertical_fly = new_jump_time;
    current_vertical_fly = distance_vertical;

	float new_speed_time = 5.f + time_since_violation;
    max_horizontal_fly = new_speed_time;
	current_horizontal_fly = distance_horizontal;
}

void c_esp::show_reload_bar( ) {
    if( !options::visuals::show_reload_bar ) {
        indicators_spacing[ 0 ] = 0.f;
        return;
    }

    core::base_player* local_player = g_cheat.local;
    if( !local_player ) {
        indicators_spacing[ 0 ] = 0.f;
        return;
    }

    core::item* held_item = local_player->get_held_item( );
    if( !held_item ) {
        indicators_spacing[ 0 ] = 0.f;
        return;
    }   

    float max_size = 130;
    float red{ }, green{ }, x{ };

    static float alpha{ };

    if( held_item->has_reload_cooldown( ) ) {
        float reload_dur = held_item->get_next_reload_time( ) - g_cheat.global_time;
        float reload_dur_total = held_item->calculate_cooldown_time( held_item->get_next_reload_time( ), held_item->get_reload_time( ) ) - g_cheat.global_time;

        float percentage = ( ( ( reload_dur / reload_dur_total ) * 100.0f ) + 1.f ) / 100;

        float num = percentage;

		if( num ) {
            num = std::clamp( num, 0.f, 1.f );
		}

        x = ( num * max_size );

        x = std::clamp( x, 1.f, max_size );

        if( alpha < 1.f )
            alpha = std::lerp( alpha, 1.f, 0.15f );
    }
    else {
        alpha = std::lerp( alpha, 0.f, 0.15f );
    }

    if( alpha > 0.15f ) {
        if( indicators_spacing[ 0 ] < 12.f )
            indicators_spacing[ 0 ] = std::lerp( indicators_spacing[ 0 ], 10.f, 0.25f );

        color_t color = options::visuals::reload_bar_color;
        color.a *= alpha;

        g_render.draw_filled_rect( vec4_t( g_cheat.screen_center.x - ( max_size / 2 ), g_cheat.screen_center.y + ( 20.f ), max_size, 4.f ), color_t( 0.f, 0.f, 0.f, 255.f * alpha ) );
        g_render.draw_filled_rect( vec4_t( g_cheat.screen_center.x - ( max_size / 2 ) + 1, g_cheat.screen_center.y + ( 21.f ), x - 2, 2.f ), color );
    }
    else {
        indicators_spacing[ 0 ] = std::lerp( indicators_spacing[ 0 ], 0.f, 0.25f );
    }
}

void c_esp::show_desync_bar( ) {
	if( !options::visuals::show_desync_bar ) {
        indicators_spacing[ 1 ] = std::lerp( indicators_spacing[ 1 ], 0.f, 0.25f );
        return;
    }

    static float alpha = 0.f;
    float max_size = 130;

	float desync_time = ( g_sdk.realtimeSinceStartup( ) - g_cheat.local->lastSentTickTime( ) ) - 0.03125 * 3;
    float desync_amount = ( ( ( desync_time / 0.85f ) * 100.0f ) + 1.f ) / 100;

	float num = desync_amount;

	if( desync_amount < 0.1f )
        num = 0;

	if( num ) {
        num = std::clamp( num, 0.f, 1.f );

        if( alpha < 1.f )
            alpha = std::lerp( alpha, 1.f, 0.15f );
	}
    else {
        alpha = std::lerp( alpha, 0.f, 0.15f );
    }

    float x = ( desync_time * max_size );

    x = std::clamp( x, 1.f, max_size );

    if( alpha > 0.15f ) {
        if( indicators_spacing[ 1 ] < 10.f )
            indicators_spacing[ 1 ] = std::lerp( indicators_spacing[ 1 ], 10.f, 0.25f );

        color_t color = options::visuals::desync_bar_color;
        color.a *= alpha;

        g_render.draw_filled_rect( vec4_t( g_cheat.screen_center.x - ( max_size / 2 ), g_cheat.screen_center.y + ( 20.f + indicators_spacing[ 0 ] ), max_size, 4.f ),
            color_t( 0.f, 0.f, 0.f, 255.f * alpha ) );

        g_render.draw_filled_rect( vec4_t( g_cheat.screen_center.x - ( max_size / 2 ) + 1, g_cheat.screen_center.y + ( 21.f + indicators_spacing[ 0 ] ), x - 2, 2.f ),
            color );
    }
    else {
        indicators_spacing[ 1 ] = std::lerp( indicators_spacing[ 1 ], 0.f, 0.25f );
    }
}

void c_esp::fly_hack_bar( ) {
    static float alpha[ 2 ]{ 0.f };

    if( current_vertical_fly > 0.f
        && alpha[ 1 ] < 1.f )
        alpha[ 1 ] = std::lerp( alpha[ 1 ], 1.f, 0.15f );
    else if( alpha[ 1 ] > 0.f )
        alpha[ 1 ] = std::lerp( alpha[ 1 ], 0.f, 0.15f );

    if( current_horizontal_fly > 0.f
        && alpha[ 0 ] < 1.f )
        alpha[ 0 ] = std::lerp( alpha[ 0 ], 1.f, 0.15f );
    else if( alpha[ 0 ] > 0.f )
        alpha[ 0 ] = std::lerp( alpha[ 0 ], 0.f, 0.15f );

    if( options::visuals::indicators 
        && options::visuals::fly_hack_indicator ) {
	    float vert_percentage = ( current_vertical_fly / max_vertical_fly );
		const float red = vert_percentage * 255.f;
		const float green = 255.f - red;
        vert_percentage = std::clamp( vert_percentage, 0.f, 1.f );

        if( alpha[ 1 ] ) {
		    g_render.draw_filled_rect( vec4_t( g_cheat.screen_center.x - 200, g_cheat.screen_center.y - 426, 402, 6 ), 
                color_t( 0, 0, 0, 255.f * alpha[ 1 ] ) );

		    g_render.draw_filled_rect( vec4_t( g_cheat.screen_center.x - 199, g_cheat.screen_center.y - 425, 400 * vert_percentage, 4 ), 
                color_t( red, green, 0, 255.f * alpha[ 1 ] ) );
        }

		float hor_percentage = ( current_horizontal_fly / max_horizontal_fly );
		const float red_horizontal = hor_percentage * 255.f;
		const float green_horizontal = 255.f - red_horizontal;
        hor_percentage = std::clamp( hor_percentage, 0.f, 1.f );

        if( alpha[ 0 ] ) {
		    g_render.draw_filled_rect( vec4_t( g_cheat.screen_center.x - 200, g_cheat.screen_center.y - 446, 402, 6 ), 
                color_t( 0, 0, 0, 255.f * alpha[ 0 ] ) );

		    g_render.draw_filled_rect( vec4_t( g_cheat.screen_center.x - 199, g_cheat.screen_center.y - 445, 400 * hor_percentage, 4 ), 
                color_t( red_horizontal, green_horizontal, 0, 255.f * alpha[ 0 ] ) );
        }
    }
}

core::base_entity* c_esp::get_closest_object_of_class( std::string class_to_find, float max_dist )
{
	float best_distance = max_dist;
	core::base_entity* best_object = NULL;

	if( !g_cheat.client_entities )
		return NULL;

	uintptr_t entity_realm = *reinterpret_cast< uintptr_t* >( g_cheat.client_entities + 0x10 );
	if( !entity_realm )
		return NULL;

	uintptr_t buffer_list = *reinterpret_cast< uintptr_t* >( entity_realm + 0x28 );
	if( !buffer_list )
		return NULL;

	uintptr_t object_list = *reinterpret_cast< uintptr_t* >( buffer_list + 0x18 );
	if( !object_list )
		return NULL;

	int object_list_size = *reinterpret_cast< int* >( buffer_list + 0x10 );
	if( !object_list_size )
		return NULL;

	for( int i = 0; i < object_list_size; i++ )
	{
		core::base_entity* current_object = *reinterpret_cast< core::base_entity** >( object_list + ( 0x20 + ( i * sizeof( uint64_t ) ) ) );

		if( !current_object )
			continue;

		std::string class_name = current_object->get_class_name( );

		if( class_name == class_to_find )
		{
			uintptr_t base_mono_object = *reinterpret_cast< uintptr_t* >( ( uintptr_t )current_object + 0x10 );
			if( !base_mono_object )
				continue;

			uintptr_t object = *reinterpret_cast< uintptr_t* >( base_mono_object + 0x30 );
			if( !object )
				continue;

			uintptr_t object_class = *reinterpret_cast< uintptr_t* >( object + 0x30 );
			if( !object_class )
				continue;

			uintptr_t entity_visual = *reinterpret_cast< uintptr_t* >( object_class + sizeof( uint64_t ) );
			if( !entity_visual )
				continue;

			uintptr_t visual_state = *reinterpret_cast< uintptr_t* >( entity_visual + 0x38 );
			if( !visual_state )
				continue;

			vec3_t position = *reinterpret_cast< vec3_t* >( visual_state + 0x90 );

			float distance = g_cheat.local_pos.distance( position );

			if( distance < best_distance )
			{
				best_distance = distance;
				best_object = current_object;
			}
		}
	}

	return best_object;
}

void c_esp::do_melee_attack( vec3_t pos, core::base_entity* entity, bool is_player )
{
    core::base_player* local = g_cheat.local;
    if( !local )
        return;

    core::player_eyes* eyes = local->get_eyes( );
    if( !eyes )
        return;
        
    core::item* held_item = local->get_held_item( );
    if( !held_item 
        || !held_item->is_melee( ) )
        return;

	if( !entity ) 
		return;

	if( held_item->get_next_attack_time( ) >= g_sdk.get_fixedTime( )
        || held_item->get_deploy_delay( ) > held_item->get_time_since_deploy( ) )
		return;

	core::transform* trans = is_player ? reinterpret_cast< core::base_player* >( entity )->get_bone_transform( head ) : entity->get_transform( );
	if( !trans )
		return;

	vec3_t transform_pos = trans->inverse_tranform_point( pos );

	core::Ray ray = core::Ray( eyes->get_position( ), ( pos - eyes->get_position( ) ).normalized( ) );

	core::hit_test* hit = core::hit_test::New( );
	if( hit ) {
		hit->set_hit_entity( entity );
		hit->set_did_hit( true );
		hit->set_max_distance( melee_max_dist );
		hit->set_hit_transform( trans );
		hit->set_attack_ray( ray );
		hit->set_hit_normal( transform_pos );
		hit->set_hit_hitpoint( transform_pos );
		hit->set_damage_properties( held_item->get_damage_properties( ) );
        held_item->process_attack( hit );
        held_item->start_attack_cooldown( held_item->get_repeat_delay( ) );
	}
}
	rmb = get_rmb( );
	cursor1 = vec2_t( position.x + 150, position.y + 45 );#pragma once

namespace options {
	inline bool friend_system = true, load_cfg = false, save_cfg = false, rainbow_accent = false;
	inline int cfg_index = 0, font_flags = 1, add_friend_key{ }, first_tab{ }, color_tab = 0, tab_selection{ };
	inline color_t accent_color = color_t( 255, 255, 255 );

	namespace visuals {
		inline bool draw_visuals{ true }, indicators{ }, fly_hack_indicator{ }, draw_tracers{ }, offscreen_arrows{ true }, draw_radar{ },
			show_name{ true }, show_weapon{ true }, show_knocked_flag{ true }, show_ducking_flag{ true },
			show_health{ true }, show_health_text{ false }, show_distance{ },
			show_hotbar{ }, show_clothes{ }, show_lines{ }, show_view_direction{ }, can_show_sleepers{ true },
			can_show_knocked{ true }, can_show_npc{ true },
			chams{ }, rgb_chams{ }, draw_bones{ true },
			show_watermark{ }, local_trails{ }, show_last_sent_tick{ }, 
			show_desync_bar{ }, show_reload_bar{ }, modify_health_color{ };

		inline bool can_show_sleepers_oof{ true },
			can_show_knocked_oof{ true }, can_show_npc_oof{ true };

		inline bool class_name_debug{ }, prefab_name_debug{ }, is_home_pos{ };

		inline int max_player_distance{ 750 }, offscreen_distance{ 100 }, health_thickness{ 1 };

		inline int box_type{ }, chams_type{ }, remove_positions_key{ }, save_pos_key{ };

		inline color_t tracers_color{ 255, 255, 255 }, desync_bar_color{ 255, 255, 255 }, trails_color{ 255, 255, 255 }, reload_bar_color{ 255, 255, 255 };

		namespace world {
			inline bool master_switch{ false }, show_stashes{ },
				show_corpse{ }, show_backpack{ }, change_rayleigh{ },
				todsky{ }, show_grenades{ }, night_stars{ }, clear_underwater{ }, change_world_color{ }, modify_rain{ };

			inline bool show_heal{ }, show_weapons{ }, show_melee_weapons{ }, show_everything{ };

			inline bool show_distance{ }, show_health{ }, show_item_amount{ };

			inline bool stars_size{ }, stars{ }, ambient{ }, mie_changer{ }, rayleigh_changer{ }, brightness_changer{ }, aspect_changer{ };

			inline bool show_sulfur_ore{ },
				show_metal_ore{ },
				show_stone_ore{ },
				show_tool_cupboard{ },
				show_box_storages{ };

			inline bool show_ammo_nails_arrows{ };

			inline bool show_supply_signals{ }, show_supply_drops{ };

			inline bool show_oil_barrel{ },
				show_regular_barrels{ },
				show_underwater_crate{ },
				show_elite_crate{ }, show_military_crate{ }, show_bradley_crate{ },
				show_food_crate{ }, show_medical_crate{ }, show_diesel_fuel{ }, show_helicopter_crate{ }, show_hackable_locked_crate{ },
				show_normal_crate{ }, show_chickens{ }, show_small_crate{ }, show_mine_crate{ },
				show_tool_box{ },
				show_boars{ }, show_wolves{ }, show_horses{ },
				show_sharks{ }, show_deers{ }, show_polar_bears{ },
				show_bears{ }, show_sulfur_collectibles{ },
				show_metal_collectibles{ }, show_wood_collectibles{ }, 
				show_vending_machine{ }, show_drone{ }, show_recycler{ },
				show_stone_collectibles{ };

			inline bool show_hemp{ }, show_mushroom{ }, show_pumpkin{ },
				show_berrys{ }, show_corns{ }, show_potatos{ };

			inline bool show_modular_car{ }, show_two_modules_car{ }, 
				show_minicopter{ }, show_scrap_helicopter{ }, show_rhib{ }, show_bradley_apc{ },
				show_kayak{ }, show_small_motorboat{ }, show_solo_submarine{ }, show_duo_submarine{ };

			inline bool show_landmines{ }, show_npc_turrets{ }, show_auto_turrets{ }, show_shotgun_traps{ },
				show_tesla_coil{ }, show_flame_turrets{ }, show_sam_site{ },
				show_land_spikes{ }, show_bear_trap{ };

			inline float size_stars_amount{ }, brightness_stars_amount{ }, ambient_value{ }, aspect_value{ },
				light_value{ }, rayleigh_amount{ }, brightness_amount{ }, mie_amount{ }, rain_amount{ };
			
			inline int max_stash_distance{ 500 },
				max_animal_distance{ 500 }, max_trap_distance{ 500 },
				max_storage_distance{ 500 }, max_vehicle_distance{ 500 },
				max_raid_distance{ 500 }, max_item_distance{ 500 },
				max_respawn_points_distance{ 500 }, max_helicopter_distance{ 500 },
				max_corpse_distance{ 500 }, max_ore_collectibles_distance{ 500 },
				max_container_distance{ 500 }, max_food_collectibles_distance{ 500 }, max_grenade_distance{ 500 },
				max_ores_distance{ 500 }, max_barrels_distance{ 500 }, max_cars_distance{ 500 };//, rayleigh_value{ };

			inline color_t color_heal{ 255, 255, 255 }, color_weapons{ 255, 255, 255 }, color_melee_weapons{ 255, 255, 255 }, color_everything{ 255, 255, 255 }, color_backpack{ 255, 255, 255 };

			inline color_t color_stashes{ 255, 255, 255 }, color_animals{ 255, 255, 255 },
				color_traps{ 255, 255, 255 }, color_storages{ 255, 255, 255 }, color_vehicles{ 255, 255, 255 },
				color_raid{ 255, 255, 255 }, color_item{ 255, 255, 255 }, color_respawn_points{ 255, 255, 255 },
				color_helicopter{ 255, 255, 255 }, color_ores{ 255, 255, 255 },
				color_corpse{ 255, 255, 255 }, color_ore_collectibles{ 255, 255, 255 }, color_food_collectibles{ 255, 255, 255 },
				color_loot_containers{ 255, 255, 255 }, color_barrels{ 255, 255, 255 }, color_cars{ 255, 255, 255 };

			inline color_t color_sulfur_ore{ 255, 255, 255 },
				color_metal_ore{ 255, 255, 255 },
				color_stone_ore{ 255, 255, 255 },
				color_tool_cupboard{ 255, 255, 255 },
				color_box_storages{ 255, 255, 255 };

			inline bool show_patrol_helicopter{ }, show_attack_helicopter{ }, show_chinook_helicopter{ };
			inline color_t color_patrol_helicopter{ 255, 255, 255 }, color_attack_helicopter{ 255, 255, 255 }, color_chinook_helicopter{ 255, 255, 255 };

			inline color_t color_ammo_nails_arrows{ 255, 255, 255 };

			inline color_t color_supply_signals{ 255, 255, 255 }, color_supply_drops{ 255, 255, 255 };

			inline color_t color_oil_barrel{ 255, 255, 255 },
				color_regular_barrels{ 255, 255, 255 },
				color_underwater_crate{ 255, 255, 255 },
				color_elite_crate{ 255, 255, 255 }, color_military_crate{ 255, 255, 255 }, color_bradley_crate{ 255, 255, 255 },
				color_food_crate{ 255, 255, 255 }, color_medical_crate{ 255, 255, 255 }, color_diesel_fuel{ 255, 255, 255 }, color_helicopter_crate{ 255, 255, 255 }, color_hackable_locked_crate{ 255, 255, 255 },
				color_normal_crate{ 255, 255, 255 }, color_chickens{ 255, 255, 255 }, color_small_crate{ 255, 255, 255 }, color_mine_crate{ 255, 255, 255 },
				color_tool_box{ 255, 255, 255 },
				color_boars{ 255, 255, 255 }, color_wolves{ 255, 255, 255 }, color_horses{ 255, 255, 255 },
				color_sharks{ 255, 255, 255 }, color_deers{ 255, 255, 255 }, color_polar_bears{ 255, 255, 255 },
				color_bears{ 255, 255, 255 }, color_sulfur_collectibles{ 255, 255, 255 },
				color_metal_collectibles{ 255, 255, 255 }, color_wood_collectibles{ 255, 255, 255 }, 
				color_vending_machine{ 255, 255, 255 }, color_drone{ 255, 255, 255 }, color_recycler{ 255, 255, 255 },
				color_stone_collectibles{ 255, 255, 255 };

			inline color_t color_hemp{ 255, 255, 255 }, color_mushroom{ 255, 255, 255 }, color_pumpkin{ 255, 255, 255 },
				color_berrys{ 255, 255, 255 }, color_corns{ 255, 255, 255 }, color_potatos{ 255, 255, 255 };

			inline color_t color_modular_car{ 255, 255, 255 }, color_two_modules_car{ 255, 255, 255 }, 
				color_minicopter{ 255, 255, 255 }, color_scrap_helicopter{ 255, 255, 255 }, color_rhib{ 255, 255, 255 }, color_bradley_apc{ 255, 255, 255 },
				color_kayak{ 255, 255, 255 }, color_small_motorboat{ 255, 255, 255 }, color_solo_submarine{ 255, 255, 255 }, color_duo_submarine{ 255, 255, 255 };

			inline color_t color_landmines{ 255, 255, 255 }, color_npc_turrets{ 255, 255, 255 }, color_auto_turrets{ 255, 255, 255 }, color_shotgun_traps{ 255, 255, 255 },
				color_tesla_coil{ 255, 255, 255 }, color_flame_turrets{ 255, 255, 255 }, color_sam_site{ 255, 255, 255 },
				color_land_spikes{ 255, 255, 255 }, color_bear_trap{ 255, 255, 255 };

			inline color_t ambient_color{ 255, 255, 255 }, sky_color{ 255, 255, 255 };
		}

		inline color_t name_color{ 255, 255, 255 }, box_color{ 255, 255, 255 },
			skeleton_color{ 255, 255, 255 }, radar_color{ },
			oof_color{ 255, 255, 255 }, snap_lines_color{ 255, 255, 255 }, distance_color{ 255, 255, 255 }, weapon_color{ 255, 255, 255 },
			view_direction_color{ 255, 255, 255 }, knocked_color{ 0, 255, 0 }, ducking_color{ 255, 0, 0 }, 
			custom_health_color{ 255, 255, 255 }, health_text_color{ 255, 255, 255 };

		inline color_t vis_name_color{ 255, 255, 255 }, vis_box_color{ 255, 255, 255 },
			vis_skeleton_color{ 255, 255, 255 }, vis_radar_color{ },
			vis_oof_color{ 255, 255, 255 }, vis_snap_lines_color{ 255, 255, 255 }, vis_distance_color{ 255, 255, 255 }, vis_weapon_color{ 255, 255, 255 },
			vis_view_direction_color{ 255, 255, 255 }, vis_knocked_color{ 0, 255, 0 }, vis_ducking_color{ 255, 0, 0 },
			vis_custom_health_color{ 255, 255, 255 }, vis_health_text_color{ 255, 255, 255 };

		inline color_t npc_name_color{ 255, 255, 255 }, npc_box_color{ 255, 255, 255 },
			npc_skeleton_color{ 255, 255, 255 }, npc_radar_color{ },
			npc_oof_color{ 255, 255, 255 }, npc_snap_lines_color{ 255, 255, 255 }, npc_distance_color{ 255, 255, 255 }, npc_weapon_color{ 255, 255, 255 },
			npc_view_direction_color{ 255, 255, 255 }, npc_knocked_color{ 0, 255, 0 }, npc_ducking_color{ 255, 0, 0 },
			npc_custom_health_color{ 255, 255, 255 }, npc_health_text_color{ 255, 255, 255 };

		inline color_t npc_vis_name_color{ 255, 255, 255 }, npc_vis_box_color{ 255, 255, 255 },
			npc_vis_skeleton_color{ 255, 255, 255 }, npc_vis_radar_color{ },
			npc_vis_oof_color{ 255, 255, 255 }, npc_vis_snap_lines_color{ 255, 255, 255 }, npc_vis_distance_color{ 255, 255, 255 }, npc_vis_weapon_color{ 255, 255, 255 },
			npc_vis_view_direction_color{ 255, 255, 255 }, npc_vis_knocked_color{ 0, 255, 0 }, npc_vis_ducking_color{ 255, 0, 0 },
			npc_vis_custom_health_color{ 255, 255, 255 }, npc_vis_health_text_color{ 255, 255, 255 };

		inline color_t chams_color{ 131, 171, 235 }, chams_visible{ 214, 224, 255 }, pos_color{ 255, 255, 255 };
	}

	namespace aimbot {
		inline bool aim_check{ },
			smoothness{ true }, auto_fire{ }, should_simulate_movement{ true },
			draw_fov{ }, draw_crosshair{ }, draw_target{ },
			aim_sleepers{ }, aim_npc{ true }, aim_helicopter{ }, aim_knocked{ },
			manipulation{ }, kill_aura{ }, auto_reload{ },
			aim_nearest_bone{ true };

		inline color_t fov_circle_color{ 255, 255, 255 }, target_line_color{ 255, 0, 0 };

		inline int aim_bone{ }, manipulation_key{ 1 }, aim_type{ 2 }, smooth_type{ },
			max_target_distance{ 750 }, fov_amount{ 150 };

		inline float smoothness_amount{ 2.f };

		namespace exploits {
			inline bool force_on_phone{ };
			namespace movement {
				inline bool infinite_jump{ }, stopper_fly{ },
					climb_assist{ }, fly_hack{ }, omni_sprint{ }, silent_walk{ },
					high_jump{ }, walk_on_water{ }, always_sprint{ }, walk_through_trees{ },
					walk_through_players{ }, disable_slow_down_melee{ }, modify_clothing_speed{ },
					increase_height{ };

				inline int fly_key{ 102 }, silent_walk_key{ 304 }, 
					ignore_key{ 118 }, omni_sprint_key{ 304 }, 
					increase_height_key{ 120 };

				inline int fly_speed{ 415 };

				inline float clothing_speed{ };

				inline float jump_height{ }, omni_sprint_speed{ }, height_amount{ };
			}
			namespace combat {
				inline bool automatic_weapons{ }, semi_automatic_weapons{ }, burst_weapons{ }, unlock_aim_on_jugger{ }, aim_bolt_cycle{ },
					extended_melee{ }, no_spread{ }, no_sway{ }, modify_eoka_chance{ },
					no_recoil{ }, modify_can_attack{ }, can_attack_in_vehicles{ }, unlock_view_angles{ },
					big_bullets{ }, quick_bullets{ }, pierce{ }, spoof_hit_distance{ }, no_shot_gun_spread{ }, head_teleportation{ };

				inline float reduce_recoil{ 100.f }, reduce_spread{ 100.f }, bullet_distance{ },
					eoka_chance{ }, attack_radius{ },
					bullet_size{ };

				inline int teleport_key{ 116 };
				inline int bullet_speed{ 50 };
			}
			namespace time {
				inline bool fast_heal{ }, fast_switch{ }, time_modifier{ },
					rapid_fire{ }, instant_charge_compound{ }, fake_lag{ }, fake_lag_on{ },
					instant_revive{ }, fast_bow{ }, always_revive_target{ }, fast_loot{ };

				inline float fake_lag_amount{ }, time_speed{ }, rapid_fire_speed{ };
				inline int fake_lag_key{ 102 }, revive_key{ 101 };
			}
			namespace misc {
				inline bool keep_wounded_alive{ }, always_hit_weak_spot{ }, long_neck{ },
					long_neck_right{ }, long_neck_left{ }, disable_land_damage{ },
					fov_changer{ }, zoom_fov{ true }, suicide{ }, fake_fire{ }, 
					fake_admin{ }, fake_fire_on{ }, debug_camera{ }, spin_bot{ }, gesture_spam{ }, interactive_debug{ },
					disarm_landmines{ }, stop_recycler{ }, use_max_view{ }, auto_pickup{ }, auto_grade{ }, auto_pickup_items{ }, 
					pickup_everything{ }, no_viewmodel_bob{ }, auto_codelock{ }, always_grade{ }, always_codelock{ },
					always_pickup{ }, auto_untie_crates{ }, auto_farm_ores{ }, auto_farm_trees{ }, auto_farm_only_hotspot{ }, 
					auto_farm_barrels{ }, no_lower{ }, no_flash{ };

				inline float long_neck_height{ 150.f }, long_neck_right_amount{ 150.f }, 
					long_neck_left_amount{ 150.f }, delay_fake_fire{ }, 
					max_grade_distance{ 5.f }, max_lock_distance{ 5.f }, max_item_distance{ 3.f }, max_collectible_distance{ 3.f };

				inline int zoom_fov_amount{ 10 }, fov_amount{ 90 }, gesture_type{ }, grade_tier{ }, code_lock_code{ }, codelock_key{ }, pickup_key{ }, grade_key{ };

				inline int view_left{ 41 }, view_right{ 42 },
					view_height{ 42 }, zoom_key{ 41 }, fake_fire_key{ 41 },
					debug_camera_key{ 3 }, suicide_key{ 7 };
			}
		}
	}
}
	cursor2 = vec2_t( position.x + 455, position.y + 45 );
}
    <ClInclude Include="core\utilities\math.hpp" />#include "il2cpp.hpp"
#include <map>

std::map< const char*, uintptr_t > this_classes;
std::map< const char*, uintptr_t > method_list;
std::map< const char*, uintptr_t > field_list;

namespace il2mgr {
	void init( )
	{
		game_assembly = LI_MODULE( ( "GameAssembly.dll" ) ).get< uintptr_t >( );
		unity_player = LI_MODULE( ( "UnityPlayer.dll" ) ).get< uintptr_t >( );

		using il2cpp_domain_get = uintptr_t( * )( );
		methods::domain_get = LI_FIND_DEF( il2cpp_domain_get );

		using il2cpp_class_get_methods = uintptr_t( * )( uintptr_t, uintptr_t* );
		methods::class_get_methods = LI_FIND_DEF( il2cpp_class_get_methods );

		using il2cpp_method_get_param = uintptr_t( * )( uintptr_t, int );
		methods::method_get_param = LI_FIND_DEF( il2cpp_method_get_param );

		using il2cpp_method_get_param_count = int ( * )( uintptr_t );
		methods::method_get_param_count = LI_FIND_DEF( il2cpp_method_get_param_count );

		using il2cpp_assembly_get_image = uintptr_t( * )( uintptr_t );
		methods::assembly_get_image = LI_FIND_DEF( il2cpp_assembly_get_image );

		using il2cpp_domain_get_assemblies = uintptr_t * ( * )( void*, uintptr_t* );
		methods::domain_get_assemblies = LI_FIND_DEF( il2cpp_domain_get_assemblies );

		using il2cpp_class_from_name = uintptr_t( * )( uintptr_t, const char*, const char* );
		methods::class_from_name = LI_FIND_DEF( il2cpp_class_from_name );

		using il2cpp_resolve_icall = uintptr_t( * )( const char* );
		methods::resolve_icall = LI_FIND_DEF( il2cpp_resolve_icall );

		using il2cpp_class_get_field_from_name = uintptr_t( * )( uintptr_t, const char* );
		methods::class_get_field_from_name = LI_FIND_DEF( il2cpp_class_get_field_from_name );

		using il2cpp_field_static_get_value = uintptr_t( * )( uintptr_t, uintptr_t* );
		methods::field_static_get_value = LI_FIND_DEF( il2cpp_field_static_get_value );

		using il2cpp_class_get_fields = uintptr_t( * )( uintptr_t, uintptr_t* );
		methods::class_get_fields = LI_FIND_DEF( il2cpp_class_get_fields );

		using il2cpp_field_get_offset = uintptr_t( * )( uintptr_t );
		methods::field_get_offset = LI_FIND_DEF( il2cpp_field_get_offset );

		using il2cpp_object_new = uintptr_t( * )( uintptr_t );
		methods::object_new = LI_FIND_DEF( il2cpp_object_new );

		using il2cpp_type_get_object = uintptr_t( * )( uintptr_t );
		methods::type_get_object = LI_FIND_DEF( il2cpp_type_get_object );

		using il2cpp_class_get_type = uintptr_t( * )( uintptr_t );
		methods::class_get_type = LI_FIND_DEF( il2cpp_class_get_type );

		using il2cpp_runtime_class_init = uintptr_t( * )( uintptr_t );
		methods::runtime_class_init = LI_FIND_DEF( il2cpp_runtime_class_init );

		using il2cpp_string_new_wrapper = il2cppstring * ( * )( const char* );
		methods::new_string = LI_FIND_DEF( il2cpp_string_new_wrapper );
	}

	uintptr_t init_class( const char* name, const char* name_space )
	{
		uintptr_t domain = methods::domain_get( );

		if( !domain )
			return NULL;

		uintptr_t nrofassemblies;
		uintptr_t* assemblies = methods::domain_get_assemblies( ( void* )domain, &nrofassemblies );

		for( int i = 0; i < nrofassemblies; i++ )
		{
			uintptr_t img = methods::assembly_get_image( assemblies[ i ] );

			uintptr_t kl = methods::class_from_name( img, name_space, name );
			if( !kl )
				continue;

			return kl;
		}

		return NULL;
	}

	uintptr_t type_object( const char* name_space, const char* name )
	{
		uintptr_t this_class = init_class( name, name_space );
		return methods::type_get_object( methods::class_get_type( this_class ) );
	}

	uintptr_t method( std::string kl, std::string name, int param_count, const char* name_space, bool param_check, int param_idx, std::string param_name )
	{
		uintptr_t this_class = init_class( kl.c_str( ), name_space );
		if( !this_class )
			return NULL;

		if( !param_check )
			return methods::class_get_method_from_name( this_class, name.c_str( ), param_count );
		else
		{
			uintptr_t nrofmethods;
			uintptr_t methods;
			methods = methods::class_get_methods( this_class, &nrofmethods );
			while( methods = methods::class_get_methods( this_class, &nrofmethods ) )
			{
				char* method_name = *reinterpret_cast< char** >( methods + 0x10 );
				if( std::string( method_name ) == name )
				{
					uintptr_t args = *reinterpret_cast< uintptr_t* >( methods + 0x28 );
					char* arg_name = *reinterpret_cast< char** >( args + 1 * 0x18 );
				}
			}
		}

		return NULL;
	}

	uintptr_t hook( void* our_func, std::string kl, std::string name, int arg, const char* name_space )
	{
		uintptr_t il2mgr_method = method( kl.c_str( ), name.c_str( ), arg, name_space );
		*reinterpret_cast< void** >( il2mgr_method ) = our_func;

		void* written = *reinterpret_cast< void** >( il2mgr_method );
		if( !written )
			return NULL;

		return il2mgr_method;
	}

	uintptr_t hook_virt( const char* classname, const char* function_to_hook, void* our_func, int param_count, const char* name_space )
	{
		uintptr_t this_method = method( classname, function_to_hook, param_count, name_space );
		if( !this_method )
			return NULL;

		uintptr_t search = *reinterpret_cast< uintptr_t* >( this_method );
		uintptr_t table = init_class( classname, name_space );

		if( search == reinterpret_cast< uintptr_t >( our_func ) )
			return reinterpret_cast< uintptr_t >( our_func );

		for( uintptr_t i = table; i <= table + 0x10000; i += 0x1 ) {
			uintptr_t addr = *reinterpret_cast< uintptr_t* >( i );
			if( addr == search )
			{
				*reinterpret_cast< uintptr_t* >( i ) = reinterpret_cast< uintptr_t >( our_func );
				return addr;
			}
		}

		return NULL;
	}

	uintptr_t field( uintptr_t this_class, const char* name )
	{
		return methods::class_get_field_from_name( this_class, name );
	}

	uintptr_t value( const char* kl, const char* name, bool get_offset, const char* name_space )
	{
		uintptr_t this_class = init_class( kl, name_space );

		if( !this_class )
			return NULL;

		uintptr_t this_field = field( this_class, name );
		if( get_offset )
		{
			uintptr_t out = 0;
			uintptr_t il2cpp_field = NULL;
			uintptr_t field_offset = NULL;

			while( il2cpp_field = methods::class_get_fields( this_class, &out ) )
			{
				char* char_name = ( char* )*reinterpret_cast< uintptr_t* >( il2cpp_field );
				if( !char_name )
					continue;

				uintptr_t offset = methods::field_get_offset( il2cpp_field );
				std::string field_name = std::string( char_name );
				if( name == field_name )
				{
					field_offset = offset;
					break;
				}
			}
			return field_offset;
		}

		uintptr_t static_value;
		methods::field_static_get_value( this_field, &static_value );
		if( static_value )
			return static_value;

		return NULL;
	}
}
#pragma once
#include "../includes/includes.hpp"
#include "../utilities/lazy_importer.hpp"

#define STR_MERGE_IMPL( a, b ) a##b
#define STR_MERGE( a, b ) STR_MERGE_IMPL( a, b )
#define MAKE_PAD( size ) STR_MERGE( _pad, __COUNTER__ )[ size ]
#define DEFINE_MEMBER_N( type, name, offset ) struct {unsigned char MAKE_PAD( offset ); type name;}

namespace il2mgr
{
	inline uintptr_t game_assembly = NULL;
	inline uintptr_t unity_player = NULL;

	void init( );
	uintptr_t init_class( const char* name, const char* name_space = ( "" ) );
	uintptr_t method( std::string kl, std::string name, int param_count, const char* name_space = ( "" ), bool param_check = false, int param_idx = 0, std::string param_name = "" );
	uintptr_t hook( void* our_func, std::string kl, std::string name, int arg, const char* name_space = ( "" ) );
	uintptr_t hook_virt( const char* classname, const char* function_to_hook, void* our_func, int param_count, const char* name_space = ( "" ) );
	uintptr_t field( uintptr_t klass, const char* field_name );
	uintptr_t value( const char* kl, const char* name, bool get_offset = true, const char* name_space = ( "" ) );
	uintptr_t type_object( const char* name_space, const char* name );

	class il2cppstring
	{
	public:
		char pad_0000[ 0x10 ];
		int len;
		wchar_t buffer[ 0 ];

		static il2cppstring* New( const char* str );
	};

	namespace methods
	{
		using il2cpp_domain_get = uintptr_t( * )( );
		static il2cpp_domain_get domain_get = LI_FIND_DEF( il2cpp_domain_get );

		using il2cpp_class_get_methods = uintptr_t( * )( uintptr_t, uintptr_t* );
		static auto class_get_methods = LI_FIND_DEF( il2cpp_class_get_methods );

		using il2cpp_method_get_param = uintptr_t( * )( uintptr_t, int );
		static auto method_get_param = LI_FIND_DEF( il2cpp_method_get_param );

		using il2cpp_method_get_param_count = int ( * )( uintptr_t );
		static auto method_get_param_count = LI_FIND_DEF( il2cpp_method_get_param_count );

		using il2cpp_assembly_get_image = uintptr_t( * )( uintptr_t );
		static auto assembly_get_image = LI_FIND_DEF( il2cpp_assembly_get_image );

		using il2cpp_domain_get_assemblies = uintptr_t * ( * )( void* domain, uintptr_t* size );
		static auto domain_get_assemblies = LI_FIND_DEF( il2cpp_domain_get_assemblies );

		using il2cpp_object_new = uintptr_t( * )( uintptr_t );
		static auto object_new = LI_FIND_DEF( il2cpp_object_new );

		using il2cpp_type_get_object = uintptr_t( * )( uintptr_t );
		static auto type_get_object = LI_FIND_DEF( il2cpp_type_get_object );

		using il2cpp_class_get_type = uintptr_t( * )( uintptr_t );
		static auto class_get_type = LI_FIND_DEF( il2cpp_class_get_type );

		using il2cpp_class_from_name = uintptr_t( * )( uintptr_t, const char*, const char* );
		static auto class_from_name = LI_FIND_DEF( il2cpp_class_from_name );

		using il2cpp_resolve_icall = uintptr_t( * )( const char* );
		static auto resolve_icall = LI_FIND_DEF( il2cpp_resolve_icall );

		using il2cpp_class_get_field_from_name = uintptr_t( * )( uintptr_t, const char* );
		static auto class_get_field_from_name = LI_FIND_DEF( il2cpp_class_get_field_from_name );

		using il2cpp_field_static_get_value = uintptr_t( * )( uintptr_t, uintptr_t* );
		static auto field_static_get_value = LI_FIND_DEF( il2cpp_field_static_get_value );

		using il2cpp_class_get_fields = uintptr_t( * )( uintptr_t, uintptr_t* );
		static auto class_get_fields = LI_FIND_DEF( il2cpp_class_get_fields );

		using il2cpp_field_get_offset = uintptr_t( * )( uintptr_t );
		static auto field_get_offset = LI_FIND_DEF( il2cpp_field_get_offset );

		using il2cpp_runtime_class_init = uintptr_t( * )( uintptr_t );
		static auto runtime_class_init = LI_FIND_DEF( il2cpp_runtime_class_init );

		using il2cpp_string_new_wrapper = il2cppstring * ( * )( const char* );
		static auto new_string = LI_FIND_DEF( il2cpp_string_new_wrapper );

		using  il2cpp_class_get_method_from_name = uintptr_t( * )( uintptr_t, const char*, int );
		static il2cpp_class_get_method_from_name class_get_method_from_name = LI_FIND_DEF( il2cpp_class_get_method_from_name );
	}
}
#include "offsets.hpp"
#include "il2cpp.hpp"

namespace offsets
{
    // --- Системные и Время ---
    uintptr_t time_get_time = 0;
    uintptr_t time_get_deltaTime = 0;
    uintptr_t real_time_since_startup = 0;
    uintptr_t get_fixed_time = 0;
    uintptr_t get_mousePosition = 0;
    uintptr_t screen_get_width = 0;
    uintptr_t screen_get_height = 0;

    // --- Базовые сущности (BasePlayer / Entity) ---
    uintptr_t MainCamera_RVA = 0x0; // Нужно обновить под текущий патч
    uintptr_t movement = 0x4d0;
    uintptr_t playerInventory = 0x690;
    uintptr_t clActiveItem = 0x5b0;
    uintptr_t playerModel = 0x4a8;
    uintptr_t clientTickInterval = 0x610;
    uintptr_t teamID = 0x590;
    uintptr_t _health = 0x22c;
    uintptr_t _maxHealth = 0x230;
    uintptr_t lifestate = 0x224;
    uintptr_t mounted = 0x5f0;

    // --- Глаза и Движение ---
    uintptr_t body_rotation = 0x44;
    uintptr_t view_offset = 0x38;
    uintptr_t gravityMultiplier = 0x84;

    // --- Отрисовка Unity (Rendering) ---
    uintptr_t get_material = 0;
    uintptr_t get_shader = 0;
    uintptr_t find = 0;
    uintptr_t set_shader = 0;
    uintptr_t CreateWithShader = 0;
    uintptr_t set_color = 0;
    uintptr_t set_pass = 0;
    uintptr_t set_float = 0;
    uintptr_t set_int = 0;
    uintptr_t push_matrix = 0;
    uintptr_t pop_matrix = 0;
    uintptr_t begin = 0;
    uintptr_t vertex = 0;
    uintptr_t end = 0;
    uintptr_t get_texture = 0;

    // --- Debug Draw (DDraw) ---
    uintptr_t ddraw_get = 0;
    uintptr_t ddraw_line = 0;
    uintptr_t ddraw_sphere = 0;
    uintptr_t ddraw_arrow = 0;
    uintptr_t ddraw_text = 0;

    // --- GUI / Инструменты ---
    uintptr_t gui_label = 0;
    uintptr_t gui_drawtexture = 0;
    uintptr_t gui_set_color = 0;
    uintptr_t gui_get_skin = 0;
    uintptr_t guistyle_set_alignment = 0;
    uintptr_t guistyle_set_fontsize = 0;
    uintptr_t guicontent_temp = 0;
    uintptr_t texture2d_get_whitetexture = 0;

    // --- Физика и Трансформы ---
    uintptr_t transform_set_position = 0;
    uintptr_t transform_inverse_transform_point = 0;
    uintptr_t transform_transform_direction = 0;
    uintptr_t get_transform_up = 0;
    uintptr_t physics_checkcapsule = 0;
    uintptr_t ignore_layer_collision = 0;
    uintptr_t gamephysics_line_of_site = 0;

    // --- Предметы и Оружие ---
    uintptr_t item_heldEntity = 0x98;
    uintptr_t item_info = 0x10;
    uintptr_t itemdefinition_displayName = 0x28;
    uintptr_t item_icon_run_timed_action = 0;
    uintptr_t item_icon_queued_for_looting = 0;
    uintptr_t heldentity_isdeployed = 0;
    uintptr_t buildingblock_upgradetograde = 0;
    uintptr_t buildingblock_canupgradetograde = 0;

    // --- Отдача (Recoil) ---
    uintptr_t recoilproperties_newRecoilOverride = 0x80;
    uintptr_t recoilproperties_recoilYawMin = 0x18;
    uintptr_t recoilproperties_recoilYawMax = 0x1c;
    uintptr_t recoilproperties_recoilPitchMin = 0x20;
    uintptr_t recoilproperties_recoilPitchMax = 0x24;

    // --- Конвары и Атмосфера ---
    uintptr_t admin_convar = 0;
    uintptr_t graphics_convar = 0;
    uintptr_t input_convar = 0;
    uintptr_t set_rain = 0;
    uintptr_t set_atmosphere_rayleigh = 0;
    uintptr_t set_atmosphere_mie = 0;
    uintptr_t set_atmosphere_brightness = 0;
    uintptr_t waterlevel_test = 0;

    // --- Ввод (Input) ---
    uintptr_t input_get_key = 0;
    uintptr_t input_get_key_down = 0;
    uintptr_t input_get_key_up = 0;

    // --- Загрузка ресурсов ---
    uintptr_t LoadAsset_Internal = 0;
    uintptr_t LoadFromFile_Internal = 0;

    // --- Остальное ---
    uintptr_t flashbang_overlay_instance = 0;
    uintptr_t gamemanager_createprefab = 0;
    uintptr_t gamemanager_destroy = 0;
    uintptr_t event_get_current = 0;
    uintptr_t event_get_type = 0;
    uintptr_t cursor_set_lockState = 0;
}
#pragma once
#include <cstdint>

namespace offsets
{
    // Глобальные и системные
    extern uintptr_t MainCamera_RVA;
    extern uintptr_t time_get_time;
    extern uintptr_t time_get_deltaTime;
    extern uintptr_t real_time_since_startup;
    extern uintptr_t get_fixed_time;
    extern uintptr_t get_mousePosition;
    extern uintptr_t screen_get_width;
    extern uintptr_t screen_get_height;

    // Поля игрока и сущностей
    extern uintptr_t movement;
    extern uintptr_t playerInventory;
    extern uintptr_t clActiveItem;
    extern uintptr_t playerModel;
    extern uintptr_t clientTickInterval;
    extern uintptr_t teamID;
    extern uintptr_t _health;
    extern uintptr_t _maxHealth;
    extern uintptr_t lifestate;
    extern uintptr_t mounted;

    // Трансформы и физика
    extern uintptr_t body_rotation;
    extern uintptr_t view_offset;
    extern uintptr_t gravityMultiplier;
    extern uintptr_t transform_set_position;
    extern uintptr_t transform_inverse_transform_point;
    extern uintptr_t transform_transform_direction;
    extern uintptr_t get_transform_up;
    extern uintptr_t physics_checkcapsule;
    extern uintptr_t ignore_layer_collision;
    extern uintptr_t gamephysics_line_of_site;

    // Рендеринг и GUI
    extern uintptr_t get_material;
    extern uintptr_t get_shader;
    extern uintptr_t find;
    extern uintptr_t set_shader;
    extern uintptr_t CreateWithShader;
    extern uintptr_t set_color;
    extern uintptr_t set_pass;
    extern uintptr_t set_float;
    extern uintptr_t set_int;
    extern uintptr_t push_matrix;
    extern uintptr_t pop_matrix;
    extern uintptr_t begin;
    extern uintptr_t vertex;
    extern uintptr_t end;
    extern uintptr_t gui_label;
    extern uintptr_t gui_drawtexture;
    extern uintptr_t gui_set_color;
    extern uintptr_t gui_get_skin;
    extern uintptr_t guistyle_set_alignment;
    extern uintptr_t guistyle_set_fontsize;
    extern uintptr_t guicontent_temp;
    extern uintptr_t texture2d_get_whitetexture;

    // Оружие и предметы
    extern uintptr_t set_aspect;
    extern uintptr_t item_heldEntity;
    extern uintptr_t item_info;
    extern uintptr_t itemdefinition_displayName;
    extern uintptr_t heldentity_isdeployed;
    extern uintptr_t buildingblock_upgradetograde;
    extern uintptr_t buildingblock_canupgradetograde;
    extern uintptr_t item_icon_run_timed_action;
    extern uintptr_t item_icon_queued_for_looting;
    extern uintptr_t recoilproperties_newRecoilOverride;
    extern uintptr_t recoilproperties_recoilYawMin;
    extern uintptr_t recoilproperties_recoilYawMax;
    extern uintptr_t recoilproperties_recoilPitchMin;
    extern uintptr_t recoilproperties_recoilPitchMax;

    // Convars
    extern uintptr_t admin_convar;
    extern uintptr_t graphics_convar;
    extern uintptr_t input_convar;
    extern uintptr_t waterlevel_test;
}
#include "sdk.hpp"
#include "offsets.hpp"
#include "../utilities/returnspoofer.hpp"

c_sdk g_sdk;
c_cheat g_cheat;
c_game g_game;

// --- Исправление WorldToScreen ---
bool c_sdk::world_to_screen(vec3_t world_pos, vec2_t& screen_pos) {
    if (!g_cheat.camera_ptr) return false;

    matrix_4x4 matrix = g_cheat.camera_ptr->get_view_matrix();

    float w = matrix._41 * world_pos.x + matrix._42 * world_pos.y + matrix._43 * world_pos.z + matrix._44;
    if (w < 0.098f) return false;

    float x = matrix._11 * world_pos.x + matrix._12 * world_pos.y + matrix._13 * world_pos.z + matrix._14;
    float y = matrix._21 * world_pos.x + matrix._22 * world_pos.y + matrix._23 * world_pos.z + matrix._24;

    screen_pos.x = (g_cheat.screen_size.x / 2.0f) * (1.0f + x / w);
    screen_pos.y = (g_cheat.screen_size.y / 2.0f) * (1.0f - y / w);

    return true;
}

// --- Исправление ввода ---
bool c_sdk::get_key(uint32_t key) {
    if (!offsets::input_get_key) return false;
    auto fn = reinterpret_cast<bool(*)(uint32_t)>(offsets::input_get_key);
    return spoof_ret(fn, key);
}

bool c_sdk::get_key_down(uint32_t key) {
    if (!offsets::input_get_key_down) return false;
    auto fn = reinterpret_cast<bool(*)(uint32_t)>(offsets::input_get_key_down);
    return spoof_ret(fn, key);
}

// --- Работа с бандлами ---
uintptr_t c_sdk::load_bundle_file(const char* path) {
    if (!offsets::LoadFromFile_Internal) return 0;
    auto fn = reinterpret_cast<uintptr_t(*)(il2mgr::il2cppstring*)>(offsets::LoadFromFile_Internal);
    return spoof_ret(fn, il2mgr::il2cppstring::New(path));
}

uintptr_t c_sdk::load_asset(uintptr_t bundle, const char* name, uintptr_t type) {
    if (!bundle || !offsets::LoadAsset_Internal) return 0;
    auto fn = reinterpret_cast<uintptr_t(*)(uintptr_t, il2mgr::il2cppstring*, uintptr_t)>(offsets::LoadAsset_Internal);
    return spoof_ret(fn, bundle, il2mgr::il2cppstring::New(name), type);
}

// --- Методы c_game ---
void c_game::set_rain(float amount) {
    if (offsets::set_rain) *reinterpret_cast<float*>(offsets::set_rain) = amount;
}

bool c_game::water_level_test(vec3_t pos, bool value1, bool value2, core::base_entity* entity) {
    if (!offsets::waterlevel_test) return false;
    auto fn = reinterpret_cast<bool(*)(vec3_t, bool, bool, core::base_entity*)>(offsets::waterlevel_test);
    return spoof_ret(fn, pos, value1, value2, entity);
}
#pragma once
#include "../includes/includes.hpp"
#include "il2cpp.hpp"
#include "enums.hpp"

namespace core {
    // Предварительные объявления
    class base_player;
    class item;

    class base_entity {
    public:
        vec3_t position; // Убедитесь, что vec3_t определен в includes.hpp
        uintptr_t get_transform();
    };

    class player_model {
    public:
        // Поля для работы с моделями (chams и т.д.)
    };

    class player_input {
    public:
        vec2_t body_angles;
    };

    class player_eyes {
    public:
        vec3_t get_view_offset();
    };

    class item {
    public:
        uintptr_t get_held_entity();
    };

    class base_player : public base_entity {
    public:
        bool is_local_player();
        float health();
        uintptr_t inventory();
        player_model* get_model();
        player_input* get_input();
    };

    struct bounds_t {
        vec3_t center;
        vec3_t extents;
    };
}

class camera {
public:
    void set_aspect_ratio(float value);
    matrix_4x4 get_view_matrix();
};

class c_sdk {
public:
    // Существующие методы
    uintptr_t get_material(uintptr_t renderer);
    uintptr_t find_shader(const char* name);
    void set_color(uintptr_t material, const char* name, color_t color);

    // Новые методы (исправляют ошибки "не является членом")
    bool world_to_screen(vec3_t world_pos, vec2_t& screen_pos);
    bool get_key(uint32_t key);
    bool get_key_down(uint32_t key);
    uintptr_t load_bundle_file(const char* path);
    uintptr_t load_asset(uintptr_t bundle, const char* name, uintptr_t type);

    // Отрисовка
    void begin(int mode);
    void vertex(vec3_t v);
    void end();
};

extern c_sdk g_sdk;

class c_cheat {
public:
    uintptr_t asset_bundle = NULL, font_bundle = NULL, chams_bundle = NULL;
    uintptr_t wireframe_chams_bundle = NULL, circuit_chams_bundle = NULL; // Добавлено

    core::base_player* local = NULL;
    core::player_eyes* local_eyes = NULL;
    camera* camera_ptr = NULL;

    vec3_t cam_pos, local_pos;
    vec2_t screen_size, screen_center;

    uintptr_t white_texture = NULL;
};

extern c_cheat g_cheat;

class c_game {
public:
    bool water_level_test(vec3_t pos, bool value1, bool value2, core::base_entity* entity);
    void set_admin_time(float time);
    void set_rain(float amount);
    void set_mie(float amount);
    void set_rayleigh(float amount);
};

extern c_game g_game;
#pragma once

enum entity_type : int {
	tunnel_dweller = 1,
	scientist,
	player,
};

enum player_flags : uint32_t
{
	is_unused1 = 1,
	is_unused2 = 2,
	is_admin = 4,
	is_receiving_snapshot = 8,
	is_sleeping = 16,
	is_spectating = 32,
	is_wounded = 64,
	is_developer = 128,
	is_connected = 256,
	third_person_view_mode = 1024,
	eyes_view_mode = 2048,
	is_muted_in_chat = 4096,
	is_not_sprinting = 8192,
	is_in_aim = 16384,
	can_display_hash = 32768,
	is_relaxed = 65536,
	is_in_safe_zone = 131072,
	server_fall = 262144,
	is_in_wbench1_area = 1048576,
	is_in_wbench2_area = 2097152,
	is_in_wbench3_area = 4194304,
};

enum model_state_flags : uint32_t {
	in_duck = 1,
	has_jumped = 2,
	on_ground = 4,
	asleep = 8,
	in_sprint = 16,
	on_ladder = 32,
	in_fly = 64,
	in_aim = 128,
	has_pruned = 256,
	is_mounted = 512,
	model_is_relaxed = 1024,
	is_on_phone = 2048,
};

enum weapon_types : int {
	spear_stone = 1602646136,
	spear_wooden = 1540934679
};

enum ammo_types : int {
	shotgun = -1685290200,
	shotgun_slug = -727717969,
	shotgun_fire = -1036635990,
	shotgun_handmade = 588596902,

	rifle_556 = -1211166256,
	rifle_556_hv = 1712070256,
	rifle_556_fire = 605467368,
	rifle_556_explosive = -1321651331,

	pistol = 785728077,
	pistol_hv = -1691396643,
	pistol_fire = 51984655,

	arrow_hv = -1023065463,
	arrow_fire = 14241751,
	arrow_bone = 215754713,
	arrow = 1234735557,

	nailgun_nails = -2097376851
};

enum bone_list : uint32_t
{
	l_hip = 1,
	l_knee,
	l_foot,
	l_toe,
	l_ankle_scale,
	pelvis,
	penis,
	GenitalCensor,
	GenitalCensor_LOD0,
	Inner_LOD0,
	GenitalCensor_LOD1,
	GenitalCensor_LOD2,
	r_hip,
	r_knee,
	r_foot,
	r_toe,
	r_ankle_scale,
	spine1,
	spine1_scale,
	spine2,
	spine3,
	spine4,
	l_clavicle,
	l_upperarm,
	l_forearm,
	l_hand,
	l_index1,
	l_index2,
	l_index3,
	l_little1,
	l_little2,
	l_little3,
	l_middle1,
	l_middle2,
	l_middle3,
	l_prop,
	l_ring1,
	l_ring2,
	l_ring3,
	l_thumb1,
	l_thumb2,
	l_thumb3,
	IKtarget_righthand_min,
	IKtarget_righthand_max,
	l_ulna,
	neck,
	head,
	jaw,
	eyeTranform,
	l_eye,
	l_Eyelid,
	r_eye,
	r_Eyelid,
	r_clavicle,
	r_upperarm,
	r_forearm,
	r_hand,
	r_index1,
	r_index2,
	r_index3,
	r_little1,
	r_little2,
	r_little3,
	r_middle1,
	r_middle2,
	r_middle3,
	r_prop,
	r_ring1,
	r_ring2,
	r_ring3,
	r_thumb1,
	r_thumb2,
	r_thumb3,
	IKtarget_lefthand_min,
	IKtarget_lefthand_max,
	r_ulna,
	l_breast,
	r_breast,
	BoobCensor,
	BreastCensor_LOD0,
	BreastCensor_LOD1,
	BreastCensor_LOD2,
	collision,
	displacement
};

enum class Signal {
	Attack,
	Alt_Attack,
	DryFire,
	Reload,
	Deploy,
	Flinch_Head,
	Flinch_Chest,
	Flinch_Stomach,
	Flinch_RearHead,
	Flinch_RearTorso,
	Throw,
	Relax,
	Gesture,
	PhysImpact,
	Eat,
	Startled
};

enum class key_code
{
	Backspace = 8,
	Delete = 127,
	Tab = 9,
	Clear = 12,
	Return = 13,
	Pause = 19,
	Escape = 27,
	Space = 32,
	Keypad0 = 256,
	Keypad1 = 257,
	Keypad2 = 258,
	Keypad3 = 259,
	Keypad4 = 260,
	Keypad5 = 261,
	Keypad6 = 262,
	Keypad7 = 263,
	Keypad8 = 264,
	Keypad9 = 265,
	KeypadPeriod = 266,
	KeypadDivide = 267,
	KeypadMultiply = 268,
	KeypadMinus = 269,
	KeypadPlus = 270,
	KeypadEnter = 271,
	KeypadEquals = 272,
	UpArrow = 273,
	DownArrow = 274,
	RightArrow = 275,
	LeftArrow = 276,
	Insert = 277,
	Home = 278,
	End = 279,
	PageUp = 280,
	PageDown = 281,
	F1 = 282,
	F2 = 283,
	F3 = 284,
	F4 = 285,
	F5 = 286,
	F6 = 287,
	F7 = 288,
	F8 = 289,
	F9 = 290,
	F10 = 291,
	F11 = 292,
	F12 = 293,
	F13 = 294,
	F14 = 295,
	F15 = 296,
	Alpha0 = 48,
	Alpha1 = 49,
	Alpha2 = 50,
	Alpha3 = 51,
	Alpha4 = 52,
	Alpha5 = 53,
	Alpha6 = 54,
	Alpha7 = 55,
	Alpha8 = 56,
	Alpha9 = 57,
	Exclaim = 33,
	DoubleQuote = 34,
	Hash = 35,
	Dollar = 36,
	Percent = 37,
	Ampersand = 38,
	Quote = 39,
	LeftParen = 40,
	RightParen = 41,
	Asterisk = 42,
	Plus = 43,
	Comma = 44,
	Minus = 45,
	Period = 46,
	Slash = 47,
	Colon = 58,
	Semicolon = 59,
	Less = 60,
	Equals = 61,
	Greater = 62,
	Question = 63,
	At = 64,
	LeftBracket = 91,
	Backslash = 92,
	RightBracket = 93,
	Caret = 94,
	Underscore = 95,
	BackQuote = 96,
	A = 97,
	B = 98,
	C = 99,
	D = 100,
	E = 101,
	F = 102,
	G = 103,
	H = 104,
	I = 105,
	J = 106,
	K = 107,
	L = 108,
	M = 109,
	N = 110,
	O = 111,
	P = 112,
	Q = 113,
	R = 114,
	S = 115,
	T = 116,
	U = 117,
	V = 118,
	W = 119,
	X = 120,
	Y = 121,
	Z = 122,
	LeftCurlyBracket = 123,
	Pipe = 124,
	RightCurlyBracket = 125,
	Tilde = 126,
	Numlock = 300,
	CapsLock = 301,
	ScrollLock = 302,
	RightShift = 303,
	LeftShift = 304,
	RightControl = 305,
	LeftControl = 306,
	RightAlt = 307,
	LeftAlt = 308,
	LeftCommand = 310,
	LeftApple = 310,
	LeftWindows = 311,
	RightCommand = 309,
	RightApple = 309,
	RightWindows = 312,
	AltGr = 313,
	Help = 315,
	Pr = 316,
	SysReq = 317,
	Break = 318,
	Menu = 319,
	Mouse0 = 323,
	Mouse1 = 324,
	Mouse2 = 325,
	Mouse3 = 326,
	Mouse4 = 327,
	Mouse5 = 328,
	Mouse6 = 329
};

enum class QueryTriggerInteraction
{
	// Token: 0x0400005B RID: 91
	UseGlobal,
	// Token: 0x0400005C RID: 92
	Ignore,
	// Token: 0x0400005D RID: 93
	Collide
};

enum class Layers
{
	Terrain = 8388608,
	World = 65536,
	Ragdolls = 512,
	Construction = 2097152,
	ConstructionSocket = 4194304,
	Craters = 1,
	GameTrace = 16384,
	Trigger = 262144,
	VehiclesDetailed = 8192,
	RainFall = 1101070337,
	Deploy = 1235288065,
	DefaultDeployVolumeCheck = 537001984,
	BuildLineOfSightCheck = 2097152,
	ProjectileLineOfSightCheck = 2162688,
	ProjectileLineOfSightCheckTerrain = 10551296,
	MeleeLineOfSightCheck = 2162688,
	EyeLineOfSightCheck = 2162688,
	EntityLineOfSightCheck = 1218519041,
	PlayerBuildings = 18874624,
	PlannerPlacement = 161546496,
	Solid = 1218652417,
	VisCulling = 10551297,
	AltitudeCheck = 1218511105,
	HABGroundEffect = 1218511105,
	AILineOfSight = 1218519297,
	DismountCheck = 1486946561,
	AIPlacement = 278986753,
	WheelRay = 1235321089,
};

enum class server_layers : int
{
	VehiclesSimple = 32768,
	Players = 131072,
	NPCs = 2048,
	Buildings = 2097152,
	Bullet = 1220225809,
	Projectile = 1237003025,
	ProjectileStaticSolid = 1084293393,
	Deployed = 256,
	Stability = 2097408,
	Decay = 2097408,
	PlayerMovement = 429990145,
	PlayerGrounded = 1503731969,
	GroundWatch = 161546240,
	Targets = 133120,
	Bushes = 67108864,
	VehicleCollision = 1235583233,
};

enum class layer : uint32_t {
	Default = 0,
	TransparentFX = 1,
	Ignore_Raycast = 2,
	Reserved1 = 3,
	Water = 4,
	UI = 5,
	Reserved2 = 6,
	Reserved3 = 7,
	Deployed = 8,
	Ragdoll = 9,
	Invisible = 10,
	AI = 11,
	PlayerMovement = 12,
	Vehicle_Detailed = 13,
	Game_Trace = 14,
	Vehicle_World = 15,
	World = 16,
	Player_Server = 17,
	Trigger = 18,
	Player_Model_Rendering = 19,
	Physics_Projectile = 20,
	Construction = 21,
	Construction_Socket = 22,
	Terrain = 23,
	Transparent = 24,
	Clutter = 25,
	Debris = 26,
	Vehicle_Large = 27,
	Prevent_Movement = 28,
	Prevent_Building = 29,
	Tree = 30,
	Unused2 = 31
};

enum class event_type : uint32_t
{
	MouseDown = 0,
	MouseUp = 1,
	MouseMove = 2,
	MouseDrag = 3,
	KeyDown = 4,
	KeyUp = 5,
	ScrollWheel = 6,
	re_paint = 7,
	Layout = 8,
	DragUpdated = 9,
	DragPerform = 10,
	DragExited = 15,
	Ignore = 11,
	Used = 12,
	ValidateCommand = 13,
	ExecuteCommand = 14,
	ContextClick = 16,
	MouseEnterWindow = 20,
	MouseLeaveWindow = 21
};
#pragma once
#include "../includes/hinclude.h"
#include "../features/menu/gui_hook.h"
#include "../hooks/player_related.h"
#include "../hooks/weapon_related.h"

namespace hooks
{
	__forceinline void init( )
	{
		hook_address[ 5 ] = *reinterpret_cast< uintptr_t* >( il2mgr::method( xs( "PerformanceUI" ), xs( "Update" ), 0, xs( "Facepunch" ) ) );

		il2mgr::hook( &perf_ui::performance_ui_update_hook, xs( "PerformanceUI" ), xs( "Update" ), 0, xs( "Facepunch" ) );
		il2mgr::hook( &perf_ui::ongui_hook, xs( "DevControls" ), xs( "OnGUI" ), 0, xs( "" ) );

		hook_address[ 0 ] = il2mgr::hook_virt( xs( "BaseMelee" ), xs( "ProcessAttack" ), &basemelee::process_attack_hook, 1 );
		hook_address[ 1 ] = il2mgr::hook_virt( xs( "BasePlayer" ), xs( "ClientInput" ), &baseplayer::client_input_hook, 1 );
		hook_address[ 2 ] = il2mgr::hook_virt( xs( "BasePlayer" ), xs( "VisUpdateUsingCulling" ), &baseplayer::fix_culling_hook, 2 );
		hook_address[ 3 ] = il2mgr::hook_virt( xs( "BasePlayer" ), xs( "OnAttacked" ), &baseplayer::on_attacked_hook, 1 );
		hook_address[ 4 ] = il2mgr::hook_virt( xs( "ItemIcon" ), xs( "TryToMove" ), &item_icon::try_to_move_hook, 0 );

		if (hook_address[4])
			printf("ayeee\n");#pragma once
#include "../../vector/vector2.hpp"
#include "../../vector/vector3.hpp"
#include "../../vector/color.hpp"
#include "../../vector/vector4.hpp"
#include <string>

enum font_flags_t : int {
	none = 0,
	dropshadow,
	outline
};

enum begin_mode : int {
	lines = 1,
	line_strip,
	triangles = 4,
	triangle_strip,
	quads = 7
};

class c_renderer {
public:
	void get_draw_shader( );

	void set_up_draw_shader( );

	void begin_gl_draw( begin_mode mode );

	void draw_circle( vec2_t pos, float radius, color_t color );

	void gl_triangle( vec2_t pos, vec2_t pos1, vec2_t pos2, color_t col );

	void draw_line( vec2_t start, vec2_t end, color_t color );

	void draw_filled_rect( vec2_t position, vec2_t size, color_t color );
	void draw_filled_rect( vec4_t position, color_t color );
	void draw_filled_rect( float x, float y, float width, float height, color_t color );

	void get_n_white_texture( );

	void ddraw_line( vec3_t start, vec3_t end, color_t color, float duration = 7.0f, bool distanceFade = true, bool ztest = true );
	void ddraw_sphere( vec3_t start, vec3_t end, color_t color, float duration = 7.0f, bool distanceFade = true );
	void ddraw_arrow( vec3_t start, vec3_t end, float size, color_t color, float duration = 2.f );
	void ddraw_text( const char* text, vec3_t pos, color_t color, float duration = 0.5f );

	void horizontal_line( vec2_t pos, float size, color_t clr );
	void vertical_line( vec2_t pos, float size, color_t clr );

	void outline_box( vec2_t position, vec2_t size, color_t color, float girth = 1.f );

	void line( vec2_t point1, vec2_t point2, color_t color );
	void label( vec4_t position, std::string text, color_t color, bool centered = false, 
		int font_size = 12 );

	void draw_text( vec4_t position, std::string text, color_t color, bool centered = false, 
		int font_size = 12, font_flags_t flags = none, color_t outline_color = color_t( 0, 0, 0, 175 ) );

	void ddraw_get( );
};

extern c_renderer g_render;
#include "../../includes/hinclude.h"
#include "../offsets.hpp"

// create global definition of render class.
c_renderer g_render;

static uintptr_t draw_shader = NULL;
static bool has_drew_once = true;

void c_renderer::get_draw_shader( ) {
	draw_shader = il2mgr::methods::object_new( il2mgr::init_class( xs( "Material" ), xs( "UnityEngine" ) ) );
}

void c_renderer::set_up_draw_shader( ) {
	if( !draw_shader )
		return get_draw_shader( );

	static uintptr_t shader = g_sdk.find( "Hidden/Internal-Colored" );
	if( !shader
		|| !has_drew_once )
		return;

	g_sdk.create_shader( draw_shader, shader );
	g_sdk.set_material_int( draw_shader, "_SrcBlend", 5 );
	g_sdk.set_material_int( draw_shader, "_DstBlend", 10 );
	g_sdk.set_material_int( draw_shader, "_Cull", 0 );
	g_sdk.set_material_int( draw_shader, "_ZWrite", 0 );
	g_sdk.dont_destroy_on_load( draw_shader );
	has_drew_once = false;
}

void c_renderer::begin_gl_draw( begin_mode mode ) {
	if( !draw_shader )
		return get_draw_shader( );

	g_sdk.push_matrix( );
	g_sdk.set_pass( draw_shader, 0 );
	g_sdk.begin( mode );
}

void c_renderer::draw_circle( vec2_t pos, float radius, color_t color ) {
	if( !draw_shader )
		return get_draw_shader( );

	begin_gl_draw( begin_mode::line_strip );
	g_sdk.set_gl_color( color );
	for( float num = 0.f; num < PIX2 * 2.f; num += 0.05f ) {
		g_sdk.vertex( vec3_t( cos( num ) * radius + pos.x, sin( num ) * radius + pos.y, 0 ) );
		g_sdk.vertex( vec3_t( cos( num + 0.05f ) * radius + pos.x, sin( num + 0.05f ) * radius + pos.y, 0 ) );
	}
	g_sdk.end( );
	g_sdk.pop_matrix( );
}

void c_renderer::gl_triangle( vec2_t pos, vec2_t pos1, vec2_t pos2, color_t col )
{
	if( !draw_shader )
		return get_draw_shader( );

	begin_gl_draw( begin_mode::triangles );
	g_sdk.set_gl_color( col );
	g_sdk.vertex( vec3_t( pos.x, pos.y, 0 ) );
	g_sdk.vertex( vec3_t( pos1.x, pos1.y, 0 ) );
	g_sdk.vertex( vec3_t( pos2.x, pos2.y, 0 ) );

	g_sdk.end( );
	g_sdk.pop_matrix( );
}

void c_renderer::draw_line( vec2_t start, vec2_t end, color_t color ) {
	if( !draw_shader )
		return get_draw_shader( );

	begin_gl_draw( begin_mode::lines );
	g_sdk.set_gl_color( color );
	g_sdk.vertex( vec3_t( start.x, start.y, 0 ) );
	g_sdk.vertex( vec3_t( end.x, end.y, 0 ) );

	g_sdk.end( );
	g_sdk.pop_matrix( );
}

void c_renderer::get_n_white_texture( ) {
	g_cheat.white_texture = g_sdk.get_white_texture( );
}

void c_renderer::horizontal_line( vec2_t pos, float size, color_t clr )
{
	if( !g_cheat.white_texture )
		return get_n_white_texture( );

	g_sdk.set_draw_color( clr );

	g_sdk.draw_texture( vec4_t( pos.x, pos.y, size, 1 ), g_cheat.white_texture );
}

void c_renderer::vertical_line( vec2_t pos, float size, color_t clr )
{
	if( !g_cheat.white_texture )
		return get_n_white_texture( );

	g_sdk.set_draw_color( clr );

	g_sdk.draw_texture( vec4_t( pos.x, pos.y, 1, size ), g_cheat.white_texture );
}

void c_renderer::outline_box( vec2_t position, vec2_t size, color_t color, float girth )
{
	if( !g_cheat.white_texture )
		return get_n_white_texture( );

	g_sdk.set_draw_color( color );

	g_sdk.draw_texture( vec4_t( position.x, position.y, girth, size.y ), g_cheat.white_texture );
	g_sdk.draw_texture( vec4_t( position.x + size.x, position.y, girth, size.y + 1 ), g_cheat.white_texture );
	g_sdk.draw_texture( vec4_t( position.x, position.y, size.x, girth ), g_cheat.white_texture );
	g_sdk.draw_texture( vec4_t( position.x, position.y + size.y, size.x, girth ), g_cheat.white_texture );
}

void c_renderer::draw_filled_rect( vec2_t position, vec2_t size, color_t color )
{
	if( !g_cheat.white_texture )
		return get_n_white_texture( );

	g_sdk.set_draw_color( color );
	g_sdk.draw_texture( vec4_t( position.x, position.y, size.x, size.y ), g_cheat.white_texture );
}

void c_renderer::draw_filled_rect( float x, float y, float width, float height, color_t color )
{
	if( !g_cheat.white_texture )
		return get_n_white_texture( );

	g_sdk.set_draw_color( color );
	g_sdk.draw_texture( vec4_t( x, y, width, height ), g_cheat.white_texture );
}

void c_renderer::draw_filled_rect( vec4_t position, color_t color )
{
	if( !g_cheat.white_texture )
		return get_n_white_texture( );

	g_sdk.set_draw_color( color );
	g_sdk.draw_texture( position, g_cheat.white_texture );
}

void c_renderer::line( vec2_t point1, vec2_t point2, color_t color )
{
	if( !g_cheat.white_texture )
		return get_n_white_texture( );

	g_sdk.set_draw_color( color );
	if( ( point1.x - point2.x ) < 1.f )
		g_sdk.draw_texture( vec4_t( point1.x, point1.y, point1.x - point2.x, 1.f ), g_cheat.white_texture );
	else
		g_sdk.draw_texture( vec4_t( point1.x, point1.y, 1.f, point1.y - point2.y ), g_cheat.white_texture );
}

void c_renderer::label( vec4_t position, std::string text, color_t color, bool centered, int font_size )
{
	if( !g_cheat.draw_label )
		return;

	g_sdk.set_draw_font_size( g_cheat.draw_label, font_size );

	g_sdk.set_draw_alignment( g_cheat.draw_label, centered ? 0x4 : 0x0 );

	//if( centered )
	//	position.x -= .5 * ( text.length( ) * font_size );

	uintptr_t method = offsets::gui_label;
	if( !method )
		return;

	uintptr_t method_ptr = *reinterpret_cast< uintptr_t* >( method );
	if( !method_ptr )
		return;

	auto label = reinterpret_cast< void( * )( vec4_t, il2mgr::il2cppstring*, uintptr_t ) >( method_ptr );

	auto contents = il2mgr::il2cppstring::New( text.c_str( ) );

	g_sdk.set_draw_color( color );
	spoof_ret( label, position, contents, g_cheat.draw_label );
}

void c_renderer::draw_text( vec4_t position, std::string text, color_t color, bool centered, int font_size, font_flags_t flags, color_t outline_color ) {
	// measure.
	outline_color.a *= color.a;

	if( flags & outline ) {
		label( vec4_t( position.x, position.y - 1, position.z, position.w ), text, outline_color, centered, font_size ); //up
		label( vec4_t( position.x, position.y + 1, position.z, position.w ), text, outline_color, centered, font_size ); //down
		label( vec4_t( position.x + 1, position.y, position.z, position.w ), text, outline_color, centered, font_size ); //right
		label( vec4_t( position.x - 1, position.y, position.z, position.w ), text, outline_color, centered, font_size ); //left
		label( vec4_t( position.x + 1, position.y + 1, position.z, position.w ), text, outline_color, centered, font_size ); //down-right
		label( vec4_t( position.x - 1, position.y + 1, position.z, position.w ), text, outline_color, centered, font_size ); //down-left
		label( vec4_t( position.x + 1, position.y - 1, position.z, position.w ), text, outline_color, centered, font_size ); //up-right
		label( vec4_t( position.x - 1, position.y - 1, position.z, position.w ), text, outline_color, centered, font_size ); //up-left
	}
	if( flags & dropshadow ) {
		label( vec4_t( position.x + 1, position.y + 1, position.z, position.w ), text, outline_color, centered, font_size );
	}

	label( position, text, color, centered, font_size );
}

void c_renderer::ddraw_line( vec3_t start, vec3_t end, color_t color, float duration, bool distanceFade, bool ztest )
{
	uintptr_t method = offsets::ddraw_line;
	if( !method )
		return;

	uintptr_t method_ptr = *reinterpret_cast< uintptr_t* >( method );
	if( !method_ptr )
		return;

	auto line = reinterpret_cast< void( * )( vec3_t, vec3_t, color_t, float, bool, bool ) >( method_ptr );
	spoof_ret( line, start, end, color, duration, distanceFade, ztest );
}

void c_renderer::ddraw_sphere( vec3_t start, vec3_t end, color_t color, float duration, bool distanceFade )
{
	uintptr_t method = offsets::ddraw_sphere;
	if( !method )
		return;

	uintptr_t method_ptr = *reinterpret_cast< uintptr_t* >( method );
	if( !method_ptr )
		return;

	auto sphere = reinterpret_cast< void( * )( vec3_t, vec3_t, color_t, float, bool ) >( method_ptr );
	spoof_ret( sphere, start, end, color, duration, distanceFade );
}

void c_renderer::ddraw_arrow( vec3_t start, vec3_t end, float size, color_t color, float duration )
{
	uintptr_t method = offsets::ddraw_arrow;
	if( !method )
		return;

	uintptr_t method_ptr = *reinterpret_cast< uintptr_t* >( method );
	if( !method_ptr )
		return;

	auto arrow = reinterpret_cast< void( * )( vec3_t, vec3_t, float, color_t, float ) >( method_ptr );
	spoof_ret( arrow, start, end, size, color, duration );
}

void c_renderer::ddraw_text( const char* text, vec3_t pos, color_t color, float duration )
{
	uintptr_t method = offsets::ddraw_text;
	if( !method )
		return;

	uintptr_t method_ptr = *reinterpret_cast< uintptr_t* >( method );
	if( !method_ptr )
		return;

	auto drawtext = reinterpret_cast< void( * )( il2mgr::il2cppstring*, vec3_t, color_t, float ) >( method_ptr );
	spoof_ret( drawtext, il2mgr::il2cppstring::New( text ), pos, color, duration );
}

void c_renderer::ddraw_get( )
{
	uintptr_t method = offsets::ddraw_get;
	if( !method )
		return;

	uintptr_t method_ptr = *reinterpret_cast< uintptr_t* >( method );
	if( !method_ptr )
		return;
#pragma once
#include "../includes/hinclude.h"
#include "../features/options.h"

namespace basemelee
{
	inline void process_attack_hook( core::item* base_item, core::hit_test* hittest )
	{
		auto orig_basemelee_process_attack = reinterpret_cast< void( * )( core::item*, core::hit_test* ) >( hook_address[ 0 ] );
		core::base_player* local = g_cheat.local;

		if( !local )
			return spoof_ret( orig_basemelee_process_attack, base_item, hittest );

		if( !options::aimbot::exploits::misc::always_hit_weak_spot )
			return spoof_ret( orig_basemelee_process_attack, base_item, hittest );

		core::base_entity* hit_entity = hittest->get_hit_entity( );
		if( !hit_entity )
			return spoof_ret( orig_basemelee_process_attack, base_item, hittest );

		core::transform* hit_entity_transform = hit_entity->get_transform( );
		if( !hit_entity_transform )
			return spoof_ret( orig_basemelee_process_attack, base_item, hittest );

		std::string hit_entity_class = hit_entity->get_class_name( );

		float max_dist = options::aimbot::exploits::combat::extended_melee ? options::aimbot::exploits::combat::attack_radius : 2;

		if( hit_entity_class == xs( "OreResourceEntity" ) )
		{
			core::base_entity* closest_object = g_esp.get_closest_object_of_class( xs( "OreHotSpot" ), max_dist );
			if( !closest_object )
				return spoof_ret( orig_basemelee_process_attack, base_item, hittest );

			core::transform* hot_spot_transform = closest_object->get_transform( );
			if( !hot_spot_transform )
				return spoof_ret( orig_basemelee_process_attack, base_item, hittest );

			hittest->set_hit_entity( hit_entity );
			hittest->set_hit_transform( hot_spot_transform );
			vec3_t hotspot_position = hot_spot_transform->get_position( );
			vec3_t inverse_point = hot_spot_transform->inverse_tranform_point( hotspot_position );
			hittest->set_hit_hitpoint( inverse_point );
		}
		else if( hit_entity_class == xs( "TreeEntity" ) )
		{
			vec3_t tree_pos = hit_entity_transform->get_position( );
			vec3_t inverse_point = hit_entity_transform->inverse_tranform_point( tree_pos + vec3_t( 0.f, 1.f, 0.f ) );
			float dist = g_cheat.local->get_closest_point( tree_pos ).distance( tree_pos );
			core::base_entity* closest_object = g_esp.get_closest_object_of_class( xs( "TreeMarker" ), max_dist );

			if( !closest_object )
			{
				hittest->set_hit_distance( dist );
				hittest->set_hit_hitpoint( inverse_point );
				return spoof_ret( orig_basemelee_process_attack, base_item, hittest );
			}
			else
			{
				core::transform* transform = closest_object->get_transform( );
				if( !transform )
					return spoof_ret( orig_basemelee_process_attack, base_item, hittest );

				vec3_t pos3 = transform->get_position( );
				vec3_t pos3_inverse_point = hit_entity_transform->inverse_tranform_point( pos3 );
				hittest->set_hit_distance( dist );
				hittest->set_hit_hitpoint( pos3_inverse_point );
				hit_entity->set_hit_direction( vec3_t( tree_pos.x, 0, tree_pos.z ) - vec3_t( pos3.x, 0, pos3.z ) );
				return spoof_ret( orig_basemelee_process_attack, base_item, hittest );
			}
		}

		return spoof_ret( orig_basemelee_process_attack, base_item, hittest );
	}
}
#pragma once

#include "../includes/hinclude.h"
#include "../features/aimbot/aimbot.h"
#include "../features/visuals/esp.h"
#include "../features/options.h"

void handle_exploits( core::base_player* local_player, core::item* held_item )
{
	if( options::aimbot::exploits::time::fast_switch )
	{
		held_item->set_deploy_delay( 0.f );
	}

	if( held_item->is_melee( ) )
	{
		if( options::aimbot::exploits::movement::disable_slow_down_melee )
		{
			held_item->set_block_sprint( false );
		}
		if( options::aimbot::exploits::combat::extended_melee )
		{
			held_item->set_attack_max_distance( options::aimbot::exploits::combat::attack_radius );
		}
	}
	else if( held_item->is_gun( ) ) {
		if( options::aimbot::exploits::combat::big_bullets )
		{
			held_item->set_bullet_thickness( options::aimbot::exploits::combat::bullet_size / 100.f );
		}
		if( options::aimbot::exploits::combat::aim_bolt_cycle )
		{
			held_item->set_aiming_while_cycling( false );
		}
		if( options::aimbot::exploits::time::fast_bow )
		{
			held_item->set_attack_ready( true );
			held_item->set_was_aiming( true );
		}
		if( options::aimbot::exploits::combat::modify_eoka_chance ) {
			float eoka_chance = options::aimbot::exploits::combat::eoka_chance / 100.f;

			held_item->set_always_eoka( eoka_chance );

			if( eoka_chance > 0.9f
				&& g_sdk.get_key( key_code::Mouse0 ) )
				held_item->set_did_spark_this_frame( true );
		}
		if( options::aimbot::exploits::time::rapid_fire )
		{
			held_item->set_repeat_delay( options::aimbot::exploits::time::rapid_fire_speed / 100.f );
		}

		if( options::aimbot::exploits::time::instant_charge_compound )
		{
			held_item->set_current_hold_progress( 1.5f );
			held_item->set_string_bonus_damage( 1000.f );
			held_item->set_movement_penalty_ramp_up_time( 1000.f );
		}

		if( options::aimbot::exploits::misc::fake_fire
			&& ( g_sdk.get_key( options::aimbot::exploits::misc::fake_fire_key ) || options::aimbot::exploits::misc::fake_fire_on ) )
		{
			static float last_shoot = 0.f;
			float delay = options::aimbot::exploits::misc::delay_fake_fire / 100.f;

			if( ( last_shoot - local_player->lastSentTickTime( ) ) > delay ) {
				held_item->send_broadcast_projectile( Signal::Attack, xs( "" ) );
				last_shoot = local_player->lastSentTickTime( );
			}
		}

		static bool just_shot{ }, did_reload{ };
		float time_since_last_shot = 0.0f, fixed_time_last_shot = 0.0f;

		if( options::aimbot::auto_reload )
		{
			if( !did_reload )
				time_since_last_shot = ( g_sdk.get_fixedTime( ) - fixed_time_last_shot );

			if( !just_shot 
				&& ( time_since_last_shot > 0.2f ) )
			{
				held_item->server_rpc( xs( "StartReload" ) );
				held_item->send_signal_broadcast( Signal::Reload );
				just_shot = true;
			}
			if( time_since_last_shot >
				( held_item->get_reload_time( ) - ( held_item->get_reload_time( ) / 10.f ) )
				&& !did_reload )
			{
				held_item->server_rpc( xs( "Reload" ) );
				did_reload = true;
				time_since_last_shot = 0;
			}

			fixed_time_last_shot = g_sdk.get_fixedTime( );
		}

		if( options::aimbot::exploits::combat::burst_weapons ) {
			held_item->set_is_burst( true );
		}
		if( options::aimbot::exploits::combat::automatic_weapons ) {
			held_item->set_is_automatic( true );
		}
		else if( options::aimbot::exploits::combat::semi_automatic_weapons ) {
			held_item->set_is_automatic( false );
		}

		float to_reduce = options::aimbot::exploits::combat::reduce_recoil / 100.f;

		held_item->set_recoil_min_max( options::aimbot::exploits::combat::no_recoil ?
			to_reduce : 1.f );

		if( options::aimbot::exploits::combat::no_sway )
		{
			held_item->set_aim_sway( 0.f );
			held_item->set_aim_sway_speed( 0.f );
		}
		if( options::aimbot::exploits::combat::no_spread )
		{
			float spread = options::aimbot::exploits::combat::reduce_spread / 100.f;

			//std::cout << "1:" << held_item->get_aim_cone( )  << std::endl;
			//std::cout << "2:" << held_item->get_aim_cone_penalty_per_shot( )  << std::endl;
			//std::cout << "3:" << held_item->get_aim_cone_penalty( )  << std::endl;
			//std::cout << "4:" << held_item->get_hip_aim_cone( )  << std::endl;
			//std::cout << "5:" << held_item->get_stance_penalty( )  << std::endl;
			//std::cout << "6:" << held_item->get_aim_cone_penalty_max( )  << std::endl;
			//std::cout << "7:" << held_item->get_aim_penalty_recover_time( )  << std::endl;
			//std::cout << "8:" << held_item->get_aim_penalty_recover_delay( )  << std::endl;
			//std::cout << "9:" << held_item->get_aim_sight_aim_cone_scale( )  << std::endl;
			//std::cout << "10:" << held_item->get_aim_sight_aim_cone_offset( )  << std::endl;
			//std::cout << "11:" << held_item->get_hip_aim_cone_scale( )  << std::endl;
			//std::cout << "12:" << held_item->get_hip_aim_cone_offset( )  << std::endl;

			held_item->set_aim_cone( spread );
			held_item->set_aim_cone_penalty_per_shot( spread );
			held_item->set_aim_cone_penalty( spread );
			held_item->set_hip_aim_cone( spread );
			held_item->set_stance_penalty( spread );
			held_item->set_aim_cone_penalty_max( spread );
			held_item->set_aim_penalty_recover_time( spread );
			held_item->set_aim_penalty_recover_delay( spread );
			held_item->set_aim_sight_aim_cone_scale( spread );
			held_item->set_aim_sight_aim_cone_offset( spread );
			held_item->set_hip_aim_cone_scale( spread );
			held_item->set_hip_aim_cone_offset( spread );
		}
		if( options::aimbot::exploits::combat::quick_bullets )
		{
			float speed = ( options::aimbot::exploits::combat::bullet_speed / 100.f );

			held_item->set_projectile_velocity_scale( speed );
		}
		if( options::aimbot::exploits::combat::spoof_hit_distance )
		{
			float distance = options::aimbot::exploits::combat::bullet_distance;

			held_item->set_projectile_distance_scale( distance );
		}
	}
}

void handle_rpc_exploits( core::base_player* local_player, core::item* held_item ) {
	core::base_player* best_target = g_aimbot.target;
	float distance = FLT_MAX;
	static float last_syringe = 0.f;

	if( !last_syringe )
		last_syringe = local_player->lastSentTickTime( );

	if( best_target ) {
		core::player_model* model = best_target->get_model( );
		if( !model )
			return;

		distance = g_cheat.local_pos.distance( model->get_position( ) );

		if( options::aimbot::exploits::time::instant_revive
			|| options::aimbot::exploits::misc::keep_wounded_alive )
		{
			if( best_target->is_knocked( ) ) {
				if( distance < 10.0f )
				{
					if( ( g_sdk.get_key( options::aimbot::exploits::time::revive_key ) || options::aimbot::exploits::time::always_revive_target )
						&& options::aimbot::exploits::time::instant_revive ) {
						best_target->server_rpc( xs( "RPC_Assist" ) );
					}
					if( options::aimbot::exploits::misc::keep_wounded_alive )
					{
						best_target->server_rpc( xs( "RPC_KeepAlive" ) );
					}
				}
			}
		}
	}

	if( held_item->is_heal( ) ) {
		if( options::aimbot::exploits::time::fast_heal )
		{
			if( ( local_player->lastSentTickTime( ) - last_syringe ) > 0.7f ) {
				if( distance < 5.f )
					held_item->server_rpc( xs( "UseOther" ) );
				else
					held_item->server_rpc( xs( "UseSelf" ) );
				last_syringe = local_player->lastSentTickTime( );
			}
		}
	}
}

namespace baseplayer
{
	inline void client_input_hook( core::base_player* player, core::input_state* state )
	{
		auto orig_baseplayer_client_input = reinterpret_cast< void( * )( core::base_player*, core::input_state* ) >( hook_address[ 1 ] );

		while( !g_cheat.camera_ptr )
			get_main_camera( );

		// reset this incase.
		if( ( g_sdk.get_key( key_code::End )
			|| !options::friend_system )
			&& !g_esp.m_friends.empty( ) )
			g_esp.m_friends.clear( );

		g_cheat.cam_pos = g_sdk.get_camera_pos( );

		g_render.ddraw_get( );

		core::base_player* local_player = g_cheat.local;
		if( local_player
			&& !local_player->get_life_state( ) ) {
			float desync_time = ( g_sdk.realtimeSinceStartup( ) - local_player->lastSentTickTime( ) ) - 0.03125 * 3;

			g_esp.maximum_eye_height = ( 0.1f + ( ( desync_time + 2.f / 60.f + 0.125f ) * 1.5f ) * local_player->get_max_speed( ) ) - 0.05f;

			core::item* item = local_player->get_held_item( );
			
			core::model_state* model_state = local_player->get_modelstate( );
			
			core::player_walk_movement* movement = local_player->get_movement( );
			core::player_input* input = local_player->get_input( );
			core::player_eyes* eyes = local_player->get_eyes( );
			if( eyes )
				g_cheat.local_eyes = eyes;

			if( eyes
				&& model_state
				&& movement ) {
				if( movement->flying( )
					|| !g_esp.not_in_fly_action )
					model_state->add_flag( model_state_flags::in_sprint );

				if( options::visuals::world::night_stars )
					model_state->add_flag( model_state_flags::asleep );

				model_state->remove_flag( model_state_flags::in_fly );

				static float x_value{ }, y_value{ }, w_value{ };

				float fake_lag = options::aimbot::exploits::time::fake_lag_amount;

				bool has_fake_lag = options::aimbot::exploits::time::fake_lag 
					&& ( g_sdk.get_key( options::aimbot::exploits::time::fake_lag_key ) || options::aimbot::exploits::time::fake_lag_on );

				if( has_fake_lag )
					local_player->set_clientTickInterval( fake_lag );
				else
					local_player->set_clientTickInterval( 0.05f );

				if( options::aimbot::exploits::combat::modify_can_attack )
				{
					model_state->add_flag( model_state_flags::on_ground );
					movement->set_is_grounded( 1.f );
				}

				if( options::aimbot::exploits::movement::climb_assist ) {
					movement->set_ground_angle_new( 0.f );
				}

				if( g_esp.not_in_fly_action ) {
					if( options::aimbot::exploits::misc::suicide
						&& g_sdk.get_key( options::aimbot::exploits::misc::suicide_key ) ) {
						movement->set_was_falling( true );
						movement->set_previous_velocity( vec3_t( 0, -1000, 0 ) );
						movement->set_ground_time( 0.f );
					}
					else {
						if( options::aimbot::exploits::misc::disable_land_damage )
						{
							movement->set_was_falling( true );
							movement->set_previous_velocity( vec3_t( ) );
						}
					}

					auto next_ground_time = movement->get_ground_time( ) + 0.5f;

					if( options::aimbot::exploits::movement::infinite_jump )
					{
						movement->set_jump_time( 0.f );
						movement->set_ground_time( next_ground_time );
						movement->set_land_time( 0.f );
					}
					movement->set_gravity_multiplier( options::aimbot::exploits::movement::high_jump ? options::aimbot::exploits::movement::jump_height / 100.f : 2.35f );
				}

				static bool has_debug_camera = false;

				if( options::aimbot::exploits::misc::debug_camera ) {
					static int delay = 0;

					if( g_sdk.get_key( options::aimbot::exploits::misc::debug_camera_key )
						&& --delay < 25 ) {
						has_debug_camera = !has_debug_camera;
						delay = 25;
					}

					static vec4_t rotation_before_debug = vec4_t( );
					static vec2_t view_before_debug = vec2_t( );

					if( has_debug_camera ) {
						bool has_pressed_left = g_sdk.get_key( key_code::A );

						bool has_pressed_right = g_sdk.get_key( key_code::D );

						bool has_pressed_down = g_sdk.get_key( key_code::S );

						bool has_pressed_up = g_sdk.get_key( key_code::W );

						bool has_pressed_shift = g_sdk.get_key( key_code::LeftShift );

						bool has_pressed_space = g_sdk.get_key( key_code::Space );

						//bool has_pressed_h = g_sdk.get_key( key_code::H );

						//bool has_pressed_k = g_sdk.get_key( key_code::K );

						if( has_pressed_left )
							x_value -= 0.25f;
						else if( has_pressed_right )
							x_value += 0.25f;

						if( has_pressed_down )
							w_value -= 0.25f;
						else if( has_pressed_up )
							w_value += 0.25f;

						if( has_pressed_shift )
							y_value -= 0.25f;
						else if( has_pressed_space )
							y_value += 0.25f;

						if( !rotation_before_debug.is_zero( ) )
							eyes->set_body_rotation( rotation_before_debug );

						if( input ) {
							if( !view_before_debug.is_zero( ) )
								input->set_view_angles( view_before_debug );
						}

						if( movement ) {
							movement->set_ground_time( 1.f );
							movement->set_jump_time( 0.f );
							movement->set_land_time( 0.f );
							movement->set_targetmovement( vec3_t( ) );
						}

						eyes->set_view_offset( vec3_t( x_value, y_value, w_value ) );
					}
					else {
						rotation_before_debug = eyes->get_body_rotation( );
						if( input )
							view_before_debug = input->get_view_angles( );

						x_value = w_value = y_value = 0; 
					}
				}
				else
					has_debug_camera = false;

				if( !has_debug_camera ) {
					bool has_up_view_offset = options::aimbot::exploits::misc::long_neck
						&& g_sdk.get_key( options::aimbot::exploits::misc::view_height );

					bool has_right_view_offset = options::aimbot::exploits::misc::long_neck_right
						&& g_sdk.get_key( options::aimbot::exploits::misc::view_right );

					bool has_left_view_offset = options::aimbot::exploits::misc::long_neck_left
						&& g_sdk.get_key( options::aimbot::exploits::misc::view_left );

					float height_view_offset = ( options::aimbot::exploits::misc::long_neck_height );
					if( options::aimbot::exploits::misc::use_max_view )
						height_view_offset = g_esp.maximum_eye_height;

					float left_view_offset = ( options::aimbot::exploits::misc::long_neck_left_amount );

					float right_view_offset = ( options::aimbot::exploits::misc::long_neck_right_amount );

					if( has_up_view_offset	
						&& ( has_left_view_offset || has_right_view_offset ) )
					{
						// we need this so shots are registered.
						local_player->set_clientTickInterval( fake_lag < 1.f ? 1.f : fake_lag );

						eyes->set_view_offset( vec3_t( has_left_view_offset ? -left_view_offset : right_view_offset, height_view_offset, 0 ) );
					}
					else if( has_up_view_offset )
					{
						if( options::aimbot::exploits::misc::use_max_view )
							local_player->set_clientTickInterval( 1.f );
						else {
							if( height_view_offset >= 0.4f )
								local_player->set_clientTickInterval( fake_lag * ( height_view_offset - 0.5f ) );
						}

						eyes->set_view_offset( vec3_t( 0, height_view_offset, 0 ) );
					}
					else if( has_right_view_offset )
					{
						if( right_view_offset >= 0.4f )
							local_player->set_clientTickInterval( fake_lag * ( right_view_offset - 0.5f ) );

						eyes->set_view_offset( vec3_t( right_view_offset, 0, 0 ) );
					}
					else if( has_left_view_offset )
					{
						if( left_view_offset >= 0.4f )
							local_player->set_clientTickInterval( fake_lag * ( left_view_offset - 0.5f ) );

						eyes->set_view_offset( vec3_t( -left_view_offset, 0, 0 ) );
					}
					else {
						if( !has_fake_lag )
							local_player->set_clientTickInterval( 0.05f );
					}
				}
			}

			if( item )
			{
				g_esp.melee_max_dist = item->get_attack_max_distance( ) + 2.f;

				if( options::aimbot::kill_aura ) {
					vec3_t pos = reinterpret_cast< core::base_player* >( g_aimbot.target )->get_bone_position( head );

					if( pos.distance( g_cheat.local_pos ) < g_esp.melee_max_dist )
						g_esp.do_melee_attack( pos, g_aimbot.target, true );
				}

				if( options::aimbot::exploits::misc::auto_farm_ores ) {
					if( options::aimbot::exploits::misc::auto_farm_only_hotspot ) {
						core::base_entity* hotspot = g_esp.get_closest_object_of_class( xs( "OreHotSpot" ), g_esp.melee_max_dist );
						if( hotspot ) {
							core::transform* transform = hotspot->get_transform( );
							if( transform ) {
								vec3_t pos = transform->get_position( );

								g_esp.do_melee_attack( pos, hotspot, false );
							}
						}
					}
					else {
						core::base_entity* ore = g_esp.get_closest_object_of_class( xs( "OreResourceEntity" ), g_esp.melee_max_dist );
						if( ore ) {
							core::transform* transform = ore->get_transform( );
							if( transform ) {
								vec3_t pos = transform->get_position( );

								// increase the height a bit.
								pos.y += 0.25f;

								g_esp.do_melee_attack( pos, ore, false );
							}
						}
					}
				}

				if( eyes ) {
					vec3_t eye_pos = eyes->get_position( );
					if( options::aimbot::exploits::misc::auto_farm_trees ) {
						if( options::aimbot::exploits::misc::auto_farm_only_hotspot ) {
							core::base_entity* marker = g_esp.get_closest_object_of_class( xs( "TreeMarker" ), g_esp.melee_max_dist );
							if( marker ) {
								core::transform* transform = marker->get_transform( );
								if( transform ) {
									vec3_t pos = transform->get_position( );
									pos.y = eye_pos.y;

									g_esp.do_melee_attack( pos, marker, false );
								}
							}
						}
						else {
							core::base_entity* tree = g_esp.get_closest_object_of_class( xs( "TreeEntity" ), g_esp.melee_max_dist );
							if( tree ) {
								core::transform* transform = tree->get_transform( );
								if( transform ) {
									vec3_t pos = transform->get_position( );
									pos.y = eye_pos.y;

									g_esp.do_melee_attack( pos, tree, false );
								}
							}
						}
					}
				}

				core::base_view_model* view = core::base_view_model::get_view( );
				if( view ) {
					core::viewmodel_bob* bob = view->get_bob( );

					core::viewmodel_lower* lower = view->get_lower( );

					if( bob
						&& options::aimbot::exploits::misc::no_viewmodel_bob ) {
						bob->set_bob_amount_run( 0.f );
						bob->set_bob_amount_walk( 0.f );
						bob->set_bob_speed_run( 0.f );
						bob->set_bob_speed_walk( 0.f );
					}

					if( lower
						&& options::aimbot::exploits::misc::no_lower )
						lower->set_should_lower( false );
				}

				//core::base_projectile* proj = reinterpret_cast< core::base_projectile* >( held_item );

				//if( proj ) {
				//	std::cout << "ayo" << std::endl;
				//	if( g_sdk.get_key( key_code::N ) ) {
				//		core::base_projectile::Magazine* magazine = proj->get_primaryMagazine( );
				//		if( magazine ) {
				//			proj->launch_projectile( );
				//			magazine->contents( )--;
				//			proj->update_ammo_display( );
				//			proj->shot_fired( );
				//			proj->did_attack_clientside( );
				//		}
				//	}
				//}

				handle_exploits( local_player, item );
				handle_rpc_exploits( local_player, item );
			}

			if( ( g_sdk.get_key( options::aimbot::exploits::misc::pickup_key ) || options::aimbot::exploits::misc::always_pickup ) ) {
				if( options::aimbot::exploits::misc::auto_pickup_items ) {
					core::base_entity* entity = g_esp.get_closest_object_of_class( xs( "DroppedItem" ), options::aimbot::exploits::misc::max_item_distance );
					if( entity ) {
						bool can_pickup = false;

						core::item* item = entity->get_world_item( );
						if( item ) {
							std::string text = g_sdk.ws2s( item->get_weapon_name( ) );
							if( options::aimbot::exploits::misc::pickup_everything )
								can_pickup = true;

							if( item->is_gun( ) )
								can_pickup = true;
							else if( item->is_melee( ) )
								can_pickup = true;
							else if( item->is_heal( ) )
								can_pickup = true;
							else if( text.find( "scrap" ) != std::string::npos )
								can_pickup = true;
							else if( text.find( "ammo" ) != std::string::npos ) {
								if( text.find( "incendiary" ) != std::string::npos )
									can_pickup = true;
								else if( text.find( "hv" ) != std::string::npos )
									can_pickup = true;
								else if( text.find( "explosive" ) != std::string::npos )
									can_pickup = true;
								else 
									can_pickup = true;
							}
						}
						if( can_pickup )
							entity->server_rpc( xs( "Pickup" ) );
					}
				}
				if( options::aimbot::exploits::misc::auto_pickup ) {
					core::base_entity* collectible = g_esp.get_closest_object_of_class( xs( "CollectibleEntity" ), options::aimbot::exploits::misc::max_collectible_distance );
					if( collectible )
						collectible->server_rpc( xs( "Pickup" ) );
				}
			}
			if( options::aimbot::exploits::misc::auto_grade
				&& ( g_sdk.get_key( options::aimbot::exploits::misc::grade_key ) || options::aimbot::exploits::misc::always_grade ) ) {
				core::building_block* building_block = ( core::building_block* )g_esp.get_closest_object_of_class( xs( "BuildingBlock" ), options::aimbot::exploits::misc::max_grade_distance );
				if( building_block )
					if( building_block->can_upgrade( options::aimbot::exploits::misc::grade_tier, 0, local_player ) ) {
						if( building_block->can_afford( options::aimbot::exploits::misc::grade_tier, 0, local_player ) )
							building_block->upgrade( options::aimbot::exploits::misc::grade_tier, 0, local_player );
					}
			}
			if( options::aimbot::exploits::misc::auto_codelock 
				&& ( g_sdk.get_key( options::aimbot::exploits::misc::codelock_key ) || options::aimbot::exploits::misc::always_pickup ) ) {
				auto code = std::to_string( options::aimbot::exploits::misc::code_lock_code );

				core::base_entity* code_lock = g_esp.get_closest_object_of_class( xs( "CodeLock" ), options::aimbot::exploits::misc::max_lock_distance );
				if( code_lock ) {
					local_player->server_rpc( ( uintptr_t )code_lock, xs( "RPC_ChangeCode" ), code.c_str( ), false );
					local_player->server_rpc( ( uintptr_t )code_lock, xs( "TryLock" ) );
					local_player->server_rpc( ( uintptr_t )code_lock, xs( "RPC_Lock" ) );
				}
			}
		}

		spoof_ret( orig_baseplayer_client_input, player, state );

		g_cheat.global_time = g_sdk.get_time( );

		if( local_player )
		{
			if( options::aimbot::exploits::misc::gesture_spam ) {
				switch( options::aimbot::exploits::misc::gesture_type ) {
				case 0:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "clap" ) );
					break;
				case 1:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "friendly" ) );
					break;
				case 2:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "thumbsdown" ) );
					break;
				case 3:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "thumbsup" ) );
					break;
				case 4:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "ok" ) );
					break;
				case 5:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "point" ) );
					break;
				case 6:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "shrug" ) );
					break;
				case 7:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "victory" ) );
					break;
				case 8:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "wave" ) );
					break;
				case 9:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "dance.cabbagepatch" ) );
					break;
				case 10:
					local_player->send_signal_broadcast( Signal::Gesture, xs( "dance.twist" ) );
					break;
				}
			}

			if( options::aimbot::exploits::misc::spin_bot )
			{
				vec3_t angle{ };
				angle.x = std::sinf( ( g_sdk.system_time( ) * 180.f ) * 3.14f ) * 180.f; // this will be our yaw.
				angle.y = std::sinf( ( g_sdk.system_time( ) * 360.f ) * 3.14f ) * 360.f; // pitch
				angle.z = std::sinf( ( g_sdk.system_time( ) * 90.f ) * 3.14f ) * 90.f; // roll

				core::input_message* input_message = state->get_input_message( );
				if( input_message )
					input_message->set_aim_angles( angle );
			}

			if( options::aimbot::exploits::misc::fake_admin )
				local_player->add_flag( player_flags::is_admin );

			core::model_state* model_state = local_player->get_modelstate( );
			if( model_state ) {
				model_state->remove_flag( model_state_flags::in_fly );
				if( options::aimbot::exploits::misc::interactive_debug )
					model_state->add_flag( model_state_flags::is_mounted );

				core::player_walk_movement* movement = local_player->get_movement( );
				if( movement ) {
					if( options::aimbot::exploits::movement::always_sprint ) {
						model_state->add_flag( model_state_flags::in_sprint );
						movement->set_is_running( 1.f );
					}
				}
				
				if( options::aimbot::exploits::movement::omni_sprint ) {
					model_state->add_flag( model_state_flags::in_sprint );
					model_state->set_sprinting( true );

					if( g_sdk.get_key( options::aimbot::exploits::movement::omni_sprint_key ) )
						g_sdk.set_timescale( options::aimbot::exploits::movement::omni_sprint_speed / 100.f );
					else
						g_sdk.set_timescale( 1.f );
				}
				else
					g_sdk.set_timescale( 1.f );

				if( options::visuals::world::night_stars )
					model_state->add_flag( model_state_flags::asleep );

				if( options::aimbot::exploits::movement::silent_walk
					&& g_sdk.get_key( key_code::LeftShift ) ) {
					model_state->set_onLadder( true );
					model_state->add_flag( model_state_flags::on_ladder );
				}
			}
		}
	}

	inline void fix_culling_hook( core::base_player* baseplayer, float dist, bool visibility = false )
	{
		auto orig_fix_culling = reinterpret_cast< void( * )( core::base_player*, float, bool ) >( hook_address[ 2 ] );
		if( options::visuals::chams )
			return spoof_ret( orig_fix_culling, baseplayer, 150.f, true );

		return spoof_ret( orig_fix_culling, baseplayer, dist, visibility );
	}

	inline void on_attacked_hook( void* instance, core::hit_info* hit_info )
	{
		auto orig_on_attacked = reinterpret_cast< void( * )( void*, core::hit_info* ) >( hook_address[ 3 ] );

		core::base_entity* hit_entity = hit_info->get_hit_entity( );

		core::base_player* local = g_cheat.local;
        if( !local )
			return spoof_ret( orig_on_attacked, instance, hit_info );

        core::player_eyes* eyes = local->get_eyes( );
        if( !eyes )
            return spoof_ret( orig_on_attacked, instance, hit_info );

        vec3_t head_pos = local->get_bone_position( head );

		bool has_up_view_offset = options::aimbot::exploits::misc::long_neck
			&& g_sdk.get_key( options::aimbot::exploits::misc::view_height );

		bool has_right_view_offset = options::aimbot::exploits::misc::long_neck_right
			&& g_sdk.get_key( options::aimbot::exploits::misc::view_right );

		bool has_left_view_offset = options::aimbot::exploits::misc::long_neck_left
			&& g_sdk.get_key( options::aimbot::exploits::misc::view_left );

		float height_view_offset = ( options::aimbot::exploits::misc::long_neck_height / 100.f );

		float left_view_offset = ( options::aimbot::exploits::misc::long_neck_left_amount / 100.f );

		float right_view_offset = ( options::aimbot::exploits::misc::long_neck_right_amount / 100.f );

		if( g_sdk.get_key( options::aimbot::exploits::misc::view_height ) )
			head_pos.y += height_view_offset;
		
		if( g_sdk.get_key( options::aimbot::exploits::misc::view_left ) )
			head_pos.x -= left_view_offset;
		else if( g_sdk.get_key( options::aimbot::exploits::misc::view_right ) )
			head_pos.x += right_view_offset;

		if( hit_entity )
			g_esp.m_shots.emplace_back( c_esp::shot_record_t( g_sdk.get_time( ), head_pos, hit_info->get_hit_end( ), 
				reinterpret_cast< core::base_player* >( hit_entity ) ) );

		return spoof_ret( orig_on_attacked, instance, hit_info );
	}
}

namespace item_icon {
	inline void try_to_move_hook( core::item_icon* item )
	{
		auto orig_try_to_move = reinterpret_cast< void( * )( core::item_icon* ) >( hook_address[ 4 ] );

		if( options::aimbot::exploits::time::fast_loot ) {
			if( item->queued_for_looting( ) )
				item->run_timed_action( );
		}

		spoof_ret( orig_try_to_move, item );
	}
}

namespace player_eyes {
	vec3_t get_body_lean_offset_hook( core::player_eyes* instance ) {
		auto orig_player_eyes_get_body_lean_offset = reinterpret_cast< vec3_t( * )( core::player_eyes* ) >( hook_address[ 4 ] );

		if( !g_esp.manipulation_angle.is_zero( ) ) {
			std::cout << "in hook cf" << std::endl;
			return g_esp.manipulation_angle;
		}
		std::cout << "in hook rn" << std::endl;
		return spoof_ret( orig_player_eyes_get_body_lean_offset, instance );
	}
}

namespace modelstate
{
	inline void is_flying_hook( bool is_flying )
	{
		auto orig_modelstate_is_flying = reinterpret_cast< void( * )( bool ) >( hook_address[ 4 ] );

		if( options::aimbot::exploits::misc::fake_admin ) {
			is_flying = false;
			return;
		}

		return spoof_ret( orig_modelstate_is_flying, is_flying );
	}
}#pragma once

#include "includes.hpp"
#include "../game/sdk.hpp"
#include "../utilities/returnspoofer.hpp"
#include "../utilities/memory.hpp"
#include "../features/menu/framework/gui_framework.h"

constexpr int max_hooks = 9;
inline std::array< uintptr_t, max_hooks > hook_address;
#pragma once
#include <Windows.h>
#include <iostream>
#include <fstream>
#include <sstream>
#include <thread>
#include <string>
#include <vector>
#include <codecvt>
#include <algorithm>
#include <regex>
#include <memory>
#include <functional>
#include <stdio.h>
#include <Psapi.h>
#include <cstdint>
#include <chrono>
#include <array>
#include <inttypes.h>
#include <utility>
#include <coroutine>

#include "../utilities/math.hpp"
#include "../utilities/xor.hpp"

#include "../game/render/render.h"

#pragma comment( lib, "user32.lib" )
#pragma comment( lib, "winmm.lib" )
/*Licensed under MIT or Public Domain. See bottom of file for details.

ferr_hash.h

	This is a collection of hashing functions that I use in various projects.
	It's mostly an effort to consolidate and clean the stuff I've scattered
	around my code!

	Included is an FNV-1a hash that I use often, plus a compile-time variant
	that can be great for avoiding runtime hashing costs. They don't match
	eachother, but I added a runtime variant that does match. Just in case.

	Works on strings and data chunks.

Example usage:

	struct test_t {
		float x, y, z;
	};

	const char *str = "test a hash!";

	uint32_t h_const = hashc_constfnv32_string("test a hash!"); // Compile time: 3166176921
	uint32_t h_dyn   = hash_constfnv32_string(str);             // Runtime:      3166176921
	uint32_t h_fnv   = hash_fnv32_string(str);                  // 1193034313

	uint64_t h64_const = hashc_constfnv64_string("test a hash!"); // Compile time: 9942215223050522873
	uint64_t h64_dyn   = hash_constfnv64_string(str);             // Runtime:      9942215223050522873
	uint64_t h64_fnv   = hash_fnv64_string(str);                  // 15918807425826589481

	test_t tmp = { 10, 1, 10 };
	uint32_t h_struct1 = hash_fnv32_data(&tmp, sizeof(test_t));  // 1650533608

	test_t tmp2 = { 10, 1, 10 };
	uint32_t h_struct2 = hash_fnv32_data(&tmp2, sizeof(test_t)); // 1650533608
*/

#pragma once

#include <stdint.h>

#ifdef __cplusplus
#define FERR_HASH_DEFAULT(x) = x
#else
#define FERR_HASH_DEFAULT(x)
#endif

///////////////////////////////////////////
//             FNV-1a hash!              //
///////////////////////////////////////////
// See: http://isthe.com/chongo/tech/comp/fnv/
// for details about FNV-1a

#define HASH_FNV32_START 2166136261
#define HASH_FNV64_START 14695981039346656037

uint64_t hash_fnv64_string ( const char* string, uint64_t start_hash FERR_HASH_DEFAULT ( HASH_FNV64_START ) );
uint64_t hash_fnv64_data ( const void* data, size_t data_size, uint64_t start_hash FERR_HASH_DEFAULT ( HASH_FNV64_START ) );

uint32_t hash_fnv32_string ( const char* string, uint32_t start_hash FERR_HASH_DEFAULT ( HASH_FNV32_START ) );
uint32_t hash_fnv32_data ( const void* data, size_t data_size, uint32_t start_hash FERR_HASH_DEFAULT ( HASH_FNV32_START ) );

///////////////////////////////////////////
//         Compile time hash!            //
///////////////////////////////////////////
//
// hash64c_constfnv_string and hash32c_constfnv_string execute at compile
// time, so you don't have to worry about cost to calculate during runtime.
// They're based on FNV-1a but don't produce the same results. They also have
// a limit of 64 characters. Characters after that will be ignored.
// See http://lolengine.net/blog/2011/12/20/cpp-constant-string-hash for
// details about this implementation.
//
// You can also use hash32_constfnv_string or hash64_constfnv_string to run
// the exact same hash at runtime, if you need to compare a dynamic string 
// with one built at compile time. It's slower than the regular fnv hash too.

#ifndef hash32c_constfnv_string
#define _h32_H1(s,i,x)  (((x)^s[ (i)< sizeof(s)?(i):sizeof(s)-1 ])*16777619u)
#define _h32_H4(s,i,x)  _h32_H1 (s,i+3, _h32_H1 (s,i+2, _h32_H1 (s,i+1 ,_h32_H1 (s,i,x))))
#define _h32_H16(s,i,x) _h32_H4 (s,i+12,_h32_H4 (s,i+8, _h32_H4 (s,i+4, _h32_H4 (s,i,x))))
#define _h32_H64(s,i,x) _h32_H16(s,i+48,_h32_H16(s,i+32,_h32_H16(s,i+16,_h32_H16(s,i,x))))
#define hashc_constfnv32_string(str) ((uint32_t)(_h32_H64(str,0,HASH_FNV32_START)))
#define hashc_constfnv32_type(type) hash32c_constfnv_string(#type)

#define _h64_H1(s,i,x)  (((x)^s[ (i)< sizeof(s)?(i):sizeof(s)-1 ])*1099511628211Ui64)
#define _h64_H4(s,i,x)  _h64_H1 (s,i+3, _h64_H1 (s,i+2, _h64_H1 (s,i+1, _h64_H1 (s,i,x))))
#define _h64_H16(s,i,x) _h64_H4 (s,i+12,_h64_H4 (s,i+8, _h64_H4 (s,i+4, _h64_H4 (s,i,x))))
#define _h64_H64(s,i,x) _h64_H16(s,i+48,_h64_H16(s,i+32,_h64_H16(s,i+16,_h64_H16(s,i,x))))
#define hashc_constfnv64_string(str) ((uint64_t)(_h64_H64(str,0,HASH_FNV64_START)))
#define hashc_constfnv64_type(type) hash64c_constfnv_string(#type)
#endif

uint64_t hash_constfnv64_string ( const char* string );
uint32_t hash_constfnv32_string ( const char* string );

///////////////////////////////////////////
#define FERR_HASH_IMPL 1

#ifdef FERR_HASH_IMPL

///////////////////////////////////////////

// Creates a 64 bit hash from a string. Use start_hash with a previous hash if you want to chain hashes together.
uint64_t  hash_fnv64_string ( const char* string, uint64_t start_hash )
{
	uint64_t hash = start_hash;
	uint8_t  c;
	while( c = *string++ )
		hash = ( hash ^ c ) * 1099511628211;
	return hash;
}

///////////////////////////////////////////

// Creates a 64 bit hash from a chunk of bytes. Use start_hash with a previous hash if you want to chain hashes together.
uint64_t hash_fnv64_data ( const void* data, size_t data_size, uint64_t start_hash )
{
	uint64_t hash = start_hash;
	uint8_t* bytes = ( uint8_t* ) data;
	for( size_t i = 0; i < data_size; i++ )
		hash = ( hash ^ bytes [ i ] ) * 1099511628211;
	return hash;
}

///////////////////////////////////////////

// Creates a 32 bit hash from a string. Use start_hash with a previous hash if you want to chain hashes together.
uint32_t hash_fnv32_string ( const char* string, uint32_t start_hash )
{
	uint32_t hash = start_hash;
	uint8_t  c;
	while( c = *string++ )
		hash = ( hash ^ c ) * 16777619;
	return hash;
}

///////////////////////////////////////////

// Creates a 32 bit hash from a chunk of bytes. Use start_hash with a previous hash if you want to chain hashes together.
uint32_t hash_fnv32_data ( const void* data, size_t data_size, uint32_t start_hash )
{
	uint32_t hash = start_hash;
	uint8_t* bytes = ( uint8_t* ) data;
	for( size_t i = 0; i < data_size; i++ )
		hash = ( hash ^ bytes [ i ] ) * 16777619;
	return hash;
}

///////////////////////////////////////////

uint64_t hash_constfnv64_string ( const char* string )
{
	uint64_t hash = HASH_FNV64_START;
	uint8_t  c = string [ 0 ];
	for( size_t i = 0; i < 64; i++ )
	{
		if( c != 0 ) c = string [ i ];
		hash = ( hash ^ c ) * 1099511628211;
	}
	return hash;
}

///////////////////////////////////////////

uint32_t hash_constfnv32_string ( const char* string )
{
	uint32_t hash = HASH_FNV32_START;
	uint8_t  c = string [ 0 ];
	for( size_t i = 0; i < 64; i++ )
	{
		if( c != 0 ) c = string [ i ];
		hash = ( hash ^ c ) * 16777619;
	}
	return hash;
}

#endif


/*
------------------------------------------------------------------------------
This software is available under 2 licenses -- choose whichever you prefer.
------------------------------------------------------------------------------
ALTERNATIVE A - MIT License
Copyright (c) 2020 Nick Klingensmith
Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
------------------------------------------------------------------------------
ALTERNATIVE B - Public Domain (www.unlicense.org)
This is free and unencumbered software released into the public domain.
Anyone is free to copy, modify, publish, use, compile, sell, or distribute this
software, either in source code form or as a compiled binary, for any purpose,
commercial or non-commercial, and by any means.
In jurisdictions that recognize copyright laws, the author or authors of this
software dedicate any and all copyright interest in the software to the public
domain. We make this dedication for the benefit of the public at large and to
the detriment of our heirs and successors. We intend this dedication to be an
overt act of relinquishment in perpetuity of all present and future rights to
this software under copyright law.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN
ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
------------------------------------------------------------------------------
*/
	auto Get = reinterpret_cast< void( * )( ) >( method_ptr );
	spoof_ret( Get );#pragma once
#include <Windows.h>
#include <vector>
#include <cmath>
#include <iostream>
#include "../includes/includes.hpp"

#include "../vector/vector2.hpp"
#include "../vector/vector3.hpp"
#include "../vector/vector4.hpp"
#include "../vector/color.hpp"

#define M_PI 3.14159265358979323846f
#define M_PI_F ( ( float )( M_PI ) )
#define RAD2DEG( x ) ( ( float )( x ) * ( float )( 180.f / M_PI_F ) )

#define PI 3.14159265358979323846f
#define PIX2 6.28318530718
#define PI_2 1.57079632679489661923

struct matrix_4x4 {
	public:
	inline float* operator[ ]( int i ) {
		return m[ i ];
	}

	inline const float* operator[ ]( int i ) const {
		return m[ i ];
	}

	inline float* base( ) {
		return &m[ 0 ][ 0 ];
	}

	inline const float* base( ) const {
		return &m[ 0 ][ 0 ];
	}
public:
	inline matrix_4x4( ) {
		init( 
			0.0f, 0.0f, 0.0f, 0.0f,
			0.0f, 0.0f, 0.0f, 0.0f,
			0.0f, 0.0f, 0.0f, 0.0f,
			0.0f, 0.0f, 0.0f, 0.0f
		 );
	}

	inline matrix_4x4( 
		float m00, float m01, float m02, float m03,
		float m10, float m11, float m12, float m13,
		float m20, float m21, float m22, float m23,
		float m30, float m31, float m32, float m33 ) {
		init( 
			m00, m01, m02, m03,
			m10, m11, m12, m13,
			m20, m21, m22, m23,
			m30, m31, m32, m33
		 );
	}

	inline void init( 
		float m00, float m01, float m02, float m03,
		float m10, float m11, float m12, float m13,
		float m20, float m21, float m22, float m23,
		float m30, float m31, float m32, float m33
	 ) {
		m[ 0 ][ 0 ] = m00;
		m[ 0 ][ 1 ] = m01;
		m[ 0 ][ 2 ] = m02;
		m[ 0 ][ 3 ] = m03;

		m[ 1 ][ 0 ] = m10;
		m[ 1 ][ 1 ] = m11;
		m[ 1 ][ 2 ] = m12;
		m[ 1 ][ 3 ] = m13;

		m[ 2 ][ 0 ] = m20;
		m[ 2 ][ 1 ] = m21;
		m[ 2 ][ 2 ] = m22;
		m[ 2 ][ 3 ] = m23;

		m[ 3 ][ 0 ] = m30;
		m[ 3 ][ 1 ] = m31;
		m[ 3 ][ 2 ] = m32;
		m[ 3 ][ 3 ] = m33;
	}

	matrix_4x4 transpose( ) const {
		return matrix_4x4( 
			m[ 0 ][ 0 ], m[ 1 ][ 0 ], m[ 2 ][ 0 ], m[ 3 ][ 0 ],
			m[ 0 ][ 1 ], m[ 1 ][ 1 ], m[ 2 ][ 1 ], m[ 3 ][ 1 ],
			m[ 0 ][ 2 ], m[ 1 ][ 2 ], m[ 2 ][ 2 ], m[ 3 ][ 2 ],
			m[ 0 ][ 3 ], m[ 1 ][ 3 ], m[ 2 ][ 3 ], m[ 3 ][ 3 ] );
	}

	float m[ 4 ][ 4 ];
};

class c_math
{
public:
	vec3_t cross_vector( vec3_t first_vec, vec3_t second_vec );

	typedef struct { double d0, d1; } double2;

	vec3_t to_euler_angles( vec4_t q1 );

	vec2_t cos_tan_horizontal( float, float, float, float, int );

	std::string remove_trailing_zeros( float );

	vec2_t calculate_angle( const vec3_t& Src, const vec3_t& Dst );
	vec3_t quatmult( const vec3_t* point, vec4_t* quat );
	vec2_t unity_calculate_angle( const vec3_t& src, const vec3_t& dst );

	float normalize_angle( float angle );

	vec3_t normalize_angles( vec3_t angles );

	void normalize( vec2_t& angle );

    float to_rad( float val );
};

extern c_math g_math;

#define ImSqrt( x ) g_math.sqrt( x )
#define ImFabs( x ) g_math.abs( x )
#include "memory.hpp"
#include "lazy_importer.hpp"
#include "../game/sdk.hpp"
#include <stdlib.h>
#include <limits.h>
#include <cctype>
#include <climits>

#define in_range( x,a,b ) ( x >=a&&x<=b ) 
#define get_bits( x ) ( in_range( ( x&( ~0x20 ) ),'A','F' )?( ( x&( ~0x20 ) )-'A'+0xa ):( in_range( x,'0','9' )?x-'0':0 ) )
#define get_byte( x ) ( get_bits( x[ 0 ] )<< 4|get_bits( x[ 1 ] ) )


#ifndef ULONG_MAX
#define        ULONG_MAX        ( ( unsigned long )( ~0L ) )                /* 0xFFFFFFFF */
#endif
/*
 * Convert a string to an unsigned long integer.
 *
 * Ignores `locale' stuff.  Assumes that the upper and lower case
 * alphabets and digits are each contiguous.
 */

uintptr_t memory::sigscan( const char* scanmodule, const char* pattern, int jump )
{
    uintptr_t moduleAdress = 0;
    const auto mod = scanmodule;
    //moduleAdress = LI_MODULE( mod ).get< uintptr_t >( );

    static auto patternToByte = [ ]( const char* pattern )
    {
        auto       bytes = std::vector< int >{ };
        const auto start = const_cast< char* >( pattern );
        const auto end = const_cast< char* >( pattern ) + strlen( pattern );

        for( auto current = start; current < end; ++current )
        {
            if( *current == '?' )
            {
                ++current;
                if( *current == '?' )
                    ++current;
                bytes.push_back( -1 );
            }
            else { bytes.push_back( strtoul( current, &current, 16 ) ); }
        }
        return bytes;
    };

    const auto dosHeader = ( PIMAGE_DOS_HEADER )moduleAdress;
    if( !dosHeader )
        return NULL;

    const auto ntHeaders = ( PIMAGE_NT_HEADERS )( ( std::uint8_t* )moduleAdress + dosHeader->e_lfanew );

    const auto sizeOfImage = ntHeaders->OptionalHeader.SizeOfImage;
    auto       patternBytes = patternToByte( pattern );
    const auto scanBytes = reinterpret_cast< std::uint8_t* >( moduleAdress );

    const auto s = patternBytes.size( );
    const auto d = patternBytes.data( );

    for( auto i = 0ul; i < sizeOfImage - s; ++i )
    {
        bool found = true;
        for( auto j = 0ul; j < s; ++j )
        {
            if( scanBytes[ i + j ] != d[ j ] && d[ j ] != -1 )
            {
                found = false;
                break;
            }
        }
        if( found )
        {
            if( !jump )
                return reinterpret_cast< uintptr_t >( &scanBytes[ i ] );
            else
            {
                uintptr_t patterScanResult = ( reinterpret_cast< uintptr_t >( &scanBytes[ i ] ) + jump );
                int relative = read< int >( patterScanResult + 3 );
                return ( patterScanResult + 7 + relative );
            }
        }
    }
    return NULL;
}

uintptr_t memory::find( uintptr_t range_start, uintptr_t range_end, const char* pattern ) {
    const char* pattern_bytes = pattern;

    uintptr_t first_match = 0;

    for( uintptr_t cur_byte = range_start; cur_byte < range_end; cur_byte++ ) {
        if( !*pattern_bytes )
            return first_match;

        if( *( uint8_t* )pattern_bytes == '\?' || *( uint8_t* )cur_byte == static_cast< uint8_t >( get_byte( pattern_bytes ) ) ) {
            if( !first_match )
                first_match = cur_byte;

            if( !pattern_bytes[ 2 ] )
                return first_match;

            if( *( uint16_t* )pattern_bytes == '\?\?' || *( uint8_t* )pattern_bytes != '\?' )
                pattern_bytes += 3;
            else
                pattern_bytes += 2;
        }
        else {
            pattern_bytes = pattern;
            first_match = 0;
        }
    }

    return 0;
}

uintptr_t memory::find( const char* mod, const char* pattern ) {
    const char* pattern_bytes = pattern;

    uintptr_t range_start = LI_MODULE_SAFE_( "GameAssembly.dll" );
    uintptr_t range_size = LI_MODULESIZE_SAFE_( "GameAssembly.dll" );
    uintptr_t range_end = range_start + range_size;

    return find( range_start, range_end, pattern );
}

uintptr_t memory::find_rel( const char* mod, const char* pattern, ptrdiff_t position, ptrdiff_t jmp_size, ptrdiff_t instruction_size ) {
    auto result = find( mod, pattern );

    if( !result )
        return 0;

    result += position;

    auto rel_addr = *reinterpret_cast< int32_t* >( result + jmp_size );
    auto abs_addr = result + instruction_size + rel_addr;

    return abs_addr;
}
#pragma once
#include "../includes/includes.hpp"

namespace memory
{
    uintptr_t sigscan( const char* module, const char* pattern, int jump = 0 );
    uintptr_t find( uintptr_t range_start, uintptr_t range_end, const char* pattern );
    uintptr_t find( const char* mod, const char* pattern );

    uintptr_t find_rel( const char* mod, const char* pattern, ptrdiff_t position = 0, ptrdiff_t jmp_size = 3, ptrdiff_t instruction_size = 7 );

    template< typename t = uintptr_t >
    t read( uintptr_t address )
    {
        if( !address )
        {
            return t( );
        }
        else if( address < 0xffffff )
        {
            return t( );
        }
        else if( address > 0x7fffffff0000 )
        {
            return t( );
        }
        else
        {
            return *reinterpret_cast< t* >( address );
        }
    }

    template< typename t >
    t read_chain( uintptr_t address, std::vector< uintptr_t > chain )
    {
        uintptr_t cur_read = address;

        for( int i = 0; i < chain.size( ) - 1; ++i )
            cur_read = read< uintptr_t >( cur_read + chain[ i ] );

        return read< t >( cur_read + chain[ chain.size( ) - 1 ] );
    }
}
#pragma once
#include <type_traits>

template < typename result, typename... arguments >
__forceinline static result spoof_ret( result( *fn )( arguments... ), arguments... args )
{
	return fn( args... );
}

/*
 * Copyright 2017 - 2021 Justas Masiulis
 *
 * Licensed under the Apache License, Version 2.0 ( the "License" );
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

#ifndef JM_XORSTR_HPP
#define JM_XORSTR_HPP

#if defined( _M_ARM64 ) || defined( __aarch64__ ) || defined( _M_ARM ) || defined( __arm__ )
#include <arm_neon.h>
#elif defined( _M_X64 ) || defined( __amd64__ ) || defined( _M_IX86 ) || defined( __i386__ )
#include <immintrin.h>
#else
#error Unsupported platform
#endif

#include <cstdint>
#include <cstddef>
#include <utility>
#include <type_traits>

#define xorstr( str ) ::jm::xor_string( [ ]( ) { return str; }, std::integral_constant< std::size_t, sizeof( str ) / sizeof( *str ) >{ }, std::make_index_sequence< ::jm::detail::_buffer_size< sizeof( str ) >( ) >{ } )
#define xs( str ) xorstr( str ).crypt_get( )

#ifdef _MSC_VER
#define JM_XORSTR_FORCEINLINE __forceinline
#else
#define JM_XORSTR_FORCEINLINE __attribute__( ( always_inline ) ) inline
#endif

#if defined( __clang__ ) || defined( __GNUC__ )
#define JM_XORSTR_LOAD_FROM_REG( x ) ::jm::detail::load_from_reg( x )
#else
#define JM_XORSTR_LOAD_FROM_REG( x ) ( x )
#endif

namespace jm {
    namespace detail {

        template< std::size_t Size >
        JM_XORSTR_FORCEINLINE constexpr std::size_t _buffer_size( )
        {
            return ( ( Size / 16 ) + ( Size % 16 != 0 ) ) * 2;
        }

        template< uint32_t Seed >
        JM_XORSTR_FORCEINLINE constexpr uint32_t key4( ) noexcept
        {
            uint32_t value = Seed;
            for( char c : __TIME__ )
                value = static_cast< uint32_t >( ( value ^ c ) * 16777619ull );
            return value;
        }

        template< std::size_t S >
        JM_XORSTR_FORCEINLINE constexpr std::uint64_t key8( )
        {
            constexpr auto first_part = key4< 2166136261 + S >( );
            constexpr auto second_part = key4< first_part >( );
            return ( static_cast< std::uint64_t >( first_part ) << 32 ) | second_part;
        }

        // loads up to 8 characters of string into uint64 and xors it with the key
        template< std::size_t N, class CharT >
        JM_XORSTR_FORCEINLINE constexpr std::uint64_t
            load_xored_str8( std::uint64_t key, std::size_t idx, const CharT* str ) noexcept
        {
            using cast_type = typename std::make_unsigned< CharT >::type;
            constexpr auto value_size = sizeof( CharT );
            constexpr auto idx_offset = 8 / value_size;

            std::uint64_t value = key;
            for( std::size_t i = 0; i < idx_offset && i + idx * idx_offset < N; ++i )
                value ^=
                ( std::uint64_t{ static_cast< cast_type >( str[ i + idx * idx_offset ] ) }
            << ( ( i % idx_offset ) * 8 * value_size ) );

            return value;
        }

        // forces compiler to use registers instead of stuffing constants in rdata
        JM_XORSTR_FORCEINLINE std::uint64_t load_from_reg( std::uint64_t value ) noexcept
        {
#if defined( __clang__ ) || defined( __GNUC__ )
            asm( "" : "=r"( value ) : "0"( value ) : );
#endif
            return value;
        }

        template< std::uint64_t V >
        struct uint64_v {
            constexpr static std::uint64_t value = V;
        };

    } // namespace detail

    template< class CharT, std::size_t Size, class Keys, class Indices >
    class xor_string;

    template< class CharT, std::size_t Size, std::uint64_t... Keys, std::size_t... Indices >
    class xor_string< CharT, Size, std::integer_sequence< std::uint64_t, Keys... >, std::index_sequence< Indices... >> {
#ifndef JM_XORSTR_DISABLE_AVX_INTRINSICS
        constexpr static inline std::uint64_t alignment = ( ( Size > 16 ) ? 32 : 16 );
#else
        constexpr static inline std::uint64_t alignment = 16;
#endif

        alignas( alignment ) std::uint64_t _storage[ sizeof...( Keys ) ];

    public:
        using value_type = CharT;
        using size_type = std::size_t;
        using pointer = CharT*;
        using const_pointer = const CharT*;

        template< class L >
        JM_XORSTR_FORCEINLINE xor_string( L l, std::integral_constant< std::size_t, Size >, std::index_sequence< Indices... > ) noexcept
            : _storage{ JM_XORSTR_LOAD_FROM_REG( detail::uint64_v< detail::load_xored_str8< Size >( Keys, Indices, l( ) ) >::value )... }
        { }

        JM_XORSTR_FORCEINLINE constexpr size_type size( ) const noexcept
        {
            return Size - 1;
        }

        JM_XORSTR_FORCEINLINE void crypt( ) noexcept
        {
            // everything is inlined by hand because a certain compiler with a certain linker is _very_ slow
#if defined( __clang__ )
            alignas( alignment )
                std::uint64_t arr[ ]{ JM_XORSTR_LOAD_FROM_REG( Keys )... };
            std::uint64_t* keys =
                ( std::uint64_t* )JM_XORSTR_LOAD_FROM_REG( ( std::uint64_t )arr );
#else
            alignas( alignment ) std::uint64_t keys[ ]{ JM_XORSTR_LOAD_FROM_REG( Keys )... };
#endif

#if defined( _M_ARM64 ) || defined( __aarch64__ ) || defined( _M_ARM ) || defined( __arm__ )
#if defined( __clang__ )
            ( ( Indices >= sizeof( _storage ) / 16 ? static_cast< void >( 0 ) : __builtin_neon_vst1q_v( 
                reinterpret_cast< uint64_t* >( _storage ) + Indices * 2,
                veorq_u64( __builtin_neon_vld1q_v( reinterpret_cast< const uint64_t* >( _storage ) + Indices * 2, 51 ),
                    __builtin_neon_vld1q_v( reinterpret_cast< const uint64_t* >( keys ) + Indices * 2, 51 ) ),
                51 ) ), ... );
#else // GCC, MSVC
            ( ( Indices >= sizeof( _storage ) / 16 ? static_cast< void >( 0 ) : vst1q_u64( 
                reinterpret_cast< uint64_t* >( _storage ) + Indices * 2,
                veorq_u64( vld1q_u64( reinterpret_cast< const uint64_t* >( _storage ) + Indices * 2 ),
                    vld1q_u64( reinterpret_cast< const uint64_t* >( keys ) + Indices * 2 ) ) ) ), ... );
#endif
#elif !defined( JM_XORSTR_DISABLE_AVX_INTRINSICS )
            ( ( Indices >= sizeof( _storage ) / 32 ? static_cast< void >( 0 ) : _mm256_store_si256( 
                reinterpret_cast< __m256i* >( _storage ) + Indices,
                _mm256_xor_si256( 
                    _mm256_load_si256( reinterpret_cast< const __m256i* >( _storage ) + Indices ),
                    _mm256_load_si256( reinterpret_cast< const __m256i* >( keys ) + Indices ) ) ) ), ... );

            if constexpr ( sizeof( _storage ) % 32 != 0 )
                _mm_store_si128( 
                    reinterpret_cast< __m128i* >( _storage + sizeof...( Keys ) - 2 ),
                    _mm_xor_si128( _mm_load_si128( reinterpret_cast< const __m128i* >( _storage + sizeof...( Keys ) - 2 ) ),
                        _mm_load_si128( reinterpret_cast< const __m128i* >( keys + sizeof...( Keys ) - 2 ) ) ) );
#else
            ( ( Indices >= sizeof( _storage ) / 16 ? static_cast< void >( 0 ) : _mm_store_si128( 
                reinterpret_cast< __m128i* >( _storage ) + Indices,
                _mm_xor_si128( _mm_load_si128( reinterpret_cast< const __m128i* >( _storage ) + Indices ),
                    _mm_load_si128( reinterpret_cast< const __m128i* >( keys ) + Indices ) ) ) ), ... );
#endif
        }

        JM_XORSTR_FORCEINLINE const_pointer get( ) const noexcept
        {
            return reinterpret_cast< const_pointer >( _storage );
        }

        JM_XORSTR_FORCEINLINE pointer get( ) noexcept
        {
            return reinterpret_cast< pointer >( _storage );
        }

        JM_XORSTR_FORCEINLINE pointer crypt_get( ) noexcept
        {
            // crypt( ) is inlined by hand because a certain compiler with a certain linker is _very_ slow
#if defined( __clang__ )
            alignas( alignment )
                std::uint64_t arr[ ]{ JM_XORSTR_LOAD_FROM_REG( Keys )... };
            std::uint64_t* keys =
                ( std::uint64_t* )JM_XORSTR_LOAD_FROM_REG( ( std::uint64_t )arr );
#else
            alignas( alignment ) std::uint64_t keys[ ]{ JM_XORSTR_LOAD_FROM_REG( Keys )... };
#endif

#if defined( _M_ARM64 ) || defined( __aarch64__ ) || defined( _M_ARM ) || defined( __arm__ )
#if defined( __clang__ )
            ( ( Indices >= sizeof( _storage ) / 16 ? static_cast< void >( 0 ) : __builtin_neon_vst1q_v( 
                reinterpret_cast< uint64_t* >( _storage ) + Indices * 2,
                veorq_u64( __builtin_neon_vld1q_v( reinterpret_cast< const uint64_t* >( _storage ) + Indices * 2, 51 ),
                    __builtin_neon_vld1q_v( reinterpret_cast< const uint64_t* >( keys ) + Indices * 2, 51 ) ),
                51 ) ), ... );
#else // GCC, MSVC
            ( ( Indices >= sizeof( _storage ) / 16 ? static_cast< void >( 0 ) : vst1q_u64( 
                reinterpret_cast< uint64_t* >( _storage ) + Indices * 2,
                veorq_u64( vld1q_u64( reinterpret_cast< const uint64_t* >( _storage ) + Indices * 2 ),
                    vld1q_u64( reinterpret_cast< const uint64_t* >( keys ) + Indices * 2 ) ) ) ), ... );
#endif
#elif !defined( JM_XORSTR_DISABLE_AVX_INTRINSICS )
            ( ( Indices >= sizeof( _storage ) / 32 ? static_cast< void >( 0 ) : _mm256_store_si256( 
                reinterpret_cast< __m256i* >( _storage ) + Indices,
                _mm256_xor_si256( 
                    _mm256_load_si256( reinterpret_cast< const __m256i* >( _storage ) + Indices ),
                    _mm256_load_si256( reinterpret_cast< const __m256i* >( keys ) + Indices ) ) ) ), ... );

            if constexpr ( sizeof( _storage ) % 32 != 0 )
                _mm_store_si128( 
                    reinterpret_cast< __m128i* >( _storage + sizeof...( Keys ) - 2 ),
                    _mm_xor_si128( _mm_load_si128( reinterpret_cast< const __m128i* >( _storage + sizeof...( Keys ) - 2 ) ),
                        _mm_load_si128( reinterpret_cast< const __m128i* >( keys + sizeof...( Keys ) - 2 ) ) ) );
#else
            ( ( Indices >= sizeof( _storage ) / 16 ? static_cast< void >( 0 ) : _mm_store_si128( 
                reinterpret_cast< __m128i* >( _storage ) + Indices,
                _mm_xor_si128( _mm_load_si128( reinterpret_cast< const __m128i* >( _storage ) + Indices ),
                    _mm_load_si128( reinterpret_cast< const __m128i* >( keys ) + Indices ) ) ) ), ... );
#endif

            return ( pointer )( _storage );
        }
    };

    template< class cL, std::size_t Size, std::size_t... Indices >
    xor_string( cL l, std::integral_constant< std::size_t, Size >, std::index_sequence< Indices... > )->xor_string< 
        std::remove_const_t< std::remove_reference_t< decltype( l( )[ 0 ] ) >>,
        Size,
        std::integer_sequence< std::uint64_t, detail::key8< Indices >( )... >,
        std::index_sequence< Indices... >>;

} // namespace jm

#endif // include guard
/*
 * Copyright 2018-2022 Justas Masiulis
 *
 * Licensed under the Apache License, Version 2.0 ( the "License" );
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

 // === FAQ === documentation is available at https://github.com/JustasMasiulis/lazy_importer
 // * Code doesn't compile with errors about pointer conversion:
 //  - Try using `nullptr` instead of `NULL` or call `get( )` instead of using the overloaded operator( )
 // * Lazy importer can't find the function I want:
 //   - Double check that the module in which it's located in is actually loaded
 //   - Try #define LAZY_IMPORTER_CASE_INSENSITIVE
 //     This will start using case insensitive comparison globally
 //   - Try #define LAZY_IMPORTER_RESOLVE_FORWARDED_EXPORTS
 //     This will enable forwarded export resolution globally instead of needing explicit `forwarded( )` calls

#ifndef LAZY_IMPORTER_HPP
#define LAZY_IMPORTER_HPP


#define LI_FN( name ) ::li::detail::lazy_function< LAZY_IMPORTER_KHASH( #name ), decltype( &name ) >( )

#define LI_FN_DEF( name ) ::li::detail::lazy_function< LAZY_IMPORTER_KHASH( #name ), name >( )

#define LI_MODULE( name ) ::li::detail::lazy_module< LAZY_IMPORTER_KHASH( name ) >( )

#define LI_MODULE_SAFE_( name ) LI_MODULE( name ).safe< uintptr_t >( )

#define LI_MODULESIZE_SAFE_( name ) LI_MODULE( name ).safesize< uintptr_t >( )

#define LI_FIND_DEF( name ) LI_FN_DEF( name ).get< name >( )

#ifndef LAZY_IMPORTER_CPP_FORWARD
#ifdef LAZY_IMPORTER_NO_CPP_FORWARD
#define LAZY_IMPORTER_CPP_FORWARD( t, v ) v
#else
#include <utility>
#define LAZY_IMPORTER_CPP_FORWARD( t, v ) std::forward< t >( v )
#endif
#endif

#include <intrin.h>

#ifndef LAZY_IMPORTER_NO_FORCEINLINE
#if defined( _MSC_VER )
#define LAZY_IMPORTER_FORCEINLINE __forceinline
#elif defined( __GNUC__ ) && __GNUC__ > 3
#define LAZY_IMPORTER_FORCEINLINE inline __attribute__( ( __always_inline__ ) )
#else
#define LAZY_IMPORTER_FORCEINLINE inline
#endif
#else
#define LAZY_IMPORTER_FORCEINLINE inline
#endif


#ifdef LAZY_IMPORTER_CASE_INSENSITIVE
#define LAZY_IMPORTER_CASE_SENSITIVITY false
#else
#define LAZY_IMPORTER_CASE_SENSITIVITY true
#endif

#define LAZY_IMPORTER_STRINGIZE( x ) #x
#define LAZY_IMPORTER_STRINGIZE_EXPAND( x ) LAZY_IMPORTER_STRINGIZE( x )

#define LAZY_IMPORTER_KHASH( str ) ::li::detail::khash( str, \
    ::li::detail::khash_impl( __TIME__ __DATE__ LAZY_IMPORTER_STRINGIZE_EXPAND( __LINE__ ) LAZY_IMPORTER_STRINGIZE_EXPAND( __COUNTER__ ), 2166136261 ) )

namespace li {
    namespace detail {

        namespace win {

            struct LIST_ENTRY_T {
                const char* Flink;
                const char* Blink;
            };

            struct UNICODE_STRING_T {
                unsigned short Length;
                unsigned short MaximumLength;
                wchar_t* Buffer;
            };

            struct PEB_LDR_DATA_T {
                unsigned long Length;
                unsigned long Initialized;
                const char* SsHandle;
                LIST_ENTRY_T  InLoadOrderModuleList;
            };

            struct PEB_T {
                unsigned char   Reserved1[ 2 ];
                unsigned char   BeingDebugged;
                unsigned char   Reserved2[ 1 ];
                const char* Reserved3[ 2 ];
                PEB_LDR_DATA_T* Ldr;
            };

            struct LDR_DATA_TABLE_ENTRY_T {
                LIST_ENTRY_T InLoadOrderLinks;
                LIST_ENTRY_T InMemoryOrderLinks;
                LIST_ENTRY_T InInitializationOrderLinks;
                const char* DllBase;
                const char* EntryPoint;
                union {
                    unsigned long SizeOfImage;
                    const char* _dummy;
                };
                UNICODE_STRING_T FullDllName;
                UNICODE_STRING_T BaseDllName;

                LAZY_IMPORTER_FORCEINLINE const LDR_DATA_TABLE_ENTRY_T*
                    load_order_next( ) const noexcept
                {
                    return reinterpret_cast< const LDR_DATA_TABLE_ENTRY_T* >( 
                        InLoadOrderLinks.Flink );
                }
            };

            struct IMAGE_DOS_HEADER { // DOS .EXE header
                unsigned short e_magic; // Magic number
                unsigned short e_cblp; // Bytes on last page of file
                unsigned short e_cp; // Pages in file
                unsigned short e_crlc; // Relocations
                unsigned short e_cparhdr; // Size of header in paragraphs
                unsigned short e_minalloc; // Minimum extra paragraphs needed
                unsigned short e_maxalloc; // Maximum extra paragraphs needed
                unsigned short e_ss; // Initial ( relative ) SS value
                unsigned short e_sp; // Initial SP value
                unsigned short e_csum; // Checksum
                unsigned short e_ip; // Initial IP value
                unsigned short e_cs; // Initial ( relative ) CS value
                unsigned short e_lfarlc; // File address of relocation table
                unsigned short e_ovno; // Overlay number
                unsigned short e_res[ 4 ]; // Reserved words
                unsigned short e_oemid; // OEM identifier ( for e_oeminfo )
                unsigned short e_oeminfo; // OEM information; e_oemid specific
                unsigned short e_res2[ 10 ]; // Reserved words
                long           e_lfanew; // File address of new exe header
            };

            struct IMAGE_FILE_HEADER {
                unsigned short Machine;
                unsigned short NumberOfSections;
                unsigned long  TimeDateStamp;
                unsigned long  PointerToSymbolTable;
                unsigned long  NumberOfSymbols;
                unsigned short SizeOfOptionalHeader;
                unsigned short Characteristics;
            };

            struct IMAGE_EXPORT_DIRECTORY {
                unsigned long  Characteristics;
                unsigned long  TimeDateStamp;
                unsigned short MajorVersion;
                unsigned short MinorVersion;
                unsigned long  Name;
                unsigned long  Base;
                unsigned long  NumberOfFunctions;
                unsigned long  NumberOfNames;
                unsigned long  AddressOfFunctions; // RVA from base of image
                unsigned long  AddressOfNames; // RVA from base of image
                unsigned long  AddressOfNameOrdinals; // RVA from base of image
            };

            struct IMAGE_DATA_DIRECTORY {
                unsigned long VirtualAddress;
                unsigned long Size;
            };

            struct IMAGE_OPTIONAL_HEADER64 {
                unsigned short       Magic;
                unsigned char        MajorLinkerVersion;
                unsigned char        MinorLinkerVersion;
                unsigned long        SizeOfCode;
                unsigned long        SizeOfInitializedData;
                unsigned long        SizeOfUninitializedData;
                unsigned long        AddressOfEntryPoint;
                unsigned long        BaseOfCode;
                unsigned long long   ImageBase;
                unsigned long        SectionAlignment;
                unsigned long        FileAlignment;
                unsigned short       MajorOperatingSystemVersion;
                unsigned short       MinorOperatingSystemVersion;
                unsigned short       MajorImageVersion;
                unsigned short       MinorImageVersion;
                unsigned short       MajorSubsystemVersion;
                unsigned short       MinorSubsystemVersion;
                unsigned long        Win32VersionValue;
                unsigned long        SizeOfImage;
                unsigned long        SizeOfHeaders;
                unsigned long        CheckSum;
                unsigned short       Subsystem;
                unsigned short       DllCharacteristics;
                unsigned long long   SizeOfStackReserve;
                unsigned long long   SizeOfStackCommit;
                unsigned long long   SizeOfHeapReserve;
                unsigned long long   SizeOfHeapCommit;
                unsigned long        LoaderFlags;
                unsigned long        NumberOfRvaAndSizes;
                IMAGE_DATA_DIRECTORY DataDirectory[ 16 ];
            };

            struct IMAGE_OPTIONAL_HEADER32 {
                unsigned short       Magic;
                unsigned char        MajorLinkerVersion;
                unsigned char        MinorLinkerVersion;
                unsigned long        SizeOfCode;
                unsigned long        SizeOfInitializedData;
                unsigned long        SizeOfUninitializedData;
                unsigned long        AddressOfEntryPoint;
                unsigned long        BaseOfCode;
                unsigned long        BaseOfData;
                unsigned long        ImageBase;
                unsigned long        SectionAlignment;
                unsigned long        FileAlignment;
                unsigned short       MajorOperatingSystemVersion;
                unsigned short       MinorOperatingSystemVersion;
                unsigned short       MajorImageVersion;
                unsigned short       MinorImageVersion;
                unsigned short       MajorSubsystemVersion;
                unsigned short       MinorSubsystemVersion;
                unsigned long        Win32VersionValue;
                unsigned long        SizeOfImage;
                unsigned long        SizeOfHeaders;
                unsigned long        CheckSum;
                unsigned short       Subsystem;
                unsigned short       DllCharacteristics;
                unsigned long        SizeOfStackReserve;
                unsigned long        SizeOfStackCommit;
                unsigned long        SizeOfHeapReserve;
                unsigned long        SizeOfHeapCommit;
                unsigned long        LoaderFlags;
                unsigned long        NumberOfRvaAndSizes;
                IMAGE_DATA_DIRECTORY DataDirectory[ 16 ];
            };

            struct IMAGE_NT_HEADERS {
                unsigned long     Signature;
                IMAGE_FILE_HEADER FileHeader;
#ifdef _WIN64
                IMAGE_OPTIONAL_HEADER64 OptionalHeader;
#else
                IMAGE_OPTIONAL_HEADER32 OptionalHeader;
#endif
            };

        } // namespace win

        struct forwarded_hashes {
            unsigned module_hash;
            unsigned function_hash;
        };

        // 64 bit integer where 32 bits are used for the hash offset
        // and remaining 32 bits are used for the hash computed using it
        using offset_hash_pair = unsigned long long;

        LAZY_IMPORTER_FORCEINLINE constexpr unsigned get_hash( offset_hash_pair pair ) noexcept { return ( pair & 0xFFFFFFFF ); }

        LAZY_IMPORTER_FORCEINLINE constexpr unsigned get_offset( offset_hash_pair pair ) noexcept { return ( pair >> 32 ); }

        template< bool CaseSensitive = LAZY_IMPORTER_CASE_SENSITIVITY >
        LAZY_IMPORTER_FORCEINLINE constexpr unsigned hash_single( unsigned value, char c ) noexcept
        {
            return static_cast< unsigned int >( 
                ( value ^ ( ( CaseSensitive && c >= 'A' && c <= 'Z' ) ? ( c | ( 1 << 5 ) ) : c ) ) *
                static_cast< unsigned long long >( 16777619 ) );
        }

        LAZY_IMPORTER_FORCEINLINE constexpr unsigned
            khash_impl( const char* str, unsigned value ) noexcept
        {
            return ( *str ? khash_impl( str + 1, hash_single( value, *str ) ) : value );
        }

        LAZY_IMPORTER_FORCEINLINE constexpr offset_hash_pair khash( 
            const char* str, unsigned offset ) noexcept
        {
            return ( ( offset_hash_pair{ offset } << 32 ) | khash_impl( str, offset ) );
        }

        template< class CharT = char >
        LAZY_IMPORTER_FORCEINLINE unsigned hash( const CharT* str, unsigned offset ) noexcept
        {
            unsigned value = offset;

            for( ;; ) {
                char c = *str++;
                if( !c )
                    return value;
                value = hash_single( value, c );
            }
        }

        LAZY_IMPORTER_FORCEINLINE unsigned hash( 
            const win::UNICODE_STRING_T& str, unsigned offset ) noexcept
        {
            auto       first = str.Buffer;
            const auto last = first + ( str.Length / sizeof( wchar_t ) );
            auto       value = offset;
            for( ; first != last; ++first )
                value = hash_single( value, static_cast< char >( *first ) );

            return value;
        }

        LAZY_IMPORTER_FORCEINLINE forwarded_hashes hash_forwarded( 
            const char* str, unsigned offset ) noexcept
        {
            forwarded_hashes res{ offset, offset };

            for( ; *str != '.'; ++str )
                res.module_hash = hash_single< true >( res.module_hash, *str );

            ++str;

            for( ; *str; ++str )
                res.function_hash = hash_single( res.function_hash, *str );

            return res;
        }

        // some helper functions
        LAZY_IMPORTER_FORCEINLINE const win::PEB_T* peb( ) noexcept
        {
#if defined( _M_X64 ) || defined( __amd64__ )
            return reinterpret_cast< const win::PEB_T* >( __readgsqword( 0x60 ) );
#elif defined( _M_IX86 ) || defined( __i386__ )
            return reinterpret_cast< const win::PEB_T* >( __readfsdword( 0x30 ) );
#elif defined( _M_ARM ) || defined( __arm__ )
            return *reinterpret_cast< const win::PEB_T** >( _MoveFromCoprocessor( 15, 0, 13, 0, 2 ) + 0x30 );
#elif defined( _M_ARM64 ) || defined( __aarch64__ )
            return *reinterpret_cast< const win::PEB_T** >( __getReg( 18 ) + 0x60 );
#elif defined( _M_IA64 ) || defined( __ia64__ )
            return *reinterpret_cast< const win::PEB_T** >( static_cast< char* >( _rdteb( ) ) + 0x60 );
#else
#error Unsupported platform. Open an issue and I'll probably add support.
#endif
        }

        LAZY_IMPORTER_FORCEINLINE const win::PEB_LDR_DATA_T* ldr( )
        {
            return reinterpret_cast< const win::PEB_LDR_DATA_T* >( peb( )->Ldr );
        }

        LAZY_IMPORTER_FORCEINLINE const win::IMAGE_NT_HEADERS* nt_headers( 
            const char* base ) noexcept
        {
            return reinterpret_cast< const win::IMAGE_NT_HEADERS* >( 
                base + reinterpret_cast< const win::IMAGE_DOS_HEADER* >( base )->e_lfanew );
        }

        LAZY_IMPORTER_FORCEINLINE const win::IMAGE_EXPORT_DIRECTORY* image_export_dir( 
            const char* base ) noexcept
        {
            return reinterpret_cast< const win::IMAGE_EXPORT_DIRECTORY* >( 
                base + nt_headers( base )->OptionalHeader.DataDirectory->VirtualAddress );
        }

        LAZY_IMPORTER_FORCEINLINE const win::LDR_DATA_TABLE_ENTRY_T* ldr_data_entry( ) noexcept
        {
            return reinterpret_cast< const win::LDR_DATA_TABLE_ENTRY_T* >( 
                ldr( )->InLoadOrderModuleList.Flink );
        }

        struct exports_directory {
            const char* _base;
            const win::IMAGE_EXPORT_DIRECTORY* _ied;
            unsigned long                      _ied_size;

        public:
            using size_type = unsigned long;

            LAZY_IMPORTER_FORCEINLINE
                exports_directory( const char* base ) noexcept : _base( base )
            {
                const auto ied_data_dir = nt_headers( base )->OptionalHeader.DataDirectory[ 0 ];
                _ied = reinterpret_cast< const win::IMAGE_EXPORT_DIRECTORY* >( 
                    base + ied_data_dir.VirtualAddress );
                _ied_size = ied_data_dir.Size;
            }

            LAZY_IMPORTER_FORCEINLINE explicit operator bool( ) const noexcept
            {
                return reinterpret_cast< const char* >( _ied ) != _base;
            }

            LAZY_IMPORTER_FORCEINLINE size_type size( ) const noexcept
            {
                return _ied->NumberOfNames;
            }

            LAZY_IMPORTER_FORCEINLINE const char* base( ) const noexcept { return _base; }
            LAZY_IMPORTER_FORCEINLINE const win::IMAGE_EXPORT_DIRECTORY* ied( ) const noexcept
            {
                return _ied;
            }

            LAZY_IMPORTER_FORCEINLINE const char* name( size_type index ) const noexcept
            {
                return reinterpret_cast< const char* >( 
                    _base + reinterpret_cast< const unsigned long* >( 
                        _base + _ied->AddressOfNames )[ index ] );
            }

            LAZY_IMPORTER_FORCEINLINE const char* address( size_type index ) const noexcept
            {
                const auto* const rva_table =
                    reinterpret_cast< const unsigned long* >( _base + _ied->AddressOfFunctions );

                const auto* const ord_table = reinterpret_cast< const unsigned short* >( 
                    _base + _ied->AddressOfNameOrdinals );

                return _base + rva_table[ ord_table[ index ] ];
            }

            LAZY_IMPORTER_FORCEINLINE bool is_forwarded( 
                const char* export_address ) const noexcept
            {
                const auto ui_ied = reinterpret_cast< const char* >( _ied );
                return ( export_address > ui_ied && export_address < ui_ied + _ied_size );
            }
        };

        struct safe_module_enumerator {
            using value_type = const detail::win::LDR_DATA_TABLE_ENTRY_T;
            value_type* value;
            value_type* head;

            LAZY_IMPORTER_FORCEINLINE safe_module_enumerator( ) noexcept
                : safe_module_enumerator( ldr_data_entry( ) )
            { }

            LAZY_IMPORTER_FORCEINLINE
                safe_module_enumerator( const detail::win::LDR_DATA_TABLE_ENTRY_T* ldr ) noexcept
                : value( ldr->load_order_next( ) ), head( value )
            { }

            LAZY_IMPORTER_FORCEINLINE void reset( ) noexcept
            {
                value = head->load_order_next( );
            }

            LAZY_IMPORTER_FORCEINLINE bool next( ) noexcept
            {
                value = value->load_order_next( );

                return value != head && value->DllBase;
            }
        };

        struct unsafe_module_enumerator {
            using value_type = const detail::win::LDR_DATA_TABLE_ENTRY_T*;
            value_type value;

            LAZY_IMPORTER_FORCEINLINE unsafe_module_enumerator( ) noexcept
                : value( ldr_data_entry( ) )
            { }

            LAZY_IMPORTER_FORCEINLINE void reset( ) noexcept { value = ldr_data_entry( ); }

            LAZY_IMPORTER_FORCEINLINE bool next( ) noexcept
            {
                value = value->load_order_next( );
                return true;
            }
        };

        // provides the cached functions which use Derive classes methods
        template< class Derived, class DefaultType = void* >
        class lazy_base {
        protected:
            // This function is needed because every templated function
            // with different args has its own static buffer
            LAZY_IMPORTER_FORCEINLINE static void*& _cache( ) noexcept
            {
                static void* value = nullptr;
                return value;
            }

        public:
            template< class T = DefaultType >
            LAZY_IMPORTER_FORCEINLINE static T safe( ) noexcept
            {
                return Derived::template get< T, safe_module_enumerator >( );
            }

            template< class T = DefaultType >
            LAZY_IMPORTER_FORCEINLINE static T safesize( ) noexcept
            {
                return Derived::template size< T, safe_module_enumerator >( );
            }

            template< class T = DefaultType, class Enum = unsafe_module_enumerator >
            LAZY_IMPORTER_FORCEINLINE static T cached( ) noexcept
            {
                auto& cached = _cache( );
                if( !cached )
                    cached = Derived::template get< void*, Enum >( );

                return ( T )( cached );
            }

            template< class T = DefaultType >
            LAZY_IMPORTER_FORCEINLINE static T safe_cached( ) noexcept
            {
                return cached< T, safe_module_enumerator >( );
            }
        };

        template< offset_hash_pair OHP >
        struct lazy_module : lazy_base< lazy_module< OHP >> {
            template< class T = void*, class Enum = unsafe_module_enumerator >
            LAZY_IMPORTER_FORCEINLINE static T get( ) noexcept
            {
                Enum e;
                do {
                    if( hash( e.value->BaseDllName, get_offset( OHP ) ) == get_hash( OHP ) )
                        return ( T )( e.value->DllBase );
                } while( e.next( ) );
                return { };
            }

            template< class T = void*, class Enum = unsafe_module_enumerator >
            LAZY_IMPORTER_FORCEINLINE static T size( ) noexcept
            {
                Enum e;
                do {
                    if( hash( e.value->BaseDllName, get_offset( OHP ) ) == get_hash( OHP ) )
                        return ( T )( e.value->SizeOfImage );
                } while( e.next( ) );
                return { };
            }

            template< class T = void*, class Ldr >
            LAZY_IMPORTER_FORCEINLINE static T in( Ldr ldr ) noexcept
            {
                safe_module_enumerator e( ( const detail::win::LDR_DATA_TABLE_ENTRY_T* )( ldr ) );
                do {
                    if( hash( e.value->BaseDllName, get_offset( OHP ) ) == get_hash( OHP ) )
                        return ( T )( e.value->DllBase );
                } while( e.next( ) );
                return { };
            }

            template< class T = void*, class Ldr >
            LAZY_IMPORTER_FORCEINLINE static T in_cached( Ldr ldr ) noexcept
            {
                auto& cached = lazy_base< lazy_module< OHP >>::_cache( );
                if( !cached )
                    cached = in( ldr );

                return ( T )( cached );
            }
        };

        template< offset_hash_pair OHP, class T >
        struct lazy_function : lazy_base< lazy_function< OHP, T >, T > {
            using base_type = lazy_base< lazy_function< OHP, T >, T >;

            template< class... Args >
            LAZY_IMPORTER_FORCEINLINE decltype( auto ) operator( )( Args&&... args ) const
            {
#ifndef LAZY_IMPORTER_CACHE_OPERATOR_PARENS
                return get( )( LAZY_IMPORTER_CPP_FORWARD( Args, args )... );
#else
                return this->cached( )( LAZY_IMPORTER_CPP_FORWARD( Args, args )... );
#endif
            }

            template< class F = T, class Enum = unsafe_module_enumerator >
            LAZY_IMPORTER_FORCEINLINE static F get( ) noexcept
            {
                // for backwards compatability.
                // Before 2.0 it was only possible to resolve forwarded exports when
                // this macro was enabled
#ifdef LAZY_IMPORTER_RESOLVE_FORWARDED_EXPORTS
                return forwarded< F, Enum >( );
#else

                Enum e;

                do {
#ifdef LAZY_IMPORTER_HARDENED_MODULE_CHECKS
                    if( !e.value->DllBase || !e.value->FullDllName.Length )
                        continue;
#endif

                    const exports_directory exports( e.value->DllBase );

                    if( exports ) {
                        auto export_index = exports.size( );
                        while( export_index-- )
                            if( hash( exports.name( export_index ), get_offset( OHP ) ) == get_hash( OHP ) )
                                return ( F )( exports.address( export_index ) );
                    }
                } while( e.next( ) );
                return { };
#endif
            }

            template< class F = T, class Enum = unsafe_module_enumerator >
            LAZY_IMPORTER_FORCEINLINE static F forwarded( ) noexcept
            {
                detail::win::UNICODE_STRING_T name;
                forwarded_hashes              hashes{ 0, get_hash( OHP ) };

                Enum e;
                do {
                    name = e.value->BaseDllName;
                    name.Length -= 8; // get rid of .dll extension

                    if( !hashes.module_hash || hash( name, get_offset( OHP ) ) == hashes.module_hash ) {
                        const exports_directory exports( e.value->DllBase );

                        if( exports ) {
                            auto export_index = exports.size( );
                            while( export_index-- )
                                if( hash( exports.name( export_index ), get_offset( OHP ) ) == hashes.function_hash ) {
                                    const auto addr = exports.address( export_index );

                                    if( exports.is_forwarded( addr ) ) {
                                        hashes = hash_forwarded( 
                                            reinterpret_cast< const char* >( addr ),
                                            get_offset( OHP ) );

                                        e.reset( );
                                        break;
                                    }
                                    return ( F )( addr );
                                }
                        }
                    }
                } while( e.next( ) );
                return { };
            }

            template< class F = T >
            LAZY_IMPORTER_FORCEINLINE static F forwarded_safe( ) noexcept
            {
                return forwarded< F, safe_module_enumerator >( );
            }

            template< class F = T, class Enum = unsafe_module_enumerator >
            LAZY_IMPORTER_FORCEINLINE static F forwarded_cached( ) noexcept
            {
                auto& value = base_type::_cache( );
                if( !value )
                    value = forwarded< void*, Enum >( );
                return ( F )( value );
            }

            template< class F = T >
            LAZY_IMPORTER_FORCEINLINE static F forwarded_safe_cached( ) noexcept
            {
                return forwarded_cached< F, safe_module_enumerator >( );
            }

            template< class F = T, bool IsSafe = false, class Module >
            LAZY_IMPORTER_FORCEINLINE static F in( Module m ) noexcept
            {
                if( IsSafe && !m )
                    return { };

                const exports_directory exports( ( const char* )( m ) );
                if( IsSafe && !exports )
                    return { };

                for( unsigned long i{ };; ++i ) {
                    if( IsSafe && i == exports.size( ) )
                        break;

                    if( hash( exports.name( i ), get_offset( OHP ) ) == get_hash( OHP ) )
                        return ( F )( exports.address( i ) );
                }
                return { };
            }

            template< class F = T, class Module >
            LAZY_IMPORTER_FORCEINLINE static F in_safe( Module m ) noexcept
            {
                return in< F, true >( m );
            }

            template< class F = T, bool IsSafe = false, class Module >
            LAZY_IMPORTER_FORCEINLINE static F in_cached( Module m ) noexcept
            {
                auto& value = base_type::_cache( );
                if( !value )
                    value = in< void*, IsSafe >( m );
                return ( F )( value );
            }

            template< class F = T, class Module >
            LAZY_IMPORTER_FORCEINLINE static F in_safe_cached( Module m ) noexcept
            {
                return in_cached< F, true >( m );
            }

            template< class F = T >
            LAZY_IMPORTER_FORCEINLINE static F nt( ) noexcept
            {
                return in< F >( ldr_data_entry( )->load_order_next( )->DllBase );
            }

            template< class F = T >
            LAZY_IMPORTER_FORCEINLINE static F nt_safe( ) noexcept
            {
                return in_safe< F >( ldr_data_entry( )->load_order_next( )->DllBase );
            }

            template< class F = T >
            LAZY_IMPORTER_FORCEINLINE static F nt_cached( ) noexcept
            {
                return in_cached< F >( ldr_data_entry( )->load_order_next( )->DllBase );
            }

            template< class F = T >
            LAZY_IMPORTER_FORCEINLINE static F nt_safe_cached( ) noexcept
            {
                return in_safe_cached< F >( ldr_data_entry( )->load_order_next( )->DllBase );
            }
        };

    }
} // namespace li::detail

#endif // include guard
#include "math.hpp"

#define M_PI_2 1.57079632679489661923
#define M_PI 3.14159265358979323846f
#define M_RADPI	57.295779513082f
#define M_PI_F ( ( float )( M_PI ) )
#define RAD2DEG( x ) ( ( float )( x ) * ( float )( 180.f / M_PI_F ) )
#define DEG2RAD( x ) ( ( float )( x ) * ( float )( M_PI_F / 180.f ) )
//#define min( a,b )            ( ( ( a ) < ( b ) ) ? ( a ) : ( b ) )
#define powww( a )	( a ) * ( a )
//#define atan2( a, b ) ( ( float )FC_NTDLL( atan2, ( double )( a ), ( double )( b ) ) )
static volatile const double Tiny = 0x1p-1022;
static volatile const double Infinity = INFINITY;
unsigned short lfsr = 0xACE1u;
unsigned int bit = 0;

// create global definition for math class.
c_math g_math;

std::string c_math::remove_trailing_zeros( float number ) {
	std::stringstream stream;
	stream << std::fixed << std::setprecision( 2 ) << number;
	std::string float_string = stream.str( );

	while( float_string.find( '.' ) != std::string::npos 
		&& float_string.back( ) == '0' 
		|| float_string.back( ) == '.' )
		float_string.pop_back( );

	return float_string;
}

vec2_t c_math::calculate_angle( const vec3_t& src, const vec3_t& dst ) {
	vec3_t dir = src - dst;
	float length = dir.length( );
	return vec2_t{ RAD2DEG( asin( dir.y / length ) ), RAD2DEG( -atan2( dir.x, -dir.z ) ) };
}

vec3_t c_math::quatmult( const vec3_t* point, vec4_t* quat )
{
	float num = quat->x * 2.f;
	float num2 = quat->y * 2.f;
	float num3 = quat->z * 2.f;
	float num4 = quat->x * num;
	float num5 = quat->y * num2;
	float num6 = quat->z * num3;
	float num7 = quat->x * num2;
	float num8 = quat->x * num3;
	float num9 = quat->y * num3;
	float num10 = quat->w * num;
	float num11 = quat->w * num2;
	float num12 = quat->w * num3;
	vec3_t result{ };
	result.x = ( 1.f - ( num5 + num6 ) ) * point->x + ( num7 - num12 ) * point->y + ( num8 + num11 ) * point->z;
	result.y = ( num7 + num12 ) * point->x + ( 1.f - ( num4 + num6 ) ) * point->y + ( num9 - num10 ) * point->z;
	result.z = ( num8 - num11 ) * point->x + ( num9 + num10 ) * point->y + ( 1.f - ( num4 + num5 ) ) * point->z;
	return result;
}

vec2_t c_math::unity_calculate_angle( const vec3_t& src, const vec3_t& dst )
{
	vec3_t dir = src - dst;

	const auto sqrtss = [ ]( float in )
	{ // thx can
		__m128 reg = _mm_load_ss( &in );
		return _mm_mul_ss( reg, _mm_rsqrt_ss( reg ) ).m128_f32[ 0 ];
	};

	float hyp = sqrtss( dir.x * dir.x + dir.y * dir.y + dir.z * dir.z );
	float nigga = roundf( dir.y );

	if( isnan( hyp ) )
		hyp = sqrtss( dir.x * dir.x + nigga * nigga );

	double ax = asin( dir.y / hyp );
	double ay = -atan2( dir.x, -dir.z );

	double x = RAD2DEG( ax );
	double y = RAD2DEG( ay );

	return vec2_t( static_cast< float >( x ), static_cast< float >( y ) );
}

float c_math::normalize_angle( float angle ) {
	while( angle > 360.0f ) {
		angle -= 360.0f;
	}
	while( angle < 0.0f ) {
		angle += 360.0f;
	}
	return angle;
}

vec3_t c_math::normalize_angles( vec3_t angles ) {
	angles.x = normalize_angle( angles.x );
	angles.y = normalize_angle( angles.y );
	angles.z = normalize_angle( angles.z );
	return angles;
}

void c_math::normalize( vec2_t& angle ) {
	if( angle.x < -89 ) 
		angle.x = -89;
	else if( angle.x > 89 ) 
		angle.x = 89;

	if( angle.y < -360 )
		angle.y += 360;
	else if( angle.y > 360 ) 
		angle.y -= 360;
}

float c_math::to_rad( float val ) {
	return val * ( PI / 180.f );
}

vec3_t c_math::cross_vector( vec3_t first_vec, vec3_t second_vec )
{
	vec3_t returnme = vec3_t( );
	returnme.x = first_vec.y * second_vec.z - first_vec.z * second_vec.y;
	returnme.y = first_vec.z * second_vec.x - first_vec.x * second_vec.z; //first_vec.x * second_vec.z - first_vec.z * second_vec.x;
	returnme.z = first_vec.x * second_vec.y - first_vec.y * second_vec.x;
	return returnme;
}

vec3_t c_math::to_euler_angles( vec4_t q1 ) {
	float num = q1.w * q1.w;
	float num2 = q1.x * q1.x;
	float num3 = q1.y * q1.y;
	float num4 = q1.z * q1.z;
	float num5 = num2 + num3 + num4 + num;
	float num6 = q1.x * q1.w - q1.y * q1.z;
	vec3_t vector = vec3_t( );
	if( num6 > 0.4995f * num5 ) {
		vector.y = 2.0f * std::atan2f( q1.y, q1.x );
		vector.x = 1.57079637f;
		vector.z = 0.0f;
		return normalize_angles( vector * 57.2958f );
	}
	if( num6 < -0.4995f * num5 ) {
		vector.y = -2.0f * std::atan2f( q1.y, q1.x );
		vector.x = -1.57079637f;
		vector.z = 0.0f;
		return normalize_angles( vector * 57.2958f );
	}
	vec4_t quaternion = vec4_t( q1.w, q1.z, q1.x, q1.y );
	vector.y = std::atan2f( 2.0f * quaternion.x * quaternion.w + 2.0f * quaternion.y * quaternion.z, 1.0f - 2.0f * ( quaternion.z * quaternion.z + quaternion.w * quaternion.w ) );
	vector.x = std::asin( 2.0f * ( quaternion.x * quaternion.z - quaternion.w * quaternion.y ) );
	vector.z = std::atan2f( 2.0f * quaternion.x * quaternion.y + 2.0f * quaternion.z * quaternion.w, 1.0f - 2.0f * ( quaternion.y * quaternion.y + quaternion.z * quaternion.z ) );
	return normalize_angles( vector * 57.2958f );
}

vec2_t c_math::cos_tan_horizontal( float angle, float range, float x, float y, int length ) {
	float our_angle = ( angle + 45.f );

	float yaw = our_angle * ( M_PI / 180.0 );

	float view_cosinus = cos( yaw );
	float view_sinus = sin( yaw );

	float x2 = range * ( -view_cosinus ) + range * view_sinus;
	float y2 = range * ( -view_cosinus ) - range * view_sinus;

	int screen_x = x + static_cast< int >( x2 / range * length );
	int screen_y = y + static_cast< int >( y2 / range * length );

	return vec2_t( screen_x, screen_y );
}
#pragma once

class vec2_t {
public:
	float x, y;

	inline vec2_t( ) {
		x = y = 0.0f;
	}

	inline vec2_t operator/( float v ) const {
		return vec2_t( x / v, y / v );
	}
	inline vec2_t( float X, float Y ) {
		x = X; y = Y;
	}

	inline vec2_t operator-( const vec2_t& v ) const {
		return vec2_t( x - v.x, y - v.y );
	}

	inline vec2_t operator+( const vec2_t& v ) const {
		return vec2_t( x + v.x, y + v.y );
	}
	
	inline vec2_t& operator*=( const vec2_t& v ) {
		x *= v.x; y *= v.y; return *this;
	}

	inline vec2_t& operator+=( const vec2_t& v ) {
		x += v.x; y += v.y; return *this;
	}

	inline vec2_t& operator-=( const vec2_t& v ) {
		x -= v.x; y -= v.y; return *this;
	}

	inline vec2_t operator*( const float& v ) const {
		return vec2_t( x * v, y * v );
	}

	inline vec2_t& operator*=( float v ) {
		x *= v; 
		y *= v; 
		return *this;
	}

	inline bool is_zero( ) const {
		return ( x > -0.1f && x < 0.1f && y > -0.1f && y < 0.1f );
	}

	inline vec2_t& operator/=( float fl )
	{
		x /= fl;
		y /= fl;
		return *this;
	}

	inline bool operator==( const vec2_t& v ) const {
		if( this->x == v.x && this->y == v.y )
			return true;
		else
			return false;
	}

	inline vec2_t normalize( )
	{
		if( x > 89.f )
			x -= 180.f;
		else if( x < -89.f )
			x += 180.f;

		while( y < -180.0f )
			y += 360.0f;

		while( y > 180.0f )
			y -= 360.0f;

		return *this;
	}

	inline bool bigger( float x, float y, bool check_equals = false ) const
	{
		return check_equals ? ( this->x >= x || this->y >= y )
			: ( this->x > x || this->y > y );
	}

	inline float length( ) const
	{
		return std::sqrt( 
			( x * x )
			+
			( y * y )
		 );
	}

	vec2_t normalized( ) const
	{
		return vec2_t( x / length( ), y / length( ) );
	}

	float distance( vec2_t input ) const
	{
		return ( *this - input ).length( );
	}
};

#pragma once

class vec3_t
{
public:
	float x, y, z;

	inline vec3_t( ) {
		x = y = z = 0.0f;
	}

	inline vec3_t( float X, float Y, float Z ) {
		x = X; y = Y; z = Z;
	}

	inline float operator[ ]( int i ) const {
		return ( ( float* )this )[ i ];
	}

	inline vec3_t& operator-=( float v ) {
		x -= v; y -= v; z -= v; return *this;
	}

	inline vec3_t operator-( const vec2_t& v ) const {
		return vec3_t( x - v.x, y - v.y, z );
	}

	inline vec3_t operator*( float v ) const {
		return vec3_t( x * v, y * v, z * v );
	}

	inline vec3_t operator/( float v ) const
	{
		return vec3_t( x / v, y / v, z / v );
	}

	inline vec3_t& operator+=( const vec3_t& v ) {
		x += v.x; y += v.y; z += v.z; return *this;
	}

	inline vec3_t& operator+=( const float& v ) {
		x += v; y += v; z += v; return *this;
	}

	inline vec3_t& operator*=( const float& v ) {
		x *= v; y *= v; z *= v; return *this;
	}

	inline vec3_t& operator*=( const vec3_t& v ) {
		x *= v.x; y *= v.y; z *= v.z; return *this;
	}

	inline vec3_t& operator-=( const vec3_t& v ) {
		x -= v.x; y -= v.y; z -= v.z; return *this;
	}

	inline vec3_t operator-( const vec3_t& v ) const {
		return vec3_t( x - v.x, y - v.y, z - v.z );
	}

	inline vec3_t operator+( const vec3_t& v ) const {
		return vec3_t( x + v.x, y + v.y, z + v.z );
	}

	inline float length( )
	{
		auto number = ( x * x + y * y + z * z );
		long        i;
		float       x2, y;
		const float threehalfs = 1.5F;

		x2 = number * 0.5F;
		y = number;
		i = *( long* )&y; // floating point bit level hacking [ sic ]
		i = 0x5f3759df - ( i >> 1 ); // Newton's approximation
		y = *( float* )&i;
		y = y * ( threehalfs - ( x2 * y * y ) ); // 1st iteration
		y = y * ( threehalfs - ( x2 * y * y ) ); // 2nd iteration

		return 1 / y;
	}

	inline vec3_t normalize( )
	{
		float mag = length( );
		if( mag > 0.00001f )
		{
			x = x / mag;
			y = y / mag;
			z = z / mag;
		}
		else
		{
			x = 0;
			y = 0;
			z = 0;
		}
		return *this;
	}

	inline bool is_zero( )
	{
		return this->x == 0 && this->y == 0 && this->z == 0;
	}

	inline float length2d( vec3_t apple )
	{
		return sqrtf( 
			( apple.x * apple.x )
			+
			( apple.z * apple.z ) );
	}

	inline bool operator==( const vec3_t& v ) const {
		return this->x == v.x && this->y == v.y && this->z == v.z;
	}

	inline bool operator==( const float v ) const {
		return this->x == v && this->y == v && this->z == v;
	}

	inline bool operator!=( const vec3_t& v ) const {
		return this->x == v.x && this->y == v.y && this->z == v.z;
	}

	inline bool operator!=( const float v ) const {
		return this->x == v && this->y == v && this->z == v;
	}

	float dot_product( vec3_t input ) const {
		return ( x * input.x ) + ( y * input.y ) + ( z * input.z );
	}

	float unity_length( )
	{
		return sqrt( ( x * x + y * y + z * z ) );
	}

	vec3_t cross( vec3_t rhs )
	{
		return vec3_t ( y * rhs.z - z * rhs.y, z * rhs.x - x * rhs.z, x * rhs.y - y * rhs.x );
	}

	void clear( )
	{
		this->x = this->y = this->z = 0;
	}

	vec3_t unity_normalize ( )
	{
		float num = unity_length( );
		if( num > 1E-05f )
		{
			x /= num;
			y /= num;
			z /= num;
		}
		else
		{
			x = 0;
			y = 0;
			z = 0;
		}

		return vec3_t( x, y, z );
	}

	float dot( const vec3_t& vector )
	{
		return x * vector.x + y * vector.y + z * vector.z;
	}

	float distance ( vec3_t input ) const
	{
		return ( *this - input ).length ( );
	}

	vec3_t normalized( ) {
		float len = length( );
		return vec3_t( x / len, y / len, z / len );
	}
};

#pragma once

#include "math.hpp"

class vec4_t {
public:
	float x, y, z, w;

public:
	inline vec4_t( ) {
		x = y = z = w = 0.0f;
	}

	inline vec4_t( float X, float Y, float Z, float W = 1.f ) {
		x = X; y = Y; z = Z; w = W;
	}

	inline float operator[ ]( int i ) const {
		return ( ( float* )this )[ i ];
	}
	
	inline vec4_t& operator-=( float v ) {
		x -= v; y -= v; z -= v, w -= v; return *this;
	}

	inline vec4_t operator*( float v ) const {
		return vec4_t( x * v, y * v, z * v, w * v );
	}

	inline vec4_t operator/( float v ) const
	{
		return vec4_t( x / v, y / v, z / v, w / v );
	}

	inline vec4_t& operator+=( const vec4_t& v ) {
		x += v.x; y += v.y; z += v.z; w += v.w; return *this;
	}

	inline vec4_t& operator+=( const float& v ) {
		x += v; y += v; z += v; w += v; return *this;
	}

	inline vec4_t& operator-=( const vec4_t& v ) {
		x -= v.x; y -= v.y; z -= v.z, w -= v.w; return *this;
	}

	inline vec4_t operator-( const vec4_t& v ) const {
		return vec4_t( x - v.x, y - v.y, z - v.z, w - v.w );
	}

	inline vec4_t operator+( const vec4_t& v ) const {
		return vec4_t( x + v.x, y + v.y, z + v.z, w + v.w );
	}

	inline bool is_zero( ) {
		return ( this->x == 0 && this->y == 0 && this->w == 0 && this->z == 0 );
	}

	inline bool contains( vec2_t point )
	{
		return point.x >= x && point.x < ( x + z ) && point.y >= y && point.y < ( y + w );
	}

	static inline float this_sqrt( float number )
	{
		long        i;
		float       x2, y;
		const float threehalfs = 1.5F;

		x2 = number * 0.5F;
		y = number;
		i = *( long* )&y; // floating point bit level hacking [ sic ]
		i = 0x5f3759df - ( i >> 1 ); // Newton's approximation
		y = *( float* )&i;
		y = y * ( threehalfs - ( x2 * y * y ) ); // 1st iteration
		y = y * ( threehalfs - ( x2 * y * y ) ); // 2nd iteration

		return 1 / y;
	}

	static vec4_t quat_look_rot( vec3_t forward, vec3_t up )
	{
		vec3_t vector = forward.unity_normalize( );
		vec3_t vector2 = up.cross( vector ).unity_normalize( );
		vec3_t vector3 = vector.cross( vector2 );
		auto m00 = vector2.x;
		auto m01 = vector2.y;
		auto m02 = vector2.z;
		auto m10 = vector3.x;
		auto m11 = vector3.y;
		auto m12 = vector3.z;
		auto m20 = vector.x;
		auto m21 = vector.y;
		auto m22 = vector.z;

		float num8 = ( m00 + m11 ) + m22;
		auto quaternion = vec4_t ( );
		if( num8 > 0.f )
		{
			auto num = this_sqrt( num8 + 1.f );
			quaternion.w = num * 0.5f;
			num = 0.5f / num;
			quaternion.x = ( m12 - m21 ) * num;
			quaternion.y = ( m20 - m02 ) * num;
			quaternion.z = ( m01 - m10 ) * num;
			return quaternion;
		}
		if( ( m00 >= m11 ) 
			&& ( m00 >= m22 ) )
		{
			auto num7 = this_sqrt( ( ( 1.f + m00 ) - m11 ) - m22 );
			auto num4 = 0.5f / num7;
			quaternion.x = 0.5f * num7;
			quaternion.y = ( m01 + m10 ) * num4;
			quaternion.z = ( m02 + m20 ) * num4;
			quaternion.w = ( m12 - m21 ) * num4;
			return quaternion;
		}
		if( m11 > m22 )
		{
			auto num6 = this_sqrt( ( ( 1.f + m11 ) - m00 ) - m22 );
			auto num3 = 0.5f / num6;
			quaternion.x = ( m10 + m01 ) * num3;
			quaternion.y = 0.5f * num6;
			quaternion.z = ( m21 + m12 ) * num3;
			quaternion.w = ( m20 - m02 ) * num3;
			return quaternion;
		}
		auto num5 = this_sqrt ( ( ( 1.f + m22 ) - m00 ) - m11 );
		auto num2 = 0.5f / num5;
		quaternion.x = ( m20 + m02 ) * num2;
		quaternion.y = ( m21 + m12 ) * num2;
		quaternion.z = 0.5f * num5;
		quaternion.w = ( m01 - m10 ) * num2;
		return quaternion;
	}

	vec4_t to_unity_color( )
	{
		return vec4_t( x / 255.f, y / 255.f, z / 255.f, w / 255.f );
	}
};

#pragma once

class color_t {
public:
	float r{ }, g{ }, b{ }, a{ };

public:
	inline color_t( ) {
		r = g = b = a = 0.0f;
	}

	inline color_t( float R, float G, float B, float A = 255.f ) {
		r = ( R / 255.f );
		g = ( G / 255.f );
		b = ( B / 255.f );
		a = ( A / 255.f );
	}

	inline float operator[ ]( int i ) const {
		return ( ( float* )this )[ i ];
	}

	inline bool operator==( const color_t& to ) const {
		return ( to.r == this->r && to.g == this->g && to.b == this->b && to.a == this->a );
	}

	inline color_t to_normal( )
	{
		return color_t( r * 255.f, g * 255.f, b * 255.f, a * 255.f );
	}

	inline color_t to_unity( )
	{
		return color_t( r / 255.f, g / 255.f, b / 255.f, a / 255.f );
	}

	inline color_t multiply( const color_t& other, float strength ) {
		if( *this == other )
			return *this;

		return color_t(
			std::lerp( r, other.r, strength ),
			std::lerp( g, other.g, strength ),
			std::lerp( b, other.b, strength )
		 );
	}

	inline color_t alpha( float alpha, bool normal = false ) {
		float new_alpha = std::clamp( alpha, 0.f, 255.f );

		return normal ? color_t( r * 255.f, g * 255.f, b * 255.f, new_alpha ) : color_t( r, g, b, new_alpha );
	}

	inline void rainbow( float speed = 1.f ) {
		static int cases = 0;
		switch( cases )
		{
			case 0: {
				this->r -= speed;
				if( this->r <= 0 )
					cases += 1; 
				break;
			}
			case 1: {
				this->g += speed; this->b -= speed;
				if( this->g >= 255 )
					cases += 1;
				break; }
			case 2: {
				this->r += speed;
				if( this->r >= 255 ) 
					cases += 1; 
				break;
			}
			case 3: { 
				this->b += speed; this->g -= speed;
				if( this->b >= 255 ) 
					cases = 0;
				break; }
			default: {
				this->r = 255.00f; this->g = 255.00f; this->b = 0.00f;
				break; 
			}
		}
	}
};
}
	}
}
    <ClInclude Include="core\utilities\memory.hpp" />
    <ClInclude Include="core\utilities\returnspoofer.hpp" />
    <ClInclude Include="core\utilities\xor.hpp" />
  </ItemGroup>
  <ItemGroup>
    <MASM Include="utils\returnspoofer.asm">
      <ExcludedFromBuild Condition="'$(Configuration)|$(Platform)'=='Release|x64'">true</ExcludedFromBuild>
    </MASM>
  </ItemGroup>
  <Import Project="$(VCTargetsPath)\Microsoft.Cpp.targets" />
  <ImportGroup Label="ExtensionTargets" />
</Project>
