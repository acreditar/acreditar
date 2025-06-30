


```csharp
public static void Main(){
    var voortex = new SoftwareDeveloper(){
    
        nickName = "VoorTex",
        myHobbies = "Coding, Watch Anime, Play Games and studying"
        };
    var skills = new Skills(){
        
        languages = new[] { "C#", "JavaScript", "Python" },
        interests = new[] { "functional programming", "pentest"},
        technologies = new[] { "Linux", "GitHub", "Vscode" }
        };
        voortex.SetSkill(skills);
}
    
```




