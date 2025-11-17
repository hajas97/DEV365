# DEV365

Ez a tároló egy egyszerű példaprojektet tartalmaz.

Használat:

- C# fájl futtatása `dotnet` SDK-val:

```bash
dotnet new console -o HelloApp --no-restore
# másold be a HelloWorld.cs tartalmát a HelloApp/Program.cs fájlba, vagy használd a saját fájlodat
dotnet run --project HelloApp
```

- Vagy `csc`-vel (ha telepítve van a .NET SDK részeként):

```bash
csc HelloWorld.cs
./HelloWorld
```

Ez a projekt tartalmaz egy `HelloWorld.cs` fájlt, amely kiírja, hogy "Hello, World!".