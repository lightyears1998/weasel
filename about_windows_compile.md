### 编译测试环境:
    windows10 Pro 19043.844
    Visual Studio 2017 Developer Command Prompt v15.9.34 (组件配置如vsconfig所示)
    boost_1_75_0-msvc-14.1-64 （offical release，该版本默认无bjam.exe，须手动复制同目录下b2.exe为该文件）
    git
    python2.7
    cmake-3.20.0

##### vsconfig:
```
{
	"version": "1.0",
	"components": [
		"Microsoft.VisualStudio.Workload.NativeDesktop",
		"microsoft.visualstudio.component.debugger.justintime",
		"microsoft.visualstudio.component.vc.diagnostictools",
		"microsoft.visualstudio.component.vc.cmake.project",
		"microsoft.visualstudio.component.vc.testadapterforboosttest",
		"microsoft.visualstudio.component.vc.testadapterforgoogletest",
		"microsoft.component.vc.runtime.ucrtsdk",
		"microsoft.visualstudio.component.winxp",
		"microsoft.visualstudio.component.vc.atlmfc",
		"microsoft.visualstudio.component.vc.cli.support",
		"component.cpython2.x86"
	]
}
```
or
```
{
  "version": "1.0",
  "components": [
    "Microsoft.VisualStudio.Component.CoreEditor",
    "Microsoft.VisualStudio.Workload.CoreEditor",
    "Microsoft.VisualStudio.Component.Roslyn.Compiler",
    "Microsoft.Component.MSBuild",
    "Microsoft.VisualStudio.Component.Static.Analysis.Tools",
    "Microsoft.Net.Component.4.6.1.SDK",
    "Microsoft.Net.Component.4.6.1.TargetingPack",
    "Microsoft.VisualStudio.Component.TextTemplating",
    "Microsoft.VisualStudio.Component.Debugger.JustInTime",
    "Microsoft.VisualStudio.Component.NuGet",
    "Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions",
    "Microsoft.VisualStudio.Component.VC.CoreIde",
    "Microsoft.VisualStudio.Component.VC.Redist.14.Latest",
    "Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core",
    "Microsoft.VisualStudio.Component.VC.Tools.x86.x64",
    "Microsoft.VisualStudio.Component.Graphics.Win81",
    "Microsoft.VisualStudio.Component.Graphics.Tools",
    "Microsoft.VisualStudio.Component.VC.DiagnosticTools",
    "Microsoft.VisualStudio.Component.VC.ATL",
    "Microsoft.VisualStudio.Component.VC.TestAdapterForBoostTest",
    "Microsoft.VisualStudio.Component.VC.TestAdapterForGoogleTest",
    "Microsoft.Component.VC.Runtime.UCRTSDK",
    "Microsoft.VisualStudio.Component.WinXP",
    "Microsoft.VisualStudio.Component.VC.ATLMFC",
    "Microsoft.VisualStudio.Component.VC.CLI.Support",
    "Microsoft.VisualStudio.Workload.NativeDesktop",
    "Component.CPython2.x86",
    "Microsoft.VisualStudio.Component.Git"
  ]
}
```
