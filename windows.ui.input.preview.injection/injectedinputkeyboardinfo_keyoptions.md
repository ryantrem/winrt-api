---
-api-id: P:Windows.UI.Input.Preview.Injection.InjectedInputKeyboardInfo.KeyOptions
-api-type: winrt property
---

<!-- Property syntax
public Windows.UI.Input.Preview.Injection.InjectedInputKeyOptions KeyOptions { get;  set; }
-->

# Windows.UI.Input.Preview.Injection.InjectedInputKeyboardInfo.KeyOptions

## -description
Gets or sets the various options, or modifiers, used to simulate input from physical or virtual keyboards.

## -property-value
The options, or modifiers, for the keyboard input.

## -remarks
Using input injection requires the following be added to the Package.appxmanifest:

- To `<Package>`
    - `xmlns:rescap="http://schemas.microsoft.com/appx/manifest/foundation/windows10/restrictedcapabilities"`
    - `IgnorableNamespaces="rescap"`
- To `<Capabilities>`
    - `<rescap:Capability Name="inputInjectionBrokered" />`


## -examples

## -see-also
