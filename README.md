# Ontwikkelomgeving Setup Gids voor MacOS

Deze gids helpt studenten bij het opzetten van hun ontwikkelomgeving op MacOS om te werken met C# en .NET. Er zijn drie opties beschikbaar: Visual Studio Code (primair), Visual Studio for Mac en Visual Studio in een Windows VM via Parallels.

## Inhoudsopgave

- [Visual Studio Code Setup](#visual-studio-code-setup)
- [Visual Studio for Mac Setup](#visual-studio-for-mac-setup)
- [Visual Studio in een Windows VM via Parallels Setup](#visual-studio-in-een-windows-vm-via-parallels-setup)

## Visual Studio Code Setup

1. Download en installeer [Visual Studio Code](https://code.visualstudio.com/download).
2. Open Visual Studio Code en ga naar de Extensions view (View -> Extensions) en zoek naar 'C#'.
3. Installeer de [C# extensie](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) voor Visual Studio Code.
4. Download en installeer [.NET SDK](https://dotnet.microsoft.com/download).
5. Open een terminal in Visual Studio Code (View -> Terminal) en voer `dotnet --version` uit om te controleren of de installatie succesvol was.

## Visual Studio for Mac Setup

1. Download en installeer [Visual Studio for Mac](https://visualstudio.microsoft.com/vs/mac/).
2. Tijdens de installatie, zorg ervoor dat je de .NET Core workload selecteert.
3. Na de installatie, open Visual Studio en ga naar Preferences -> Projects -> SDK Locations -> .NET Core en controleer of de geïnstalleerde versie van .NET Core wordt weergegeven.

## Visual Studio in een Windows VM via Parallels Setup

1. Download en installeer [Parallels](https://www.parallels.com/products/desktop/).
2. Maak een nieuwe Windows VM.
3. Download en installeer [Visual Studio](https://visualstudio.microsoft.com/downloads/) in de VM.
4. Tijdens de installatie, zorg ervoor dat je de .NET Core workload selecteert.
5. Na de installatie, open Visual Studio en ga naar Tools -> Options -> Projects and Solutions -> .NET Core en controleer of de geïnstalleerde versie van .NET Core wordt weergegeven.

## Verdere Hulp

Als je problemen ondervindt bij het opzetten van je ontwikkelomgeving, neem dan contact op met je docent of vraag hulp op het forum.