# Storage.Put method (StorageContext, byte[], string)

Insert the operation, in the form of key-value to the persistent storage area to insert data.

Namespace: [AntShares.SmartContract.Framework.Services.AntShares](../../AntShares.md)

Assembly: AntShares.SmartContract.Framework

## syntax

```c#
public extern void Put (AntShares.SmartContract.Framework.Services.AntShares.StorageContext context, byte[] key, string value)
```

parameter:
Context: storage context, [StorageContext](../StorageContex.md) type.

Key: key, byte array.

Value: value, string.

Return value: void.

## example

```c#
public class Contract1: FunctionCode
{
     public static void Main ()
     {
         byte[] key = new byte[] {0};
         String value = "value";
         Storage.Put (Storage.CurrentContext, key, value);
     }
}
```



[Return to superior](../Storage.md)
