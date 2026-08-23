# 👨‍💻 anordinaryusername

```csharp
using System;
using System.Linq;

namespace GitHubProfile
{
    public sealed class DeveloperProfile
    {
        public string   Username    { get; } = "anordinaryusername";
        public string   Platform    { get; } = "GitHub";
        public string   OS          { get; } = "Arch Linux x86_64";
        public string   Shell       { get; } = "zsh 5.8";
        public string   Pronouns    { get; } = "He/Him";
        public string   Location    { get; } = "Artesia, CA";
        public string[] Frameworks  { get; } = { "React" };
        public string[] Languages   { get; } = { "JavaScript", "TypeScript", "HTML", "CSS" };
        public string[] Learning    { get; } = { "Node.js", "Express", "PostgreSQL", "Three.js", "CPP" };
        public string[] Hobbies     { get; } = { "Gardening", "Cooking", "Gaming" };
        public int      Commits     { get; } = 968;
        public int      Stars       { get; } = 14;
        public string   Discord     { get; } = "RandomPotato#1377";
        public string[] DailyTools  { get; } = { ".php", ".js", ".html", ".css", ".svg", ".psd", ".ai" };

        public void PrintProfile()
        {
            var lines = new[]
            {
                $"Username   : {Username}",
                $"Platform   : {Platform}",
                $"OS         : {OS}",
                $"Shell      : {Shell}",
                $"Pronouns   : {Pronouns}",
                $"Location   : {Location}",
                $"Frameworks : {string.Join(", ", Frameworks)}",
                $"Languages  : {string.Join(", ", Languages)}",
                $"Learning   : {string.Join(", ", Learning)}",
                $"Hobbies    : {string.Join(", ", Hobbies)}",
                $"Commits    : {Commits}",
                $"Stars      : {Stars}",
                $"Discord    : {Discord}",
                $"Daily Tools: {string.Join(", ", DailyTools)}"
            };

            int maxLength = lines.Max(l => l.Length);
            int totalWidth = maxLength + 4; // 2 espaços + 2 bordas
            string horizontal = new string('═', totalWidth - 2);

            Console.WriteLine($"╔{horizontal}╗");
            foreach (string line in lines)
                Console.WriteLine($"║ {line.PadRight(maxLength)} ║");
            Console.WriteLine($"╚{horizontal}╝");
        }
    }

    public static class Program
    {
        public static void Main()
        {
            new DeveloperProfile().PrintProfile();
        }
    }
}
```

### 🖥️ Saída esperada

```
╔══════════════════════════════════════════════════════════════╗
║ Username   : anordinaryusername                              ║
║ Platform   : GitHub                                          ║
║ OS         : Arch Linux x86_64                               ║
║ Shell      : zsh 5.8                                         ║
║ Pronouns   : He/Him                                          ║
║ Location   : Artesia, CA                                     ║
║ Frameworks : React                                           ║
║ Languages  : JavaScript, TypeScript, HTML, CSS               ║
║ Learning   : Node.js, Express, PostgreSQL, Three.js, CPP     ║
║ Hobbies    : Gardening, Cooking, Gaming                      ║
║ Commits    : 968                                             ║
║ Stars      : 14                                              ║
║ Discord    : RandomPotato#1377                               ║
║ Daily Tools: .php, .js, .html, .css, .svg, .psd, .ai         ║
╚══════════════════════════════════════════════════════════════╝
```

> [!TIP]
> Lembre-se: o computador faz exatamente o que você manda, não o que você quer.
