---
-api-id: T:Windows.UI.Input.Preview.Injection.InjectedInputPenInfo
-api-type: winrt class
---

<!-- Class syntax.
public class InjectedInputPenInfo : Windows.UI.Input.Preview.Injection.IInjectedInputPenInfo
-->

# Windows.UI.Input.Preview.Injection.InjectedInputPenInfo

## -description
Represents programmatically generated pen input.

## -remarks
Using input injection requires the following be added to the Package.appxmanifest:

- To `<Package>`
    - `xmlns:rescap="http://schemas.microsoft.com/appx/manifest/foundation/windows10/restrictedcapabilities"`
    - `IgnorableNamespaces="rescap"`
- To `<Capabilities>`
    - `<rescap:Capability Name="inputInjectionBrokered" />`


## -examples

## -see-also
[Windows.UI.Input.Preview.Injection classes](windows_ui_input_preview_injection_classes.md)