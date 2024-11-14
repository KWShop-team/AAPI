# How to inject:

```csharp
using aapi;

try
{
  API.Inject();
}
catch (Exception ex) {
 MessageBox.Show("Error while injecting AAPI: "+e, "Error!", MessageBoxButtons.OK, MessageBoxIcon.Error);
}

```

# How to execute:

```csharp
using aapi;

  API.ExecuteScript(richTextBox1.Text); // Make sure to have richTextBox1 In UI!
```

> [!WARNING]
>
> Exploiting in Roblox results an ban. Use at you'r own risk!
