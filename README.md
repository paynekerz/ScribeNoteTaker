# What is this?

![notebook](./s-l1200.jpg)

So, I wanted to startcreating form apps with C# and came up with this temporary app. The funny thing is, this first try of mine is a bit of a dud – it doesn't hold onto any data once you close it (hence the "_temporary_" note-taking app title). But you know what? It might still have its moments of usefulness, even in its quirky state. It's like that funky tool you're not quite sure how to use, but you keep it around because you never know, right? Just a little experiment for now, but who knows, it might turn into something cooler down the road.

# Usage

1. Download the latest release from the releases section.
2. Run the executable.
3. Type in your note.
4. Click the save button.
5. Close the app.
6. Reopen the app.
7. Woah your previous note just appeared again

# Dependencies

- dotNET Framework version: at least v4.7.2
- Winforms desktop development SDK: included by default in VS installation, or manually added from the installer if needed
- Newtonsoft Json package version: v13.0.3 for storage

- Note: I've decided to include the packages folder with the repo, so the NuGet dependencies should come with the repo. This means you shouldn't need a `dotnet restore` to get them back.
