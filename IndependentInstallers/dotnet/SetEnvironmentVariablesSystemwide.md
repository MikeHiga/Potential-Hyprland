# Set environment variables system-wide

Set the following two environment variables in your shell profile:

* DOTNET_ROOT

This variable is set to the folder .NET was installed to, such as $HOME/.dotnet:

```SH
export DOTNET_ROOT=$HOME/.dotnet
```

* PATH

This variable should include both the DOTNET_ROOT folder and the DOTNET_ROOT/tools folder:

```SH
export PATH=$PATH:$DOTNET_ROOT:$DOTNET_ROOT/tools
```
