# WhatsAppLink
[NuGet package](https://www.nuget.org/packages/WhatsAppLink/)

Make custom link to Whatsapp!

### Example
```
var waComposer = new WaComposer();
waComposer.WriteText("My Order",1,1);
/////////////////// Observation: this 1,1 is break line. 1 before and 1 after

waComposer.WriteText("Item One");

var textResult = waComposer.GetText();

var whatsAppLink = WaSender.GetLink("PHONE_NUMBER_HERE",textResult);

```
