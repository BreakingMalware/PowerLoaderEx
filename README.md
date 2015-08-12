# PowerLoaderEx
* Advanced Code Injection Technique for x32 / x64
* More Info: http://www.slideshare.net/enSilo/injection-on-steroids-codeless-code-injection-and-0day-techniques?utm_source=slideshow&utm_medium=ssemail&utm_campaign=post_upload_view_cta

# Original PowerLoader
* Known since ~2013
* Loader used in many different dropper families (Gapz / Redyms / Carberp / Vabushky ...)
* First injection technique via Return Oriented Programming technique (ROP).
* “explorer.exe” is injected using Shell_TrayWnd / NtQueueApcThread (32bit / 64bit)

# PowerLoaderEx
* Injection via shared desktop heap
* Remove dependency in Explorer.exe shared sections (more generic)
* Injection without reading memory from the target process
* 32 and 64-bit versions (same technique)

#Tested Environments
* Windows 7 32 and 64 bit.

# Authors
* BreakingMalware.com
