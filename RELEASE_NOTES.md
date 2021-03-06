#### 2.0.0 - May 16 2016
* Major update which changes the way code behind is accessed and generated.  
* This provides more efficiently generated types, as well as direct support for code behind via inheritance. 
* Simplifies accessing child controls, and eliminates the view controllers.  
* All blend behaviors have moved to FsXaml.Wpf.Blend, which is now a separate NuGet package

#### 2.1.0 - May 19 2016
* Change in code generation to more closely match C# generation
* Generated types now implement System.Windows.Markup.IComponentConnector
* Generated types include virtual OnInitialize method to simplify wiring up code behind
* Resolved issues with ElementName bindings and logical tree disconnects

#### 2.2.0 - Dec 14 2016
* Improved error messages on parse failures
* Updated Blend Libs to new Expression SDK for .NET 4+
* Added ability to filter converted options in EventToCommand

#### 3.0.0 - Feb 1 2017
* Rewrote XAML parsing to be more in line with runtime loading
* Added initial support for events
* Removed OnInitialized support, as Loaded event can be triggered in XAML instead
* Fixed issue with EventToMailbox

#### 3.1.0 - Feb 2 2017
* Changed event handlers to be abstract, providing better compile time experience
* Improved error messages when XAML is poorly formed
* Improved generated XML Doc comments

#### 3.1.1 - Feb 2 2017
* Allowed Name to be used as well as x:Name for finding members
* Changed event handlers to be abstract, providing better compile time experience
* Improved error messages when XAML is poorly formed
* Improved generated XML Doc comments

#### 3.1.2 - Feb 3 2017
* Reworked accessors to work around exceptions due to invalid programs in some types
* Allowed Name to be used as well as x:Name for finding members
* Searches embedded resources as well as resources for xaml

#### 3.1.3 - Feb 17 2017
* Corrected bug relating to named local user controls
* Signed assemblies with strong name

#### 3.1.4 - Feb 24 2017
* Corrected bug with assembly version references in Blend packages

#### 3.1.5 - Feb 24 2017
* Corrected bug with assembly version references in Blend packages

#### 3.1.6 - Mar 8 2017
* Added ability to use FsXaml from within FSI



