
![ alt text](https://img.shields.io/twitter/follow/xRadeCoding?logo=twitter&amp;style=for-the-badge)
![Count](https://komarev.com/ghpvc/?username=xRadeCoding&color=brightgreen)

```Java
public class Kenji extends GitHubUser {

    public Kenji() {
        super("xRadeCoding", "The Belgium");
        this.addLanguage("Java", "Python", "C", "C++", "C#", "Javascript", "LUA", "PHP", "HTML", "Sass",  "CSS", "Typescript", "Ruby", "Kotlin", "GO", "Rust");
        this.addOperatingSystem("Windows","Kali Linux","Ubuntu");
        this.addExperience("ZortusRP", "SaturnusMC", "GappleNetwork, ZoutePopcorn", "AvantisRP", "Tedeapolis");
    }
}

public abstract class GitHubUser {

    @Getter private final String username;
    @Getter private final String country;

    private Set<String> languages = new HashSet<>();
    private Set<String> operatingSystem = new HashSet<>();
    private Set<String> experiences = new HashSet<>();

    public GitHubUser(String username, String country) {
        this.username = username;
        this.country = country;
    }

    public void addLanguage(String... language) {
        Collections.addAll(this.languages, language);
    }

    public void addOperatingSystem(String... operatingSystem) {
        Collections.addAll(this.operatingSystem, operatingSystem);
    }

    public void addExperience(String... experience) {
        Collections.addAll(this.experiences, experience);
    }
}
```
![Github stats](https://github-readme-stats.vercel.app/api?username=xRadeCoding&amp;theme=dark&ampg&show_icons=true&include_all_commits=true&locale=nl&count_private=true)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=xRadeCoding&amp;theme=dark)](https://github.com/xRadeCoding/xRadeCoding)

