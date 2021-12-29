# StealthInjector
Basic DLL Injector using CreateRemoteThread and WPM

Writes a DLL name into the memory of process p, then creates a remote thread in p calling LoadLibraryA on our DLL name.

Many other methods will work, with some being 'better' than others.

Other examples:
Manual mapping memory
Writing PE image into address space of a host process (reflective DLL injection)
