# JDK_15_Binary_Mirror

This is a JDK 15 binary mirrior 

## Set up 

```{bash}
git clone https://github.com/DMinghao/JDK_15_Binary_Mirror.git
powershell.exe -nologo -noprofile -command "& { Add-Type -A 'System.IO.Compression.FileSystem'; [IO.Compression.ZipFile]::ExtractToDirectory('jdk-15\lib\modules.zip', 'jdk-15\lib'); }" 
```
