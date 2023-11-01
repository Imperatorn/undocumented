Undocumented translated function declarations from C to D

Using anything in this repo comes with absolutely no warranty. \
Your home might burn to the ground and destabilize society if you use this.

Example usage for dnsapi:

```cmd
dub add undocumented
```

```d
import std.stdio;
import dnsapi;

void main()
{
	writeln("Flushed dns cache: ", DnsFlushResolverCache() ? "Success" : "Failed");
}
```
