Clean turtle-wow data from files to create generic patch that works with any wow 1.12.1 client.

![Screenshot 2024-07-27 175350](https://github.com/user-attachments/assets/d1df41c8-16d3-4aa3-8025-ddee14cd8317)


## Installation

### [Patch-Y.MPQ download link](https://github.com/MetalEgl/Autologin-for-WoW-1.12.1-Vanilla-Client/releases/download/v1.0/Patch-Y.mpq)

Download the `Patch-Y.MPQ` and place the file inside `\Data` folder of your client.

## Advanced usage

Account information is saved under `accountName` in your `\WTF\Config.wtf` file, unlike normal behavior, where it contains only the account name. When using this patch it will contain data in following format:

```
<name> <password> <character-index?>;
```

Each entry ends with a `;` symbol. To disable character auto login, omit third value and the space.
